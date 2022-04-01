---
title: Storage Manager | Microsoft Docs
description: API reference for StorageManager.
author: jinichu

ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Storage Manager

The storage manager acts like a storage for the [corpus](../cdm/corpus.md) and is used to interact with [storage adapters](storageadapter.md).

```csharp
public class StorageManager
```

## Constructors
|Name|Description|
|---|---|
|**StorageManager([CdmCorpusDefinition](../cdm/corpus.md))**<br/>*corpus*: The corpus that owns this storage manager.|Initializes a new instance of the [StorageManager](storagemanager.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|DefaultNamespace|string|The namespace that will be used when one isn't explicitly provided.|
|NamespaceAdapters|IDictionary\<string, [StorageAdapter](storageadapter.md)>|The dictionary of registered namespaces to storage adapters.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Mount(string, [StorageAdapter](storageadapter.md))**<br/>*nameSpace*: The namespace to mount.<br/>*adapter*: The storage adapter.|Mounts a namespace to the specified adapter.<br/><br/>For example, the corpus paths under a namespace named "local" would have the following form: "local:/path/to/document".|void|
|**MountFromConfig(string, bool)**<br/>*adapterConfig*: A JSON string representing the configurations for the adapters we want to create and mount.<br/>*doesReturnErrorList [optional]*: A boolean that denotes whether to return a list of configurations for adapters that were not recognized. The default value is false.|Creates storage adapters using the specified adapter configuration and mounts them to the namespaces found in the configuration. Multiple adapters can be specified in the configuration to be created and mounted. Returns a list of configurations for unrecognized adapters.|List\<string>|
|**Unmount(string)**<br/>*nameSpace*: The namespace to unmount.|Unmounts a namespace. Returns true if the unmount is successful, false otherwise.|bool|
|**FetchAdapter(string)**<br/>*nameSpace*: The namespace.|Retrieves the adapter for the specified namespace.|[StorageAdapter](storageadapter.md)|
|**FetchRootFolder(string)**<br/>*nameSpace*: The namespace.|Given the namespace of a registered storage adapter, returns the root folder containing the sub-folders and documents.|[CdmFolderDefinition](../cdm/folder.md)|
|**AdapterPathToCorpusPath(string)**<br/>*adapterPath*: The path.|Takes the specified storage adapter domain path, figures out the right adapter to use, and then returns a corpus path.|string|
|**CorpusPathToAdapterPath(string)**<br/>*corpusPath*: The path.|Takes the specified corpus path, figures out the right adapter to use, and then returns a storage adapter domain path.|string|
|**CreateAbsoluteCorpusPath(string, [CdmObject](../cdm/cdmobject.md))**<br/>*objectPath*: The corpus path.<br/>*obj [optional]*: The object that the *objectPath* parameter should be relative to. If not set, *objectPath* will be assumed to be relative to the root folder in the default namespace.|Takes the specified corpus path (relative or absolute) and creates a valid absolute path with the namespace. Returns the created path.|string|
|**CreateRelativeCorpusPath(string, CdmContainerDefinition)**<br/>*objectPath*: The corpus path.<br/>*relativeTo [optional]*: The object that the path should be made relative to.|Takes the specified corpus path (relative or absolute) and creates a valid relative corpus path with the namespace. Returns the created path.|string|
|**FetchConfig()**|Generates a JSON string representing the configurations of all the adapters that exist on this storage manager.|string|
|**SaveAdaptersConfigAsync(string, [StorageAdapter](storageadapter.md))**<br/>*name*: The name of the file to save. <br/>*adapter*: The storage adapter to use to save the configurations to a file.|Saves the configurations of all the adapters that exist on this storage manager to a file with the specified name. Uses the specified adapter to save.|void|
