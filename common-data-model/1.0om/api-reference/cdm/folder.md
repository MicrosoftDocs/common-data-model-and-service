---
title: Folder | Microsoft Docs
description: API reference for CdmFolderDefinition.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 10/18/2019
ms.author: jibyun
---

# Folder

A folder provides a hierarchical structure of the object model for organizing [documents](document.md). Folders can contain other folders or documents.

```csharp
public class CdmFolderDefinition extends CdmObjectDefinitionBase, CdmContainerDefinition
```
*CdmFolderDefinition extends CdmObjectDefinition, CdmContainerDefinition in Python.*
<br/>*CdmFolderDefinition extends CdmObjectDefinitionBase in TypeScript.*

## Constructors
|Name|Description|
|---|---|
|**CdmFolderDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The folder's name.|Initializes a new instance of the [CdmFolderDefinition](folder.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|AtCorpusPath|string|The corpus path of the folder.|
|ChildFolders|[CdmFolderCollection](foldercollection.md)|The direct children of the folder.|
|Documents|[CdmDocumentCollection](documentcollection.md)|The child documents of the folder.|
|FolderPath|string (read-only)|The folder path starting from the root.|
|Name|string|The name of the folder.|
|Namespace|string (read-only)|The root namespace of the folder.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FetchObjectDefinition\<T>([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.FetchObjectDefinition\<T>(...)](cdmobject.md#methods).|T|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

