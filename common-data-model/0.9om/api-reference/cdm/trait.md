---
title: Trait - Common Data Model | Microsoft Docs
description: Reference for CdmTraitDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Trait 

A trait helps express semantic meaning and structural guidance. Traits are essentially a metadata's metadata. Traits can extend other traits and have a format that is easy to understand and follow. (E.g. The trait is.partition.format.CSV describes a data partition in CSV format and has parameters that can provide additional information, such as which character to use as a delimiter).

```
public class CdmTraitDefinition extends CdmObjectDefinitionBase
```

## Constructors
|Name|Description|
|---|---|
|TODO: Update once extendsTraits is optional<br/>**CdmTraitDefinition(CdmCorpusContext, string, [CdmTraitReference](traitreference.md), bool)**<br/>*ctx*: The corpus context.<br/>*name*: The trait's name.<br/>*extendsTrait*: The reference to the trait extended by this trait.<br/>*hasParameters*: A boolean that denotes whether this trait has parameters.|Initializes a new instance of the CdmTraitDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|TraitName|string|The trait's name.|
|ExtendsTrait|[CdmTraitReference](traitreference.md)|The trait extended by this trait.|
|Parameters|[CdmCollection](collection.md)\<[CdmParameterDefinition](parameter.md)>|The trait's parameters.|
|Elevated|bool?|Denotes whether this trait is elevated (e.g. if an attribute has an elevated trait, then that trait should also be applied to the outer entity).|
|Ugly|bool?|Denotes whether the trait is user facing (false if it is user facing, true otherwise).|
|AssociatedProperties|List\<string>|The properties for the entity or attribute that this trait contributes to (using trait2propertyMap).|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, ResolveOptions)**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|[CdmObject](cdmobject.md)|
|**Validate()**|See *CdmObject.Validate()*.|bool|

