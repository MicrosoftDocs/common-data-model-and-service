---
title: FreeTextInvoiceHeaderEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# FreeTextInvoiceHeaderEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/FreeTextInvoiceHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InvoiceIdentifier](#InvoiceIdentifier)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[FreeTextNumber](#FreeTextNumber)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[InvoiceId](#InvoiceId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[DueDate](#DueDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[AdjustingInvoiceDate](#AdjustingInvoiceDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CentralBankPurposeCode](#CentralBankPurposeCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CentralBankPurposeText](#CentralBankPurposeText)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[PaymentTermsBaseDate](#PaymentTermsBaseDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[PaymentTermsBaseDays](#PaymentTermsBaseDays)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CashDiscountDate](#CashDiscountDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CashDiscountPercentage](#CashDiscountPercentage)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[ComplimentedInvoiceId](#ComplimentedInvoiceId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CorrectionReasonCode](#CorrectionReasonCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CashFlowForecast](#CashFlowForecast)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[BankAccountId](#BankAccountId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[BillingClassificationId](#BillingClassificationId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CustomerReference](#CustomerReference)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[DirectDebitMandateId](#DirectDebitMandateId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[IsPostedViaIntercompany](#IsPostedViaIntercompany)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[LanguageId](#LanguageId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[InvoiceName](#InvoiceName)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[numberSequenceGroup](#numberSequenceGroup)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[IsOneTimeCustomer](#IsOneTimeCustomer)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[TermsOfPayment](#TermsOfPayment)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[PaymentSchedule](#PaymentSchedule)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[MethodOfPayment](#MethodOfPayment)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[IsPosted](#IsPosted)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[PostingProfile](#PostingProfile)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CustomerRequisition](#CustomerRequisition)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[SalesTaxGroupId](#SalesTaxGroupId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[SalesTaxItemGroupId](#SalesTaxItemGroupId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[EInvoiceAccountCode](#EInvoiceAccountCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[EInvoiceIsLineSpecific](#EInvoiceIsLineSpecific)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[GiroType](#GiroType)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[IsLumpSumRecoveryTextPrinted](#IsLumpSumRecoveryTextPrinted)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CustomerGroup](#CustomerGroup)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[DirectDebitMandateReference](#DirectDebitMandateReference)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[SalesDate](#SalesDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[VatDueDate](#VatDueDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[BillingClassification](#BillingClassification)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[InclTax](#InclTax)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[PostponedVAT](#PostponedVAT)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[ComplementaryFiscalDocumentType](#ComplementaryFiscalDocumentType)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CFOPTableRecId](#CFOPTableRecId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CFPSCode](#CFPSCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[IsFinalUser](#IsFinalUser)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CustomerPaymentFineCode](#CustomerPaymentFineCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[FiscalDocumentTypeRecId](#FiscalDocumentTypeRecId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[FiscalEstablishmentRecId](#FiscalEstablishmentRecId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CustomerPaymentFinancialInterestCode](#CustomerPaymentFinancialInterestCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[FiscalOperationPresenceType](#FiscalOperationPresenceType)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[SalesPurchOperationTypeRecId](#SalesPurchOperationTypeRecId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[IsServiceDeliveryAddressBased](#IsServiceDeliveryAddressBased)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CFOPCode](#CFOPCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[FiscalDocumentTypeId](#FiscalDocumentTypeId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[FiscalDocumentOperationTypeId](#FiscalDocumentOperationTypeId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[TransportationDocumentLineId](#TransportationDocumentLineId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[ExternalInvoiceId](#ExternalInvoiceId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[ConsigneeAccount](#ConsigneeAccount)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[ConsignorAccount](#ConsignorAccount)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[IsCorrection](#IsCorrection)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CorrectedFactureDate](#CorrectedFactureDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CorrectedFactureExternalId](#CorrectedFactureExternalId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CorrectedInvoiceDate](#CorrectedInvoiceDate)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CorrectedInvoiceId](#CorrectedInvoiceId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CorrectedPeriod](#CorrectedPeriod)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[CorrectionType](#CorrectionType)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[NonRealRevenue](#NonRealRevenue)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[VATOnPayment](#VATOnPayment)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[InvoiceOriginCode](#InvoiceOriginCode)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_CustomerAccountRelationshipId](#Relationship_CustomerAccountRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_InvoiceAccountRelationshipId](#Relationship_InvoiceAccountRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_PaymTermRelationshipId](#Relationship_PaymTermRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_CashDiscRelationshipId](#Relationship_CashDiscRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_PaymentScheduleRelationshipId](#Relationship_PaymentScheduleRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_PaymModeRelationshipId](#Relationship_PaymModeRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_CustomerInvoiceOriginRelationshipId](#Relationship_CustomerInvoiceOriginRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[BackingTable_CustInvoiceTableRelationshipId](#BackingTable_CustInvoiceTableRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="FreeTextInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderEntity</a>|

