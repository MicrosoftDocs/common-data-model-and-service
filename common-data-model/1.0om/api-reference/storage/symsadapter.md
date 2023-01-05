---
title: SyMS Adapter | Microsoft Docs
description: API reference for SymsAdapter.
author: supawa

ms.topic: article
ms.date: 09/01/2021
ms.author: supawa
---
# SyMS Adapter

The SyMS adapter is a Common Data Model SDK storage adapter that is used to interact with metadata stored in a Synapse workspace, by providing a standardized representation of the workspace. For more details about its use, please refer to this [article](../../../sdk/syms-cdm.md).

```csharp
public class SymsAdapter extends NetworkAdapter
```

## Constructors
|Name|Description|
|---|---|
|**SymsAdapter()**|Initializes a new instance of the [SymsAdapter](symsadapter.md) class. The user must apply an adapter configuration if this constructor is used. See *UpdateConfig(...)*.|
|**SymsAdapter(string, string, string, string)**<br/>*endpoint*: The SyMS workspace endpoint.<br/>*tenant*: The tenant.<br/>*clientId*: The client ID of the application accessing SyMS.<br/>*secret*: The secret for the application accessing SyMS.|Initializes a new instance of the [SymsAdapter](symsadapter.md) class with client ID/secret authentication.|
|**SymsAdapter(string, string, [TokenProvider](../utilities/tokenprovider.md))**<br/>*endpoint*: The SyMS workspace endpoint.<br/>*tokenProvider*: The user-defined token provider.|Initializes a new instance of the [SymsAdapter](symsadapter.md) class with a user-defined implementation of the [TokenProvider](../utilities/tokenprovider.md) interface.|

## Properties
|Name|Type|Description|
|---|---|---|
|Endpoint|string|The SyMS workspace endpoint.|
|Tenant|string|The tenant.|
|ClientId|string|The client ID of the application accessing SyMS.|
|Secret|string|The secret for the application accessing SyMS.|
|Token Provider|[TokenProvider](../utilities/tokenprovider.md)|The token provider used to dynamically generate the access token.|


## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the SyMS adapter can read data.|bool|
|**CanWrite()**|Returns true, since the SyMS adapter can write data to its source.|bool|
|**ReadAsync(string)**| Reads the database or table from SyMS workspace.|
|**WriteAsync(string, string)**| Create/Update/Remove database or table from SyMS workspace. |
|**CreateAdapterPath(string)**|See [StorageAdapterBase.CreateAdapterPath(...)](storageadapterbase.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapterBase.CreateCorpusPath(...)](storageadapterbase.md#methods).|string|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapterBase.ComputeLastModifiedTimeAsync(...)](storageadapterbase.md#methods).|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**| Gets all tables as a list from SyMS database.|Task\<List\<string>>|
|**FetchAllFilesMetadataAsync(string)**|See [StorageAdapterBase.FetchAllFilesMetadataAsync(...)](storageadapterbase.md#methods).|Task\<IDictionary\<string, CdmFileMetadata>>|
|**FetchConfig()**|See [StorageAdapterBase.FetchConfig()](storageadapterbase.md#methods).|string|
|**UpdateConfig(string)**|See [StorageAdapterBase.UpdateConfig(...)](storageadapterbase.md#methods).|void|
