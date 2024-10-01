---
title: Entity Collection | Microsoft Docs
description: API reference for CdmEntityCollection.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 10/18/2019
ms.author: jibyun
---

# Entity Collection
An entity collection extends [Collection](collection.md) and adds additional behaviors specific to entity collections.

```csharp
public class CdmEntityCollection extends CdmCollection<CdmEntityDeclarationDefinition>
```

## Constructors
|Name|Description|
|---|---|
**CdmEntityCollection(CdmCorpusContext, [CdmObject](cdmobject.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The object that contains this collection.|Initializes a new instance of the [CdmEntityCollection](entitycollection.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Add([CdmEntityDefinition](entity.md), bool)**<br/>*entity*: The entity definition to use to create the entity declaration.<br/>*simpleRef [optional]*: This parameter is unused. It's kept just for consistency with other Common Data Model collections.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates an entity declaration based on an entity definition and adds it to the collection. Returns the entity declaration that was added to the collection.|[CdmEntityDeclarationDefinition](entitydeclaration.md)|
|**Add(string, string, bool)**<br/>*name*: The name of the entity to add to the collection.<br/>*entityPath*: The entity's path.<br/>*simpleRef [optional]*: This parameter is unused. It's kept just for consistency with other Common Data Model collections.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Adds a new entity to the collection with the specified name and entity path. Returns the entity declaration that was added to the collection.|[CdmEntityDeclarationDefinition](entitydeclaration.md)|
|**AddRange(IEnumerable\<[CdmEntityDefinition](entity.md)>)**<br/>*entityList*: The list of entities to add.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of entities to the collection.|void|
|**Remove([CdmEntityDefinition](entity.md))**<br/>*entityDefToRemove*: The entity whose reference we want to remove from the collection.|Removes the specified entity's entity reference from the collection. Returns true if the operation is successful, false otherwise.|bool|
