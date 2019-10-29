---
title: CdmObject Definition | Microsoft Docs
description: API reference for CdmObjectDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# CdmObject Definition

This is the base for all Common Data Model object definitions. It is extended by *CdmObjectDefinitionBase* in C# and Java.

```
public interface CdmObjectDefinition extends CdmObject
```
*CdmObjectDefinition is a class in Python.*

## Properties
|Name|Type|Description|
|---|---|---|
|Explanation|string|The object's explanation.|
|ExhibitsTraits|[CdmTraitCollection](traitcollection.md)|The collection of traits that this object exhibits by default.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|All object definitions have some kind of name, so this method returns the name independent from the *name* property.|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**<br/>*baseDef*: The name of the object that we want to check whether this object is derived from it.<br/>*resOpt [optional]*: The resolve options.|Returns true if the object (or the referenced object) is an extension of the specified symbol name in some way.|bool|


