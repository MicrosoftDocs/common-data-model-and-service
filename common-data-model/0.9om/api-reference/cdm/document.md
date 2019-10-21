---
title: Document Class - Common Data Model | Microsoft Docs
description: Reference for CdmDocumentDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Document Class

A document enables the OM to have a persisted state. Every document can contain different CDM definitions, such as entities, data partitions, or attributes.

```
public class CdmDocumentDefinition extends CdmObjectSimple, CdmContainerDefinition
```

## Constructors
|Name|Description|
|---|---|
|TODO: Update once hasImports is removed<br/>**CdmDocumentDefinition(CdmCorpusContext, string, bool)**<br/>*ctx*: The corpus context.<br/>*name*: The document's name.<br/>*hasImports [optional]*: A boolean that denotes whether this document has imports.|Initializes a new instance of the CdmDocumentDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The document's name.|
|Schema|string|The schema link that points to a validating schema.|
|JsonSchemaSemanticVersion|string|Identifies the version of the OM that supports this file shape.|
|Definitions|CdmCollection\<CdmObjectDefinition>|The document's definitions - can be any object that implements CdmObjectDefinition.|
|TODO: Update once Folder is replaced by Owner<br/>Folder|CdmFolderDefinition|The document's folder. This property will eventually be replaced by CdmObject's *Owner* property.|
|Imports|CdmCollection\<CdmImport>|The list of corpus paths/monikers that denote the CDM objects that need to be imported in order to use the document.|
|AtCorpusPath|string|The corpus path of the object declaration.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**RefreshAsync(ResolveOptions)**<br />*resOpt*: The resolution options.|Updates the indexes in the document. The method is supposed to be called after modifying the objects in the document.|Task\<bool>|
|**SaveAsAsync(string, bool, CopyOptions)**<br />*newName*: The new document's name.<br/>*saveReferenced [optional]*: A boolean that denotes whether we want to save all the references files (schema definition documents that are linked from the source document that have been modified) as well since the manifest can reference different entity documents. The default value is false.<br/>*options [optional]*: The copy options.|Saves the document back through the adapter in the requested format. The format is specified via the document name/extension based on conventions: '.model.json' for the backwards-compatible model, '.manifest.cdm.json' for manifest, '.folio.cdm.json' for folio, and '.cdm.json' for CDM definitions. Returns false on any failure.|Task\<bool>|
|**FetchObjectDefinition\<T>(ResolveOptions)**|See *CdmObject.FetchObjectDefinition\<T>(...)*.|T|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|CdmObject|
|**Validate()**|See *CdmObject.Validate()*.|bool|

