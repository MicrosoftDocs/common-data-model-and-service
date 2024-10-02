---
title: Trait Reference | Microsoft Docs
description: API reference for CdmTraitReference.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 10/18/2019
ms.author: jibyun
---

# Trait Reference

*From SDK version 1.2 this class extends CdmTraitReferenceBase instead of CdmObjectReferenceBase*

This is the reference class for [traits](trait.md).

```csharp
public class CdmTraitReference extends CdmTraitReferenceBase
```

## Constructors
|Name|Description|
|---|---|
|**CdmTraitReference(CdmCorpusContext, dynamic, bool, bool)**<br/>*ctx*: The corpus context.<br/>*trait*: The trait that this trait reference is referencing.<br/>*simpleReference*: A boolean that denotes whether this trait reference is simple named or not. The default value is false.<br/>*hasArguments*: A boolean that denotes whether this trait reference has arguments.|Initializes a new instance of the [CdmTraitReference](traitreference.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|IsFromProperty|bool|Denotes whether the trait was generated from a property or if it was directly loaded.|
|Arguments|[CdmArgumentCollection](argumentcollection.md)|The trait reference's arguments.|



