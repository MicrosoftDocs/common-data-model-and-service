---
title: Partition File Status Check Type | Microsoft Docs
description: API reference for PartitionFileStatusCheckType.
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 04/20/2022
ms.author: weiluo
---

# Partition File Status Check Type

An enum class containing the incremental partition types in CDM.

> [!NOTE]
> PartitionFileStatusCheckType is available in SDK version >= 1.6.0.

```csharp
public enum PartitionFileStatusCheckType
{
    Full,
    Incremental,
    FullAndIncremental,
    None
}
```

* **Full**: SDK only updates the non-incremental partition objects and non-incremental partition pattern objects when calling `FetchObjectAsync` with `PartitionFileStatusCheckType.Full`. This is the default behavior.
* **Incremental**: SDK only updates the incremental partition objects and incremental partition pattern objects when calling `FetchObjectAsync` with `PartitionFileStatusCheckType.Incremental`.
* **FullAndIncremental**: SDK updates both non-incremental and incremental partition objects, as well as non-incremental and incremental partition pattern objects when calling `FetchObjectAsync` with `PartitionFileStatusCheckType.FullAndIncremental`.
* **None**: SDK only refreshes the last update time of the entity definition document.
