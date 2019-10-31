---
title: Import | Microsoft Docs
description: API reference for CdmImport.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Import

An import is used by [documents](document.md) to provide the files and documents that need to be imported first.

```
public class CdmImport extends CdmObjectSimple
```

## Constructors
|Name|Description|
|---|---|
|**CdmImport(CdmCorpusContext, string, string)**<br/>*ctx*: The corpus context.<br/>*corpusPath*: The import path.<br/>*moniker*: The import moniker.|Initializes a new instance of the [CdmImport](import.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|CorpusPath|string|The import path.|
|Moniker|string|A nickname used for imports to specify which document to import in the case of duplicate symbols. For example, we might have multiple Account documents, but by specifying a moniker 'base_Account', we can pinpoint the exact document.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

