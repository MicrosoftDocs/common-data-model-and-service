---
title: Event Callback | Microsoft Docs
description: API reference for EventCallback.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Event Callback

The event callback represents the callback object used in [CdmCorpusDefinition.SetEventCallback(...)](../cdm/corpus.md#methods).

```
public class EventCallback
```

## Properties
|Name|Type|Description|
|---|---|---|
|Invoke<br/><br/>*apply(...) in Java.*|Action\<[CdmStatusLevel](../cdm/statuslevel.md), string>|Invokes a log message with the status level.|


