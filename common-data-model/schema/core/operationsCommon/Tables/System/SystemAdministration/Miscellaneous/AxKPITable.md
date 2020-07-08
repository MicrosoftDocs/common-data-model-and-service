---
title: AxKPITable in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# AxKPITable in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/AxKPITable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AxKPITable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[AllowCrossCompany](#AllowCrossCompany)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[BadThreshold](#BadThreshold)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[DrillThroughLinkType](#DrillThroughLinkType)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[ExternalURL](#ExternalURL)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[GoodThreshold](#GoodThreshold)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[HelpText](#HelpText)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[Label](#Label)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[Measurement](#Measurement)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[MenuItemName](#MenuItemName)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[MenuItemType](#MenuItemType)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[Name](#Name)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[OwnerId](#OwnerId)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[ParentKPIId](#ParentKPIId)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[ScoringPattern](#ScoringPattern)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[ShowGoal](#ShowGoal)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[ShowStatus](#ShowStatus)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[ShowTrend](#ShowTrend)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[Tags](#Tags)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[ThresholdShortLabel](#ThresholdShortLabel)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[ThresholdType](#ThresholdType)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[AxKPIValueId](#AxKPIValueId)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[AxKPIGoalId](#AxKPIGoalId)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[Relationship_AxKPIValueRelationshipId](#Relationship_AxKPIValueRelationshipId)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[Relationship_AxKPIGoalRelationshipId](#Relationship_AxKPIGoalRelationshipId)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|
|[Relationship_AxKPITrendsRelationshipId](#Relationship_AxKPITrendsRelationshipId)||<a href="AxKPITable.md" target="_blank">Miscellaneous/AxKPITable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AxKPITable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AllowCrossCompany name="AllowCrossCompany">AllowCrossCompany</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowCrossCompany attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BadThreshold name="BadThreshold">BadThreshold</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BadThreshold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DrillThroughLinkType name="DrillThroughLinkType">DrillThroughLinkType</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DrillThroughLinkType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExternalURL name="ExternalURL">ExternalURL</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GoodThreshold name="GoodThreshold">GoodThreshold</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GoodThreshold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#HelpText name="HelpText">HelpText</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HelpText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Label name="Label">Label</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Label attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Measurement name="Measurement">Measurement</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Measurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MenuItemName name="MenuItemName">MenuItemName</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MenuItemType name="MenuItemType">MenuItemType</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OwnerId name="OwnerId">OwnerId</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwnerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentKPIId name="ParentKPIId">ParentKPIId</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentKPIId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ScoringPattern name="ScoringPattern">ScoringPattern</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScoringPattern attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGoal name="ShowGoal">ShowGoal</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGoal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowStatus name="ShowStatus">ShowStatus</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowTrend name="ShowTrend">ShowTrend</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTrend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Tags name="Tags">Tags</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tags attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdShortLabel name="ThresholdShortLabel">ThresholdShortLabel</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdShortLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdType name="ThresholdType">ThresholdType</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AxKPIValueId name="AxKPIValueId">AxKPIValueId</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AxKPIValueId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AxKPIGoalId name="AxKPIGoalId">AxKPIGoalId</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AxKPIGoalId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_AxKPIValueRelationshipId name="Relationship_AxKPIValueRelationshipId">Relationship_AxKPIValueRelationshipId</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AxKPIValueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AxKPIValueTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/AxKPIValueTable.cdm.json/AxKPIValueTable</a></td><td><a href="AxKPIValueTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AxKPIGoalRelationshipId name="Relationship_AxKPIGoalRelationshipId">Relationship_AxKPIGoalRelationshipId</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AxKPIGoalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AxKPIGoalTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/AxKPIGoalTable.cdm.json/AxKPIGoalTable</a></td><td><a href="AxKPIGoalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AxKPITrendsRelationshipId name="Relationship_AxKPITrendsRelationshipId">Relationship_AxKPITrendsRelationshipId</a>

First included in: Miscellaneous/AxKPITable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AxKPITrendsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AxKPITrendTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/AxKPITrendTable.cdm.json/AxKPITrendTable</a></td><td><a href="AxKPITrendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
