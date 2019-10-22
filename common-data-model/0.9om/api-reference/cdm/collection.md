---
title: Collection - Common Data Model | Microsoft Docs
description: Reference for CdmCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Collection

A collection holds a set of [CDM objects](cdmobject.md) and provides easier handling of them.

```
public class CdmCollection<CdmObject> extends IList<CdmObject> 
```

## Constructors
|Name|Description|
|---|---|
|**CdmCollection(CdmCorpusContext, [CdmObject](cdmobject.md), [CdmObjectType](objecttype.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The CDM object that contains this collection.<br/>*defaultType*: The default CDM object type of this collection.|Initializes a new instance of the CdmCollection class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Count<br/>(*Length* in Java and Python)|int|The number of items in the CDM collection.|

## Methods
There are additional methods and properties in this class that just extend IList\<T> methods/properties. These are: *this[...], AddRange(...), IndexOf(...), Insert(...), RemoveAt(...), Clear(), Contains(...), CopyTo(...), GetEnumerator(...),* and *IsReadOnly*. 

|Name|Description|Return Type|
|---|---|---|
|**Add(string, bool)**<br/>*name*: The name of the CDM object that is being added to the collection.<br/>*simpleRef [optional]*: A boolean that denotes whether we want a reference to be a simple reference, if we are adding one. The default value is false.|Adds a CDM object of a default type (the default type can be set in the property) with the given name to the collection.|void|
|**Add(T)**<br />*currObject*: The CDM object to add to the collection.|Adds the specified CDM object to the collection.	|void|
|**Remove(T)**<br/>*currObject*: The CDM object to remove from the collection.|Removes the specified CDM object from the collection.|boolean|
|**Item(string)**<br />*name*: The name of the CDM object to fetch.|Retrieves the CDM object with the specified name.|T|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**<br/>*resOpt*: The resolve options.|Creates a copy of the current CdmCollection.|CdmCollection\<T>|
