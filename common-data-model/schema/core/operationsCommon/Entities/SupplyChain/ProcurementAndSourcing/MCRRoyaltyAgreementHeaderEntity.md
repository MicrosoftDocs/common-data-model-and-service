---
title: MCRRoyaltyAgreementHeaderEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Royalty agreement headers in ProcurementAndSourcing(MCRRoyaltyAgreementHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Royalty agreement headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RoyaltyAgreementId](#RoyaltyAgreementId)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[IsApprovalRequired](#IsApprovalRequired)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[DefaultCalculationSearchDateType](#DefaultCalculationSearchDateType)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[SalesCumulationMethod](#SalesCumulationMethod)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[DefaultCurrencyCode](#DefaultCurrencyCode)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[AgreementDescription](#AgreementDescription)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[DefaultEffectiveDate](#DefaultEffectiveDate)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[DefaultExpirationDate](#DefaultExpirationDate)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[ItemRoyaltyRelation](#ItemRoyaltyRelation)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[ItemRoyaltyCode](#ItemRoyaltyCode)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[RoyaltyAccrualMainAccountId](#RoyaltyAccrualMainAccountId)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[RoyaltyAccrualMainAccountIdDisplayValue](#RoyaltyAccrualMainAccountIdDisplayValue)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[RoyaltyExpenseMainAccountId](#RoyaltyExpenseMainAccountId)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[RoyaltyExpenseMainAccountIdDisplayValue](#RoyaltyExpenseMainAccountIdDisplayValue)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[SalesCumulationMethodCustomizedPeriodType](#SalesCumulationMethodCustomizedPeriodType)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[AgreementNote](#AgreementNote)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[RoyaltyBreakBasis](#RoyaltyBreakBasis)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[LineAmountBasis](#LineAmountBasis)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[SalesUnitSymbolOption](#SalesUnitSymbolOption)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[DefaultSalesUnitSymbol](#DefaultSalesUnitSymbol)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[SalesUnitSymbolType](#SalesUnitSymbolType)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[DefaultVendorAccountNumber](#DefaultVendorAccountNumber)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[IsValidated](#IsValidated)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[ValidatedBy](#ValidatedBy)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[ValidatingWorkerPersonnelNumber](#ValidatingWorkerPersonnelNumber)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[Relationship_RoyaltyAccrualAccountCombinationRelationshipId](#Relationship_RoyaltyAccrualAccountCombinationRelationshipId)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[Relationship_RoyaltyExpenseAccountCombinationRelationshipId](#Relationship_RoyaltyExpenseAccountCombinationRelationshipId)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[BackingTable_MCRRoyaltyContractRelationshipId](#BackingTable_MCRRoyaltyContractRelationshipId)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="MCRRoyaltyAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity</a>|

### <a href=#RoyaltyAgreementId name="RoyaltyAgreementId">RoyaltyAgreementId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Royalty agreement Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Royalty agreement Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsApprovalRequired name="IsApprovalRequired">IsApprovalRequired</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

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

### <a href=#DefaultCalculationSearchDateType name="DefaultCalculationSearchDateType">DefaultCalculationSearchDateType</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCalculationSearchDateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCumulationMethod name="SalesCumulationMethod">SalesCumulationMethod</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

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

### <a href=#DefaultCurrencyCode name="DefaultCurrencyCode">DefaultCurrencyCode</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementDescription name="AgreementDescription">AgreementDescription</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultEffectiveDate name="DefaultEffectiveDate">DefaultEffectiveDate</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultEffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultExpirationDate name="DefaultExpirationDate">DefaultExpirationDate</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRoyaltyRelation name="ItemRoyaltyRelation">ItemRoyaltyRelation</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRoyaltyRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRoyaltyCode name="ItemRoyaltyCode">ItemRoyaltyCode</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRoyaltyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyAccrualMainAccountId name="RoyaltyAccrualMainAccountId">RoyaltyAccrualMainAccountId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyAccrualMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyAccrualMainAccountIdDisplayValue name="RoyaltyAccrualMainAccountIdDisplayValue">RoyaltyAccrualMainAccountIdDisplayValue</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accrual account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyAccrualMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accrual account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyExpenseMainAccountId name="RoyaltyExpenseMainAccountId">RoyaltyExpenseMainAccountId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyExpenseMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyExpenseMainAccountIdDisplayValue name="RoyaltyExpenseMainAccountIdDisplayValue">RoyaltyExpenseMainAccountIdDisplayValue</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyExpenseMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expense account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCumulationMethodCustomizedPeriodType name="SalesCumulationMethodCustomizedPeriodType">SalesCumulationMethodCustomizedPeriodType</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

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

### <a href=#AgreementNote name="AgreementNote">AgreementNote</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyBreakBasis name="RoyaltyBreakBasis">RoyaltyBreakBasis</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyBreakBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmountBasis name="LineAmountBasis">LineAmountBasis</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

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

### <a href=#SalesUnitSymbolOption name="SalesUnitSymbolOption">SalesUnitSymbolOption</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitSymbolOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesUnitSymbol name="DefaultSalesUnitSymbol">DefaultSalesUnitSymbol</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitSymbolType name="SalesUnitSymbolType">SalesUnitSymbolType</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitSymbolType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVendorAccountNumber name="DefaultVendorAccountNumber">DefaultVendorAccountNumber</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsValidated name="IsValidated">IsValidated</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsValidated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidatedBy name="ValidatedBy">ValidatedBy</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidatingWorkerPersonnelNumber name="ValidatingWorkerPersonnelNumber">ValidatingWorkerPersonnelNumber</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Validated by</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatingWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Validated by</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RoyaltyAccrualAccountCombinationRelationshipId name="Relationship_RoyaltyAccrualAccountCombinationRelationshipId">Relationship_RoyaltyAccrualAccountCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RoyaltyAccrualAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RoyaltyExpenseAccountCombinationRelationshipId name="Relationship_RoyaltyExpenseAccountCombinationRelationshipId">Relationship_RoyaltyExpenseAccountCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RoyaltyExpenseAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_MCRRoyaltyContractRelationshipId name="BackingTable_MCRRoyaltyContractRelationshipId">BackingTable_MCRRoyaltyContractRelationshipId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MCRRoyaltyContractRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Worksheet/MCRRoyaltyContract.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Worksheet/MCRRoyaltyContract.cdm.json/MCRRoyaltyContract</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Worksheet/MCRRoyaltyContract.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementHeaderEntity (this entity)  

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
