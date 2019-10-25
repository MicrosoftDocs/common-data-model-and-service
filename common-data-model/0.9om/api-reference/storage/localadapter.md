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
*LocalAdapter extends StorageAdapterBase in Python.*

## Constructors
|Name|Description|
|---|---|
|**LocalAdapter(string)**<br/>*root*: The root path of the schema documents.|Initializes a new instance of the [LocalAdapter](localadapter.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Root|string|The root path of the schema documents.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the local adapter can read data.|bool|
|**CanWrite()**|Returns true, since the local adapter can write data to its source.|bool|
|**ReadAsync(string)**|See [StorageAdapter.ReadAsync(...)](storageadapter.md#methods).|Task\<string>|
|**WriteAsync(string, dynamic)**|See [StorageAdapter.WriteAsync(...)](storageadapter.md#methods).|Task|
|**CreateAdapterPath(string)**|See [StorageAdapter.CreateAdapterPath(...)](storageadapter.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapter.CreateCorpusPath(...)](storageadapter.md#methods).|string|
|**ClearCache()**|See [StorageAdapter.ClearCache()](storageadapter.md#methods). This method does not do anything because the local adapter does not maintain a cache.|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapter.ComputeLastModifiedTimeAsync(...)](storageadapter.md#methods).|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapter.FetchAllFilesAsync(...)](storageadapter.md#methods).|Task\<List\<string>>|

