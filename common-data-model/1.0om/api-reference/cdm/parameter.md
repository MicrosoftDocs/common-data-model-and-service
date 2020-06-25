---
title: Parameter | Microsoft Docs
description: API reference for CdmParameterDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Parameter

A parameter provides the ability to specify the parameters that a [trait](trait.md) should contain. By providing a name, default values, and supported data types, trait references become restricted by which arguments they can contain. Parameters are defined for traits in the [schema documents](https://github.com/microsoft/CDM/tree/master/schemaDocuments) folder.

```csharp
public class CdmParameterDefinition extends CdmObjectDefinitionBase
```
*CdmParameterDefinition extends CdmObjectSimple in Python and TypeScript.*

## Constructors
|Name|Description|
|---|---|
|**CdmParameterDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The parameter's name.|Initializes a new instance of the [CdmParameterDefinition](parameter.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The parameter's name. This can be used to set argument values when referencing traits.|
|DefaultValue|dynamic|The parameter's default value to use if no corresponding arguments are set.|
|Required|bool|If true, an error will be reported if a trait being referenced has no value set as an argument.|
|DataTypeRef|CdmDataTypeReference|The data type that describes the meaning and shape of the values that can be represented by this parameter.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

