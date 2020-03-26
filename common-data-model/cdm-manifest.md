---
title: Common Data Model metadata - Introducing manifest | Microsoft Docs
description: Common Data Model manifest.
author: oovanesy
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 02/27/2020
ms.author: olegov
---

# Common Data Model metadata: Introducing manifest

In a data lake, a “Common Data Model folder” is a collection, spread over sub-folders or accounts, of the data files and schema description files that constitute a set of related entities that have been organized together for some purpose, such as to back an application or perform analysis. This collection of related data is sometimes called a “solution.” A Common Data Model manifest object and the document containing one (\*.manifest.cdm.json) is an organizing document that acts as an entry point—a “directory” pointing at the pieces making up a the Common Data Model folder. It describes a list of the entities in the solution, documents giving a detailed schema description for each entity, a collection of data partition files for each entity, a list of the known relationships between entities, and potentially other sub-manifest objects that are nested solutions.

Those familiar with the model.json file and format for describing a Common Data Model folder will recognize the manifest as an equivalent but expanded concept. In fact, the Common Data Model object model offers backward compatibility with the model.json format.

A manifest can also be used to organize purely abstract entity definitions as a way of sharing standard schemas. In this form (a “Common Data Model domain”), the manifest will list entities with schema documents, known relationships, and sub-manifests, but will not give data partition file locations for the entities.

A folder may contain multiple manifest documents, each presenting an alternate view or organization of the entities. These views can be used to hide, simplify, or focus the entities of a solution for different personas, or to show different business perspectives. By convention, when there are multiple manifest documents in a folder, the one called “default.manifest.cdm.json” should be used when no specific manifest name is specified.

A manifest document will have the following structure:

-   **Version information**

-   **Imports**

-   **Manifest definition**

    -   **Entity list**

        -   **Local entity declaration**

            -   **Data partition list**

            -   **Data partition pattern list**

        -   **Referenced entity declaration**

    -   **Relationship list**

    -   **Sub-manifest list**

## Imports

Imports are used to specify schema documents that need to be imported first.

Because a manifest will use Common Data Model traits to describe details about data partitions, attributes, etc., most of the time, a single import of `cdm:/foundations.cdm.json` will be sufficient enough to get the standard definitions for these traits.

## Shared concepts inside the manifest

The manifest object and the Common Data Model objects it contains all share some properties and methods.

