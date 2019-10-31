---
title: Purpose | Microsoft Docs
description: API reference for CdmPurposeDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Purpose

A purpose provides an attribute with what it does for an entity, for example *SortedBy* or *NamedBy*.


```
public class CdmPurposeDefinition extends CdmObjectDefinitionBase
```
*CdmObjectDefinitionBase is called CdmObjectDefinition in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmPurposeDefinition(CdmCorpusContext, string, CdmPurposeReference)**<br/>*ctx*: The corpus context.<br/>*purposeName*: The purpose's name.<br/>*extendsPurpose [optional]*: The reference to the purpose extended by this purpose.|Initializes a new instance of the [CdmPurposeDefinition](purpose.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|PurposeName|string|The purpose's name.|
|ExtendsPurpose|CdmPurposeReference|The reference to the purpose extended by this purpose.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

