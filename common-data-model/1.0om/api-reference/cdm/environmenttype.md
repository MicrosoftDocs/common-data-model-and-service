---
title: Environment Type | Microsoft Docs
description: API reference for EnvironmentType.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 07/15/2021
ms.author: jibyun
---

# Environment Type

An enum class indicating the running environment type.

> [!NOTE]
> EnvironmentType is available in SDK version >= 1.3.0.

```csharp
public enum EnvironmentType
{
    DEV,
    TEST,
    PROD
}
```


* **DEV**: Development environment. Allows the more detailed information to be consumed in development environment.
* **TEST**: Testing In Production. Protects all information that may contain user-created content.
* **PROD**: Production environment. Protects all information that may contain user-created content.
