---
title: CdmObject Definition - Common Data Model | Microsoft Docs
description: Reference for CdmObjectDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# CdmObject Definition

This is the base interface for all CDM object definitions.

```
public interface CdmObjectDefinition extends CdmObject
```

## Properties
|Name|Type|Description|
|---|---|---|
|Explanation|string|The object's explanation.|
|ExhibitsTraits|TODO: Update after CdmTraitCollection is created<br/>[CdmCollection](collection.md)\<[CdmTraitReference](traitreference.md)>|The collection of exhibited traits.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|TODO: Remove after CdmTraitCollection is created<br/>**AddExhibitedTrait(dynamic, bool)**<br />*traitDef*: The trait definition, either a string representing the name or a [CdmTraitReference](traitreference.md) object.<br/>*implicitRef [optional]*: A boolean that denotes whether the trait is an implicit trait. It is used only if the name is provided as a trait definition. The default value is false.|Adds the specified trait definition to the list of exhibited traits. Returns the added trait.|[CdmTraitReference](traitreference.md)|
|TODO: Remove after CdmTraitCollection is created<br/>**RemoveExhibitedTrait(dynamic, bool)**<br />*traitDef*: The trait definition, either a string representing the name or a [CdmTraitReference](traitreference.md) object.<br />*onlyFromProperty [optional]*: TODO|Removes the trait definition from the exhibited trait list.|void|
|**GetName()**|All object definitions have some kind of name, so this method returns the name independent of the name from the name property.|string|
|**IsDerivedFrom(string, ResolveOptions)**<br/>*baseDef*: The symbol name of the object that we want to check whether this object is derived from it.<br/>*resOpt [optional]*: The resolve options.|Returns true if the object (or the referenced object) is an extension of the specified symbol name in some way.|bool|


