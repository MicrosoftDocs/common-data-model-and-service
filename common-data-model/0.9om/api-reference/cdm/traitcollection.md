---
title: Trait Collection - Common Data Model | Microsoft Docs
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
|**Add([CdmTraitReference](traitreference.md))**<br/>*trait*: The trait to add to the collection.|Adds the specified trait to the collection.|void|
|**Add([CdmTraitDefinition](trait.md), bool)**<br/>*traitDefinition*: The trait definition to use to create the trait reference.<br/>*simpleRef [optional]*: A boolean that denotes whether the trait reference is simple named or not. The default value is false.|Creates a trait reference based on the specified trait definition and adds it to the collection. Returns the trait reference that was added to the collection.|[CdmTraitReference](traitreference.md)|
|**Add(string, bool)**<br/>*name*: The name of the trait to add to the collection.<br/>*simpleRef [optional]*: A boolean that denotes whether the trait reference is simple named or not. The default value is false.|Creates a trait with the specified name and adds it to the collection. Returns the trait that was added to the collection.|[CdmTraitReference](traitreference.md)|
|**AddRange(IEnumerable\<[CdmTraitDefinition](trait.md)>, bool)**<br/>*traitList*: The list of trait definitions to use to create trait references that will be added to the collection.<br/>*simpleRef [optional]*: A boolean that denotes whether the trait reference is simple named or not. The default value is false.|Adds the elements of the specified list of trait definitions to the collection, after converting them to trait references first.|void|
|**Remove([CdmTraitDefinition](trait.md), bool)**<br/>*traitDefToRemove*: The trait whose reference we want to remove from the collection.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Removes the specified trait's trait reference from the collection. If there are multiple matches, this method will remove the first one by prioritizing traits that are from properties, even if *onlyFromProperty* is set to false. Returns true if the operation is successful, false otherwise.|bool|
|**Remove(string, bool)**<br/>*traitName*: The name of the trait to remove from the collection. <br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Removes the trait with the specified name from the collection. If there are multiple matches, this method will remove the first one by prioritizing traits that are from properties, even if *onlyFromProperty* is set to false. Returns true if the operation is successful, false otherwise.|bool|
|**Remove([CdmTraitReference](traitreference.md), bool)**<br/>*traitToRemove*: The trait to remove from the collection.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Removes the specified trait from the collection. Returns true if the operation is successful, false otherwise.|bool|
|**IndexOf([CdmTraitDefinition](trait.md), bool)**<br/>*traitDefinition*: The trait definition associated with the trait reference we want the index of.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Returns the index of the specified trait definition's trait reference, or -1 if no such trait exists in the collection.|int|
|**IndexOf(string, bool)**<br/>*traitName*: The trait name associated with the trait reference we want the index of.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Returns the index of the trait reference with the specified name, or -1 if no such trait exists in the collection.|int|
|**IndexOf([CdmTraitReference](traitreference.md), bool)**<br/>*trait*: The trait we want the index of.<br/>*onlyFromProperty*: A boolean that denotes whether this method should only be applied for traits that originate from properties.|Returns the index of the specified trait reference, or -1 if no such trait exists in the collection.|int|
