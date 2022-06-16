---
title: Trait Group | Microsoft Docs
description: API reference for CdmTraitGroupDefinition.
author: miroslavplese

ms.reviewer: deonhe 
ms.topic: article
ms.date: 04/17/2021
ms.author: miplese
---

# Trait Group

*SDK version 1.2*

A trait group allows multiple traits to be combined into a single set identified by a name. Behavior is similar to that of data types and purposes, except that trait groups may be applied to any object, not just entity or type attributes.

```csharp
public class CdmTraitGroupDefinition extends CdmObjectDefinitionBase
```
*CdmTraitGroupDefinition extends CdmObjectDefinition in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmTraitGroupDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The trait group's name.<br/>|Initializes a new instance of the [CdmTraitGroupDefinition](traitgroup.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|TraitGroupName|string|The trait group's name.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods). Always returns false because trait groups do not support inheritance.|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

