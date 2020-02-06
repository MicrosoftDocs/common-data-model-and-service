---
title: Logger | Microsoft Docs
description: API reference for Logger.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Logger

The logger formats log messages in a consistent way. This class only exists in C#, Python, and TypeScript.

```
public class Logger
```

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Debug(string, CdmCorpusContext, string, string)**<br/>*tag*: The tag, usually the class that is calling this method.<br/>*ctx*: The CDM corpus context.<br/>*message*: The message to log.<br/>*path [optional]*: The path, usually denotes the class and method calling this method.|Log to DEBUG level.|void|
|**Info(string, CdmCorpusContext, string, string)**<br/>*tag*: The tag, usually the class that is calling this method.<br/>*ctx*: The CDM corpus context.<br/>*message*: The message to log.<br/>*path [optional]*: The path, usually denotes the class and method calling this method.|Log to INFO level.|void|
|**Warning(string, CdmCorpusContext, string, string)**<br/>*tag*: The tag, usually the class that is calling this method.<br/>*ctx*: The CDM corpus context.<br/>*message*: The message to log.<br/>*path [optional]*: The path, usually denotes the class and method calling this method.|Log to WARNING level.|void|
|**Error(string, CdmCorpusContext, string, string)**<br/>*tag*: The tag, usually the class that is calling this method.<br/>*ctx*: The CDM corpus context.<br/>*message*: The message to log.<br/>*path [optional]*: The path, usually denotes the class and method calling this method.|Log to ERROR level.|void|
