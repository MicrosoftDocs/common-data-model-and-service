---
title: TaxParametersEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Sales tax parameters in Tax

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CalculationPrinciple](#CalculationPrinciple)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[CheckSalesTaxGroupIntersection](#CheckSalesTaxGroupIntersection)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[ConditionalTax](#ConditionalTax)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[AmountsIncludeTaxInJournals](#AmountsIncludeTaxInJournals)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[Key](#Key)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[MandatoryTaxDirection](#MandatoryTaxDirection)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[AutoTaxSearch](#AutoTaxSearch)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[SalesTaxTaxationRules](#SalesTaxTaxationRules)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[IncludeAdjustmentOnReport](#IncludeAdjustmentOnReport)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[ReverseSalesTaxOnCashDiscount](#ReverseSalesTaxOnCashDiscount)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[TaxCalculationDate](#TaxCalculationDate)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[DefaultSalesTaxGroup](#DefaultSalesTaxGroup)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[DefaultItemSalesTaxGroup](#DefaultItemSalesTaxGroup)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[DeductTaxBeforeCashDiscountCalculation](#DeductTaxBeforeCashDiscountCalculation)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[LegalEntityforIntercompanyTax](#LegalEntityforIntercompanyTax)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[AdjustTaxForOverUnderpayment](#AdjustTaxForOverUnderpayment)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[TaxPerInvoiceLine](#TaxPerInvoiceLine)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[ValidateTaxCode](#ValidateTaxCode)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[BASFormatMappingRecId](#BASFormatMappingRecId)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[BASFormatName](#BASFormatName)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[BASSolutionName](#BASSolutionName)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[BASVendorUrl](#BASVendorUrl)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[IsConsumptionTaxReportsEnabled](#IsConsumptionTaxReportsEnabled)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[DefaultInvoiceType](#DefaultInvoiceType)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[GSTAuditFileFormatMappingRecId](#GSTAuditFileFormatMappingRecId)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[GSTAuditFileFormatName](#GSTAuditFileFormatName)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[GSTSolutionName](#GSTSolutionName)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[GSTVendorUrl](#GSTVendorUrl)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[GSTExemptPrintCode](#GSTExemptPrintCode)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[GSTGAFVersion](#GSTGAFVersion)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[GSTInvoiceFormat](#GSTInvoiceFormat)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[GSTSummaryDelimiter](#GSTSummaryDelimiter)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[IncludeDelimiterInGSTSummary](#IncludeDelimiterInGSTSummary)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[IncludeTaxCodeInGSTSummary](#IncludeTaxCodeInGSTSummary)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[IncludeTaxValueInGSTSummary](#IncludeTaxValueInGSTSummary)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[UseSelfBilledInvoice](#UseSelfBilledInvoice)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[DateForSecondTaxRaise](#DateForSecondTaxRaise)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[BankExchangeRate](#BankExchangeRate)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[SalesTaxPayableExchangeRateType](#SalesTaxPayableExchangeRateType)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[SalesTaxPayableExchangeRateTypeRecId](#SalesTaxPayableExchangeRateTypeRecId)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[SalesTaxReceivableExchangeRateType](#SalesTaxReceivableExchangeRateType)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[SalesTaxReceivableExchangeRateTypeRecId](#SalesTaxReceivableExchangeRateTypeRecId)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[IsTaxBranchEnabled](#IsTaxBranchEnabled)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[CashDiscountIsAppliedInTheInvoice](#CashDiscountIsAppliedInTheInvoice)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[ExchangeRateDifferenceDocumentType](#ExchangeRateDifferenceDocumentType)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[IncommingVATPayment](#IncommingVATPayment)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[UseVATDueDateInReports](#UseVATDueDateInReports)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[RestoredVATCalculationMethod](#RestoredVATCalculationMethod)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[RestoredVATGainCalculationMethod](#RestoredVATGainCalculationMethod)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[FixedOffsetPosting](#FixedOffsetPosting)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[BackingTable_TaxParametersRelationshipId](#BackingTable_TaxParametersRelationshipId)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxParametersEntity.md" target="_blank">Tax/TaxParametersEntity</a>|

### <a href=#CalculationPrinciple name="CalculationPrinciple">CalculationPrinciple</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationPrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckSalesTaxGroupIntersection name="CheckSalesTaxGroupIntersection">CheckSalesTaxGroupIntersection</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckSalesTaxGroupIntersection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConditionalTax name="ConditionalTax">ConditionalTax</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConditionalTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountsIncludeTaxInJournals name="AmountsIncludeTaxInJournals">AmountsIncludeTaxInJournals</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountsIncludeTaxInJournals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandatoryTaxDirection name="MandatoryTaxDirection">MandatoryTaxDirection</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryTaxDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoTaxSearch name="AutoTaxSearch">AutoTaxSearch</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoTaxSearch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxTaxationRules name="SalesTaxTaxationRules">SalesTaxTaxationRules</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxTaxationRules attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeAdjustmentOnReport name="IncludeAdjustmentOnReport">IncludeAdjustmentOnReport</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeAdjustmentOnReport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReverseSalesTaxOnCashDiscount name="ReverseSalesTaxOnCashDiscount">ReverseSalesTaxOnCashDiscount</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseSalesTaxOnCashDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCalculationDate name="TaxCalculationDate">TaxCalculationDate</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCalculationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesTaxGroup name="DefaultSalesTaxGroup">DefaultSalesTaxGroup</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultItemSalesTaxGroup name="DefaultItemSalesTaxGroup">DefaultItemSalesTaxGroup</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductTaxBeforeCashDiscountCalculation name="DeductTaxBeforeCashDiscountCalculation">DeductTaxBeforeCashDiscountCalculation</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductTaxBeforeCashDiscountCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityforIntercompanyTax name="LegalEntityforIntercompanyTax">LegalEntityforIntercompanyTax</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityforIntercompanyTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdjustTaxForOverUnderpayment name="AdjustTaxForOverUnderpayment">AdjustTaxForOverUnderpayment</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustTaxForOverUnderpayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPerInvoiceLine name="TaxPerInvoiceLine">TaxPerInvoiceLine</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPerInvoiceLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateTaxCode name="ValidateTaxCode">ValidateTaxCode</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateTaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BASFormatMappingRecId name="BASFormatMappingRecId">BASFormatMappingRecId</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BASFormatMappingRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BASFormatName name="BASFormatName">BASFormatName</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BASFormatName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BASSolutionName name="BASSolutionName">BASSolutionName</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BASSolutionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BASVendorUrl name="BASVendorUrl">BASVendorUrl</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BASVendorUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsConsumptionTaxReportsEnabled name="IsConsumptionTaxReportsEnabled">IsConsumptionTaxReportsEnabled</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsConsumptionTaxReportsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInvoiceType name="DefaultInvoiceType">DefaultInvoiceType</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInvoiceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTAuditFileFormatMappingRecId name="GSTAuditFileFormatMappingRecId">GSTAuditFileFormatMappingRecId</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTAuditFileFormatMappingRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTAuditFileFormatName name="GSTAuditFileFormatName">GSTAuditFileFormatName</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTAuditFileFormatName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTSolutionName name="GSTSolutionName">GSTSolutionName</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTSolutionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTVendorUrl name="GSTVendorUrl">GSTVendorUrl</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTVendorUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTExemptPrintCode name="GSTExemptPrintCode">GSTExemptPrintCode</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exempt GST print code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTExemptPrintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exempt GST print code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTGAFVersion name="GSTGAFVersion">GSTGAFVersion</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTGAFVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTInvoiceFormat name="GSTInvoiceFormat">GSTInvoiceFormat</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTInvoiceFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTSummaryDelimiter name="GSTSummaryDelimiter">GSTSummaryDelimiter</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTSummaryDelimiter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeDelimiterInGSTSummary name="IncludeDelimiterInGSTSummary">IncludeDelimiterInGSTSummary</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeDelimiterInGSTSummary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeTaxCodeInGSTSummary name="IncludeTaxCodeInGSTSummary">IncludeTaxCodeInGSTSummary</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeTaxCodeInGSTSummary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeTaxValueInGSTSummary name="IncludeTaxValueInGSTSummary">IncludeTaxValueInGSTSummary</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeTaxValueInGSTSummary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseSelfBilledInvoice name="UseSelfBilledInvoice">UseSelfBilledInvoice</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSelfBilledInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateForSecondTaxRaise name="DateForSecondTaxRaise">DateForSecondTaxRaise</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateForSecondTaxRaise attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankExchangeRate name="BankExchangeRate">BankExchangeRate</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bank exchange rate</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank exchange rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxPayableExchangeRateType name="SalesTaxPayableExchangeRateType">SalesTaxPayableExchangeRateType</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax payable exchange rate type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxPayableExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax payable exchange rate type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxPayableExchangeRateTypeRecId name="SalesTaxPayableExchangeRateTypeRecId">SalesTaxPayableExchangeRateTypeRecId</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxPayableExchangeRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxReceivableExchangeRateType name="SalesTaxReceivableExchangeRateType">SalesTaxReceivableExchangeRateType</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable exchange rate type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxReceivableExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable exchange rate type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxReceivableExchangeRateTypeRecId name="SalesTaxReceivableExchangeRateTypeRecId">SalesTaxReceivableExchangeRateTypeRecId</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxReceivableExchangeRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTaxBranchEnabled name="IsTaxBranchEnabled">IsTaxBranchEnabled</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxBranchEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountIsAppliedInTheInvoice name="CashDiscountIsAppliedInTheInvoice">CashDiscountIsAppliedInTheInvoice</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountIsAppliedInTheInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateDifferenceDocumentType name="ExchangeRateDifferenceDocumentType">ExchangeRateDifferenceDocumentType</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateDifferenceDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncommingVATPayment name="IncommingVATPayment">IncommingVATPayment</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncommingVATPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseVATDueDateInReports name="UseVATDueDateInReports">UseVATDueDateInReports</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseVATDueDateInReports attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestoredVATCalculationMethod name="RestoredVATCalculationMethod">RestoredVATCalculationMethod</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestoredVATCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestoredVATGainCalculationMethod name="RestoredVATGainCalculationMethod">RestoredVATGainCalculationMethod</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestoredVATGainCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedOffsetPosting name="FixedOffsetPosting">FixedOffsetPosting</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedOffsetPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TaxParametersRelationshipId name="BackingTable_TaxParametersRelationshipId">BackingTable_TaxParametersRelationshipId</a>

First included in: Tax/TaxParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Parameter/TaxParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Parameter/TaxParameters.cdm.json/TaxParameters</a></td><td><a href="../../../Tables/Finance/Tax/Parameter/TaxParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/TaxParametersEntity (this entity)  

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
