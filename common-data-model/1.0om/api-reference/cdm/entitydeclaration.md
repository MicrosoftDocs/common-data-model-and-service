---
title: Entity Declaration | Microsoft Docs
description: API reference for CdmEntityDeclarationDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Entity Declaration

An entity declaration provides a simple functionality that's extended by a [local entity declaration](localentitydeclaration.md) and a [referenced entity declaration](referencedentitydeclaration.md).

```csharp
public interface CdmEntityDeclarationDefinition extends CdmObjectDefinition, CdmFileStatus
```
*This interface is substituted with a regular class in Python.*

## Properties
|Name|Type|Description|
|---|---|---|
|EntityName|string|The entity's name.|
|EntityPath|string|The entity's path.|
|DataPartitions|[CdmCollection](collection.md)\<[CdmDataPartitionDefinition](datapartition.md)>|The data partitions, implemented only by [LocalEntityDeclaration](localentitydeclaration.md).|
|DataPartitionPatterns|[CdmCollection](collection.md)\<[CdmDataPartitionPatternDefinition](datapartitionpattern.md)>|The data partition patterns, implemented only by [LocalEntityDeclaration](localentitydeclaration.md).|

