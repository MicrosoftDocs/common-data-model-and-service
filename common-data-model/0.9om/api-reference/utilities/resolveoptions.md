---
title: Resolve Options | Microsoft Docs
description: API reference for ResolveOptions.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Resolve Options

Resolve options are options to be used for resolution. If it is an optional argument to a method, it is safe to leave it null because default resolve options would just be created and used instead. 

```
public class ResolveOptions
```

## Constructors
|Name|Description|
|---|---|
|**ResolveOptions()**|Initializes a new instance of the [ResolveOptions](resolveoptions.md) class.|
|**ResolveOptions([CdmDocumentDefinition](../cdm/document.md), AttributeResolutionDirectiveSet)**<br/>*cdmDocument*: The document to use as the point of reference when resolving relative paths and symbol names.<br/>*directives [optional]*: The set of string flags that direct how attribute-resolving traits should behave.|
|**ResolveOptions([CdmObject](../cdm/cdmobject.md), AttributeResolutionDirectiveSet)**<br/>*cdmObject*: The CDM object to use to fetch the document that contains the owner of this object. The fetched document is then used as the point of reference when resolving relative paths and symbol names.<br/>*directives [optional]*: The set of string flags that direct how attribute resolving traits should behave.|Initializes a new instance of the [ResolveOptions](resolveoptions.md) class using the most common parameters.|

## Properties
|Name|Type|Description|
|---|---|---|
|WrtDoc|[CdmDocumentDefinition](../cdm/document.md)|The document to use as the point of reference when resolving relative paths and symbol names.|
|Directives|AttributeResolutionDirectiveSet|The set of string flags that direct how attribute resolving traits should behave (e.g. *normalized*, *structured*, etc.).|
|ShallowValidation|bool|When enabled, errors regarding object references being unable to load or resolve are suppressed and logged as warnings instead. This resolve option is enabled through the *shallowValidation* parameter in [FetchObjectAsync(...)](../cdm/corpus.md#methods) and is used only during loading.<br/><br/>A use case for this resolve option is when loading a resolved schema without its referenced schemas being present. This may be acceptable behavior if you're not interested in *how* the schema was resolved (e.g. where its attributes originated from) and are just concerned with reading the contents inside the resolved schema.<br/><br/>**Note:** By enabling shallow validation, you may be suppressing important errors about your schemas being incorrect, incomplete, etc. Use caution when using this resolve option.|
