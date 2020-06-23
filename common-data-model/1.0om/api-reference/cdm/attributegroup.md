---
title: Attribute Group | Microsoft Docs
description: API reference for CdmAttributeGroupDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Attribute Group

An attribute group represents a group of [attribute items](attributeitem.md) that provide a similar role.

```csharp
public class CdmAttributeGroupDefinition extends CdmObjectDefinitionBase, CdmReferencesEntities
```
*CdmAttributeGroupDefinition extends CdmObjectDefinition, CdmReferencesEntities in Python.*<br/>
*CdmAttributeGroupDefinition extends CdmObjectDefinitionBase in TypeScript.*

## Constructors
|Name|Description|
|---|---|
|**CdmAttributeGroupDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*attributeGroupName*: The attribute group's name.|Initializes a new instance of the [CdmAttributeGroupDefinition](attributegroup.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|AttributeGroupName|string|The attribute group's name.|
|AttributeContext|CdmAttributeContextReference|The attribute group context.|
|Members|[CdmCollection](collection.md)\<[CdmAttributeItem](attributeitem.md)>|The collection of attribute items for the attribute group.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|