---
title: File Metadata | Microsoft Docs
description: API reference for FileMetadata.
author: mfriscia7

ms.reviewer: deonhe 
ms.topic: article
ms.date: 1/5/2023
ms.author: mafrisci
---

# File Metadata

File metadata is an object that holds metadata information about a file fetched from a [Storage Adapter](../storage/storageadapter.md) such as file size.

```csharp
public class CdmFileMetadata
```

## Properties
|Name|Type|Description|
|---|---|---|
|FileSizeBytes|long|Represents the file size of a given file in bytes.|
