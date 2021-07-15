---
title: Telemetry Kusto Client | Microsoft Docs
description: API reference for TelemetryKustoClient.
author: honchenMS
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 07/15/2021
ms.author: t-honchen
---

# Telemetry Kusto Client

> [!IMPORTANT]
> Telemetry Kusto Client is currently in PREVIEW.

The telemetry Kusto client is a client for ingesting logs into Kusto database. 

For the client to function as expected, the log tables in the Kusto database must have the following schema:<br>
`timestamp: datetime, className: string, method: string, message: string, code: string, corpusPath: string, correlationId: string, apiCorrelationId: string, appId: string, property: string`.

```csharp
public class TelemetryKustoClient : TelemetryClient
```

## Constructors
|Name|Description|
|---|---|
|**TelemetryKustoClient(CdmCorpusContext, [TelemetryConfig](telemetryconfig.md))**<br/>*ctx*: The corpus context.<br/>*config*: The configuration for the client.|Initializes a new instance of the [TelemetryKustoClient](telemetrykustoclient.md) class with configuration specified.|

## Properties
|Name|Type|Description|
|---|---|---|
|MaxNumRetries|int|Maximum number of retries allowed for an HTTP request.|
|MaxTimeoutMilliseconds|int|Maximum timeout for completing an HTTP request including retries.|
|TimeoutMilliseconds|int|Maximum timeout for a single HTTP request.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**AddToIngestionQueue(string, [CdmStatusLevel](../cdm/statuslevel.md), string, string, string, string, bool, CdmLogCode)**<br/>*timestamp*: The timestamp of the log.<br/>*level*: Logging status level.<br/>*className*: Name of the class from which the log was issued.<br/>*method*:  Name of the method from which the log was issued.<br/>*corpusPath*: Corpus path of the CDM object related to the log being issued. May be null if the path is not available.<br/>*message*: The message to the log.<br/>*requireIngestion*: Whether the log is required to be ingested. Optional, default to be false.<br/>*code*: Optional warning or error code to be logged.|Enqueue the request queue with the information to be logged into Kusto.|void|
|**CheckRequestQueueIsEmpty()**|Check if all the logs have been dequeued from the request queue and got ingested.|bool|
|**Enable()**|Enable the Kusto client to start ingestion on a background thread.|void|
|**PostKustoQuery(string)**<br/>*query*: The Kusto query command to be posted to the cluster.|Get an authorization token and send the ingestion command to Kusto.|Task|
