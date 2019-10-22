---
title: Local Adapter - Common Data Model | Microsoft Docs
description: Reference for LocalAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Local Adapter

The local adapter is the storage adapter that is used to interact with data on the local file system.

```
public class LocalAdapter extends StorageAdapter
```

## Constructors
|Name|Description|
|---|---|
|**LocalAdapter(string)**<br/>*root*: The root path of the schema documents.|Initializes a new instance of the LocalAdapter class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Root|string|The root path of the schema documents.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the LocalAdapter can read data.|boolean|
|**CanWrite()**|Returns true, since the LocalAdapter can write data to its source.|boolean|
|**ReadAsync(string)**|See *StorageAdapter.ReadAsync(...)*.|Task\<string>|
|**WriteAsync(string, dynamic)**|See *StorageAdapter.WriteAsync(...)*.|Task|
|**CreateAdapterPath(string)**|See *StorageAdapter.CreateAdapterPath(...)*.|string|
|**CreateCorpusPath(string)**|See *StorageAdapter.CreateCorpusPath(...)*.|string|
|**ClearCache()**|See *StorageAdapter.ClearCache()*. This method doesn't do anything because the LocalAdapter doesn't maintain a cache.|void|
|**ComputeLastModifiedTimeAsync(string)**|See *StorageAdapter.ComputeLastModifiedTimeAsync(...)*.|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See *StorageAdapter.FetchAllFilesAsync(...)*.|Task\<List\<string>>|

