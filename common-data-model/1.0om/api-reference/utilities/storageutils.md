---
title: Storage Utils | Microsoft Docs
description: API reference for StorageUtils.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 06/19/2020
ms.author: jibyun
---

# Storage Utils

This class contains [storage-related](../storage/storage.md) utility methods.

```
public class StorageUtils
```

## Methods
|Name|Type|Description|
|---|---|---|
|**SplitNamespacePath(string)**<br/>*objectPath*: The object path.<br/>|Splits the specified object path into the namespace and the path. Returns a tuple where the first item is the namespace and the second item is the path.<br/><br/>Ex. "local:/path/to/file" -> ("local", "path/to/file")|Tuple\<string, string>|