---
title: Logger | Microsoft Docs
description: API reference for Logger.
author: jinichu

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
|**Debug(CdmCorpusContext, string, string, string, string)**<br/>*ctx*: The corpus context.<br/>*className*: Name of the class from which the log was issued.<br/>*method*:  Name of the method from which the log was issued.<br/>*corpusPath*: Corpus path of the CDM object related to the log being issued. May be null if the path is not available.<br/>*message*: The message to the log.|Log to DEBUG level.|void|
|**Info(CdmCorpusContext, string, string, string, string)**<br/>*ctx*: The corpus context.<br/>*className*: Name of the class from which the log was issued.<br/>*corpusPath*: Corpus path of the CDM object related to the log being issued. May be null if the path is not available.<br/>*method*:  Name of the method from which the log was issued.<br/>*message*: The message to the log.|Log to INFO level.|void|
|**Warning(string, CdmCorpusContext, string, string, string, CdmLogCode, params string[])**<br/>*ctx*: The corpus context.<br/>*className*: Name of the class from which the log was issued.<br/>*method*:  Name of the method from which the log was issued.<br/>*corpusPath*: Corpus path of the CDM object related to the log being issued. May be null if the path is not available.<br/>*code*:  The code, denotes the code enum for a message.<br/>*args*: The args, denotes the arguments inserted into the messages.|Log to WARNING level.|void|
|**Error(string, CdmCorpusContext, string, string, string, CdmLogCode, params string[])**<br/>*ctx*: The corpus context.<br/>*className*: Name of the class from which the log was issued.<br/>*method*:  Name of the method from which the log was issued.<br/>*corpusPath*: Corpus path of the CDM object related to the log being issued. May be null if the path is not available.<br/>*code*:  The code, denotes the code enum for a message.<br/>*args*: The args, denotes the arguments inserted into the messages.|Log to ERROR level.|void|
