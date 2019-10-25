---
title: Argument Collection - Common Data Model | Microsoft Docs
description: Reference for CdmArgumentCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Argument Collection

An argument collection extends [Collection](collection.md) and adds additional behaviors specific to argument collections. It is used only for the *Arguments* property in [trait references](traitreference.md) and not for any other argument collections because this collection is optimized to handle adjustments to the trait when adding an argument.

```
public class CdmArgumentCollection extends CdmCollection<CdmArgumentDefinition>
```

## Constructors
|Name|Description|
|---|---|
**CdmArgumentCollection(CdmCorpusContext, [CdmTraitReference](traitreference.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The trait reference that contains this collection.|Initializes a new instance of the [CdmArgumentCollection](argumentcollection.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Add([CdmArgumentDefinition](argument.md))**<br/>*arg*: The argument to add to the collection.|Adds the specified argument to the collection.|void|
|**Add(string, dynamic)**<br/>*name*: The name of the argument to add to the collection.<br/>*value*: The value of the argument to add to the collection.|Creates an argument with the specified name and value and adds it to the collection. Returns the argument that was added to the collection.|[CdmArgumentDefinition](argument.md)|
|**AddRange(IEnumerable\<[CdmArgumentDefinition](argument.md)>)**<br/>*argumentList*: The list of arguments to add.|Adds the elements of the specified list of arguments to the collection.|void|
|**FetchValue(string)**<br/>*name*: The name of the argument to fetch the value of.|Returns the value of the argument with the specified name.|dynamic|
|**UpdateArgument(string, dynamic)**<br/>*name*: The name of the argument to update.<br/>*value*: The value to update the argument with.|Updates the argument with the specified name with the specified value. Returns true if the operation is successful, false otherwise.|bool|
|**UpdateOrAddArgument(string, dynamic)**<br/>*name*: The name of the argument to update.<br/>*value*: The value to update the argument with.|Updates the argument with the specified name with the specified value. If an argument with the specified name is not found, then it is created instead.|void|
