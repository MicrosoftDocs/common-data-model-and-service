---
title: Attribute Item | Microsoft Docs
description: API reference for CdmAttributeItem.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Attribute Item

An attribute item represents the base interface for a generic attribute that could be a [type attribute](typeattribute.md) or an [entity attribute](entityattribute.md).

```
public interface CdmAttributeItem extends CdmObject, CdmReferencesEntities
```
*CdmAttributeItem is a class in Python.*

## Properties
|Name|Type|Description|
|---|---|---|
|AppliedTraits|[CdmTraitCollection](traitcollection.md)|The attribute's applied traits.|

