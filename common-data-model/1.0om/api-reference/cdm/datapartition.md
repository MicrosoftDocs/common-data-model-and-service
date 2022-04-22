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
|Name|Type|Description|SDK|
|---|---|---|---|
|Name|string|The data partition's name.|1.0|
|Description|string|The data partition's description.|1.0|
|Location|string|The corpus path to the data partition's location.|1.0|
|Inferred|bool|Denotes whether the data partition was created from a data partition pattern.|1.0|
|IsIncremental|bool|Denotes whether the data partition is incremental.|1.6|
|Arguments|Dictionary\<string, List\<string>>|The dictionary of argument names to argument values. If this data partition was created from a data partition pattern, then the argument names will match the parameters specified in the data partition pattern, and the values will be those discovered from the pattern's regular expression.|1.0|
|SpecializedSchema|string|The path of the specialized schema to use specifically for the data partitions generated (for example, *CSV*).|1.0|
|RefreshTime|DateTimeOffset?|The data partition's refresh time.|1.0|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|1.0|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the object model.|1.0|
|LastChildFileModifiedTime|DateTimeOffset?|The greatest last time reported by any of the children objects about their file status check times.|1.0|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

