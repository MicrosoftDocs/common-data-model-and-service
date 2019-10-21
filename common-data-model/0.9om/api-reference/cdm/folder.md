---
title: Folder Class - Common Data Model | Microsoft Docs
description: Reference for CdmFolderDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Folder Class

A folder provides a hierarchical structure of the OM for organizing documents. Folders can contain other folders or documents.

TODO: Update after CdmContainerDefinition is replaced by some intermediate base class
```
public class CdmFolderDefinition extends CdmObjectDefinitionBase, CdmContainerDefinition
```

## Constructors
|Name|Description|
|---|---|
|**CdmFolderDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The folder's name.|Initializes a new instance of the CdmFolderDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The name of the folder.|
|TODO: Update once CdmDocumentCollection is created<br/>Documents|CdmCollection\<CdmDocumentDefinition>|The child documents of the folder.|
|TODO: Update once CdmFolderCollection is created<br/>ChildFolders|CdmCollection\<CdmFolderDefinition>|The direct children of the folder.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|TODO: Remove after CdmFolderCollection is created<br/>**AddChildFolder(string)**<br/>*name*: The name of the folder.|Adds a child folder to the current folder and returns the newly added folder.|CdmFolderDefinition|
|TODO: Remove after CdmDocumentCollection is created<br/>**AddDocument(string, CdmDocumentDefinition)**<br />*name*: The name of the document.<br/>*doc*: The document to add.|Adds a child document to the current folder and returns the newly added document.|CdmDocumentDefinition|
|TODO: Remove after CdmDocumentCollection is created<br/>**RemoveDocument(string)**<br/>*name*: The name of the document.|Removes the document with the specified name from the folder.|void|
|**FetchObjectDefinition\<T>(ResolveOptions)**|See *CdmObject.FetchObjectDefinition\<T>(...)*.|T|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, ResolveOptions)**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|CdmObject|
|**Validate()**|See *CdmObject.Validate()*.|bool|

