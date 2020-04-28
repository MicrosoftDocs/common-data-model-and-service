---
title: HcmPositionV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Positions V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmPositionV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Positions V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PositionId](#PositionId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[AvailableForAssignment](#AvailableForAssignment)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[CompensationRegion](#CompensationRegion)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Department](#Department)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Description](#Description)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[FullTimeEquivalent](#FullTimeEquivalent)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Job](#Job)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[PositionType](#PositionType)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Title](#Title)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[DetailEffective](#DetailEffective)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[DetailExpiration](#DetailExpiration)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[DepartmentNumber](#DepartmentNumber)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[CompensationRegionId](#CompensationRegionId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[JobId](#JobId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[PositionTypeId](#PositionTypeId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[TitleId](#TitleId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Activation](#Activation)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Retirement](#Retirement)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[WorkerAssignmentReasonCode](#WorkerAssignmentReasonCode)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[WorkerAssignmentStart](#WorkerAssignmentStart)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[WorkerAssignmentEnd](#WorkerAssignmentEnd)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Worker](#Worker)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[WorkerPersonnelNumber](#WorkerPersonnelNumber)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[WorkerAssignmentReasonCodeId](#WorkerAssignmentReasonCodeId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[WorkerName](#WorkerName)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[LegalEntity](#LegalEntity)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[PaidByLegalEntity](#PaidByLegalEntity)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[PayCycle](#PayCycle)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[PayCycleId](#PayCycleId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[AnnualRegularHours](#AnnualRegularHours)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[PayrollDetailEffective](#PayrollDetailEffective)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[PayrollDetailExpiration](#PayrollDetailExpiration)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[IsSalaryGenerated](#IsSalaryGenerated)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[DefaultEarningCodeId](#DefaultEarningCodeId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[InsuranceBenefit](#InsuranceBenefit)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[AreEarningsGeneratedFromSchedule](#AreEarningsGeneratedFromSchedule)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[PaidBy](#PaidBy)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[PayPeriodOvertimeHours](#PayPeriodOvertimeHours)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Schedule](#Schedule)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[ScheduleLegalEntity](#ScheduleLegalEntity)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[BenefitId](#BenefitId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Relationship_JobRelationshipId](#Relationship_JobRelationshipId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Relationship_TitleRelationshipId](#Relationship_TitleRelationshipId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Relationship_PositionTypeRelationshipId](#Relationship_PositionTypeRelationshipId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Relationship_DepartmentRelationshipId](#Relationship_DepartmentRelationshipId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Relationship_PayrollPayCycleRelationshipId](#Relationship_PayrollPayCycleRelationshipId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|
|[Relationship_WorkCalendarRelationshipId](#Relationship_WorkCalendarRelationshipId)||<a href="HcmPositionV2Entity.md" target="_blank">HRM/HcmPositionV2Entity</a>|

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailableForAssignment name="AvailableForAssignment">AvailableForAssignment</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailableForAssignment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompensationRegion name="CompensationRegion">CompensationRegion</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Department name="Department">Department</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Department attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FullTimeEquivalent name="FullTimeEquivalent">FullTimeEquivalent</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullTimeEquivalent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Job name="Job">Job</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Job attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionType name="PositionType">PositionType</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Title name="Title">Title</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Title attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DetailEffective name="DetailEffective">DetailEffective</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DetailEffective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DetailExpiration name="DetailExpiration">DetailExpiration</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DetailExpiration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepartmentNumber name="DepartmentNumber">DepartmentNumber</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Department number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepartmentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Department number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompensationRegionId name="CompensationRegionId">CompensationRegionId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Compensation region</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Compensation region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobId name="JobId">JobId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionTypeId name="PositionTypeId">PositionTypeId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TitleId name="TitleId">TitleId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TitleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Activation name="Activation">Activation</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Activation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Retirement name="Retirement">Retirement</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Retirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerAssignmentReasonCode name="WorkerAssignmentReasonCode">WorkerAssignmentReasonCode</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerAssignmentReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerAssignmentStart name="WorkerAssignmentStart">WorkerAssignmentStart</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerAssignmentStart attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerAssignmentEnd name="WorkerAssignmentEnd">WorkerAssignmentEnd</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerAssignmentEnd attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerPersonnelNumber name="WorkerPersonnelNumber">WorkerPersonnelNumber</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerAssignmentReasonCodeId name="WorkerAssignmentReasonCodeId">WorkerAssignmentReasonCodeId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerAssignmentReasonCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerName name="WorkerName">WorkerName</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Worker name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Worker name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaidByLegalEntity name="PaidByLegalEntity">PaidByLegalEntity</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaidByLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayCycle name="PayCycle">PayCycle</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayCycle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayCycleId name="PayCycleId">PayCycleId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayCycleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnnualRegularHours name="AnnualRegularHours">AnnualRegularHours</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnnualRegularHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollDetailEffective name="PayrollDetailEffective">PayrollDetailEffective</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollDetailEffective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollDetailExpiration name="PayrollDetailExpiration">PayrollDetailExpiration</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollDetailExpiration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalaryGenerated name="IsSalaryGenerated">IsSalaryGenerated</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalaryGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultEarningCodeId name="DefaultEarningCodeId">DefaultEarningCodeId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default earning code</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultEarningCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default earning code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuranceBenefit name="InsuranceBenefit">InsuranceBenefit</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceBenefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreEarningsGeneratedFromSchedule name="AreEarningsGeneratedFromSchedule">AreEarningsGeneratedFromSchedule</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreEarningsGeneratedFromSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaidBy name="PaidBy">PaidBy</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaidBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayPeriodOvertimeHours name="PayPeriodOvertimeHours">PayPeriodOvertimeHours</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayPeriodOvertimeHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Schedule name="Schedule">Schedule</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Schedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduleLegalEntity name="ScheduleLegalEntity">ScheduleLegalEntity</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduleLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JobRelationshipId name="Relationship_JobRelationshipId">Relationship_JobRelationshipId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JobRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TitleRelationshipId name="Relationship_TitleRelationshipId">Relationship_TitleRelationshipId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TitleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PositionTypeRelationshipId name="Relationship_PositionTypeRelationshipId">Relationship_PositionTypeRelationshipId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PositionTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DepartmentRelationshipId name="Relationship_DepartmentRelationshipId">Relationship_DepartmentRelationshipId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepartmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkerRelationshipId name="Relationship_WorkerRelationshipId">Relationship_WorkerRelationshipId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollPayCycleRelationshipId name="Relationship_PayrollPayCycleRelationshipId">Relationship_PayrollPayCycleRelationshipId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollPayCycleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkCalendarRelationshipId name="Relationship_WorkCalendarRelationshipId">Relationship_WorkCalendarRelationshipId</a>

First included in: HRM/HcmPositionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkCalendarRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
