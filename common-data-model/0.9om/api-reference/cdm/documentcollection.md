---
title: Document Collection - Common Data Model | Microsoft Docs
description: Reference for CdmDocumentCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
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

## Properties
|Name|Type|Description|
|---|---|---|
|Owner|[CdmFolderDefinition](folder.md)|The folder that contains this collection.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Add([CdmDocumentDefinition](document.md))**<br/>*document*: The document to add to the collection.|Adds the specified document to the collection.|void|
|**Add(string, bool)**<br/>*name*: The name of the document to add to the collection.<br/>*simpleRef [optional]*: TODO. The default value is false.|Creates a document with the specified name and adds it to the collection. Returns the document that was added to the collection.|[CdmDocumentDefinition](document.md)|
|**AddRange(IEnumerable\<[CdmDocumentDefinition](document.md)>)**<br/>*documents*: The list of documents to add.|Adds the elements of the specified list of documents to the collection.|void|
|**Remove([CdmDocumentDefinition](document.md))**<br/>*document*: The document to remove from the collection.|Removes the specified document from the collection. Returns true if the operation is successful, false otherwise.|bool|
|**Remove(string)**<br/>*name*: The name of the document to remove from the collection.|Removes the document with the specified name from the collection. Returns true if the operation is successful, false otherwise.|bool|
