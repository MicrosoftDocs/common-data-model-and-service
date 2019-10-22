---
title: Remote Adapter - Common Data Model | Microsoft Docs
description: Reference for RemoteAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Remote Adapter

The remote adapter is the storage adapter that is used to interact with data on a remote file system.

```
public class RemoteAdapter extends NetworkAdapter, StorageAdapter
```

## Constructors
|Name|Description|
|---|---|
|**RemoteAdapter()**|Initializes a new instance of the RemoteAdapter class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Hosts|Dictionary\<string, string>|The list of hosts.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the RemoteAdapter can read data.|boolean|
|**CanWrite()**|Returns false, since the RemoteAdapter cannot write data to its source.|boolean|
|**ReadAsync(string)**|See *StorageAdapter.ReadAsync(...)*.|Task\<string>|
|**ClearCache()**|See *StorageAdapter.ClearCache()*.|void|
|**ComputeLastModifiedTimeAsync(string)**|See *StorageAdapter.ComputeLastModifiedTimeAsync(...)*. Currently just returns Time.Now()|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See *StorageAdapter.FetchAllFilesAsync(...)*. Currently just returns null.|Task\<List\<string>>|

