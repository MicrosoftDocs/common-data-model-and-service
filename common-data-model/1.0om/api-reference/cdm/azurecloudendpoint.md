---
title: Azure Cloud Endpoint | Microsoft Docs
description: API reference for AzureCloudEndpoint.
author: llawwaii

ms.reviewer: deonhe 
ms.topic: article
ms.date: 09/07/2021
ms.author: weiluo
---

# Azure Cloud Endpoint

An enum class containing all the national cloud endpoints which enables [ADLSAdapter](./../storage/adlsadapter.md) to support [Azure AD authentication endpoints](/azure/active-directory/develop/authentication-national-cloud#azure-ad-authentication-endpoints) of each sovereign cloud.

> [!NOTE]
> AzureCloudEndpoint is available in SDK version >= 1.3.1. Use Pascal Case in adapter's configuration config.json file.

```csharp
public enum AzureCloudEndpoint
{
    AzurePublic,
    AzureChina,
    AzureGermany,
    AzureUsGovernment
}
```

* **AzurePublic**: Microsoft Azure public cloud. Maps to https://login.microsoftonline.com.
* **AzureChina**: Microsoft Chinese national cloud. Maps to https://login.chinacloudapi.cn.
* **AzureGermany**: Microsoft German national cloud. Maps to https://login.microsoftonline.de.
* **AzureUsGovernment**: US Government cloud. Maps to https://login.microsoftonline.us.

