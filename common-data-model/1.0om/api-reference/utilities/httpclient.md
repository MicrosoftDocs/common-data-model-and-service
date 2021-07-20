---
title: HTTP Client | Microsoft Docs
description: API reference for CdmHttpClient.
author: honchenMS
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 07/15/2021
ms.author: t-honchen
---

# HTTP Client

CDM Http Client is an HTTP client that implements retry logic to execute retries.

```csharp
public class CdmHttpClient
```

## Constructors
|Name|Description|
|---|---|
|**CdmHttpClient(string, HttpMessageHandler)**<br/>*apiEndpoint*: Optional API endpoint.<br/>*handler*: Optional HTTP message handler, handler can be changed to support testing and so on.|Initializes a new instance of the [CdmHttpClient](httpclient.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|**Callback(CdmHttpResponse, bool, int)**<br/>*response*: The CDM Http response.<br/>*hasFailed*: Denotes whether a request has failed.<br/>*retryNumber*: The number of retries happened (starting from 1).|delegate|The callback function that gets called after the request is finished in CDM Http client.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**SendAsync(CdmHttpRequest, Callback, CdmCorpusContext)**<br/>*cdmRequest*: The CDM Http request.<br/>*callback*: The callback that gets executed after the request finishes.<br/>*ctx*: The corpus context.|Send a CDM request with the retry logic and returns an HTTP response.|Task\<CdmHttpResponse>|
