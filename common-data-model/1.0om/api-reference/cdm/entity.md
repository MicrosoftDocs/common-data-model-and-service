---
title: Entity | Microsoft Docs
description: API reference for CdmEntityDefinition.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 10/18/2019
ms.author: jibyun
---

# Entity 

An entity is the basic building block of the object model. It provides a concrete placeholder for a user to attach certain information to a concept. It's a collection of attributes that creates a semantic meaning of why these attributes coexist. Since entities can inherit from other entities, it's possible for them to represent a hierarchical structure. The hierarchical structure can also be removed from the entities by resolving them.

```csharp
public class CdmEntityDefinition extends CdmObjectDefinitionBase, CdmReferencesEntities
```
*CdmEntityDefinition extends CdmObjectDefinition, CdmReferencesEntities in Python.*<br/>
*CdmEntityDefinition extends CdmObjectDefinitionBase in TypeScript.*

## Constructors
|Name|Description|
|---|---|
|**CdmEntityDefinition(CdmCorpusContext, string, CdmEntityReference)**<br/>*ctx*: The corpus context.<br/>*entityName*: The entity's name.<br/>*extendsEntity [optional]*: The entity extended by this entity.|Initializes a new instance of the [CdmEntityDefinition](entity.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|EntityName|string|The entity's name.|
|ExtendsEntity|CdmEntityReference|The entity extended by this entity.|
|Attributes|[CdmCollection](collection.md)\<[CdmAttributeItem](attributeitem.md)>|The collection of attributes for this entity.|
|AttributeContext|[CdmAttributeContext](attributecontext.md)|The entity's attribute context.|
|DisplayName|string|The entity's display name.|
|SourceName|string|The entity's source name - the original entity name from another source system (for example, *Dynamics*).|
|Description|string|The entity's description.|
|CdmSchemas|List\<string>|The list of Common Data Model entities that the entity "contains" or implements (a set of contracts or interfaces).|
|Version|string|The entity's version.|
|ExtendsEntityResolutionGuidance|[CdmAttributeResolutionGuidance](attributeresolutionguidance.md)|The resolution guidance for the attributes taken from the entity extended by this entity.|
|PrimaryKey|string|The attribute that identifies itself as the primary key.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CreateResolvedEntityAsync(string, [ResolveOptions](../utilities/resolveoptions.md), [CdmFolderDefinition](folder.md), string)**<br />*newEntName*: The new entity name.<br/>*resOpt [optional]*: The resolve options.<br/>*folder [optional]*: The folder that will be used as a target corpus path. If not specified, *InDocument's* folder (a property on the entity) is used instead.<br/>*newDocName [optional]*: The new document name.|Creates a resolved copy of the entity.|Task\<[CdmEntityDefinition](entity.md)>|
|**GetName()**|See [CdmObjectDefinition.GetName()](cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.IsDerivedFrom(...)](cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../utilities/resolveoptions.md), [CdmObject](cdmobject.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|

