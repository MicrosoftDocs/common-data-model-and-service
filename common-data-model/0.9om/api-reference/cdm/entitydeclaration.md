---
title: Entity Declaration - Common Data Model | Microsoft Docs
description: Reference for CdmEntityDeclarationDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Entity Declaration

An entity declaration is an interface/class that provides a simple functionality that is extended by a [local entity declaration](localentitydeclaration.md) and a [referenced entity declaration](referencedentitydeclaration.md).

```
public interface CdmEntityDeclarationDefinition extends CdmObjectDefinition, CdmFileStatus
```
*CdmEntityDeclarationDefinition is a class in Python.*

## Properties
|Name|Type|Description|
|---|---|---|
|EntityName|string|The entity's name.|
|EntityPath|string|The entity's path, implemented only by [LocalEntityDeclaration](localentitydeclaration.md).|
|DataPartitions|[CdmCollection](collection.md)\<[CdmDataPartitionDefinition](datapartition.md)>|The data partitions, implemented only by [LocalEntityDeclaration](localentitydeclaration.md).|
|DataPartitionPatterns|[CdmCollection](collection.md)\<[CdmDataPartitionPatternDefinition](datapartitionpattern.md)>|The data partition patterns, implemented only by [LocalEntityDeclaration](localentitydeclaration.md).|
|TODO: Update after LastFileStatusCheckTime, LastFileModifiedTime, LastChildFileModifiedTime are moved here|


