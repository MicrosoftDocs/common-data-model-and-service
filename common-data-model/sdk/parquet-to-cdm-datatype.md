---
title: Parquet Type to CDM Type | Microsoft Docs
description: Mapping Parquet types to Common Data Model data types.
author: surenderpawar
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 02/12/2021
ms.author: supawa
---

# Parquet Type to CDM Type

This article provides assistance to developers in finding the appropriate equivalents of Parquet data types in Common Data Model.

- [Parquet Type](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md) : This column represents parquet data type. For more details visit [here](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md).
- [Common Data Model Type](list-of-datatypes.md) : Each attribute in Common Data Model entities can be associated with a single data type. A Common Data Model dataType is an object that represents a collection of traits. All dataTypes should indicate the dataFormat traits but can also add additional semantic information.For more details visit [here](logical-definitions.md#the-datatype-object)
- [Trait](trait-concepts-and-use-cases.md) : Traits are the fundamental mechanism in the Common Data Model metadata grammar for describing the data format, semantic meaning, and specifications for entities, attributes and other objects, such as partitions or manifests.
- Unsupported Types | Common Data Model doesn't offer out-of-box equivalents. Depending on the use case, users can define new data types but it will not be standard.

The following is code snippet to set integer data type to Common Data Model attribute. Please follow [CDM SDK API documentation](../1.0om/api-reference/api-reference.md) for the API references.  

```csharp
CdmTypeAttributeDefinition artAtt = MakeObject<CdmTypeAttributeDefinition>(CdmObjectType.TypeAttributeDef, "count"); 
artAtt.DataType = MakeObject<CdmDataTypeReference>(CdmObjectType.DataTypeRef, "integer", true); 
```
[Here](../samples.md#customize-entities) is a sample example which shows how to set data types.

Parquet Type | Common Data Model Type | Trait
-------|----|-------
string | [string](list-of-datatypes.md#string) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter),<br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)
uuid | [guid](list-of-datatypes.md#guid) | [is.dataFormat.guid](list-of-traits.md#isdataformatguid)
Decimal | [decimal](list-of-datatypes.md#decimal) | [is.dataFormat.numeric.shaped](list-of-traits.md#isdataformatnumericshaped) (extends [is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric))<br>It has two parameters: <UL><LI>precision - The total number of significant digits and datatype is an integer.</LI><LI>scale - The number of digits to the right of the decimal place and datatype is integer. 
Date | [date](list-of-datatypes.md#date) | [is.dataFormat.date](list-of-traits.md#isdataformatdate)
interval | [binary](list-of-datatypes.md#binary) | [is.dataFormat.byte](list-of-traits.md#isdataformatbyte), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray)
Json | [json](list-of-datatypes.md#json) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[means.content.text.JSON](list-of-traits.md#meanscontenttextjson)
Enum | [string](list-of-datatypes.md#string) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)
boolean | [boolean](list-of-datatypes.md#boolean) | [is.dataFormat.boolean](list-of-traits.md#isdataformatboolean)
**Signed integer** | |
INT(8, true) | [byte](list-of-datatypes.md#byte) | [is.dataFormat.byte](list-of-traits.md#isdataformatbyte)
INT(16, true) | [smallinteger](list-of-datatypes.md#smallinteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.small](list-of-traits.md#isdataformatsmall)
INT(32, true) | [Integer](list-of-datatypes.md#integer) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger)
INT(64, true) | [biginteger](list-of-datatypes.md#biginteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)
**Unsupported** | |
Time (UTC adjustment (true/false) and precision (MILLIS/MICRO/Not availableNO)) | Not available | Not available 
Timestamp ( UTC adjustment (true/false) and precision (MILLIS/MICRO/Not availableNO) ) | Not available | Not available 
unsigned integer | Not available | Not available 
map | Not available | Not available 
list | Not available | Not available 
Bson | Not available | Not available 
null | Not available | Not available
