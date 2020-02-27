---
title: CdmObject Definition | Microsoft Docs
description: API reference for CdmObjectDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# CdmObject Definition

This is the base interface for all Common Data Model object definitions. It's extended by *CdmObjectDefinitionBase* in C#, Java, and TypeScript.

```
public interface CdmObjectDefinition extends CdmObject
```
*This interface is substituted with a regular class in Python.*

## Properties
|Name|Type|Description|
|---|---|---|
|Explanation|string|The object's explanation.|
|ExhibitsTraits|[CdmTraitCollection](traitcollection.md)|The collection of traits that this object exhibits by default.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|All object definitions have some kind of name, so this method returns the name independent from the *name* property.|string|



