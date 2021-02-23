---
title: Parquet type to Commmon Data Model type | Microsoft Docs
description: Learn about the mapping from Parquet data type to Commmon Data Model data type.
author: surenderpawar
ms.service: common-data-model
ms.reviewer: v-iap
ms.topic: article
ms.date: 02/12/2021
ms.author: supawa
---

# Parquet Type to CDM Type

This article is a guide to the mapping from Parquet data type to Commmon Data Model data type. 

Document | Description | 
|------|--------|
[Parquet type](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md) | This column represents parquet data type. For more details visit [here](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md).|
[Commmon Data Model type](list-of-datatypes.md) | This represents datatype in Commmon Data Model format. For more details visit [here](logical-definitions.md#the-datatype-object)|
[Trait](trait-concepts-and-use-cases.md) | Traits are the fundamental mechanism in the Common Data Model metadata grammar for describing the data format, semantic meaning, and specifications for entities, attributes and other objects, such as partitions or manifests.|
Unsupported Types | Commmon Data Model doesn't offer out-of-box equivalents. Depending on the use case, users can define new data types but it would not be standard.|

The following is code snippet to set integer data type to Commmon Data Model attribute. Please follow [Commmon Data Model SDK API documentation](../1.0om/api-reference/api-reference.md) for the API references.  

```csharp
CdmTypeAttributeDefinition artAtt = MakeObject<CdmTypeAttributeDefinition>(CdmObjectType.TypeAttributeDef, "count"); 
artAtt.DataType = MakeObject<CdmDataTypeReference>(CdmObjectType.DataTypeRef, "integer", true); 
```

|Parquet Type | CDM Type | Trait |
|-------|----|-------|
string | [string](list-of-datatypes.md#string) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter),<br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)
uuid | [guid](list-of-datatypes.md#guid) | [is.dataFormat.guid](list-of-traits.md#isdataformatguid)
Decimal | [decimal](list-of-datatypes.md#decimal) | [is.dataFormat.numeric.shaped](list-of-traits.md#isdataformatnumericshaped) (extends [is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric))<br>It has two parameters. <UL><LI>Precision - The total number of significant digits and datatype is an integer.</LI><LI>Scale - The number of digits to the right of the decimal place and datatype is integer. 
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
Time (UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO)) | NA | NA 
Timestamp ( UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO) ) | NA | NA 
unsigned integer | NA | NA 
map | NA | NA 
list | NA | NA 
Bson | NA | NA 
null | NA | NA




