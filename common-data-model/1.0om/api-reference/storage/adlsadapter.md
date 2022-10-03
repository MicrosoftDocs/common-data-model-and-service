---
title: ADLS Adapter | Microsoft Docs
description: API reference for ADLSAdapter.
author: jinichu

ms.reviewer: deonhe 
ms.topic: article
ms.date: 08/24/2020
ms.author: jibyun
---

# ADLS Adapter

The ADLS adapter is the storage adapter that's used to interact with data on Azure Data Lake Storage Gen2.

```csharp
public class ADLSAdapter extends NetworkAdapter
```
*ADLSAdapter extends NetworkAdapter, StorageAdapterBase in Python.*

## Constructors
|Name|Description|
|---|---|
|**ADLSAdapter()**|Initializes a new instance of the [ADLSAdapter](adlsadapter.md) class. The user must apply an adapter configuration if this constructor is used. See *UpdateConfig(...)*.|
|**ADLSAdapter(string, string, string, string, string, [AzureCloudEndpoint](../cdm/azurecloudendpoint.md))**<br/>*hostname*: The ADLS hostname.<br/>*root*: The root path of the schema documents.<br/>*tenant*: The tenant.<br/>*clientId*: The client ID of the application accessing ADLS.<br/>*secret*: The secret for the application accessing ADLS.<br/>*endpoint [optional]*: The national cloud authentication endpoint, default is the public cloud endpoint.|Initializes a new instance of the [ADLSAdapter](adlsadapter.md) class with client ID/secret authentication.|
|**ADLSAdapter(string, string, string)**<br/>*hostname*: The ADLS hostname.<br/>*root*: The root path of the schema documents.<br/>*sharedKey*: The account/shared key.|Initializes a new instance of the [ADLSAdapter](adlsadapter.md) class with shared key authentication.|
|**ADLSAdapter(string, string, [TokenProvider](../utilities/tokenprovider.md))**<br/>*hostname*: The ADLS hostname.<br/>*root*: The root path of the schema documents.<br/>*tokenProvider*: The user-defined token provider.|Initializes a new instance of the [ADLSAdapter](adlsadapter.md) class with a user-defined implementation of the [TokenProvider](../utilities/tokenprovider.md) interface.|

## Properties
|Name|Type|Description|
|---|---|---|
|Root|string|The root path of the schema documents.|
|Hostname|string|The ADLS hostname.|
|Tenant|string|The tenant.|
|ClientId|string|The client ID of the application accessing ADLS.|
|Secret|string|The secret for the application accessing ADLS.|
|Endpoint|[AzureCloudEndpoint](../cdm/azurecloudendpoint.md)|The [Azure AD authentication endpoint](/azure/active-directory/develop/authentication-national-cloud#azure-ad-authentication-endpoints) for the application accessing ADLS.|
|SharedKey|string|The account or shared key.|
|SasToken|string|The SAS token.|
|Token Provider|[TokenProvider](../utilities/tokenprovider.md)|The token provider used to dynamically generate the access token.|
|LocationHint|string|The hint given to the reader application about where to find the the adapter implementation (for example, in Nuget, NPM, etc.).|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CanRead()**|Returns true, since the ADLS adapter can read data.|bool|
|**CanWrite()**|Returns true, since the ADLS adapter can write data to its source.|bool|
|**ReadAsync(string)**|See [StorageAdapterBase.ReadAsync(...)](storageadapterbase.md#methods).|Task\<string>|
|**WriteAsync(string, string)**|See [StorageAdapterBase.WriteAsync(...)](storageadapterbase.md#methods). Deletes empty file by default if write operation fails. Please set the following feature flag to **false** in [CdmCorpusContext](../utilities/resolvecontext.md) to skip delete: **ADLSAdapter_deleteEmptyFile**.|Task|
|**CreateAdapterPath(string)**|See [StorageAdapterBase.CreateAdapterPath(...)](storageadapterbase.md#methods).|string|
|**CreateCorpusPath(string)**|See [StorageAdapterBase.CreateCorpusPath(...)](storageadapterbase.md#methods).|string|
|**ClearCache()**|See [StorageAdapterBase.ClearCache()](storageadapterbase.md#methods). This method doesn't do anything if the ADLS adapter doesn't maintain a cache.|void|
|**ComputeLastModifiedTimeAsync(string)**|See [StorageAdapterBase.ComputeLastModifiedTimeAsync(...)](storageadapterbase.md#methods).|Task\<DateTimeOffset?>|
|**FetchAllFilesAsync(string)**|See [StorageAdapterBase.FetchAllFilesAsync(...)](storageadapterbase.md#methods).|Task\<List\<string>>|
|**FetchConfig()**|See [StorageAdapterBase.FetchConfig()](storageadapterbase.md#methods).|string|
|**UpdateConfig(string)**|See [StorageAdapterBase.UpdateConfig(...)](storageadapterbase.md#methods).|void|
|**CreateFileQueryCacheContext()**|See [StorageAdapterBase.CreateFileQueryCacheContext()](storageadapterbase.md#methods).|IDisposable|
