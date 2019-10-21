---
title: Entity Collection Class - Common Data Model | Microsoft Docs
description: Reference for CdmEntityCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Entity Collection Class

An entity collection extends [Collection](collection.md) and adds additional behaviors specific to entity collections.

```
public class CdmEntityCollection extends CdmCollection<CdmEntityDeclarationDefinition>
```

## Constructors
|Name|Description|
|---|---|
**CdmEntityCollection(CdmCorpusContext, CdmObject, CdmObjectType)**<br/>*ctx*: The corpus context.<br/>*owner*: The CDM object that contains this collection.<br/>*defaultType*: The default CDM object type of this collection.|Initializes a new instance of the CdmEntityCollection class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|TODO: Update once simpleRef is removed<br/>**Add(CdmEntityDefinition, bool)**<br/>*entity*: The entity definition to use to create the entity declaration.<br/>*simpleRef [optional]*: TODO|Creates an entity declaration based on an entity definition and adds it to the collection.|CdmEntityDeclarationDefinition|
|TODO: Update once simpleRef is removed<br/>**Add(string, string, bool)**<br/>*name*: The entity's name.<br/>*entityPath*: The entity's path.<br/>*simpleRef [optional]*: TODO|Adds a new entity to the collection with the specified name and entity path.|CdmEntityDeclarationDefinition|
|**AddRange(IEnumerable\<CdmEntityDefinition>)**<br/>*entityList*: The list of entities.|Adds the elements of the specified list of entities to the collection.|void|

