---
title: Type Attribute | Microsoft Docs
description: API reference for CdmTypeAttributeDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Type Attribute

A type attribute defines data type attributes along with supported functionalities, such as custom default values and descriptions. Model.json attributes are converted into Common Data Model type attributes.

```csharp
public class CdmTypeAttributeDefinition extends CdmAttribute
```

## Constructors
|Name|Description|
|---|---|
|**CdmTypeAttributeDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The type attribute's name.|Initializes a new instance of the [CdmTypeAttributeDefinition](typeattribute.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|DataType|CdmDataTypeReference|The type attribute's data type, a Common Data Model object reference.|
|DataFormat|[CdmDataFormat](dataformat.md)|The type attribute's data format (string, int, etc.).|
|AttributeContext|CdmAttributeContextReference |The attribute context of the type attribute.|
|DefaultValue|dynamic|The type attribute's default value.|
|Description|string|The type attribute's description.|
|DisplayName|string|The type attribute's display name.|
|SourceName|string|The type attribute's source name.|
|IsNullable|bool?|Denotes whether the type attribute can be null or not.|
|IsPrimaryKey|bool?|Denotes whether the type attribute is the primary key.|
|IsReadOnly|bool?|Denotes whether the type attribute is read only.|
|MaximumLength|int?|The type attribute's maximum length.|
|MaximumValue|string|The type attribute's maximum value (for data types that this can apply to, like integers).|
|MinimumValue|string|The type attribute's minimum value (for data types that this can apply to, like integers).|
|SourceOrdering|int?|Denotes the order attributes exist in some underlying source system.|
|ValueConstrainedToList|bool?|Denotes whether the type attribute's value is constrained to a list. The values can only be from enums.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

