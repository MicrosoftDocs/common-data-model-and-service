---
title: Storage Adapter | Microsoft Docs
description: API reference for StorageAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# StorageAdapter

This is the base for an adapter object that can read and write documents to and from a data source. It allows a user to interact with data from multiple data sources without having to manually copy data to the location where the Common Data Model object model is running. This interface also allows users to create their own adapter, if needed.

```
public interface StorageAdapter
```
*StorageAdapter is a class in Python and is called StorageAdapterBase.*

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true if the adapter can read data, false otherwise.|bool|
|**CanWrite()**|Returns true if the adapter can write data to its source, false otherwise.|bool|
|**ReadAsync(string)**<br/>*corpusPath*: The corpus path.|Returns the object data that exists at the specified path as a string.|Task\<string>|
|**WriteAsync(string, dynamic)**<br/>*corpusPath*: The corpus path.<br/>*data*: The object data.|Writes the object data to the specified document path.|Task|
|**CreateAdapterPath(string)**<br/>*corpusPath*: The corpus path.|Converts the specified corpus path into a path in the domain of this adapter. Returns the adapter path.|string|
|**CreateCorpusPath(string)**<br/>*adapterPath*: The adapter path.|Converts the specified path in the domain of this adapter into a corpus path. Returns the corpus path.|string|
|**ClearCache()**|Empties the cache of files and folders if the storage adapter uses a cache.|void|
|**ComputeLastModifiedTimeAsync(string)**<br/>*corpusPath*: The corpus path to a document.|Returns the last modified time of the specified document.|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**<br/>*folderCorpusPath*: The corpus path to a folder.|Returns a list of corpus paths to all files and folders at or under the specified corpus path to a folder.|Task\<List\<string>>|

