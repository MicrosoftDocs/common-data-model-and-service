---
title: Environment Type | Microsoft Docs
description: API reference for EnvironmentType.
author: honchenMS
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 07/15/2021
ms.author: t-honchen
---

# Environment Type

An enum class indicating the running environment type.

> [!NOTE]
> EnvironmentType is available in SDK version >= 1.2.4.

```csharp
public enum EnvironmentType
{
    DEV,
    TEST,
    PROD
}
```


* **DEV**: Development environment. Allows the more detailed information to be consumed in development environment.
* **TEST**: Testing In Production. Protects all information that may contain user-created contents.
* **PROD**: Production environment. Protects all information that may contain user-created contents.
