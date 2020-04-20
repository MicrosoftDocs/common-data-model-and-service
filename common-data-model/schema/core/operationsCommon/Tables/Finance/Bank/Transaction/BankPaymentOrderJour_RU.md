---
title: BankPaymentOrderJour_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# BankPaymentOrderJour_RU

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/Transaction/BankPaymentOrderJour_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankPaymentOrderJour_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[AccountNumForeignRecipient](#AccountNumForeignRecipient)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[AccountNumPayer](#AccountNumPayer)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[AccountNumRecipient](#AccountNumRecipient)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[AmountCur](#AmountCur)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[BankAccountCurrency](#BankAccountCurrency)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[BankCentralBankPurposeCode](#BankCentralBankPurposeCode)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[BankClientDocumentTypeId](#BankClientDocumentTypeId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[BankCurrencyTransferLog_RU](#BankCurrencyTransferLog_RU)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[BankIdPayer](#BankIdPayer)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[BankIdRecipient](#BankIdRecipient)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[BankTransactionType](#BankTransactionType)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[CommBankAccountPayer](#CommBankAccountPayer)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[CompanyRecipient](#CompanyRecipient)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[CorrBankRecipient](#CorrBankRecipient)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[CurrencyCode](#CurrencyCode)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[CustVendPaymAccount](#CustVendPaymAccount)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[ElectronicPayment](#ElectronicPayment)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[FreeFormat](#FreeFormat)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[JournalLineNum](#JournalLineNum)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[JournalNum](#JournalNum)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[JournalTransDate](#JournalTransDate)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[LedgerACType](#LedgerACType)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[OrderOfPayment](#OrderOfPayment)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymBaseCode](#PaymBaseCode)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymBudgetReceiptClassCode](#PaymBudgetReceiptClassCode)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymDocDate](#PaymDocDate)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymDocNum](#PaymDocNum)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymentOrderNum](#PaymentOrderNum)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymentTransDate](#PaymentTransDate)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymentTransDueDate](#PaymentTransDueDate)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymMode](#PaymMode)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymOrderType](#PaymOrderType)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymPeriodCode](#PaymPeriodCode)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymPeriodNumber](#PaymPeriodNumber)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymSpec](#PaymSpec)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymStatusCode](#PaymStatusCode)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymTaxPeriodDate](#PaymTaxPeriodDate)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PaymTypeCode](#PaymTypeCode)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PrintKPP](#PrintKPP)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[PurposeOfPayment](#PurposeOfPayment)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[RecipientRCOAD](#RecipientRCOAD)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[TransTypeCur](#TransTypeCur)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Voucher](#Voucher)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[WorkerResponsible](#WorkerResponsible)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Year](#Year)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[YourCharges](#YourCharges)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[YourCorrCharges](#YourCorrCharges)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[UIN](#UIN)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_BankAccountTable_PayerRelationshipId](#Relationship_BankAccountTable_PayerRelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_BankAccountTable_RecipientRelationshipId](#Relationship_BankAccountTable_RecipientRelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_BankAccountTransRelationshipId](#Relationship_BankAccountTransRelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_BankCentralBankPurposeRelationshipId](#Relationship_BankCentralBankPurposeRelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_BankClientDocumentType_RURelationshipId](#Relationship_BankClientDocumentType_RURelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_BankCurrencyTransferLog_RURelationshipId](#Relationship_BankCurrencyTransferLog_RURelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_BankTransTypeRelationshipId](#Relationship_BankTransTypeRelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_LedgerJournalTableRelationshipId](#Relationship_LedgerJournalTableRelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId](#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId](#Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_PaymentOrderStatusTable_RURelationshipId](#Relationship_PaymentOrderStatusTable_RURelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_PaymentOrderTypeTable_RURelationshipId](#Relationship_PaymentOrderTypeTable_RURelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="BankPaymentOrderJour_RU.md" target="_blank">Transaction/BankPaymentOrderJour_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankPaymentOrderJour_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountNumForeignRecipient name="AccountNumForeignRecipient">AccountNumForeignRecipient</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNumForeignRecipient attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNumPayer name="AccountNumPayer">AccountNumPayer</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNumPayer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNumRecipient name="AccountNumRecipient">AccountNumRecipient</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNumRecipient attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountCur name="AmountCur">AmountCur</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankAccountCurrency name="BankAccountCurrency">BankAccountCurrency</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountCurrency attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankCentralBankPurposeCode name="BankCentralBankPurposeCode">BankCentralBankPurposeCode</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCentralBankPurposeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankClientDocumentTypeId name="BankClientDocumentTypeId">BankClientDocumentTypeId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankClientDocumentTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankCurrencyTransferLog_RU name="BankCurrencyTransferLog_RU">BankCurrencyTransferLog_RU</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCurrencyTransferLog_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankIdPayer name="BankIdPayer">BankIdPayer</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankIdPayer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankIdRecipient name="BankIdRecipient">BankIdRecipient</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankIdRecipient attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankTransactionType name="BankTransactionType">BankTransactionType</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommBankAccountPayer name="CommBankAccountPayer">CommBankAccountPayer</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommBankAccountPayer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyRecipient name="CompanyRecipient">CompanyRecipient</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyRecipient attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrBankRecipient name="CorrBankRecipient">CorrBankRecipient</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrBankRecipient attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

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

### <a href=#CustVendPaymAccount name="CustVendPaymAccount">CustVendPaymAccount</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendPaymAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicPayment name="ElectronicPayment">ElectronicPayment</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FreeFormat name="FreeFormat">FreeFormat</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalLineNum name="JournalLineNum">JournalLineNum</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#JournalNum name="JournalNum">JournalNum</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalTransDate name="JournalTransDate">JournalTransDate</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LedgerACType name="LedgerACType">LedgerACType</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerACType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OrderOfPayment name="OrderOfPayment">OrderOfPayment</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymBaseCode name="PaymBaseCode">PaymBaseCode</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymBaseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymBudgetReceiptClassCode name="PaymBudgetReceiptClassCode">PaymBudgetReceiptClassCode</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymBudgetReceiptClassCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymDocDate name="PaymDocDate">PaymDocDate</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymDocDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PaymDocNum name="PaymDocNum">PaymDocNum</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymDocNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentOrderNum name="PaymentOrderNum">PaymentOrderNum</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentOrderNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTransDate name="PaymentTransDate">PaymentTransDate</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PaymentTransDueDate name="PaymentTransDueDate">PaymentTransDueDate</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTransDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PaymMode name="PaymMode">PaymMode</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymOrderType name="PaymOrderType">PaymOrderType</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymOrderType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymPeriodCode name="PaymPeriodCode">PaymPeriodCode</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymPeriodCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymPeriodNumber name="PaymPeriodNumber">PaymPeriodNumber</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymPeriodNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymSpec name="PaymSpec">PaymSpec</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymSpec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymStatusCode name="PaymStatusCode">PaymStatusCode</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymStatusCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymTaxPeriodDate name="PaymTaxPeriodDate">PaymTaxPeriodDate</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymTaxPeriodDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PaymTypeCode name="PaymTypeCode">PaymTypeCode</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintKPP name="PrintKPP">PrintKPP</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintKPP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurposeOfPayment name="PurposeOfPayment">PurposeOfPayment</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurposeOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecipientRCOAD name="RecipientRCOAD">RecipientRCOAD</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecipientRCOAD attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransTypeCur name="TransTypeCur">TransTypeCur</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransTypeCur attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

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

### <a href=#WorkerResponsible name="WorkerResponsible">WorkerResponsible</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerResponsible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Year name="Year">Year</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Year attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#YourCharges name="YourCharges">YourCharges</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YourCharges attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#YourCorrCharges name="YourCorrCharges">YourCorrCharges</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YourCorrCharges attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UIN name="UIN">UIN</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UIN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

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

### <a href=#Relationship_BankAccountTable_PayerRelationshipId name="Relationship_BankAccountTable_PayerRelationshipId">Relationship_BankAccountTable_PayerRelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankAccountTable_PayerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/BankAccountTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/BankAccountTable.cdm.json/BankAccountTable</a></td><td><a href="../Main/BankAccountTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankAccountTable_RecipientRelationshipId name="Relationship_BankAccountTable_RecipientRelationshipId">Relationship_BankAccountTable_RecipientRelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankAccountTable_RecipientRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/BankAccountTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/BankAccountTable.cdm.json/BankAccountTable</a></td><td><a href="../Main/BankAccountTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankAccountTransRelationshipId name="Relationship_BankAccountTransRelationshipId">Relationship_BankAccountTransRelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankAccountTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankAccountTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankAccountTrans.cdm.json/BankAccountTrans</a></td><td><a href="BankAccountTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankCentralBankPurposeRelationshipId name="Relationship_BankCentralBankPurposeRelationshipId">Relationship_BankCentralBankPurposeRelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankCentralBankPurposeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BankCentralBankPurpose.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankCentralBankPurpose.cdm.json/BankCentralBankPurpose</a></td><td><a href="../Group/BankCentralBankPurpose.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankClientDocumentType_RURelationshipId name="Relationship_BankClientDocumentType_RURelationshipId">Relationship_BankClientDocumentType_RURelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankClientDocumentType_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BankClientDocumentType_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankClientDocumentType_RU.cdm.json/BankClientDocumentType_RU</a></td><td><a href="../Group/BankClientDocumentType_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankCurrencyTransferLog_RURelationshipId name="Relationship_BankCurrencyTransferLog_RURelationshipId">Relationship_BankCurrencyTransferLog_RURelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankCurrencyTransferLog_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankCurrencyTransferLog_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankCurrencyTransferLog_RU.cdm.json/BankCurrencyTransferLog_RU</a></td><td><a href="BankCurrencyTransferLog_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankTransTypeRelationshipId name="Relationship_BankTransTypeRelationshipId">Relationship_BankTransTypeRelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankTransTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BankTransType.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankTransType.cdm.json/BankTransType</a></td><td><a href="../Group/BankTransType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

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

### <a href=#Relationship_LedgerJournalTableRelationshipId name="Relationship_LedgerJournalTableRelationshipId">Relationship_LedgerJournalTableRelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

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

### <a href=#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId name="Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId">Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentOrderBudgetReceiptClassTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.cdm.json/PaymentOrderBudgetReceiptClassTable_RU</a></td><td><a href="../Main/PaymentOrderBudgetReceiptClassTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId name="Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId">Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentOrderPaymBaseCodeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderPaymBaseCodeTable_RU.cdm.json/PaymentOrderPaymBaseCodeTable_RU</a></td><td><a href="../Main/PaymentOrderPaymBaseCodeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentOrderStatusTable_RURelationshipId name="Relationship_PaymentOrderStatusTable_RURelationshipId">Relationship_PaymentOrderStatusTable_RURelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderStatusTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentOrderStatusTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderStatusTable_RU.cdm.json/PaymentOrderStatusTable_RU</a></td><td><a href="../Main/PaymentOrderStatusTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentOrderTypeTable_RURelationshipId name="Relationship_PaymentOrderTypeTable_RURelationshipId">Relationship_PaymentOrderTypeTable_RURelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderTypeTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentOrderTypeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderTypeTable_RU.cdm.json/PaymentOrderTypeTable_RU</a></td><td><a href="../Main/PaymentOrderTypeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/BankPaymentOrderJour_RU (this entity)  

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
