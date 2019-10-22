---
title: Github Adapter - Common Data Model | Microsoft Docs
description: Reference for GithubAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Github Adapter

TODO: Description <br/>

**Note**: This class is on the deprecation path. 

```
public class GithubAdapter extends NetworkAdapter, StorageAdapter
```

## Constructors
|Name|Description|
|---|---|
|**GithubAdapter()**|Initializes a new instance of the GithubAdapter class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the GithubAdapter can read data.|boolean|
|**CanWrite()**|Returns false, since the GithubAdapter cannot write data to its source.|boolean|
|**ReadAsync(string)**|See *StorageAdapter.ReadAsync(...)*.|Task\<string>|
|**ClearCache()**|See *StorageAdapter.ClearCache()*.|void|
|**ComputeLastModifiedTimeAsync(string)**|See *StorageAdapter.ComputeLastModifiedTimeAsync(...)*. Currently just returns Time.Now()|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See *StorageAdapter.FetchAllFilesAsync(...)*. Currently just returns null.|Task\<List\<string>>|

