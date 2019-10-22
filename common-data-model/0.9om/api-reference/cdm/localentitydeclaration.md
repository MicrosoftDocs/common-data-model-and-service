---
title: Local Entity Declaration - Common Data Model | Microsoft Docs
description: Reference for CdmLocalEntityDeclarationDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Local Entity Declaration 

A local entity declaration is a declaration of an entity that resides locally and has associated data partitions.

```
public class CdmLocalEntityDeclarationDefinition extends CdmObjectDefinitionBase, CdmEntityDeclarationDefinition
```

## Constructors
|Name|Description|
|---|---|
|**CdmLocalEntityDeclarationDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*entityName*: The entity's name.|Initializes a new instance of the CdmLocalEntityDeclarationDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|EntityName|string|The entity's name.|
|EntityPath|string|The entity's path.|
|DataPartitions|[CdmCollection](collection.md)\<[CdmDataPartitionDefinition](datapartition.md)>|The data partitions.|
|DataPartitionPatterns|[CdmCollection](collection.md)\<[CdmDataPartitionPatternDefinition](datapartitionpattern.md)>|The data partition patterns.|
|LastFileStatusCheckTime|DateTimeOffset?|The last time the modified time was checked for this file.|
|LastFileModifiedTime|DateTimeOffset?|The last time this file was modified according to the OM.|
|LastChildFileModifiedTime|DateTimeOffset?|The last time a child file was modified according to the OM.|


## Methods
|Name|Description|Return Type|
|---|---|---|
|**FileStatusCheckAsync()**|Updates the object and its children, if any, with the current time.|Task|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See *CdmObject.Copy(...)*.|[CdmObject](cdmobject.md)|
|**Validate()**|See *CdmObject.Validate()*.|bool|

