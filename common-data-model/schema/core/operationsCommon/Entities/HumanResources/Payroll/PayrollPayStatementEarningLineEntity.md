---
title: PayrollPayStatementEarningLineEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Pay statement earning lines in Payroll(PayrollPayStatementEarningLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollPayStatementEarningLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pay statement earning lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AmountInTransactionCurrency](#AmountInTransactionCurrency)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[AccountingDate](#AccountingDate)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[TemplateId](#TemplateId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[EmployerContribution](#EmployerContribution)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[LineToRemove](#LineToRemove)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[LineOverridden](#LineOverridden)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[PayStatement](#PayStatement)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[Position](#Position)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[PayStatementLineSource](#PayStatementLineSource)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[Company](#Company)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[EarningCode](#EarningCode)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[EarningsDate](#EarningsDate)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[EarningRate](#EarningRate)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[Quantity](#Quantity)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[WorkerCompensationBenefit](#WorkerCompensationBenefit)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[GeneralLiabilityInsurance](#GeneralLiabilityInsurance)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[TaxRegion](#TaxRegion)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[AccountingDistributionTemplateId](#AccountingDistributionTemplateId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[AccountingDistributionLegalEntityId](#AccountingDistributionLegalEntityId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[AccountingDistributionLegalEntity](#AccountingDistributionLegalEntity)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[PayStatementNumber](#PayStatementNumber)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[PositionId](#PositionId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[EarningCodeId](#EarningCodeId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[CompensationBenefitId](#CompensationBenefitId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[GeneralLiabilityInsuranceBenefitId](#GeneralLiabilityInsuranceBenefitId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[WorkerTaxRegion](#WorkerTaxRegion)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[TaxRegionLocationId](#TaxRegionLocationId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[WorkerTaxRegionLocationId](#WorkerTaxRegionLocationId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[ReversedPayStatementNumber](#ReversedPayStatementNumber)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[ReversedPayStatement](#ReversedPayStatement)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[ReversedPayStatementLineNum](#ReversedPayStatementLineNum)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[Relationship_PayrollPayStatementHeaderEntityRelationshipId](#Relationship_PayrollPayStatementHeaderEntityRelationshipId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[Relationship_HcmWorkerEntityRelationshipId](#Relationship_HcmWorkerEntityRelationshipId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[Relationship_HcmPositionV2EntityRelationshipId](#Relationship_HcmPositionV2EntityRelationshipId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[Relationship_PayrollWorkerTaxRegionEntityRelationshipId](#Relationship_PayrollWorkerTaxRegionEntityRelationshipId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|
|[BackingTable_PayrollPayStatementEarningLineRelationshipId](#BackingTable_PayrollPayStatementEarningLineRelationshipId)||<a href="PayrollPayStatementEarningLineEntity.md" target="_blank">Payroll/PayrollPayStatementEarningLineEntity</a>|

### <a href=#AmountInTransactionCurrency name="AmountInTransactionCurrency">AmountInTransactionCurrency</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmployerContribution name="EmployerContribution">EmployerContribution</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

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

### <a href=#LineToRemove name="LineToRemove">LineToRemove</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineToRemove attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineOverridden name="LineOverridden">LineOverridden</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStatement name="PayStatement">PayStatement</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

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

### <a href=#PayStatementLineSource name="PayStatementLineSource">PayStatementLineSource</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatementLineSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

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

### <a href=#EarningCode name="EarningCode">EarningCode</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningsDate name="EarningsDate">EarningsDate</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningsDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningRate name="EarningRate">EarningRate</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerCompensationBenefit name="WorkerCompensationBenefit">WorkerCompensationBenefit</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerCompensationBenefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLiabilityInsurance name="GeneralLiabilityInsurance">GeneralLiabilityInsurance</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLiabilityInsurance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRegion name="TaxRegion">TaxRegion</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplateId name="AccountingDistributionTemplateId">AccountingDistributionTemplateId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionLegalEntityId name="AccountingDistributionLegalEntityId">AccountingDistributionLegalEntityId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionLegalEntity name="AccountingDistributionLegalEntity">AccountingDistributionLegalEntity</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStatementNumber name="PayStatementNumber">PayStatementNumber</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCodeId name="EarningCodeId">EarningCodeId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompensationBenefitId name="CompensationBenefitId">CompensationBenefitId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationBenefitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLiabilityInsuranceBenefitId name="GeneralLiabilityInsuranceBenefitId">GeneralLiabilityInsuranceBenefitId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLiabilityInsuranceBenefitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerTaxRegion name="WorkerTaxRegion">WorkerTaxRegion</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerTaxRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRegionLocationId name="TaxRegionLocationId">TaxRegionLocationId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegionLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerTaxRegionLocationId name="WorkerTaxRegionLocationId">WorkerTaxRegionLocationId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerTaxRegionLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

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

### <a href=#ReversedPayStatementNumber name="ReversedPayStatementNumber">ReversedPayStatementNumber</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversedPayStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReversedPayStatement name="ReversedPayStatement">ReversedPayStatement</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversedPayStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReversedPayStatementLineNum name="ReversedPayStatementLineNum">ReversedPayStatementLineNum</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversedPayStatementLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollPayStatementHeaderEntityRelationshipId name="Relationship_PayrollPayStatementHeaderEntityRelationshipId">Relationship_PayrollPayStatementHeaderEntityRelationshipId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollPayStatementHeaderEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmWorkerEntityRelationshipId name="Relationship_HcmWorkerEntityRelationshipId">Relationship_HcmWorkerEntityRelationshipId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmPositionV2EntityRelationshipId name="Relationship_HcmPositionV2EntityRelationshipId">Relationship_HcmPositionV2EntityRelationshipId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmPositionV2EntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PayrollWorkerTaxRegionEntityRelationshipId name="Relationship_PayrollWorkerTaxRegionEntityRelationshipId">Relationship_PayrollWorkerTaxRegionEntityRelationshipId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollWorkerTaxRegionEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollPayStatementEarningLineRelationshipId name="BackingTable_PayrollPayStatementEarningLineRelationshipId">BackingTable_PayrollPayStatementEarningLineRelationshipId</a>

First included in: Payroll/PayrollPayStatementEarningLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollPayStatementEarningLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementEarningLine.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementEarningLine.cdm.json/PayrollPayStatementEarningLine</a></td><td><a href="../../../Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementEarningLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
