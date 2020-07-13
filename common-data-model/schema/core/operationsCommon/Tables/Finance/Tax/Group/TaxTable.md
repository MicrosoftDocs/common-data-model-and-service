---
title: TaxTable in Group - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Sales tax codes in Group(TaxTable)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax codes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxCode](#TaxCode)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[BusinessType_LV](#BusinessType_LV)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[CustomCalcMethod_RU](#CustomCalcMethod_RU)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[CustomChargeType_RU](#CustomChargeType_RU)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[CustomCombinedRate_RU](#CustomCombinedRate_RU)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[CustomsPractice_FI](#CustomsPractice_FI)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[CustomUnitId_RU](#CustomUnitId_RU)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[DiotAddInfo_MX](#DiotAddInfo_MX)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[DomesticMarketTaxCode_RU](#DomesticMarketTaxCode_RU)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[ExcludeFromInvoice](#ExcludeFromInvoice)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[IncludedTax_BR](#IncludedTax_BR)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[NegativeTax](#NegativeTax)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[NotEUSalesList](#NotEUSalesList)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[PaymentTaxCode](#PaymentTaxCode)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[PrintCode](#PrintCode)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseIncoming](#RepFieldBaseIncoming)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseIncomingCreditNote](#RepFieldBaseIncomingCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseIncomingDebitNote_MY](#RepFieldBaseIncomingDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseOutgoing](#RepFieldBaseOutgoing)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseOutgoingCreditNote](#RepFieldBaseOutgoingCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseOutgoingDebitNote_MY](#RepFieldBaseOutgoingDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseUseTax](#RepFieldBaseUseTax)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseUseTaxCreditNote](#RepFieldBaseUseTaxCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseUseTaxOffset](#RepFieldBaseUseTaxOffset)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseUseTaxOffsetCreditNote](#RepFieldBaseUseTaxOffsetCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxFreeBuy](#RepFieldTaxFreeBuy)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxFreeBuyCreditNote](#RepFieldTaxFreeBuyCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxFreeBuyDebitNote_MY](#RepFieldTaxFreeBuyDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxFreeSales](#RepFieldTaxFreeSales)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxFreeSalesCreditNote](#RepFieldTaxFreeSalesCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxFreeSalesDebitNote_MY](#RepFieldTaxFreeSalesDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxIncoming](#RepFieldTaxIncoming)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxIncomingCreditNote](#RepFieldTaxIncomingCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxIncomingDebitNote_MY](#RepFieldTaxIncomingDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxOutgoing](#RepFieldTaxOutgoing)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxOutgoingCreditNote](#RepFieldTaxOutgoingCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldTaxOutgoingDebitNote_MY](#RepFieldTaxOutgoingDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldUseTax](#RepFieldUseTax)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldUseTaxCreditNote](#RepFieldUseTaxCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldUseTaxOffset](#RepFieldUseTaxOffset)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldUseTaxOffsetCreditNote](#RepFieldUseTaxOffsetCreditNote)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RetainedTax_BR](#RetainedTax_BR)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxAccountGroup](#TaxAccountGroup)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxationCodeTable_BR](#TaxationCodeTable_BR)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxBase](#TaxBase)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxBorderNumReq_FI](#TaxBorderNumReq_FI)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxCalcMethod](#TaxCalcMethod)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxComponentTable_IN](#TaxComponentTable_IN)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxCountryRegionType](#TaxCountryRegionType)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxCurrencyCode](#TaxCurrencyCode)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxIncludeInTax](#TaxIncludeInTax)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxJurisdictionCode](#TaxJurisdictionCode)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxLedgerAccountGroup_IN](#TaxLedgerAccountGroup_IN)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxLimitBase](#TaxLimitBase)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxName](#TaxName)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxOnTax](#TaxOnTax)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxPackagingSort](#TaxPackagingSort)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxPackagingTax](#TaxPackagingTax)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxPeriod](#TaxPeriod)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxPurchaseTax](#TaxPurchaseTax)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxRoundOff](#TaxRoundOff)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxRoundOffType](#TaxRoundOffType)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxSubstitution_BR](#TaxSubstitution_BR)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxType_BR](#TaxType_BR)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxType_JP](#TaxType_JP)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxType_IN](#TaxType_IN)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxType_IT](#TaxType_IT)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxType_MX](#TaxType_MX)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxType_SG](#TaxType_SG)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxType_TH](#TaxType_TH)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxType_W](#TaxType_W)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxUnit](#TaxUnit)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxValueQty_RU](#TaxValueQty_RU)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxVatReportCategory_MX](#TaxVatReportCategory_MX)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxWriteSelection](#TaxWriteSelection)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[UnrealizedTax](#UnrealizedTax)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[VATChargeSource_RU](#VATChargeSource_RU)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[VATOperationCode_RU](#VATOperationCode_RU)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[TaxSubstitutionBaseRedCalcMode_BR](#TaxSubstitutionBaseRedCalcMode_BR)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[IsGST_MY](#IsGST_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseUseTaxDebitNote_MY](#RepFieldBaseUseTaxDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldBaseUseTaxOffsetDebitNote_MY](#RepFieldBaseUseTaxOffsetDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldUseTaxDebitNote_MY](#RepFieldUseTaxDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RepFieldUseTaxOffsetDebitNote_MY](#RepFieldUseTaxOffsetDebitNote_MY)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RetailSAFTStandardVATCode](#RetailSAFTStandardVATCode)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RetailPrintCode](#RetailPrintCode)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[RevenueCode_BR](#RevenueCode_BR)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[AffectPlafond_IT](#AffectPlafond_IT)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[DescriptionQRBill_CH](#DescriptionQRBill_CH)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxationCodeTable_BRRelationshipId](#Relationship_TaxationCodeTable_BRRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxComponentTable_INRelationshipId](#Relationship_TaxComponentTable_INRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxJurisdictionRelationshipId](#Relationship_TaxJurisdictionRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxLedgerAccountGroupRelationshipId](#Relationship_TaxLedgerAccountGroupRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxLedgerAccountGroup_INRelationshipId](#Relationship_TaxLedgerAccountGroup_INRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxPeriodHeadRelationshipId](#Relationship_TaxPeriodHeadRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseIncomingRelationshipId](#Relationship_TaxReportCollection_BaseIncomingRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseIncomingCreditNoRelationshipId](#Relationship_TaxReportCollection_BaseIncomingCreditNoRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseIncomingDebit_MYRelationshipId](#Relationship_TaxReportCollection_BaseIncomingDebit_MYRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseOutgoingRelationshipId](#Relationship_TaxReportCollection_BaseOutgoingRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseOutgoingCreditNoRelationshipId](#Relationship_TaxReportCollection_BaseOutgoingCreditNoRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseOutgoingDebit_MYRelationshipId](#Relationship_TaxReportCollection_BaseOutgoingDebit_MYRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseUseTaxRelationshipId](#Relationship_TaxReportCollection_BaseUseTaxRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseUseTaxCreditNoteRelationshipId](#Relationship_TaxReportCollection_BaseUseTaxCreditNoteRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseUseTaxOffsetRelationshipId](#Relationship_TaxReportCollection_BaseUseTaxOffsetRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_BaseUseTaxOffsetCredRelationshipId](#Relationship_TaxReportCollection_BaseUseTaxOffsetCredRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxFreeBuyRelationshipId](#Relationship_TaxReportCollection_TaxFreeBuyRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxFreeBuyCreditNoteRelationshipId](#Relationship_TaxReportCollection_TaxFreeBuyCreditNoteRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxFreeBuyDebitN_MYRelationshipId](#Relationship_TaxReportCollection_TaxFreeBuyDebitN_MYRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxFreeSalesRelationshipId](#Relationship_TaxReportCollection_TaxFreeSalesRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxFreeSalesCreditNoRelationshipId](#Relationship_TaxReportCollection_TaxFreeSalesCreditNoRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxFreeSalesDebit_MYRelationshipId](#Relationship_TaxReportCollection_TaxFreeSalesDebit_MYRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxIncomingRelationshipId](#Relationship_TaxReportCollection_TaxIncomingRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxIncomingCreditNotRelationshipId](#Relationship_TaxReportCollection_TaxIncomingCreditNotRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxIncomingDebitN_MYRelationshipId](#Relationship_TaxReportCollection_TaxIncomingDebitN_MYRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxOutgoingRelationshipId](#Relationship_TaxReportCollection_TaxOutgoingRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxOutgoingCreditNotRelationshipId](#Relationship_TaxReportCollection_TaxOutgoingCreditNotRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_TaxOutgoingDebitN_MYRelationshipId](#Relationship_TaxReportCollection_TaxOutgoingDebitN_MYRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_UseTaxRelationshipId](#Relationship_TaxReportCollection_UseTaxRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_UseTaxCreditNoteRelationshipId](#Relationship_TaxReportCollection_UseTaxCreditNoteRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_UseTaxOffsetRelationshipId](#Relationship_TaxReportCollection_UseTaxOffsetRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxReportCollection_UseTaxOffsetCreditNoRelationshipId](#Relationship_TaxReportCollection_UseTaxOffsetCreditNoRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_TaxVatReportCategory_MXRelationshipId](#Relationship_TaxVatReportCategory_MXRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_VATOperationCodeTable_RURelationshipId](#Relationship_VATOperationCodeTable_RURelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxTable.md" target="_blank">Group/TaxTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessType_LV name="BusinessType_LV">BusinessType_LV</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessType_LV attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustomCalcMethod_RU name="CustomCalcMethod_RU">CustomCalcMethod_RU</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomCalcMethod_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustomChargeType_RU name="CustomChargeType_RU">CustomChargeType_RU</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomChargeType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustomCombinedRate_RU name="CustomCombinedRate_RU">CustomCombinedRate_RU</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomCombinedRate_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustomsPractice_FI name="CustomsPractice_FI">CustomsPractice_FI</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsPractice_FI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustomUnitId_RU name="CustomUnitId_RU">CustomUnitId_RU</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomUnitId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiotAddInfo_MX name="DiotAddInfo_MX">DiotAddInfo_MX</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiotAddInfo_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DomesticMarketTaxCode_RU name="DomesticMarketTaxCode_RU">DomesticMarketTaxCode_RU</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax code for domestic market</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticMarketTaxCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax code for domestic market</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeFromInvoice name="ExcludeFromInvoice">ExcludeFromInvoice</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeFromInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IncludedTax_BR name="IncludedTax_BR">IncludedTax_BR</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Included tax</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludedTax_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Included tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#NegativeTax name="NegativeTax">NegativeTax</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NegativeTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NotEUSalesList name="NotEUSalesList">NotEUSalesList</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Excluded</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotEUSalesList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Excluded</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PaymentTaxCode name="PaymentTaxCode">PaymentTaxCode</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment sales tax code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTaxCode attribute are listed below.</summary>

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

First included in: Group/TaxTable (this entity)  

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

### <a href=#RepFieldBaseIncoming name="RepFieldBaseIncoming">RepFieldBaseIncoming</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable purchases</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseIncoming attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable purchases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseIncomingCreditNote name="RepFieldBaseIncomingCreditNote">RepFieldBaseIncomingCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable purchase credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseIncomingCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable purchase credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseIncomingDebitNote_MY name="RepFieldBaseIncomingDebitNote_MY">RepFieldBaseIncomingDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable purchase debit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseIncomingDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable purchase debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseOutgoing name="RepFieldBaseOutgoing">RepFieldBaseOutgoing</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable sales</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseOutgoing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseOutgoingCreditNote name="RepFieldBaseOutgoingCreditNote">RepFieldBaseOutgoingCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable sales credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseOutgoingCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable sales credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseOutgoingDebitNote_MY name="RepFieldBaseOutgoingDebitNote_MY">RepFieldBaseOutgoingDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable sales debit notes</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseOutgoingDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable sales debit notes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseUseTax name="RepFieldBaseUseTax">RepFieldBaseUseTax</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable import</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseUseTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable import</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseUseTaxCreditNote name="RepFieldBaseUseTaxCreditNote">RepFieldBaseUseTaxCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable import credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseUseTaxCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable import credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseUseTaxOffset name="RepFieldBaseUseTaxOffset">RepFieldBaseUseTaxOffset</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset taxable import</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseUseTaxOffset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset taxable import</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseUseTaxOffsetCreditNote name="RepFieldBaseUseTaxOffsetCreditNote">RepFieldBaseUseTaxOffsetCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset taxable import credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseUseTaxOffsetCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset taxable import credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxFreeBuy name="RepFieldTaxFreeBuy">RepFieldTaxFreeBuy</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax-free purchase</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxFreeBuy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax-free purchase</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxFreeBuyCreditNote name="RepFieldTaxFreeBuyCreditNote">RepFieldTaxFreeBuyCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax exempt purchase credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxFreeBuyCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax exempt purchase credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxFreeBuyDebitNote_MY name="RepFieldTaxFreeBuyDebitNote_MY">RepFieldTaxFreeBuyDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax exempt purchase debit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxFreeBuyDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax exempt purchase debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxFreeSales name="RepFieldTaxFreeSales">RepFieldTaxFreeSales</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax-free sale</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxFreeSales attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax-free sale</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxFreeSalesCreditNote name="RepFieldTaxFreeSalesCreditNote">RepFieldTaxFreeSalesCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax exempt sales credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxFreeSalesCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax exempt sales credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxFreeSalesDebitNote_MY name="RepFieldTaxFreeSalesDebitNote_MY">RepFieldTaxFreeSalesDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax exempt sales debit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxFreeSalesDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax exempt sales debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxIncoming name="RepFieldTaxIncoming">RepFieldTaxIncoming</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxIncoming attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxIncomingCreditNote name="RepFieldTaxIncomingCreditNote">RepFieldTaxIncomingCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on purchase credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxIncomingCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on purchase credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxIncomingDebitNote_MY name="RepFieldTaxIncomingDebitNote_MY">RepFieldTaxIncomingDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on purchase debit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxIncomingDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on purchase debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxOutgoing name="RepFieldTaxOutgoing">RepFieldTaxOutgoing</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax payable</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxOutgoing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax payable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxOutgoingCreditNote name="RepFieldTaxOutgoingCreditNote">RepFieldTaxOutgoingCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on sales credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxOutgoingCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on sales credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldTaxOutgoingDebitNote_MY name="RepFieldTaxOutgoingDebitNote_MY">RepFieldTaxOutgoingDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on sales debit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldTaxOutgoingDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on sales debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldUseTax name="RepFieldUseTax">RepFieldUseTax</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use tax</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldUseTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldUseTaxCreditNote name="RepFieldUseTaxCreditNote">RepFieldUseTaxCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on import credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldUseTaxCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on import credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldUseTaxOffset name="RepFieldUseTaxOffset">RepFieldUseTaxOffset</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset use tax</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldUseTaxOffset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset use tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldUseTaxOffsetCreditNote name="RepFieldUseTaxOffsetCreditNote">RepFieldUseTaxOffsetCreditNote</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset sales tax on import credit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldUseTaxOffsetCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset sales tax on import credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RetainedTax_BR name="RetainedTax_BR">RetainedTax_BR</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retained tax/to recuperate</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetainedTax_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retained tax/to recuperate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxAccountGroup name="TaxAccountGroup">TaxAccountGroup</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAccountGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxationCodeTable_BR name="TaxationCodeTable_BR">TaxationCodeTable_BR</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxation code</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationCodeTable_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxation code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxBase name="TaxBase">TaxBase</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBase attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxBorderNumReq_FI name="TaxBorderNumReq_FI">TaxBorderNumReq_FI</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBorderNumReq_FI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxCalcMethod name="TaxCalcMethod">TaxCalcMethod</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculation method</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCalcMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculation method</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxComponentTable_IN name="TaxComponentTable_IN">TaxComponentTable_IN</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax component</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxComponentTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax component</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxCountryRegionType name="TaxCountryRegionType">TaxCountryRegionType</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCountryRegionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxCurrencyCode name="TaxCurrencyCode">TaxCurrencyCode</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIncludeInTax name="TaxIncludeInTax">TaxIncludeInTax</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncludeInTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxJurisdictionCode name="TaxJurisdictionCode">TaxJurisdictionCode</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxJurisdictionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxLedgerAccountGroup_IN name="TaxLedgerAccountGroup_IN">TaxLedgerAccountGroup_IN</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax ledger posting group</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxLedgerAccountGroup_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax ledger posting group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxLimitBase name="TaxLimitBase">TaxLimitBase</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxLimitBase attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxName name="TaxName">TaxName</a>

First included in: Group/TaxTable (this entity)  

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

First included in: Group/TaxTable (this entity)  

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

### <a href=#TaxPackagingSort name="TaxPackagingSort">TaxPackagingSort</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPackagingSort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPackagingTax name="TaxPackagingTax">TaxPackagingTax</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPackagingTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxPeriod name="TaxPeriod">TaxPeriod</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPurchaseTax name="TaxPurchaseTax">TaxPurchaseTax</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPurchaseTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxRoundOff name="TaxRoundOff">TaxRoundOff</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRoundOff attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxRoundOffType name="TaxRoundOffType">TaxRoundOffType</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRoundOffType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxSubstitution_BR name="TaxSubstitution_BR">TaxSubstitution_BR</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSubstitution_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxType_BR name="TaxType_BR">TaxType_BR</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxType_JP name="TaxType_JP">TaxType_JP</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxType_IN name="TaxType_IN">TaxType_IN</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxType_IT name="TaxType_IT">TaxType_IT</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxType_MX name="TaxType_MX">TaxType_MX</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxType_SG name="TaxType_SG">TaxType_SG</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_SG attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxType_TH name="TaxType_TH">TaxType_TH</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxType_W name="TaxType_W">TaxType_W</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxUnit name="TaxUnit">TaxUnit</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxValueQty_RU name="TaxValueQty_RU">TaxValueQty_RU</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxValueQty_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxVatReportCategory_MX name="TaxVatReportCategory_MX">TaxVatReportCategory_MX</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax category report</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxVatReportCategory_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax category report</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWriteSelection name="TaxWriteSelection">TaxWriteSelection</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWriteSelection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UnrealizedTax name="UnrealizedTax">UnrealizedTax</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unrealized tax</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unrealized tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#VATChargeSource_RU name="VATChargeSource_RU">VATChargeSource_RU</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATChargeSource_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VATOperationCode_RU name="VATOperationCode_RU">VATOperationCode_RU</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATOperationCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxSubstitutionBaseRedCalcMode_BR name="TaxSubstitutionBaseRedCalcMode_BR">TaxSubstitutionBaseRedCalcMode_BR</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSubstitutionBaseRedCalcMode_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsGST_MY name="IsGST_MY">IsGST_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GST</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGST_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>GST</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseUseTaxDebitNote_MY name="RepFieldBaseUseTaxDebitNote_MY">RepFieldBaseUseTaxDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable import debit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseUseTaxDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable import debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldBaseUseTaxOffsetDebitNote_MY name="RepFieldBaseUseTaxOffsetDebitNote_MY">RepFieldBaseUseTaxOffsetDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset taxable import debit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldBaseUseTaxOffsetDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset taxable import debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldUseTaxDebitNote_MY name="RepFieldUseTaxDebitNote_MY">RepFieldUseTaxDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax on import debit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldUseTaxDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax on import debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RepFieldUseTaxOffsetDebitNote_MY name="RepFieldUseTaxOffsetDebitNote_MY">RepFieldUseTaxOffsetDebitNote_MY</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset sales tax on import debit note</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepFieldUseTaxOffsetDebitNote_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset sales tax on import debit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RetailSAFTStandardVATCode name="RetailSAFTStandardVATCode">RetailSAFTStandardVATCode</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailSAFTStandardVATCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPrintCode name="RetailPrintCode">RetailPrintCode</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPrintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueCode_BR name="RevenueCode_BR">RevenueCode_BR</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AffectPlafond_IT name="AffectPlafond_IT">AffectPlafond_IT</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AffectPlafond_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DescriptionQRBill_CH name="DescriptionQRBill_CH">DescriptionQRBill_CH</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DescriptionQRBill_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/TaxTable (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxationCodeTable_BRRelationshipId name="Relationship_TaxationCodeTable_BRRelationshipId">Relationship_TaxationCodeTable_BRRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxationCodeTable_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxationCodeTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxationCodeTable_BR.cdm.json/TaxationCodeTable_BR</a></td><td><a href="TaxationCodeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxComponentTable_INRelationshipId name="Relationship_TaxComponentTable_INRelationshipId">Relationship_TaxComponentTable_INRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxComponentTable_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxComponentTable_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxComponentTable_IN.cdm.json/TaxComponentTable_IN</a></td><td><a href="../Main/TaxComponentTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxJurisdictionRelationshipId name="Relationship_TaxJurisdictionRelationshipId">Relationship_TaxJurisdictionRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxJurisdictionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxJurisdiction.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxJurisdiction.cdm.json/TaxJurisdiction</a></td><td><a href="TaxJurisdiction.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxLedgerAccountGroupRelationshipId name="Relationship_TaxLedgerAccountGroupRelationshipId">Relationship_TaxLedgerAccountGroupRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxLedgerAccountGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxLedgerAccountGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxLedgerAccountGroup.cdm.json/TaxLedgerAccountGroup</a></td><td><a href="TaxLedgerAccountGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxLedgerAccountGroup_INRelationshipId name="Relationship_TaxLedgerAccountGroup_INRelationshipId">Relationship_TaxLedgerAccountGroup_INRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxLedgerAccountGroup_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxLedgerAccountGroup_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxLedgerAccountGroup_IN.cdm.json/TaxLedgerAccountGroup_IN</a></td><td><a href="../Main/TaxLedgerAccountGroup_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxPeriodHeadRelationshipId name="Relationship_TaxPeriodHeadRelationshipId">Relationship_TaxPeriodHeadRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxPeriodHeadRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxPeriodHead.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxPeriodHead.cdm.json/TaxPeriodHead</a></td><td><a href="TaxPeriodHead.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseIncomingRelationshipId name="Relationship_TaxReportCollection_BaseIncomingRelationshipId">Relationship_TaxReportCollection_BaseIncomingRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseIncomingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseIncomingCreditNoRelationshipId name="Relationship_TaxReportCollection_BaseIncomingCreditNoRelationshipId">Relationship_TaxReportCollection_BaseIncomingCreditNoRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseIncomingCreditNoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseIncomingDebit_MYRelationshipId name="Relationship_TaxReportCollection_BaseIncomingDebit_MYRelationshipId">Relationship_TaxReportCollection_BaseIncomingDebit_MYRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseIncomingDebit_MYRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseOutgoingRelationshipId name="Relationship_TaxReportCollection_BaseOutgoingRelationshipId">Relationship_TaxReportCollection_BaseOutgoingRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseOutgoingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseOutgoingCreditNoRelationshipId name="Relationship_TaxReportCollection_BaseOutgoingCreditNoRelationshipId">Relationship_TaxReportCollection_BaseOutgoingCreditNoRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseOutgoingCreditNoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseOutgoingDebit_MYRelationshipId name="Relationship_TaxReportCollection_BaseOutgoingDebit_MYRelationshipId">Relationship_TaxReportCollection_BaseOutgoingDebit_MYRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseOutgoingDebit_MYRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseUseTaxRelationshipId name="Relationship_TaxReportCollection_BaseUseTaxRelationshipId">Relationship_TaxReportCollection_BaseUseTaxRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseUseTaxRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseUseTaxCreditNoteRelationshipId name="Relationship_TaxReportCollection_BaseUseTaxCreditNoteRelationshipId">Relationship_TaxReportCollection_BaseUseTaxCreditNoteRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseUseTaxCreditNoteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseUseTaxOffsetRelationshipId name="Relationship_TaxReportCollection_BaseUseTaxOffsetRelationshipId">Relationship_TaxReportCollection_BaseUseTaxOffsetRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseUseTaxOffsetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_BaseUseTaxOffsetCredRelationshipId name="Relationship_TaxReportCollection_BaseUseTaxOffsetCredRelationshipId">Relationship_TaxReportCollection_BaseUseTaxOffsetCredRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_BaseUseTaxOffsetCredRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxFreeBuyRelationshipId name="Relationship_TaxReportCollection_TaxFreeBuyRelationshipId">Relationship_TaxReportCollection_TaxFreeBuyRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxFreeBuyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxFreeBuyCreditNoteRelationshipId name="Relationship_TaxReportCollection_TaxFreeBuyCreditNoteRelationshipId">Relationship_TaxReportCollection_TaxFreeBuyCreditNoteRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxFreeBuyCreditNoteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxFreeBuyDebitN_MYRelationshipId name="Relationship_TaxReportCollection_TaxFreeBuyDebitN_MYRelationshipId">Relationship_TaxReportCollection_TaxFreeBuyDebitN_MYRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxFreeBuyDebitN_MYRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxFreeSalesRelationshipId name="Relationship_TaxReportCollection_TaxFreeSalesRelationshipId">Relationship_TaxReportCollection_TaxFreeSalesRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxFreeSalesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxFreeSalesCreditNoRelationshipId name="Relationship_TaxReportCollection_TaxFreeSalesCreditNoRelationshipId">Relationship_TaxReportCollection_TaxFreeSalesCreditNoRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxFreeSalesCreditNoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxFreeSalesDebit_MYRelationshipId name="Relationship_TaxReportCollection_TaxFreeSalesDebit_MYRelationshipId">Relationship_TaxReportCollection_TaxFreeSalesDebit_MYRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxFreeSalesDebit_MYRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxIncomingRelationshipId name="Relationship_TaxReportCollection_TaxIncomingRelationshipId">Relationship_TaxReportCollection_TaxIncomingRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxIncomingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxIncomingCreditNotRelationshipId name="Relationship_TaxReportCollection_TaxIncomingCreditNotRelationshipId">Relationship_TaxReportCollection_TaxIncomingCreditNotRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxIncomingCreditNotRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxIncomingDebitN_MYRelationshipId name="Relationship_TaxReportCollection_TaxIncomingDebitN_MYRelationshipId">Relationship_TaxReportCollection_TaxIncomingDebitN_MYRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxIncomingDebitN_MYRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxOutgoingRelationshipId name="Relationship_TaxReportCollection_TaxOutgoingRelationshipId">Relationship_TaxReportCollection_TaxOutgoingRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxOutgoingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxOutgoingCreditNotRelationshipId name="Relationship_TaxReportCollection_TaxOutgoingCreditNotRelationshipId">Relationship_TaxReportCollection_TaxOutgoingCreditNotRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxOutgoingCreditNotRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_TaxOutgoingDebitN_MYRelationshipId name="Relationship_TaxReportCollection_TaxOutgoingDebitN_MYRelationshipId">Relationship_TaxReportCollection_TaxOutgoingDebitN_MYRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_TaxOutgoingDebitN_MYRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_UseTaxRelationshipId name="Relationship_TaxReportCollection_UseTaxRelationshipId">Relationship_TaxReportCollection_UseTaxRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_UseTaxRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_UseTaxCreditNoteRelationshipId name="Relationship_TaxReportCollection_UseTaxCreditNoteRelationshipId">Relationship_TaxReportCollection_UseTaxCreditNoteRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_UseTaxCreditNoteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_UseTaxOffsetRelationshipId name="Relationship_TaxReportCollection_UseTaxOffsetRelationshipId">Relationship_TaxReportCollection_UseTaxOffsetRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_UseTaxOffsetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportCollection_UseTaxOffsetCreditNoRelationshipId name="Relationship_TaxReportCollection_UseTaxOffsetCreditNoRelationshipId">Relationship_TaxReportCollection_UseTaxOffsetCreditNoRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportCollection_UseTaxOffsetCreditNoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportCollection.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportCollection.cdm.json/TaxReportCollection</a></td><td><a href="TaxReportCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxVatReportCategory_MXRelationshipId name="Relationship_TaxVatReportCategory_MXRelationshipId">Relationship_TaxVatReportCategory_MXRelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxVatReportCategory_MXRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxVatReportCategory_MX.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxVatReportCategory_MX.cdm.json/TaxVatReportCategory_MX</a></td><td><a href="TaxVatReportCategory_MX.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VATOperationCodeTable_RURelationshipId name="Relationship_VATOperationCodeTable_RURelationshipId">Relationship_VATOperationCodeTable_RURelationshipId</a>

First included in: Group/TaxTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VATOperationCodeTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RSalesPurchBooks/Group/VATOperationCodeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/Group/VATOperationCodeTable_RU.cdm.json/VATOperationCodeTable_RU</a></td><td><a href="../../RSalesPurchBooks/Group/VATOperationCodeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/TaxTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
