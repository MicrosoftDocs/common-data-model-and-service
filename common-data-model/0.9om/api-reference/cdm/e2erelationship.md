---
title: E2E Relationship | Microsoft Docs
description: API reference for CdmE2ERelationship.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# E2E Relationship

An E2E relationship is a relationship between two entity's attributes.

```
public class CdmE2ERelationship extends CdmObjectDefinitionBase
```
*CdmObjectDefinitionBase is called CdmObjectDefinition in Python.*

## Constructors
|Name|Description|
|---|---|
|**CdmE2ERelationship(CdmCorpusContext, string)**<br/>*ctx*: The corpus context.<br/>*name*: The relationship's name.|Initializes a new instance of the [CdmE2ERelationship](e2erelationship.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The relationship's name.|
|FromEntity|string|The corpus path to the entity the relationship is pointing from.|
|FromEntityAttribute|string|The entity attribute the relationship is pointing from (foreign key).|
|ToEntity|string|The corpus path to entity the relationship is pointing to.|
|ToEntityAttribute|string|The entity attribute the relationship is pointing to (often the entity's primary key).|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

