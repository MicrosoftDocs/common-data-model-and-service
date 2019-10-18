---
title: Attribute Group Class - Common Data Model | Microsoft Docs
description: Reference for CdmAttributeGroupDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Attribute Group Class 

An attribute group represents a group of [attribute items](attributeitem.md) that provide a similar role.

```
public class CdmAttributeGroupDefinition extends CdmObjectDefinitionBase, CdmReferencesEntities
```

## Constructors
|Name|Description|
|---|---|
|**CdmAttributeGroupDefinition(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*attributeGroupName*: The attribute group's name.|Initializes a new instance of the CdmAttributeGroupDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|AttributeGroupName|string|The attribute group's name.|
|AttributeContext|CdmAttributeContextReference|The attribute group context.|
|Members|CdmCollection\<CdmAttributeItem>|The list of attribute items for the attribute group.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, ResolveOptions)**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|CdmObject|
|**Validate()**|See *CdmObject.Validate()*.|bool|