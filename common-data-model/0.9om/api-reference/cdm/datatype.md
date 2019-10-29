---
title: Data Type - Common Data Model | Microsoft Docs
description: API reference for CdmDataTypeDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Data Type

A data type provides the ability to assign different data types to attributes (such as string, Boolean, etc.).

```
public class CdmDataTypeDefinition extends CdmObjectDefinitionBase
```
*CdmDataTypeDefinition extends CdmObjectDefinition in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmDataTypeDefinition(CdmCorpusContext, string, CdmDataTypeReference)**<br/>*ctx*: The corpus context.<br/>*dataTypeName*: The data type's name.<br/>*extendsDataType [optional]*: The data type extended by this data type.|Initializes a new instance of the [CdmDataTypeDefinition](datatype.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|DataTypeName|string|The data type's name.|
|ExtendsDataType|CdmDataTypeReference|The data type extended by this data type.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See  [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

