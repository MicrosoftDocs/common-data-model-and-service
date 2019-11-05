---
title: Document Collection | Microsoft Docs
description: API reference for CdmDocumentCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Document Collection

A document collection extends [Collection](collection.md) and adds additional behaviors specific to document collections.

```
public class CdmDocumentCollection extends CdmCollection<CdmDocumentDefinition>
```

## Constructors
|Name|Description|
|---|---|
|**CdmDocumentCollection(CdmCorpusContext, [CdmFolderDefinition](folder.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The folder that contains this collection.|Initializes a new instance of the [CdmDocumentCollection](documentcollection.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Add([CdmDocumentDefinition](document.md))**<br/>*document*: The document to add to the collection.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Adds the specified document to the collection. Returns the document that was added to the collection.|[CdmDocumentDefinition](document.md)|
|**Add([CdmDocumentDefinition](document.md), string)**<br/>*document*: The document to add to the collection.<br/>*documentName*: The name of the document.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Adds the specified document to the collection and sets its name to be the specified name. Returns the document that was added to the collection.|[CdmDocumentDefinition](document.md)|
|**Add(string, bool)**<br/>*name*: The name of the document to add to the collection.<br/>*simpleRef [optional]*: This parameter is unused. It is kept just for consistency with other CDM collections.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates a document with the specified name and adds it to the collection. Returns the document that was added to the collection.|[CdmDocumentDefinition](document.md)|
|**AddRange(IEnumerable\<[CdmDocumentDefinition](document.md)>)**<br/>*documents*: The list of documents to add.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of documents to the collection.|void|
|**Insert(int, [CdmDocumentDefinition](document.md))**<br/>*index*: The index to insert the document at.<br/>*document*: The document to add to the collection.|Inserts the document into the collection at the specified index.|void|
|**Remove([CdmDocumentDefinition](document.md))**<br/>*document*: The document to remove from the collection.|Removes the specified document from the collection. Returns true if the operation is successful, false otherwise.|bool|
|**Remove(string)**<br/>*name*: The name of the document to remove from the collection.|Removes the document with the specified name from the collection. Returns true if the operation is successful, false otherwise.|bool|
|**RemoveAt(int)**<br/>*index*: The index of the document to remove.|Removes the document at the specified index from the collection.|void|
|**Clear()**|Empties the collection.|void|
