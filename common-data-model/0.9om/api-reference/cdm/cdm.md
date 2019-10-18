---
title: CDM Object Model - Common Data Model | Microsoft Docs
description: API reference for 0.9 OM.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# CDM Object Model

## Overview

The hierarchical structure of the CDM object model:

![OM Hierarchy](omhierarchy.png)

The CDM object model (OM) provides two types of classes: definition classes and reference classes. Since the OM is heavily interconnected and different concepts have different interactions among each other, the OM introduces the reference classes in order to be able to easily reference different concepts without actually encapsulating them. Every reference class has its own corresponding definition class, and they are closely correlated. 

## Definition Classes

|Name|Description|
|---|---|
|[Argument](argument.md)|Exists inside [trait references](traitreference.md) and provides name/value pairs for a specific trait reference. Arguments give life to traits by enabling them to actually contain some specific data.|
|[Attribute Context](attributecontext.md)|Provides more insight into an attribute's (child/parent) relationship. It is heavily used during an entity's attribute resolution and can contain the history of all changes that lead to an attribute's resolution. Resolved concepts, such as resolved attributes, can contain attribute contexts to provide more insights into the original, non-resolved hierarchic attributes.|
|[Attribute Group](attributegroup.md)|Represents a group of [attribute items](attributeitem.md) that provide a similar role.|
|[Attribute Resolution Guidance](attributeresolutionguidance.md)|Provides properties that help with the resolution process of [entities](entity.md), attributes, and other resolvable CDM concepts.|
|[Collection](collection.md)|Holds a set of [CDM objects](cdmobject.md) and provides easier handling of them.|
|[Constant Entity](constantentity.md)|Provides a way of making an [entity](entity.md) with records of data in it and an associated schema in a JSON file. We use these whenever we want to store some table of information inside a parameter of a [trait](trait.md). They show up in the enum definitions, in the localized display text, etc.|

 
 
## Reference Classes

|Name|Description|
|---|---|



## Interfaces
|Name|Description|
|---|---|
|[Attribute Item](attributeitem.md)|Represents the base interface for a generic attribute that could be a [type attribute](typeattribute.md) or an [entity attribute](entityattribute.md).|