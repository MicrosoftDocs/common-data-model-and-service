---
title: Github Adapter | Microsoft Docs
description: API reference for GithubAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Github Adapter

The Github adapter is the storage adapter that points to the Common Data Model public standards schema documents on Github.<br/>

**Note**: This class is on the deprecation path. 

```
public class GithubAdapter extends NetworkAdapter, StorageAdapter
```
*StorageAdapter is called StorageAdapterBase in Python.*

## Constructors
|Name|Description|
|---|---|
|**GithubAdapter()**|Initializes a new instance of the [GithubAdapter](githubadapter.md) class.|
|**GithubAdapter(string)**<br/>*configs*: A JSON string representing the configuration for the adapter.|Initializes a new instance of the [GithubAdapter](githubadapter.md) class using the specified configuration.|

## Properties
|Name|Type|Description|
|---|---|---|
|LocationHint|string|The hint given to the reader application about where the adapter implementation can be obtained (Nuget, NPM, etc.).|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the Github adapter can read data.|bool|
|**CanWrite()**|Returns false, since the Github adapter cannot write data to its source.|bool|
|**ReadAsync(string)**|See [StorageAdapter.ReadAsync(...)](storageadapter.md#methods).|Task\<string>|
|**WriteAsync(string, dynamic)**|See [StorageAdapter.WriteAsync(...)](storageadapter.md#methods). Throws a *NotImplementedException* because the Github adapter cannot write to its source.|Task|
|**CreateAdapterPath(string)**|See [StorageAdapter.CreateAdapterPath(...)](storageadapter.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapter.CreateCorpusPath(...)](storageadapter.md#methods).|string|
|**ClearCache()**|See [StorageAdapter.ClearCache()](storageadapter.md#methods).|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapter.ComputeLastModifiedTimeAsync(...)](storageadapter.md#methods). Currently just returns Time.Now()|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapter.FetchAllFilesAsync(...)](storageadapter.md#methods). Currently just returns null.|Task\<List\<string>>|
|**ConstructConfig()**|See [StorageAdapter.ConstructConfig()](storageadapter.md#methods).|string|

