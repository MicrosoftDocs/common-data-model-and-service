---
title: Import Collection | Microsoft Docs
description: API reference for CdmImportCollection.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 10/18/2019
ms.author: jibyun
---

# Import Collection

An import collection extends [Collection](collection.md) and adds additional behaviors specific to import collections. 

```csharp
public class CdmImportCollection extends CdmCollection<CdmImport>
```

## Constructors
|Name|Description|
|---|---|
|**CdmImportCollection(CdmCorpusContext, [CdmDocumentDefinition](document.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The owner of this collection. Must be a document.|Initializes a new instance of the [CdmImportCollection](importcollection.md) class.|

## Methods
|Name|Description|Return Type|SDK|
|---|---|---|---|
|**Add(string, bool)**<br/>*corpusPath*: The corpus path to be set for the import.<br/>*simpleRef [optional]*: This parameter is unused. It's kept just for consistency with other Common Data Model collections.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates an import with the specified corpus path and adds it to the collection. Returns the import that was added to the collection.|[CdmImport](import.md)|1.0|
|**Add(string, string)**<br/>*corpusPath*: The corpus path to be set for the import.<br/>*moniker*: The moniker to be set for the import.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates an import with the specified corpus path and moniker and adds it to the collection. Returns the import that was added to the collection.|[CdmImport](import.md)| 1.0|
|**AddRange(IEnumerable\<[CdmImport](import.md)>)**<br/>*importList*: The list of imports to add.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of imports to the collection.|void|1.0|
|**Item(string, string, bool)**<br/>*corpusPath*: The corpus path for the import to fetch.<br/>*moniker [optional]*: A nickname used for imports to specify which document to import in the case of duplicate symbols.<br/>*checkMoniker [optional]*: A boolean that denotes whether to fetch the import by checking both the corpus name and moniker or only the corpus name. The default value is true.|Returns the object with the specified corpus path and/or moniker.|[CdmImport](import.md)|1.6|
