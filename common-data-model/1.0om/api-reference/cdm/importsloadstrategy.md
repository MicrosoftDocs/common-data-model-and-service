---
title: Imports Load Strategy | Microsoft Docs
description: API reference for ImportsLoadStrategy.
author: violivei
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 09/25/2020
ms.author: violivei
---

# Imports Load Strategy

An enum class containing the options on when the Object Model will load the imported files. 

```csharp
public enum ImportsLoadStrategy
{
    // With the LazyLoad option, the imports will only be loaded when a symbol from an external file is needed by the Object Model.
    LazyLoad,
    // The imports will be loaded along with the file.
    Load,
    // The imports will not be loaded at all. If a symbol is needed the Object Model will log an error.
    DoNotLoad
}
```
