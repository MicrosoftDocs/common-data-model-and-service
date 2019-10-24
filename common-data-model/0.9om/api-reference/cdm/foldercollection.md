---
title: Folder Collection - Common Data Model | Microsoft Docs
description: Reference for CdmFolderCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Folder Collection

A folder collection extends [Collection](collection.md) and adds additional behaviors specific to folder collections. It is used only for the *ChildFolders* property in [Folder](folder.md) and not for any other folder collections.

```
public class CdmFolderCollection : CdmCollection<CdmFolderDefinition>
```

## Constructors
|Name|Description|
|---|---|
|**CdmFolderCollection(CdmCorpusContext, [CdmFolderDefinition](folder.md))**<br/>*ctx*: The corpus context.<br/>*parentFolder*: The folder that contains this collection.|Initializes a new instance of the [CdmFolderCollection](foldercollection.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|TODO|

