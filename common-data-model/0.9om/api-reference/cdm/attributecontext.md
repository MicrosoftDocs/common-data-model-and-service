---
title: Attribute Context | Microsoft Docs
description: API reference for CdmAttributeContext.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Attribute Context

An attribute context provides more insight into an attribute's (parent/child) relationship. It is heavily used during an entity's attribute resolution and can contain the history of all changes that led to an attribute's resolution. Resolved concepts, such as resolved attributes, can contain attribute contexts to provide more insight into the original, non-resolved hierarchical attributes.

```
public class CdmAttributeContext extends CdmObjectDefinitionBase
```
*CdmAttributeContext extends CdmObjectDefinition in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmAttributeContext(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The attribute context's name.|Initializes a new instance of the [CdmAttributeContext](attributecontext.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The attribute context's name.|
|Contents|[CdmCollection](collection.md)\<[CdmObject](cdmobject.md)>|The attribute context's content collection.|
|Definition|[CdmObjectReference](cdmobjectreference.md)|The reference to the object this attribute context was defined from.|
|Parent|[CdmObjectReference](cdmobjectreference.md)|The attribute context's parent.|
|Type|[CdmAttributeContextType?](attributecontexttype.md)|The attribute context's type.|
|AtCorpusPath|string|The path to the object declaration, relative to the declaration of the resolved entity. For an attribute context, we do not follow the standard path calculation behavior.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|