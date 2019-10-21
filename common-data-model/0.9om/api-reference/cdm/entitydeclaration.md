---
title: Entity Declaration Interface - Common Data Model | Microsoft Docs
description: Reference for CdmEntityDeclarationDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Entity Declaration Interface

An entity declaration is an interface that provides a simple functionality that is extended by a [local entity declaration](localentitydeclaration.md) and a [referenced entity declaration](referencedentitydeclaration.md).

```
public interface CdmEntityDeclarationDefinition extends CdmObjectDefinition, CdmFileStatus
```

## Properties
|Name|Type|Description|
|---|---|---|
|EntityName|string|The entity's name.|
|EntityPath|string|The entity's path, implemented only by LocalEntityDeclaration.|
|DataPartitions|CdmCollection\<CdmDataPartitionDefinition>|The data partitions, implemented only by LocalEntityDeclaration.|
|DataPartitionPatterns|CdmCollection\<CdmDataPartitionPatternDefinition>|The data partition patterns, implemented only by LocalEntityDeclaration.|
|TODO: Update after LastFileStatusCheckTime, LastFileModifiedTime, LastChildFileModifiedTime are moved here|


