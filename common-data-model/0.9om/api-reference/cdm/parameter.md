---
title: Parameter - Common Data Model | Microsoft Docs
description: Reference for CdmParameterDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Parameter

A parameter provides the ability to specify the parameters that a trait should contain. By providing a name, default values, and supported data types, trait references become restricted by which arguments they can contain. Parameters are defined for traits in the *CDM.SchemaDocuments* repository.

```
public class CdmParameterDefinition extends CdmObjectDefinitionBase
```

## Constructors
|Name|Description|
|---|---|
|**CdmParameterDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The parameter's name.|Initializes a new instance of the CdmParameterDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The parameter's name.|
|DefaultValue|dynamic|The parameter's default value.|
|Required|bool|Denotes whether this parameter is required.|
|DataTypeRef|CdmDataTypeReference|The parameter's data type reference.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See *CdmObject.Copy(...)*.|[CdmObject](cdmobject.md)|
|**Validate()**|See *CdmObject.Validate()*.|bool|

