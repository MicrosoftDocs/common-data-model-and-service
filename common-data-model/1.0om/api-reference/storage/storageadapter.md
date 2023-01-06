---
title: Storage adapter | Microsoft Docs
description: The API reference for StorageAdapter.
author: jinichu

ms.reviewer: deonhe 
ms.topic: article
ms.date: 08/24/2020
ms.author: jibyun
---

# Storage Adapter

This is the base interface for an adapter object that can read and write documents to and from a data source. It allows a user to interact with data from multiple data sources without having to manually copy data to the location where the [object model](../cdm/cdm.md) is running. This interface also allows users to create their own adapter, if needed.

>[!NOTE]
>This class is on the deprecation path. Use [StorageAdapterBase] instead

```csharp
public interface StorageAdapter
```
*This interface is substituted with a regular class in Python and is called StorageAdapterBase.*

## Properties
|Name|Type|Description|
|---|---|---|
|LocationHint|string|The hint given to the reader application about the location of the implementation for the adapter (Nuget, NPM, etc.).|

>[!IMPORTANT]
>Storage adapter methods that take in a corpus path as a parameter (*ReadAsync(...), WriteAsync(...), CreateAdapterPath(...), ComputeLastModifiedTimeAsync(...), and FetchAllFilesAsync(...)*) will only accept corpus paths **without** a namespace. For example, use "/some/path" instead of "local:/some/path".

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true if the adapter can read data, false otherwise.|bool|
|**CanWrite()**|Returns true if the adapter can write data to its source, false otherwise.|bool|
|**ReadAsync(string)**<br/>*corpusPath*: The corpus path.|Returns the object data that exists at the specified path as a string.|Task\<string>|
|**WriteAsync(string, string)**<br/>*corpusPath*: The corpus path.<br/>*data*: The object data as a string.|Writes the object data to the specified document path.|Task|
|**CreateAdapterPath(string)**<br/>*corpusPath*: The corpus path.|Converts the specified corpus path into a path in the domain of this adapter. Returns the adapter path.|string|
|**CreateCorpusPath(string)**<br/>*adapterPath*: The adapter path.|Converts the specified path in the domain of this adapter into a corpus path. Returns the corpus path.|string|
|**ClearCache()**|Empties the cache of files and folders if the storage adapter uses a cache.|void|
|**ComputeLastModifiedTimeAsync(string)**<br/>*corpusPath*: The corpus path to a document.|Returns the last modified time of the specified document.|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**<br/>*folderCorpusPath*: The corpus path to a folder.|Returns a list of corpus paths to all files and folders at or under the specified corpus path to a folder. This has been deprecated, please use FetchAllFilesMetadataAsync instead. |Task\<List\<string>>|
|**FetchAllFilesMetadataAsync(string)**<br/>*folderCorpusPath*: The corpus path to a folder.|Returns a dictionary where the keys are the corpus paths to all files and folders at or under the specified corpus path to a folder, values contain the information about the file.|Task\<IDictionary\<string, CdmFileMetadata>>|
|**FetchConfig()**|Constructs the adapter's configuration. Returns a JSON string representing the configuration.|string|
|**UpdateConfig(string)**<br/>*string*: A JSON string representing the configuration for the adapter.|Applies the specified configuration to the adapter. This method must be called after using the default constructor.|void|

