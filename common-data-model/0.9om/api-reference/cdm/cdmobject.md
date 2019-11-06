---
title: CdmObject | Microsoft Docs
description: API reference for CdmObject.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# CdmObject

This is the base interface for all Common Data Model objects. It is extended by *CdmObjectBase* and *CdmObjectDefinitionBase* in C#, Java, and TypeScript.

```
public interface CdmObject
```
*CdmObject is a class in Python.*

## Properties
|Name|Type|Description|
|---|---|---|
|Id|int|The object's ID.|
|InDocument|[CdmDocumentDefinition](document.md)|The document where this object is defined inside of.|
|AtCorpusPath|string|The corpus path to the object.|
|ObjectType|[CdmObjectType](objecttype.md)|The object's type.|
|Owner|[CdmObject](cdmobject.md)|The object that owns or contains this object.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FetchObjectDefinition\<T>([ResolveOptions](../utilities/resolveoptions.md))**<br/>*resOpt [optional]*: The resolve options.|Returns the resolved object reference.|T, where T extends [CdmObjectDefinition](cdmobjectdefinition.md)|
|**FetchObjectDefinitionName()**|Returns the name of the object if this is an object definition, or the name of the referenced object if this is an object reference.|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**<br/>*baseDef*: The name of the object that we want to check whether this object is derived from it.<br/>*resOpt [optional]*: The resolve options.|Returns true if the object (or the referenced object) is an extension of the specified symbol name in some way.|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**<br/>*resOpt*: The resolve options.|Creates a copy of this object.|[CdmObject](cdmobject.md)|
|**Validate()**|Validates that the object is configured properly. Returns false if it is not.|bool|
|**CreateSimpleReference([ResolveOptions](../utilities/resolveoptions.md))**<br/>*resOpt [optional]*: The resolve options.|Takes an object definition and returns the object reference that points to the definition.|[CdmObjectReference](cdmobjectreference.md)|

