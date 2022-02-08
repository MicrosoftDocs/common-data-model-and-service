---
title: TaxCodeEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Sales tax codes in Tax(TaxCodeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxCodeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax codes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TaxCode](#TaxCode)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[NegativeTax](#NegativeTax)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[NotEUSalesList](#NotEUSalesList)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[PaymentTaxCodeId](#PaymentTaxCodeId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[PrintCode](#PrintCode)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxablePurchases](#ReportingCodeTaxablePurchases)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxablePurchasesCreditNote](#ReportingCodeTaxablePurchasesCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxableSales](#ReportingCodeTaxableSales)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxableSalesCreditNote](#ReportingCodeTaxableSalesCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxableImport](#ReportingCodeTaxableImport)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxableImportCreditNote](#ReportingCodeTaxableImportCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxableImportOffset](#ReportingCodeTaxableImportOffset)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxableImportOffsetCreditNote](#ReportingCodeTaxableImportOffsetCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxFreePurchase](#ReportingCodeTaxFreePurchase)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxFreePurchaseCreditNote](#ReportingCodeTaxFreePurchaseCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxFreeSale](#ReportingCodeTaxFreeSale)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxFreeSaleCreditNote](#ReportingCodeTaxFreeSaleCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeSalesTaxReceivable](#ReportingCodeSalesTaxReceivable)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeSalesTaxReceivableCreditNote](#ReportingCodeSalesTaxReceivableCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeSalesTaxPayable](#ReportingCodeSalesTaxPayable)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeSalesTaxPayableCreditNote](#ReportingCodeSalesTaxPayableCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeUseTax](#ReportingCodeUseTax)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeUseTaxCreditNote](#ReportingCodeUseTaxCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeUseTaxOffset](#ReportingCodeUseTaxOffset)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeUseTaxOffsetCreditNote](#ReportingCodeUseTaxOffsetCreditNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxPostingGroupId](#TaxPostingGroupId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxBase](#TaxBase)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxCalculationMethod](#TaxCalculationMethod)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxCountryRegionType](#TaxCountryRegionType)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxCurrencyCodeId](#TaxCurrencyCodeId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[CalculateUnitTaxBeforeSalesTax](#CalculateUnitTaxBeforeSalesTax)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxLimitBase](#TaxLimitBase)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxName](#TaxName)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxOnTax](#TaxOnTax)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[PackingDutySortCode](#PackingDutySortCode)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[PackingDuty](#PackingDuty)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxPeriodId](#TaxPeriodId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxRoundOff](#TaxRoundOff)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxRoundOffType](#TaxRoundOffType)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxUnitId](#TaxUnitId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[PrintCodeType](#PrintCodeType)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportLayout](#ReportLayout)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[IncludedTax](#IncludedTax)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[RetainedTax](#RetainedTax)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxationCode](#TaxationCode)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxationCodeRecId](#TaxationCodeRecId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[FiscalValue](#FiscalValue)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxSubstitutionMethod](#TaxSubstitutionMethod)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[BrazilTaxType](#BrazilTaxType)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[DiotAddInfo](#DiotAddInfo)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[MexicoTaxType](#MexicoTaxType)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxVatReportCategoryRecId](#TaxVatReportCategoryRecId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxVatReportCategoryCode](#TaxVatReportCategoryCode)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[UnrealizedTax](#UnrealizedTax)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[SingaporeTaxType](#SingaporeTaxType)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeBaseIncomingDebitNote](#ReportingCodeBaseIncomingDebitNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeBaseOutgoingDebitNote](#ReportingCodeBaseOutgoingDebitNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxFreeBuyDebitNote](#ReportingCodeTaxFreeBuyDebitNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxFreeSalesDebitNote](#ReportingCodeTaxFreeSalesDebitNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxIncomingDebitNote](#ReportingCodeTaxIncomingDebitNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ReportingCodeTaxOutgoingDebitNote](#ReportingCodeTaxOutgoingDebitNote)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[IsGST](#IsGST)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TypeOfTax](#TypeOfTax)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxType](#TaxType)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[DomesticCustomsPractice](#DomesticCustomsPractice)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[ExcludeFromInvoice](#ExcludeFromInvoice)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[TaxSubstitutionCalculationMethod](#TaxSubstitutionCalculationMethod)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[RevenueCode](#RevenueCode)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[VATChargeSource](#VATChargeSource)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[JapanTaxType](#JapanTaxType)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[DescriptionQRBill](#DescriptionQRBill)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_TaxPeriodIdRelationshipId](#Relationship_TaxPeriodIdRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxablePurchasesRelationshipId](#Relationship_ReportingCodeTaxablePurchasesRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxablePurchasesCreditNoteRelationshipId](#Relationship_ReportingCodeTaxablePurchasesCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxableSalesRelationshipId](#Relationship_ReportingCodeTaxableSalesRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxableSalesCreditNoteRelationshipId](#Relationship_ReportingCodeTaxableSalesCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxableImportRelationshipId](#Relationship_ReportingCodeTaxableImportRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxableImportCreditNoteRelationshipId](#Relationship_ReportingCodeTaxableImportCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxableImportOffsetRelationshipId](#Relationship_ReportingCodeTaxableImportOffsetRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxableImportOffsetCreditNoteRelationshipId](#Relationship_ReportingCodeTaxableImportOffsetCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxFreePurchaseRelationshipId](#Relationship_ReportingCodeTaxFreePurchaseRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxFreePurchaseCreditNoteRelationshipId](#Relationship_ReportingCodeTaxFreePurchaseCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxFreeSaleRelationshipId](#Relationship_ReportingCodeTaxFreeSaleRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxFreeSaleCreditNoteRelationshipId](#Relationship_ReportingCodeTaxFreeSaleCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeSalesTaxReceivableRelationshipId](#Relationship_ReportingCodeSalesTaxReceivableRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeSalesTaxReceivableCreditNoteRelationshipId](#Relationship_ReportingCodeSalesTaxReceivableCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeSalesTaxPayableRelationshipId](#Relationship_ReportingCodeSalesTaxPayableRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeSalesTaxPayableCreditNoteRelationshipId](#Relationship_ReportingCodeSalesTaxPayableCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeUseTaxRelationshipId](#Relationship_ReportingCodeUseTaxRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeUseTaxCreditNoteRelationshipId](#Relationship_ReportingCodeUseTaxCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeUseTaxOffsetRelationshipId](#Relationship_ReportingCodeUseTaxOffsetRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeUseTaxOffsetCreditNoteRelationshipId](#Relationship_ReportingCodeUseTaxOffsetCreditNoteRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeBaseIncomingDebitNote_MYRelationshipId](#Relationship_ReportingCodeBaseIncomingDebitNote_MYRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeBaseOutgoingDebitNote_MYRelationshipId](#Relationship_ReportingCodeBaseOutgoingDebitNote_MYRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxFreeBuy_MYRelationshipId](#Relationship_ReportingCodeTaxFreeBuy_MYRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxFreeSales_MYRelationshipId](#Relationship_ReportingCodeTaxFreeSales_MYRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxIncomingDebitNote_MYRelationshipId](#Relationship_ReportingCodeTaxIncomingDebitNote_MYRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_ReportingCodeTaxOutgoingDebitNote_MYRelationshipId](#Relationship_ReportingCodeTaxOutgoingDebitNote_MYRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[BackingTable_TaxTableRelationshipId](#BackingTable_TaxTableRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxCodeEntity.md" target="_blank">Tax/TaxCodeEntity</a>|

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NegativeTax name="NegativeTax">NegativeTax</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NegativeTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NotEUSalesList name="NotEUSalesList">NotEUSalesList</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Excluded</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotEUSalesList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Excluded</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTaxCodeId name="PaymentTaxCodeId">PaymentTaxCodeId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment sales tax code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTaxCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment sales tax code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintCode name="PrintCode">PrintCode</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxablePurchases name="ReportingCodeTaxablePurchases">ReportingCodeTaxablePurchases</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable purchases</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxablePurchases attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable purchases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxablePurchasesCreditNote name="ReportingCodeTaxablePurchasesCreditNote">ReportingCodeTaxablePurchasesCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable purchase credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxablePurchasesCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable purchase credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxableSales name="ReportingCodeTaxableSales">ReportingCodeTaxableSales</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable sales</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxableSales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxableSalesCreditNote name="ReportingCodeTaxableSalesCreditNote">ReportingCodeTaxableSalesCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable sales credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxableSalesCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable sales credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxableImport name="ReportingCodeTaxableImport">ReportingCodeTaxableImport</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable import</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxableImport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable import</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxableImportCreditNote name="ReportingCodeTaxableImportCreditNote">ReportingCodeTaxableImportCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable import credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxableImportCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable import credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxableImportOffset name="ReportingCodeTaxableImportOffset">ReportingCodeTaxableImportOffset</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset taxable import</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxableImportOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset taxable import</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxableImportOffsetCreditNote name="ReportingCodeTaxableImportOffsetCreditNote">ReportingCodeTaxableImportOffsetCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset taxable import credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxableImportOffsetCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset taxable import credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxFreePurchase name="ReportingCodeTaxFreePurchase">ReportingCodeTaxFreePurchase</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax-free purchase</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxFreePurchase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax-free purchase</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxFreePurchaseCreditNote name="ReportingCodeTaxFreePurchaseCreditNote">ReportingCodeTaxFreePurchaseCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax exempt purchase credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxFreePurchaseCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax exempt purchase credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxFreeSale name="ReportingCodeTaxFreeSale">ReportingCodeTaxFreeSale</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax-free sale</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxFreeSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax-free sale</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxFreeSaleCreditNote name="ReportingCodeTaxFreeSaleCreditNote">ReportingCodeTaxFreeSaleCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax exempt sales credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxFreeSaleCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax exempt sales credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeSalesTaxReceivable name="ReportingCodeSalesTaxReceivable">ReportingCodeSalesTaxReceivable</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeSalesTaxReceivable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeSalesTaxReceivableCreditNote name="ReportingCodeSalesTaxReceivableCreditNote">ReportingCodeSalesTaxReceivableCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on purchase credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeSalesTaxReceivableCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on purchase credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeSalesTaxPayable name="ReportingCodeSalesTaxPayable">ReportingCodeSalesTaxPayable</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax payable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeSalesTaxPayable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax payable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeSalesTaxPayableCreditNote name="ReportingCodeSalesTaxPayableCreditNote">ReportingCodeSalesTaxPayableCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on sales credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeSalesTaxPayableCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on sales credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeUseTax name="ReportingCodeUseTax">ReportingCodeUseTax</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeUseTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeUseTaxCreditNote name="ReportingCodeUseTaxCreditNote">ReportingCodeUseTaxCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on import credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeUseTaxCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on import credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeUseTaxOffset name="ReportingCodeUseTaxOffset">ReportingCodeUseTaxOffset</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset use tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeUseTaxOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset use tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeUseTaxOffsetCreditNote name="ReportingCodeUseTaxOffsetCreditNote">ReportingCodeUseTaxOffsetCreditNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset sales tax on import credit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeUseTaxOffsetCreditNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset sales tax on import credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPostingGroupId name="TaxPostingGroupId">TaxPostingGroupId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPostingGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBase name="TaxBase">TaxBase</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCalculationMethod name="TaxCalculationMethod">TaxCalculationMethod</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculation method</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculation method</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCountryRegionType name="TaxCountryRegionType">TaxCountryRegionType</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCountryRegionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCurrencyCodeId name="TaxCurrencyCodeId">TaxCurrencyCodeId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCurrencyCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculateUnitTaxBeforeSalesTax name="CalculateUnitTaxBeforeSalesTax">CalculateUnitTaxBeforeSalesTax</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateUnitTaxBeforeSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxLimitBase name="TaxLimitBase">TaxLimitBase</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxLimitBase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxName name="TaxName">TaxName</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOnTax name="TaxOnTax">TaxOnTax</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on sales tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOnTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingDutySortCode name="PackingDutySortCode">PackingDutySortCode</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingDutySortCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingDuty name="PackingDuty">PackingDuty</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingDuty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPeriodId name="TaxPeriodId">TaxPeriodId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPeriodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRoundOff name="TaxRoundOff">TaxRoundOff</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRoundOff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRoundOffType name="TaxRoundOffType">TaxRoundOffType</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRoundOffType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxUnitId name="TaxUnitId">TaxUnitId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintCodeType name="PrintCodeType">PrintCodeType</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCodeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportLayout name="ReportLayout">ReportLayout</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludedTax name="IncludedTax">IncludedTax</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Included tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludedTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Included tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetainedTax name="RetainedTax">RetainedTax</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retained tax/to recuperate</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetainedTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retained tax/to recuperate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxationCode name="TaxationCode">TaxationCode</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxationCodeRecId name="TaxationCodeRecId">TaxationCodeRecId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationCodeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalValue name="FiscalValue">FiscalValue</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxSubstitutionMethod name="TaxSubstitutionMethod">TaxSubstitutionMethod</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSubstitutionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilTaxType name="BrazilTaxType">BrazilTaxType</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilTaxType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiotAddInfo name="DiotAddInfo">DiotAddInfo</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiotAddInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MexicoTaxType name="MexicoTaxType">MexicoTaxType</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MexicoTaxType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxVatReportCategoryRecId name="TaxVatReportCategoryRecId">TaxVatReportCategoryRecId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax category report</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxVatReportCategoryRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax category report</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxVatReportCategoryCode name="TaxVatReportCategoryCode">TaxVatReportCategoryCode</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxVatReportCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedTax name="UnrealizedTax">UnrealizedTax</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unrealized tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unrealized tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SingaporeTaxType name="SingaporeTaxType">SingaporeTaxType</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SingaporeTaxType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeBaseIncomingDebitNote name="ReportingCodeBaseIncomingDebitNote">ReportingCodeBaseIncomingDebitNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable purchase debit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeBaseIncomingDebitNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable purchase debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeBaseOutgoingDebitNote name="ReportingCodeBaseOutgoingDebitNote">ReportingCodeBaseOutgoingDebitNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable sales debit notes</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeBaseOutgoingDebitNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable sales debit notes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxFreeBuyDebitNote name="ReportingCodeTaxFreeBuyDebitNote">ReportingCodeTaxFreeBuyDebitNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax exempt purchase debit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxFreeBuyDebitNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax exempt purchase debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxFreeSalesDebitNote name="ReportingCodeTaxFreeSalesDebitNote">ReportingCodeTaxFreeSalesDebitNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax exempt sales debit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxFreeSalesDebitNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax exempt sales debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxIncomingDebitNote name="ReportingCodeTaxIncomingDebitNote">ReportingCodeTaxIncomingDebitNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on purchase debit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxIncomingDebitNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on purchase debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCodeTaxOutgoingDebitNote name="ReportingCodeTaxOutgoingDebitNote">ReportingCodeTaxOutgoingDebitNote</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on sales debit note</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCodeTaxOutgoingDebitNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on sales debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsGST name="IsGST">IsGST</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeOfTax name="TypeOfTax">TypeOfTax</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeOfTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DomesticCustomsPractice name="DomesticCustomsPractice">DomesticCustomsPractice</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticCustomsPractice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeFromInvoice name="ExcludeFromInvoice">ExcludeFromInvoice</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeFromInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxSubstitutionCalculationMethod name="TaxSubstitutionCalculationMethod">TaxSubstitutionCalculationMethod</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSubstitutionCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueCode name="RevenueCode">RevenueCode</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATChargeSource name="VATChargeSource">VATChargeSource</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATChargeSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JapanTaxType name="JapanTaxType">JapanTaxType</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JapanTaxType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DescriptionQRBill name="DescriptionQRBill">DescriptionQRBill</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DescriptionQRBill attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxPeriodIdRelationshipId name="Relationship_TaxPeriodIdRelationshipId">Relationship_TaxPeriodIdRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxPeriodIdRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxablePurchasesRelationshipId name="Relationship_ReportingCodeTaxablePurchasesRelationshipId">Relationship_ReportingCodeTaxablePurchasesRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxablePurchasesRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxablePurchasesCreditNoteRelationshipId name="Relationship_ReportingCodeTaxablePurchasesCreditNoteRelationshipId">Relationship_ReportingCodeTaxablePurchasesCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxablePurchasesCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxableSalesRelationshipId name="Relationship_ReportingCodeTaxableSalesRelationshipId">Relationship_ReportingCodeTaxableSalesRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxableSalesRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxableSalesCreditNoteRelationshipId name="Relationship_ReportingCodeTaxableSalesCreditNoteRelationshipId">Relationship_ReportingCodeTaxableSalesCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxableSalesCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxableImportRelationshipId name="Relationship_ReportingCodeTaxableImportRelationshipId">Relationship_ReportingCodeTaxableImportRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxableImportRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxableImportCreditNoteRelationshipId name="Relationship_ReportingCodeTaxableImportCreditNoteRelationshipId">Relationship_ReportingCodeTaxableImportCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxableImportCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxableImportOffsetRelationshipId name="Relationship_ReportingCodeTaxableImportOffsetRelationshipId">Relationship_ReportingCodeTaxableImportOffsetRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxableImportOffsetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxableImportOffsetCreditNoteRelationshipId name="Relationship_ReportingCodeTaxableImportOffsetCreditNoteRelationshipId">Relationship_ReportingCodeTaxableImportOffsetCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxableImportOffsetCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxFreePurchaseRelationshipId name="Relationship_ReportingCodeTaxFreePurchaseRelationshipId">Relationship_ReportingCodeTaxFreePurchaseRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxFreePurchaseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxFreePurchaseCreditNoteRelationshipId name="Relationship_ReportingCodeTaxFreePurchaseCreditNoteRelationshipId">Relationship_ReportingCodeTaxFreePurchaseCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxFreePurchaseCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxFreeSaleRelationshipId name="Relationship_ReportingCodeTaxFreeSaleRelationshipId">Relationship_ReportingCodeTaxFreeSaleRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxFreeSaleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxFreeSaleCreditNoteRelationshipId name="Relationship_ReportingCodeTaxFreeSaleCreditNoteRelationshipId">Relationship_ReportingCodeTaxFreeSaleCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxFreeSaleCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeSalesTaxReceivableRelationshipId name="Relationship_ReportingCodeSalesTaxReceivableRelationshipId">Relationship_ReportingCodeSalesTaxReceivableRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeSalesTaxReceivableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeSalesTaxReceivableCreditNoteRelationshipId name="Relationship_ReportingCodeSalesTaxReceivableCreditNoteRelationshipId">Relationship_ReportingCodeSalesTaxReceivableCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeSalesTaxReceivableCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeSalesTaxPayableRelationshipId name="Relationship_ReportingCodeSalesTaxPayableRelationshipId">Relationship_ReportingCodeSalesTaxPayableRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeSalesTaxPayableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeSalesTaxPayableCreditNoteRelationshipId name="Relationship_ReportingCodeSalesTaxPayableCreditNoteRelationshipId">Relationship_ReportingCodeSalesTaxPayableCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeSalesTaxPayableCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeUseTaxRelationshipId name="Relationship_ReportingCodeUseTaxRelationshipId">Relationship_ReportingCodeUseTaxRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeUseTaxRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeUseTaxCreditNoteRelationshipId name="Relationship_ReportingCodeUseTaxCreditNoteRelationshipId">Relationship_ReportingCodeUseTaxCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeUseTaxCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeUseTaxOffsetRelationshipId name="Relationship_ReportingCodeUseTaxOffsetRelationshipId">Relationship_ReportingCodeUseTaxOffsetRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeUseTaxOffsetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeUseTaxOffsetCreditNoteRelationshipId name="Relationship_ReportingCodeUseTaxOffsetCreditNoteRelationshipId">Relationship_ReportingCodeUseTaxOffsetCreditNoteRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeUseTaxOffsetCreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeBaseIncomingDebitNote_MYRelationshipId name="Relationship_ReportingCodeBaseIncomingDebitNote_MYRelationshipId">Relationship_ReportingCodeBaseIncomingDebitNote_MYRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeBaseIncomingDebitNote_MYRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeBaseOutgoingDebitNote_MYRelationshipId name="Relationship_ReportingCodeBaseOutgoingDebitNote_MYRelationshipId">Relationship_ReportingCodeBaseOutgoingDebitNote_MYRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeBaseOutgoingDebitNote_MYRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxFreeBuy_MYRelationshipId name="Relationship_ReportingCodeTaxFreeBuy_MYRelationshipId">Relationship_ReportingCodeTaxFreeBuy_MYRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxFreeBuy_MYRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxFreeSales_MYRelationshipId name="Relationship_ReportingCodeTaxFreeSales_MYRelationshipId">Relationship_ReportingCodeTaxFreeSales_MYRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxFreeSales_MYRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxIncomingDebitNote_MYRelationshipId name="Relationship_ReportingCodeTaxIncomingDebitNote_MYRelationshipId">Relationship_ReportingCodeTaxIncomingDebitNote_MYRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxIncomingDebitNote_MYRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCodeTaxOutgoingDebitNote_MYRelationshipId name="Relationship_ReportingCodeTaxOutgoingDebitNote_MYRelationshipId">Relationship_ReportingCodeTaxOutgoingDebitNote_MYRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCodeTaxOutgoingDebitNote_MYRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TaxTableRelationshipId name="BackingTable_TaxTableRelationshipId">BackingTable_TaxTableRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../../Tables/Finance/Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/TaxCodeEntity (this entity)  

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
