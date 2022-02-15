---
title: Telemetry Client | Microsoft Docs
description: API reference for TelemetryClient.
author: honchenMS

ms.reviewer: deonhe 
ms.topic: article
ms.date: 07/15/2021
ms.author: t-honchen
---

# Telemetry Client

> [!IMPORTANT]
> Telemetry Client is currently in PREVIEW.

The interface that can be implemented to ingest telemetry into databases.

> [!NOTE]
> TelemetryClient is available in SDK version >= 1.3.0.

```csharp
public interface TelemetryClient
```
*This interface is substituted with a regular class in Python.*

## Methods
|Name|Description|Return Type|
|---|---|---|
|**AddToIngestionQueue(string, [CdmStatusLevel](../cdm/statuslevel.md), string, string, string, string, bool, CdmLogCode)**<br/>*timestamp*: The timestamp of the log.<br/>*level*: Logging status level.<br/>*className*: Name of the class from which the log was issued.<br/>*method*:  Name of the method from which the log was issued.<br/>*corpusPath*: Corpus path of the CDM object related to the log being issued. May be null if the path is not available.<br/>*message*: The message to the log.<br/>*requireIngestion*: Whether the log is required to be ingested. Optional, default to be false.<br/>*code*: Optional warning or error code to be logged.|Enqueue the request queue with the information to be logged.|void|
|**Enable()**|Enable the telemetry client and start ingestion.|void|
