---
title: Common Data Model standards adapter | Microsoft Docs
description: The API reference for CdmStandardsAdapter.
author: violivei

ms.reviewer: deonhe 
ms.topic: article
ms.date: 08/24/2020
ms.author: violivei
---

# Common Data Model standards adapter

The Common Data Model standards adapter is the storage adapter that points to the Common Data Model public standards schema documents. 
This adapter is configured to read from the 'Microsoft.CommonDataModel.ObjectModel.CdmStandards' package that is a dependency of the SDK.

The standards schema documents are also published on [GitHub](https://github.com/microsoft/CDM/tree/master/schemaDocuments) for reference purposes.


```csharp
public class CdmStandardsAdapter extends StorageAdapterBase
```

## Constructors
|Name|Description|
|---|---|
|**CdmStandardsAdapter()**|Initializes a new instance of the [CdmStandardsAdapter](cdmstandardsadapter.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, if the Common Data Model standards adapter can read data.|bool|
|**CanWrite()**|Returns false, if the Common Data Model standards adapter can't write data to its source.|bool|
|**ReadAsync(string)**|See [StorageAdapterBase.ReadAsync(...)](storageadapterbase.md#methods).|Task\<string>|
|**WriteAsync(string, string)**|See [StorageAdapterBase.WriteAsync(...)](storageadapterbase.md#methods). Throws a *NotImplementedException* if the Common Data Model standards adapter can't write to its source.|Task|
|**CreateAdapterPath(string)**|See [StorageAdapterBase.CreateAdapterPath(...)](storageadapterbase.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapterBase.CreateCorpusPath(...)](storageadapterbase.md#methods).|string|
|**ClearCache()**|See [StorageAdapterBase.ClearCache()](storageadapterbase.md#methods).|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapterBase.ComputeLastModifiedTimeAsync(...)](storageadapterbase.md#methods). Returns Time.Now().|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapterBase.FetchAllFilesAsync(...)](storageadapterbase.md#methods). Returns null.|Task\<List\<string>>|
|**FetchConfig()**|See [StorageAdapterBase.FetchConfig()](storageadapterbase.md#methods).|string|
|**UpdateConfig(string)**|See [StorageAdapterBase.UpdateConfig(...)](storageadapterbase.md#methods).|void|
|**CreateFileQueryCacheContext()**|See [StorageAdapterBase.CreateFileQueryCacheContext()](storageadapterbase.md#methods).|IDisposable|

