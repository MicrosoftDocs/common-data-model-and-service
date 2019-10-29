---
title: Network Adapter - Common Data Model | Microsoft Docs
description: API reference for NetworkAdapter.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Network Adapter

This is an abstract class that contains logic for adapters that deal with data across a network. See [GithubAdapter](githubadapter.md), [ADLSAdapter](adlsadapter.md), or [RemoteAdapter](remoteadapter.md) for usage of this class. When extending this class, a CdmHttpClient has to be defined with the specified endpoint and callback function in the constructor. Then the class helper methods can be used to set up CDM HTTP requests and read data. If *Timeout*, *MaxmimumTimeout*, or *NumberOfRetries* are not specified, the default values for those properties that are specified in this class will be used. 

```
public abstract class NetworkAdapter extends IDisposable
```

## Properties
|Name|Type|Description|
|---|---|---|
|Timeout|TimeSpan?|The timeout for an HTTP request.|
|MaximumTimeout|TimeSpan?|The maximum timeout for all retried HTTP requests.|
|NumberOfRetries|int|The maximum number of retries for an HTTP request. The default value is 0.|
|WaitTimeCallback|CdmHttpClient.Callback|The wait time callback that gets called after each request is executed.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Dispose()**|Disposes the CDM HTTP client (only in C#).|void|


