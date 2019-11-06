---
title: CdmObject Definition Collection | Microsoft Docs
description: API reference for CdmDefinitionCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# CdmObject Definition Collection

A CdmObject definition collection extends [Collection](collection.md) and adds additional behaviors specific to CdmObject definition collections.

```
public class CdmDefinitionCollection extends CdmCollection<CdmObjectDefinition>
```

## Constructors
|Name|Description|
|---|---|
|**CdmDefinitionCollection(CdmCorpusContext, [CdmDocumentDefinition](document.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The owner of this collection. Must be a document.|Initializes a new instance of the [CdmDefinitionCollection](definitioncollection.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Add([CdmObjectDefinition](cdmobjectdefinition.md))**<br/>*definition*: The object definition to add to the collection.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Adds the specified object definition to the collection. Returns the object definition that was added to the collection.|[CdmObjectDefinition](cdmobjectdefinition.md)|
|**Add(string, bool)**<br/>*name*: The name of the entity to add to the collection.<br/>*simpleRef [optional]*: This parameter is unused. It is kept just for consistency with other CDM collections.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates an entity with the specified name and adds it to the collection. Returns the entity that was added to the collection.|[CdmEntityDefinition](entity.md)|
|**Add(CdmObjectType, string)**<br/>*ofType*: The type of the CDM object to add to the collection.<br/>*name*: The name of the object.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates an object definition of the specified type with the specified name and adds it to the collection. Returns the object definition that was added to the collection.|[CdmObjectDefinition](cdmobjectdefinition.md)|
|**AddRange(IEnumerable\<[CdmDocumentDefinition](document.md)>)**<br/>*objectsList*: The list of object definitions to add.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of object definition to the collection.|void|
|**Insert(int, [CdmObjectDefinition](cdmobjectdefinition.md))**<br/>*index*: The index to insert the object definition at.<br/>*definition*: The object definition to add to the collection.|Inserts the object definition into the collection at the specified index.|void|

