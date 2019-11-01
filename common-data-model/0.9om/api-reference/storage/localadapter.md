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

The local adapter is the storage adapter that is used to interact with data on the local file system.

```
public class LocalAdapter extends StorageAdapter
```
*LocalAdapter extends StorageAdapterBase in Python.*

## Constructors
|Name|Description|
|---|---|
|**LocalAdapter()**|Initializes a new instance of the [LocalAdapter](localadapter.md) class. The user must apply an adapter configuration if this constructor is used. See *ApplyConfig(...)*.|
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
|**ClearCache()**|See [StorageAdapter.ClearCache()](storageadapter.md#methods). This method does not do anything because the local adapter does not maintain a cache.|void|
|**ComputeLastModifiedTimeAsync(string)**<br/><br/>*fetchLastModifiedTimeAsync(...) in Java and Python.*|See [StorageAdapter.ComputeLastModifiedTimeAsync(...)](storageadapter.md#methods).|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapter.FetchAllFilesAsync(...)](storageadapter.md#methods).|Task\<List\<string>>|
|**ConstructConfig()**|See [StorageAdapter.ConstructConfig()](storageadapter.md#methods).|string|
|**ApplyConfig(string)**|See [StorageAdapter.ApplyConfig(...)](storageadapter.md#methods).|void|

