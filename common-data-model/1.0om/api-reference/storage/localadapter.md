---
title: Local Adapter | Microsoft Docs
description: API reference for LocalAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 08/24/2020
ms.author: jibyun
---

# Local Adapter

The local adapter is the storage adapter that's used to interact with data on the local file system.

```csharp
public class LocalAdapter extends StorageAdapterBase
```

## Constructors
|Name|Description|
|---|---|
|**LocalAdapter()**|Initializes a new instance of the [LocalAdapter](localadapter.md) class. The user must apply an adapter configuration if this constructor is used. See *UpdateConfig(...)*.|
|**LocalAdapter(string)**<br/>*root*: The root path of the schema documents.|Initializes a new instance of the [LocalAdapter](localadapter.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Root|string|The root path of the schema documents.|
|LocationHint|string|The hint given to the reader application about where the adapter implementation can be obtained (Nuget, NPM, etc.).|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the local adapter can read data.|bool|
|**CanWrite()**|Returns true, since the local adapter can write data to its source.|bool|
|**ReadAsync(string)**|See [StorageAdapterBase.ReadAsync(...)](storageadapterbase.md#methods).|Task\<string>|
|**WriteAsync(string, string)**|See [StorageAdapterBase.WriteAsync(...)](storageadapterbase.md#methods).|Task|
|**CreateAdapterPath(string)**|See [StorageAdapterBase.CreateAdapterPath(...)](storageadapterbase.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapterBase.CreateCorpusPath(...)](storageadapterbase.md#methods).|string|
|**ClearCache()**|See [StorageAdapterBase.ClearCache()](storageadapterbase.md#methods). This method doesn't do anything because the local adapter doesn't maintain a cache.|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapterBase.ComputeLastModifiedTimeAsync(...)](storageadapterbase.md#methods).|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapterBase.FetchAllFilesAsync(...)](storageadapterbase.md#methods).|Task\<List\<string>>|
|**FetchConfig()**|See [StorageAdapterBase.FetchConfig()](storageadapterbase.md#methods).|string|
|**UpdateConfig(string)**|See [StorageAdapterBase.UpdateConfig(...)](storageadapterbase.md#methods).|void|
|**CreateFileQueryCacheContext()**|See [StorageAdapterBase.CreateFileQueryCacheContext()](storageadapterbase.md#methods).|IDisposable|

