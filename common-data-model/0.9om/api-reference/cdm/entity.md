---
title: Entity Class - Common Data Model | Microsoft Docs
description: Reference for CdmEntityDefinition.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Entity Class

An entity is the basic building block of the OM. It provides a concrete placeholder for a user to attach certain information to a concept. It is a collection of attributes that creates some semantic meaning of why these attributes exist together. Since entities can inherit from other entities, it is possible for them to represent a hierarchical structure. The hierarchical structure can also be removed from the entities by resolving them.

TODO: Remove CdmReferencesEntities inheritence once CdmReferencesEntities is deleted
```
public class CdmEntityDefinition extends CdmObjectDefinitionBase, CdmReferencesEntities
```

## Constructors
|Name|Description|
|---|---|
|TODO: Update once exhibitsTraits is removed and extends entity is optional<br/>**CdmEntityDefinition(CdmCorpusContext, string, CdmEntityReference, bool, bool)**<br/>*ctx*: The corpus context.<br/>*entityName*: The entity's name.<br/>*extendsEntity*: The entity extended by this entity.<br/>*exhibitsTraits [optional]*: TODO. The default value is false.<br/>*hasAttributes [optional]*: A boolean that denotes whether this entity has attributes. The default value is false.|Initializes a new instance of the CdmEntityDefinition class.|

## Properties
|Name|Type|Description|
|---|---|---|
|EntityName|string|The entity's name.|
|ExtendsEntity|CdmEntityReference|The entity extended by this entity.|
|Attributes|[CdmCollection](collection.md)\<[CdmAttributeItem](attributeitem.md)>|The list of attributes for this entity.|
|AttributeContext|[CdmAttributeContext](attributecontext.md)|The entity's attribute context.|
|DisplayName|string|The entity's display name.|
|SourceName|string|The entity's source name - the original entity name from another source system (e.g. *Dynamics*).|
|Description|string|The entity's description.|
|CdmSchemas|string|The list of CDM entities that the entity "contains" or implements (a set of contracts or interfaces).|
|Version|string|The entity's version.|
|ExtendsEntityResolutionGuidance|[CdmAttributeResolutionGuidance](attributeresolutionguidance.md)|The resolution guidance for the attributes taken from the entity extended by this entity.|
|PrimaryKey|string|TODO|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**CreateResolvedEntityAsync(string, ResolveOptions, [CdmFolderDefinition](folder.md), string)**<br />*newEntName*: The new entity name.<br/>*resOpt [optional]*: The resolve options.<br/>*folder [optional]*: The folder that will be used as a target corpus path. If not specified, in-document folder (a property on the entity) is used.<br/>*newDocName [optional]*: The new document name.|Creates a resolved copy of the entity.|Task\<CdmEntityDefinition>|
|**GetName()**|See *CdmObjectDefinition.GetName()*.|string|
|**IsDerivedFrom(string, ResolveOptions)**|See *CdmObject.IsDerivedFrom(...)*.|bool|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|[CdmObject](cdmobject.md)|
|**Validate()**|See *CdmObject.Validate()*.|bool|

