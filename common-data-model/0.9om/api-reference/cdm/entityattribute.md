---
title: Entity Attribute | Microsoft Docs
description: API reference for CdmEntityAttributeDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Entity Attribute

An entity attribute is an attribute that also points to an [entity](entity.md).

```
public class CdmEntityAttributeDefinition extends CdmAttribute
```

## Constructors
|Name|Description|
|---|---|
|**CdmEntityAttributeDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The entity attribute's name.|Initializes a new instance of the [CdmEntityAttributeDefinition](entityattribute.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Entity|CdmEntityReference|The entity attribute's entity reference.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

