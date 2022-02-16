---
title: TAMVendorRebateAgreementHeaderEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Vendor rebate agreement headers in ProcurementAndSourcing(TAMVendorRebateAgreementHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor rebate agreement headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsApprovalRequired](#IsApprovalRequired)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[PurchaseCumulationMethod](#PurchaseCumulationMethod)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ItemCode](#ItemCode)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ItemRelation](#ItemRelation)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[AccrualMainAccountId](#AccrualMainAccountId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[AgreementNote](#AgreementNote)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ExpenseMainAccountId](#ExpenseMainAccountId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[PurchaseCumulationMethodCustomizedPeriodType](#PurchaseCumulationMethodCustomizedPeriodType)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[RebateBreakBasis](#RebateBreakBasis)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[MinimumPurchaseAmountQualifyingRebate](#MinimumPurchaseAmountQualifyingRebate)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[MinimumPurchaseQuantityQualifyingRebate](#MinimumPurchaseQuantityQualifyingRebate)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[RebateProgramId](#RebateProgramId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[LineAmountBasis](#LineAmountBasis)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ProductUnitSymbol](#ProductUnitSymbol)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ProductUnitSymbolOption](#ProductUnitSymbolOption)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ProductUnitSymbolType](#ProductUnitSymbolType)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[isAgreementValidated](#isAgreementValidated)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[EffectiveDate](#EffectiveDate)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ExpirationDate](#ExpirationDate)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[CalculationSearchDateType](#CalculationSearchDateType)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[VendRebateCode](#VendRebateCode)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[VendRebateRelation](#VendRebateRelation)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ValidatingWorkerPersonnelNumber](#ValidatingWorkerPersonnelNumber)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[WorkflowApprovalStatus](#WorkflowApprovalStatus)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[IsTaxable](#IsTaxable)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[AccrualMainAccountIdDisplayValue](#AccrualMainAccountIdDisplayValue)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ExpenseMainAccountIdDisplayValue](#ExpenseMainAccountIdDisplayValue)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[QualifyingWarehouseId](#QualifyingWarehouseId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[QualifyingSiteId](#QualifyingSiteId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[VendorRebateProductGroupId](#VendorRebateProductGroupId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[VendorRebateVendorGroupId](#VendorRebateVendorGroupId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[RebateAgreementId](#RebateAgreementId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[IsProductSelectionUsed](#IsProductSelectionUsed)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[IsProductUnitSymbolExact](#IsProductUnitSymbolExact)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[Relationship_AccrualMainAccountIdCombinationRelationshipId](#Relationship_AccrualMainAccountIdCombinationRelationshipId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[Relationship_ExpenseMainAccountIdCombinationRelationshipId](#Relationship_ExpenseMainAccountIdCombinationRelationshipId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[BackingTable_TAMVendRebateAgreementRelationshipId](#BackingTable_TAMVendRebateAgreementRelationshipId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TAMVendorRebateAgreementHeaderEntity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity</a>|

### <a href=#IsApprovalRequired name="IsApprovalRequired">IsApprovalRequired</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#PurchaseCumulationMethod name="PurchaseCumulationMethod">PurchaseCumulationMethod</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseCumulationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#AccrualMainAccountId name="AccrualMainAccountId">AccrualMainAccountId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#AgreementNote name="AgreementNote">AgreementNote</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#ExpenseMainAccountId name="ExpenseMainAccountId">ExpenseMainAccountId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#PurchaseCumulationMethodCustomizedPeriodType name="PurchaseCumulationMethodCustomizedPeriodType">PurchaseCumulationMethodCustomizedPeriodType</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseCumulationMethodCustomizedPeriodType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateBreakBasis name="RebateBreakBasis">RebateBreakBasis</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#MinimumPurchaseAmountQualifyingRebate name="MinimumPurchaseAmountQualifyingRebate">MinimumPurchaseAmountQualifyingRebate</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumPurchaseAmountQualifyingRebate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumPurchaseQuantityQualifyingRebate name="MinimumPurchaseQuantityQualifyingRebate">MinimumPurchaseQuantityQualifyingRebate</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumPurchaseQuantityQualifyingRebate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateProgramId name="RebateProgramId">RebateProgramId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#LineAmountBasis name="LineAmountBasis">LineAmountBasis</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#ProductUnitSymbolOption name="ProductUnitSymbolOption">ProductUnitSymbolOption</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#ProductUnitSymbolType name="ProductUnitSymbolType">ProductUnitSymbolType</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#isAgreementValidated name="isAgreementValidated">isAgreementValidated</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isAgreementValidated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveDate name="EffectiveDate">EffectiveDate</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculationSearchDateType name="CalculationSearchDateType">CalculationSearchDateType</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#VendRebateCode name="VendRebateCode">VendRebateCode</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRebateCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRebateRelation name="VendRebateRelation">VendRebateRelation</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRebateRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidatingWorkerPersonnelNumber name="ValidatingWorkerPersonnelNumber">ValidatingWorkerPersonnelNumber</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatingWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowApprovalStatus name="WorkflowApprovalStatus">WorkflowApprovalStatus</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowApprovalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTaxable name="IsTaxable">IsTaxable</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#AccrualMainAccountIdDisplayValue name="AccrualMainAccountIdDisplayValue">AccrualMainAccountIdDisplayValue</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#QualifyingWarehouseId name="QualifyingWarehouseId">QualifyingWarehouseId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#QualifyingSiteId name="QualifyingSiteId">QualifyingSiteId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#VendorRebateProductGroupId name="VendorRebateProductGroupId">VendorRebateProductGroupId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorRebateProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorRebateVendorGroupId name="VendorRebateVendorGroupId">VendorRebateVendorGroupId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorRebateVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateAgreementId name="RebateAgreementId">RebateAgreementId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate agreement id</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate agreement id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductSelectionUsed name="IsProductSelectionUsed">IsProductSelectionUsed</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#IsProductUnitSymbolExact name="IsProductUnitSymbolExact">IsProductUnitSymbolExact</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#Relationship_AccrualMainAccountIdCombinationRelationshipId name="Relationship_AccrualMainAccountIdCombinationRelationshipId">Relationship_AccrualMainAccountIdCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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

### <a href=#BackingTable_TAMVendRebateAgreementRelationshipId name="BackingTable_TAMVendRebateAgreementRelationshipId">BackingTable_TAMVendRebateAgreementRelationshipId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TAMVendRebateAgreementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/TAMVendRebateAgreement.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/TAMVendRebateAgreement.cdm.json/TAMVendRebateAgreement</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/TAMVendRebateAgreement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementHeaderEntity (this entity)  

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
