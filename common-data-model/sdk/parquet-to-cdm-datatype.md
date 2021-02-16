---
title: Parquet Type to CDM Type | Microsoft Docs
description: Parquet Type to CDM Type.
author: supawa
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 02/12/2021
ms.author: 
---

# Parquet Type to CDM Type

This document helps user to find the mapping from Parquet data type to CDM data type. 

Document | Description | 
------|--------
[Parquet Type](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md) | This column represents parquet data type. For more details visit [here](https://github.com/apache/parquet-format/blob/master/LogicalTypes.md).
[CDM Type](sdk/list-of-datatypes.md) | This represents datatype in CDM format. For more details visit [here](https://docs.microsoft.com/en-us/common-data-model/sdk/logical-definitions#the-datatype-object)
[Trait](sdk/trait-concepts-and-use-cases.md) | Traits are the fundamental mechanism in the Common Data Model metadata grammar for describing the data format, semantic meaning, and specifications for entities, attributes and other objects, such as partitions or manifests.
Unsupported Types | CDM doesn't offer out-of-box equivalents. Depending on the use case, users can define new data types but it would not be standard.

<br/>The following is code snippet to set integer data type to CDM attribute. Please follow [CDM SDK API documentation](1.0om/api-reference/api-reference.md) for the API references.  

```csharp
CdmTypeAttributeDefinition artAtt = MakeObject<CdmTypeAttributeDefinition>(CdmObjectType.TypeAttributeDef, "count"); 
artAtt.DataType = MakeObject<CdmDataTypeReference>(CdmObjectType.DataTypeRef, "integer", true); 
```

Parquet Type | CDM Type | Trait
-------|----|-------
string | [string](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#string) | [is.dataFormat.character](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatcharacter),<br>[is.dataFormat.array](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatarray),<br>[is.dataFormat.big](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatbig)
uuid | [guid](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#guid) | [is.dataFormat.guid](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatguid)
Decimal | [decimal](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#decimal) | [is.dataFormat.numeric.shaped](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatnumericshaped) (extends [is.dataFormat.numeric](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatnumeric))<br>It has two parameters. Precision (the total number of significant digits and datatype is an integer.) and scale (the number of digits to the right of the decimal place and datatype is integer). 
Date | [date](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#date) | [is.dataFormat.date](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatdate)
interval | [binary](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#binary) | [is.dataFormat.byte](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatbyte), <br>[is.dataFormat.array](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatarray)
Json | [json](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#json) | [is.dataFormat.character](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatcharacter), <br>[is.dataFormat.array](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatarray),<br>[means.content.text.JSON](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#meanscontenttextjson)
Enum | [string](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#string) | [is.dataFormat.character](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatcharacter), <br>[is.dataFormat.array](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatarray),<br>[is.dataFormat.big](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatbig)
boolean | [boolean](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#boolean) | [is.dataFormat.boolean](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatboolean)
**Signed integer** | |
INT(8, true) | [byte](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#byte) | [is.dataFormat.byte](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatbyte)
INT(16, true) | [smallinteger](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#smallinteger) | [is.dataFormat.integer](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatinteger), <br>[is.dataFormat.small]()
INT(32, true) | [Integer](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#integer) | [is.dataFormat.integer](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatinteger)
INT(64, true) | [biginteger](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-datatypes#biginteger) | [is.dataFormat.integer](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatinteger), <br>[is.dataFormat.big](https://docs.microsoft.com/en-us/common-data-model/sdk/list-of-traits#isdataformatbig)
**Unsupported** | |
Time (UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO)) | NA | NA 
Timestamp ( UTC adjustment (true/false) and precision (MILLIS/MICRO/NANO) ) | NA | NA 
unsigned integer | NA | NA 
map | NA | NA 
list | NA | NA 
Bson | NA | NA 
null | NA | NA




