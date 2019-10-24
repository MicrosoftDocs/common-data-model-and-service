---
title: Data Format - Common Data Model | Microsoft Docs
description: Reference for CdmDataFormat.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Data Format

An enum class containing the data formats. 

C#, Python:
```
public enum CdmDataFormat
{
    Unknown,
    Int16,
    Int32,
    Int64,
    Float,
    Double,
    Guid,
    String,
    Char,
    Byte,
    Binary,
    Time,
    Date,
    DateTime,
    DateTimeOffset,
    Boolean,
    Decimal,
    Json
}
```

Java:
```
public enum CdmDataFormat {
    INTEGER("is.dataFormat.integer"),
    NUMERIC_SHAPED("is.dataFormat.numeric.shaped"),
    BOOLEAN("is.dataFormat.boolean"),
    SMALL("is.dataFormat.small"),
    BIG("is.dataFormat.big"),
    FLOATING_POINT("is.dataFormat.floatingPoint"),
    CHARACTER("is.dataFormat.character"),
    ARRAY("is.dataFormat.array"),
    GUID("is.dataFormat.guid"),
    BYTE("is.dataFormat.byte"),
    TIME("is.dataFormat.time"),
    DATE("is.dataFormat.date"),
    DATETIME_OFFSET("is.dataFormat.timeOffset"),
    JSON("means.content.text.JSON"),
    DEFAULT("default");
}
```


