---
title: HcmInjuryIncidentEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# HcmInjuryIncidentEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/HumanResources/HRM/HcmInjuryIncidentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ActionToBeTaken](#ActionToBeTaken)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[BodyPart](#BodyPart)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[BodyPartId](#BodyPartId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[CaseClosedDate](#CaseClosedDate)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[CaseDescription](#CaseDescription)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[CaseNumber](#CaseNumber)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[CaseOpenedDate](#CaseOpenedDate)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[CaseStatus](#CaseStatus)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[CauseOfIncident](#CauseOfIncident)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[DaysAwayFromWork](#DaysAwayFromWork)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[DaysOnJobTransferOrRestriction](#DaysOnJobTransferOrRestriction)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[ExpectedDaysAwayFromWork](#ExpectedDaysAwayFromWork)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[HumanResourcesContact](#HumanResourcesContact)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[HumanResourcesContactId](#HumanResourcesContactId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[DateAndTimeOfIncident](#DateAndTimeOfIncident)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[InjuryOrIllnessType](#InjuryOrIllnessType)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[InjuryOrIllnessTypeId](#InjuryOrIllnessTypeId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[PrivacyCase](#PrivacyCase)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[WhereIncidentOccurred](#WhereIncidentOccurred)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[OnWorkPremises](#OnWorkPremises)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[OshaCaseType](#OshaCaseType)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[OshaInjuryType](#OshaInjuryType)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[OutcomeType](#OutcomeType)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[OutcomeTypeId](#OutcomeTypeId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Position](#Position)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[PositionId](#PositionId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[ComplianceRecordableCase](#ComplianceRecordableCase)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[ReportedBy](#ReportedBy)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[ReportedById](#ReportedById)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[DateAndTimeReported](#DateAndTimeReported)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[SafeguardsThatWereProvided](#SafeguardsThatWereProvided)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[SeverityLevel](#SeverityLevel)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[SeverityLevelId](#SeverityLevelId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Supervisor](#Supervisor)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[SupervisorId](#SupervisorId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[EmployeeJobOrTask](#EmployeeJobOrTask)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Worker](#Worker)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[WorkerId](#WorkerId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[DateAndTimeBeganWork](#DateAndTimeBeganWork)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_BodyPartRelationshipId](#Relationship_BodyPartRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_IncidentTypeRelationshipId](#Relationship_IncidentTypeRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_OutcomeTypeRelationshipId](#Relationship_OutcomeTypeRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_PositionRelationshipId](#Relationship_PositionRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_SeverityLevelRelationshipId](#Relationship_SeverityLevelRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_HumanResourcesContactWorkerRelationshipId](#Relationship_HumanResourcesContactWorkerRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_ReportedByWorkerRelationshipId](#Relationship_ReportedByWorkerRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_SupervisorWorkerRelationshipId](#Relationship_SupervisorWorkerRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="HcmInjuryIncidentEntity.md" target="_blank">HRM/HcmInjuryIncidentEntity</a>|