### <a href=#InvoiceIdentifier name="InvoiceIdentifier">InvoiceIdentifier</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreeTextNumber name="FreeTextNumber">FreeTextNumber</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeTextNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

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

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

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

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdjustingInvoiceDate name="AdjustingInvoiceDate">AdjustingInvoiceDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustingInvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankPurposeCode name="CentralBankPurposeCode">CentralBankPurposeCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankPurposeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankPurposeText name="CentralBankPurposeText">CentralBankPurposeText</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankPurposeText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsBaseDate name="PaymentTermsBaseDate">PaymentTermsBaseDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsBaseDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsBaseDays name="PaymentTermsBaseDays">PaymentTermsBaseDays</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsBaseDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountDate name="CashDiscountDate">CashDiscountDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountPercentage name="CashDiscountPercentage">CashDiscountPercentage</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplimentedInvoiceId name="ComplimentedInvoiceId">ComplimentedInvoiceId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplimentedInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionReasonCode name="CorrectionReasonCode">CorrectionReasonCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowForecast name="CashFlowForecast">CashFlowForecast</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountId name="BankAccountId">BankAccountId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingClassificationId name="BillingClassificationId">BillingClassificationId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingClassificationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerReference name="CustomerReference">CustomerReference</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitMandateId name="DirectDebitMandateId">DirectDebitMandateId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitMandateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPostedViaIntercompany name="IsPostedViaIntercompany">IsPostedViaIntercompany</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPostedViaIntercompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceName name="InvoiceName">InvoiceName</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#numberSequenceGroup name="numberSequenceGroup">numberSequenceGroup</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberSequenceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOneTimeCustomer name="IsOneTimeCustomer">IsOneTimeCustomer</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOneTimeCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPayment name="TermsOfPayment">TermsOfPayment</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TermsOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSchedule name="PaymentSchedule">PaymentSchedule</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MethodOfPayment name="MethodOfPayment">MethodOfPayment</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MethodOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPosted name="IsPosted">IsPosted</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisition name="CustomerRequisition">CustomerRequisition</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupId name="SalesTaxGroupId">SalesTaxGroupId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroupId name="SalesTaxItemGroupId">SalesTaxItemGroupId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EInvoiceAccountCode name="EInvoiceAccountCode">EInvoiceAccountCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EInvoiceAccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EInvoiceIsLineSpecific name="EInvoiceIsLineSpecific">EInvoiceIsLineSpecific</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EInvoiceIsLineSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroType name="GiroType">GiroType</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLumpSumRecoveryTextPrinted name="IsLumpSumRecoveryTextPrinted">IsLumpSumRecoveryTextPrinted</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLumpSumRecoveryTextPrinted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerGroup name="CustomerGroup">CustomerGroup</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitMandateReference name="DirectDebitMandateReference">DirectDebitMandateReference</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitMandateReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesDate name="SalesDate">SalesDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VatDueDate name="VatDueDate">VatDueDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingClassification name="BillingClassification">BillingClassification</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InclTax name="InclTax">InclTax</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostponedVAT name="PostponedVAT">PostponedVAT</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostponedVAT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementaryFiscalDocumentType name="ComplementaryFiscalDocumentType">ComplementaryFiscalDocumentType</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementaryFiscalDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPTableRecId name="CFOPTableRecId">CFOPTableRecId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPTableRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFPSCode name="CFPSCode">CFPSCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFPSCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFinalUser name="IsFinalUser">IsFinalUser</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinalUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFineCode name="CustomerPaymentFineCode">CustomerPaymentFineCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentFineCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeRecId name="FiscalDocumentTypeRecId">FiscalDocumentTypeRecId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentRecId name="FiscalEstablishmentRecId">FiscalEstablishmentRecId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFinancialInterestCode name="CustomerPaymentFinancialInterestCode">CustomerPaymentFinancialInterestCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentFinancialInterestCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalOperationPresenceType name="FiscalOperationPresenceType">FiscalOperationPresenceType</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOperationPresenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPurchOperationTypeRecId name="SalesPurchOperationTypeRecId">SalesPurchOperationTypeRecId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPurchOperationTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsServiceDeliveryAddressBased name="IsServiceDeliveryAddressBased">IsServiceDeliveryAddressBased</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsServiceDeliveryAddressBased attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPCode name="CFOPCode">CFOPCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeId name="FiscalDocumentTypeId">FiscalDocumentTypeId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentOperationTypeId name="FiscalDocumentOperationTypeId">FiscalDocumentOperationTypeId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentOperationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDocumentLineId name="TransportationDocumentLineId">TransportationDocumentLineId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDocumentLineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalInvoiceId name="ExternalInvoiceId">ExternalInvoiceId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsigneeAccount name="ConsigneeAccount">ConsigneeAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsigneeAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsignorAccount name="ConsignorAccount">ConsignorAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsignorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCorrection name="IsCorrection">IsCorrection</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCorrection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedFactureDate name="CorrectedFactureDate">CorrectedFactureDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedFactureExternalId name="CorrectedFactureExternalId">CorrectedFactureExternalId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureExternalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedInvoiceDate name="CorrectedInvoiceDate">CorrectedInvoiceDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedInvoiceId name="CorrectedInvoiceId">CorrectedInvoiceId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedPeriod name="CorrectedPeriod">CorrectedPeriod</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionType name="CorrectionType">CorrectionType</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonRealRevenue name="NonRealRevenue">NonRealRevenue</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonRealRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATOnPayment name="VATOnPayment">VATOnPayment</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATOnPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceOriginCode name="InvoiceOriginCode">InvoiceOriginCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceOriginCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomerAccountRelationshipId name="Relationship_CustomerAccountRelationshipId">Relationship_CustomerAccountRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomerAccountRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InvoiceAccountRelationshipId name="Relationship_InvoiceAccountRelationshipId">Relationship_InvoiceAccountRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceAccountRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymTermRelationshipId name="Relationship_PaymTermRelationshipId">Relationship_PaymTermRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTermRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CashDiscRelationshipId name="Relationship_CashDiscRelationshipId">Relationship_CashDiscRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashDiscRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentScheduleRelationshipId name="Relationship_PaymentScheduleRelationshipId">Relationship_PaymentScheduleRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentScheduleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymModeRelationshipId name="Relationship_PaymModeRelationshipId">Relationship_PaymModeRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymModeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustomerInvoiceOriginRelationshipId name="Relationship_CustomerInvoiceOriginRelationshipId">Relationship_CustomerInvoiceOriginRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomerInvoiceOriginRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_CustInvoiceTableRelationshipId name="BackingTable_CustInvoiceTableRelationshipId">BackingTable_CustInvoiceTableRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

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

First included in: AccountsReceivable/FreeTextInvoiceHeaderEntity (this entity)  

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
