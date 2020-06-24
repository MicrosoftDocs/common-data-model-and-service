---
title: Local Adapter | Microsoft Docs
description: API reference for LocalAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Local Adapter

The local adapter is the storage adapter that's used to interact with data on the local file system.

```csharp
public class LocalAdapter extends StorageAdapter
```
*LocalAdapter extends StorageAdapterBase in Python.*

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
|**ReadAsync(string)**|See [StorageAdapter.ReadAsync(...)](storageadapter.md#methods).|Task\<string>|
|**WriteAsync(string, string)**|See [StorageAdapter.WriteAsync(...)](storageadapter.md#methods).|Task|
|**CreateAdapterPath(string)**|See [StorageAdapter.CreateAdapterPath(...)](storageadapter.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapter.CreateCorpusPath(...)](storageadapter.md#methods).|string|
|**ClearCache()**|See [StorageAdapter.ClearCache()](storageadapter.md#methods). This method doesn't do anything because the local adapter doesn't maintain a cache.|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapter.ComputeLastModifiedTimeAsync(...)](storageadapter.md#methods).|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapter.FetchAllFilesAsync(...)](storageadapter.md#methods).|Task\<List\<string>>|
|**FetchConfig()**|See [StorageAdapter.FetchConfig()](storageadapter.md#methods).|string|
|**UpdateConfig(string)**|See [StorageAdapter.UpdateConfig(...)](storageadapter.md#methods).|void|

