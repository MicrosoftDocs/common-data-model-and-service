---
title: Mapping Parquet types to Common Data Model data types | Microsoft Docs
description: This article provides assistance to developers in finding the appropriate equivalents of Parquet data types in Common Data Model.
author: surenderpawar

ms.reviewer: v-iap
ms.topic: article
ms.date: 02/12/2021
ms.author: supawa
---

# Mapping Parquet types to Common Data Model data types

This article provides assistance to developers in finding the appropriate equivalents of Parquet data types in Common Data Model.

- **Parquet type**: This column represents Parquet data type. For more details, visit [here](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md).
- **Common Data Model equivalent type**: Each attribute in Common Data Model entities can be associated with a single data type. A Common Data Model data type is an object that represents a collection of traits. All data types should indicate the data format traits but can also add additional semantic information. For more details, visit [here](logical-definitions.md#the-datatype-object).
- **Traits included in the equivalent data type**: When an attribute is defined by using a data type, the attribute will gain the traits of the data type, visit [here](logical-definitions.md#the-datatype-object). Traits are the fundamental mechanism in the Common Data Model metadata grammar for describing the data format, semantic meaning, and specifications for entities, attributes and other objects, such as partitions or manifests. For more details visit [here](trait-concepts-and-use-cases.md).
- **Traits to add**: The traits that won't be implicitly included when specifying the Common Data Model data type, users must add them in addition to complete the suggested data type and match the equivalent Parquet type.

- **Unsupported Types**: Common Data Model doesn't offer out-of-box equivalents. Depending on the use case, users can define new data types but it will not be standard.

The following code snippet sets integer data type to Common Data Model attribute. Follow [CDM SDK API documentation](../1.0om/api-reference/api-reference.md) for the API references.  

```csharp
CdmTypeAttributeDefinition artAtt = MakeObject<CdmTypeAttributeDefinition>(CdmObjectType.TypeAttributeDef, "count"); 
artAtt.DataType = MakeObject<CdmDataTypeReference>(CdmObjectType.DataTypeRef, "integer", true); 
```
[Here](../samples.md#customize-entities) is a sample application demonstrating how data types can be set.

Parquet Type | Common Data Model equivalent type | Traits included in the equivalent Data Type | Traits to add
-------|----|-------|-----
BOOLEAN | [boolean](list-of-datatypes.md#boolean) | [is.dataFormat.boolean](list-of-traits.md#isdataformatboolean) | N/A
FLOAT   | [float](list-of-datatypes.md#float) |  [is.dataFormat.floatingPoint](list-of-traits.md#isdataformatfloatingpoint)| N/A
DOUBLE  | [double](list-of-datatypes.md#double) |  [is.dataFormat.floatingPoint](list-of-traits.md#isdataformatfloatingpoint), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)| N/A
BYTE_ARRAY | [binary](list-of-datatypes.md#binary) | [is.dataFormat.byte](list-of-traits.md#isdataformatbyte), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray)| N/A
STRING | [string](list-of-datatypes.md#string) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)| N/A
UUID | [guid](list-of-datatypes.md#guid) | [is.dataFormat.guid](list-of-traits.md#isdataformatguid)| N/A
DECIMAL | [decimal](list-of-datatypes.md#decimal) | [is.dataFormat.numeric.shaped](list-of-traits.md#isdataformatnumericshaped) (extends [is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric))<br>It has two parameters: <UL><LI>precision - The total number of significant digits and datatype is an integer.</LI><LI>scale - The number of digits to the right of the decimal place and datatype is integer. | N/A
DATE | [date](list-of-datatypes.md#date) | [is.dataFormat.date](list-of-traits.md#isdataformatdate)| N/A
INTERVAL | [binary](list-of-datatypes.md#binary) | [is.dataFormat.byte](list-of-traits.md#isdataformatbyte), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray)| N/A
JSON | [json](list-of-datatypes.md#json) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[means.content.text.JSON](list-of-traits.md#meanscontenttextjson)| N/A
ENUM | [string](list-of-datatypes.md#string) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)| N/A
MAP | *(complex object)* | N/A | Structured Resolution Form: <br>[is.dataFormat.map](list-of-traits.md#isdataformatmap), <br>[is.dataFormat.maspKey](list-of-traits.md#isdataformatmapkey), <br>[is.dataFormat.mapValue](list-of-traits.md#isdataformatmapvalue) <br>Non-structured Resolution Form; <br>[indicates.expansionInfo.mapKey](list-of-traits.md#indicatesexpansioninfomapkey), <br>[indicates.expansionInfo.mapValue](list-of-traits.md#hasexpansioninfomapvalue) <br><br> For a detailed description and use cases refer to [this page](./projections/map-and-array-types.md#map-type).
LIST | *(complex object)* | N/A | Structured Resolution Form: <br>[is.dataFormat.list](list-of-traits.md#isdataformatlist) <br>Non-structured Resolution Form: <br>[has.expansionInfo.list](list-of-traits.md#hasexpansioninfolist) <br><br> For a detailed description and use cases refer to [this page](./projections/map-and-array-types.md#array-type).
**Signed integers** | |
INT(8, true) | [byte](list-of-datatypes.md#byte) | [is.dataFormat.byte](list-of-traits.md#isdataformatbyte)| N/A
INT(16, true) | [smallinteger](list-of-datatypes.md#smallinteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.signed](list-of-traits.md#isdataformatsigned), <br>[is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric), <br>[is.dataFormat.small](list-of-traits.md#isdataformatsmall)| N/A
INT(32, true) | [integer](list-of-datatypes.md#integer) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.signed](list-of-traits.md#isdataformatsigned), <br>[is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric)| N/A
INT(64, true) | [biginteger](list-of-datatypes.md#biginteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig), <br>[is.dataFormat.signed](list-of-traits.md#isdataformatsigned), <br>[is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric)| N/A
Unsigned integers | [biginteger](list-of-datatypes.md#biginteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.unsigned](list-of-traits.md#isdataformatunsigned), <br>[is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)| N/A
TIME (UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO)) | [integer](list-of-datatypes.md#integer) (MILLIS) <br>[biginteger](list-of-datatypes.md#biginteger) (MICRO and NANO)  | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig) (additional for MICRO and NANO), <br>[is.dataFormat.signed](list-of-traits.md#isdataformatsigned), <br>[is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric) | Only one of the listed traits below should be used: <br>[means.time.parquet.milli](list-of-traits.md#meanstimeparquetmilli), <br>[means.time.parquet.micro](list-of-traits.md#meanstimeparquetmicro), <br>[means.time.parquet.nano](list-of-traits.md#meanstimeparquetnano)
TIMESTAMP (UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO)) | [biginteger](list-of-datatypes.md#biginteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig), <br>[is.dataFormat.signed](list-of-traits.md#isdataformatsigned), <br>[is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric) | Only one of the listed traits below should be used: <br>[means.timestamp.parquet.milli](list-of-traits.md#meanstimestampparquetmilli), <br>[means.timestamp.parquet.micro](list-of-traits.md#meanstimestampparquetmicro), <br>[means.timestamp.parquet.nano](list-of-traits.md#meanstimestampparquetnano)
**Unsupported** | |
INT96 | Not available | Not available | Not available 
BSON | Not available | Not available | Not available 
Null | Not available | Not available| Not available 
