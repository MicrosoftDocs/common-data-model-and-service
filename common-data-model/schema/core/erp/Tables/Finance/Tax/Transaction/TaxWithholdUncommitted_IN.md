---
title: TaxWithholdUncommitted_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# TaxWithholdUncommitted_IN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Tax/Transaction/TaxWithholdUncommitted_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdUncommitted_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[AccountNumber](#AccountNumber)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[AcknowledgermentNumber](#AcknowledgermentNumber)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[AdvancePayment](#AdvancePayment)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[AmountOriginMST](#AmountOriginMST)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[CalculationDate](#CalculationDate)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[CalcUncalcPostedTrans](#CalcUncalcPostedTrans)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Company](#Company)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[ConcessionCertificateNumber](#ConcessionCertificateNumber)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[CountryRegionToRemittance](#CountryRegionToRemittance)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[CPOrigInvoiceRefRecId](#CPOrigInvoiceRefRecId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[ExchangeRate](#ExchangeRate)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[ExchRateSecond](#ExchRateSecond)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[ExemptTax](#ExemptTax)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[HeadingRecId](#HeadingRecId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[HeadingTableId](#HeadingTableId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[InvoiceId](#InvoiceId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[IsPartOfTurnOver](#IsPartOfTurnOver)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[IsTaxCalculated](#IsTaxCalculated)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[LedgerDimensionDefaultAccount](#LedgerDimensionDefaultAccount)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[NatureOfRemittance](#NatureOfRemittance)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[OverlookThreshold](#OverlookThreshold)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[RateOfDeduction](#RateOfDeduction)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Reason](#Reason)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Source](#Source)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceBaseAmountCur](#SourceBaseAmountCur)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceBaseAmountCurCalculated](#SourceBaseAmountCurCalculated)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceBaseAmountCurRaw](#SourceBaseAmountCurRaw)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceBaseAmountCurRegulated](#SourceBaseAmountCurRegulated)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceCurrencyCOde](#SourceCurrencyCOde)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceRecId](#SourceRecId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceRegulateAmountCur](#SourceRegulateAmountCur)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceTableId](#SourceTableId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceTaxAmountCur](#SourceTaxAmountCur)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceTaxAmountCurReal](#SourceTaxAmountCurReal)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceTransDate](#SourceTransDate)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceTransRecId](#SourceTransRecId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceTransTableId](#SourceTransTableId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[SourceTransVoucher](#SourceTransVoucher)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxAmount](#TaxAmount)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxAmountCur](#TaxAmountCur)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxApplicability](#TaxApplicability)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxAutogenerated](#TaxAutogenerated)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxBaseAmountCur](#TaxBaseAmountCur)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxBaseAmountRaw](#TaxBaseAmountRaw)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxBaseQty](#TaxBaseQty)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxCurrencyCode](#TaxCurrencyCode)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxWithholdCode](#TaxWithholdCode)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxWithholdGroup](#TaxWithholdGroup)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxWithholdType](#TaxWithholdType)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxWithholdValue](#TaxWithholdValue)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[ThresholdValidFrom](#ThresholdValidFrom)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[ThresholdValidTo](#ThresholdValidTo)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TransactionStatus](#TransactionStatus)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TurnoverThreshold](#TurnoverThreshold)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Voucher](#Voucher)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[TaxCalcAsNonTaxTransInVoucher](#TaxCalcAsNonTaxTransInVoucher)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_CPOrigCustTransRelationshipId](#Relationship_CPOrigCustTransRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_CPOrigVendTransRelationshipId](#Relationship_CPOrigVendTransRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_CustInvoiceLineRelationshipId](#Relationship_CustInvoiceLineRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_CustInvoiceTableRelationshipId](#Relationship_CustInvoiceTableRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_CustTransRelationshipId](#Relationship_CustTransRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_DimensionAttributeValueCombinationRelationshipId](#Relationship_DimensionAttributeValueCombinationRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_SourceCurrencyRelationshipId](#Relationship_SourceCurrencyRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_SourceDocumentLineRelationshipId](#Relationship_SourceDocumentLineRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_TaxCurrencyCodeRelationshipId](#Relationship_TaxCurrencyCodeRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_TaxWithholdCountryRegionToRemittance_INRelationshipId](#Relationship_TaxWithholdCountryRegionToRemittance_INRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_TaxWithholdGroupHeadingRelationshipId](#Relationship_TaxWithholdGroupHeadingRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_TaxWithholdNatureOfRemittance_INRelationshipId](#Relationship_TaxWithholdNatureOfRemittance_INRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_TaxWithholdTableRelationshipId](#Relationship_TaxWithholdTableRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_VendTransRelationshipId](#Relationship_VendTransRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxWithholdUncommitted_IN.md" target="_blank">Transaction/TaxWithholdUncommitted_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdUncommitted_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountNumber name="AccountNumber">AccountNumber</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcknowledgermentNumber name="AcknowledgermentNumber">AcknowledgermentNumber</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcknowledgermentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvancePayment name="AdvancePayment">AdvancePayment</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancePayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AmountOriginMST name="AmountOriginMST">AmountOriginMST</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountOriginMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CalculationDate name="CalculationDate">CalculationDate</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CalcUncalcPostedTrans name="CalcUncalcPostedTrans">CalcUncalcPostedTrans</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcUncalcPostedTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConcessionCertificateNumber name="ConcessionCertificateNumber">ConcessionCertificateNumber</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConcessionCertificateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionToRemittance name="CountryRegionToRemittance">CountryRegionToRemittance</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionToRemittance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CPOrigInvoiceRefRecId name="CPOrigInvoiceRefRecId">CPOrigInvoiceRefRecId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CPOrigInvoiceRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExchRateSecond name="ExchRateSecond">ExchRateSecond</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateSecond attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExemptTax name="ExemptTax">ExemptTax</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExemptTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HeadingRecId name="HeadingRecId">HeadingRecId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeadingRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HeadingTableId name="HeadingTableId">HeadingTableId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeadingTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPartOfTurnOver name="IsPartOfTurnOver">IsPartOfTurnOver</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPartOfTurnOver attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsTaxCalculated name="IsTaxCalculated">IsTaxCalculated</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxCalculated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerDimensionDefaultAccount name="LedgerDimensionDefaultAccount">LedgerDimensionDefaultAccount</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDefaultAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NatureOfRemittance name="NatureOfRemittance">NatureOfRemittance</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NatureOfRemittance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OverlookThreshold name="OverlookThreshold">OverlookThreshold</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverlookThreshold attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RateOfDeduction name="RateOfDeduction">RateOfDeduction</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateOfDeduction attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Reason name="Reason">Reason</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Source name="Source">Source</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Source attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceBaseAmountCur name="SourceBaseAmountCur">SourceBaseAmountCur</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceBaseAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceBaseAmountCurCalculated name="SourceBaseAmountCurCalculated">SourceBaseAmountCurCalculated</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceBaseAmountCurCalculated attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceBaseAmountCurRaw name="SourceBaseAmountCurRaw">SourceBaseAmountCurRaw</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceBaseAmountCurRaw attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceBaseAmountCurRegulated name="SourceBaseAmountCurRegulated">SourceBaseAmountCurRegulated</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceBaseAmountCurRegulated attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceCurrencyCOde name="SourceCurrencyCOde">SourceCurrencyCOde</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceCurrencyCOde attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceRecId name="SourceRecId">SourceRecId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceRegulateAmountCur name="SourceRegulateAmountCur">SourceRegulateAmountCur</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRegulateAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceTableId name="SourceTableId">SourceTableId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceTaxAmountCur name="SourceTaxAmountCur">SourceTaxAmountCur</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTaxAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceTaxAmountCurReal name="SourceTaxAmountCurReal">SourceTaxAmountCurReal</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTaxAmountCurReal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceTransDate name="SourceTransDate">SourceTransDate</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SourceTransRecId name="SourceTransRecId">SourceTransRecId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTransRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceTransTableId name="SourceTransTableId">SourceTransTableId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTransTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceTransVoucher name="SourceTransVoucher">SourceTransVoucher</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTransVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountCur name="TaxAmountCur">TaxAmountCur</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxApplicability name="TaxApplicability">TaxApplicability</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxApplicability attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxAutogenerated name="TaxAutogenerated">TaxAutogenerated</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAutogenerated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmountCur name="TaxBaseAmountCur">TaxBaseAmountCur</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmountRaw name="TaxBaseAmountRaw">TaxBaseAmountRaw</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountRaw attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseQty name="TaxBaseQty">TaxBaseQty</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxCurrencyCode name="TaxCurrencyCode">TaxCurrencyCode</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

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

