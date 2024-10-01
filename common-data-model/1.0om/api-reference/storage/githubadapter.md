---
title: GitHub Adapter | Microsoft Docs
description: API reference for GitHubAdapter.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 08/24/2020
ms.author: jibyun
---

# GitHub Adapter

The GitHub adapter is the storage adapter that points to the Common Data Model public standards schema documents on [GitHub](https://github.com/microsoft/CDM/tree/master/schemaDocuments).<br/>

**Note**: This class is on the deprecation path. 

```csharp
public class GitHubAdapter extends NetworkAdapter
```
*GitHubAdapter extends NetworkAdapter, StorageAdapterBase in Python.*

## Constructors
|Name|Description|
|---|---|
|**GitHubAdapter()**|Initializes a new instance of the [GitHubAdapter](githubadapter.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|LocationHint|string|The hint given to the reader application about where the adapter implementation can be obtained (Nuget, NPM, etc.).|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the GitHub adapter can read data.|bool|
|**CanWrite()**|Returns false, since the GitHub adapter can't write data to its source.|bool|
|**ReadAsync(string)**|See [StorageAdapterBase.ReadAsync(...)](storageadapterbase.md#methods).|Task\<string>|
|**WriteAsync(string, string)**|See [StorageAdapterBase.WriteAsync(...)](storageadapterbase.md#methods). Throws a *NotImplementedException* because the GitHub adapter can't write to its source.|Task|
|**CreateAdapterPath(string)**|See [StorageAdapterBase.CreateAdapterPath(...)](storageadapterbase.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapterBase.CreateCorpusPath(...)](storageadapterbase.md#methods).|string|
|**ClearCache()**|See [StorageAdapterBase.ClearCache()](storageadapterbase.md#methods).|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapterBase.ComputeLastModifiedTimeAsync(...)](storageadapterbase.md#methods). Returns Time.Now().|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapterBase.FetchAllFilesAsync(...)](storageadapterbase.md#methods). Returns null.|Task\<List\<string>>|
|**FetchConfig()**|See [StorageAdapterBase.FetchConfig()](storageadapterbase.md#methods).|string|
|**UpdateConfig(string)**|See [StorageAdapterBase.UpdateConfig(...)](storageadapterbase.md#methods).|void|
|**CreateFileQueryCacheContext()**|See [StorageAdapterBase.CreateFileQueryCacheContext()](storageadapterbase.md#methods).|IDisposable|

