---
title: Common Data Model Metadata - introducing Manifest | Microsoft Docs
description: Common data model manifest.
author: oovanesy
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 02/27/2020
ms.author: olegov
---

# Common Data Model Metadata: introducing Manifest


In a data lake, a “Common Data Model Folder” is a collection, spread over
sub-folders or accounts, of the data files and schema description files that
constitute a set of related entities which have been organized together for some
purpose such as to back an application or perform analysis. This collection of
related data is sometimes called a “solution.” A Common Data Model Manifest
object and the document containing one (\*.manifest.cdm.json) is an organizing
document that acts as an entry point, a “directory” pointing at the pieces
making up a the Common Data Model Folder. It describes a list of the entities in
the solution, a document giving a detailed schema description for each entity, a
collection of partition data files for each entity, a list of the known
relationships between entities and potentially other sub-Manifest objects that
are nested solutions.

Those familiar with the model.json file and format for describing a Common Data
Model folder will recognize the manifest as an equivalent but expanded concept.
In fact, the Common Data Model object model offers backward compatibility with
the model.json format.

A Manifest can also be used to organize purely abstract entity definitions as a
way of sharing standard schemas. In this form (a “Common Data Model Domain”),
the Manifest will list entities with schema documents, known relationships and
sub-manifests but will not give partition data file locations for the entities.

A folder might contain many manifest files. Each of them may be presenting
an alternate view or organization of the entities. These views could be used to
hide, simplify, or focus the entities of a solution for different personas or to
show different business perspectives. By convention, when there are multiple
manifest files in a folder, one called “default.manifest.cdm.json” should be
used when no specific manifest name is specified.

A manifest document will have this structure:

-   **Version information**

-   **Imports**

-   **Manifest definition**

    -   **Entity list**

        -   **Local entity declaration**

            -   **Partition list**

            -   **Partition pattern list**

        -   **Referenced entity declaration**

    -   **Relationship list**

    -   **Sub-manifest list**

## Imports


Imports are described in the “Technical Details” section upfront.

Because a manifest will use Common Data Model traits (explained later) to
describe details about data partitions, etc. Most of the time, the single import
of `Cdm:/foundations.cdm.json` will have the standard definitions for these traits.

## Shared concepts inside the manifest

The Manifest object and the objects it contains all share some properties,
collections, and abilities (methods in the object moel).

| Property / Method | Description                                                                                                                                                                     |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| \*\*\*Name        | The name of the object where \*\*\* is the type of object                                                                                                                       |
| Explanation       | A string used to document the use or meaning of the object or reference                                                                                                         |
| exhibitsTraits    | A collection of Common Data Model trait references (detail on traits later) that provide detailed meanings, semantics, usage parameters or other application specific metadata. |
| fileStatusCheck   | A method that updates the information about modified times for files referenced in the model.                                                                                   |
| fileStatus times  | Details at end of Manifest explanation                                                                                                                                          |

## Entities

The list of entities in a manifest represent some joint context or purpose, such
as the entities used for an application or data analysis project. Some of these
entities are “owned” by the manifest, that is, the manifest knows the location
of the schema definitions files and all of the partition data files and the
owner of the manifest document is responsible for managing that set of data. It
is also possible for a manifest to simply ‘borrow’ an entity that is owned by a
different manifest. The application that owns the main manifest can write and
maintain the data for its owned entities but can only act as a reader for the
borrowed entities. The two types of entity listings are called the
localEntityDeclaration and the referenceEntityDeclaration.

### Local entity declaration

For an entity that is owned by the manifest, the declaration describes the
location of the schema document where details about the entity metadata can be
found, the set of data partition files that contain the data records for the
entity and some file location hints that can be used to discover new data
partitions. The declaration also has the shared features described later in the
manifest section.

