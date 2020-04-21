---
title: HcmParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# HcmParametersEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmParametersEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AbsenceStatusColor](#AbsenceStatusColor)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[ApplicationAttachmentType](#ApplicationAttachmentType)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[ApplicationWordDocuTypeId](#ApplicationWordDocuTypeId)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[ApplicationEmailDocuTypeId](#ApplicationEmailDocuTypeId)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[ApplicationUnsolictedRecruitingId](#ApplicationUnsolictedRecruitingId)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[ApplicationExpirationPeriod](#ApplicationExpirationPeriod)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[ApplicationExpirationPeriodUnit](#ApplicationExpirationPeriodUnit)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[CompensationCompetencyRatingModel](#CompensationCompetencyRatingModel)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[CompensationCompetencyRatingModelId](#CompensationCompetencyRatingModelId)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[EnableInjuryIllnessIncidentRetention](#EnableInjuryIllnessIncidentRetention)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[InjuryIllnessIncidentRetentionDays](#InjuryIllnessIncidentRetentionDays)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[Key](#Key)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEntitlementLeaveCalendarType](#FMLAEntitlementLeaveCalendarType)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEligibilityHoursWorked](#FMLAEligibilityHoursWorked)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEligibilityLengthOfEmployment](#FMLAEligibilityLengthOfEmployment)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEligibilityPeriodType](#FMLAEligibilityPeriodType)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEntitlementMilitaryHours](#FMLAEntitlementMilitaryHours)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEntitlementStandardHours](#FMLAEntitlementStandardHours)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEntitlementLeaveCalendarStartDate](#FMLAEntitlementLeaveCalendarStartDate)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEntitlementUseEligibilityPrioritySequence](#FMLAEntitlementUseEligibilityPrioritySequence)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEligibilityPriorityDateSequence1](#FMLAEligibilityPriorityDateSequence1)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEligibilityPriorityDateSequence2](#FMLAEligibilityPriorityDateSequence2)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEligibilityPriorityDateSequence3](#FMLAEligibilityPriorityDateSequence3)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEligibilityPriorityDateSequence4](#FMLAEligibilityPriorityDateSequence4)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEntitlementAnniversaryPriorityDateSequence1](#FMLAEntitlementAnniversaryPriorityDateSequence1)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEntitlementAnniversaryPriorityDateSequence2](#FMLAEntitlementAnniversaryPriorityDateSequence2)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEntitlementAnniversaryPriorityDateSequence3](#FMLAEntitlementAnniversaryPriorityDateSequence3)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[FMLAEntitlementAnniversaryPriorityDateSequence4](#FMLAEntitlementAnniversaryPriorityDateSequence4)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[RecentHireWorkersPeriod](#RecentHireWorkersPeriod)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[RecentHireWorkersPeriodUnit](#RecentHireWorkersPeriodUnit)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[LeavingSoonWorkersPeriod](#LeavingSoonWorkersPeriod)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[LeavingSoonWorkersPeriodUnit](#LeavingSoonWorkersPeriodUnit)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[MssOpenPositionsType](#MssOpenPositionsType)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[MssViewExitingWorkerOption](#MssViewExitingWorkerOption)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[MssExitingWorkersPeriod](#MssExitingWorkersPeriod)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[MssExitingWorkersPeriodUnit](#MssExitingWorkersPeriodUnit)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[IdentificationTypeDefault](#IdentificationTypeDefault)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[AllowRehireDefault](#AllowRehireDefault)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[ElectronicDisbursementValidationDisabled](#ElectronicDisbursementValidationDisabled)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[BankAccountAndRoutingNumberValidationDisabled](#BankAccountAndRoutingNumberValidationDisabled)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[CompensationRatingSource](#CompensationRatingSource)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="HcmParametersEntity.md" target="_blank">HRM/HcmParametersEntity</a>|

