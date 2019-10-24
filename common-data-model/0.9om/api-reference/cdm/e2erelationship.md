---
title: E2E Relationship - Common Data Model | Microsoft Docs
description: Reference for CdmE2ERelationship.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# E2E Relationship

An E2E relationship is a relationship between two entities' attributes.

```
public class CdmE2ERelationship extends CdmObjectDefinitionBase
```
*CdmE2ERelationship extends CdmObjectDefinition in Python.*

## Constructors
|Name|Description|
|---|---|
|TODO: Update once exhibitsTraits is removed<br/>**CdmE2ERelationship(CdmCorpusContext, string, bool)**<br/>*ctx*: The corpus context.<br/>*name*: The relationship's name.<br/>*exhibitsTraits*: TODO|Initializes a new instance of the [CdmE2ERelationship](e2erelationship.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|Name|string|The relationship's name.|
|FromEntity|string|The entity the relationship is pointing from.|
|FromEntityAttribute|string|The entity attribute the relationship is pointing from.|
|ToEntity|string|The entity the relationship is pointing to.|
|ToEntityAttribute|string|The entity attribute the relationship is pointing to.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

