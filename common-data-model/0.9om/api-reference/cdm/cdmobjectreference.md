---
title: CdmObject Reference Interface - Common Data Model | Microsoft Docs
description: Reference for CdmObjectReference.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# CdmObject Reference Interface

This is the base interface for all CDM object references. It is extended by *CdmObjectReferenceBase, CdmAttributeContextReference, CdmAttributeGroupReference, CdmAttributeReference, CdmDataTypeReference, CdmEntityReference*, and *CdmPurposeReference*.

```
public interface CdmObjectReference extends CdmObject
```

## Properties
|Name|Type|Description|
|---|---|---|
|AppliedTraits|TODO: Update once CdmTraitCollection is created<br/>CdmCollection\<CdmTraitReference>|The collection of applied traits.|
|ExplicitReference|CdmObjectDefinition|The object definition that this reference is referencing.|
|NamedReference|string|The string used to simply reference different concepts just by name without having to include any other extra data.|
|SimpleNamedReference|bool|A boolean denoting whether the reference is simple named or not. If true, it will use a named reference, otherwise it will use an explicit reference.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|TODO: Remove after CdmTraitCollection is created<br/>**AddAppliedTrait(dynamic, bool)**<br />*traitDef*: The trait definition, either a string representing the name or a CdmTraitReference object.<br/>*implicitRef [optional]*: A boolean that denotes whether the trait is an implicit trait. It is used only if the name is provided as a trait definition. The default value is false.|Adds the specified trait definition to the list of applied traits. Returns the added trait.|CdmTraitReference|
|TODO: Remove after CdmTraitCollection is created<br/>**RemoveAppliedTrait(dynamic, bool)**<br />*traitDef*: The trait definition, either a string representing the name or a CdmTraitReference object.<br/>*onlyFromProperty [optional]*: TODO |Removes the trait definition from the list of applied traits. |void|

