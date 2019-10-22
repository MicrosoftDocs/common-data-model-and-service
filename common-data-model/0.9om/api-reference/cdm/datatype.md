---
title: Data Type - Common Data Model | Microsoft Docs
description: Reference for CdmDataTypeDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Data Type

A data type provides the ability to assign different data types to attributes (such as string, boolean, etc).

```
public class CdmDataTypeDefinition extends CdmObjectDefinitionBase
```

## Constructors
|Name|Description|
|---|---|
|TODO: Update once exhibitsTraits removed and extendsDataType is optional <br/>**CdmDataTypeDefinition(CdmCorpusContext, string, CdmDataTypeReference, bool)**<br/>*ctx*: The corpus context.<br/>*dataTypeName*: The data type's name.<br/>*extendsDataType*: The data type extended by this data type.<br/>*exhibitsTraits [optional]*: TODO. The default value is false.|Initializes a new instance of the CdmDataTypeDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|DataTypeName|string|The data type's name.|
|ExtendsDataType|CdmDataTypeReference|The data type extended by this data type.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, ResolveOptions)**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|[CdmObject](cdmobject.md)|
|**Validate()**|See *CdmObject.Validate()*.|bool|

