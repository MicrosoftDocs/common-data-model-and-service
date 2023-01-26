---
title: Telemetry Configuration | Microsoft Docs
description: API reference for TelemetryConfig.
author: honchenMS

ms.reviewer: deonhe 
ms.topic: article
ms.date: 07/15/2021
ms.author: t-honchen
---

# Telemetry Configuration

> [!IMPORTANT]
> Telemetry Configuration is currently in PREVIEW.

Configuration information to establish a connection with the database for telemetry collection.

> [!NOTE]
> TelemetryConfig is available in SDK version >= 1.3.0.

```csharp
public class TelemetryConfig
```

## Constructors
|Name|Description|
|---|---|
|**TelemetryConfig([TokenProvider](tokenprovider.md), [EnvironmentType](../cdm/environmenttype.md), string, bool)**<br/>*tokenProvider*: The user-defined token provider.<br/>*ingestAtLevel*: Kusto ingestion security level for the execution environment.<br/>*region*: Optional geographic information, e.g. "West US".|Initializes a new instance of the [TelemetryConfig](telemetryconfig.md) class with a user-defined implementation of the [TokenProvider](tokenprovider.md) interface.|<br/>*removeUserContent*: Optional flag allowing CDM telemetry client to ingest user generated content (for example filenames)|
|**TelemetryConfig(string, string, string, string, string, [EnvironmentType](../cdm/environmenttype.md), string, AzureCloudInstance, bool)**<br/>*tenantId*: Azure AD tenant (directory) ID.<br/>*clientId*: The client ID of the AAD application accessing Kusto.<br/>*secret*: The client secret of the AAD application accessing Kusto.<br/>*clusterName*: Kusto cluster into which the telemetry will be ingested.<br/>*databaseName*: Kusto database name.<br/>*ingestAtLevel*: Kusto ingestion security level for the execution environment.<br/>*region*: Optional geographic information, for example "West US".<br/>*cloudInstance*: Optional Azure cloud instance, default to be `AzureCloudInstance.AzurePublic`.|Initializes a new instance of the [TelemetryConfig](telemetryconfig.md) class with client ID/secret authentication and default log table names.|<br/>*removeUserContent*: Optional flag allowing CDM telemetry client to ingest user generated content (for example filenames)|
|**TelemetryConfig(string, string, string, string, string, string, string, string, [EnvironmentType](../cdm/environmenttype.md), string, AzureCloudInstance, bool)**<br/>*tenantId*: Azure AD tenant (directory) ID.<br/>*clientId*: The client ID of the AAD application accessing Kusto.<br/>*secret*: The client secret of the AAD application accessing Kusto.<br/>*clusterName*: Kusto cluster into which the telemetry will be ingested.<br/>*databaseName*: Kusto database name.<br/>*infoTable*: Table for storing informational logs.<br/>*warningTable*: Table for storing warning logs.<br/>*errorTable*: Table for storing error logs.<br/>*ingestAtLevel*: Kusto ingestion security level for the execution environment.<br/>*region*: Optional geographic information, for example "West US".<br/>*cloudInstance*: Optional Azure cloud instance, default to be `AzureCloudInstance.AzurePublic`.|Initializes a new instance of the [TelemetryConfig](telemetryconfig.md) class with client ID/secret authentication and custom log table names.|<br/>*removeUserContent*: Optional flag allowing CDM telemetry client to ingest user generated content (for example filenames)|

## Properties
|Name|Type|Description|
|---|---|---|
|TenantId|string|Azure AD tenant (directory) ID.|
|ClientId|string|The client ID of the AAD application.|
|Secret|string|The client secret of the AAD application.|
|Region|string|User geographic info.|
|KustoClusterName|string|Kusto (ADX) cluster name.|
|KustoDatabaseName|string|Kusto database name.|
|KustoInfoLogTable|string|Kusto table for informational logs, default to be *infoLogs*.|
|KustoWarningLogTable|string|Kusto table for warning logs, default to be *warningLogs*.|
|KustoErrorLogTable|string|Kusto table for error logs, default to be *errorLogs*.|
|CloudInstance|AzureCloudInstance|The Azure cloud instance.|
|IngestAtLevel|[EnvironmentType](../cdm/environmenttype.md)|The level of detail to be logged into the Kusto database depending on the environment.|
|Token Provider|[TokenProvider](tokenprovider.md)|The token provider used to dynamically generate the access token.|
