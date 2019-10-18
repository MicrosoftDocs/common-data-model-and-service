---
title: Collection Class - Common Data Model | Microsoft Docs
description: Reference for CdmCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Collection Class

A collection holds a set of [CDM objects](cdmobject.md) and provides easier handling of them.

```
public class CdmCollection<T> extends IList<T> where T : CdmObject
```

## Constructors
|Name|Description|
|---|---|
|**CdmCollection(CdmCorpusContext, CdmObject, CdmObjectType)**<br/>*ctx*: The corpus context.<br/>*owner*: The CDM object that contains this collection.<br/>*defaultType*: The default CDM object type of this collection.|Initializes a new instance of the CdmCollection class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Count<br/>(*Length* in Java and Python)|int|The number of items in the CDM collection.|
|AllItems|List\<T>|The list of all items.|

## Methods
|Name|Description|Return Type|
|---|---|---|