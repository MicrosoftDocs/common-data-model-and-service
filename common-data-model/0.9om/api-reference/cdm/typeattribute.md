---
title: Type Attribute Class - Common Data Model | Microsoft Docs
description: Reference for CdmTypeAttributeDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Type Attribute Class

A type attribute defines data type attributes along with supported functionalities, such as custom default values and descriptions. Model.json attributes are converted into CDM type attributes.

```
public class CdmTypeAttributeDefinition extends CdmAttribute
```

## Constructors
|Name|Description|
|---|---|
|TODO: Update once appliedTraits is removed<br/>**CdmTypeAttributeDefinition(CdmCorpusContext, string, bool)**<br/>*ctx*: The corpus context.<br/>*name*: The type attribute's name.<br/>*appliedTraits*: TODO|Initializes a new instance of the CdmTypeAttributeDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|DataType|CdmDataTypeReference|The type attribute's data type, a CDM reference object (see *Data Type*).|
|DataFormat|[CdmDataFormat](dataformat.md)|The type attribute's data format, in a string format derived from traits (string, int, etc).|
|AttributeContext|CdmAttributeContextReference |The attribute context of the type attribute.|
|DefaultValue|dynamic|The type attribute's default value.|
|Description|string|The type attribute's description.|
|DisplayName|string|The type attribute's display name.|
|SourceName|string|The type attribute's source name.|
|IsNullable|bool?|Denotes whether the type attribute can be null or not.|
|IsPrimaryKey|bool?|Denotes whether the type attribute is the primary key.|
|IsReadOnly|bool||Denotes whether the type attribute is read only.|
|MaximumLength|int?|The type attribute's maximum length.|
|MaximumValue|string|The type attribute's maximum value (for data types that this can apply to, like integers).|
|MinimumValue|string|The type attribute's minimum value (for data types that this can apply to, like integers).|
|SourceOrdering|int?|Denotes the order attributes exist in some underlying source system.|
|ValueConstrainedToList|bool?|Denotes whether the type attribute's value is constrained to a list. The values can only be from enums.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**IsDerivedFrom(string, ResolveOptions)**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|[CdmObject](cdmobject.md)|
|**Validate()**|See *CdmObject.Validate()*.|bool|

