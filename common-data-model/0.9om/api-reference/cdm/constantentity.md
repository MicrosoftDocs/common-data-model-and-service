---
title: Constant Entity - Common Data Model | Microsoft Docs
description: Reference for CdmConstantEntityDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Constant Entity

A constant entity provides a way of making an [entity](entity.md) with records of data in it and an associated schema in a JSON file. We use these whenever we want to store some table of information inside a parameter of a [trait](trait.md). They show up in the enum definitions, in the localized display text, etc.

```
public class CdmConstantEntityDefinition extends CdmObjectDefinitionBase
```

## Constructors
|Name|Description|
|---|---|
|**CdmConstantEntityDefinition(CdmCorpusContext)**<br/>*ctx*: The corpus context.|Initializes a new instance of the CdmConstantEntityDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|ConstantEntityName|string|The constant entity's name.|
|ConstantValues|List\<List\<string>>|The list of constant string values.|
|EntityShape|CdmEntityReference|The entity shape.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, ResolveOptions)**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|[CdmObject](cdmobject.md)|
|**Validate()**|See *CdmObject.Validate()*.|bool|