---
title: Import Class - Common Data Model | Microsoft Docs
description: Reference for CdmImport.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Import Class

An import is used by documents to provide the files and documents that need to be imported first.

```
public class CdmImport extends CdmObjectSimple
```

## Constructors
|Name|Description|
|---|---|
|**CdmImport(CdmCorpusContext, string, string)**<br/>*ctx*: The corpus context.<br/>*corpusPath*: The import path.<br/>*moniker*: The import moniker.|Initializes a new instance of the CdmImport class.|

## Properties
|Name|Type|Description|
|---|---|---|
|CorpusPath|string|The import path.|
|Moniker|string|A nickname used for imports to specify which document to import in the case of duplicate symbols (e.g. we might have multiple Account documents, but by specifying a moniker 'base_Account', we can pinpoint the exact document).|
|Doc|[CdmDocumentDefinition](document.md)|The document that has been resolved for this import.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|[CdmObject](cdmobject.md)|
|**Validate()**|See *CdmObject.Validate()*.|bool|

