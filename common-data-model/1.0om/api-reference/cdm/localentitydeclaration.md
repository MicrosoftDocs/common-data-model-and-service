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
|Name|Type|Description|
|---|---|---|
|EntityName|string|The entity's name.|
|EntityPath|string|The corpus path to the entity definition.|
|DataPartitions|[CdmCollection](collection.md)\<[CdmDataPartitionDefinition](datapartition.md)>|The data partitions.|
|DataPartitionPatterns|[CdmCollection](collection.md)\<[CdmDataPartitionPatternDefinition](datapartitionpattern.md)>|The data partition patterns.|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the object model.|
|LastChildFileModifiedTime|DateTimeOffset?|The greatest last time reported by any of the children objects about their file status check times.|


## Methods
|Name|Description|Return Type|
|---|---|---|
|**FileStatusCheckAsync()**|Recursively updates the object and its children, if any, with the current time. If this entity declaration contains a data partition pattern, this function will trigger the pattern to be matched against the files on the storage. There will be one data partition per file matching the pattern created on this entity declaration.|Task|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

