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
    InsertAndDelete
}
```

* **None**: Non-incremental type.
* **Insert**: An enum value that denotes the partition file contains records of insertion, insert is an operation that inserts a row into a database table.
* **Update**: An enum value that denotes the partition file contains records of update, update is an operation that change or update values of a row in a database table.
* **Delete**: An enum value that denotes the partition file contains records of deletion, delete is an operation that delete a row in a database table.
* **Upsert**: An enum value that denotes the partition file contains records of insertion and update, upsert is an operation that inserts a row into a database table if it do not already exist, or updates it if it does.
* **InsertAndDelete**: An enum value that denotes the partition file contains records of insertion, update and deletion. This is a delta-lake-like partition file.
