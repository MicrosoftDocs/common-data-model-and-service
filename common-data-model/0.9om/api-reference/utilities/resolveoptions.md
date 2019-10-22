---
title: Resolve Options - Common Data Model | Microsoft Docs
description: Reference for ResolveOptions.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Resolve Options

TODO: Description

```
public class ResolveOptions
```

## Constructors
|Name|Description|
|---|---|
|**ResolveOptions()**|Initializes a new instance of the ResolveOptions class.|
|**ResolveOptions([CdmDocumentDefinition](../cdm/document.md))**<br/>*cdmDocument*: The document to use as the point of reference when resolving relative paths and symbol names.|Initializes a new instance of the ResolveOptions class using the most common parameters.|
|**ResolveOptions([CdmObject](../cdm/cdmobject.md))**<br/>*cdmObject*: The CDM object to use to fetch the document that contains the owner of this object. The fetched document is then used as the point of reference when resolving relative paths and symbol names.|Initializes a new instance of the ResolveOptions class using the most common parameters.|

## Properties
|Name|Type|Description|
|---|---|---|
|WrtDoc|[CdmDocumentDefinition](../cdm/document.md)|The document to use as the point of reference when resolving relative paths and symbol names.|
|Directives|AttributeResolutionDirectiveSet|The set of string flags that direct how attribute resolving traits should behave (e.g. *normalized*, *structured*, etc).|
