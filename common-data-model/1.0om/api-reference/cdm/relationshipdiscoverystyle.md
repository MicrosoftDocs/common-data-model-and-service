---
title: Relationship Discovery Style | Microsoft Docs
description: API reference for CdmRelationshipDiscoveryStyle.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 10/18/2019
ms.author: jibyun
---

# Relationship Discovery Style

An enum class containing the types of relationships we want populated in a manifest. 

```csharp
public enum CdmRelationshipDiscoveryStyle
{
    None,       
    Exclusive,       
    All         
}               
```

*None*: Don't add any relationships to the manifest.<br/>
*Exclusive*: Only include relationships where the *toEntity* and *fromEntity* are entities found in the manifest.<br/>
*All*: Include all relationships including any relationships where the *toEntity* or the *fromEntity* point to entities not found in the manifest.