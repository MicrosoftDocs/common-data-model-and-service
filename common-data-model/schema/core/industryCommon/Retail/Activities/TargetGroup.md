---
title: TargetGroup in Activities - Common Data Model | Microsoft Docs
description: Target groups are used to group outlets into segments
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 3/6/2024
ms.author: anbichse
---

# Target group in Activities(TargetGroup)

Target groups are used to group outlets into segments  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/Retail\Activities/TargetGroup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TargetGroup/(resolvedAttributes)/targetgroupId](#targetgroupId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/Retail/Activities/TargetGroup.cdm.json<br>/TargetGroup/hasAttributes<br>/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target groups are used to group outlets into segments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msrex_targetgroup"</td><td>string</td><td></td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[targetgroupId](#targetgroupId)|Unique identifier for entity instances|<a href="TargetGroup.md" target="_blank">Retail\Activities/TargetGroup</a>|

### <a href=#targetgroupId name="targetgroupId">targetgroupId</a>

Unique identifier for entity instances  
First included in: Retail\\Activities/TargetGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target group</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>msrex_targetgroupid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the targetgroupId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **means.identity.entityId**  
  **is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TargetGroup/(resolvedAttributes)/targetgroupId](#targetgroupId)</td><td>attribute</td><td></td></tr></table>

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msrex_targetgroupid"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"1"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>
