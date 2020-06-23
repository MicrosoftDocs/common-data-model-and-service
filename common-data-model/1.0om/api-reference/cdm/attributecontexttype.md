---
title: Attribute Context Type | Microsoft Docs
description: API reference for CdmAttributeContextType.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Attribute Context Type

An enum class containing the attribute context types. 

```csharp
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
