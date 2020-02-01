---
title: API reference for utilities | Microsoft Docs
description: API reference for utilities.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Utilities

## Overview

This section contains the commonly used utility classes. 

The code can be found [here](https://github.com/microsoft/CDM/tree/master/objectModel/CSharp/Microsoft.CommonDataModel.ObjectModel/Utilities) (C#).

## Classes
|Name|Description|
|---|---|
|[Copy Options](copyoptions.md)|Options to be used when copying a [CdmObject](../cdm/cdmobject.md) or when converting a [manifest](../cdm/manifest.md) to a persisted type.|
|[Event Callback](callback.md)|Represents the callback object used in [CdmCorpusDefinition.SetEventCallback(...)](../cdm/corpus.md#methods).|
|[Logger](logger.md)|Formats log messages in a consistent way.| 
|[Resolve Options](resolveoptions.md)|Options to be used for resolution. If it is an optional argument to a method, it is safe to leave it null because default resolve options would just be created and used instead.|