| Property / Method     | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| entityName            | The name of the owned entity                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| entityPath            | A corpus path to the entity definition within its containing document. For example, “local:/MyEntity.cdm.json/MyEntity”. By convention, this entity definition should be the ‘resolved’ form of a definition (see section on resolving entity schemas later, but in short a resolved definition has removed any layers of abstraction that would make the definition difficult to interpret.) This is the ‘default’ schema that should be used for any partition file that does not offer a specialized alternate schema. |
| dataPartitions        | The data partition objects in this collection each describe the location, format and perhaps specific details about of one file that contains data records for the local entity.                                                                                                                                   |
| dataPartitionPatterns | A data partition pattern describes a search space over a set of files that can be used to infer or discover and list new data partition files. These patterns are used for situations where many new partition files are being regularly added in some structured way and finding / listing them individually is impractical.                                                                                                                                                                                             |

### Data Partition Defs in the dataPartitions collection

A Data Partition Definition (Def) object describes and points to one particular
file of data for the entity. Common Data Model Traits (explained later) on this
object give detailed information about the file format and parsing options. By
default, the data should be interpreted using the schema description indicated
by the associated Local Entity Declaration. However, because schemas can change
over time and older files may have different content than newer files, an
override of the default entity schema can be used for a specific partition file.

Data Partition Definitions may be generated at runtime by the object model using
a dataPartitionPattern. A property indicates if the partition description was
generated in memory or if the description was explicitly created and stored with
the folder.

| Property / Method | Description                                                                                                                                                                                                                                                                                                                                                                                |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| dataPartitionName | An optional name that can be given to the partition                                                                                                                                                                                                                                                                                                                                        |
| Location          | The corpus path to the data file location and name                                                                                                                                                                                                                                                                                                                                         |
| Inferred          | Boolean. True if the partition object was created through use of a dataPartitionPattern and only exists in the OM’s memory. If set to false, the partition information will be saved with the folder and will override any identical partitions that are inferred in the future                                                                                                            |
| specializedSchema | An optional corpus path pointing to an entity definition within a containing document that is specifically for describing this partition as an override of the default shape of data that is normally taken from the entitySchema property of the for the entity declaration containing this partition.                                                                                    |
| refreshTime       | A place for the application that owns the manifest to store a “refresh” time for the data in the file.                                                                                                                                                                                                                                                                                     |
| Arguments         | A mapping from argument names to a value or values associated with that argument. An array of partitionArgument objects that hold a set of name/value pairs. If the partition is generated from a partitionPattern, then these argument names will match the parameters specified on the pattern object and the values will be those discovered from the regular expression of the pattern |

#### Data partition specific traits

The traits collection for a partition is used to hold partition type specific
settings and behaviors

| Trait / parameter           | Description                                                                                                                |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------|
| is.partition.format.CSV     | Indicates a text file with a fixed set of columns with column separators, text qualifiers, etc.                            |
| columnHeaders               | True if the first row of the file contains names for columns                                                               |
| csvStyle                    | The CSV style which is always CsvStyle.QuoteAlways or CsvStyle.QuoteAfterDelimiter. Default is QuoteAlways                 |
| delimiter                   | The delimiter type in the .csv file.                                                                                       |
| quoteStyle                  | the quote style which is always QuoteStyle.Csv or QuoteStyle.None. Default is Csv meaning text values are quote delimited. |
| is.partition.format.parquet |                                                                                                                            |
| is.partition.culture        | The culture for data formats in the file                                                                                   |
| culture                     | Default is “us-en”                                                                                                         |

### Data Partition Patterns

An entity declaration can specify one or more dataPartitionPattern objects, one
for each search pattern that can be used to discover and describe partition
files. Use of a pattern may result (using the Common Data Model OM) in
dynamically discovered dataPartition objects in that collection.

