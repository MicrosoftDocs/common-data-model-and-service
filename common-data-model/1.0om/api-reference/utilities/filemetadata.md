---
title: File Metadata | Microsoft Docs
description: API reference for FileMetadata.
author: jinichu

ms.reviewer: deonhe 
ms.topic: article
ms.date: 1/5/2023
ms.author: mafrisci
---

# File Metadata

File status check options are options to be used when calling FetchAllFilesAsync from a [Storage Adapter](../storage/storageadapter.md) on a CDM object.

```csharp
public class CdmFileMetadata
```

## Properties
|Name|Type|Description|
|---|---|---|
|FileSizeBytes|long|Represents the file size of a given file in bytes.|
