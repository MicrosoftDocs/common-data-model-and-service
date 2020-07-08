---
title: FreeTextInvoiceEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Customer free text invoice in AccountsReceivable(FreeTextInvoiceEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/FreeTextInvoiceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer free text invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FreeTextNumber](#FreeTextNumber)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[PostingProfile](#PostingProfile)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[MethodOfPayment](#MethodOfPayment)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[TermsOfPayment](#TermsOfPayment)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[DueDate](#DueDate)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CashDiscountDate](#CashDiscountDate)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[LineNumber](#LineNumber)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[Description](#Description)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[LedgerDimension](#LedgerDimension)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[Quantity](#Quantity)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[UnitPrice](#UnitPrice)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[AmountCur](#AmountCur)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[SalesTaxItemGroup](#SalesTaxItemGroup)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[DirectDebitMandateId](#DirectDebitMandateId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CustomerReference](#CustomerReference)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CustomerRequisition](#CustomerRequisition)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[InvoiceId](#InvoiceId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[BillingClassification](#BillingClassification)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[BillingCode](#BillingCode)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[EInvoiceAccountCode](#EInvoiceAccountCode)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[EInvoiceIsLineSpecific](#EInvoiceIsLineSpecific)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[GiroType](#GiroType)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[IsLumpSumRecoveryTextPrinted](#IsLumpSumRecoveryTextPrinted)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[NGPCode](#NGPCode)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[PropertyNumber](#PropertyNumber)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[InclTax](#InclTax)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[PostponedVAT](#PostponedVAT)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[DeliveryDate](#DeliveryDate)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[DiscountPercentage](#DiscountPercentage)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CFOPTableRecId](#CFOPTableRecId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CFPSCode](#CFPSCode)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[IsFinalUser](#IsFinalUser)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CustomerPaymentFineCode](#CustomerPaymentFineCode)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[FiscalDocumentTypeRecId](#FiscalDocumentTypeRecId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[FiscalEstablishmentRecId](#FiscalEstablishmentRecId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CustomerPaymentFinancialInterestCode](#CustomerPaymentFinancialInterestCode)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[FiscalOperationPresenceType](#FiscalOperationPresenceType)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[SalesPurchOperationTypeRecId](#SalesPurchOperationTypeRecId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[IsServiceDeliveryAddressBased](#IsServiceDeliveryAddressBased)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CFOPCode](#CFOPCode)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[FiscalDocumentTypeId](#FiscalDocumentTypeId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[FiscalDocumentOperationTypeId](#FiscalDocumentOperationTypeId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[ComplementaryFiscalDocumentType](#ComplementaryFiscalDocumentType)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[TransportationDocumentLineId](#TransportationDocumentLineId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[InvoiceTxt](#InvoiceTxt)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[ConsigneeAccount](#ConsigneeAccount)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[ConsignorAccount](#ConsignorAccount)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[IsCorrection](#IsCorrection)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CorrectedFactureDate](#CorrectedFactureDate)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CorrectedFactureExternalId](#CorrectedFactureExternalId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CorrectedInvoiceDate](#CorrectedInvoiceDate)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CorrectedInvoiceId](#CorrectedInvoiceId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CorrectedPeriod](#CorrectedPeriod)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[CorrectionType](#CorrectionType)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[VATOnPayment](#VATOnPayment)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[NonRealRevenue](#NonRealRevenue)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[HeaderDefaultDimensionDisplayValue](#HeaderDefaultDimensionDisplayValue)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[DateOfVATRegister](#DateOfVATRegister)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[SalesDate](#SalesDate)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[IntentLetterId_IT](#IntentLetterId_IT)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[BackingTable_CustInvoiceTableRelationshipId](#BackingTable_CustInvoiceTableRelationshipId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="FreeTextInvoiceEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceEntity</a>|

### <a href=#FreeTextNumber name="FreeTextNumber">FreeTextNumber</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Free text number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeTextNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Free text number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

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

### <a href=#MethodOfPayment name="MethodOfPayment">MethodOfPayment</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MethodOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPayment name="TermsOfPayment">TermsOfPayment</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TermsOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountDate name="CashDiscountDate">CashDiscountDate</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountCur name="AmountCur">AmountCur</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCur attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroup name="SalesTaxItemGroup">SalesTaxItemGroup</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitMandateId name="DirectDebitMandateId">DirectDebitMandateId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitMandateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerReference name="CustomerReference">CustomerReference</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisition name="CustomerRequisition">CustomerRequisition</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingClassification name="BillingClassification">BillingClassification</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingCode name="BillingCode">BillingCode</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EInvoiceAccountCode name="EInvoiceAccountCode">EInvoiceAccountCode</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EInvoiceAccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EInvoiceIsLineSpecific name="EInvoiceIsLineSpecific">EInvoiceIsLineSpecific</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EInvoiceIsLineSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroType name="GiroType">GiroType</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLumpSumRecoveryTextPrinted name="IsLumpSumRecoveryTextPrinted">IsLumpSumRecoveryTextPrinted</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLumpSumRecoveryTextPrinted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NGPCode name="NGPCode">NGPCode</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NGPCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyNumber name="PropertyNumber">PropertyNumber</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InclTax name="InclTax">InclTax</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostponedVAT name="PostponedVAT">PostponedVAT</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostponedVAT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDate name="DeliveryDate">DeliveryDate</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage name="DiscountPercentage">DiscountPercentage</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPTableRecId name="CFOPTableRecId">CFOPTableRecId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPTableRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFPSCode name="CFPSCode">CFPSCode</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFPSCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFinalUser name="IsFinalUser">IsFinalUser</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinalUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFineCode name="CustomerPaymentFineCode">CustomerPaymentFineCode</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentFineCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeRecId name="FiscalDocumentTypeRecId">FiscalDocumentTypeRecId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentRecId name="FiscalEstablishmentRecId">FiscalEstablishmentRecId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFinancialInterestCode name="CustomerPaymentFinancialInterestCode">CustomerPaymentFinancialInterestCode</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentFinancialInterestCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalOperationPresenceType name="FiscalOperationPresenceType">FiscalOperationPresenceType</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOperationPresenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPurchOperationTypeRecId name="SalesPurchOperationTypeRecId">SalesPurchOperationTypeRecId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPurchOperationTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsServiceDeliveryAddressBased name="IsServiceDeliveryAddressBased">IsServiceDeliveryAddressBased</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsServiceDeliveryAddressBased attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPCode name="CFOPCode">CFOPCode</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeId name="FiscalDocumentTypeId">FiscalDocumentTypeId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentOperationTypeId name="FiscalDocumentOperationTypeId">FiscalDocumentOperationTypeId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentOperationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementaryFiscalDocumentType name="ComplementaryFiscalDocumentType">ComplementaryFiscalDocumentType</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementaryFiscalDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDocumentLineId name="TransportationDocumentLineId">TransportationDocumentLineId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDocumentLineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceTxt name="InvoiceTxt">InvoiceTxt</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsigneeAccount name="ConsigneeAccount">ConsigneeAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsigneeAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsignorAccount name="ConsignorAccount">ConsignorAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsignorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCorrection name="IsCorrection">IsCorrection</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCorrection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedFactureDate name="CorrectedFactureDate">CorrectedFactureDate</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedFactureExternalId name="CorrectedFactureExternalId">CorrectedFactureExternalId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureExternalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedInvoiceDate name="CorrectedInvoiceDate">CorrectedInvoiceDate</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedInvoiceId name="CorrectedInvoiceId">CorrectedInvoiceId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedPeriod name="CorrectedPeriod">CorrectedPeriod</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionType name="CorrectionType">CorrectionType</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATOnPayment name="VATOnPayment">VATOnPayment</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATOnPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonRealRevenue name="NonRealRevenue">NonRealRevenue</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonRealRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderDefaultDimensionDisplayValue name="HeaderDefaultDimensionDisplayValue">HeaderDefaultDimensionDisplayValue</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Header ledger account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderDefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Header ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateOfVATRegister name="DateOfVATRegister">DateOfVATRegister</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date of VAT register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfVATRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date of VAT register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesDate name="SalesDate">SalesDate</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntentLetterId_IT name="IntentLetterId_IT">IntentLetterId_IT</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntentLetterId_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustInvoiceTableRelationshipId name="BackingTable_CustInvoiceTableRelationshipId">BackingTable_CustInvoiceTableRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustInvoiceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/WorksheetHeader/CustInvoiceTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetHeader/CustInvoiceTable.cdm.json/CustInvoiceTable</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/WorksheetHeader/CustInvoiceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceEntity (this entity)  

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
