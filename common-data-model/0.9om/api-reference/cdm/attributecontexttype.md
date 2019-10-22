---
title: Attribute Context Type Class - Common Data Model | Microsoft Docs
description: Reference for CdmAttributeContextType.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Attribute Context Type Class

An enum class containing the attribute context types. 

```
public enum CdmAttributeContextType
{
    Entity,
    EntityReferenceExtends,
    AttributeDefinition,
    EntityReferenceAsAttribute,
    AttributeGroup,
    GeneratedSet,
    GeneratedRound,
    AddedAttributeSupporting,
    AddedAttributeIdentity,
    AddedAttributeSelectedType,
    AddedAttributeExpansionTotal,
    PassThrough
}
```


