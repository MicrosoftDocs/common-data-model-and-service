---
title: Trait Reference - Common Data Model | Microsoft Docs
description: Reference for CdmTraitReference.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Trait Reference

This is the reference class for [traits](trait.md).

```
public class CdmTraitReference extends CdmObjectReferenceBase
```
*CdmTraitReference extends CdmObjectReference in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmTraitReference(CdmCorpusContext, dynamic, bool, bool)**<br/>*ctx*: The corpus context.<br/>*trait*: The trait that this trait reference is referencing.<br/>*simpleReference*: TODO<br/>*hasArguments*: A boolean that denotes whether this trait reference has arguments.|Initializes a new instance of the [CdmTraitReference](traitreference.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|IsFromProperty|bool|Denotes whether the trait was generated from a property or if it was directly loaded.|
|Arguments|[CdmArgumentCollection](argumentcollection.md)|The trait reference's arguments.|



