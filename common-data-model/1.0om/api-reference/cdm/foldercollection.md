---
title: Folder Collection | Microsoft Docs
description: API reference for CdmFolderCollection.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 10/18/2019
ms.author: jibyun
---

# Folder Collection

A folder collection extends [Collection](collection.md) and adds additional behaviors specific to folder collections. It's used only for the *ChildFolders* property in [Folder](folder.md) and not for any other folder collections, as this collection copies fields from the parent folder to the children.

```csharp
public class CdmFolderCollection extends CdmCollection<CdmFolderDefinition>
```

## Constructors
|Name|Description|
|---|---|
|**CdmFolderCollection(CdmCorpusContext, [CdmFolderDefinition](folder.md))**<br/>*ctx*: The corpus context.<br/>*parentFolder*: The folder that contains this collection. Must be the parent folder.|Initializes a new instance of the [CdmFolderCollection](foldercollection.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Add([CdmFolderDefinition](folder.md))**<br/>*childFolder*: The folder to add to the collection.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Adds the specified child folder to the collection. Returns the folder that was added to the collection.|[CdmFolderDefinition](folder.md)|
|**Add(string, bool)**<br/>*name*: The name of the folder to add to the collection.<br/>*simpleRef [optional]*: This parameter is unused. It's kept just for consistency with other Common Data Model collections.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates a folder with the specified name and adds it to the collection. Returns the folder that was added to the collection.|[CdmFolderDefinition](folder.md)|
|**AddRange(IEnumerable\<[CdmFolderDefinition](folder.md)>)**<br/>*childFolderList*: The list of folders to add.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of folders to the collection.|void|
|**Insert(int, [CdmFolderDefinition](folder.md))**<br/>*index*: The index to insert the folder at.<br/>*childFolder*: The folder to add to the collection.<br/><br/>*add(...) in Java.*|Inserts the folder into the collection at the specified index.|void|



