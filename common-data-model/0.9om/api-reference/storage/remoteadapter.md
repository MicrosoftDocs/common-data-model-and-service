---
title: Remote Adapter | Microsoft Docs
description: API reference for RemoteAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Remote Adapter

The remote adapter is the storage adapter that is used to interact with data on a remote file system.

```
public class RemoteAdapter extends NetworkAdapter, StorageAdapter
```
*RemoteAdapter extends NetworkAdapter, StorageAdapterBase in Python.*

## Constructors
|Name|Description|
|---|---|
|**RemoteAdapter()**|Initializes a new instance of the [RemoteAdapter](remoteadapter.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Hosts|Dictionary\<string, string>|The dictionary of hosts. The mapping is from a key  to a host. For example, { "contoso": "http://contoso.com" }. <br/><br/>The key is used as a shorthand for the host. For example, if a remote adapter is configured with { "contoso": "http://contoso.com" }, given the url "http://contoso.com/example.cdm.json", the converted corpus path would then be "remote:/contoso/example.cdm.json" (assuming the remote adapter is mounted under the "remote" namespace).|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the remote adapter can read data.|bool|
|**CanWrite()**|Returns false, since the remote adapter cannot write data to its source.|bool|
|**ReadAsync(string)**|See [StorageAdapter.ReadAsync(...)](storageadapter.md#methods).|Task\<string>|
|**WriteAsync(string, dynamic)**|See [StorageAdapter.WriteAsync(...)](storageadapter.md#methods). Throws a *NotImplementedException* because the remote adapter cannot write to its source.|Task|
|**CreateAdapterPath(string)**|See [StorageAdapter.CreateAdapterPath(...)](storageadapter.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapter.CreateCorpusPath(...)](storageadapter.md#methods).|string|
|**ClearCache()**|See [StorageAdapter.ClearCache()](storageadapter.md#methods).|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapter.ComputeLastModifiedTimeAsync(...)](storageadapter.md#methods). Currently just returns Time.Now()|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapter.FetchAllFilesAsync(...)](storageadapter.md#methods). Currently just returns null.|Task\<List\<string>>|

