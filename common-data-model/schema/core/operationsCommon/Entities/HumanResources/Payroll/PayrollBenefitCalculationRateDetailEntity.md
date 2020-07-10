---
title: PayrollBenefitCalculationRateDetailEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Benefit calculation rate detail in Payroll(PayrollBenefitCalculationRateDetailEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollBenefitCalculationRateDetailEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Benefit calculation rate detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BenefitCalculationRateVersion](#BenefitCalculationRateVersion)||<a href="PayrollBenefitCalculationRateDetailEntity.md" target="_blank">Payroll/PayrollBenefitCalculationRateDetailEntity</a>|
|[ContributionMethod](#ContributionMethod)||<a href="PayrollBenefitCalculationRateDetailEntity.md" target="_blank">Payroll/PayrollBenefitCalculationRateDetailEntity</a>|
|[WorkerDeduction](#WorkerDeduction)||<a href="PayrollBenefitCalculationRateDetailEntity.md" target="_blank">Payroll/PayrollBenefitCalculationRateDetailEntity</a>|
|[EmployerContribution](#EmployerContribution)||<a href="PayrollBenefitCalculationRateDetailEntity.md" target="_blank">Payroll/PayrollBenefitCalculationRateDetailEntity</a>|
|[BenefitCalculationRate](#BenefitCalculationRate)||<a href="PayrollBenefitCalculationRateDetailEntity.md" target="_blank">Payroll/PayrollBenefitCalculationRateDetailEntity</a>|
|[Effective](#Effective)||<a href="PayrollBenefitCalculationRateDetailEntity.md" target="_blank">Payroll/PayrollBenefitCalculationRateDetailEntity</a>|
|[Expiration](#Expiration)||<a href="PayrollBenefitCalculationRateDetailEntity.md" target="_blank">Payroll/PayrollBenefitCalculationRateDetailEntity</a>|
|[Name](#Name)||<a href="PayrollBenefitCalculationRateDetailEntity.md" target="_blank">Payroll/PayrollBenefitCalculationRateDetailEntity</a>|
|[Relationship_PayrollBenefitCalculationRateHeaderEntityRelationshipId](#Relationship_PayrollBenefitCalculationRateHeaderEntityRelationshipId)||<a href="PayrollBenefitCalculationRateDetailEntity.md" target="_blank">Payroll/PayrollBenefitCalculationRateDetailEntity</a>|

### <a href=#BenefitCalculationRateVersion name="BenefitCalculationRateVersion">BenefitCalculationRateVersion</a>

First included in: Payroll/PayrollBenefitCalculationRateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitCalculationRateVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionMethod name="ContributionMethod">ContributionMethod</a>

First included in: Payroll/PayrollBenefitCalculationRateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerDeduction name="WorkerDeduction">WorkerDeduction</a>

First included in: Payroll/PayrollBenefitCalculationRateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerDeduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmployerContribution name="EmployerContribution">EmployerContribution</a>

First included in: Payroll/PayrollBenefitCalculationRateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployerContribution attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitCalculationRate name="BenefitCalculationRate">BenefitCalculationRate</a>

First included in: Payroll/PayrollBenefitCalculationRateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitCalculationRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Effective name="Effective">Effective</a>

First included in: Payroll/PayrollBenefitCalculationRateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Effective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Expiration name="Expiration">Expiration</a>

First included in: Payroll/PayrollBenefitCalculationRateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Expiration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Payroll/PayrollBenefitCalculationRateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollBenefitCalculationRateHeaderEntityRelationshipId name="Relationship_PayrollBenefitCalculationRateHeaderEntityRelationshipId">Relationship_PayrollBenefitCalculationRateHeaderEntityRelationshipId</a>

First included in: Payroll/PayrollBenefitCalculationRateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollBenefitCalculationRateHeaderEntityRelationshipId attribute are listed below.</summary>

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