| Property / Method | Description                                                                                                                                                                                                                                                                                                                                                                                                                     |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| rootLocation      | A corpus path that acts as the starting location from which the patterns mentioned in the regularExpression property should be matched or from which the OM should start when searching for inferred data partitions.                                                                                                                                                                                                           |
| regularExpression | A regular expression that may contain (capture) sub-expressions for the folders and files to seek. This regular expression should describe locations relative to the location given in the rootLocation property value. Any captured values should have corresponding (in order) names supplied in the parameters list,                                                                                                         |
| Parameters        | An array of string that give names for the replacement values extracted from the regular expression. The order of strings corresponds to the order of (replacement) capture expressions in the regularExpression. If a data partition pattern is used to generate inferred partitions, the resulting inferred partition will have a collection of arguments corresponding to these parameter names and the value(s) discovered. |
| specializedSchema | Optional. A corpus path pointing to an entity definition. The path will be used for the specializedSchema property for any partitions generated from this pattern. Used when the partition data will have a different schema than the schema which is the default for the containing entity.                                                                                                                                    |

A few examples showing the interplay of rootLocation, regularExpression and
parameter should help.

#### All .csv files in a specific folder

Make a partition for each ‘Customer’ CSV data file sitting in the
Customer/dataFiles/ folder (that is relative to the folder where the manifest
document exists). Assuming there are no sub directories.

Customer/dataFiles/august.csv

Customer/dataFiles/last-year.csv

Customer/dataFiles/last-year.csv.**backup** (Not matched)

| rootLocation        | regularExpression | explained                                            | parameters  |
|---------------------|-------------------|------------------------------------------------------|-------------|
| Customer/dataFiles/ | .+\\.csv\$        | One or more of any character followed by only ‘.csv’ | none needed |

#### All csv files in structured folders with information in file name

Extract the year, month and cohort number from the file paths and make them
arguments

dataFiles/**2016**/June/cohort001.csv

dataFiles/2016/**June**/cohort002.csv

dataFiles/2017/April/cohort**001**.csv

dataFiles/2017/May/cohort001.csv

| rootLocation | regularExpression                     | explained                                                                                            | parameters                |
|--------------|---------------------------------------|------------------------------------------------------------------------------------------------------|---------------------------|
| dataFiles/   | (\\d{4})/(\\w+)/ cohort(\\d+)\\.csv\$ | Capture 4 digits / capture a word / capture one or more digits after the word cohort but before .csv | Year, month, cohortNumber |

#### All files in any sub folder

Extract the file extension.

dataFiles/2016/June/cohort001.csv

dataFiles/2016/June/backups/cohort002.csv

dataFiles/2017/April/cohort001.**txt**

dataFiles/2017/May/cohort001.csv.**save**

| rootLocation | regularExpression | explained                                                         | parameters |
|--------------|-------------------|-------------------------------------------------------------------|------------|
| dataFiles/   | .+\\.(\\w+)\$     | One or more characters followed by only a ‘.’ and a captured word | extension  |

#### Order of processing and conflicts

Since one entity can have many partition patterns that use different root
locations and different regular expressions, it is possible for the same files
to be found by multiple partition patterns. It is also possible for a found
partition to conflict with one of the ‘non-inferred’ (AKA explicitly listed)
partitions for the entity. When a conflict happens, the following rules will
determine which argument values and specialized schema should apply to a new
inferred partition

1.  Inferred partitions will never overwrite an existing non-inferred partition
    on the same entity

2.  The last pattern processed will take precedence.

### Referenced Entity Declaration

The reference to an entity owned by a different manifest is nothing more than a
name and a location.

| Property / Method | Description                                                                                                                                                |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| entityName        | The name of the referenced entity                                                                                                                          |
| entityPath        | A corpus path to the entity declaration within the referenced manifest document. For example, “remote:/otherSolution/default.manifest.cdm.json/ThatEntity” |

## Sub-Manifests