|Property/Method|Description|
|---|---|
|\*\*\*Name|The name of the object where \*\*\* is the type of the object (for example, ManifestName).|
|Explanation|A string used to document the use or meaning of the object or reference.|
|ExhibitsTraits| A collection of Common Data Model trait references that provide detailed meanings, semantics, usage parameters, or other application specific metadata.|
|[FileStatusCheckAsync()](0.9om/api-reference/cdm/manifest.md#methods)| A method that updates the information about modified times for the files referenced in the model.|
|File status times|See [file status check and modified times](cdm-manifest.md#file-status-check-and-modified-times).|

## Entities

The list of entities in a manifest represent some joint context or purpose, such as the entities used for an application or data analysis project. Some of these entities are “owned” by the manifest—that is, the manifest knows the location of the schema definitions files and all of the data partition files. The owner of the manifest document is responsible for managing that set of data. It's also possible for a manifest to simply ‘borrow’ an entity that is owned by a different manifest. The application that owns the main manifest can write and maintain the data for its owned entities but can only act as a reader for the borrowed entities. An entity listing can be one of two types: a local entity declaration or a referenced entity declaration.

### Local entity declaration

For an entity that is owned by the manifest, the entity declaration describes the location of the schema document where details about the entity metadata, the set of data partition files that contain the data records for the entity, and file location hints that can be used to discover new data partitions, can all be found. The declaration also has the shared features described earlier in the [shared concepts inside the manifest](cdm-manifest.md#shared-concepts-inside-the-manifest) section.

|Property|Description|
|---|---|      
|EntityName|The name of the local (owned) entity.|
|EntityPath|A corpus path to the entity definition in its containing document. <br/><br/>For example, “local:/MyEntity.cdm.json/MyEntity”. By convention, this entity definition should be the "resolved" form of a definition, meaning that any layers of abstraction that would make the definition difficult to interpret has been removed. This is the "default" schema that should be used for any partition file that doesn't offer a specialized alternate schema.|
|DataPartitions|A collection of data partition objects that each describe the location, format, and perhaps specific details about one file that contains data records for the local entity.|
|DataPartitionPatterns|A pattern that describes a search space over a set of files that can be used to infer or discover and list new data partition files. These patterns are used for situations where many new partition files are being regularly added in some structured way and finding or listing them individually is impractical.|

### Data partition

A data partition object describes and points to one particular data file for the entity. Common Data Model traits on this object give detailed information about the file format and parsing options. By default, the data should be interpreted using the schema description indicated by the associated local entity declaration. However, as schemas can change over time and older files may have different content than newer files, an override of the default entity schema can be used for a specific partition file.

Data partitions may be generated at runtime by the object model using a [data partition pattern](cdm-manifest.md#data-partition-pattern). A property indicates if the partition description was generated in-memory or if the description was explicitly created and stored with the folder.

|Property|Description|
|---|---|
|DataPartitionName|An optional name that can be given to the data partition.|
|Location|The corpus path to the data file location.|
|Inferred|A boolean that denotes whether the data partition object was created through the use of a data partition pattern and only exists in-memory in the object model. If set to false, the partition information will be saved with the folder and will override any identical partitions that are inferred in the future.|
|SpecializedSchema|An optional corpus path pointing to an entity definition within a containing document that is specifically for describing this partition as an override of the default shape of data, normally taken from the EntitySchema property of the entity declaration containing this partition.|
|RefreshTime|A place for the application that owns the manifest to store a “refresh” time for the data in the file.|
|Arguments|A mapping of argument names to a value or values associated with that argument. An array of data partition argument objects that hold a set of name/value pairs. If the data partition is generated from a data partition pattern, then these argument names will match the parameters specified on the pattern object, and the values will be those discovered from the regular expression of the pattern.|

#### Data partition specific traits

A data partition's trait collection is used to hold data partition specific settings and behaviors.

|Trait/Parameter|Description|
|---|---|
|is.partition.format.CSV|Indicates a text file with a fixed set of columns with column separators, text qualifiers, etc.|
|columnHeaders|True if the first row of the file contains names for columns.|
|csvStyle|The CSV style, which is always either CsvStyle.QuoteAlways or CsvStyle.QuoteAfterDelimiter. The default is CsvStyle.QuoteAlways.|
|delimiter|The delimiter type in the .csv file.|
|quoteStyle|The quote style, which is always either QuoteStyle.Csv or QuoteStyle.None. The default is QuoteStyle.Csv, meaning that text values are quote delimited.|
|is.partition.format.parquet|The file format settings of a partition parquet file.|
|is.partition.culture|The culture for data formats in the file.|
|culture|The default is “us-en”.|

### Data partition patterns

An entity declaration can specify one or more data partition pattern objects, one for each search pattern that can be used to discover and describe partition files. The use of a pattern (using the Common Data Model object model) may result in dynamically discovered data partition objects in the collection.

|Property|Description|
|---|---|
|RootLocation|A corpus path that acts as the starting location from which the patterns mentioned in the RegularExpression property should be matched, or from which the object model should start when searching for inferred data partitions.|
|RegularExpression|A regular expression that may contain (capture) sub-expressions for the folders and files to seek. This regular expression should describe locations relative to the location given in the RootLocation property. Any captured values should have corresponding (in order) names supplied in the parameters list.|
|Parameters|An array of strings that give names for the replacement values extracted from the regular expression. The order of strings corresponds to the order of (replacement) capture expressions in the RegularExpression property. If a data partition pattern is used to generate inferred partitions, the resulting inferred partition will have a collection of arguments corresponding to these parameter names and the value(s) discovered.|
|SpecializedSchema|An optional corpus path pointing to an entity definition. The path will be used for the SpecializedSchema property for any partitions generated from this pattern. Used when the data partition will have a different schema than the schema that is the default for the containing entity.|

Here are a few examples showing the interplay of RootLocation, RegularExpression, and
Parameters:

#### All .csv files in a specific folder

Make a partition for each ‘Customer’ CSV data file sitting in the *Customer/dataFiles/folder* (relative to the folder where the manifest document exists). Assume there are no sub-directories.

Customer/dataFiles/august.csv

Customer/dataFiles/last-year.csv

Customer/dataFiles/last-year.csv.**backup** (not matched)

|RootLocation|RegularExpression|RegularExpression explanation|Parameters|
|---|---|---|---|
|Customer/dataFiles/|.+\\.csv\$|One or more of any character followed by only ‘.csv’.|None needed|

#### All .csv files in structured folders with information in the file name

Extract the year, month, and cohort number from the file paths and make them arguments.

dataFiles/**2016**/June/cohort001.csv

dataFiles/2016/**June**/cohort002.csv

dataFiles/2017/April/cohort**001**.csv

dataFiles/2017/May/cohort001.csv

|RootLocation|RegularExpression|RegularExpression explanation|Parameters|
|---|---|---|---|
|dataFiles/|(\\d{4})/(\\w+)/ cohort(\\d+)\\.csv\$|Capture 4 digits/capture a word/capture one or more digits after the word 'cohort' but before '.csv'.|Year, month, cohort number|

#### All files in any sub-folder

Extract the file extension.

dataFiles/2016/June/cohort001.csv

dataFiles/2016/June/backups/cohort002.csv

dataFiles/2017/April/cohort001.**txt**

dataFiles/2017/May/cohort001.csv.**save**

|RootLocation|RegularExpression|RegularExpression explanation|Parameters|
|---|---|---|---|
|dataFiles/|.+\\.(\\w+)\$|One or more characters followed by only a ‘.’ and a captured word.|Extension|

#### Order of processing and conflicts

Since one entity can have many partition patterns that use different root locations and different regular expressions, it's possible for the same files to be found by multiple partition patterns. It's also possible for a found partition to conflict with one of the ‘non-inferred’ (explicitly listed) partitions for the entity. When a conflict happens, the following rules will determine which argument values and specialized schema should apply to a new inferred partition:

1.  Inferred partitions will never overwrite an existing non-inferred partition
    on the same entity.

2.  The last pattern processed will take precedence.

### Referenced entity declaration

The reference to an entity owned by a different manifest is nothing more than a name and a location.

|Property|Description|
|---|---|
|EntityName|The name of the referenced entity.|
|EntityPath|A corpus path to the entity declaration in the referenced manifest document.<br/><br/>For example, “remote:/otherSolution/default.manifest.cdm.json/ThatEntity".|

## Sub-manifests

When a set of related manifests form some kind of logical hierarchy, the hierarchy can be described using sub-manifests. A manifest object can indicate a list of sub-manifests. A sub-manifest may be an independent solution but often the entities in a sub-manifest are "aware of", "extensions of", or "built upon" the entities in the manifest(s) that are the "parent" of the sub-manifest.

A manifest has a collection of manifest declarations called SubManifests.

|Property|Description|
|---|---|
|Definition|The corpus path to the sub-manifest’s \*.manifest.cdm.json document.|

## Entity relationships

A manifest may contain a list of the known entity-to-entity relationships involving the entities in the manifest. When data is stored in a lake in relational form, where different entities are stored in separate sets of data partitions, these relationships are expressed in the data through foreign key references in one entity’s partitions that line up with primary key values from another entity.

These entity-to-entity relationship descriptions can be extracted from some external metadata repository and stored in the manifest through some automation, or simply listed in the document through some other means. As an alternative, the Common Data Model object model offers functionality to analyze the logical metadata of the entities in the corpus and populate the discovered relationships for a manifest.

Currently, only single attribute relationships are supported. All relationships are modeled from the many side to the one side—that is, from the referencing entity to the one referenced record in another entity. A “many-to-many” relationship is modeled from the intersection entity, which correlates two “many-to-one” relationships.

|Property|Description|
|---|---|
|FromEntity|A corpus path to the document or entity on the **many** side of the relationship.|
|FromEntityAttribute|The name of the referencing entity attribute, a foreign key.|
|ToEntity|A corpus path to the document or entity on the **one** side of the relationship.|
|ToEntityAttribute|The name of the referenced entity attribute, often the primary key of that entity.|

<br/>

|Method|Description|
|---|---|
|[CdmCorpusDefinition.CalculateEntityGraphAsync(...)](0.9om/api-reference/cdm/corpus.md#methods)|Causes the corpus to calculate and cache knowledge about all entity-to-entity relationships found in the logical entity descriptions for the given manifest, and all of the sub-manifests that it indicates.|
|[CdmManifestDefinition.PopulateManifestRelationshipsAsync(...)](0.9om/api-reference/cdm/manifest.md#methods)|The manifest uses the graph of relationships held in the corpus to create the set of relationship descriptions for any entity that is on either the **one** side or the **many** side of a known relationship.|

## File status check and modified times

The manifest object and the objects it contains collect and report information about the modification times for the files being referenced. The following properties are shared:

|Property|Description|
|---|---|
|LastFileStatusCheckTime|The last time that the status of files and sub-objects was checked. Set directly using application logic or indirectly by the [FileStatusCheckAsync()](0.9om/api-reference/cdm/manifest.md#methods) method.|
|LastFileModifiedTime|The last time reported from the file system about modifications, saving of the files, or objects tracked.|
|LastChildFileModifiedTime|The greatest last time reported by any of the child objects about their file status check times. Since the [FileStatusCheckAsync()](0.9om/api-reference/cdm/manifest.md#methods) method can be called on individual objects, or individual files can be updated at different times, this property will help locate the latest changed child.|

The meanings of these times and the scope of the [FileStatusCheckAsync()](0.9om/api-reference/cdm/manifest.md#methods) method depend upon the specific object.

|Object|FileStatusCheckAsync()|
|---|---|
|Manifest| Checks manifest, all entity declarations, and sub-manifests.|
|Local entity|Checks the schema documents and all data partitions and patterns for the entity.|
|Referenced entity|Checks the remote manifest document.|
|Data partition|Checks the file indicated by the partitions and the optional AlternateSchema document.|
|Data partiton pattern|Invokes the evaluation of the data partition pattern and creation of new partitions.|
|Sub-manifest|Checks the sub-manifest file.|

## Example manifest document

This sample manifest document demonstrates each of the above-mentioned
capabilities for the manifest object:

```json
{
   "manifestName":"MySolution",
   "jsonSchemaSemanticVersion":"0.9.0",
   "imports":[
      {
         "corpusPath":"cdm:/foundations.cdm.json"
      }
   ],
   "lastFileStatusCheckTime":"2019-10-01T02:09:08Z",
   "lastFileModifiedTime":"2019-10-01T02:09:08Z",
   "lastChildFileModifiedTime":"2019-10-01T02:09:08Z",
   "entities":[
      {
         "entityName":"Person",
         "entitySchema":"PersonData/Person.cdm.json/Person",
         "dataPartitions":[
            {
               "location":"PersonData/all-people.csv",
               "exhibitsTraits":[
                  {
                     "traitReference":"is.partition.format.CSV",
                     "arguments":[
                        {
                           "name":"columnHeaders",
                           "value":"true"
                        },
                        {
                           "name":"delimiter",
                           "value":","
                        }
                     ]
                  }
               ]
            }
         ]
      },
      {
         "entityName":"EmailMessage",
         "entityPath":"EmailMessageData/EmailMessage.cdm.json/EmailMessage",
         "dataPartitions":[
            {
               "location":"EmailMessageData/Sep/emails.csv",
               "exhibitsTraits":[],
               "arguments":[
                  {
                     "month":[
                        "Sep"
                     ]
                  }
               ],
               "lastFileStatusCheckTime":"2019-10-01T02:09:08Z",
               "lastFileModifiedTime":"2019-09-01T02:19:06Z"
            },
            {
               "location":"EmailMessageData/Oct/emails.csv",
               "exhibitsTraits":[],
               "arguments":[
                  {
                     "month":[
                        "Oct"
                     ]
                  }
               ],
               "lastFileStatusCheckTime":"2019-10-01T02:09:08Z",
               "lastFileModifiedTime":"2019-10-01T02:09:08Z"
            }
         ],
         "dataPartitionPatterns":[
            {
               "name":"EmailByMonth",
               "rootLocation":"EmailMessageData/",
               // This pattern is what describes the partitions found above 
               "regularExpression":"(\\\\w{3})/emails.csv)",
               "parameters":[
                  "month"
               ]
            }
         ],
         "lastFileStatusCheckTime":"2019-10-01T02:09:08Z",
         "lastFileModifiedTime":"2019-09-27T02:09:08.149Z",
         "lastChildFileModifiedTime":"2019-09-27T02:09:08.149Z"
      },
      {
         // This is a referenced entity declaration. 
         // We are just pointing at another manifest and entity.
         "entityName":"FrequentPairs",
         "explanation":"Borrow the analysis of frequent email pairs from that project",
         "entityPath":"networkProject/NetworkAnalysis.manifest.cdm.json/FrequentPairs"
      }
   ],
   "relationships":[
      // A relationship between the entities.
      {
         "fromEntity":"EmailMessageData/EmailMessage.cdm.json/EmailMessage",
         "fromEntityAttribute":"ownerId",
         "toEntity":"PersonData/Person.cdm.json/Person",
         "toEntityAttribute":"personId"
      }
   ],
   "submanifests":[
      // This sub-manifest is independent but described here so we know it's related
      {
         "name":"NetworkAnalysis",
         "definition":"networkProject/NetworkAnalysis.manifest.cdm.json"
      }
   ]
}
```
