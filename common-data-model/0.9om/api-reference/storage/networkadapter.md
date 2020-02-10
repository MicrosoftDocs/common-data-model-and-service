---
title: Network Adapter | Microsoft Docs
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
public abstract class NetworkAdapter
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
|**UpdateNetworkConfig(string)**<br/>*config*: A JSON string representing the configuration for the network adapter.|Updates the network specific properties on the network adapter using the specified configuration.|void|
|**FetchNetworkConfig()**|Constructs the network adapter's configuration. Returns a list of JProperty objects containing the network specific properties.|List\<JProperty>|
|**ExecuteRequest(CdmHttpRequest)**<br/>*httpRequest*: The HTTP request to execute.<br/><br/>*read(...) in Python.*|Executes an HTTP request and returns the response of the request.|Task\<CdmHttpResponse>|
|**Dispose()**<br/><br/>*Only in C#.*|Disposes the CDM HTTP client. Exists only in C#.|void|


