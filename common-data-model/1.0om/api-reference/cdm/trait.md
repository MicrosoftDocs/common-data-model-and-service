---
title: Trait | Microsoft Docs
description: API reference for CdmTraitDefinition.
author: jinichu

ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Trait 

A trait helps express the semantic meaning and structural guidance. Traits are essentially a metadata's metadata. Traits can extend other traits and have a format that's easy to understand and follow. For example, the trait *is.partition.format.CSV* describes a data partition in CSV format and has parameters that can provide additional information, such as which character to use as a delimiter.

```csharp
public class CdmTraitDefinition extends CdmObjectDefinitionBase
```
*CdmTraitDefinition extends CdmObjectDefinition in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmTraitDefinition(CdmCorpusContext, string, [CdmTraitReference](traitreference.md))**<br/>*ctx*: The corpus context.<br/>*name*: The trait's name.<br/>*extendsTrait [optional]*: The reference to the trait extended by this trait.|Initializes a new instance of the [CdmTraitDefinition](trait.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|TraitName|string|The trait's name.|
|ExtendsTrait|[CdmTraitReference](traitreference.md)?|The trait extended by this trait.|
|Parameters|[CdmCollection](collection.md)\<[CdmParameterDefinition](parameter.md)>|The trait's parameters, for holding values or settings with the trait.|
|Elevated|bool?|Denotes whether this trait is elevated. If an attribute has an elevated trait, then that trait should also be applied to the outer entity.|
|Ugly|bool?|Denotes whether the trait is user facing (false if it's user facing, true otherwise).|
|AssociatedProperties|List\<string>|The trait's associated properties.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

