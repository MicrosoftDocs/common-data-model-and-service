---
title: PayrollBenefitDetailEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Payroll benefit detail in Payroll(PayrollBenefitDetailEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollBenefitDetailEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payroll benefit detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Benefit](#Benefit)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[ContributionCalculationFrequency](#ContributionCalculationFrequency)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[ContributionCalculationRate](#ContributionCalculationRate)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[DeductionCalculationFrequency](#DeductionCalculationFrequency)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[DefaultContributionAccountingCurrencyAmt](#DefaultContributionAccountingCurrencyAmt)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[DefaultContributionBasis](#DefaultContributionBasis)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[DefaultDeductionAccountingCurrencyAmt](#DefaultDeductionAccountingCurrencyAmt)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[DefaultDeductionBasis](#DefaultDeductionBasis)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[ValidTo](#ValidTo)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[BenefitId](#BenefitId)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[ContributionCalculationFrequencyId](#ContributionCalculationFrequencyId)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[ContributionCalculationRateId](#ContributionCalculationRateId)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|
|[DeductionCalculationFrequencyId](#DeductionCalculationFrequencyId)||<a href="PayrollBenefitDetailEntity.md" target="_blank">Payroll/PayrollBenefitDetailEntity</a>|

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

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

### <a href=#ContributionCalculationFrequency name="ContributionCalculationFrequency">ContributionCalculationFrequency</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionCalculationFrequency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionCalculationRate name="ContributionCalculationRate">ContributionCalculationRate</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionCalculationRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionCalculationFrequency name="DeductionCalculationFrequency">DeductionCalculationFrequency</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionCalculationFrequency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultContributionAccountingCurrencyAmt name="DefaultContributionAccountingCurrencyAmt">DefaultContributionAccountingCurrencyAmt</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultContributionAccountingCurrencyAmt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultContributionBasis name="DefaultContributionBasis">DefaultContributionBasis</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultContributionBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDeductionAccountingCurrencyAmt name="DefaultDeductionAccountingCurrencyAmt">DefaultDeductionAccountingCurrencyAmt</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDeductionAccountingCurrencyAmt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDeductionBasis name="DefaultDeductionBasis">DefaultDeductionBasis</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDeductionBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

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

### <a href=#ContributionCalculationFrequencyId name="ContributionCalculationFrequencyId">ContributionCalculationFrequencyId</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contribution calculation frequency</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionCalculationFrequencyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contribution calculation frequency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContributionCalculationRateId name="ContributionCalculationRateId">ContributionCalculationRateId</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContributionCalculationRateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductionCalculationFrequencyId name="DeductionCalculationFrequencyId">DeductionCalculationFrequencyId</a>

First included in: Payroll/PayrollBenefitDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deduction calculation frequency</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionCalculationFrequencyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deduction calculation frequency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
