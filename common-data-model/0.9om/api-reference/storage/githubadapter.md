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

The Github adapter is the storage adapter that points to the CDM public standards schema documents on Github.<br/>

**Note**: This class is on the deprecation path. 

```
public class GithubAdapter extends NetworkAdapter, StorageAdapter
```

## Constructors
|Name|Description|
|---|---|
|**GithubAdapter()**|Initializes a new instance of the [GithubAdapter](githubadapter.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the Github adapter can read data.|boolean|
|**CanWrite()**|Returns false, since the Github adapter cannot write data to its source.|boolean|
|**ReadAsync(string)**|See [StorageAdapter.ReadAsync(...)](storageadapter.md#methods).|Task\<string>|
|**WriteAsync(string, dynamic)**|See [StorageAdapter.WriteAsync(...)](storageadapter.md#methods). Throws a *NotImplementedException* because the Github adapter cannot write to its source.|Task|
|**CreateAdapterPath(string)**|See [StorageAdapter.CreateAdapterPath(...)](storageadapter.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapter.CreateCorpusPath(...)](storageadapter.md#methods).|string|
|**ClearCache()**|See [StorageAdapter.ClearCache()](storageadapter.md#methods).|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapter.ComputeLastModifiedTimeAsync(...)](storageadapter.md#methods). Currently just returns Time.Now()|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapter.FetchAllFilesAsync(...)](storageadapter.md#methods). Currently just returns null.|Task\<List\<string>>|

