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

An enum class containing the security/privacy levels of running environment.

```csharp
public enum EnvironmentType
{
    DEV,
    TIP,
    PROD
}
```


* **DEV**: Development environment. Allows the more detailed information to be consumed in development environment.
* **TIP**: Testing In Production. Protects all information that may contain user-created contents.
* **PROD**: Production environment. Protects all information that may contain user-created contents.
