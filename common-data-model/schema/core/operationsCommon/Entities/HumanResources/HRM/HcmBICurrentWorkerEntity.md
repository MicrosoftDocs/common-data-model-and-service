---
title: HcmBICurrentWorkerEntity in HRM - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# HcmBICurrentWorkerEntity in HRM

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmBICurrentWorkerEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Company](#Company)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[Compensation](#Compensation)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[Benefit](#Benefit)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[Performance](#Performance)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PersonSkill](#PersonSkill)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[Demographics](#Demographics)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[Employment](#Employment)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[GeographicLocation](#GeographicLocation)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[Job](#Job)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[Position](#Position)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[ReportsTo](#ReportsTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[Title](#Title)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[Age](#Age)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[YearsOfService](#YearsOfService)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PositionAssignmentStartDate](#PositionAssignmentStartDate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PositionAssignmentEndDate](#PositionAssignmentEndDate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[EmploymentValidFrom](#EmploymentValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[EmploymentValidTo](#EmploymentValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[EmploymentDetailValidTo](#EmploymentDetailValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[EmploymentDetailValidFrom](#EmploymentDetailValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[FixedCompensationValidTo](#FixedCompensationValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[FixedCompensationValidFrom](#FixedCompensationValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PositionDetailValidFrom](#PositionDetailValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PositionDetailValidTo](#PositionDetailValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[JobDetailValidFrom](#JobDetailValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[JobDetailValidTo](#JobDetailValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PositionHierarchyValidTo](#PositionHierarchyValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PositionHierarchyValidFrom](#PositionHierarchyValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[ReportsToWorkerPositionAssignmentValidFrom](#ReportsToWorkerPositionAssignmentValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[ReportsToWorkerPositionAssignmentValidTo](#ReportsToWorkerPositionAssignmentValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PostalAddressValidFrom](#PostalAddressValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PostalAddressValidTo](#PostalAddressValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PersonDetailsValidFrom](#PersonDetailsValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PersonDetailsValidTo](#PersonDetailsValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[WorkerTitleValidFrom](#WorkerTitleValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[WorkerTitleValidTo](#WorkerTitleValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[WorkerEnrolledBenefitValidFrom](#WorkerEnrolledBenefitValidFrom)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[WorkerEnrolledBenefitValidTo](#WorkerEnrolledBenefitValidTo)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PersonDetailsValidToPrivate](#PersonDetailsValidToPrivate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PersonDetailsValidFromPrivate](#PersonDetailsValidFromPrivate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PositionDetailValidFromPrivate](#PositionDetailValidFromPrivate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[PositionDetailValidToPrivate](#PositionDetailValidToPrivate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[JobDetailValidFromPrivate](#JobDetailValidFromPrivate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[JobDetailValidToPrivate](#JobDetailValidToPrivate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[EmploymentDetailValidToPrivate](#EmploymentDetailValidToPrivate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|
|[EmploymentDetailValidFromPrivate](#EmploymentDetailValidFromPrivate)||<a href="HcmBICurrentWorkerEntity.md" target="_blank">HRM/HcmBICurrentWorkerEntity</a>|

### <a href=#Company name="Company">Company</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Compensation name="Compensation">Compensation</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Compensation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Benefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Performance name="Performance">Performance</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Performance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonSkill name="PersonSkill">PersonSkill</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonSkill attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Demographics name="Demographics">Demographics</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Demographics attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Employment name="Employment">Employment</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Employment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeographicLocation name="GeographicLocation">GeographicLocation</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeographicLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Job name="Job">Job</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Job attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportsTo name="ReportsTo">ReportsTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportsTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Title name="Title">Title</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Title attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Age name="Age">Age</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Age attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearsOfService name="YearsOfService">YearsOfService</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearsOfService attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionAssignmentStartDate name="PositionAssignmentStartDate">PositionAssignmentStartDate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionAssignmentStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionAssignmentEndDate name="PositionAssignmentEndDate">PositionAssignmentEndDate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionAssignmentEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentValidFrom name="EmploymentValidFrom">EmploymentValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentValidTo name="EmploymentValidTo">EmploymentValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidTo name="EmploymentDetailValidTo">EmploymentDetailValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidFrom name="EmploymentDetailValidFrom">EmploymentDetailValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedCompensationValidTo name="FixedCompensationValidTo">FixedCompensationValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedCompensationValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedCompensationValidFrom name="FixedCompensationValidFrom">FixedCompensationValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedCompensationValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionDetailValidFrom name="PositionDetailValidFrom">PositionDetailValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionDetailValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionDetailValidTo name="PositionDetailValidTo">PositionDetailValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionDetailValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidFrom name="JobDetailValidFrom">JobDetailValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidTo name="JobDetailValidTo">JobDetailValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionHierarchyValidTo name="PositionHierarchyValidTo">PositionHierarchyValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionHierarchyValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionHierarchyValidFrom name="PositionHierarchyValidFrom">PositionHierarchyValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionHierarchyValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportsToWorkerPositionAssignmentValidFrom name="ReportsToWorkerPositionAssignmentValidFrom">ReportsToWorkerPositionAssignmentValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportsToWorkerPositionAssignmentValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportsToWorkerPositionAssignmentValidTo name="ReportsToWorkerPositionAssignmentValidTo">ReportsToWorkerPositionAssignmentValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportsToWorkerPositionAssignmentValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostalAddressValidFrom name="PostalAddressValidFrom">PostalAddressValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostalAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostalAddressValidTo name="PostalAddressValidTo">PostalAddressValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostalAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidFrom name="PersonDetailsValidFrom">PersonDetailsValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidTo name="PersonDetailsValidTo">PersonDetailsValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerTitleValidFrom name="WorkerTitleValidFrom">WorkerTitleValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerTitleValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerTitleValidTo name="WorkerTitleValidTo">WorkerTitleValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerTitleValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerEnrolledBenefitValidFrom name="WorkerEnrolledBenefitValidFrom">WorkerEnrolledBenefitValidFrom</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerEnrolledBenefitValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerEnrolledBenefitValidTo name="WorkerEnrolledBenefitValidTo">WorkerEnrolledBenefitValidTo</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerEnrolledBenefitValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidToPrivate name="PersonDetailsValidToPrivate">PersonDetailsValidToPrivate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidToPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidFromPrivate name="PersonDetailsValidFromPrivate">PersonDetailsValidFromPrivate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidFromPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionDetailValidFromPrivate name="PositionDetailValidFromPrivate">PositionDetailValidFromPrivate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionDetailValidFromPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionDetailValidToPrivate name="PositionDetailValidToPrivate">PositionDetailValidToPrivate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionDetailValidToPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidFromPrivate name="JobDetailValidFromPrivate">JobDetailValidFromPrivate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidFromPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidToPrivate name="JobDetailValidToPrivate">JobDetailValidToPrivate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidToPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidToPrivate name="EmploymentDetailValidToPrivate">EmploymentDetailValidToPrivate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidToPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidFromPrivate name="EmploymentDetailValidFromPrivate">EmploymentDetailValidFromPrivate</a>

First included in: HRM/HcmBICurrentWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidFromPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
