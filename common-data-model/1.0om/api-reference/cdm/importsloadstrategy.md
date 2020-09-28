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

An enum class that specifies when the Object Model will load the documents imported by the document being loaded.

```csharp
public enum ImportsLoadStrategy
{
    LazyLoad,
    Load,
    DoNotLoad
}
```

* **LazyLoad**: the imports will only be loaded when a symbol from an external file is needed by the Object Model.
For example, if `FetchObjectAsync` is called the imports will not be loaded since they are not required right away. If an API like `CreateResolvedEntityAsync` is called the imports are needed and will be loaded before continuing the execution.
* **Load**: the imports will be loaded along with the file when calling `FetchObjectAsync`.
* **DoNotLoad**: the imports will not be loaded at all. If an import is needed the Object Model will log an error.
