---
title: Remote Adapter | Microsoft Docs
description: API reference for RemoteAdapter.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 08/24/2020
ms.author: jibyun
---

# Remote Adapter

The remote adapter is the storage adapter that's used to interact with data on a remote file system.

```csharp
public class RemoteAdapter extends NetworkAdapter
```

## Constructors
|Name|Description|
|---|---|
|**RemoteAdapter()**<br/>*hosts [optional]*: The dictionary of hosts.|Initializes a new instance of the [RemoteAdapter](remoteadapter.md) class. The user must apply an adapter configuration (see *UpdateConfig(...)*) or provide hosts.|

## Properties
|Name|Type|Description|
|---|---|---|
|Hosts|Dictionary\<string, string>|The dictionary of hosts. The mapping is from a key  to a host. For example, { "contoso": "http://contoso.com" }. <br/><br/>The key is used as a shorthand for the host. For example, if a remote adapter is configured with { "contoso": "http://contoso.com" }, given the url "http://contoso.com/example.cdm.json", the converted corpus path would then be "remote:/contoso/example.cdm.json" (assuming the remote adapter is mounted under the "remote" namespace).|
|LocationHint|string|The hint given to the reader application about where the adapter implementation can be obtained (Nuget, NPM, etc.).|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the remote adapter can read data.|bool|
|**CanWrite()**|Returns false, since the remote adapter can't write data to its source.|bool|
|**ReadAsync(string)**|See [StorageAdapterBase.ReadAsync(...)](storageadapterbase.md#methods).|Task\<string>|
|**WriteAsync(string, string)**|See [StorageAdapterBase.WriteAsync(...)](storageadapterbase.md#methods). Throws a *NotImplementedException* because the remote adapter can't write to its source.|Task|
|**CreateAdapterPath(string)**|See [StorageAdapterBase.CreateAdapterPath(...)](storageadapterbase.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapterBase.CreateCorpusPath(...)](storageadapterbase.md#methods).|string|
|**ClearCache()**|See [StorageAdapterBase.ClearCache()](storageadapterbase.md#methods).|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapterBase.ComputeLastModifiedTimeAsync(...)](storageadapterbase.md#methods). Returns Time.Now().|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapterBase.FetchAllFilesAsync(...)](storageadapterbase.md#methods). Returns null.|Task\<List\<string>>|
|**FetchConfig()**|See [StorageAdapterBase.FetchConfig()](storageadapterbase.md#methods).|string|
|**UpdateConfig(string)**|See [StorageAdapterBase.UpdateConfig(...)](storageadapterbase.md#methods).|void|
|**CreateFileQueryCacheContext()**|See [StorageAdapterBase.CreateFileQueryCacheContext()](storageadapterbase.md#methods).|IDisposable|

