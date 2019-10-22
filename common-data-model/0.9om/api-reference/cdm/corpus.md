---
title: Corpus Class - Common Data Model | Microsoft Docs
description: Reference for CdmCorpusDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Corpus Class

The corpus is a top-level folder that the most important basic functionalities to deal with the object model. There will usually only be one corpus when dealing with the OM.

```
public class CdmCorpusDefinition extends CdmFolderDefinition
```

## Constructors
|Name|Description|
|---|---|
|**CdmCorpusDefinition()**|Initializes a new instance of the CdmCorpusDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|TODO: Update once DefaultNamespace gets moved to StorageManger<br/>DefaultNamespace|string|The namespace that will be used when one is not explicitly provided.|
|Storage|[StorageManager](../storage/storagemanager.md)|The storage for the corpus. Used for interacting with storage adapters.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**MakeRef\<T>([CdmObjectType](objecttype.md), dynamic, bool)**<br/>*ofType*: The type of the CDM object we want to make. <br/>*refObj*: The reference object. <br/> *simpleNameRef*: A boolean that denotes whether it is a simple name reference.	| Instantiates an OM class reference based on the object type passed as the first parameter.|T, where T : [CdmObjectReference](cdmobjectreference.md)|
|**MakeObject\<T>([CdmObjectType](objecttype.md), string, bool)**<br/>*ofType*: The type of the CDM object we want to make. <br/>*nameOrRef [optional]*: The name or reference.<br/>*simpleNameRef [optional]*: A boolean that denotes whether it is a simple name reference. The default value is false.	| Instantiates an OM class based on the object type passed as the first parameter.|T, where T : [CdmObject](cdmobject.md)|
|**FetchObjectAsync\<T>(string, [CdmObject](cdmobject.md))**<br/>*objectPath*: The object path of a folder or document.<br/>*obj [optional]*: TODO | Fetches an object from the corpus path.	|Task\<T>|
|**SetEventCallback([RptCallback](../utilities/callback.md), [CdmStatusLevel](statuslevel.md))**<br/>*status*: The callback. <br/>*reportAtLevel*: At which status level to report.| Sets the status and error callback that gets called for status/warning/error purposes.|void|
|**CalculateEntityGraphAsync([CdmManifestDefinition](manifest.md))**<br/>*currManifest*: The manifest (and any sub-manifests it contains) that we want to calculate relationships for.|Calculates the entity to entity relationships for all the entities present in the manifest and its sub-manifests.|Task|
|**FetchIncomingRelationships([CdmEntityDefinition](entity.md))**<br/>*entity*: The entity that we want to get relationships for.|Returns a list of relationships where the input entity is the incoming entity.|List\<[CdmE2ERelationship](e2erelationship.md)>|
|**FetchOutgoingRelationships([CdmEntityDefinition](entity.md))**<br/>*entity*: The entity that we want to get relationships for.|Returns a list of relationships where the input entity is the outgoing entity.|List\<[CdmE2ERelationship](e2erelationship.md)>|

