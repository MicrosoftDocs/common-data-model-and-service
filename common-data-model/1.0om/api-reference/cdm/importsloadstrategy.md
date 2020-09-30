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

* **LazyLoad**: the imports will only load when the Object Model needs access to definitions existent in the imported files.
For example, if `FetchObjectAsync` is called, the imports will not load since they are not required right away. If after loading the document, an API like `CreateResolvedEntityAsync` is called, the imports will load before continuing the execution.
* **Load**: the imports will be loaded along with the document when calling `FetchObjectAsync`.
* **DoNotLoad**: the imports will not load at any point. The Object Model will log an error if it needs an import to load during the execution.
