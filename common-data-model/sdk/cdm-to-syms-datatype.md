---
title: Mapping  types Common Data Model to SyMS data types | Microsoft Docs
description: This article provides assistance to developers in finding the appropriate equivalents of Common Data Model in SyMS.
author: surenderpawar
ms.service: common-data-model
ms.topic: article
ms.date: 11/02/2021
ms.author: supawa
---

# Mapping Common Data Model to SyMS data types

This article provides assistance to developers in finding the appropriate equivalents of Common Data Model in SyMS.

- **Common Data Model Type**: Each attribute in Common Data Model entities can be associated with a single data type. A Common Data Model data type is an object that represents a collection of traits. All data types should indicate the data format traits but can also add additional semantic information.For more details, visit [here](logical-definitions.md#the-datatype-object)
- **Trait**: Traits are the fundamental mechanism in the Common Data Model metadata grammar for describing the data format, semantic meaning, and specifications for entities, attributes and other objects, such as partitions or manifests.For more details visit [here](trait-concepts-and-use-cases.md)
- **SyMS Type**: This column represents SyMS data type.

The following code snippet sets integer data type to Common Data Model attribute. Follow [CDM SDK API documentation](../1.0om/api-reference/api-reference.md) for the API references.  

```csharp
CdmTypeAttributeDefinition artAtt = MakeObject<CdmTypeAttributeDefinition>(CdmObjectType.TypeAttributeDef, "count"); 
artAtt.DataType = MakeObject<CdmDataTypeReference>(CdmObjectType.DataTypeRef, "integer", true); 
```
[Here](../samples.md#customize-entities) is a sample application demonstrating how data types can be set.

Common Data Model Equivalent | Trait | SyMS data type
-------|----|-------
[boolean](list-of-datatypes.md#boolean) | [is.dataFormat.boolean](list-of-traits.md#isdataformatboolean) | boolean
[float](list-of-datatypes.md#float) |  [is.dataFormat.floatingPoint](list-of-traits.md#isdataformatfloatingpoint) | float
[double](list-of-datatypes.md#double) |  [is.dataFormat.floatingPoint](list-of-traits.md#isdataformatfloatingpoint), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig) | double
[byte](list-of-datatypes.md#binary) | [is.dataFormat.byte](list-of-traits.md#isdataformatbyte) | byte
[smallinteger](list-of-datatypes.md#smallinteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.small](list-of-traits.md#isdataformatsmall) | short
[Integer](list-of-datatypes.md#integer) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger) | integer
[biginteger](list-of-datatypes.md#biginteger) | [is.dataFormat.integer](list-of-traits.md#isdataformatinteger), <br>[is.dataFormat.big](list-of-traits.md#isdataformatbig) | long
[char](list-of-datatypes.md#string) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter) | string </br>(length=1)
[string](list-of-datatypes.md#string) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[is.dataFormat.big](list-of-traits.md#isdataformatbig) | string
[guid](list-of-datatypes.md#guid) | [is.dataFormat.guid](list-of-traits.md#isdataformatguid) | string<br>(properties[guid] = true)
[decimal](list-of-datatypes.md#decimal) | [is.dataFormat.numeric.shaped](list-of-traits.md#isdataformatnumericshaped) (extends [is.dataFormat.numeric](list-of-traits.md#isdataformatnumeric))<br>It has two parameters: <UL><LI>precision - The total number of significant digits and datatype is an integer.</LI><LI>scale - The number of digits to the right of the decimal place and datatype is integer. | decimal
[time](list-of-datatypes.md#time) | [is.dataFormat.time](list-of-traits.md#isdataformattime) | timestamp
[date](list-of-datatypes.md#date) | [is.dataFormat.date](list-of-traits.md#isdataformatdate) | date
[dateTime](list-of-datatypes.md#datetimeoffset) | [is.dataFormat.date](list-of-traits.md#isdataformatdate), [means.measurement.date](list-of-traits.md#meansmeasurementdate), [is.dataFormat.time](list-of-traits.md#isdataformattime), [means.measurement.time](list-of-traits.md#meansmeasurementtime) | timestamp<br>(properties[datetime] = true)
[dateTimeOffset ](list-of-datatypes.md#datetimeoffset) | [is.dataFormat.date](list-of-traits.md#isdataformatdate), [means.measurement.date](list-of-traits.md#meansmeasurementdate), [is.dataFormat.time](list-of-traits.md#isdataformattime), [means.measurement.time](list-of-traits.md#meansmeasurementtime), [is.dataFormat.timeOffset](list-of-traits.md#isdataformattimeoffset) | string<br>(properties[datetimeoffset] = true)
[json](list-of-datatypes.md#json) | [is.dataFormat.character](list-of-traits.md#isdataformatcharacter), <br>[is.dataFormat.array](list-of-traits.md#isdataformatarray),<br>[means.content.text.JSON](list-of-traits.md#meanscontenttextjson) | string<br> (properties[json] = true)