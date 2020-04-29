---
title: PayrollWorkerGarnishmentDetailEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Garnishment and tax levy details

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/PayrollWorkerGarnishmentDetailEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Garnishment and tax levy details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AdministrativeFee](#AdministrativeFee)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[CaseNumber](#CaseNumber)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[GarnishmentTaxLevyType](#GarnishmentTaxLevyType)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[State](#State)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[WorkerEnrolledBenefit](#WorkerEnrolledBenefit)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[Benefit](#Benefit)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[EnrollmentStart](#EnrollmentStart)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[EnrollmentEnd](#EnrollmentEnd)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[Worker](#Worker)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[BenefitID](#BenefitID)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollWorkerGarnishmentDetailEntity.md" target="_blank">Tax/PayrollWorkerGarnishmentDetailEntity</a>|

### <a href=#AdministrativeFee name="AdministrativeFee">AdministrativeFee</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdministrativeFee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CaseNumber name="CaseNumber">CaseNumber</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

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

### <a href=#GarnishmentTaxLevyType name="GarnishmentTaxLevyType">GarnishmentTaxLevyType</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GarnishmentTaxLevyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerEnrolledBenefit name="WorkerEnrolledBenefit">WorkerEnrolledBenefit</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerEnrolledBenefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

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

### <a href=#EnrollmentStart name="EnrollmentStart">EnrollmentStart</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

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

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

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

### <a href=#Worker name="Worker">Worker</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

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

### <a href=#BenefitID name="BenefitID">BenefitID</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: Tax/PayrollWorkerGarnishmentDetailEntity (this entity)  

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
