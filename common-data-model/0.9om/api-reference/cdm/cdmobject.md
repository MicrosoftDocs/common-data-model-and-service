---
title: CdmObject - Common Data Model | Microsoft Docs
description: Reference for CdmObject.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# CdmObject

This is the base interface for all CDM interfaces. It is extended by *CdmObjectBase* and *CdmObjectDefinitionBase*.

```
public interface CdmObject
```

## Properties
|Name|Type|Description|
|---|---|---|
|Id|int|The object's ID.|
|InDocument|[CdmDocumentDefinition](document.md)|The declaration document of the object.|
|AtCorpusPath|string|The corpus path of the object declaration.|
|ObjectType|[CdmObjectType](objecttype.md)|The object's type.|
|Owner|CdmObject|The object that owns or contains this object.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**FetchObjectDefinition\<T>(ResolveOptions)**<br/>*resOpt [optional]*: The resolve options.|Returns the resolved object reference.|T, where T : [CdmObjectDefinition](cdmobjectdefinition.md)|
|**FetchObjectDefinitionName()**|Returns the name of the object if this is an object definition, or the name of the referenced object if this is an object reference.|string|
|**IsDerivedFrom(string, ResolveOptions)**<br/>*baseDef*: The symbol name of the object that we want to check whether this object is derived from it.<br/>*resOpt [optional]*: The resolve options.|Returns true if the object (or the referenced object) is an extension of the specified symbol name in some way.|bool|
|**Copy(ResolveOptions)**<br/>*resOpt*: The resolve options.|Creates a copy of this object.|CdmObject|
|**Validate()**|Validates that the object is configured properly. Returns false if not.|bool|
|**CreateSimpleReference(ResolveOptions)**<br/>*resOpt [optional]*: The resolve options.|TODO|[CdmObjectReference](cdmobjectreference.md)|

