---
title: Argument Collection | Microsoft Docs
description: API reference for CdmArgumentCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Argument Collection

An argument collection extends [Collection](collection.md) and adds additional behaviors specific to argument collections. 

```
public class CdmArgumentCollection extends CdmCollection<CdmArgumentDefinition>
```

## Constructors
|Name|Description|
|---|---|
**CdmArgumentCollection(CdmCorpusContext, [CdmTraitReference](traitreference.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The owner of this collection. Must be a trait reference because this collection is optimized to handle adjustments to the trait when adding an argument.|Initializes a new instance of the [CdmArgumentCollection](argumentcollection.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Add([CdmArgumentDefinition](argument.md))**<br/>*arg*: The argument to add to the collection.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Adds the specified argument to the collection. Returns the argument that was added to the collection.|[CdmArgumentDefinition](argument.md)|
|**Add(string, dynamic)**<br/>*name*: The name of the argument to add to the collection.<br/>*value*: The value of the argument to add to the collection.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates an argument with the specified name and value and adds it to the collection. Returns the argument that was added to the collection.|[CdmArgumentDefinition](argument.md)|
|**AddRange(IEnumerable\<[CdmArgumentDefinition](argument.md)>)**<br/>*argumentList*: The list of arguments to add.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of arguments to the collection.|void|
|**Insert(int, [CdmArgumentDefinition](argument.md))**<br/>*index*: The index to insert the argument at.<br/>*arg*: The argument to add to the collection.<br/><br/>*add(...) in Java.*|Inserts the argument into the collection at the specified index.|void|
|**FetchValue(string)**<br/>*name*: The name of the argument to fetch the value of.|Returns the value of the argument with the specified name.|dynamic|
|**UpdateArgument(string, dynamic)**<br/>*name*: The name of the argument to update.<br/>*value*: The value to update the argument with.|Updates the argument with the specified name with the specified value. If an argument with the specified name is not found, then it is created and added to the collection.|void|

