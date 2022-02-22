---
title: smmActivitiesEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Activities in SalesAndMarketing(smmActivitiesEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/smmActivitiesEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activities</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ActivityNumber](#ActivityNumber)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[ActivityStatus](#ActivityStatus)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[ActualWork](#ActualWork)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[AllDay](#AllDay)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[BillingInformation](#BillingInformation)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Category](#Category)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Closed](#Closed)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[ClosedBy](#ClosedBy)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[ClosedByPersonnelNumber](#ClosedByPersonnelNumber)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[CompletedPercentage](#CompletedPercentage)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[DateAndTimeClosed](#DateAndTimeClosed)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Dispatched](#Dispatched)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[EndDateTime](#EndDateTime)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[KeepSynchronized](#KeepSynchronized)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[LastDateTimeEdited](#LastDateTimeEdited)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Location](#Location)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[MasterAppointment](#MasterAppointment)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Mileage](#Mileage)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Modified](#Modified)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Notes](#Notes)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[OriginalStartDate](#OriginalStartDate)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[OutlookCategories](#OutlookCategories)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[OutlookEntryId](#OutlookEntryId)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[OutlookResources](#OutlookResources)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[OutlookResponseRequested](#OutlookResponseRequested)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[OutlookSharedObjectId](#OutlookSharedObjectId)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[OutlookText](#OutlookText)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[PhaseId](#PhaseId)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[PlanId](#PlanId)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Priority](#Priority)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Purpose](#Purpose)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[RecurrenceState](#RecurrenceState)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Reminder](#Reminder)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[ReminderDate](#ReminderDate)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[ReminderMinutes](#ReminderMinutes)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Responsible](#Responsible)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[ResponsibleWorkerPersonnelNumber](#ResponsibleWorkerPersonnelNumber)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[ResponsibilityId](#ResponsibilityId)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Role](#Role)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Sensitivity](#Sensitivity)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[ShowTimeAs](#ShowTimeAs)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[SourceApplication](#SourceApplication)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[StartDateTime](#StartDateTime)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[TeamTask](#TeamTask)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Template](#Template)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[TotalWork](#TotalWork)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[TypeId](#TypeId)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="smmActivitiesEntity.md" target="_blank">SalesAndMarketing/smmActivitiesEntity</a>|

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityStatus name="ActivityStatus">ActivityStatus</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualWork name="ActualWork">ActualWork</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllDay name="AllDay">AllDay</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingInformation name="BillingInformation">BillingInformation</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Category attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Closed name="Closed">Closed</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Closed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedBy name="ClosedBy">ClosedBy</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedByPersonnelNumber name="ClosedByPersonnelNumber">ClosedByPersonnelNumber</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedByPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompletedPercentage name="CompletedPercentage">CompletedPercentage</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompletedPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateAndTimeClosed name="DateAndTimeClosed">DateAndTimeClosed</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateAndTimeClosed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dispatched name="Dispatched">Dispatched</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dispatched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDateTime name="EndDateTime">EndDateTime</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeepSynchronized name="KeepSynchronized">KeepSynchronized</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeepSynchronized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastDateTimeEdited name="LastDateTimeEdited">LastDateTimeEdited</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last date/time edited</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastDateTimeEdited attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last date/time edited</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MasterAppointment name="MasterAppointment">MasterAppointment</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MasterAppointment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Mileage name="Mileage">Mileage</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Mileage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Modified name="Modified">Modified</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Modified attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalStartDate name="OriginalStartDate">OriginalStartDate</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookCategories name="OutlookCategories">OutlookCategories</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookCategories attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookEntryId name="OutlookEntryId">OutlookEntryId</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookEntryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookResources name="OutlookResources">OutlookResources</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookResources attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookResponseRequested name="OutlookResponseRequested">OutlookResponseRequested</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookResponseRequested attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookSharedObjectId name="OutlookSharedObjectId">OutlookSharedObjectId</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookSharedObjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookText name="OutlookText">OutlookText</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhaseId name="PhaseId">PhaseId</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlanId name="PlanId">PlanId</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Priority name="Priority">Priority</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Priority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purpose name="Purpose">Purpose</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecurrenceState name="RecurrenceState">RecurrenceState</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecurrenceState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reminder name="Reminder">Reminder</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reminder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReminderDate name="ReminderDate">ReminderDate</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReminderDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReminderMinutes name="ReminderMinutes">ReminderMinutes</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReminderMinutes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Responsible name="Responsible">Responsible</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Responsible attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsibleWorkerPersonnelNumber name="ResponsibleWorkerPersonnelNumber">ResponsibleWorkerPersonnelNumber</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsibleWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsibilityId name="ResponsibilityId">ResponsibilityId</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsibilityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Role name="Role">Role</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Role attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sensitivity name="Sensitivity">Sensitivity</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sensitivity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowTimeAs name="ShowTimeAs">ShowTimeAs</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTimeAs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceApplication name="SourceApplication">SourceApplication</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceApplication attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDateTime name="StartDateTime">StartDateTime</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TeamTask name="TeamTask">TeamTask</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TeamTask attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Template name="Template">Template</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Template attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalWork name="TotalWork">TotalWork</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeId name="TypeId">TypeId</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/smmActivitiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
