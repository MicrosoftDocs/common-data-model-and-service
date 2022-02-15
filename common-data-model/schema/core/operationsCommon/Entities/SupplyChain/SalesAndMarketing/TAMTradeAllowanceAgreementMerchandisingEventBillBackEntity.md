---
title: TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Trade allowance agreement merchandising event bill backs in SalesAndMarketing(TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trade allowance agreement merchandising event bill backs</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsTaxable](#IsTaxable)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[AccrualMainAccountId](#AccrualMainAccountId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[ExpenseMainAccountId](#ExpenseMainAccountId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[IsApprovalRequired](#IsApprovalRequired)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[SalesCumulationMethod](#SalesCumulationMethod)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[RebateBreakBasis](#RebateBreakBasis)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[MinimumBillBackAmountQualifyingRebate](#MinimumBillBackAmountQualifyingRebate)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[MinimumBillBackQuantityQualifyingRebate](#MinimumBillBackQuantityQualifyingRebate)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[LineAmountBasis](#LineAmountBasis)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[BillBackUnitSymbol](#BillBackUnitSymbol)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[BillBackQuantityType](#BillBackQuantityType)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[CalculationSearchDateType](#CalculationSearchDateType)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[SalesCumulationMethodCustomizedPeriodType](#SalesCumulationMethodCustomizedPeriodType)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[BillBackAmountCalculationOption](#BillBackAmountCalculationOption)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[AccrualMainAccountIdDisplayValue](#AccrualMainAccountIdDisplayValue)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[ExpenseMainAccountIdDisplayValue](#ExpenseMainAccountIdDisplayValue)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[SalesRebateProgramTypeId](#SalesRebateProgramTypeId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[BillBackId](#BillBackId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[BillBackClaimVendorAccountNumber](#BillBackClaimVendorAccountNumber)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[TradeAllowanceAgreementMerchandisingEventId](#TradeAllowanceAgreementMerchandisingEventId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[TradeAllowanceAgreementId](#TradeAllowanceAgreementId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[Relationship_AccrualMainAccountRelationshipId](#Relationship_AccrualMainAccountRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[Relationship_ExpenseMainAccountRelationshipId](#Relationship_ExpenseMainAccountRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId](#Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[Relationship_SalesRebateProgramTypeRelationshipId](#Relationship_SalesRebateProgramTypeRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[Relationship_TradeAllowanceAgreementHeaderRelationshipId](#Relationship_TradeAllowanceAgreementHeaderRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[BackingTable_PdsRebateAgreementRelationshipId](#BackingTable_PdsRebateAgreementRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity</a>|

### <a href=#IsTaxable name="IsTaxable">IsTaxable</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualMainAccountId name="AccrualMainAccountId">AccrualMainAccountId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseMainAccountId name="ExpenseMainAccountId">ExpenseMainAccountId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsApprovalRequired name="IsApprovalRequired">IsApprovalRequired</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsApprovalRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCumulationMethod name="SalesCumulationMethod">SalesCumulationMethod</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCumulationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateBreakBasis name="RebateBreakBasis">RebateBreakBasis</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateBreakBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumBillBackAmountQualifyingRebate name="MinimumBillBackAmountQualifyingRebate">MinimumBillBackAmountQualifyingRebate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumBillBackAmountQualifyingRebate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumBillBackQuantityQualifyingRebate name="MinimumBillBackQuantityQualifyingRebate">MinimumBillBackQuantityQualifyingRebate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumBillBackQuantityQualifyingRebate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmountBasis name="LineAmountBasis">LineAmountBasis</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmountBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillBackUnitSymbol name="BillBackUnitSymbol">BillBackUnitSymbol</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillBackUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillBackQuantityType name="BillBackQuantityType">BillBackQuantityType</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillBackQuantityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculationSearchDateType name="CalculationSearchDateType">CalculationSearchDateType</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationSearchDateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCumulationMethodCustomizedPeriodType name="SalesCumulationMethodCustomizedPeriodType">SalesCumulationMethodCustomizedPeriodType</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCumulationMethodCustomizedPeriodType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillBackAmountCalculationOption name="BillBackAmountCalculationOption">BillBackAmountCalculationOption</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill back amount calculation option</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillBackAmountCalculationOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bill back amount calculation option</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccrualMainAccountIdDisplayValue name="AccrualMainAccountIdDisplayValue">AccrualMainAccountIdDisplayValue</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate program accrual account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate program accrual account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseMainAccountIdDisplayValue name="ExpenseMainAccountIdDisplayValue">ExpenseMainAccountIdDisplayValue</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate program expense account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate program expense account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRebateProgramTypeId name="SalesRebateProgramTypeId">SalesRebateProgramTypeId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRebateProgramTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillBackId name="BillBackId">BillBackId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillBackId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillBackClaimVendorAccountNumber name="BillBackClaimVendorAccountNumber">BillBackClaimVendorAccountNumber</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillBackClaimVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementMerchandisingEventId name="TradeAllowanceAgreementMerchandisingEventId">TradeAllowanceAgreementMerchandisingEventId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAllowanceAgreementMerchandisingEventId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementId name="TradeAllowanceAgreementId">TradeAllowanceAgreementId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAllowanceAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccrualMainAccountRelationshipId name="Relationship_AccrualMainAccountRelationshipId">Relationship_AccrualMainAccountRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccrualMainAccountRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ExpenseMainAccountRelationshipId name="Relationship_ExpenseMainAccountRelationshipId">Relationship_ExpenseMainAccountRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExpenseMainAccountRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId name="Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId">Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesRebateProgramTypeRelationshipId name="Relationship_SalesRebateProgramTypeRelationshipId">Relationship_SalesRebateProgramTypeRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesRebateProgramTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TradeAllowanceAgreementHeaderRelationshipId name="Relationship_TradeAllowanceAgreementHeaderRelationshipId">Relationship_TradeAllowanceAgreementHeaderRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeAllowanceAgreementHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PdsRebateAgreementRelationshipId name="BackingTable_PdsRebateAgreementRelationshipId">BackingTable_PdsRebateAgreementRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsRebateAgreementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/PdsRebateAgreement.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/PdsRebateAgreement.cdm.json/PdsRebateAgreement</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/PdsRebateAgreement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackEntity (this entity)  

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
