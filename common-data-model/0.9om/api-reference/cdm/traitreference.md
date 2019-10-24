---
title: Trait Reference - Common Data Model | Microsoft Docs
description: Reference for CdmTraitReference.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Trait Reference

This is the reference class for [traits](trait.md).

```
public class CdmTraitReference extends CdmObjectReferenceBase
```

## Constructors
|Name|Description|
|---|---|
|TODO: Update once simpleReference is removed<br/>**CdmTraitReference(CdmCorpusContext, dynamic, bool, bool)**<br/>*ctx*: The corpus context.<br/>*trait*: The trait that this trait reference is referencing.<br/>*simpleReference*: TODO<br/>*hasArguments*: A boolean that denotes whether this trait reference has arguments.|Initializes a new instance of the [CdmTraitReference](traitreference.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|IsFromProperty|bool|Denotes whether the trait was generated from a property or if it was directly loaded.|
|Arguments|TODO: Replace with CdmArgumentCollection later<br/>[CdmCollection](collection.md)\<[CdmArgumentDefinition](argument.md)>|The trait reference's arguments.|


## Methods
|Name|Description|Return Type|
|---|---|---|
|TODO: Update once CdmArgumentCollection is created<br/>**AddArgument(string, dynamic)**<br />*name*: The name of the argument.<br/>*value*: The value of the argument.|Adds an argument with the specified name and value to the Arguments list. Arguments have to match the parameters format specified in the schema documents.|[CdmArgumentDefinition](argument.md)|
|TODO: Update once CdmArgumentCollection is created<br/>**FetchArgumentValue(string)**<br />*name*: The name of the argument.|Retrieves the value for the specified argument name from the arguments list.|dynamic|
|TODO: Update once CdmArgumentCollection is created<br/>**UpdateArgumentValue(string, dynamic)**<br />*name*: The name of the argument.<br/>*value*: The value of the argument.|Sets the specified value to the argument with the specified name.|void|


