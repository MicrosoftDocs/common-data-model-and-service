---
title: Resolve Options - Common Data Model | Microsoft Docs
description: API reference for ResolveOptions.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Resolve Options

Resolve options are options to be used for resolution. If it is an optional argument to a method, it is safe to leave it null. Default resolve options would just be created and used instead. 

```
public class ResolveOptions
```

## Constructors
|Name|Description|
|---|---|
|**ResolveOptions()**|Initializes a new instance of the [ResolveOptions](resolveoptions.md) class.|
|**ResolveOptions([CdmDocumentDefinition](../cdm/document.md))**<br/>*cdmDocument*: The document to use as the point of reference when resolving relative paths and symbol names.|Initializes a new instance of the [ResolveOptions](resolveoptions.md) class using the most common parameters.|
|**ResolveOptions([CdmObject](../cdm/cdmobject.md))**<br/>*cdmObject*: The CDM object to use to fetch the document that contains the owner of this object. The fetched document is then used as the point of reference when resolving relative paths and symbol names.|Initializes a new instance of the [ResolveOptions](resolveoptions.md) class using the most common parameters.|

## Properties
|Name|Type|Description|
|---|---|---|
|WrtDoc|[CdmDocumentDefinition](../cdm/document.md)|The document to use as the point of reference when resolving relative paths and symbol names.|
|Directives|AttributeResolutionDirectiveSet|The set of string flags that direct how attribute resolving traits should behave (e.g. *normalized*, *structured*, etc.).|
