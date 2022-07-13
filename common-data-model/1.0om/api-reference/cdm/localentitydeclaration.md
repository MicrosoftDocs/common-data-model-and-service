---
title: Local Entity Declaration | Microsoft Docs
description: API reference for CdmLocalEntityDeclarationDefinition.
author: jinichu

ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Local Entity Declaration 

A local entity declaration is a declaration of an entity that resides locally and has associated [data partitions](datapartition.md).

```csharp
public class CdmLocalEntityDeclarationDefinition extends CdmObjectDefinitionBase, CdmEntityDeclarationDefinition
```
*CdmLocalEntityDeclarationDefinition extends CdmEntityDeclarationDefinition in Python.*<br/>
*CdmLocalEntityDeclarationDefinition extends CdmObjectDefinitionBase, CdmFileStatus in TypeScript.*

## Constructors
|Name|Description|
|---|---|
|**CdmLocalEntityDeclarationDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*entityName*: The entity's name.|Initializes a new instance of the [CdmLocalEntityDeclarationDefinition](localentitydeclaration.md) class.|

## Properties
|Name|Type|Description|SDK|
|---|---|---|---|
|EntityName|string|The entity's name.|1.0|
|EntityPath|string|The corpus path to the entity definition.|1.0|
|DataPartitions|[CdmCollection](collection.md)\<[CdmDataPartitionDefinition](datapartition.md)>|The data partitions.|1.0|
|DataPartitionPatterns|[CdmCollection](collection.md)\<[CdmDataPartitionPatternDefinition](datapartitionpattern.md)>|The data partition patterns.|1.0|
|IncrementalPartitions|[CdmCollection](collection.md)\<[CdmDataPartitionDefinition](datapartition.md)>|The incremental partitions.|1.6|
|IncrementalPartitionPatterns|[CdmCollection](collection.md)\<[CdmDataPartitionPatternDefinition](datapartitionpattern.md)>|The incremental partition patterns.|1.6|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|1.0|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the object model.|1.0|
|LastChildFileModifiedTime|DateTimeOffset?|The greatest last time reported by any of the children objects about their file status check times.|1.0|


## Methods
|Name|Description|Return Type|SDK|
|---|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|1.0|
|**FileStatusCheckAsync([PartitionFileStatusCheckType](partitionfilestatuscheckType.md), [CdmIncrementalPartitionType](cdmincrementalpartitiontype.md))**<br/>*partitionFileStatusCheckType [optional]*: An enum value that denotes the type of partition objects and partition pattern objects to update. The default value is `PartitionFileStatusCheckType.Full`. <br/>*incrementalType [optional]*: An enum value that denotes what type of incremental partition objects and incremental partition pattern objects to update. The default value is `CdmIncrementalPartitionType.None`.|Updates the object and its children, if any, with the current time. `PartitionFileStatusCheckType` and `CdmIncrementalPartitionType` allow users to have better control of which data partition or/and data partition pattern updates should be performed.|Task|1.6|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|1.0|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|1.0|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|1.0|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|1.0|
