---
title: File Status Check Options | Microsoft Docs
description: API reference for FileStatusCheckOptions.
author: mafrisci

ms.reviewer: deonhe 
ms.topic: article
ms.date: 1/5/2023
ms.author: mafrisci
---

# File Status Check Options

File status check options are options to be used when calling FileStatusCheckAsync on a CDM object.

```csharp
public class FileStatusCheckOptions
```

## Constructors
|Name|Description|
|---|---|
|**FileStatusCheckOptions()**|Initializes a new instance of the [FileStatusCheckOptions](filestatuscheckoptions.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|IncludeDataPartitionSize|bool|A boolean value that specifies if the size of the data information should be included in the data partition object generated during FileStatusCheckAsync. This information can be found in the "is.partition.size" trait on the resulting data partition. The default value is false.|
