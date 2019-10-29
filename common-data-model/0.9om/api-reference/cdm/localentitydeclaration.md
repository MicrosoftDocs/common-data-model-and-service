---
title: Local Entity Declaration - Common Data Model | Microsoft Docs
description: API reference for CdmLocalEntityDeclarationDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Local Entity Declaration 

A local entity declaration is a declaration of an entity that resides locally and has associated [data partitions](datapartition.md).

```
public class CdmLocalEntityDeclarationDefinition extends CdmObjectDefinitionBase, CdmEntityDeclarationDefinition
```
*CdmLocalEntityDeclarationDefinition extends CdmEntityDeclarationDefinition in Python.*

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
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the OM.|
|LastChildFileModifiedTime|DateTimeOffset?|The greatest last time reported by any of the children objects about their file status check times.|


## Methods
|Name|Description|Return Type|
|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

