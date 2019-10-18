---
title: Attribute Resolution Guidance - Common Data Model | Microsoft Docs
description: Reference for CdmAttributeResolutionGuidance.
author: jinichu
ms.service: common-data-model
ms.reviewer: 
ms.topic: article
ms.date: 10/18/2019
ms.author: jinichu
---

# Attribute Resolution Guidance (CdmAttributeResolutionGuidance extends CdmObjectSimple)

Provides properties that help with the resolution process of [entities](entity.md), attributes, and other resolvable CDM concepts.

## Constructors
|Name|Description|
|---|---|
|**CdmAttributeResolutionGuidance(CdmCorpusContext)**<br/>*ctx*: The corpus context.|Initializes a new instance of the CdmAttributeResolutionGuidance class.|

## Properties
|Name|Type|Description|
|---|---|---|
|removeAttribute|bool?|If true, this attribute definition will be removed from the entity's final resolved attribute list.|
|imposedDirectives|List\<string>|A list of strings, one for each 'directive' that should always be imposed at this attribute definition.|
|removedDirectives|List\<string>|A list of strings, one for each 'directive' that should be removed if previously imposed.|
|addSupportingAttribute|CdmTypeAttributeDefinition|The supplied attribute definition that will be added to the entity.|
|cardinality|string|If 'one', then there is a single instance of the attribute or entity used. 'many' indicates multiple instances, and the 'expansion' properties will describe the array enumeration to use when needed.|
|renameFormat|string|The format specifier for generated attribute names. May contain a single occurence of ('\{a} or 'A'), ('\{m}' or '\{M}') and '\{o}' for the base (a/A)ttribute name, any (m/M)ember attributes from entities, and array (o)rdinal. For example, '\{a}\{o}.\{m}' could produce 'address2.city', and '\{a}\{o}' gives 'city1'. Using '\{A}' or '\{M}' will uppercase the first letter of the name portion.|
|expansion|Expansion|The parameters that control array expansion if inline repeating of attributes is needed.|
|entityByReference|CdmAttributeResolutionGuidance_EntityByReference|The parameters that control the use of foreign keys to reference entity instances instead of embedding the entity in a nested way.|
|selectsSubAttribute|CdmAttributeResolutionGuidance_SelectsSubAttribute|Indicates that this attribute selects either 'one' or 'all' of the sub-attributes from an entity. If the 'structured' directive is set, this trait causes resolved attributes to end up in groups rather than a flattened list.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**makeEntityByReference()**|Returns a new CdmAttributeResolutionGuidance_EntityByReference object.|CdmAttributeResolutionGuidance_EntityByReference|
|**makeSelectsSubAttribute()**|Returns a new CdmAttributeResolutionGuidance_SelectsSubAttribute object.|CdmAttributeResolutionGuidance_SelectsSubAttribute|
|**Copy(ResolveOptions)**|See *CdmObject.Copy(...)*.|CdmObject|
|**Validate()**|See *CdmObject.Validate()*.|bool|
 
## Nested Classes
[Expansion](attributeresolutionguidance.md#expansion)<br/>
[CdmAttributeResolutionGuidance_EntityByReference](attributeresolutionguidance.md#CdmAttributeResolutionGuidance_EntityByReference)<br/>
[CdmAttributeResolutionGuidance_SelectsSubAttribute](attributeresolutionguidance.md#CdmAttributeResolutionGuidance_SelectsSubAttribute)<br/>

## Expansion
The parameters that control array expansion if inline repeating of attributes is needed.

### Properties
|Name|Type|Description|
|---|---|---|
|startingOrdinal|int?|TODO|
|maximumExpansion|int?|The maximum number of times that the attribute pattern should be repeated.|
|countAttribute|CdmTypeAttributeDefinition|The supplied attribute definition is added to the entity to represent the total number of instances found in the data.|

## CdmAttributeResolutionGuidance_EntityByReference
The parameters that control the use of foreign keys to reference entity instances instead of embedding the entity in a nested way.

### Properties
|Name|Type|Description|
|---|---|---|
|allowReference|bool?|Denotes, explicitly, whether a reference is allowed.
|alwaysIncludeForeignKey|bool?|If true, a foreign key attribute will be added to the entity even when the entity attribute is embedded in a nested way.|
|referenceOnlyAfterDepth|int?|After the given depth of non-reference nesting using entity attributes, the 'referenceOnly' directive will be imposed.|
|foreignKeyAttribute|CdmTypeAttributeDefinition|The supplied attribute definition is added to the entity to hold a foreign key value for the referenced entity.|

## CdmAttributeResolutionGuidance_SelectsSubAttribute
Indicates that this attribute selects either 'one' or 'all' of the sub-attributes from an entity. If the 'structured' directive is set, this trait causes resolved attributes to end up in groups rather than a flattened list.

### Properties
|Name|Type|Description|
|---|---|---|
|selects|string|Indicates either 'one' or 'all' sub-attributes selected.|
|selectedTypeAttribute|CdmTypeAttributeDefinition|he supplied attribute definition is added to the entity to hold a description of the single attribute that was selected from the sub-entity when selects is 'one'.|
|selectsSomeTakeNames|List\<string>|TODO|
|selectsSomeAvoidNames|List\<string>|TODO|

