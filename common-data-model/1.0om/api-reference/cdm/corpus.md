---
title: Corpus | Microsoft Docs
description: API reference for CdmCorpusDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 08/20/2020
ms.author: jibyun
---

# Corpus

The corpus is a top-level folder that provides the most important basic functionalities to deal with the object model. There will usually only be one corpus when dealing with the object model.

```csharp
public class CdmCorpusDefinition
```

## Constructors
|Name|Description|
|---|---|
|**CdmCorpusDefinition()**|Initializes a new instance of the [CdmCorpusDefinition](corpus.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|RootPath|string|The root path of the corpus.|
|Storage|[StorageManager](../storage/storagemanager.md)|The storage for the corpus. Used for interacting with storage adapters.|
|AppId|string|The ID of the application using the object model. This is an optional property.|
|DefaultResolutionDirectives|AttributeResolutionDirectiveSet|The set of default resolution directives that will be used by the object model when it's resolving entities and when no per-call set of directives is provided.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**MakeRef\<T>([CdmObjectType](objecttype.md), dynamic, bool)**<br/>*ofType*: The type of the object we want to create. <br/>*refObj*: The reference object. <br/> *simpleNameRef*: A boolean that denotes whether it's a simple name reference.|Instantiates a Common Data Model object reference based on the object type passed as the first parameter.|T, where T extends [CdmObjectReference](cdmobjectreference.md)|
|**MakeObject\<T>([CdmObjectType](objecttype.md), string, bool)**<br/>*ofType*: The type of the object we want to create. <br/>*nameOrRef [optional]*: The name or reference.<br/>*simpleNameRef [optional]*: A boolean that denotes whether the reference is simple named or not. The default value is false.|Instantiates a Common Data Model object based on the object type passed as the first parameter.|T, where T extends [CdmObject](cdmobject.md)|
|**FetchObjectAsync\<T>(string, [CdmObject](cdmobject.md), bool)**<br/>*objectPath*: The object path of a folder or document. The path can be absolute or relative.<br/>*obj [optional]*: When provided, it's used to obtain the *FolderPath* and *Namespace* that are needed to create the absolute path from a relative path.<br/>*shallowValidation [optional]*: When provided, shallow validation in [ResolveOptions](../utilities/resolveoptions.md) is enabled, which logs errors regarding loading and resolving object references as warnings instead.<br/>*forceReload [optional]*: When true, the document containing the requested object is reloaded from storage to access any external changes made to the document since it may have been cached by the corpus.|Fetches the object in the specified path from the corpus.|Task\<T>|
|**SetEventCallback([EventCallback](../utilities/callback.md), [CdmStatusLevel](statuslevel.md))**<br/>*status*: The callback. <br/>*reportAtLevel*: At which status level to report.|Sets a callback object that gets invoked when status/warning/error messages are logged, and the status level the callback should be invoked at.|void|
|**CalculateEntityGraphAsync([CdmManifestDefinition](manifest.md))**<br/>*currManifest*: The manifest (and any sub-manifests it contains) that we want to calculate relationships for.|Calculates the entity-to-entity relationships for all the entities present in the manifest and its sub-manifests.|Task|
|**FetchIncomingRelationships([CdmEntityDefinition](entity.md))**<br/>*entity*: The entity that we want to get relationships for.|Returns a list of relationships where the input entity is the incoming entity.|List\<[CdmE2ERelationship](e2erelationship.md)>|
|**FetchOutgoingRelationships([CdmEntityDefinition](entity.md))**<br/>*entity*: The entity for which we want to get relationships.|Returns a list of relationships where the input entity is the outgoing entity.|List\<[CdmE2ERelationship](e2erelationship.md)>|
