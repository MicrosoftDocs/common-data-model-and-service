---
title: SalesRebateAgreementHeaderV2Entity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Customer rebate agreement headers V2 in SalesAndMarketing(SalesRebateAgreementHeaderV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesRebateAgreementHeaderV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer rebate agreement headers V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsTaxable](#IsTaxable)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[AccrualMainAccountId](#AccrualMainAccountId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[Note](#Note)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ExpenseMainAccountId](#ExpenseMainAccountId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[IsApprovalRequired](#IsApprovalRequired)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[SalesCumulationMethod](#SalesCumulationMethod)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[PdsCustRebateCode](#PdsCustRebateCode)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[PdsCustRebateRelation](#PdsCustRebateRelation)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ItemCode](#ItemCode)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ItemRelation](#ItemRelation)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[PaymentType](#PaymentType)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[RebateBreakBasis](#RebateBreakBasis)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[MinimumSalesAmountQualifyingRebate](#MinimumSalesAmountQualifyingRebate)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[MinimumSalesQuantityQualifyingRebate](#MinimumSalesQuantityQualifyingRebate)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[LineAmountBasis](#LineAmountBasis)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ProductUnitSymbol](#ProductUnitSymbol)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ProductUnitSymbolType](#ProductUnitSymbolType)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[CalculationSearchDateType](#CalculationSearchDateType)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[SalesCumulationMethodCustomizedPeriodType](#SalesCumulationMethodCustomizedPeriodType)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[IsGenericCurrencySearchEnabled](#IsGenericCurrencySearchEnabled)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ProductUnitSymbolOption](#ProductUnitSymbolOption)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ApprovalStatus](#ApprovalStatus)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[IsValidated](#IsValidated)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ValidFrom](#ValidFrom)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ValidTo](#ValidTo)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ValidatedBy](#ValidatedBy)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ValidatingWorkerPersonnelNumber](#ValidatingWorkerPersonnelNumber)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[AccrualMainAccountIdDisplayValue](#AccrualMainAccountIdDisplayValue)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ExpenseMainAccountIdDisplayValue](#ExpenseMainAccountIdDisplayValue)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[RebateProgramId](#RebateProgramId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[QualifyingSiteId](#QualifyingSiteId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[QualifyingWarehouseId](#QualifyingWarehouseId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[SalesRebateProductGroupId](#SalesRebateProductGroupId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[SalesRebateCustomerGroupId](#SalesRebateCustomerGroupId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[IsProductUnitSymbolExact](#IsProductUnitSymbolExact)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[IsProductSelectionUsed](#IsProductSelectionUsed)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[RebateAgreementId](#RebateAgreementId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[Relationship_AccrualMainAccountIdCombinationRelationshipId](#Relationship_AccrualMainAccountIdCombinationRelationshipId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[Relationship_ExpenseMainAccountIdCombinationRelationshipId](#Relationship_ExpenseMainAccountIdCombinationRelationshipId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[BackingTable_PdsRebateAgreementRelationshipId](#BackingTable_PdsRebateAgreementRelationshipId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesRebateAgreementHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesRebateAgreementHeaderV2Entity</a>|

### <a href=#IsTaxable name="IsTaxable">IsTaxable</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

### <a href=#Note name="Note">Note</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Note attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseMainAccountId name="ExpenseMainAccountId">ExpenseMainAccountId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

### <a href=#PdsCustRebateCode name="PdsCustRebateCode">PdsCustRebateCode</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCustRebateCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsCustRebateRelation name="PdsCustRebateRelation">PdsCustRebateRelation</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCustRebateRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentType name="PaymentType">PaymentType</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateBreakBasis name="RebateBreakBasis">RebateBreakBasis</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

### <a href=#MinimumSalesAmountQualifyingRebate name="MinimumSalesAmountQualifyingRebate">MinimumSalesAmountQualifyingRebate</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumSalesAmountQualifyingRebate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumSalesQuantityQualifyingRebate name="MinimumSalesQuantityQualifyingRebate">MinimumSalesQuantityQualifyingRebate</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumSalesQuantityQualifyingRebate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmountBasis name="LineAmountBasis">LineAmountBasis</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

### <a href=#ProductUnitSymbol name="ProductUnitSymbol">ProductUnitSymbol</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductUnitSymbolType name="ProductUnitSymbolType">ProductUnitSymbolType</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductUnitSymbolType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculationSearchDateType name="CalculationSearchDateType">CalculationSearchDateType</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCumulationMethodCustomizedPeriodType name="SalesCumulationMethodCustomizedPeriodType">SalesCumulationMethodCustomizedPeriodType</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

### <a href=#IsGenericCurrencySearchEnabled name="IsGenericCurrencySearchEnabled">IsGenericCurrencySearchEnabled</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGenericCurrencySearchEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductUnitSymbolOption name="ProductUnitSymbolOption">ProductUnitSymbolOption</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductUnitSymbolOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovalStatus name="ApprovalStatus">ApprovalStatus</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsValidated name="IsValidated">IsValidated</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

### <a href=#ValidatedBy name="ValidatedBy">ValidatedBy</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

### <a href=#AccrualMainAccountIdDisplayValue name="AccrualMainAccountIdDisplayValue">AccrualMainAccountIdDisplayValue</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate program accrual account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccrualMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate program accrual account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseMainAccountIdDisplayValue name="ExpenseMainAccountIdDisplayValue">ExpenseMainAccountIdDisplayValue</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate program expense account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate program expense account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateProgramId name="RebateProgramId">RebateProgramId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateProgramId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualifyingSiteId name="QualifyingSiteId">QualifyingSiteId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualifyingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualifyingWarehouseId name="QualifyingWarehouseId">QualifyingWarehouseId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualifyingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRebateProductGroupId name="SalesRebateProductGroupId">SalesRebateProductGroupId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRebateProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRebateCustomerGroupId name="SalesRebateCustomerGroupId">SalesRebateCustomerGroupId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRebateCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductUnitSymbolExact name="IsProductUnitSymbolExact">IsProductUnitSymbolExact</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductUnitSymbolExact attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductSelectionUsed name="IsProductSelectionUsed">IsProductSelectionUsed</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductSelectionUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateAgreementId name="RebateAgreementId">RebateAgreementId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccrualMainAccountIdCombinationRelationshipId name="Relationship_AccrualMainAccountIdCombinationRelationshipId">Relationship_AccrualMainAccountIdCombinationRelationshipId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccrualMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ExpenseMainAccountIdCombinationRelationshipId name="Relationship_ExpenseMainAccountIdCombinationRelationshipId">Relationship_ExpenseMainAccountIdCombinationRelationshipId</a>

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExpenseMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesRebateAgreementHeaderV2Entity (this entity)  

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
