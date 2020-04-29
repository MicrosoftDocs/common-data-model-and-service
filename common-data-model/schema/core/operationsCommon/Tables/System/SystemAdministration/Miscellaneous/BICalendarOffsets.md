---
title: BICalendarOffsets - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# BICalendarOffsets

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BICalendarOffsets.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BICalendarOffsets/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BICalendarOffsets.md" target="_blank">Miscellaneous/BICalendarOffsets</a>|
|[BIDateDimension](#BIDateDimension)||<a href="BICalendarOffsets.md" target="_blank">Miscellaneous/BICalendarOffsets</a>|
|[CurrentMonth](#CurrentMonth)||<a href="BICalendarOffsets.md" target="_blank">Miscellaneous/BICalendarOffsets</a>|
|[OffsetMonth](#OffsetMonth)||<a href="BICalendarOffsets.md" target="_blank">Miscellaneous/BICalendarOffsets</a>|
|[MonthOffset](#MonthOffset)||<a href="BICalendarOffsets.md" target="_blank">Miscellaneous/BICalendarOffsets</a>|
|[QuarterOffset](#QuarterOffset)||<a href="BICalendarOffsets.md" target="_blank">Miscellaneous/BICalendarOffsets</a>|
|[YearOffset](#YearOffset)||<a href="BICalendarOffsets.md" target="_blank">Miscellaneous/BICalendarOffsets</a>|
|[Relationship_BIDateDimensionRelationshipId](#Relationship_BIDateDimensionRelationshipId)||<a href="BICalendarOffsets.md" target="_blank">Miscellaneous/BICalendarOffsets</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/BICalendarOffsets (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BICalendarOffsets/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BIDateDimension name="BIDateDimension">BIDateDimension</a>

First included in: Miscellaneous/BICalendarOffsets (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BIDateDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrentMonth name="CurrentMonth">CurrentMonth</a>

First included in: Miscellaneous/BICalendarOffsets (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentMonth attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#OffsetMonth name="OffsetMonth">OffsetMonth</a>

First included in: Miscellaneous/BICalendarOffsets (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetMonth attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#MonthOffset name="MonthOffset">MonthOffset</a>

First included in: Miscellaneous/BICalendarOffsets (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthOffset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#QuarterOffset name="QuarterOffset">QuarterOffset</a>

First included in: Miscellaneous/BICalendarOffsets (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuarterOffset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#YearOffset name="YearOffset">YearOffset</a>

First included in: Miscellaneous/BICalendarOffsets (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearOffset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_BIDateDimensionRelationshipId name="Relationship_BIDateDimensionRelationshipId">Relationship_BIDateDimensionRelationshipId</a>

First included in: Miscellaneous/BICalendarOffsets (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BIDateDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/BIDateDimension.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/BIDateDimension.cdm.json/BIDateDimension</a></td><td><a href="../Main/BIDateDimension.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
