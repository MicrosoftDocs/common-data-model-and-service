---
title: Parquet Type to CDM Type | Microsoft Docs
description: Parquet Type to CDM Type.
author: surenderpawar
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 02/12/2021
ms.author: supawa
---

# Parquet Type to CDM Type

This document helps user to find the mapping from Parquet data type to CDM data type. 

Document | Description | 
------|--------
[Parquet Type](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md) | This column represents parquet data type. For more details visit [here](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md).
[CDM Type](list-of-datatypes.md) | This represents datatype in CDM format. For more details visit [here](logical-definitions.md#the-datatype-object)
[Trait](trait-concepts-and-use-cases.md) | Traits are the fundamental mechanism in the Common Data Model metadata grammar for describing the data format, semantic meaning, and specifications for entities, attributes and other objects, such as partitions or manifests.
Unsupported Types | CDM doesn't offer out-of-box equivalents. Depending on the use case, users can define new data types but it would not be standard.

The following is code snippet to set integer data type to CDM attribute. Please follow [CDM SDK API documentation](../1.0om/api-reference/api-reference.md) for the API references.  

```csharp
CdmTypeAttributeDefinition artAtt = MakeObject<CdmTypeAttributeDefinition>(CdmObjectType.TypeAttributeDef, "count"); 
artAtt.DataType = MakeObject<CdmDataTypeReference>(CdmObjectType.DataTypeRef, "integer", true); 
```

Parquet Type | CDM Type | Trait
-------|----|-------
string | [string](list-of-datatypes.md#<b>string</b>) | [is.dataFormat.character](list-of-traits#<b>isdataformatcharacter</b>),<br>[is.dataFormat.array](list-of-traits#<b>isdataformatarray</b>),<br>[is.dataFormat.big](list-of-traits#<b>isdataformatbig</b>)
uuid | [guid](list-of-datatypes#<b>guid</b>) | [is.dataFormat.guid](list-of-traits#<b>isdataformatguid</b>)
Decimal | [decimal](list-of-datatypes.md#<b>decimal</b>) | [is.dataFormat.numeric.shaped](list-of-traits#<b>isdataformatnumericshaped</b>) (extends [is.dataFormat.numeric](list-of-traits#<b>isdataformatnumeric</b>))<br>It has two parameters. <UL><LI>Precision - The total number of significant digits and datatype is an integer.</LI><LI>Scale - The number of digits to the right of the decimal place and datatype is integer. 
Date | [date](list-of-datatypes#<b>date</b>) | [is.dataFormat.date](list-of-traits#<b>isdataformatdate</b>)
interval | [binary](list-of-datatypes#<b>binary</b>) | [is.dataFormat.byte](list-of-traits#<b>isdataformatbyte</b>), <br>[is.dataFormat.array](list-of-traits#<b>isdataformatarray</b>)
Json | [json](list-of-datatypes#<b>json</b>) | [is.dataFormat.character](list-of-traits#<b>isdataformatcharacter</b>), <br>[is.dataFormat.array](list-of-traits#<b>isdataformatarray</b>),<br>[means.content.text.JSON](list-of-traits#<b>meanscontenttextjson</b>)
Enum | [string](list-of-datatypes#<b>string</b>) | [is.dataFormat.character](list-of-traits#<b>isdataformatcharacter</b>), <br>[is.dataFormat.array](list-of-traits#<b>isdataformatarray</b>),<br>[is.dataFormat.big](list-of-traits#<b>isdataformatbig</b>)
boolean | [boolean](list-of-datatypes#<b>boolean</b>) | [is.dataFormat.boolean](list-of-traits#<b>isdataformatboolean</b>)
**Signed integer** | |
INT(8, true) | [byte](list-of-datatypes#<b>byte</b>) | [is.dataFormat.byte](list-of-traits#<b>isdataformatbyte</b>)
INT(16, true) | [smallinteger](list-of-datatypes#<b>smallinteger</b>) | [is.dataFormat.integer](list-of-traits#<b>isdataformatinteger</b>), <br>[is.dataFormat.small](list-of-traits#<b>isdataformatsmall</b>)
INT(32, true) | [Integer](list-of-datatypes#<b>integer</b>) | [is.dataFormat.integer](list-of-traits#<b>isdataformatinteger</b>)
INT(64, true) | [biginteger](list-of-datatypes#<b>biginteger</b>) | [is.dataFormat.integer](list-of-traits#<b>isdataformatinteger</b>), <br>[is.dataFormat.big](list-of-traits#<b>isdataformatbig</b>)
**Unsupported** | |
Time (UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO)) | NA | NA 
Timestamp ( UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO) ) | NA | NA 
unsigned integer | NA | NA 
map | NA | NA 
list | NA | NA 
Bson | NA | NA 
null | NA | NA




