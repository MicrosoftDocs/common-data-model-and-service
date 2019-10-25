---
title: Storage Manager - Common Data Model | Microsoft Docs
description: Reference for StorageManager.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Storage Manager

The storage manager acts like a storage for the [corpus](../cdm/corpus.md) and is used to interact with [storage adapters](storageadapter.md).

```
public class StorageManager
```

## Constructors
|Name|Description|
|---|---|
|**StorageManager([CdmCorpusDefinition](../cdm/corpus.md))**<br/>*corpus*: The corpus that this storage manager is in.|Initializes a new instance of the [StorageManager](storagemanager.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|DefaultNamespace|string|The namespace that will be used when one is not explicitly provided.|
|DefaultGithubAdapter|[GithubAdapter](githubadapter.md)|The default Github adapter.|
|DefaultLocalAdapter|[LocalAdapter](localadapter.md)|The default local adapter.|
|NamespaceAdapters|IDictionary\<string, [StorageAdapter](storageadapter.md)>|The dictionary of registered namespaces to storage adapters.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Mount(string, [StorageAdapter](storageadapter.md))**<br/>*nameSpace*: The namespace.<br/>*adapter*: The storage adapter.|Mounts a namespace to the specified adapter.|void|
|**Unmount(string)**<br/>*nameSpace*: The namespace.|Unmounts a namespace. Returns true if the unmount is successful, false otherwise.|bool|
|**FetchAdapter(string)**<br/>*nameSpace*: The namespace.|Retrieves the adapter for the specified namespace.|[StorageAdapter](storageadapter.md)|
|**FetchRootFolder(string)**<br/>*nameSpace*: The namespace.|Given the namespace of a registered stoarge adapter, returns the root folder containing the sub-folders and documents.|[CdmFolderDefinition](../cdm/folder.md)|
|**AdapterPathToCorpusPath(string)**<br/>*adapterPath*: The path.|Takes the specified storage adapter domain path, figures out the right adapter to use, and then returns a corpus path.|string|
|**CorpusPathToAdapterPath(string)**<br/>*corpusPath*: The path.|Takes the specified corpus path, figures out the right adapter to use, and then returns a storage adapter domain path.|string|
|**CreateAbsoluteCorpusPath(string, [CdmObject](../cdm/cdmobject.md))**<br/>*objectPath*: The corpus path.<br/>*obj [optional]*: TODO|Takes the specified corpus path (relative or absolute) and creates a valid absolute path with the namespace. Returns the created path.|string|
|**CreateRelativeCorpusPath(string, CdmContainerDefinition)**<br/>*objectPath*: The corpus path.<br/>*relativeTo [optional]*: The object that the path should be made relative to.|Takes the specified corpus path (relative or absolute) and creates a valid relative corpus path with the namespace. Returns the created path.|string|

