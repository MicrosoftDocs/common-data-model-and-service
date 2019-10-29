---
title: Folder Collection - Common Data Model | Microsoft Docs
description: API reference for CdmFolderCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Folder Collection

A folder collection extends [Collection](collection.md) and adds additional behaviors specific to folder collections. It is used only for the *ChildFolders* property in [Folder](folder.md) and not for any other folder collections, as this collection copies fields from the parent folder to the children.

```
public class CdmFolderCollection extends CdmCollection<CdmFolderDefinition>
```

## Constructors
|Name|Description|
|---|---|
|**CdmFolderCollection(CdmCorpusContext, [CdmFolderDefinition](folder.md))**<br/>*ctx*: The corpus context.<br/>*parentFolder*: The folder that contains this collection. Must be the parent folder.|Initializes a new instance of the [CdmFolderCollection](foldercollection.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Add([CdmFolderDefinition](folder.md))**<br/>*childFolder*: The folder to add to the collection.|Adds the specified child folder to the collection.|void|
|**Add(string, bool)**<br/>*name*: The name of the folder to add to the collection.<br/>*simpleRef [optional]*: This parameter is unused. It is kept just for consistency with other CDM collections.|Creates a folder with the specified name and adds it to the collection. Returns the folder that was added to the collection.|[CdmFolderDefinition](folder.md)|
|**AddRange(IEnumerable\<[CdmFolderDefinition](folder.md)>)**<br/>*childFolderList*: The list of folders to add.|Adds the elements of the specified list of folders to the collection.|void|



