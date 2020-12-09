---
title: Event List | Microsoft Docs
description: API reference for EventList.
author: miroslavplese
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 08/20/2020
ms.author: miplese
---

# Event List

EventList is a supporting class for the logging system and allows subset of messages
emitted by the SDK to be collected and inspected by the SDK users. The events are stored in an ordered list, each element being a dictionary of string keys and string values.

Upon completion of the API call, the recorded events can be inspected by the host application to determine what step to take to address the issue. To simply list all events and their elements,a simple for-each like this will work:

```csharp
corpus.Ctx.Events.ForEach(
    logEntry => logEntry.ToList().ForEach(
        logEntryPair => Console.WriteLine($"{logEntryPair.Key}={logEntryPair.Value}")
    )
);
```

Note: this class is NOT a replacement for standard logging mechanism employed by the SDK. It serves specifically to offer immediate post-call context specific diagnostic information for the application to automate handling of certain common problems, such as invalid file name being supplied, file already being present on the file-system, etc.

```csharp
public class EventList extends List<Dictionary<string, string>>
```
*_Note: Typescript version of this class does not extend lists, it instead contains the list of events in its publicly accessible field allItems._

## Properties
|Name|Type|Description|
|---|---|---|
|IsRecording|bool|Specifies if the recording of events is in progress. Read-only.|
