---
title: SysTaskRecorderFrameworkIndustryMap - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Framework industry map

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Main/SysTaskRecorderFrameworkIndustryMap.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysTaskRecorderFrameworkIndustryMap/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Framework industry map</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysTaskRecorderFrameworkIndustryMap.md" target="_blank">Main/SysTaskRecorderFrameworkIndustryMap</a>|
|[Framework](#Framework)||<a href="SysTaskRecorderFrameworkIndustryMap.md" target="_blank">Main/SysTaskRecorderFrameworkIndustryMap</a>|
|[GenerateProcessData](#GenerateProcessData)||<a href="SysTaskRecorderFrameworkIndustryMap.md" target="_blank">Main/SysTaskRecorderFrameworkIndustryMap</a>|
|[Industry](#Industry)||<a href="SysTaskRecorderFrameworkIndustryMap.md" target="_blank">Main/SysTaskRecorderFrameworkIndustryMap</a>|
|[Relationship_SysTaskRecorderFrameworkRelationshipId](#Relationship_SysTaskRecorderFrameworkRelationshipId)||<a href="SysTaskRecorderFrameworkIndustryMap.md" target="_blank">Main/SysTaskRecorderFrameworkIndustryMap</a>|
|[Relationship_SysTaskRecorderIndustryRelationshipId](#Relationship_SysTaskRecorderIndustryRelationshipId)||<a href="SysTaskRecorderFrameworkIndustryMap.md" target="_blank">Main/SysTaskRecorderFrameworkIndustryMap</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/SysTaskRecorderFrameworkIndustryMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysTaskRecorderFrameworkIndustryMap/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Framework name="Framework">Framework</a>

First included in: Main/SysTaskRecorderFrameworkIndustryMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Framework attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GenerateProcessData name="GenerateProcessData">GenerateProcessData</a>

First included in: Main/SysTaskRecorderFrameworkIndustryMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generate process data</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerateProcessData attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generate process data</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Industry name="Industry">Industry</a>

First included in: Main/SysTaskRecorderFrameworkIndustryMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Industry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_SysTaskRecorderFrameworkRelationshipId name="Relationship_SysTaskRecorderFrameworkRelationshipId">Relationship_SysTaskRecorderFrameworkRelationshipId</a>

First included in: Main/SysTaskRecorderFrameworkIndustryMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysTaskRecorderFrameworkRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysTaskRecorderFramework.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysTaskRecorderFramework.cdm.json/SysTaskRecorderFramework</a></td><td><a href="SysTaskRecorderFramework.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysTaskRecorderIndustryRelationshipId name="Relationship_SysTaskRecorderIndustryRelationshipId">Relationship_SysTaskRecorderIndustryRelationshipId</a>

First included in: Main/SysTaskRecorderFrameworkIndustryMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysTaskRecorderIndustryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysTaskRecorderIndustry.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysTaskRecorderIndustry.cdm.json/SysTaskRecorderIndustry</a></td><td><a href="SysTaskRecorderIndustry.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
