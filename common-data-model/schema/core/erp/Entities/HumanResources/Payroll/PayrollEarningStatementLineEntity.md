---
title: PayrollEarningStatementLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PayrollEarningStatementLineEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/HumanResources/Payroll/PayrollEarningStatementLineEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[Amount](#Amount)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[AccountingDate](#AccountingDate)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[Dimension](#Dimension)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[EarningCode](#EarningCode)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[EarningsDate](#EarningsDate)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[EarningRate](#EarningRate)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[EarningsStatementHeader](#EarningsStatementHeader)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[GenerationSource](#GenerationSource)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[LineModified](#LineModified)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[IsManual](#IsManual)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[Note](#Note)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[PaymentStatus](#PaymentStatus)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[PayStatementEarningLine](#PayStatementEarningLine)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[Position](#Position)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[ActivityNumber](#ActivityNumber)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[ProjectCategory](#ProjectCategory)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[ProjectID](#ProjectID)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[ProjectLineProperty](#ProjectLineProperty)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[Quantity](#Quantity)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[WorkerCompensationBenefit](#WorkerCompensationBenefit)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[GeneralLiabilityInsurance](#GeneralLiabilityInsurance)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[TaxRegion](#TaxRegion)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[PremiumCode](#PremiumCode)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[OriginalRetroactiveRate](#OriginalRetroactiveRate)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[WorkPeriod](#WorkPeriod)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[EarningCodeId](#EarningCodeId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[EarningsStatementNumber](#EarningsStatementNumber)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[PositionId](#PositionId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[WorkerCompensationBenefitId](#WorkerCompensationBenefitId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[WorkerGeneralLiabilityInsuranceBenefitId](#WorkerGeneralLiabilityInsuranceBenefitId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[WorkerTaxRegionRecId](#WorkerTaxRegionRecId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[Worker](#Worker)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[LocationId](#LocationId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[WorkerTaxRegionLocationId](#WorkerTaxRegionLocationId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[OriginatingEarningStatementLine](#OriginatingEarningStatementLine)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[OriginatingEarningsStatementHeader](#OriginatingEarningsStatementHeader)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[OriginatingEarningStatementLineNumber](#OriginatingEarningStatementLineNumber)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[OriginatingEarningStatementNumber](#OriginatingEarningStatementNumber)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[PremiumEarningCode](#PremiumEarningCode)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[Company](#Company)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[AccountingDistributionTemplate](#AccountingDistributionTemplate)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[Relationship_PayrollEarningStatementHeaderEntityRelationshipId](#Relationship_PayrollEarningStatementHeaderEntityRelationshipId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|
|[BackingTable_PayrollEarningStatementLineRelationshipId](#BackingTable_PayrollEarningStatementLineRelationshipId)||<a href="PayrollEarningStatementLineEntity.md" target="_blank">Payroll/PayrollEarningStatementLineEntity</a>|

### <a href=#Amount name="Amount">Amount</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension name="Dimension">Dimension</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningCode name="EarningCode">EarningCode</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningsDate name="EarningsDate">EarningsDate</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningsDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningRate name="EarningRate">EarningRate</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarningsStatementHeader name="EarningsStatementHeader">EarningsStatementHeader</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningsStatementHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GenerationSource name="GenerationSource">GenerationSource</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerationSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineModified name="LineModified">LineModified</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineModified attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsManual name="IsManual">IsManual</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsManual attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Note attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentStatus name="PaymentStatus">PaymentStatus</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStatementEarningLine name="PayStatementEarningLine">PayStatementEarningLine</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatementEarningLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

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

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategory name="ProjectCategory">ProjectCategory</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectID name="ProjectID">ProjectID</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectLineProperty name="ProjectLineProperty">ProjectLineProperty</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectLineProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerCompensationBenefit name="WorkerCompensationBenefit">WorkerCompensationBenefit</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerCompensationBenefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralLiabilityInsurance name="GeneralLiabilityInsurance">GeneralLiabilityInsurance</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralLiabilityInsurance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRegion name="TaxRegion">TaxRegion</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PremiumCode name="PremiumCode">PremiumCode</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalRetroactiveRate name="OriginalRetroactiveRate">OriginalRetroactiveRate</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalRetroactiveRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkPeriod name="WorkPeriod">WorkPeriod</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

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

### <a href=#EarningCodeId name="EarningCodeId">EarningCodeId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

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

### <a href=#EarningsStatementNumber name="EarningsStatementNumber">EarningsStatementNumber</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarningsStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

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

### <a href=#WorkerCompensationBenefitId name="WorkerCompensationBenefitId">WorkerCompensationBenefitId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerCompensationBenefitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerGeneralLiabilityInsuranceBenefitId name="WorkerGeneralLiabilityInsuranceBenefitId">WorkerGeneralLiabilityInsuranceBenefitId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerGeneralLiabilityInsuranceBenefitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerTaxRegionRecId name="WorkerTaxRegionRecId">WorkerTaxRegionRecId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerTaxRegionRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

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

### <a href=#LocationId name="LocationId">LocationId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerTaxRegionLocationId name="WorkerTaxRegionLocationId">WorkerTaxRegionLocationId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

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

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

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

### <a href=#OriginatingEarningStatementLine name="OriginatingEarningStatementLine">OriginatingEarningStatementLine</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingEarningStatementLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatingEarningsStatementHeader name="OriginatingEarningsStatementHeader">OriginatingEarningsStatementHeader</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingEarningsStatementHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatingEarningStatementLineNumber name="OriginatingEarningStatementLineNumber">OriginatingEarningStatementLineNumber</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingEarningStatementLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatingEarningStatementNumber name="OriginatingEarningStatementNumber">OriginatingEarningStatementNumber</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingEarningStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PremiumEarningCode name="PremiumEarningCode">PremiumEarningCode</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

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

### <a href=#AccountingDistributionTemplate name="AccountingDistributionTemplate">AccountingDistributionTemplate</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PayrollEarningStatementHeaderEntityRelationshipId name="Relationship_PayrollEarningStatementHeaderEntityRelationshipId">Relationship_PayrollEarningStatementHeaderEntityRelationshipId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollEarningStatementHeaderEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollEarningStatementLineRelationshipId name="BackingTable_PayrollEarningStatementLineRelationshipId">BackingTable_PayrollEarningStatementLineRelationshipId</a>

First included in: Payroll/PayrollEarningStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollEarningStatementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/WorksheetLine/PayrollEarningStatementLine.md" target="_blank">/core/erp/Tables/HumanResources/Payroll/WorksheetLine/PayrollEarningStatementLine.cdm.json/PayrollEarningStatementLine</a></td><td><a href="../../../Tables/HumanResources/Payroll/WorksheetLine/PayrollEarningStatementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
