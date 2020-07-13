---
title: TaxWithholdTrans in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Withholding tax transaction in Transaction(TaxWithholdTrans)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxWithholdTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[VendAccount](#VendAccount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[CanBeReversed_BR](#CanBeReversed_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[CompetenceDate](#CompetenceDate)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[CustAccount](#CustAccount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[CustTransInvoiceId](#CustTransInvoiceId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[CustTransPaymId](#CustTransPaymId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[CustVendTransOpenRecId_BR](#CustVendTransOpenRecId_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[ExemptedAmount](#ExemptedAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[IntersectionWithholdBaseAmount_BR](#IntersectionWithholdBaseAmount_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Invoice](#Invoice)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[InvoiceBaseAmount](#InvoiceBaseAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[InvoiceCurrency](#InvoiceCurrency)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[InvoiceExemptedAmount](#InvoiceExemptedAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[InvoiceNotTaxableByTreaty](#InvoiceNotTaxableByTreaty)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[InvoiceNotTaxableExpenses](#InvoiceNotTaxableExpenses)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[InvoiceTaxAmount](#InvoiceTaxAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[InvoiceTaxWithholdAmount](#InvoiceTaxWithholdAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[InvoiceWithholdBaseAmount](#InvoiceWithholdBaseAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[JournalNum](#JournalNum)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[LedgerDimension](#LedgerDimension)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[LedgerJourTransRecId_BR](#LedgerJourTransRecId_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[NotTaxableByTreaty](#NotTaxableByTreaty)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[NotTaxableExpenses](#NotTaxableExpenses)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PackedExtensions](#PackedExtensions)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PartyId_BR](#PartyId_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PaymCompany](#PaymCompany)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PaymCurrency](#PaymCurrency)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PaymExemptedAmount](#PaymExemptedAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PaymNotTaxableByTreaty](#PaymNotTaxableByTreaty)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PaymNotTaxableExpenses](#PaymNotTaxableExpenses)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PaymTaxWithholdAmount](#PaymTaxWithholdAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PaymVendor](#PaymVendor)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[PaymWithholdBaseAmount](#PaymWithholdBaseAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Posted](#Posted)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[RefCustVendTransRecId_BR](#RefCustVendTransRecId_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Settled](#Settled)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[SettlementVoucher](#SettlementVoucher)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Source_BR](#Source_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[SpecTransId](#SpecTransId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxExemptedAmount](#TaxExemptedAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxNotTaxableByTreaty](#TaxNotTaxableByTreaty)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxNotTaxableExpenses](#TaxNotTaxableExpenses)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxRepCounter_BR](#TaxRepCounter_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxTaxWithholdAmount](#TaxTaxWithholdAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxType_IN](#TaxType_IN)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdAmount](#TaxWithholdAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdBaseAmount](#TaxWithholdBaseAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdCode](#TaxWithholdCode)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdComponentGroupTable_IN](#TaxWithholdComponentGroupTable_IN)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdComponentTable_IN](#TaxWithholdComponentTable_IN)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdCurrency](#TaxWithholdCurrency)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdGroup](#TaxWithholdGroup)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdIsSelected_BR](#TaxWithholdIsSelected_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdItemGroupHeading_TH](#TaxWithholdItemGroupHeading_TH)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdPeriod_BR](#TaxWithholdPeriod_BR)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdPeriodHead_TH](#TaxWithholdPeriodHead_TH)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdSlipNum_TH](#TaxWithholdSlipNum_TH)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TransDate](#TransDate)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[VendorType_TH](#VendorType_TH)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[VendTransInvoiceId](#VendTransInvoiceId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[VendTransPaymId](#VendTransPaymId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Voucher](#Voucher)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[VoucherInvoice](#VoucherInvoice)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[WithholdBaseAmount](#WithholdBaseAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxWithholdAccumulatedBaseAmount](#TaxWithholdAccumulatedBaseAmount)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[HideInReport_IT](#HideInReport_IT)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[TaxReimbursement_IT](#TaxReimbursement_IT)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_Currency_InvoiceCurrencyRelationshipId](#Relationship_Currency_InvoiceCurrencyRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_Currency_PaymCurrencyRelationshipId](#Relationship_Currency_PaymCurrencyRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_Currency_TaxWithholdCurrencyRelationshipId](#Relationship_Currency_TaxWithholdCurrencyRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_CustTrans_CustTransInvoiceIdRelationshipId](#Relationship_CustTrans_CustTransInvoiceIdRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_CustTrans_CustTransPaymIdRelationshipId](#Relationship_CustTrans_CustTransPaymIdRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_LedgerJournalTableRelationshipId](#Relationship_LedgerJournalTableRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_SpecTransRelationshipId](#Relationship_SpecTransRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_TaxWithholdComponentGroupTable_INFKRelationshipId](#Relationship_TaxWithholdComponentGroupTable_INFKRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_TaxWithholdComponentTable_INFKRelationshipId](#Relationship_TaxWithholdComponentTable_INFKRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_TaxWithholdGroupHeadingRelationshipId](#Relationship_TaxWithholdGroupHeadingRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_TaxWithholdItemGroupHeading_THRelationshipId](#Relationship_TaxWithholdItemGroupHeading_THRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_TaxWithholdPeriodHead_THRelationshipId](#Relationship_TaxWithholdPeriodHead_THRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_TaxWithholdTableRelationshipId](#Relationship_TaxWithholdTableRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_VendTable_PaymVendorRelationshipId](#Relationship_VendTable_PaymVendorRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_VendTable_VendAccountRelationshipId](#Relationship_VendTable_VendAccountRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_VendTransInvoiceRelationshipId](#Relationship_VendTransInvoiceRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_VendTransOpenRelationshipId](#Relationship_VendTransOpenRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_VendTransPaymRelationshipId](#Relationship_VendTransPaymRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxWithholdTrans.md" target="_blank">Transaction/TaxWithholdTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanBeReversed_BR name="CanBeReversed_BR">CanBeReversed_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanBeReversed_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CompetenceDate name="CompetenceDate">CompetenceDate</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Competence date</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompetenceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Competence date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustTransInvoiceId name="CustTransInvoiceId">CustTransInvoiceId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTransInvoiceId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustTransPaymId name="CustTransPaymId">CustTransPaymId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTransPaymId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustVendTransOpenRecId_BR name="CustVendTransOpenRecId_BR">CustVendTransOpenRecId_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendTransOpenRecId_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExemptedAmount name="ExemptedAmount">ExemptedAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount exempted from withhold in default currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExemptedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount exempted from withhold in default currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IntersectionWithholdBaseAmount_BR name="IntersectionWithholdBaseAmount_BR">IntersectionWithholdBaseAmount_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis for withholding tax calculation in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntersectionWithholdBaseAmount_BR attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Basis for withholding tax calculation in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAmount name="InvoiceAmount">InvoiceAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice amount to be paid in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice amount to be paid in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceBaseAmount name="InvoiceBaseAmount">InvoiceBaseAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base amount in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Base amount in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceCurrency name="InvoiceCurrency">InvoiceCurrency</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice currency</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceExemptedAmount name="InvoiceExemptedAmount">InvoiceExemptedAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount exempted from withhold in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceExemptedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount exempted from withhold in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceNotTaxableByTreaty name="InvoiceNotTaxableByTreaty">InvoiceNotTaxableByTreaty</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not withhold taxable by treaty in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNotTaxableByTreaty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Not withhold taxable by treaty in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceNotTaxableExpenses name="InvoiceNotTaxableExpenses">InvoiceNotTaxableExpenses</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not taxable expenses in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNotTaxableExpenses attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Not taxable expenses in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceTaxAmount name="InvoiceTaxAmount">InvoiceTaxAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax amount in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax amount in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceTaxWithholdAmount name="InvoiceTaxWithholdAmount">InvoiceTaxWithholdAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTaxWithholdAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceWithholdBaseAmount name="InvoiceWithholdBaseAmount">InvoiceWithholdBaseAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis for withholding tax calculation in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceWithholdBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Basis for withholding tax calculation in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#JournalNum name="JournalNum">JournalNum</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerJourTransRecId_BR name="LedgerJourTransRecId_BR">LedgerJourTransRecId_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJourTransRecId_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NotTaxableByTreaty name="NotTaxableByTreaty">NotTaxableByTreaty</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not withhold taxable by treaty in default currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotTaxableByTreaty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Not withhold taxable by treaty in default currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NotTaxableExpenses name="NotTaxableExpenses">NotTaxableExpenses</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not taxable expenses in default currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotTaxableExpenses attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Not taxable expenses in default currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PackedExtensions name="PackedExtensions">PackedExtensions</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedExtensions attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#PartyId_BR name="PartyId_BR">PartyId_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyId_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymCompany name="PaymCompany">PaymCompany</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company accounts</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymCurrency name="PaymCurrency">PaymCurrency</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment currency</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymExemptedAmount name="PaymExemptedAmount">PaymExemptedAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount exempted from withhold in payment currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymExemptedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount exempted from withhold in payment currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PaymNotTaxableByTreaty name="PaymNotTaxableByTreaty">PaymNotTaxableByTreaty</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not withhold taxable by treaty in payment currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymNotTaxableByTreaty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Not withhold taxable by treaty in payment currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PaymNotTaxableExpenses name="PaymNotTaxableExpenses">PaymNotTaxableExpenses</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not taxable expenses in payment currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymNotTaxableExpenses attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Not taxable expenses in payment currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PaymTaxWithholdAmount name="PaymTaxWithholdAmount">PaymTaxWithholdAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax in payment currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymTaxWithholdAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax in payment currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PaymVendor name="PaymVendor">PaymVendor</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment vendor account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment vendor account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymWithholdBaseAmount name="PaymWithholdBaseAmount">PaymWithholdBaseAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis for withholding tax calculation in payment currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymWithholdBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Basis for withholding tax calculation in payment currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefCustVendTransRecId_BR name="RefCustVendTransRecId_BR">RefCustVendTransRecId_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefCustVendTransRecId_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Settled name="Settled">Settled</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Settled</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Settled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Settled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SettlementVoucher name="SettlementVoucher">SettlementVoucher</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Source_BR name="Source_BR">Source_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Source_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SpecTransId name="SpecTransId">SpecTransId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecTransId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxExemptedAmount name="TaxExemptedAmount">TaxExemptedAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount exempted from withhold in withholding tax currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount exempted from withhold in withholding tax currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxNotTaxableByTreaty name="TaxNotTaxableByTreaty">TaxNotTaxableByTreaty</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not withhold taxable by treaty in withholding tax currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxNotTaxableByTreaty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Not withhold taxable by treaty in withholding tax currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxNotTaxableExpenses name="TaxNotTaxableExpenses">TaxNotTaxableExpenses</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not taxable expenses in withholding tax currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxNotTaxableExpenses attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Not taxable expenses in withholding tax currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxRepCounter_BR name="TaxRepCounter_BR">TaxRepCounter_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRepCounter_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxTaxWithholdAmount name="TaxTaxWithholdAmount">TaxTaxWithholdAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax in withholding tax currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTaxWithholdAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax in withholding tax currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxType_IN name="TaxType_IN">TaxType_IN</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

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

### <a href=#TaxWithholdAmount name="TaxWithholdAmount">TaxWithholdAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax in default currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax in default currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWithholdBaseAmount name="TaxWithholdBaseAmount">TaxWithholdBaseAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis for withholding tax calculation in withholding tax currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Basis for withholding tax calculation in withholding tax currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWithholdCode name="TaxWithholdCode">TaxWithholdCode</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdComponentGroupTable_IN name="TaxWithholdComponentGroupTable_IN">TaxWithholdComponentGroupTable_IN</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax component group</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdComponentGroupTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax component group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdComponentTable_IN name="TaxWithholdComponentTable_IN">TaxWithholdComponentTable_IN</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax component</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdComponentTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax component</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdCurrency name="TaxWithholdCurrency">TaxWithholdCurrency</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax currency</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdGroup name="TaxWithholdGroup">TaxWithholdGroup</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdIsSelected_BR name="TaxWithholdIsSelected_BR">TaxWithholdIsSelected_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax is selected</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdIsSelected_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax is selected</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdItemGroupHeading_TH name="TaxWithholdItemGroupHeading_TH">TaxWithholdItemGroupHeading_TH</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdItemGroupHeading_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdPeriod_BR name="TaxWithholdPeriod_BR">TaxWithholdPeriod_BR</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdPeriod_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdPeriodHead_TH name="TaxWithholdPeriodHead_TH">TaxWithholdPeriodHead_TH</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdPeriodHead_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdSlipNum_TH name="TaxWithholdSlipNum_TH">TaxWithholdSlipNum_TH</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdSlipNum_TH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#VendorType_TH name="VendorType_TH">VendorType_TH</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorType_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VendTransInvoiceId name="VendTransInvoiceId">VendTransInvoiceId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTransInvoiceId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendTransPaymId name="VendTransPaymId">VendTransPaymId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTransPaymId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment voucher</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment voucher</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherInvoice name="VoucherInvoice">VoucherInvoice</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice voucher</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice voucher</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdBaseAmount name="WithholdBaseAmount">WithholdBaseAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis for withholding tax calculation in default currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Basis for withholding tax calculation in default currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWithholdAccumulatedBaseAmount name="TaxWithholdAccumulatedBaseAmount">TaxWithholdAccumulatedBaseAmount</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax accumulated base amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAccumulatedBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax accumulated base amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#HideInReport_IT name="HideInReport_IT">HideInReport_IT</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hide</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideInReport_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Hide</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxReimbursement_IT name="TaxReimbursement_IT">TaxReimbursement_IT</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reimbursement in withholding tax currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReimbursement_IT attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reimbursement in withholding tax currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

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

### <a href=#Relationship_Currency_InvoiceCurrencyRelationshipId name="Relationship_Currency_InvoiceCurrencyRelationshipId">Relationship_Currency_InvoiceCurrencyRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_InvoiceCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_PaymCurrencyRelationshipId name="Relationship_Currency_PaymCurrencyRelationshipId">Relationship_Currency_PaymCurrencyRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_PaymCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_TaxWithholdCurrencyRelationshipId name="Relationship_Currency_TaxWithholdCurrencyRelationshipId">Relationship_Currency_TaxWithholdCurrencyRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_TaxWithholdCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTrans_CustTransInvoiceIdRelationshipId name="Relationship_CustTrans_CustTransInvoiceIdRelationshipId">Relationship_CustTrans_CustTransInvoiceIdRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTrans_CustTransInvoiceIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustTrans.cdm.json/CustTrans</a></td><td><a href="../../AccountsReceivable/Transaction/CustTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTrans_CustTransPaymIdRelationshipId name="Relationship_CustTrans_CustTransPaymIdRelationshipId">Relationship_CustTrans_CustTransPaymIdRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTrans_CustTransPaymIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustTrans.cdm.json/CustTrans</a></td><td><a href="../../AccountsReceivable/Transaction/CustTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalTableRelationshipId name="Relationship_LedgerJournalTableRelationshipId">Relationship_LedgerJournalTableRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetHeader/LedgerJournalTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetHeader/LedgerJournalTable.cdm.json/LedgerJournalTable</a></td><td><a href="../../AccountingFoundation/WorksheetHeader/LedgerJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SpecTransRelationshipId name="Relationship_SpecTransRelationshipId">Relationship_SpecTransRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SpecTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/WorksheetLine/SpecTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/SpecTrans.cdm.json/SpecTrans</a></td><td><a href="../../Bank/WorksheetLine/SpecTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdComponentGroupTable_INFKRelationshipId name="Relationship_TaxWithholdComponentGroupTable_INFKRelationshipId">Relationship_TaxWithholdComponentGroupTable_INFKRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdComponentGroupTable_INFKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxWithholdComponentGroupTable_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxWithholdComponentGroupTable_IN.cdm.json/TaxWithholdComponentGroupTable_IN</a></td><td><a href="../Main/TaxWithholdComponentGroupTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdComponentTable_INFKRelationshipId name="Relationship_TaxWithholdComponentTable_INFKRelationshipId">Relationship_TaxWithholdComponentTable_INFKRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdComponentTable_INFKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxWithholdComponentTable_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxWithholdComponentTable_IN.cdm.json/TaxWithholdComponentTable_IN</a></td><td><a href="../Main/TaxWithholdComponentTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdGroupHeadingRelationshipId name="Relationship_TaxWithholdGroupHeadingRelationshipId">Relationship_TaxWithholdGroupHeadingRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxWithholdGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdGroupHeading.cdm.json/TaxWithholdGroupHeading</a></td><td><a href="../Group/TaxWithholdGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdItemGroupHeading_THRelationshipId name="Relationship_TaxWithholdItemGroupHeading_THRelationshipId">Relationship_TaxWithholdItemGroupHeading_THRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdItemGroupHeading_THRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxWithholdItemGroupHeading_TH.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdItemGroupHeading_TH.cdm.json/TaxWithholdItemGroupHeading_TH</a></td><td><a href="../Group/TaxWithholdItemGroupHeading_TH.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdPeriodHead_THRelationshipId name="Relationship_TaxWithholdPeriodHead_THRelationshipId">Relationship_TaxWithholdPeriodHead_THRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdPeriodHead_THRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxWithholdPeriodHead_TH.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdPeriodHead_TH.cdm.json/TaxWithholdPeriodHead_TH</a></td><td><a href="../Group/TaxWithholdPeriodHead_TH.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdTableRelationshipId name="Relationship_TaxWithholdTableRelationshipId">Relationship_TaxWithholdTableRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxWithholdTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxWithholdTable.cdm.json/TaxWithholdTable</a></td><td><a href="../Main/TaxWithholdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTable_PaymVendorRelationshipId name="Relationship_VendTable_PaymVendorRelationshipId">Relationship_VendTable_PaymVendorRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTable_PaymVendorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTable_VendAccountRelationshipId name="Relationship_VendTable_VendAccountRelationshipId">Relationship_VendTable_VendAccountRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTable_VendAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTransInvoiceRelationshipId name="Relationship_VendTransInvoiceRelationshipId">Relationship_VendTransInvoiceRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendTrans.cdm.json/VendTrans</a></td><td><a href="../../AccountsPayable/Transaction/VendTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTransOpenRelationshipId name="Relationship_VendTransOpenRelationshipId">Relationship_VendTransOpenRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransOpenRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendTransOpen.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendTransOpen.cdm.json/VendTransOpen</a></td><td><a href="../../AccountsPayable/Transaction/VendTransOpen.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTransPaymRelationshipId name="Relationship_VendTransPaymRelationshipId">Relationship_VendTransPaymRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransPaymRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendTrans.cdm.json/VendTrans</a></td><td><a href="../../AccountsPayable/Transaction/VendTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxWithholdTrans (this entity)  

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
