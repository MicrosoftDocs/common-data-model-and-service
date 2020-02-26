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
|**CdmCollection(CdmCorpusContext, [CdmObject](cdmobject.md), [CdmObjectType](objecttype.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The object that contains this collection.<br/>*defaultType*: The default object type of this collection.|Initializes a new instance of the [CdmCollection](collection.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|DefaultType|[CdmObjectType](objecttype.md)|The default object type of this collection.|
|Count<br/><br/>*Length in TypeScript.*|int|The number of items in the collection.|

## Methods
There are additional methods and properties in this class that just extend standard list methods (*IndexOf(...), Insert(...), Clear(), Contains(...), CopyTo(...), GetEnumerator(...)*, etc.).

|Name|Description|Return Type|
|---|---|---|
|**Add(string, bool)**<br/>*name*: The name of the object to add to the collection.<br/>*simpleRef [optional]*: A boolean that denotes whether we want a reference to be a simple reference, if we're adding one. The default value is false.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates an object of a default type with the specified name and adds it to the collection. The default type can be set in the property. Returns the object that was added to the collection.|T|
|**Add(T)**<br />*currObject*: The object to add to the collection.<br/><br/>*append(...). in Python, push(...) in TypeScript.*|Adds the specified object to the collection. Returns the  object that was added to the collection.|T|
|**AddRange(IEnumerable\<T>)**<br/>*list*: The list of objects to add.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of objects to the collection.|void|
|**Remove(T)**<br/>*currObject*: The object to remove from the collection.|Removes the specified object from the collection. Returns true if the operation is successful, false otherwise.|bool|
|**RemoveAt(int)**<br/>*index*: The index of the object to remove.<br/><br/>*pop(...) in Python.*|Removes the object at the specified index from the collection.|void|
|**Item(string)**<br />*name*: The name of the object to fetch.|Returns the object with the specified name.|T|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**<br/>*resOpt*: The resolve options.<br/><br/>*Only in C# and Java.*|Creates a copy of the current collection.|[CdmCollection\<T>](collection.md)|
