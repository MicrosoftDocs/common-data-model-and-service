---
title: PSAActivitySetup - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# PSAActivitySetup

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/Project/Main/PSAActivitySetup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PSAActivitySetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[Activity](#Activity)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[ActivityDuration](#ActivityDuration)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[ActivityGroup](#ActivityGroup)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[ActivityNumber](#ActivityNumber)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[CalendarId](#CalendarId)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[CategoryDefault](#CategoryDefault)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[CostAtComplete](#CostAtComplete)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[DurationToEnd](#DurationToEnd)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[Effort](#Effort)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[EffortAtComplete](#EffortAtComplete)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[ElementNodeType](#ElementNodeType)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[ElementNumber](#ElementNumber)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[HierarchyId](#HierarchyId)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[IgnoreCalendar](#IgnoreCalendar)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[IsTemplate](#IsTemplate)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[Level](#Level)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[LineNum](#LineNum)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[Mandatory](#Mandatory)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[MileStone](#MileStone)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[NumberOfResources](#NumberOfResources)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[ParentElementNumber](#ParentElementNumber)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[PSAHierarchyLevelType](#PSAHierarchyLevelType)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[PSALevelDescription](#PSALevelDescription)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[PSALevelName](#PSALevelName)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[PSANameLink](#PSANameLink)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[PSASchedEnd](#PSASchedEnd)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[PSASchedFromTime](#PSASchedFromTime)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[PSASchedStart](#PSASchedStart)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[PSASchedToTime](#PSASchedToTime)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[PSASubproject](#PSASubproject)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[ReferenceElementNumber](#ReferenceElementNumber)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[SiblingNumber](#SiblingNumber)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[Txt](#Txt)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[ResourceCategory](#ResourceCategory)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[DataAreaId](#DataAreaId)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[Relationship_ProjCategoryRelationshipId](#Relationship_ProjCategoryRelationshipId)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[Relationship_WorkCalendarTableRelationshipId](#Relationship_WorkCalendarTableRelationshipId)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[Relationship_PSASchedRoleRelationshipId](#Relationship_PSASchedRoleRelationshipId)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PSAActivitySetup.md" target="_blank">Main/PSAActivitySetup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PSAActivitySetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Activity name="Activity">Activity</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Activity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityDuration name="ActivityDuration">ActivityDuration</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityDuration attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ActivityGroup name="ActivityGroup">ActivityGroup</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarId name="CalendarId">CalendarId</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryDefault name="CategoryDefault">CategoryDefault</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAtComplete name="CostAtComplete">CostAtComplete</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAtComplete attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DurationToEnd name="DurationToEnd">DurationToEnd</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DurationToEnd attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Effort name="Effort">Effort</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Effort attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EffortAtComplete name="EffortAtComplete">EffortAtComplete</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffortAtComplete attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ElementNodeType name="ElementNodeType">ElementNodeType</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementNodeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ElementNumber name="ElementNumber">ElementNumber</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyId name="HierarchyId">HierarchyId</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IgnoreCalendar name="IgnoreCalendar">IgnoreCalendar</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IgnoreCalendar attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsTemplate name="IsTemplate">IsTemplate</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTemplate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Level name="Level">Level</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Mandatory name="Mandatory">Mandatory</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Mandatory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MileStone name="MileStone">MileStone</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MileStone attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NumberOfResources name="NumberOfResources">NumberOfResources</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfResources attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ParentElementNumber name="ParentElementNumber">ParentElementNumber</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentElementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSAHierarchyLevelType name="PSAHierarchyLevelType">PSAHierarchyLevelType</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSAHierarchyLevelType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSALevelDescription name="PSALevelDescription">PSALevelDescription</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSALevelDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSALevelName name="PSALevelName">PSALevelName</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSALevelName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSANameLink name="PSANameLink">PSANameLink</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSANameLink attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSASchedEnd name="PSASchedEnd">PSASchedEnd</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSASchedEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PSASchedFromTime name="PSASchedFromTime">PSASchedFromTime</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSASchedFromTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.readOnly**  
**is.dataFormat.time**  
</details>

### <a href=#PSASchedStart name="PSASchedStart">PSASchedStart</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSASchedStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PSASchedToTime name="PSASchedToTime">PSASchedToTime</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSASchedToTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.readOnly**  
**is.dataFormat.time**  
</details>

### <a href=#PSASubproject name="PSASubproject">PSASubproject</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSASubproject attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReferenceElementNumber name="ReferenceElementNumber">ReferenceElementNumber</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceElementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiblingNumber name="SiblingNumber">SiblingNumber</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiblingNumber attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Txt name="Txt">Txt</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCategory name="ResourceCategory">ResourceCategory</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategoryRelationshipId name="Relationship_ProjCategoryRelationshipId">Relationship_ProjCategoryRelationshipId</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProjectManagementAndAccounting/Group/ProjCategory.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="../../ProjectManagementAndAccounting/Group/ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkCalendarTableRelationshipId name="Relationship_WorkCalendarTableRelationshipId">Relationship_WorkCalendarTableRelationshipId</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkCalendarTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductionControl/Group/WorkCalendarTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/WorkCalendarTable.cdm.json/WorkCalendarTable</a></td><td><a href="../../../SupplyChain/ProductionControl/Group/WorkCalendarTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PSASchedRoleRelationshipId name="Relationship_PSASchedRoleRelationshipId">Relationship_PSASchedRoleRelationshipId</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PSASchedRoleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/PSASchedRole.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/Project/Miscellaneous/PSASchedRole.cdm.json/PSASchedRole</a></td><td><a href="../Miscellaneous/PSASchedRole.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/PSAActivitySetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
