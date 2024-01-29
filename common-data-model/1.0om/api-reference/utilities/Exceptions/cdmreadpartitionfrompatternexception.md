---
title: CdmReadPartitionFromPatternException | Microsoft Docs
description: API reference for CdmReadPartitionFromPatternException.
author: mafrisci
ms.reviewer: anbichse
ms.topic: article
ms.date: 01/23/2024
ms.author: mafrisci
---

# CdmReadPartitionFromPatternException

The CdmReadPartitionFromPattern Exception is an exception that the SDK throws if there an error reading a partition from a partition pattern is encountered during the FileStatusCheckAsync call. The 'ThrowErrorOnPartition' flag must be set to true in FileStatusCheckOptions to throw the error, otherwise only a warning is logged and the SDK continues to process partition patterns.

```csharp
var options = new FileStatusCheckOptions()
{
    ThrowOnPartitionError = true
};

try
{
    manifest.fileStatusCheckAsync(fileStatusCheckOptions: options);
}
catch (CdmReadPartitionFromPatternException e)
{
    // handle error
}
```