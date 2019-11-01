---
title: Folder | Microsoft Docs
description: API reference for CdmFolderDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Folder

A folder provides a hierarchical structure of the OM for organizing [documents](document.md). Folders can contain other folders or documents.

```
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
|Name|string|The name of the folder.|
|Documents|[CdmDocumentCollection](documentcollection.md)|The child documents of the folder.|
|ChildFolders|[CdmFolderCollection](foldercollection.md)|The direct children of the folder.|
|AtCorpusPath|string|The corpus path of the folder.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FetchObjectDefinition\<T>([ResolveOptions](../utilities/resolveoptions.md))**<br/><br/>*Only in C# and Java.*|See [CdmObject.FetchObjectDefinition\<T>(...)](cdmobject.md#methods).|T|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

