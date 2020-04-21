---
title: HcmBIApplicantEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# HcmBIApplicantEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmBIApplicantEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[Age](#Age)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[Application](#Application)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[Applicant](#Applicant)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[CorrespondenceAction](#CorrespondenceAction)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[DateOfReceipt](#DateOfReceipt)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[ExpiryDate](#ExpiryDate)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[HiringManager](#HiringManager)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[Media](#Media)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[EducationLevel](#EducationLevel)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[RecruitmentProject](#RecruitmentProject)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[LodgingCost](#LodgingCost)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[OtherCost](#OtherCost)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[TravelCost](#TravelCost)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[Rating](#Rating)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[ReasonCode](#ReasonCode)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[ApplicationStatus](#ApplicationStatus)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[ApplicantType](#ApplicantType)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[StartDate](#StartDate)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[CreatedSource](#CreatedSource)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[Company](#Company)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[Job](#Job)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[Department](#Department)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[Demographics](#Demographics)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[GeographicLocation](#GeographicLocation)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[PostalAddressValidFrom](#PostalAddressValidFrom)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[PostalAddressValidTo](#PostalAddressValidTo)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[PersonDetailsValidFrom](#PersonDetailsValidFrom)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[PersonDetailsValidTo](#PersonDetailsValidTo)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[JobDetailValidFrom](#JobDetailValidFrom)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[JobDetailValidTo](#JobDetailValidTo)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[PersonDetailsValidFromPrivate](#PersonDetailsValidFromPrivate)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[PersonDetailsValidToPrivate](#PersonDetailsValidToPrivate)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[JobDetailValidFromPrivate](#JobDetailValidFromPrivate)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[JobDetailValidToPrivate](#JobDetailValidToPrivate)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[EmploymentValidFromPrivate](#EmploymentValidFromPrivate)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[EmploymentValidToPrivate](#EmploymentValidToPrivate)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="HcmBIApplicantEntity.md" target="_blank">HRM/HcmBIApplicantEntity</a>|

### <a href=#Age name="Age">Age</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Age attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Application name="Application">Application</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Application attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Applicant name="Applicant">Applicant</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Applicant attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrespondenceAction name="CorrespondenceAction">CorrespondenceAction</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrespondenceAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateOfReceipt name="DateOfReceipt">DateOfReceipt</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpiryDate name="ExpiryDate">ExpiryDate</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpiryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HiringManager name="HiringManager">HiringManager</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HiringManager attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Media name="Media">Media</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Media attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EducationLevel name="EducationLevel">EducationLevel</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EducationLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecruitmentProject name="RecruitmentProject">RecruitmentProject</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecruitmentProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LodgingCost name="LodgingCost">LodgingCost</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LodgingCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OtherCost name="OtherCost">OtherCost</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TravelCost name="TravelCost">TravelCost</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Rating name="Rating">Rating</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rating attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonCode name="ReasonCode">ReasonCode</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationStatus name="ApplicationStatus">ApplicationStatus</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicantType name="ApplicantType">ApplicantType</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicantType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreatedSource name="CreatedSource">CreatedSource</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatedSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Job name="Job">Job</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

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

### <a href=#Department name="Department">Department</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

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

### <a href=#Demographics name="Demographics">Demographics</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Demographics attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeographicLocation name="GeographicLocation">GeographicLocation</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeographicLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostalAddressValidFrom name="PostalAddressValidFrom">PostalAddressValidFrom</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostalAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostalAddressValidTo name="PostalAddressValidTo">PostalAddressValidTo</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostalAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidFrom name="PersonDetailsValidFrom">PersonDetailsValidFrom</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidTo name="PersonDetailsValidTo">PersonDetailsValidTo</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidFrom name="JobDetailValidFrom">JobDetailValidFrom</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidTo name="JobDetailValidTo">JobDetailValidTo</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidFromPrivate name="PersonDetailsValidFromPrivate">PersonDetailsValidFromPrivate</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidFromPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidToPrivate name="PersonDetailsValidToPrivate">PersonDetailsValidToPrivate</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidToPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidFromPrivate name="JobDetailValidFromPrivate">JobDetailValidFromPrivate</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidFromPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidToPrivate name="JobDetailValidToPrivate">JobDetailValidToPrivate</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidToPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentValidFromPrivate name="EmploymentValidFromPrivate">EmploymentValidFromPrivate</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentValidFromPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentValidToPrivate name="EmploymentValidToPrivate">EmploymentValidToPrivate</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentValidToPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: HRM/HcmBIApplicantEntity (this entity)  

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
