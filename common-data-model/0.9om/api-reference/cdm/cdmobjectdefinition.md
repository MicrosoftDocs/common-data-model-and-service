---
title: CdmObject Definition - Common Data Model | Microsoft Docs
description: Reference for CdmObjectDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# CdmObject Definition

This is the base for all CDM object definitions. It is extended by *CdmObjectDefinitionBase* in C# and Java.

```
public interface CdmObjectDefinition extends CdmObject
```
*CdmObjectDefinition is a class in Python.*

## Properties
|Name|Type|Description|
|---|---|---|
|Explanation|string|The object's explanation.|
|ExhibitsTraits|[CdmTraitCollection](traitcollection.md)|The collection of  traits that this object exhibits.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|All object definitions have some kind of name, so this method returns the name independent of the name from the *name* property.|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**<br/>*baseDef*: The name of the object that we want to check whether this object is derived from it.<br/>*resOpt [optional]*: The resolve options.|Returns true if the object (or the referenced object) is an extension of the specified symbol name in some way.|bool|


