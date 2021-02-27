---
title: Operation Rename Attributes | Microsoft Docs
description: API reference for CdmOperationRenameAttributes.
author: violivei
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 24/02/2020
ms.author: violivei
---

# CdmOperationRenameAttributes

Renames each attribute in the input set by applying a provided format string. The format string can contain literal text  and one instance each of the replacement indicators (‘{a}’ or ‘{A}’) for the (lowercase or uppercase first character) name of the containing attribute name, (‘{m}’ or ‘{M}’) for the (lowercase or uppercase first character) name of the set member (like ‘line1’ or ‘addId’ and ‘{o}’ for the held ordinal of the attribute in the set. Examples are “{m}AsPartOf{A}”, “{a}{M}” or “{a}{M}{o}”. For a detailed description and a list of use cases for this operation refer to [this page](../../../../sdk/projections/renameattributes.md).

```csharp
public abstract class CdmOperationRenameAttributes extends CdmOperationBase
```
*CdmProjection extends CdmObjectDefinition in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmOperationRenameAttributes(CdmCorpusContext)**<br/>*ctx*: The corpus context.<br/>|Initializes a new instance of the [CdmOperationRenameAttributes](renameattributes.md) class.|

# Properties
|Name|Type|Description|
|---|---|---|
|ApplyTo|List\<string>|A list of attributes from the input attributes set that will renamed following the patterns specified on RenameFormat. If not specified, renames all the attributes.
|RenameFormat|string|A string pattern used to determine the new name for each attribute.

## Common properties
|Name|Type|Description|
|---|---|---|
|Condition|string|A string condition that is evaluated at runtime to determine if the operation will run or not. If the condition evaluates to false, only this operation will not run.
|Explanation|string|The operation's explanation
|SourceInput|bool?|Property of an operation that defines if the operation receives the input from previous operation or from source entity. If true, this operation receives the attributes coming from the source entity while if false, receives the attributes coming from the previous operation. In case this property is not set, it defaults to `!runSequentially`.

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See  [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

