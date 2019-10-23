---
title: Child Folder Collection - Common Data Model | Microsoft Docs
description: Reference for CdmChildFolderCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Child Folder Collection

A child folder collection extends [Collection](collection.md) and adds additional behaviors specific to folder collections. It is used only for the *ChildFolders* property in [Folder](folder.md) and not for any other folder collections.

```
public class CdmChildFolderCollection extends CdmCollection<CdmFolderDefinition>
```

## Constructors
|Name|Description|
|---|---|
|**CdmChildFolderCollection(CdmCorpusContext, [CdmFolderDefinition](folder.md), [CdmObjectType](objecttype.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The folder that contains this collection.<br/>*defaultType*: The default CDM object type of this collection.|Initializes a new instance of the CdmChildFolderCollection class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|TODO|

