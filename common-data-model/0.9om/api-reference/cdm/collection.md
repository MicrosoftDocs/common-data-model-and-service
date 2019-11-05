---
title: Collection | Microsoft Docs
description: API reference for CdmCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Collection

A collection holds a set of [Common Data Model objects](cdmobject.md) and provides easy handling of them.

```
public class CdmCollection<CdmObject> extends List<CdmObject>
```

## Constructors
|Name|Description|
|---|---|
|**CdmCollection(CdmCorpusContext, [CdmObject](cdmobject.md), [CdmObjectType](objecttype.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The CDM object that contains this collection.<br/>*defaultType*: The default CDM object type of this collection.|Initializes a new instance of the [CdmCollection](collection.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|DefaultType|[CdmObjectType](objecttype.md)|The default CDM object type of this collection.|
|Count<br/><br/>*Length in TypeScript.*|int|The number of items in the CDM collection.|

## Methods
There are additional methods and properties in this class that just extend standard list methods (*Insert(...), RemoveAt(...), Clear(), Contains(...), CopyTo(...), GetEnumerator(...)*, etc.). 

|Name|Description|Return Type|
|---|---|---|
|**Add(string, bool)**<br/>*name*: The name of the CDM object to add to the collection.<br/>*simpleRef [optional]*: A boolean that denotes whether we want a reference to be a simple reference, if we are adding one. The default value is false.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates a CDM object of a default type with the specified name and adds it to the collection. The default type can be set in the property. Returns the CDM object that was added to the collection.|T|
|**Add(T)**<br />*currObject*: The CDM object to add to the collection.<br/><br/>*append(...). in Python, push(...) in TypeScript.*|Adds the specified CDM object to the collection.	Returns the CDM object that was added to the collection.|T|
|**AddRange(IEnumerable\<T>)**<br/>*list*: The list of objects to add.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of objects to the collection.|void|
|**Remove(T)**<br/>*currObject*: The CDM object to remove from the collection.|Removes the specified CDM object from the collection. Returns true if the operation is successful, false otherwise.|bool|
|**Item(string)**<br />*name*: The name of the CDM object to fetch.|Returns the CDM object with the specified name.|T|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**<br/>*resOpt*: The resolve options.<br/><br/>*Only in C#.*|Creates a copy of the current CDM collection.|[CdmCollection\<T>](collection.md)|
