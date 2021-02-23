---
title: Mapping Parquet types to Common Data Model data types | Microsoft Docs
description: This article provides assistance to developers in finding the appropriate equivalents of Parquet data types in Common Data Model.
author: surenderpawar
ms.service: common-data-model
ms.reviewer: v-iap
ms.topic: article
ms.date: 02/12/2021
ms.author: supawa
---

# Mapping Parquet types to Common Data Model data types

This article provides assistance to developers in finding the appropriate equivalents of Parquet data types in Common Data Model.

- **Parquet Type**: This column represents Parquet data type. For more details, visit [here](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md).
- **Common Data Model Type**: Each attribute in Common Data Model entities can be associated with a single data type. A Common Data Model data type is an object that represents a collection of traits. All data types should indicate the data format traits but can also add additional semantic information.For more details, visit [here](logical-definitions.md#the-datatype-object)
- **Trait**: Traits are the fundamental mechanism in the Common Data Model metadata grammar for describing the data format, semantic meaning, and specifications for entities, attributes and other objects, such as partitions or manifests.For more details visit [here](trait-concepts-and-use-cases.md)
- **Unsupported Types**: Common Data Model doesn't offer out-of-box equivalents. Depending on the use case, users can define new data types but it will not be standard.

The following code snippet sets integer data type to Common Data Model attribute. Follow [CDM SDK API documentation](../1.0om/api-reference/api-reference.md) for the API references.  

```csharp
CdmTypeAttributeDefinition artAtt = MakeObject<CdmTypeAttributeDefinition>(CdmObjectType.TypeAttributeDef, "count"); 
artAtt.DataType = MakeObject<CdmDataTypeReference>(CdmObjectType.DataTypeRef, "integer", true); 
```
[Here](../samples.md#customize-entities) is a sample application demonstrating how data types can be set.

Parquet Type | Common Data Model Type | Trait
-------|----|-------
BOOLEAN | [boolean](list-of-datatypes.md#boolean) | [is.dataFormat.boolean](list-of-traits.md#isdataformatboolean)
FLOAT | [float](list-of-datatypes.md#float) |  [is.dataFormat.floatingPoint](list-of-traits.md#isdataformatfloatingpoint)
DOUBLE | [double](list-of-datatypes.md#double) |  [is.dataFormat.floatingPoint](list-of-traits.md#isdataformatfloatingpoint),<br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)
BYTE_ARRAY | [binary](list-of-datatypes.md#binary) | [is.dataFormat.byte](list-of-traits.md#isdataformatbyte), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray)
STRING | [string](list-of-datatypes.md#string) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter),<br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)
UUID | [guid](list-of-datatypes.md#guid) | [is.dataFormat.guid](list-of-traits.md#isdataformatguid)
DECIMAL | [decimal](list-of-datatypes.md#decimal) | [is.dataFormat.numeric.shaped](list-of-traits.md#isdataformatnumericshaped) (extends [is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric))<br>It has two parameters: <UL><LI>precision - The total number of significant digits and datatype is an integer.</LI><LI>scale - The number of digits to the right of the decimal place and datatype is integer. 
DATE | [date](list-of-datatypes.md#date) | [is.dataFormat.date](list-of-traits.md#isdataformatdate)
INTERVAL | [binary](list-of-datatypes.md#binary) | [is.dataFormat.byte](list-of-traits.md#isdataformatbyte), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray)
JSON | [json](list-of-datatypes.md#json) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[means.content.text.JSON](list-of-traits.md#meanscontenttextjson)
ENUM | [string](list-of-datatypes.md#string) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)
**Signed integers** | |
INT(8, true) | [byte](list-of-datatypes.md#byte) | [is.dataFormat.byte](list-of-traits.md#isdataformatbyte)
INT(16, true) | [small integer](list-of-datatypes.md#smallinteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.small](list-of-traits.md#isdataformatsmall)
INT(32, true) | [Integer](list-of-datatypes.md#integer) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger)
INT(64, true) | [big integer](list-of-datatypes.md#biginteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig)
**Unsupported** | |
TIME (UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO)) | Not available | Not available 
TIMESTAMP (UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO)) | Not available | Not available 
INT96 | Not available | Not available 
Unsigned integers | Not available | Not available
Maps | Not available | Not available 
List | Not available | Not available 
BSON | Not available | Not available 
Null | Not available | Not available
