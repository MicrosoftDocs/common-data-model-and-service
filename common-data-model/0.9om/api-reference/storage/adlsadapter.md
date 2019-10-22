---
title: ADLS Adapter - Common Data Model | Microsoft Docs
description: Reference for ADLSAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# ADLS Adapter

The ADLS adapter is the storage adapter that is used to interact with data on Azure Data Lake Storage Gen2.

```
public class ADLSAdapter extends NetworkAdapter, StorageAdapter
```

## Constructors
|Name|Description|
|---|---|
|**ADLSAdapter(string, string, string, string, string)**<br/>*hostname*: The hostname of ADLS.<br/>*root*: The root path of the schema documents.<br/>*tenant*: The tenant.<br/>*clientId*: The client ID of the application accessing ADLS.<br/>*secret*: The secret for the application accessing ADLS.|Initializes a new instance of the ADLSAdapter class with client ID/secret authentication.|
|**ADLSAdapter(string, string, string)**<br/>*hostname*: The hostname of ADLS.<br/>*root*: The root path of the schema documents.<br/>*sharedKey*: The account/shared key.|Initializes a new instance of the ADLSAdapter class with shared key authentication.|

## Properties
|Name|Type|Description|
|---|---|---|
|Root|string|The root path of the schema documents.|
|Hostname|string| The hostname of ADLS.|
|Tenant|string|The tenant.|
|ClientId|string|The client ID of the application accessing ADLS.|
|Secret|string|The secret for the application accessing ADLS.|
|SharedKey|string|The account/shared key.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the ADLSAdapter can read data.|boolean|
|**CanWrite()**|Returns true, since the ADLSAdapter can write data to its source.|boolean|
|**ReadAsync(string)**|See *StorageAdapter.ReadAsync(...)*.|Task\<string>|
|**WriteAsync(string, dynamic)**|See *StorageAdapter.WriteAsync(...)*.|Task|
|**CreateAdapterPath(string)**|See *StorageAdapter.CreateAdapterPath(...)*.|string|
|**CreateCorpusPath(string)**|See *StorageAdapter.CreateCorpusPath(...)*.|string|
|**ClearCache()**|See *StorageAdapter.ClearCache()*. This method doesn't do anything because the ADLSAdapter doesn't maintain a cache.|void|
|**ComputeLastModifiedTimeAsync(string)**|See *StorageAdapter.ComputeLastModifiedTimeAsync(...)*.|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See *StorageAdapter.FetchAllFilesAsync(...)*.|Task\<List\<string>>|
