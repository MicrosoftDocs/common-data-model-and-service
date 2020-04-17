---
title: smmOutlookRecurrencePattern - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# smmOutlookRecurrencePattern

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/SalesAndMarketing/Main/smmOutlookRecurrencePattern.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[smmOutlookRecurrencePattern/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[DayofMonth](#DayofMonth)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[DaysOfWeek](#DaysOfWeek)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[DurationMinutes](#DurationMinutes)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[Instance](#Instance)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[Interval](#Interval)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[MasterOutlookEntryID](#MasterOutlookEntryID)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[MonthOfYearId](#MonthOfYearId)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[NoEndDate](#NoEndDate)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[PatternEndDateTime](#PatternEndDateTime)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[PatternStartDateTime](#PatternStartDateTime)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[RecurrenceType](#RecurrenceType)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[DataAreaId](#DataAreaId)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="smmOutlookRecurrencePattern.md" target="_blank">Main/smmOutlookRecurrencePattern</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[smmOutlookRecurrencePattern/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DayofMonth name="DayofMonth">DayofMonth</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DayofMonth attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DaysOfWeek name="DaysOfWeek">DaysOfWeek</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysOfWeek attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DurationMinutes name="DurationMinutes">DurationMinutes</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DurationMinutes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Instance name="Instance">Instance</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Instance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Interval name="Interval">Interval</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Interval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MasterOutlookEntryID name="MasterOutlookEntryID">MasterOutlookEntryID</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MasterOutlookEntryID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MonthOfYearId name="MonthOfYearId">MonthOfYearId</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthOfYearId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NoEndDate name="NoEndDate">NoEndDate</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NoEndDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PatternEndDateTime name="PatternEndDateTime">PatternEndDateTime</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PatternEndDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PatternStartDateTime name="PatternStartDateTime">PatternStartDateTime</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PatternStartDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#RecurrenceType name="RecurrenceType">RecurrenceType</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecurrenceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/smmOutlookRecurrencePattern (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
