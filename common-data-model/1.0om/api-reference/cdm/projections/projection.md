---
title: Projection | Microsoft Docs
description: API reference for CdmProjection.
author: violivei
ms.service: common-data-model
ms.reviewer: v-iap 
ms.topic: article
ms.date: 02/24/2021
ms.author: violivei
---

# Projection

A projection provides the ability to define a set of operations to dynamically manipulate a logical definition. For a in-depth explanation about how projections work refer to [this page](../../../../sdk/convert-logical-entities-resolved-entities.md#projection-overview).

```csharp
public class CdmProjection extends CdmObjectDefinitionBase
```

*CdmProjection extends CdmObjectDefinition in Python.*

## Constructors

|Name|Description|
|---|---|
|**CdmProjection(CdmCorpusContext)**<br/>*ctx*: The corpus context.<br/>|Initializes a new instance of the [CdmProjection](projection.md) class.|

## Properties

|Name|Type|Description|
|---|---|---|
|Condition|string|A string condition that is evaluated at runtime to determine if the operations will run or not. If the condition evaluates to false, the operations will not run and the attributes coming from the source are the result of the projection.
|Operations|List<[CdmOperationBase](operationbase.md)>|A list of operations that composes this projection.
|RunSequentially|bool|If true, runs the operations sequentially so each operation receives the result of the previous one. Otherwise, all operation will receive the same attribute set which comes from the source property.
|Source|string|The data type's name.|

## Methods

|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](../cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../../utilities/resolveoptions.md))**|See  [CdmObject.IsDerivedFrom(...)](../cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../../utilities/resolveoptions.md), [CdmObject](../cdmobject.md))**|See [CdmObject.Copy(...)](../cdmobject.md#methods).|[CdmObject](../cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](../cdmobject.md#methods).|bool|
