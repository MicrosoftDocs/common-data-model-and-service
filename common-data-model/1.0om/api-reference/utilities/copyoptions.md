---
title: Copy Options | Microsoft Docs
description: API reference for CopyOptions.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Copy Options

Copy options are options to be used when copying a [CdmObject](../cdm/cdmobject.md) or when converting a [manifest](../cdm/manifest.md) to a persisted type.

```csharp
public class CopyOptions
```

## Constructors
|Name|Description|
|---|---|
|**CopyOptions()**|Initializes a new instance of the [CopyOptions](copyoptions.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|SaveConfigFile|bool|Determines if the config.json file should be saved or not when calling SaveAsAsync.|
|StringRefs|bool?|Denotes whether to turn simple named string object references into objects with a relative path.|



