---
title: Attribute Resolution Guidance | Microsoft Docs
description: API reference for CdmAttributeResolutionGuidance.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Attribute Resolution Guidance

An attribute resolution guidance properties that help with the resolution process of [entities](entity.md), attributes, and other resolvable Common Data Model concepts.

```
public class CdmAttributeResolutionGuidance extends CdmObjectSimple
```
## Constructors
|Name|Description|
|---|---|
|**CdmAttributeResolutionGuidance(CdmCorpusContext)**<br/>*ctx*: The corpus context.|Initializes a new instance of the [CdmAttributeResolutionGuidance](attributeresolutionguidance.md) class.|

## Properties
|Name|Type|Description|
|---|---|---|
|removeAttribute|bool?|If true, this attribute definition will be removed from the entity's final resolved attribute list.|
|imposedDirectives|List\<string>|A list of strings, one for each 'directive' that should always be imposed for this attribute definition.|
|removedDirectives|List\<string>|A list of strings, one for each 'directive' that should be removed if previously imposed.|
|addSupportingAttribute|[CdmTypeAttributeDefinition](typeattribute.md)|TODO|
|cardinality|string|If set to 'one', then there is a single instance of the attribute or entity used. If set to 'many', then there are multiple instances of the attribute/entity used, in which case the 'expansion' properties will describe the array enumeration to use if needed.|
|renameFormat|string|The format specifier for generated attribute names. May contain a single occurence of ('\{a}' or '\{A}'), ('\{m}' or '\{M}') and '\{o}' for the base (a/A)ttribute name, any (m/M)ember attributes from entities, and array (o)rdinal. For example, '\{a}\{o}.\{m}' could produce 'address2.city', and '\{a}\{o}' gives 'city1'. Using '\{A}' or '\{M}' will uppercase the first letter of the name portion.|
|expansion|[Expansion](attributeresolutionguidance.md#expansion)|The parameters that control array expansion if inline repeating of attributes is needed.|
|entityByReference|[CdmAttributeResolutionGuidance_EntityByReference](attributeresolutionguidance.md#cdmattributeresolutionguidance_entitybyreference)|The parameters that control the use of foreign keys to reference entity instances instead of embedding the entity in a nested way.|
|selectsSubAttribute|[CdmAttributeResolutionGuidance_SelectsSubAttribute](attributeresolutionguidance.md#cdmattributeresolutionguidance_selectssubattribute)|Indicates that this attribute selects either 'one' or 'all' of the sub-attributes from an entity. If the 'structured' directive is set, this trait causes resolved attributes to end up in groups rather than a flattened list.|

## Methods
|Name|Description|Return Type|
|---|---|---|
|**makeExpansion()**|Returns a new [Expansion](attributeresolutionguidance.md#expansion) object.|[Expansion](attributeresolutionguidance.md#expansion)|
|**makeEntityByReference()**|Returns a new [CdmAttributeResolutionGuidance_EntityByReference](attributeresolutionguidance.md#cdmattributeresolutionguidance_entitybyreference) object.|[CdmAttributeResolutionGuidance_EntityByReference](attributeresolutionguidance.md#cdmattributeresolutionguidance_entitybyreference)|
|**makeSelectsSubAttribute()**|Returns a new [CdmAttributeResolutionGuidance_SelectsSubAttribute](attributeresolutionguidance.md#cdmattributeresolutionguidance_selectssubattribute) object.|[CdmAttributeResolutionGuidance_SelectsSubAttribute](attributeresolutionguidance.md#cdmattributeresolutionguidance_selectssubattribute)|
|**Copy([ResolveOptions](../utilities/resolveoptions.md))**|See [CdmObject.Copy(...)](cdmobject.md#methods).|[CdmObject](cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](cdmobject.md#methods).|bool|
 
## Nested Classes
[Expansion](attributeresolutionguidance.md#expansion)<br/>
[CdmAttributeResolutionGuidance_EntityByReference](attributeresolutionguidance.md#cdmattributeresolutionguidance_entitybyreference)<br/>
[CdmAttributeResolutionGuidance_SelectsSubAttribute](attributeresolutionguidance.md#cdmattributeresolutionguidance_selectssubattribute)<br/>

## Expansion
The parameters that control array expansion if inline repeating of attributes is needed.

### Properties
|Name|Type|Description|
|---|---|---|
|startingOrdinal|int?|TODO|
|maximumExpansion|int?|The maximum number of times that the attribute pattern should be repeated.|
|countAttribute|[CdmTypeAttributeDefinition](typeattribute.md)|This attribute definition is added to the entity to represent the total number of instances found in the data.|

## CdmAttributeResolutionGuidance_EntityByReference
The parameters that control the use of foreign keys to reference entity instances instead of embedding the entity in a nested way.

### Properties
|Name|Type|Description|
|---|---|---|
|allowReference|bool?|Denotes whether a reference to an entity is allowed through the use of a foreign key to the entity. By default, this property is set to false and entities are embedded instead.|
|alwaysIncludeForeignKey|bool?|If true, a foreign key attribute will be added to the entity even when the entity attribute is embedded in a nested way.|
|referenceOnlyAfterDepth|int?|After the given depth of non-reference nesting using entity attributes, the 'referenceOnly' directive will be imposed.|
|foreignKeyAttribute|[CdmTypeAttributeDefinition](typeattribute.md)|This attribute definition is added to the entity to hold a foreign key value for the referenced entity.|

## CdmAttributeResolutionGuidance_SelectsSubAttribute
Indicates that this attribute selects either 'one' or 'all' of the sub-attributes from an entity. If the 'structured' directive is set, this trait causes resolved attributes to end up in groups rather than a flattened list.

### Properties
|Name|Type|Description|
|---|---|---|
|selects|string|Indicates how many sub-attributes are selected (either 'one' or 'all').|
|selectedTypeAttribute|[CdmTypeAttributeDefinition](typeattribute.md)|This attribute definition is added to the entity to hold a description of the single attribute that was selected from the sub-entity when selects is set to 'one'.|
|selectsSomeTakeNames|List\<string>|The list of sub-attributes from an entity that should be added.|
|selectsSomeAvoidNames|List\<string>|The list of sub-attributes from an entity that should not be added.|

