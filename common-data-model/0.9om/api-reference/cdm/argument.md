---
title: Argument Class - Common Data Model | Microsoft Docs
description: Reference for CdmArgumentDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Argument Class

An argument exists inside trait references and provides name/value pairs for a specific trait reference. Arguments give life to traits by enabling them to actually contain some specific data.

```
public class CdmArgumentDefinition : CdmObjectSimple 
```

## Constructors
|||
|---|---|
|**CdmArgumentDefinition(CdmCorpusContext)**<br />*ctx*: The corpus context.|Initializes a new instance of the CdmArgumentDefinition class.|

## Properties
|||
|---|---|
|Name|The argument's name.|
|Value|The argument's value.| 
|Explanation|The argument's explanation.|