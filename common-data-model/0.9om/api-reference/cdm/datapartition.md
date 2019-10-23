---
title: Data Partition - Common Data Model | Microsoft Docs
description: Reference for CdmDataPartitionDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Data Partition

A data partition is an object pointing to a location of entity-related data.

```
public class CdmDataPartitionDefinition extends CdmObjectDefinitionBase, CdmFileStatus
```

## Constructors
|Name|Description|
|---|---|
|**CdmDataPartitionDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The data partition's name.|Initializes a new instance of the CdmDataPartitionDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The data partition's name.|
|Description|string|The data partition's description.|
|Location|string|The data partition's location.|
|Inferred|bool|Denotes whether the data partition was created from a data partition pattern.|
|Arguments|Dictionary\<string, List\<string>>|The list of key-value pairs to give names for the replacement values from the regex.|
|SpecializedSchema|string|The path for the specialized schema to use specifically for the data partitions generated (e.g. *CSV*).|
|RefreshTime|DateTime?|The data partition's refresh time.|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the OM.|
|LastChildFileModifiedTime|DateTimeOffset?|The last time a child file was modified according to the OM.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

