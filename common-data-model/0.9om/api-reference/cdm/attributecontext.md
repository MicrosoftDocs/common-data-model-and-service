---
title: Attribute Context - Common Data Model | Microsoft Docs
description: Reference for CdmAttributeContext.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Attribute Context (CdmAttributeContext extends CdmObjectDefinitionBase)

An attribute context provides more insight into an attribute's relationship (child/parent). It is heavily used during the entity's attribute resolution and can contain the history of all changes that lead to an attribute's resolution. Resolved concepts, such as resolved attributes, can contain attribute contexts to provide more insights into the original, non-resolved hierarchic attributes.

## Constructors
|Name|Description|
|---|---|
|**CdmAttributeContext(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The attribute context's name.|Initializes a new instance of the CdmAttributeContext class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The attribute context's name.|
|Contents|CdmCollection\<CdmObject>|The attribute context's content list.|
|Definition|CdmObjectReference|The reference to the object this attribute context was defined from.|
|Parent|CdmObjectReference|The attribute context's parent.|
|Type?|CdmAttributeContextType?|The attribute context's type (can be *Entity, EntityReferenceExtends, AttributeDefinition, EntityReferenceAsAttribute, AttributeGroup, GeneratedSet, GeneratedRound, AddedAttributeSupporting, AddedAttributeIdentity, AddedAttributeSelectedType AddedAttributeExpansionTotal,* or *PassThrough*).|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, ResolveOptions)**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|CdmObject|
|**Validate()**|See *CdmObject.Validate()*.|bool|