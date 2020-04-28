---
title: SalesRebateEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Customer rebates

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesRebateEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer rebates</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CurrencyCode](#CurrencyCode)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesInvoiceLineRecId](#SalesInvoiceLineRecId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesInvoiceLineCreationSequenceNumber](#SalesInvoiceLineCreationSequenceNumber)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[DefaultAccrualLedgerDimension](#DefaultAccrualLedgerDimension)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[DefaultAccrualLedgerDimensionDisplayValue](#DefaultAccrualLedgerDimensionDisplayValue)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesOrderLineInventoryLotId](#SalesOrderLineInventoryLotId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[DefaultAccrualMainAccountId](#DefaultAccrualMainAccountId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[DefaultAccrualMainAccountIdDisplayValue](#DefaultAccrualMainAccountIdDisplayValue)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[DefaultExpenseLedgerDimension](#DefaultExpenseLedgerDimension)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[DefaultExpenseLedgerDimensionDisplayValue](#DefaultExpenseLedgerDimensionDisplayValue)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[DefaultExpenseMainAccountId](#DefaultExpenseMainAccountId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[DefaultExpenseMainAccountIdDisplayValue](#DefaultExpenseMainAccountIdDisplayValue)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[CorrectedRebateAmount](#CorrectedRebateAmount)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesInvoiceRecId](#SalesInvoiceRecId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[CustomersOrderReference](#CustomersOrderReference)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesRebateCustomerGroupId](#SalesRebateCustomerGroupId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[InvoicedCatchWeightQuantity](#InvoicedCatchWeightQuantity)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesRebateProductGroupId](#SalesRebateProductGroupId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[IsCreditRebate](#IsCreditRebate)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[PaymentType](#PaymentType)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[AccountingDate](#AccountingDate)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebateAdjustmentDate](#RebateAdjustmentDate)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebateAgreementRefRecId](#RebateAgreementRefRecId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[ValueType](#ValueType)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebateBalanceAmount](#RebateBalanceAmount)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebateId](#RebateId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[VoucherNumber](#VoucherNumber)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebateStatus](#RebateStatus)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesRebateProgramTypeId](#SalesRebateProgramTypeId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[StartingRebateAmount](#StartingRebateAmount)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebateCalculationDate](#RebateCalculationDate)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebateAgreementLineRefRecId](#RebateAgreementLineRefRecId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebateSalesAmount](#RebateSalesAmount)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesOrderNumber](#SalesOrderNumber)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesInvoiceDate](#SalesInvoiceDate)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[InvoicedSalesQuantity](#InvoicedSalesQuantity)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesInvoiceNumber](#SalesInvoiceNumber)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesLineRecId](#SalesLineRecId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesLineAmount](#SalesLineAmount)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesPriceQuantity](#SalesPriceQuantity)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesTableRefRecId](#SalesTableRefRecId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[TradeAllowanceAgreementMerchandisingEventId](#TradeAllowanceAgreementMerchandisingEventId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesTaxItemGroupCode](#SalesTaxItemGroupCode)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebateAmountPerProductUnitSold](#RebateAmountPerProductUnitSold)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[FixedRebateAmount](#FixedRebateAmount)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[RebatePercentage](#RebatePercentage)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[SalesRebateAgreementId](#SalesRebateAgreementId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[Relationship_DefaultAccrualLedgerDimensionRelationshipId](#Relationship_DefaultAccrualLedgerDimensionRelationshipId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[Relationship_DefaultAccrualMainAccountIdRelationshipId](#Relationship_DefaultAccrualMainAccountIdRelationshipId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[Relationship_DefaultExpenseLedgerDimensionRelationshipId](#Relationship_DefaultExpenseLedgerDimensionRelationshipId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[Relationship_DefaultExpenseMainAccountIdRelationshipId](#Relationship_DefaultExpenseMainAccountIdRelationshipId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[BackingTable_PdsRebateTableRelationshipId](#BackingTable_PdsRebateTableRelationshipId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesRebateEntity.md" target="_blank">SalesAndMarketing/SalesRebateEntity</a>|

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

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

### <a href=#SalesInvoiceLineRecId name="SalesInvoiceLineRecId">SalesInvoiceLineRecId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInvoiceLineRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesInvoiceLineCreationSequenceNumber name="SalesInvoiceLineCreationSequenceNumber">SalesInvoiceLineCreationSequenceNumber</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInvoiceLineCreationSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultAccrualLedgerDimension name="DefaultAccrualLedgerDimension">DefaultAccrualLedgerDimension</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAccrualLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultAccrualLedgerDimensionDisplayValue name="DefaultAccrualLedgerDimensionDisplayValue">DefaultAccrualLedgerDimensionDisplayValue</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate accrual dimension display value</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAccrualLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate accrual dimension display value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderLineInventoryLotId name="SalesOrderLineInventoryLotId">SalesOrderLineInventoryLotId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultAccrualMainAccountId name="DefaultAccrualMainAccountId">DefaultAccrualMainAccountId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAccrualMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultAccrualMainAccountIdDisplayValue name="DefaultAccrualMainAccountIdDisplayValue">DefaultAccrualMainAccountIdDisplayValue</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate accrual account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAccrualMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate accrual account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultExpenseLedgerDimension name="DefaultExpenseLedgerDimension">DefaultExpenseLedgerDimension</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultExpenseLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultExpenseLedgerDimensionDisplayValue name="DefaultExpenseLedgerDimensionDisplayValue">DefaultExpenseLedgerDimensionDisplayValue</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate expense dimension display value</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultExpenseLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate expense dimension display value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultExpenseMainAccountId name="DefaultExpenseMainAccountId">DefaultExpenseMainAccountId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultExpenseMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultExpenseMainAccountIdDisplayValue name="DefaultExpenseMainAccountIdDisplayValue">DefaultExpenseMainAccountIdDisplayValue</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate expense account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultExpenseMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate expense account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedRebateAmount name="CorrectedRebateAmount">CorrectedRebateAmount</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedRebateAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesInvoiceRecId name="SalesInvoiceRecId">SalesInvoiceRecId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInvoiceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomersOrderReference name="CustomersOrderReference">CustomersOrderReference</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomersOrderReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRebateCustomerGroupId name="SalesRebateCustomerGroupId">SalesRebateCustomerGroupId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRebateCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicedCatchWeightQuantity name="InvoicedCatchWeightQuantity">InvoicedCatchWeightQuantity</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRebateProductGroupId name="SalesRebateProductGroupId">SalesRebateProductGroupId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRebateProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreditRebate name="IsCreditRebate">IsCreditRebate</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreditRebate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentType name="PaymentType">PaymentType</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

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

### <a href=#RebateAdjustmentDate name="RebateAdjustmentDate">RebateAdjustmentDate</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAdjustmentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateAgreementRefRecId name="RebateAgreementRefRecId">RebateAgreementRefRecId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAgreementRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueType name="ValueType">ValueType</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateBalanceAmount name="RebateBalanceAmount">RebateBalanceAmount</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateBalanceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateId name="RebateId">RebateId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherNumber name="VoucherNumber">VoucherNumber</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateStatus name="RebateStatus">RebateStatus</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRebateProgramTypeId name="SalesRebateProgramTypeId">SalesRebateProgramTypeId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

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

### <a href=#StartingRebateAmount name="StartingRebateAmount">StartingRebateAmount</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartingRebateAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateCalculationDate name="RebateCalculationDate">RebateCalculationDate</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateCalculationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateAgreementLineRefRecId name="RebateAgreementLineRefRecId">RebateAgreementLineRefRecId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAgreementLineRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateSalesAmount name="RebateSalesAmount">RebateSalesAmount</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales amount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateSalesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderNumber name="SalesOrderNumber">SalesOrderNumber</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesInvoiceDate name="SalesInvoiceDate">SalesInvoiceDate</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicedSalesQuantity name="InvoicedSalesQuantity">InvoicedSalesQuantity</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicedSalesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesInvoiceNumber name="SalesInvoiceNumber">SalesInvoiceNumber</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInvoiceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineRecId name="SalesLineRecId">SalesLineRecId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineAmount name="SalesLineAmount">SalesLineAmount</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceQuantity name="SalesPriceQuantity">SalesPriceQuantity</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTableRefRecId name="SalesTableRefRecId">SalesTableRefRecId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTableRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementMerchandisingEventId name="TradeAllowanceAgreementMerchandisingEventId">TradeAllowanceAgreementMerchandisingEventId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

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

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroupCode name="SalesTaxItemGroupCode">SalesTaxItemGroupCode</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateAmountPerProductUnitSold name="RebateAmountPerProductUnitSold">RebateAmountPerProductUnitSold</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate amount per product unit sold</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAmountPerProductUnitSold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate amount per product unit sold</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedRebateAmount name="FixedRebateAmount">FixedRebateAmount</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed rebate amount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedRebateAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed rebate amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebatePercentage name="RebatePercentage">RebatePercentage</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate percentage</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebatePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRebateAgreementId name="SalesRebateAgreementId">SalesRebateAgreementId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRebateAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultAccrualLedgerDimensionRelationshipId name="Relationship_DefaultAccrualLedgerDimensionRelationshipId">Relationship_DefaultAccrualLedgerDimensionRelationshipId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultAccrualLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultAccrualMainAccountIdRelationshipId name="Relationship_DefaultAccrualMainAccountIdRelationshipId">Relationship_DefaultAccrualMainAccountIdRelationshipId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultAccrualMainAccountIdRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultExpenseLedgerDimensionRelationshipId name="Relationship_DefaultExpenseLedgerDimensionRelationshipId">Relationship_DefaultExpenseLedgerDimensionRelationshipId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultExpenseLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultExpenseMainAccountIdRelationshipId name="Relationship_DefaultExpenseMainAccountIdRelationshipId">Relationship_DefaultExpenseMainAccountIdRelationshipId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultExpenseMainAccountIdRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PdsRebateTableRelationshipId name="BackingTable_PdsRebateTableRelationshipId">BackingTable_PdsRebateTableRelationshipId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsRebateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/PdsRebateTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/PdsRebateTable.cdm.json/PdsRebateTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/PdsRebateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesRebateEntity (this entity)  

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
