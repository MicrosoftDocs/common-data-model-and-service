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

The logger formats log messages in a consistent way.

```csharp
public class Logger
```

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Debug(CdmCorpusContext, string, string, string, string)**<br/>*ctx*: The corpus context.<br/>*className*: The className, usually the class that's calling this method.<br/>*method*: The method, usually method calling this method.<br/>*corpusPath*: The corpusPath, usually denotes corpus path of the document.<br/>*message*: The message to log.|Log to DEBUG level.|void|
|**Info(CdmCorpusContext, string, string, string, string)**<br/>*ctx*: The corpus context.<br/>*className*: The className, usually the class that's calling this method..<br/>*corpusPath*: The corpusPath, usually denotes corpus path of the document.<br/>*method*: The method, usually method calling this method.<br/>*message*: The message to log.|Log to INFO level.|void|
|**Warning(string, CdmCorpusContext, string, string, string, CdmLogCode, params string[])**<br/>*ctx*: The corpus context.<br/>*className*: The className, usually the class that's calling this method.<br/>*method*: The method, usually method calling this method..<br/>*corpusPath*: The corpusPath, usually denotes corpus path of the document.<br/>*code*:  The code, denotes the code enum for a message.<br/>*args*: The args, denotes the arguments inserted into the messages.|Log to WARNING level.|void|
|**Error(string, CdmCorpusContext, string, string, string, CdmLogCode, params string[])**<br/>*ctx*: The corpus context.<br/>*className*: The className, usually the class that's calling this method.<br/>*method*: The method, usually method calling this method..<br/>*corpusPath*: The corpusPath, usually denotes corpus path of the document.<br/>*code*:  The code, denotes the code enum for a message.<br/>*args*: The args, denotes the arguments inserted into the messages.|Log to ERROR level.|void|
