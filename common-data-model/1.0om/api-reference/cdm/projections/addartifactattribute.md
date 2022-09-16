---
title: Operation Add Artifact Attribute | Microsoft Docs
description: API reference for CdmOperationAddArtifactAttribute.
author: llawwaii

ms.reviewer: v-iap 
ms.topic: article
ms.date: 09/03/2021
ms.author: weiluo
---

# CdmOperationAddArtifactAttribute

Adding a user-specified attribute (currently, only supports type attribute) to the final resolved entity. For a detailed description and a list of use cases for this operation refer to [this page](../../../../sdk/projections/addartifactattribute.md).

```csharp
public class CdmOperationAddArtifactAttribute extends CdmOperationBase
```

*CdmProjection extends CdmObjectDefinition in Python.*

## Constructors

|Name|Description|
|---|---|
|**CdmOperationAddArtifactAttribute(CdmCorpusContext)**<br/>*ctx*: The corpus context.<br/>|Initializes a new instance of the [CdmOperationAddArtifactAttribute](addartifactattribute.md) class.|

## Properties

|Name|Type|Description|
|---|---|---|
|NewAttribute|[CdmAttributeItem](..\attributeitem.md)|The new attribute that will be added to the input attributes list.
|InsertAtTop|bool?|If true, the new attribute will be added at the top of the input attribute list. Otherwise, it is added at the bottom of the input attribute list.

## Common properties

|Name|Type|Description|
|---|---|---|
|Condition|string|A string condition that is evaluated at runtime to determine if the operation will run or not. If the condition evaluates to false, only this operation will not run.
|Explanation|string|The operation's explanation.
|SourceInput|bool?|Property of an operation that defines if the operation receives the input from previous operation or from source entity. If true, this operation receives the attributes coming from the source entity while if false, receives the attributes coming from the previous operation. In case this property is not set, it defaults to `!runSequentially` (false).

## Methods

|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](../cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../../utilities/resolveoptions.md))**|See  [CdmObject.IsDerivedFrom(...)](../cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../../utilities/resolveoptions.md), [CdmObject](../cdmobject.md))**|See [CdmObject.Copy(...)](../cdmobject.md#methods).|[CdmObject](../cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](../cdmobject.md#methods).|bool|
