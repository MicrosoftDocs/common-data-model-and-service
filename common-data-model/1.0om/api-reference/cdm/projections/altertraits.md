---
title: Operation Alter Traits | Microsoft Docs
description: API reference for CdmOperationAlterTraits.
author: llawwaii

ms.reviewer: v-iap 
ms.topic: reference 
ms.date: 09/03/2021
ms.author: weiluo
---

# CdmOperationAlterTraits

Adding, updating, or/and removing a user-specified set of traits or trait groups to a specified set of attributes from the source, which can either be an entity reference or another projection. For a detailed description and a list of use cases for this operation refer to [this page](../../../../sdk/projections/altertraits.md).

```csharp
public class CdmOperationAlterTraits extends CdmOperationBase
```

*CdmProjection extends CdmObjectDefinition in Python.*

## Constructors

|Name|Description|
|---|---|
|**CdmOperationAlterTraits(CdmCorpusContext)**<br/>*ctx*: The corpus context.<br/>|Initializes a new instance of the [CdmOperationAlterTraits](altertraits.md) class.|

## Properties

|Name|Type|Description|
|---|---|---|
|TraitsToAdd|[CdmCollection](..\collection.md)\<[CdmTraitReferenceBase](..\traitreferencebase.md)>|A CdmCollection of traits or trait groups that will be applied on the input.
|TraitsToRemove|[CdmCollection](..\collection.md)\<[CdmTraitReferenceBase](..\traitreferencebase.md)>|A CdmCollection of traits or trait groups that will be removed (if found) on the input.
|ArgumentsContainWildcards|bool?|If true, checks all arguments from all traits and performs replacement. May contain a single occurrence of ('{a}' or '{A}') for the (original or capitalized) form name of the projection owner, ('{m}' or '{M}') for the (original or capitalized) resolved name of the member attribute, ('{mo}' or '{Mo}') for the (original or capitalized) original name of the member attribute, and '{o}' for the held ordinal of the attribute in the array.
|ApplyTo|List\<string>|A list of attributes from the input attributes set to which traits defined in traitsToAdd property will be added (or arguments updated) and/or removed as indicated in traitsToRemove property. If not specified, traits in all attributes from the source will be targeted.

## Common properties

|Name|Type|Description|
|---|---|---|
|Condition|string|A string condition that is evaluated at runtime to determine if the operation will run or not. If the condition evaluates to false, only this operation will not run.
|Explanation|string|The operation's explanation.
|SourceInput|bool?|Property of an operation that defines if the operation receives the input from previous operation or from source entity. If true, this operation receives the attributes coming from the source entity while if false, receives the attributes coming from the previous operation. In case this property is not set, it defaults to `!runSequentially`.

## Methods

|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](../cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../../utilities/resolveoptions.md))**|See  [CdmObject.IsDerivedFrom(...)](../cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../../utilities/resolveoptions.md), [CdmObject](../cdmobject.md))**|See [CdmObject.Copy(...)](../cdmobject.md#methods).|[CdmObject](../cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](../cdmobject.md#methods).|bool|
