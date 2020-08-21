---
title: Data Partition | Microsoft Docs
description: API reference for CdmDataPartitionDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Data Partition

A data partition is an object pointing to a location of entity-related data.

```csharp
public class CdmDataPartitionDefinition extends CdmObjectDefinitionBase, CdmFileStatus
```
*CdmDataPartitionDefinition extends CdmObjectDefinition, CdmFileStatus in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmDataPartitionDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The data partition's name.|Initializes a new instance of the [CdmDataPartitionDefinition](datapartition.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The data partition's name.|
|Description|string|The data partition's description.|
|Location|string|The corpus path to the data partition's location.|
|Inferred|bool|Denotes whether the data partition was created from a data partition pattern.|
|Arguments|Dictionary\<string, List\<string>>|The dictionary of argument names to argument values. If this data partition was created from a data partition pattern, then the argument names will match the parameters specified in the data partition pattern, and the values will be those discovered from the pattern's regular expression.|
|SpecializedSchema|string|The path of the specialized schema to use specifically for the data partitions generated (for example, *CSV*).|
|RefreshTime|DateTimeOffset?|The data partition's refresh time.|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the object model.|
|LastChildFileModifiedTime|DateTimeOffset?|The greatest last time reported by any of the children objects about their file status check times.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

