---
title: Imports Load Strategy | Microsoft Docs
description: API reference for ImportsLoadStrategy.
author: violivei

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 11/09/2020
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

* **LazyLoad**: the imports will only load when the object model needs access to definitions that exist in the imported files.
For example, if `FetchObjectAsync` is called, the imports will not load because they are not required immediately. If after loading the document, an API like `CreateResolvedEntityAsync` is called, the imports will load before continuing the run.
* **Load**: the imports will be loaded along with the document when calling `FetchObjectAsync`.
* **DoNotLoad**: the imports will not load at any point. The object model will log an error if it needs an import to load during the run.
