---
title: CDM metadata format | Microsoft Docs
description: "Provides information about how you can use the Common Data Model to develop apps and solutions."
author: theresapalmer
ms.service: commondatamodel
ms.reviewer: anneta
ms.topic: article
ms.date: 11/21/2019
ms.author: tpalmer
---

# CDM metadata file - model.json

The metadata file or model.json of a CDM folder describes the data in the CDM folder, metadata and location, as well as how it was generated and by which data producer.
  
The model file enables:
- Discoverability based on data producer metadata
- Obtaining semantic information about entity records / attributes, links to underlying data files, 
- Indicates compliance with CDM Standard Entities
- Information about when entities have been updated last

![Model.json in CDM folder structure](media/cdm-folder.png)

Download the json schema of the model.json file [here](https://aka.ms/AA39f6l).

## Model file contents
 
The CDM folder contents is described by a standardized metadata JSON file, containing the following key categories of metadata:

- Root elements
    - Overall CDM folder metadata applicable to all entities within the folder, such as description, last modified time, data culture
- Entity information
    - General metadata such as type, description, etc.
    - Attributes, including attribute metadata such as data types
    - [optional] Compliance with CDM Standard Entity schema shapes
        - For example, a given entity in the folder might be compliant with all the attributes required for a ‘base’ Account entity 
    - Data file (partition) locations, and metadata about data encoding of data files
- Reference models
    - Existing entities and datafiles that this model.json file refers to
- Relationships 
    - Describes the relationships among the entities

In addition to the standard elements, additional producer-specific elements or extensions can be added with a prefix, such as “pbi:mashup” where “pbi:” is the prefix. Consumers can ignore these fields but the libraries will roundtrip the fields to ensure no loss of fidelity. 

The following sections describes each standard category in more detail. 

### Root properties

These properties are listed at the root of the model.json file and describe properties relevant to all entities, relationship, etc. 


| Property | Type | Description | Required? |
| ---------------- |---------------- |-------------------------------- |------------- |
| application | string | The name of the producing application. A consumer uses this to identify which application created the model.json file.  | No | 
| name | string | The model name | Yes | 
| description | string | The model description | No | 
| version | string (enum) | The model schema version (currently must be 1.0) | Yes | 
| culture | string | An (IETF language tag)[] representing the language and country, supported by Windows and .NET (i.e. "en-US"). This value should be used to parse datatypes that can be culture sensitive such as datetimes, numbers etc. When not set, the datatype formats should match the [non-specified culture formats](#non-specified-culture) defined below. | No | 
| modifiedTime | datetimeoffset |The last time the model definition was updated in ISO 8601. | No | 
| isHidden | boolean | Whether or not this model is hidden. If set to 'true', this model is not intended for other applications to consumer. | No |
| [annotations](#annotations) | Annotation[] | Array of optional model annotations - non essential of key/value pairs containing contextual information that can be used to store additional context | No | 
| [entities](#entities) | Entity[] | The model entities | Yes | 
| [referenceModels](#reference-models) | ReferenceModel[] | References to other used/extended models | No | 
| [relationships](#relationships) | Relationship[] | Relationships between entities in the model relationships can be from/to local or reference entities. When the relationship involves reference entity, the attributes needs to be resolved from the local entity in the referenced model | No | 

Sample:
<pre>
{   
    "application": "MyApplication",  
    "name": "OrdersProducts",  
    "description": "Model containing data for Order and Products.",  
    "version": "1.0",  
    "modifiedTime": 2018-01-02T12:00:00+08:00,  
    "name": "OrdersProducts",  
    "annotations": [ ],  
    "entities": [ ],  
    "referenceModels": [ ]  
}  
</pre>

### Annotations

Property name: **annotations**

Optional, non-essential contextual information (key/value pairs) that can be used to store additional context about a properties in the model file. Annotations can be applied at multiple levels including to entities and attributes. Producers can add a prefix, such as “pbi:MappingDisplayHint” where “pbi:” is the prefix, when annotations are not necessarily relevant to other consumers. 

| Property | Type | Description | Required? | 
| ---------------- |---------------- |-------------------------------- |------------- |
| name | string |  Name of the annotation | Yes | 
| value | string |  Value of the annotation | No | 

Sample:
<pre>
    "annotations": [
        {
            "name": "MyApp:VersionNum",
            "value": "3.0.1"
        }
    ]
</pre>


### Reference Models

Property name: **referenceModels**

Reference models are existing model.json files with entities and datafiles defined that this model.json file refers to. This allows existing metadata and data to be reused without copying it into this CDM folder.

| Property | Type | Description | Required? | 
| ---------------- |---------------- |-------------------------------- |------------- |
| id | string | The id of the referenced model to be used within this model.json file. This value must be unique within this model file and can be used as a shorthand to the location property. The specific value is up to the implementer. | Yes | 
|location | URI | The location the model being referenced. The URI should include the model version/snapshot that this model is consistent with (it is expected that when this model is refreshed it will update the version/snapshot accordingly)  | Yes | 

Sample:
<pre>
    "referenceModels": [
        {
            "id": "f19bbb97-c031-441a-8bd1-61b9181c0b83 ",
            "location": "https://contosostorageaccount.dfs.core.windows.net/contosoFilesystem/cdmFolder/model.json"
        }
    ]
</pre>

### Entities

Property name: **entities**

An entity is a collection of attributes and metadata that defines a concept like Account or Contact and can be defined by any data producer. An entity may match the schema of a  standard entity, defined as part of the Common Data Model and listed in the GitHub repo: https://aka.ms/cdmrepo. Entities that don’t match one of the standard shapes are said to be custom entities.

Within the model.json file there are two type of entities you can specify, Local and Reference entities. A **local entity** has the details about the entity (attributes, schemas, partitions, etc.) defined within the model.json file and the data files are expected to be within the same CDM folder. A **referenced entity** is pointer to an entity defined by a referenced model, where all the metadata and data files are defined.

Depending on the type of entity, you may find different fields defined:

|Property | Local entity | Reference entity | 
|------------ | ---------- | ----------| 
|$type | R | R | 
|name | R | R | 
|description | O | O | 
|annotations | O | O | 
|schemas | O |  | 
|attributes | R |  | 
|partitions | O |  | 
|source |  | R | 
|modelId |  | R | 

R - required, O - optional, (blank) – n/a

#### Entity level properties
In the required columns, “n/a” means the field shouldn’t exist for that type of entity. 

|Property | Type | Description | LocalEntity Required? | ReferencedEntity Required? |
| ---------------- |---------------- |-------------------------------- |------------- | ------------- | 
|$type | Constant | Type of entity being defined in this model. This attribute must be set to:  “LocalEntity”. | Yes | Yes | 
|name | string | The entity name | Yes | Yes | 
|description | string | The entity description | No | No | 
|[annotations](#annotations) | Annotation[] | Array of optional model annotations - non essential of key/value pairs containing contextual information that can be used to store additional context | No | No | 
|schemas | SchemaURI[] | A collection of URIs to the schema definitions the entity conforms to. <br> Allowed pattern: https://raw.githubusercontent.com/Microsoft/CDM/master/schemaDocuments/<CDM folder hiearchy>/<entity name>.<entity version>.cdm.json  <br>Example: https://raw.githubusercontent.com/Microsoft/CDM/master/schemaDocuments/core/applicationCommon/Account.0.8.cdm.json | No | n/a | 
|[attributes](#attributes) | Attribute[] |  The attributes within the entity. Each entity must have at least one | Yes | n/a | 
|[partitions](#partitions) | Partition[] | The entity physical partitions (data files) | No | n/a | 
|source | String | The source (referenced) entity name | n/a | Yes | 
|modelId | String | The source (referenced) model id, must match the id of one of the model’s referenceModels | n/a | Yes | 

LocalEntity Sample:
<pre>
    "entities": [
        {
            "$type": "LocalEntity",
            "name": "Products",
            "description": "Information about products and their pricing information.",
            "annotations": [ ]
            "attributes": [ ],
            "partitions": [ ],
            "schemas": [
"https://raw.githubusercontent.com/Microsoft/CDM/master/schemaDocuments/core/applicationCommon/foundationCommon/Product.0.7.cdm.json"
            ]
        }
    ]
</pre>

ReferencedEntity Sample:
<pre>
    "entities": [
        {
            "$type": "ReferenceEntity",
            "name": "Products",
            "description": "Information about products and their pricing information.",
            "source": "Products",
            "modelId": "f19bbb97-c031-441a-8bd1-61b9181c0b83",
            "annotations": [ ]
        },
    ]
</pre>

#### Attributes

Property name: **attributes**

Attributes are the fields within an entity that corespond to data values within the data file. For example, a Contact entity may have attributes such as First Name, Last Name, etc. 

| Property | Type | Description | Required? | 
| ---------------- |---------------- |-------------------------------- |------------- |
|name | string | the attribute name | Yes | 
|description | string | the attribute description | No | 
|dataType | enum | This attribute should be set to one of:  string, int64, double, dateTime, dateTimeOffset, decimal, boolean, GUID, JSON. If a culture is specified then it should be used to parse the datatype. More details can be found [here](#datatype-formats). | Yes | 
|[annotations](#annotations)  | Annotation[] | Array of optional model annotations - non essential of key/value pairs containing contextual information that can be used to store additional context | No | 

Sample:
<pre>
    "attributes": [
            {
                "name": "productId",
                "description": "The unique identifier of the product.",
                "dataType": "string",
                "annotations": [ ] 
            },
        ]
</pre>

#### Partitions

Property name: **partitions**

The partition array indicates the name and location of the actual data files corresponding to the entity definition. Today, the partition contains a full URI to the location of the data file so new data files need to be manually added to the list of partition. In the future, we’re looking to support patterns of data files (wildcards, etc.)

| Property | Type | Description | Required? | 
| ---------------- |---------------- |-------------------------------- |------------- |
|name | string | the partition name | Yes | 
|description | string | the partition description | No | 
|refreshTime | datetime | the last time the partition data was updated in ISO 8601 | No | 
|location | URI | The partition physical file location, including the file itself. If null, this entity definition is for schema purposes only. | No | 
|fileFormatSettings | FileFormatSettings | Optional file format settings. | No | 

##### File Format Settings

Property name: **fileFormatSettings**

The file format settings provide metadata related to the data files in the partition. Depending on the type, you may find different fields defined although only one type is suppoorted today. 

| Property | Type | Description | CsvFormatSetting Required? | 
| ---------------- |---------------- |-------------------------------- |------------- |
|$type | string (enum) | Defines the type of the file format setting, currently only one value is supported: “CsvFormatSettings” | Yes | 
|columnHeaders | boolean | Indicates whether the CSV file has headers. This attribute should be set to one of: “true”, “false”. If not specified, this can be interpreted as false. | No | 
|delimiter | string | The delimiter type in the CSV file. If not specified, this can be interpreted as “,” | No | 
|quoteStyle | string (enum) | The CSV quote style. This attribute should be set to one of:  “QuoteStyle.Csv”, “QuoteStyle.None”. If not specified, this can be interpreted as “QuoteStyle.Csv”. | No | 
|csvStyle | string (enum) | The CSV style, values: This attribute should be set to one of:  “CsvStyle.QuoteAlways” “CsvStyle.QuoteAfterDelimiter” . By default, this will be set “CsvStyle.QuoteAlways”  | No | 
|encoding | string | The CSV encoding. If not specified, this can be interpreted as “UTF-8” | No  | 

### Relationships

Property name: **relationships**

Relationships describe how entities are connected, such as an Account has a Contact. Today only relationships based on a single attribute in the source and target entities is supported, but more types will be supported in the future.

| Property | Type | Description | SingleKeyRelationship Required? | 
| ---------------- |---------------- |-------------------------------- |------------- |
|$type | string (enum) | Defines the type relationship, currently only one value is supported: “SingleKeyRelationship” | Yes | 
|fromAttribute | [ReferenceAttribute](#referenceattribute) | The object in the source entity (see below) that refers to an attribute in another entity, “toAttribute”. | Yes | 
|toAttribute | [ReferenceAttribute](#referenceattribute) | The object in the destination entity (see below) that is referred to by the “fromAttribute”. | Yes | 
|encoding | string | The CSV encoding. By default, this will be "UTF-8" (which is 65001 in Windows). | No  | 

#### ReferenceAttribute

| Property | Type | Description | Required? | 
| ---------------- |---------------- |-------------------------------- |------------- |
|entityName | string | The entity name in the local model (must exist in the model entities list). | Yes | 
|attributeName | string | The attribute name (for referenced entities need to be resolved from the target entity in the referenced model). | Yes | 

Sample:
<pre>
    "relationships": [
        {
            "$type": " SingleKeyRelationship ",
            "fromAttribute": [ 
                "entityName": "Account",
                "attributeName": "ContactId",
           ],
            "toAttribute": [ 
                "entityName": "Contact",
                "attributeName": "Id",
           ]
        },
    ]
</pre>

## Datatype formats
In general the recommendation is for data producers to leverage datatype formats that are not culture sensitive, such as ISO 8601 for datetime/datetimeoffsets. However, if a data producer writes data with culture-specific formats, the "culture" property must be set in the model.json format and consumers must leverage that value to properly parse the data in the partition files.

### Non-specified Culture
When "culture" is not specified in the model.json, consumers can assume the following data formats:

|Datatype	| Format |	Description|
| ---------------- |---------------- |-------------------------------- |
|datetime	|2018-01-02T12:00:00Z| ISO 8601|
|datetimeoffset|	2018-01-02T12:00:00+08:00|	ISO 8601 with timezone offset. |
|decimal|	1.0 | A decimal number with "." or a period as the decimal separator. |


## Model file attributes
 
We also suggest setting metadata as file properties directly on model.json for effective discovery of data producer metadata by applications. 


|Name	|Required|	Description|
| ---------------- |---------------- |-------------------------------- |
|Application Name	|No	|An application name that is meaningful to a business user and can be shown in a user interface (UI).  |
|Application Instance Name|	No|	An instance name for disambiguation if needed; The value should be meaningful for business user. |
|Model Name|	No|	Same value as the "Name" property inside the [model.json](#root-properties)|

