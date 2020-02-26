---
title: Document | Microsoft Docs
description: API reference for CdmDocumentDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Document

A document enables the object model to have a persisted state. Every document can contain different Common Data Model object definitions, such as [entities](entity.md), [data partitions](datapartition.md), or attributes.

```
public class CdmDocumentDefinition extends CdmObjectSimple, CdmContainerDefinition
```

## Constructors
|Name|Description|
|---|---|
|**CdmDocumentDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The document's name.|Initializes a new instance of the [CdmDocumentDefinition](document.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The document's name.|
|Schema|string|The schema link that points to a validating schema.|
|JsonSchemaSemanticVersion|string|Identifies the version of the object model that supports this file shape.|
|Definitions|[CdmDefinitionCollection](definitioncollection.md)|The document's definitions - can be any object that implements [CdmObjectDefinition](cdmobjectdefinition.md).|
|Imports|[CdmImportCollection](importcollection.md)|The collection of corpus paths/monikers that denote the Common Data Model objects that need to be imported in order to use the document.|
|AtCorpusPath|string|The corpus path of the object declaration.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**RefreshAsync([ResolveOptions](../utilities/resolveoptions.md))**<br />*resOpt*: The resolve options.|Updates the indexes in the document. The method is supposed to be called after modifying the objects in the document.|Task\<bool>|
|**SaveAsAsync(string, bool, [CopyOptions](../utilities/copyoptions.md))**<br />*newName*: The new document's name.<br/>*saveReferenced [optional]*: A boolean that denotes whether we want to save all the references files (schema definition documents that are linked from the source document that have been modified) as well since the manifest can reference different entity documents. The default value is false.<br/>*options [optional]*: The copy options.|Saves the document back through the adapter in the requested format. The format is specified via the document name and extension based on the following conventions: *'model.json'* for the backwards-compatible model, *'.manifest.cdm.json'* for manifest, *'.folio.cdm.json'* for folio, and *'.cdm.json'* for Common Data Model object definitions. Returns false on any failure.<br/><br/>**Note:** For manifest and folio, there has to be a name in front of the extension (for example, *'example.manifest.cdm.json'* or *'example.folio.cdm.json'*), as saving with just the extension (*'manifest.cdm.json'*) will result in an empty JSON file. For model.json, however, it needs to be saved without a name in front, as just *'model.json'* (not *'example.model.json'*).|Task\<bool>|
|**FetchObjectDefinition\<T>([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.FetchObjectDefinition\<T>(...)](cdmobject.md#methods).|T|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

