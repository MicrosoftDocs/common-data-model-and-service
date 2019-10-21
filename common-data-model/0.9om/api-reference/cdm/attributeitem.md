---
title: Attribute Item Interface - Common Data Model | Microsoft Docs
description: Reference for CdmAttributeItem.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Attribute Item Interface

An attribute item represents the base interface for a generic attribute that could be a [type attribute](typeattribute.md) or an [entity attribute](entityattribute.md).

TODO: Delete CdmReferencesEntities once removed
```
public interface CdmAttributeItem extends CdmObject, CdmReferencesEntities
```

## Properties
|Name|Type|Description|
|---|---|---|
|AppliedTraits|CdmCollection\<CdmTraitReference>|The attribute's applied traits.|

