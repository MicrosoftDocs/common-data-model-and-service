---
title: PayrollWorkerEnrolledBenefitLimitEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Contribution and deduction limit of enrolled benefits in Payroll(PayrollWorkerEnrolledBenefitLimitEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollWorkerEnrolledBenefitLimitEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contribution and deduction limit of enrolled benefits</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ContributionLimitAmount](#ContributionLimitAmount)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[ContributionLimitEndDate](#ContributionLimitEndDate)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[ContributionLimitPeriod](#ContributionLimitPeriod)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[ContributionLimitPeriodRemaining](#ContributionLimitPeriodRemaining)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[DeductionLimitAmount](#DeductionLimitAmount)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[DeductionLimitEndDate](#DeductionLimitEndDate)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[DeductionLimitPeriod](#DeductionLimitPeriod)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[DeductionLimitPeriodRemaining](#DeductionLimitPeriodRemaining)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[WorkerEnrolledBenefit](#WorkerEnrolledBenefit)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[Benefit](#Benefit)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[EnrollmentStart](#EnrollmentStart)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[EnrollmentEnd](#EnrollmentEnd)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[EnrolledBenefitWorker](#EnrolledBenefitWorker)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[BenefitId](#BenefitId)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollWorkerEnrolledBenefitLimitEntity.md" target="_blank">Payroll/PayrollWorkerEnrolledBenefitLimitEntity</a>|

### <a href=#ContributionLimitAmount name="ContributionLimitAmount">ContributionLimitAmount</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionLimitAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionLimitEndDate name="ContributionLimitEndDate">ContributionLimitEndDate</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionLimitEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionLimitPeriod name="ContributionLimitPeriod">ContributionLimitPeriod</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionLimitPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionLimitPeriodRemaining name="ContributionLimitPeriodRemaining">ContributionLimitPeriodRemaining</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionLimitPeriodRemaining attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionLimitAmount name="DeductionLimitAmount">DeductionLimitAmount</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionLimitAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionLimitEndDate name="DeductionLimitEndDate">DeductionLimitEndDate</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionLimitEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionLimitPeriod name="DeductionLimitPeriod">DeductionLimitPeriod</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionLimitPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionLimitPeriodRemaining name="DeductionLimitPeriodRemaining">DeductionLimitPeriodRemaining</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionLimitPeriodRemaining attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerEnrolledBenefit name="WorkerEnrolledBenefit">WorkerEnrolledBenefit</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerEnrolledBenefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

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

### <a href=#EnrollmentStart name="EnrollmentStart">EnrollmentStart</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnrollmentStart attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnrollmentEnd name="EnrollmentEnd">EnrollmentEnd</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnrollmentEnd attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnrolledBenefitWorker name="EnrolledBenefitWorker">EnrolledBenefitWorker</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnrolledBenefitWorker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

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

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: Payroll/PayrollWorkerEnrolledBenefitLimitEntity (this entity)  

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
