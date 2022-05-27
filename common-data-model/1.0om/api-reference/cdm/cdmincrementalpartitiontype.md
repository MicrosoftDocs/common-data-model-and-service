---
title: Incremental Partition Type | Microsoft Docs
description: API reference for CdmIncrementalPartitionType.
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 04/20/2022
ms.author: weiluo
---

# Incremental Partition Type

An enum class containing the incremental partition types in CDM.

> [!NOTE]
> CdmIncrementalPartitionType is available in SDK version >= 1.6.0.

```csharp
public enum CdmIncrementalPartitionType
{
    None,
    Insert,
    Update,
    Delete,
    Upsert,
    UpsertAndDelete
}
```

* **None**: An enum value indicating that the partition file does not contain incremental records.
* **Insert**: An enum value indicating that the partition file contains newly inserted table records only.
* **Update**: An enum value indicating that the partition file contains updated table records only.
* **Delete**: An enum value indicating that the partition file contains deleted table records only.
* **Upsert**: An enum value indicating that the partition file contains newly inserted or updated table records.
* **UpsertAndDelete**: An enum value indicating that the partition file contains newly inserted, updated and deleted table records. Example would be a delta-lake partition file.
