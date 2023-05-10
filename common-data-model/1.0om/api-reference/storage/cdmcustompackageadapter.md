---
title: Common Data Model custom package adapter | Microsoft Docs
description: The API reference for CdmCustomPackageAdapter.
author: mafrisci

ms.reviewer: deonhe 
ms.topic: article
ms.date: 05/10/2023
ms.author: mafrisci
---

# Common Data Model custom package adapter

The Common Data Model custom package adapter is the storage adapter that can load any custom package that contains CDM schema documents. 


```csharp
public class CdmCustomPackageAdapter extends StorageAdapterBase
```

## Constructors
|Name|Description|
|---|---|
|**CdmCustomPackageAdapter(string, string)**<br/>*packageName*: The name of the package that contains CDM schemas.<br/>*root [optional]*: The root path to the schema documents in the package, default is "Resources".|Initializes a new instance of the [CdmCustomPackageAdapter](cdmcustompackageadapter.md) class.|
|**CdmCustomPackageAdapter(object, string)**<br/>*assembly*: The package object that contains the CDM schemas. This object type will differ depending on what language is used.<br/>*root [optional]* The root path to the schema documents in the package, default is "Resources".|Initializes a new instance of the [CdmCustomPackageAdapter](cdmcustompackageadapter.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, if the Common Data Model custom package adapter can read data.|bool|
|**CanWrite()**|Returns false, if the Common Data Model custom package adapter can't write data to its source.|bool|
|**ReadAsync(string)**|See [StorageAdapterBase.ReadAsync(...)](storageadapterbase.md#methods).|Task\<string>|
|**WriteAsync(string, string)**|See [StorageAdapterBase.WriteAsync(...)](storageadapterbase.md#methods). Throws a *NotImplementedException* if the Common Data Model custom package adapter can't write to its source.|Task|
|**CreateAdapterPath(string)**|See [StorageAdapterBase.CreateAdapterPath(...)](storageadapterbase.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapterBase.CreateCorpusPath(...)](storageadapterbase.md#methods).|string|
|**ClearCache()**|See [StorageAdapterBase.ClearCache()](storageadapterbase.md#methods).|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapterBase.ComputeLastModifiedTimeAsync(...)](storageadapterbase.md#methods). Returns Time.Now().|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapterBase.FetchAllFilesAsync(...)](storageadapterbase.md#methods). Returns null.|Task\<List\<string>>|
|**FetchConfig()**|See [StorageAdapterBase.FetchConfig()](storageadapterbase.md#methods).|string|
|**UpdateConfig(string)**|See [StorageAdapterBase.UpdateConfig(...)](storageadapterbase.md#methods).|void|
|**CreateFileQueryCacheContext()**|See [StorageAdapterBase.CreateFileQueryCacheContext()](storageadapterbase.md#methods).|IDisposable|