### <a href=#TaxWithholdCode name="TaxWithholdCode">TaxWithholdCode</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

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

### <a href=#TaxWithholdGroup name="TaxWithholdGroup">TaxWithholdGroup</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdType name="TaxWithholdType">TaxWithholdType</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdValue name="TaxWithholdValue">TaxWithholdValue</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ThresholdValidFrom name="ThresholdValidFrom">ThresholdValidFrom</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ThresholdValidTo name="ThresholdValidTo">ThresholdValidTo</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TransactionStatus name="TransactionStatus">TransactionStatus</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TurnoverThreshold name="TurnoverThreshold">TurnoverThreshold</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TurnoverThreshold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCalcAsNonTaxTransInVoucher name="TaxCalcAsNonTaxTransInVoucher">TaxCalcAsNonTaxTransInVoucher</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCalcAsNonTaxTransInVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

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

### <a href=#Relationship_CPOrigCustTransRelationshipId name="Relationship_CPOrigCustTransRelationshipId">Relationship_CPOrigCustTransRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CPOrigCustTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustTrans.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Transaction/CustTrans.cdm.json/CustTrans</a></td><td><a href="../../AccountsReceivable/Transaction/CustTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CPOrigVendTransRelationshipId name="Relationship_CPOrigVendTransRelationshipId">Relationship_CPOrigVendTransRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CPOrigVendTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendTrans.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Transaction/VendTrans.cdm.json/VendTrans</a></td><td><a href="../../AccountsPayable/Transaction/VendTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustInvoiceLineRelationshipId name="Relationship_CustInvoiceLineRelationshipId">Relationship_CustInvoiceLineRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/WorksheetLine/CustInvoiceLine.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/WorksheetLine/CustInvoiceLine.cdm.json/CustInvoiceLine</a></td><td><a href="../../AccountsReceivable/WorksheetLine/CustInvoiceLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustInvoiceTableRelationshipId name="Relationship_CustInvoiceTableRelationshipId">Relationship_CustInvoiceTableRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/WorksheetHeader/CustInvoiceTable.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/WorksheetHeader/CustInvoiceTable.cdm.json/CustInvoiceTable</a></td><td><a href="../../AccountsReceivable/WorksheetHeader/CustInvoiceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTransRelationshipId name="Relationship_CustTransRelationshipId">Relationship_CustTransRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustTrans.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Transaction/CustTrans.cdm.json/CustTrans</a></td><td><a href="../../AccountsReceivable/Transaction/CustTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueCombinationRelationshipId name="Relationship_DimensionAttributeValueCombinationRelationshipId">Relationship_DimensionAttributeValueCombinationRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceCurrencyRelationshipId name="Relationship_SourceCurrencyRelationshipId">Relationship_SourceCurrencyRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceCurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceDocumentLineRelationshipId name="Relationship_SourceDocumentLineRelationshipId">Relationship_SourceDocumentLineRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceDocumentLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/TransactionLine/SourceDocumentLine.md" target="_blank">/core/erp/Tables/Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.cdm.json/SourceDocumentLine</a></td><td><a href="../../AccountingFoundation/TransactionLine/SourceDocumentLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxCurrencyCodeRelationshipId name="Relationship_TaxCurrencyCodeRelationshipId">Relationship_TaxCurrencyCodeRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxCurrencyCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdCountryRegionToRemittance_INRelationshipId name="Relationship_TaxWithholdCountryRegionToRemittance_INRelationshipId">Relationship_TaxWithholdCountryRegionToRemittance_INRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdCountryRegionToRemittance_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxWithholdCountryRegionToRemittance_IN.md" target="_blank">/core/erp/Tables/Finance/Tax/Main/TaxWithholdCountryRegionToRemittance_IN.cdm.json/TaxWithholdCountryRegionToRemittance_IN</a></td><td><a href="../Main/TaxWithholdCountryRegionToRemittance_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdGroupHeadingRelationshipId name="Relationship_TaxWithholdGroupHeadingRelationshipId">Relationship_TaxWithholdGroupHeadingRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxWithholdGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxWithholdGroupHeading.cdm.json/TaxWithholdGroupHeading</a></td><td><a href="../Group/TaxWithholdGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdNatureOfRemittance_INRelationshipId name="Relationship_TaxWithholdNatureOfRemittance_INRelationshipId">Relationship_TaxWithholdNatureOfRemittance_INRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdNatureOfRemittance_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxWithholdNatureOfRemittance_IN.md" target="_blank">/core/erp/Tables/Finance/Tax/Main/TaxWithholdNatureOfRemittance_IN.cdm.json/TaxWithholdNatureOfRemittance_IN</a></td><td><a href="../Main/TaxWithholdNatureOfRemittance_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdTableRelationshipId name="Relationship_TaxWithholdTableRelationshipId">Relationship_TaxWithholdTableRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxWithholdTable.md" target="_blank">/core/erp/Tables/Finance/Tax/Main/TaxWithholdTable.cdm.json/TaxWithholdTable</a></td><td><a href="../Main/TaxWithholdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTransRelationshipId name="Relationship_VendTransRelationshipId">Relationship_VendTransRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendTrans.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Transaction/VendTrans.cdm.json/VendTrans</a></td><td><a href="../../AccountsPayable/Transaction/VendTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxWithholdUncommitted_IN (this entity)  

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
