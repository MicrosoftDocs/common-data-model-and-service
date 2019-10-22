---
title: Argument Class - Common Data Model | Microsoft Docs
description: Reference for CdmArgumentDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Argument Class 

An argument exists inside [trait references](traitreference.md) and provides name/value pairs for a specific trait reference. Arguments give life to traits by enabling them to actually contain some specific data.

```
public class CdmArgumentDefinition extends CdmObjectSimple
```

## Constructors
|Name|Description|
|---|---|
|**CdmArgumentDefinition(CdmCorpusContext)**<br />*ctx*: The corpus context.|Initializes a new instance of the CdmArgumentDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The argument's name.|
|Value|dynamic|The argument's value.| 
|Explanation|string|The argument's explanation.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|[CdmObject](cdmobject.md)|
|**Validate()**|See *CdmObject.Validate()*.|bool|