---
title: Argument | Microsoft Docs
description: API reference for CdmArgumentDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Argument 

An argument exists inside [trait references](traitreference.md) and provides name/value pairs for a trait reference. With arguments traits can contain data.

```
public class CdmArgumentDefinition extends CdmObjectSimple
```

## Constructors
|Name|Description|
|---|---|
|**CdmArgumentDefinition(CdmCorpusContext)**<br />*ctx*: The corpus context.|Initializes a new instance of the [CdmArgumentDefinition](argument.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The argument's name.|
|Value|dynamic|The argument's value.| 
|Explanation|string|The argument's explanation.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|