---
title: Trait Collection | Microsoft Docs
description: API reference for CdmTraitCollection.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Trait Collection

A trait collection extends [Collection](collection.md) and adds additional behaviors specific to trait collections.

```
public class CdmTraitCollection extends CdmCollection<CdmTraitReference>
```

## Constructors
|Name|Description|
|---|---|
|**CdmTraitCollection(CdmCorpusContext, [CdmObject](cdmobject.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The CDM object that contains this collection.|Initializes a new instance of the [CdmTraitCollection](traitcollection.md) class.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**Add([CdmTraitReference](traitreference.md))**<br/>*trait*: The trait to add to the collection.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Adds the specified trait to the collection. Returns the trait that was added to the collection.|[CdmTraitReference](traitreference.md)|
|**Add([CdmTraitDefinition](trait.md), bool)**<br/>*traitDefinition*: The trait definition to use to create the trait reference.<br/>*simpleRef [optional]*: A boolean that denotes whether the trait reference is simple named or not. The default value is false.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates a trait reference based on the specified trait definition and adds it to the collection. Returns the trait reference that was added to the collection.|[CdmTraitReference](traitreference.md)|
|**Add(string, bool)**<br/>*name*: The name of the trait to add to the collection.<br/>*simpleRef [optional]*: A boolean that denotes whether the trait reference is simple named or not. The default value is false.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates a trait with the specified name and adds it to the collection. Returns the trait that was added to the collection.|[CdmTraitReference](traitreference.md)|
|**AddRange(IEnumerable\<[CdmTraitDefinition](trait.md)>, bool)**<br/>*traitList*: The list of trait definitions to use to create trait references that will be added to the collection.<br/>*simpleRef [optional]*: A boolean that denotes whether the trait reference is simple named or not. The default value is false.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of trait definitions to the collection, after converting them to trait references first.|void|
|**Insert(int, [CdmTraitReference](traitreference.md))**<br/>*index*: The index to insert the trait at.<br/>*trait*: The trait to add to the collection.|Inserts the trait into the collection at the specified index.|void|
|**Remove([CdmTraitDefinition](trait.md), bool)**<br/>*traitDefToRemove*: The trait whose reference we want to remove from the collection.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Removes the trait reference with the same name as the specified trait definition from the collection. If there are multiple matches, this method will remove the first one by prioritizing traits that are from properties, even if *onlyFromProperty* is set to false. Returns true if the operation is successful, false otherwise.|bool|
|**Remove(string, bool)**<br/>*traitName*: The name of the trait to remove from the collection. <br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Removes the trait with the specified name from the collection. If there are multiple matches, this method will remove the first one by prioritizing traits that are from properties, even if *onlyFromProperty* is set to false. Returns true if the operation is successful, false otherwise.|bool|
|**Remove([CdmTraitReference](traitreference.md), bool)**<br/>*traitToRemove*: The trait to remove from the collection.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Removes the trait with the same name as the specified trait from the collection. Returns true if the operation is successful, false otherwise.|bool|
|**RemoveAt(int)**<br/>*index*: The index of the trait to remove.|Removes the trait at the specified index from the collection.|void|
|**IndexOf([CdmTraitDefinition](trait.md), bool)**<br/>*traitDefinition*: The trait whose reference we want the index of.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.<br/><br/>*index(...) in Python.*|Returns the index of the trait reference with the same name as the specified trait definition. If there are multiple matches, this method will return the index of the first trait that is from a property. If there are not any traits from properties and *onlyFromProperty* is false, then this method will return the index of the last trait that is not from a property.|int|
|**IndexOf(string, bool)**<br/>*traitName*: The trait name associated with the trait reference we want the index of.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.<br/><br/>*index(...) in Python.*|Returns the index of the trait reference with the specified name. If there are multiple matches, this method will return the index of the first trait that is from a property. If there are not any traits from properties and *onlyFromProperty* is false, then this method will return the index of the last trait that is not from a property.|int|
|**IndexOf([CdmTraitReference](traitreference.md), bool)**<br/>*trait*: The trait we want the index of.<br/>*onlyFromProperty*: A boolean that denotes whether this method should only be applied for traits that originate from properties.<br/><br/>*index(...) in Python.*|Returns the index of the trait reference with the same name as the specified trait. If there are multiple matches, this method will return the index of the first trait that is from a property. If there are not any traits from properties and *onlyFromProperty* is false, then this method will return the index of the last trait that is not from a property.|int|


