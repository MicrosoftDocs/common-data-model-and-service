---
title: HcmBICourseAttendeesEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# HcmBICourseAttendeesEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/HumanResources/HRM/HcmBICourseAttendeesEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[Course](#Course)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Company](#Company)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[RegistrationDate](#RegistrationDate)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Demographics](#Demographics)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Person](#Person)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[AttendeeName](#AttendeeName)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Status](#Status)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[ApprovalStatus](#ApprovalStatus)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Job](#Job)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Position](#Position)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Title](#Title)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Employment](#Employment)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[ReportsTo](#ReportsTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Benefit](#Benefit)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[EmploymentValidFrom](#EmploymentValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[EmploymentValidTo](#EmploymentValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[EmploymentDetailValidFrom](#EmploymentDetailValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[EmploymentDetailValidTo](#EmploymentDetailValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PositionAssignmentValidTo](#PositionAssignmentValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PositionAssignmentValidFrom](#PositionAssignmentValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PositionDetailValidFrom](#PositionDetailValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PositionDetailValidTo](#PositionDetailValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[JobDetailValidFrom](#JobDetailValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[JobDetailValidTo](#JobDetailValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PositionHierarchyValidTo](#PositionHierarchyValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PositionHierarchyValidFrom](#PositionHierarchyValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[ReportsToWorkerPositionAssignmentValidFrom](#ReportsToWorkerPositionAssignmentValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[ReportsToWorkerPositionAssignmentValidTo](#ReportsToWorkerPositionAssignmentValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PersonDetailsValidFrom](#PersonDetailsValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PersonDetailsValidTo](#PersonDetailsValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[WorkerTitleValidFrom](#WorkerTitleValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[WorkerTitleValidTo](#WorkerTitleValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[WorkerEnrolledBenefitValidFrom](#WorkerEnrolledBenefitValidFrom)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[WorkerEnrolledBenefitValidTo](#WorkerEnrolledBenefitValidTo)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[EmploymentDetailValidToPrivate](#EmploymentDetailValidToPrivate)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[EmploymentDetailValidFromPrivate](#EmploymentDetailValidFromPrivate)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PositionDetailValidFromPrivate](#PositionDetailValidFromPrivate)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PositionDetailValidToPrivate](#PositionDetailValidToPrivate)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[JobDetailValidFromPrivate](#JobDetailValidFromPrivate)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[JobDetailValidToPrivate](#JobDetailValidToPrivate)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PersonDetailsValidFromPrivate](#PersonDetailsValidFromPrivate)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[PersonDetailsValidToPrivate](#PersonDetailsValidToPrivate)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="HcmBICourseAttendeesEntity.md" target="_blank">HRM/HcmBICourseAttendeesEntity</a>|

### <a href=#Course name="Course">Course</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Course attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

### <a href=#RegistrationDate name="RegistrationDate">RegistrationDate</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Demographics name="Demographics">Demographics</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

### <a href=#Person name="Person">Person</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Person attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttendeeName name="AttendeeName">AttendeeName</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttendeeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovalStatus name="ApprovalStatus">ApprovalStatus</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Job name="Job">Job</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

### <a href=#Position name="Position">Position</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

### <a href=#Title name="Title">Title</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

### <a href=#Employment name="Employment">Employment</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Employment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportsTo name="ReportsTo">ReportsTo</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportsTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Benefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentValidFrom name="EmploymentValidFrom">EmploymentValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentValidTo name="EmploymentValidTo">EmploymentValidTo</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidFrom name="EmploymentDetailValidFrom">EmploymentDetailValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidTo name="EmploymentDetailValidTo">EmploymentDetailValidTo</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionAssignmentValidTo name="PositionAssignmentValidTo">PositionAssignmentValidTo</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionAssignmentValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionAssignmentValidFrom name="PositionAssignmentValidFrom">PositionAssignmentValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionAssignmentValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionDetailValidFrom name="PositionDetailValidFrom">PositionDetailValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionDetailValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionDetailValidTo name="PositionDetailValidTo">PositionDetailValidTo</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionDetailValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidFrom name="JobDetailValidFrom">JobDetailValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

### <a href=#PositionHierarchyValidTo name="PositionHierarchyValidTo">PositionHierarchyValidTo</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionHierarchyValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionHierarchyValidFrom name="PositionHierarchyValidFrom">PositionHierarchyValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionHierarchyValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportsToWorkerPositionAssignmentValidFrom name="ReportsToWorkerPositionAssignmentValidFrom">ReportsToWorkerPositionAssignmentValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportsToWorkerPositionAssignmentValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportsToWorkerPositionAssignmentValidTo name="ReportsToWorkerPositionAssignmentValidTo">ReportsToWorkerPositionAssignmentValidTo</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportsToWorkerPositionAssignmentValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidFrom name="PersonDetailsValidFrom">PersonDetailsValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

### <a href=#WorkerTitleValidFrom name="WorkerTitleValidFrom">WorkerTitleValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerTitleValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerTitleValidTo name="WorkerTitleValidTo">WorkerTitleValidTo</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerTitleValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerEnrolledBenefitValidFrom name="WorkerEnrolledBenefitValidFrom">WorkerEnrolledBenefitValidFrom</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerEnrolledBenefitValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerEnrolledBenefitValidTo name="WorkerEnrolledBenefitValidTo">WorkerEnrolledBenefitValidTo</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerEnrolledBenefitValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidToPrivate name="EmploymentDetailValidToPrivate">EmploymentDetailValidToPrivate</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidToPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidFromPrivate name="EmploymentDetailValidFromPrivate">EmploymentDetailValidFromPrivate</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidFromPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionDetailValidFromPrivate name="PositionDetailValidFromPrivate">PositionDetailValidFromPrivate</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionDetailValidFromPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionDetailValidToPrivate name="PositionDetailValidToPrivate">PositionDetailValidToPrivate</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionDetailValidToPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidFromPrivate name="JobDetailValidFromPrivate">JobDetailValidFromPrivate</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

### <a href=#PersonDetailsValidFromPrivate name="PersonDetailsValidFromPrivate">PersonDetailsValidFromPrivate</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: HRM/HcmBICourseAttendeesEntity (this entity)  

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