### <a href=#ActionToBeTaken name="ActionToBeTaken">ActionToBeTaken</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionToBeTaken attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BodyPart name="BodyPart">BodyPart</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BodyPart attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BodyPartId name="BodyPartId">BodyPartId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BodyPartId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CaseClosedDate name="CaseClosedDate">CaseClosedDate</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CaseClosedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CaseDescription name="CaseDescription">CaseDescription</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CaseDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CaseNumber name="CaseNumber">CaseNumber</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CaseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CaseOpenedDate name="CaseOpenedDate">CaseOpenedDate</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CaseOpenedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CaseStatus name="CaseStatus">CaseStatus</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CaseStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CauseOfIncident name="CauseOfIncident">CauseOfIncident</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CauseOfIncident attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysAwayFromWork name="DaysAwayFromWork">DaysAwayFromWork</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysAwayFromWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysOnJobTransferOrRestriction name="DaysOnJobTransferOrRestriction">DaysOnJobTransferOrRestriction</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysOnJobTransferOrRestriction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpectedDaysAwayFromWork name="ExpectedDaysAwayFromWork">ExpectedDaysAwayFromWork</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedDaysAwayFromWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HumanResourcesContact name="HumanResourcesContact">HumanResourcesContact</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HumanResourcesContact attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HumanResourcesContactId name="HumanResourcesContactId">HumanResourcesContactId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HumanResourcesContactId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateAndTimeOfIncident name="DateAndTimeOfIncident">DateAndTimeOfIncident</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateAndTimeOfIncident attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InjuryOrIllnessType name="InjuryOrIllnessType">InjuryOrIllnessType</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InjuryOrIllnessType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InjuryOrIllnessTypeId name="InjuryOrIllnessTypeId">InjuryOrIllnessTypeId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InjuryOrIllnessTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrivacyCase name="PrivacyCase">PrivacyCase</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrivacyCase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WhereIncidentOccurred name="WhereIncidentOccurred">WhereIncidentOccurred</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WhereIncidentOccurred attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnWorkPremises name="OnWorkPremises">OnWorkPremises</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnWorkPremises attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OshaCaseType name="OshaCaseType">OshaCaseType</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OshaCaseType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OshaInjuryType name="OshaInjuryType">OshaInjuryType</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OshaInjuryType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutcomeType name="OutcomeType">OutcomeType</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutcomeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutcomeTypeId name="OutcomeTypeId">OutcomeTypeId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutcomeTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

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

### <a href=#ComplianceRecordableCase name="ComplianceRecordableCase">ComplianceRecordableCase</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplianceRecordableCase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedBy name="ReportedBy">ReportedBy</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedById name="ReportedById">ReportedById</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedById attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateAndTimeReported name="DateAndTimeReported">DateAndTimeReported</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateAndTimeReported attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeguardsThatWereProvided name="SafeguardsThatWereProvided">SafeguardsThatWereProvided</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeguardsThatWereProvided attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SeverityLevel name="SeverityLevel">SeverityLevel</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeverityLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SeverityLevelId name="SeverityLevelId">SeverityLevelId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeverityLevelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Supervisor name="Supervisor">Supervisor</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Supervisor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SupervisorId name="SupervisorId">SupervisorId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SupervisorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmployeeJobOrTask name="EmployeeJobOrTask">EmployeeJobOrTask</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployeeJobOrTask attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

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

### <a href=#WorkerId name="WorkerId">WorkerId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateAndTimeBeganWork name="DateAndTimeBeganWork">DateAndTimeBeganWork</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateAndTimeBeganWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BodyPartRelationshipId name="Relationship_BodyPartRelationshipId">Relationship_BodyPartRelationshipId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BodyPartRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_IncidentTypeRelationshipId name="Relationship_IncidentTypeRelationshipId">Relationship_IncidentTypeRelationshipId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IncidentTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OutcomeTypeRelationshipId name="Relationship_OutcomeTypeRelationshipId">Relationship_OutcomeTypeRelationshipId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OutcomeTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PositionRelationshipId name="Relationship_PositionRelationshipId">Relationship_PositionRelationshipId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PositionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SeverityLevelRelationshipId name="Relationship_SeverityLevelRelationshipId">Relationship_SeverityLevelRelationshipId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SeverityLevelRelationshipId attribute are listed below.</summary>

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

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

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

### <a href=#Relationship_HumanResourcesContactWorkerRelationshipId name="Relationship_HumanResourcesContactWorkerRelationshipId">Relationship_HumanResourcesContactWorkerRelationshipId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HumanResourcesContactWorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportedByWorkerRelationshipId name="Relationship_ReportedByWorkerRelationshipId">Relationship_ReportedByWorkerRelationshipId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportedByWorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SupervisorWorkerRelationshipId name="Relationship_SupervisorWorkerRelationshipId">Relationship_SupervisorWorkerRelationshipId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SupervisorWorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: HRM/HcmInjuryIncidentEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