When a set of related manifests form some kind of logical hierarchy, the
hierarchy can be described using sub-manifests. A manifest object can indicate a
list of sub-manifests. A sub-manifest may be an independent solution but often
the entities in a sub-manifest are ‘aware of’, ‘extensions of’ or ‘built upon’
the entities in the manifest(s) that are ‘parent’ of the sub-manifest.

A manifest has a collection, called subManifests, of Manifest Declarations

| Property / Method | Description                                                         |
|-------------------|---------------------------------------------------------------------|
| Definition        | The corpus path to the sub-manifest’s \*.manifest.cdm.json document |

## Entity relationships


A manifest may contain a list of the known entity to entity relationships
involving entities in the manifest. When data is stored in a lake in a
relational form, where different entities are stored in separate sets of data
partitions, these relationships are expressed in the data through foreign key
references in one entity’s partitions that that line up with primary key values
from another entity.

These entity to entity relationship descriptions can be extracted from some
external metadata repository and stored in the manifest through some automation
or simply listed in the document through some other means. As an alternative,
the Common Data Model object model offers functions that analyze the logical
metadata of the entities in the corpus and populates the discovered
relationships for a manifest.

Currently, only single attribute relationships are supported. All relationships
are modeled from the many side to the one side, that is from the referencing
entity to the one referenced record in another entity. A “many to many”
relationship is modeled from the intersection entity which correlates two “many
to one” relationships.

| Property                                                   | Description                                                                                                                                                                                                        |
|------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| fromEntity                                                 | A corpus path to the document/entity on the MANY side of the relationship.                                                                                                                                         |
| fromEntityAttribute                                        | The name of the referencing attribute, a foreign key                                                                                                                                                               |
| toEntity                                                   | A corpus path to the documents/entity on the ONE side of the relationship.                                                                                                                                         |
| toEntityAttribute                                          | The name of the referenced attribute, often the primary key of that entity.                                                                                                                                        |
| Method                                                     | Description                                                                                                                                                                                                        |
| Corpus.CalculateEntityGraph(ICdmManifestDef rootManifest); | Causes the corpus to calculate and cache knowledge about all of the entity to entity relationships found in the logical entity descriptions for the given manifest and all of the sub-manifests that it indicates. |
| Manifest. PopulateManifestRelationships()                  | The manifest will use the graph of relationships held in the corpus to create the set of relationship descriptions for any entity that is on either the ONE side or the MANY side of a known relationship.         |

## File status check and modified times


The Manifest object and the objects it contains collect and report information
about the modification times for files being referenced. These properties are
shared:

| Property / Method         | Description                                                                                                                                                                                                                                                                                |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| LastFileStatusCheckTime   | The last time that the status of files and sub-objects was checked. Set directly using application logic or indirectly by the fileStatusCheck method.                                                                                                                                      |
| LastFileModifiedTime      | The last time reported from the file system about modifications / save of the files / objects tracked.                                                                                                                                                                                     |
| LastChildFileModifiedTime | The greatest last time reported by any of the child objects about their file status check times. Since the fileStatusCheck method can be called on individual object or since individual files can be updates at different times, this property will help locate the latest changed child. |

The meaning of these times and the scope of the status check method depend upon
the specific object.

| Object               | fileStatusCheck                                                                       |
|----------------------|---------------------------------------------------------------------------------------|
| Manifest             | Checks manifest, all entity declarations and sub-manifests                            |
| Local entity         | Checks the schema documents and all data partitions and patterns for the entity       |
| Referenced entity    | Checks the status of the remote manifest document                                     |
| dataPartition        | Checks the file indicated by the partitions and the optional alternateSchema document |
| dataPartiton Pattern | Causes evaluation of the data partition pattern search and creation of new partitions |
| Sub-manifest         | Checks file of sub-manifest                                                           |

## Manifest example document


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
   "subManifests":[
      // This sub-manifest is independent but described here so we know it's related
      {
         "name":"NetworkAnalysis",
         "definition":"networkProject/NetworkAnalysis.manifest.cdm.json"
      }
   ]
}
```
