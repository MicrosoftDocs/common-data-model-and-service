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

This is the base interface for all Common Data Model objects. It's extended by *CdmObjectBase* and *CdmObjectDefinitionBase* in C#, Java, and TypeScript.

```csharp
public interface CdmObject
```
*This interface is substituted with a regular class in Python.*

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
|**FetchObjectDefinition\<T>([ResolveOptions](../utilities/resolveoptions.md))**<br/>*resOpt [optional]*: The resolve options.|Returns the resolved object reference.|T, where T extends [CdmObjectDefinition](cdmobjectdefinition.md)<br/><br/>**Note:** In TypeScript, there is an async variant of this function called FetchObjectDefinitionAsync. This function will load the import files as they are required by this function.|
|**FetchObjectDefinitionName()**|Returns the name of the object if this is an object definition, or the name of the referenced object if this is an object reference.|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**<br/>*baseDef*: The name of the object that we want to check whether this object is derived from it.<br/>*resOpt [optional]*: The resolve options.|Returns true if the object (or the referenced object) is an extension of the specified symbol name in some way.|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**<br/>*resOpt*: The resolve options.<br/>*host [optional]*: For internal use. The host to copy the object into, instead of creating a new object instance.|Creates a copy of this object.|[CdmObject](cdmobject.md)|
|**Validate()**|Validates that the object is configured properly. Returns false if it's not.|bool|
|**CreateSimpleReference([ResolveOptions](../utilities/resolveoptions.md))**<br/>*resOpt [optional]*: The resolve options.|Takes an object definition and returns the object reference that points to the definition.|[CdmObjectReference](cdmobjectreference.md)|

