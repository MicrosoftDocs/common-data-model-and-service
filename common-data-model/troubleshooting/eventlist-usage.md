---
title: Using EventList to analyze API behavior | Microsoft Docs
description: This article helps developer to analyze API behaviour using EventList class.
author: surenderpawar
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 02/15/2021
ms.author: supawa
---

# Using EventList to analyze API behavior

## Overview
Services implementing Common Data Model features sometime perform many API calls to the SDK which accumulates considerable number of log messages in plain string form through asynchronous callbacks, making it difficult for the service to know and understand what happened after each call. 

To help developers, [EventList](../1.0om/api-reference/utilities/eventlist.md) has been introduced which is initialized on commonly used API entry points and performs collection of log messages emitted by underlying code from the entry to the exit, to be then retrievable by clients easily after relevant API calls are complete.

## Usage
EventList is a supporting class for the logging system and allows subset of messages emitted by the SDK to be collected and inspected by the SDK users. The events are stored in an ordered list, each element being a dictionary of string keys and string values. Upon completion of the API call, the recorded events can be inspected by the host application to determine what step to take to address the issue. To simply list all events and their elements, a simple for-each like this will work: 
```csharp
     corpus.Ctx.Events.ForEach( 
        logEntry => logEntry.ToList().ForEach( 
            logEntryPair => Console.WriteLine($"{logEntryPair.Key}={logEntryPair.Value}") 
         ) 
     ); 
```
 >Note :
 > <br>This class is NOT a replacement for the standard logging mechanism employed by the SDK. It serves specifically to offer immediate post-call context specific diagnostic information for the application to automate handling of certain common problems, such as invalid file name being supplied, file already being present on the filesystem, etc. 

## Sample Code 
  This sample code shows the usage of EventList class. It creates a 'manifest' object and adds entity. If resolution fails, iterate over EventList object to analysis the error.

When iterate over Events object following errors can be observed.<br> "Cannot resolve the manifest 'dummy' because it has not been added to a folder" <br>

Please follow the comments to understand the code.
```csharp
    CdmCorpusDefinition corpus = new CdmCorpusDefinition(); 
    corpus.Storage.DefaultNamespace = "local"; 
    corpus.Storage.Mount("local", new LocalAdapter(".")); 
  
    // set event call back with warning (or error) and CorrelationId. Event class object record message as per the logging level.   
    corpus.SetEventCallback(eventCallback,  // event call back function    
        CdmStatusLevel.Warning,  // logging level( info , warning, error).This level of logging stored in evenlistclass object. note: Default is info if not set.   
        DummyCorrelationId);    // CorrelationId appended to log messages sent back callback function.
  
    var manifest = corpus.MakeObject<CdmManifestDefinition>(CdmObjectType.ManifestDef, "dummy"); 

    //corpus.Storage.FetchRootFolder("local").Documents.Add(manifest); 
    var entity1 = corpus.MakeObject<CdmEntityDefinition>(CdmObjectType.EntityDef, "MyEntity1"); 
    var someAttrib1 = corpus.MakeObject<CdmTypeAttributeDefinition>(CdmObjectType.TypeAttributeDef, "someAttrib1", false); 
    someAttrib1.DataType = corpus.MakeRef<CdmDataTypeReference>(CdmObjectType.DataTypeRef, "entityId", true); 
    entity1.Attributes.Add(someAttrib1); 
    var entity1Doc = corpus.MakeObject<CdmDocumentDefinition>(CdmObjectType.DocumentDef, "MyEntity1.cdm.json"); 
    entity1Doc.Definitions.Add(entity1); 
    corpus.Storage.FetchRootFolder("local").Documents.Add(entity1Doc); 
    manifest.Entities.Add(entity1); 
    var manifestResolved = await manifest.CreateResolvedManifestAsync("new dummy 2", null); 
    if (manifestResolved == null) { 
        // Let check what went wrong!   
        corpus.Ctx.Events.ForEach(logEntry => 
        { 
          logEntry.ToList().ForEach(logEntryPair => Console.WriteLine($"{logEntryPair.Key}=	{logEntryPair.Value}")); 
                Console.WriteLine(); 
                }); 
        // throw exception as per recorded messages.   
        } 
```
Purposely commented, the following line in sample code.This makes CreateResolvedManifestAsync return null. 
```csharp
//corpus.Storage.FetchRootFolder("local").Documents.Add(manifest); 
```
If there are multiple related errors, their order in the EventList will be the root cause being first, followed with other logs reported by upper layers as the problem propagates upward.

## Bonus Tip
CorrelationId is optional parameter, can be set to event callback function which will append correlation ID with log messages, generated within SDK and sends back to callback. This can help SDK caller to filter log using correlation Id. 
```csharp
corpus.SetEventCallback(eventCallback, CdmStatusLevel.Warning, CorrelationId); 
```
CorrelationId can also be set on Ctx object in the corpus. 
```csharp
corpus.Ctx.CorrelationId 
```
## APIs supporting EventList logging 
-   [CreateResolvedEntityAsync](../1.0om/api-reference/cdm/entity.md#methods)
-   [CreateResolvedManifestAsync](../1.0om/api-reference/cdm/manifest.md#methods)
-   [FetchObjectAsync](../1.0om/api-reference/cdm/corpus.md#methods)
-   [FileStatusCheckAsync](../1.0om/api-reference/cdm/manifest.md#methods)
-   [SaveAsAsync](../1.0om/api-reference/cdm/document.md#methods)
