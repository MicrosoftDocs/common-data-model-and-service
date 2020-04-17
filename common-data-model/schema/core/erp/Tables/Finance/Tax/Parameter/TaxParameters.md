---
title: TaxParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# TaxParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Tax/Parameter/TaxParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[AllowDuplicates](#AllowDuplicates)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[BankExchRate_W](#BankExchRate_W)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[CalculatePrinciple](#CalculatePrinciple)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[CashAccountingRegime_ES](#CashAccountingRegime_ES)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[CashDiscOnInvoice](#CashDiscOnInvoice)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[CheckIntersection](#CheckIntersection)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ConditionalTax](#ConditionalTax)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[CustomerCalculationDateType_IN](#CustomerCalculationDateType_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[Customs_IN](#Customs_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[DeductionPercent_LT](#DeductionPercent_LT)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ExchRateDiffDocType_RU](#ExchRateDiffDocType_RU)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[Excise_IN](#Excise_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[EximIncentiveSchemes_IN](#EximIncentiveSchemes_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[IncomingVATPayment_RU](#IncomingVATPayment_RU)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ItemizedVATStatement_HU](#ItemizedVATStatement_HU)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ItemizedVATStatementLimit_HU](#ItemizedVATStatementLimit_HU)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[JournalInclTax](#JournalInclTax)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[Key](#Key)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[MainEconomicActivityCode_CZ](#MainEconomicActivityCode_CZ)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[MainEconomicActivityCode_LT](#MainEconomicActivityCode_LT)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[MandatoryTaxDirection](#MandatoryTaxDirection)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[MCRAutoTaxSearch](#MCRAutoTaxSearch)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[NaturalPersonFirstName_CZ](#NaturalPersonFirstName_CZ)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[NaturalPersonLastName_CZ](#NaturalPersonLastName_CZ)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[PersonTitle_CZ](#PersonTitle_CZ)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[PurchTaxOnOperations](#PurchTaxOnOperations)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ReportAdjustment](#ReportAdjustment)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ReportUseVatDueDate_W](#ReportUseVatDueDate_W)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[RestoredVATCalcMethod_RU](#RestoredVATCalcMethod_RU)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[RestoredVATGainCalcMethod_RU](#RestoredVATGainCalcMethod_RU)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ReverseOnCashDisc](#ReverseOnCashDisc)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ReverseSettlementDatePrinciple_W](#ReverseSettlementDatePrinciple_W)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[SalesTax_IN](#SalesTax_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[SalesTaxPayableExchangeRateType](#SalesTaxPayableExchangeRateType)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[SalesTaxReceivableExchangeRateType](#SalesTaxReceivableExchangeRateType)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ServiceTax_IN](#ServiceTax_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ServiceTaxACBasis_IN](#ServiceTaxACBasis_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxBranchEnabled](#TaxBranchEnabled)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxCalculationDateType](#TaxCalculationDateType)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxGroup](#TaxGroup)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxLessCashDisc](#TaxLessCashDisc)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxObligationCompany](#TaxObligationCompany)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxOnOverpayment](#TaxOnOverpayment)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxpayerStatus_CZ](#TaxpayerStatus_CZ)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxpayerType_CZ](#TaxpayerType_CZ)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxRecoverable_IN](#TaxRecoverable_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxReport_JP](#TaxReport_JP)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxReportFactor_CZ](#TaxReportFactor_CZ)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxSpecifyLine](#TaxSpecifyLine)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxSpecPosting_RU](#TaxSpecPosting_RU)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[ValidateTaxCode](#ValidateTaxCode)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[VAT_IN](#VAT_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[VendorCalculationDateType_IN](#VendorCalculationDateType_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[DefaultInvoiceType_MY](#DefaultInvoiceType_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[GSTExemptPrintCode_MY](#GSTExemptPrintCode_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[GSTGAFVersion_MY](#GSTGAFVersion_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[GSTInvoiceFormat_MY](#GSTInvoiceFormat_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[GSTSummaryDelimiter_MY](#GSTSummaryDelimiter_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[IncludeDelimiterInGSTSummary_MY](#IncludeDelimiterInGSTSummary_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[IncludeTaxCodeInGSTSummary_MY](#IncludeTaxCodeInGSTSummary_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[IncludeTaxValueInGSTSummary_MY](#IncludeTaxValueInGSTSummary_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[UseSelfBilledInvoice_MY](#UseSelfBilledInvoice_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[BASFormatMapping_AU](#BASFormatMapping_AU)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[GSTAuditFileFormatMapping_MY](#GSTAuditFileFormatMapping_MY)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[DateForSecondTaxRaise_JP](#DateForSecondTaxRaise_JP)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[DomesticTaxCancellationERFormatMapping_IT](#DomesticTaxCancellationERFormatMapping_IT)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[DomesticTaxAggregatedERFormatMapping_IT](#DomesticTaxAggregatedERFormatMapping_IT)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[DomesticTaxAnalyticERFormatMapping_IT](#DomesticTaxAnalyticERFormatMapping_IT)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxYearlyComERFormatMapping_IT](#TaxYearlyComERFormatMapping_IT)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[QuarterlyVATComERFormatMapping_IT](#QuarterlyVATComERFormatMapping_IT)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[SAFTAccountingBooksERFormatMapping_PL](#SAFTAccountingBooksERFormatMapping_PL)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[SAFTBankStatementERFormatMapping_PL](#SAFTBankStatementERFormatMapping_PL)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[SAFTInventoryERFormatMapping_PL](#SAFTInventoryERFormatMapping_PL)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[SAFTVATSalesPurchERFormatMapping_PL](#SAFTVATSalesPurchERFormatMapping_PL)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[SAFTVATInvoicesERFormatMapping_PL](#SAFTVATInvoicesERFormatMapping_PL)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[AdvancedSalesTaxPayment_IN](#AdvancedSalesTaxPayment_IN)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[FactureJournalFormatMappingID](#FactureJournalFormatMappingID)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[SAFTERFormatMapping_W](#SAFTERFormatMapping_W)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxReportFormatMappingID_UK](#TaxReportFormatMappingID_UK)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[IndirectTaxERFormatMapping_RU](#IndirectTaxERFormatMapping_RU)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[DelayTaxCalculation](#DelayTaxCalculation)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[TaxCurConvPath](#TaxCurConvPath)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[Relationship_SalesTaxPayableExchangeRateTypeRelationshipId](#Relationship_SalesTaxPayableExchangeRateTypeRelationshipId)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[Relationship_SalesTaxReceivableExchangeRateTypeRelationshipId](#Relationship_SalesTaxReceivableExchangeRateTypeRelationshipId)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[Relationship_TaxGroupHeadingRelationshipId](#Relationship_TaxGroupHeadingRelationshipId)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[Relationship_TaxItemGroupHeadingRelationshipId](#Relationship_TaxItemGroupHeadingRelationshipId)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxParameters.md" target="_blank">Parameter/TaxParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AllowDuplicates name="AllowDuplicates">AllowDuplicates</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowDuplicates attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankExchRate_W name="BankExchRate_W">BankExchRate_W</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankExchRate_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CalculatePrinciple name="CalculatePrinciple">CalculatePrinciple</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatePrinciple attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashAccountingRegime_ES name="CashAccountingRegime_ES">CashAccountingRegime_ES</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashAccountingRegime_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDiscOnInvoice name="CashDiscOnInvoice">CashDiscOnInvoice</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscOnInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckIntersection name="CheckIntersection">CheckIntersection</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckIntersection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ConditionalTax name="ConditionalTax">ConditionalTax</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConditionalTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerCalculationDateType_IN name="CustomerCalculationDateType_IN">CustomerCalculationDateType_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerCalculationDateType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Customs_IN name="Customs_IN">Customs_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Customs_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeductionPercent_LT name="DeductionPercent_LT">DeductionPercent_LT</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionPercent_LT attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExchRateDiffDocType_RU name="ExchRateDiffDocType_RU">ExchRateDiffDocType_RU</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateDiffDocType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Excise_IN name="Excise_IN">Excise_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Excise_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EximIncentiveSchemes_IN name="EximIncentiveSchemes_IN">EximIncentiveSchemes_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximIncentiveSchemes_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncomingVATPayment_RU name="IncomingVATPayment_RU">IncomingVATPayment_RU</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomingVATPayment_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemizedVATStatement_HU name="ItemizedVATStatement_HU">ItemizedVATStatement_HU</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemizedVATStatement_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemizedVATStatementLimit_HU name="ItemizedVATStatementLimit_HU">ItemizedVATStatementLimit_HU</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemizedVATStatementLimit_HU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#JournalInclTax name="JournalInclTax">JournalInclTax</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalInclTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#MainEconomicActivityCode_CZ name="MainEconomicActivityCode_CZ">MainEconomicActivityCode_CZ</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainEconomicActivityCode_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainEconomicActivityCode_LT name="MainEconomicActivityCode_LT">MainEconomicActivityCode_LT</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainEconomicActivityCode_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandatoryTaxDirection name="MandatoryTaxDirection">MandatoryTaxDirection</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryTaxDirection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRAutoTaxSearch name="MCRAutoTaxSearch">MCRAutoTaxSearch</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRAutoTaxSearch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NaturalPersonFirstName_CZ name="NaturalPersonFirstName_CZ">NaturalPersonFirstName_CZ</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NaturalPersonFirstName_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NaturalPersonLastName_CZ name="NaturalPersonLastName_CZ">NaturalPersonLastName_CZ</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NaturalPersonLastName_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonTitle_CZ name="PersonTitle_CZ">PersonTitle_CZ</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonTitle_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchTaxOnOperations name="PurchTaxOnOperations">PurchTaxOnOperations</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchTaxOnOperations attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReportAdjustment name="ReportAdjustment">ReportAdjustment</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportAdjustment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReportUseVatDueDate_W name="ReportUseVatDueDate_W">ReportUseVatDueDate_W</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportUseVatDueDate_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RestoredVATCalcMethod_RU name="RestoredVATCalcMethod_RU">RestoredVATCalcMethod_RU</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestoredVATCalcMethod_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RestoredVATGainCalcMethod_RU name="RestoredVATGainCalcMethod_RU">RestoredVATGainCalcMethod_RU</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestoredVATGainCalcMethod_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReverseOnCashDisc name="ReverseOnCashDisc">ReverseOnCashDisc</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseOnCashDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReverseSettlementDatePrinciple_W name="ReverseSettlementDatePrinciple_W">ReverseSettlementDatePrinciple_W</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseSettlementDatePrinciple_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesTax_IN name="SalesTax_IN">SalesTax_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTax_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesTaxPayableExchangeRateType name="SalesTaxPayableExchangeRateType">SalesTaxPayableExchangeRateType</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxPayableExchangeRateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SalesTaxReceivableExchangeRateType name="SalesTaxReceivableExchangeRateType">SalesTaxReceivableExchangeRateType</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxReceivableExchangeRateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceTax_IN name="ServiceTax_IN">ServiceTax_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTax_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ServiceTaxACBasis_IN name="ServiceTaxACBasis_IN">ServiceTaxACBasis_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxACBasis_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxBranchEnabled name="TaxBranchEnabled">TaxBranchEnabled</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBranchEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxCalculationDateType name="TaxCalculationDateType">TaxCalculationDateType</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCalculationDateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxLessCashDisc name="TaxLessCashDisc">TaxLessCashDisc</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxLessCashDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxObligationCompany name="TaxObligationCompany">TaxObligationCompany</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxObligationCompany attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxOnOverpayment name="TaxOnOverpayment">TaxOnOverpayment</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOnOverpayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxpayerStatus_CZ name="TaxpayerStatus_CZ">TaxpayerStatus_CZ</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxpayerStatus_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxpayerType_CZ name="TaxpayerType_CZ">TaxpayerType_CZ</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxpayerType_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxRecoverable_IN name="TaxRecoverable_IN">TaxRecoverable_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRecoverable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxReport_JP name="TaxReport_JP">TaxReport_JP</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReport_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxReportFactor_CZ name="TaxReportFactor_CZ">TaxReportFactor_CZ</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportFactor_CZ attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxSpecifyLine name="TaxSpecifyLine">TaxSpecifyLine</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSpecifyLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxSpecPosting_RU name="TaxSpecPosting_RU">TaxSpecPosting_RU</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSpecPosting_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidateTaxCode name="ValidateTaxCode">ValidateTaxCode</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateTaxCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VAT_IN name="VAT_IN">VAT_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VAT_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorCalculationDateType_IN name="VendorCalculationDateType_IN">VendorCalculationDateType_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCalculationDateType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultInvoiceType_MY name="DefaultInvoiceType_MY">DefaultInvoiceType_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInvoiceType_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GSTExemptPrintCode_MY name="GSTExemptPrintCode_MY">GSTExemptPrintCode_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTExemptPrintCode_MY attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTGAFVersion_MY name="GSTGAFVersion_MY">GSTGAFVersion_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTGAFVersion_MY attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTInvoiceFormat_MY name="GSTInvoiceFormat_MY">GSTInvoiceFormat_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTInvoiceFormat_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GSTSummaryDelimiter_MY name="GSTSummaryDelimiter_MY">GSTSummaryDelimiter_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTSummaryDelimiter_MY attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeDelimiterInGSTSummary_MY name="IncludeDelimiterInGSTSummary_MY">IncludeDelimiterInGSTSummary_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeDelimiterInGSTSummary_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncludeTaxCodeInGSTSummary_MY name="IncludeTaxCodeInGSTSummary_MY">IncludeTaxCodeInGSTSummary_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeTaxCodeInGSTSummary_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncludeTaxValueInGSTSummary_MY name="IncludeTaxValueInGSTSummary_MY">IncludeTaxValueInGSTSummary_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeTaxValueInGSTSummary_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseSelfBilledInvoice_MY name="UseSelfBilledInvoice_MY">UseSelfBilledInvoice_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSelfBilledInvoice_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BASFormatMapping_AU name="BASFormatMapping_AU">BASFormatMapping_AU</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BASFormatMapping_AU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GSTAuditFileFormatMapping_MY name="GSTAuditFileFormatMapping_MY">GSTAuditFileFormatMapping_MY</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTAuditFileFormatMapping_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DateForSecondTaxRaise_JP name="DateForSecondTaxRaise_JP">DateForSecondTaxRaise_JP</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateForSecondTaxRaise_JP attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DomesticTaxCancellationERFormatMapping_IT name="DomesticTaxCancellationERFormatMapping_IT">DomesticTaxCancellationERFormatMapping_IT</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticTaxCancellationERFormatMapping_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DomesticTaxAggregatedERFormatMapping_IT name="DomesticTaxAggregatedERFormatMapping_IT">DomesticTaxAggregatedERFormatMapping_IT</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticTaxAggregatedERFormatMapping_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DomesticTaxAnalyticERFormatMapping_IT name="DomesticTaxAnalyticERFormatMapping_IT">DomesticTaxAnalyticERFormatMapping_IT</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticTaxAnalyticERFormatMapping_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxYearlyComERFormatMapping_IT name="TaxYearlyComERFormatMapping_IT">TaxYearlyComERFormatMapping_IT</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxYearlyComERFormatMapping_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#QuarterlyVATComERFormatMapping_IT name="QuarterlyVATComERFormatMapping_IT">QuarterlyVATComERFormatMapping_IT</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuarterlyVATComERFormatMapping_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SAFTAccountingBooksERFormatMapping_PL name="SAFTAccountingBooksERFormatMapping_PL">SAFTAccountingBooksERFormatMapping_PL</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SAFTAccountingBooksERFormatMapping_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SAFTBankStatementERFormatMapping_PL name="SAFTBankStatementERFormatMapping_PL">SAFTBankStatementERFormatMapping_PL</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SAFTBankStatementERFormatMapping_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SAFTInventoryERFormatMapping_PL name="SAFTInventoryERFormatMapping_PL">SAFTInventoryERFormatMapping_PL</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SAFTInventoryERFormatMapping_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SAFTVATSalesPurchERFormatMapping_PL name="SAFTVATSalesPurchERFormatMapping_PL">SAFTVATSalesPurchERFormatMapping_PL</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SAFTVATSalesPurchERFormatMapping_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SAFTVATInvoicesERFormatMapping_PL name="SAFTVATInvoicesERFormatMapping_PL">SAFTVATInvoicesERFormatMapping_PL</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SAFTVATInvoicesERFormatMapping_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdvancedSalesTaxPayment_IN name="AdvancedSalesTaxPayment_IN">AdvancedSalesTaxPayment_IN</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancedSalesTaxPayment_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FactureJournalFormatMappingID name="FactureJournalFormatMappingID">FactureJournalFormatMappingID</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureJournalFormatMappingID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SAFTERFormatMapping_W name="SAFTERFormatMapping_W">SAFTERFormatMapping_W</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SAFTERFormatMapping_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxReportFormatMappingID_UK name="TaxReportFormatMappingID_UK">TaxReportFormatMappingID_UK</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportFormatMappingID_UK attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IndirectTaxERFormatMapping_RU name="IndirectTaxERFormatMapping_RU">IndirectTaxERFormatMapping_RU</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectTaxERFormatMapping_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DelayTaxCalculation name="DelayTaxCalculation">DelayTaxCalculation</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DelayTaxCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxCurConvPath name="TaxCurConvPath">TaxCurConvPath</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCurConvPath attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTaxPayableExchangeRateTypeRelationshipId name="Relationship_SalesTaxPayableExchangeRateTypeRelationshipId">Relationship_SalesTaxPayableExchangeRateTypeRelationshipId</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTaxPayableExchangeRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/ExchangeRateType.md" target="_blank">/core/erp/Tables/Common/Currency/Group/ExchangeRateType.cdm.json/ExchangeRateType</a></td><td><a href="../../../Common/Currency/Group/ExchangeRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTaxReceivableExchangeRateTypeRelationshipId name="Relationship_SalesTaxReceivableExchangeRateTypeRelationshipId">Relationship_SalesTaxReceivableExchangeRateTypeRelationshipId</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTaxReceivableExchangeRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/ExchangeRateType.md" target="_blank">/core/erp/Tables/Common/Currency/Group/ExchangeRateType.cdm.json/ExchangeRateType</a></td><td><a href="../../../Common/Currency/Group/ExchangeRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGroupHeadingRelationshipId name="Relationship_TaxGroupHeadingRelationshipId">Relationship_TaxGroupHeadingRelationshipId</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxItemGroupHeadingRelationshipId name="Relationship_TaxItemGroupHeadingRelationshipId">Relationship_TaxItemGroupHeadingRelationshipId</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxItemGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxItemGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/TaxParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