### <a href=#AbsenceStatusColor name="AbsenceStatusColor">AbsenceStatusColor</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsenceStatusColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationAttachmentType name="ApplicationAttachmentType">ApplicationAttachmentType</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationAttachmentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationWordDocuTypeId name="ApplicationWordDocuTypeId">ApplicationWordDocuTypeId</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationWordDocuTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationEmailDocuTypeId name="ApplicationEmailDocuTypeId">ApplicationEmailDocuTypeId</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationEmailDocuTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationUnsolictedRecruitingId name="ApplicationUnsolictedRecruitingId">ApplicationUnsolictedRecruitingId</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationUnsolictedRecruitingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationExpirationPeriod name="ApplicationExpirationPeriod">ApplicationExpirationPeriod</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationExpirationPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationExpirationPeriodUnit name="ApplicationExpirationPeriodUnit">ApplicationExpirationPeriodUnit</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationExpirationPeriodUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompensationCompetencyRatingModel name="CompensationCompetencyRatingModel">CompensationCompetencyRatingModel</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationCompetencyRatingModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompensationCompetencyRatingModelId name="CompensationCompetencyRatingModelId">CompensationCompetencyRatingModelId</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationCompetencyRatingModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableInjuryIllnessIncidentRetention name="EnableInjuryIllnessIncidentRetention">EnableInjuryIllnessIncidentRetention</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableInjuryIllnessIncidentRetention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InjuryIllnessIncidentRetentionDays name="InjuryIllnessIncidentRetentionDays">InjuryIllnessIncidentRetentionDays</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InjuryIllnessIncidentRetentionDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEntitlementLeaveCalendarType name="FMLAEntitlementLeaveCalendarType">FMLAEntitlementLeaveCalendarType</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEntitlementLeaveCalendarType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEligibilityHoursWorked name="FMLAEligibilityHoursWorked">FMLAEligibilityHoursWorked</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEligibilityHoursWorked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEligibilityLengthOfEmployment name="FMLAEligibilityLengthOfEmployment">FMLAEligibilityLengthOfEmployment</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEligibilityLengthOfEmployment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEligibilityPeriodType name="FMLAEligibilityPeriodType">FMLAEligibilityPeriodType</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEligibilityPeriodType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEntitlementMilitaryHours name="FMLAEntitlementMilitaryHours">FMLAEntitlementMilitaryHours</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEntitlementMilitaryHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEntitlementStandardHours name="FMLAEntitlementStandardHours">FMLAEntitlementStandardHours</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEntitlementStandardHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEntitlementLeaveCalendarStartDate name="FMLAEntitlementLeaveCalendarStartDate">FMLAEntitlementLeaveCalendarStartDate</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEntitlementLeaveCalendarStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEntitlementUseEligibilityPrioritySequence name="FMLAEntitlementUseEligibilityPrioritySequence">FMLAEntitlementUseEligibilityPrioritySequence</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEntitlementUseEligibilityPrioritySequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEligibilityPriorityDateSequence1 name="FMLAEligibilityPriorityDateSequence1">FMLAEligibilityPriorityDateSequence1</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEligibilityPriorityDateSequence1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEligibilityPriorityDateSequence2 name="FMLAEligibilityPriorityDateSequence2">FMLAEligibilityPriorityDateSequence2</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEligibilityPriorityDateSequence2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEligibilityPriorityDateSequence3 name="FMLAEligibilityPriorityDateSequence3">FMLAEligibilityPriorityDateSequence3</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEligibilityPriorityDateSequence3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEligibilityPriorityDateSequence4 name="FMLAEligibilityPriorityDateSequence4">FMLAEligibilityPriorityDateSequence4</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEligibilityPriorityDateSequence4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEntitlementAnniversaryPriorityDateSequence1 name="FMLAEntitlementAnniversaryPriorityDateSequence1">FMLAEntitlementAnniversaryPriorityDateSequence1</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEntitlementAnniversaryPriorityDateSequence1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEntitlementAnniversaryPriorityDateSequence2 name="FMLAEntitlementAnniversaryPriorityDateSequence2">FMLAEntitlementAnniversaryPriorityDateSequence2</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEntitlementAnniversaryPriorityDateSequence2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEntitlementAnniversaryPriorityDateSequence3 name="FMLAEntitlementAnniversaryPriorityDateSequence3">FMLAEntitlementAnniversaryPriorityDateSequence3</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEntitlementAnniversaryPriorityDateSequence3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FMLAEntitlementAnniversaryPriorityDateSequence4 name="FMLAEntitlementAnniversaryPriorityDateSequence4">FMLAEntitlementAnniversaryPriorityDateSequence4</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FMLAEntitlementAnniversaryPriorityDateSequence4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecentHireWorkersPeriod name="RecentHireWorkersPeriod">RecentHireWorkersPeriod</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecentHireWorkersPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecentHireWorkersPeriodUnit name="RecentHireWorkersPeriodUnit">RecentHireWorkersPeriodUnit</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecentHireWorkersPeriodUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeavingSoonWorkersPeriod name="LeavingSoonWorkersPeriod">LeavingSoonWorkersPeriod</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeavingSoonWorkersPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeavingSoonWorkersPeriodUnit name="LeavingSoonWorkersPeriodUnit">LeavingSoonWorkersPeriodUnit</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeavingSoonWorkersPeriodUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MssOpenPositionsType name="MssOpenPositionsType">MssOpenPositionsType</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MssOpenPositionsType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MssViewExitingWorkerOption name="MssViewExitingWorkerOption">MssViewExitingWorkerOption</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MssViewExitingWorkerOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MssExitingWorkersPeriod name="MssExitingWorkersPeriod">MssExitingWorkersPeriod</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MssExitingWorkersPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MssExitingWorkersPeriodUnit name="MssExitingWorkersPeriodUnit">MssExitingWorkersPeriodUnit</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MssExitingWorkersPeriodUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentificationTypeDefault name="IdentificationTypeDefault">IdentificationTypeDefault</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentificationTypeDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowRehireDefault name="AllowRehireDefault">AllowRehireDefault</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowRehireDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicDisbursementValidationDisabled name="ElectronicDisbursementValidationDisabled">ElectronicDisbursementValidationDisabled</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicDisbursementValidationDisabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountAndRoutingNumberValidationDisabled name="BankAccountAndRoutingNumberValidationDisabled">BankAccountAndRoutingNumberValidationDisabled</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountAndRoutingNumberValidationDisabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompensationRatingSource name="CompensationRatingSource">CompensationRatingSource</a>

First included in: HRM/HcmParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationRatingSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: HRM/HcmParametersEntity (this entity)  

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
