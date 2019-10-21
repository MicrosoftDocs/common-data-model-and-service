---
title: Purpose Class - Common Data Model | Microsoft Docs
description: Reference for CdmPurposeDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Purpose Class

A purpose provides an attribute with what it does for an entity *(e.g. SortedBy, NamedBy)*.


```
public class CdmPurposeDefinition : CdmObjectDefinitionBase
```

## Constructors
|Name|Description|
|---|---|
|TODO: Update once exhibitsTraits is removed and extendsPurpose is optional<br/>**CdmPurposeDefinition(CdmCorpusContext, string, CdmPurposeReference, bool)**<br/>*ctx*: The corpus context.<br/>*purposeName*: The purpose's name.<br/>*extendsPurpose*: The reference to the purpose extended by this purpose.<br/>*exhibitsTraits [optional]*: TODO. The default value is false.|Initializes a new instance of the CdmPurposeDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|PurposeName|string|The purpose's name.|
|ExtendsPurpose|CdmPurposeReference|The reference to the purpose extended by this purpose.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, ResolveOptions)**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|CdmObject|
|**Validate()**|See *CdmObject.Validate()*.|bool|

