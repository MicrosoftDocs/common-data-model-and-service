---
title: CdmReadPartitionFromPatternException | Microsoft Docs
description: API reference for CdmReadPartitionFromPatternException.
author: mafrisci
ms.reviewer: anbichse
ms.topic: article
ms.date: 01/23/2024
ms.author: mafrisci
---

# Cdm Read Partition From Pattern Exception

The Cdm Read Partition From Pattern Exception is an exception that is thrown if there is an error reading a partition from a partition pattern during the FileStatusCheckAsync call and when the 'ThrowErrorOnPartition' flag is set to true in FileStatusCheckOptions

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