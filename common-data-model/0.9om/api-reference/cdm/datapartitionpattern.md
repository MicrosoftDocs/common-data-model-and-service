---
title: Data Partition Pattern - Common Data Model | Microsoft Docs
description: API reference for CdmDataPartitionPatternDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Data Partition Pattern

A data partition pattern provides a way of selecting or generating a set of partitions based on the requirements specified as a regular expression.

```
CdmDataPartitionPatternDefinition extends CdmObjectDefinitionBase, CdmFileStatus
```
*CdmDataPartitionPatternDefinition extends CdmObjectDefinition, CdmFileStatus in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmDataPartitionPatternDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The data partition pattern's name.|Initializes a new instance of the [CdmDataPartitionPatternDefinition](datapartitionpattern.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The data partition pattern's name.|
|RootLocation|string|The starting location's corpus path to use to search for inferred data partitions.|
|RegularExpression|string|The regular expression string to use to search for data partitions.|
|Parameters|List\<string>|The names for the replacement values extracted from the regular expression.|
|SpecializedSchema|string|The corpus path of the specialized schema to use for the matched data partitions (e.g. *CSV*).|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the OM.|
|LastChildFileModifiedTime|DateTimeOffset?|The greatest last time reported by any of the chlidren objects about their file status check times. This property only exists because this class extends CdmFileStatus and will throw a *NotImplementedException* because a data partition pattern object does not contain any children.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

