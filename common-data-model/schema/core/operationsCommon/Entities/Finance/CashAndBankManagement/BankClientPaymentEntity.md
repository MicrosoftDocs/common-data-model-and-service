---
title: BankClientPaymentEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Payments by Client-Bank data

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankClientPaymentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payments by Client-Bank data</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BankAccount](#BankAccount)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[AgreementNumberLocking](#AgreementNumberLocking)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Amount](#Amount)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[BankExchangeRate](#BankExchangeRate)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[BankTransactionType](#BankTransactionType)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Currency](#Currency)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Counteragent](#Counteragent)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Dimension](#Dimension)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[DocumentNumber](#DocumentNumber)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[DocumentType](#DocumentType)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Include](#Include)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[JournalNumber](#JournalNumber)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[CounteragentType](#CounteragentType)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayeeAccountNumber](#PayeeAccountNumber)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayeeBankAccountNumber](#PayeeBankAccountNumber)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayeeBankAddress](#PayeeBankAddress)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayeeBankBIC](#PayeeBankBIC)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayeeBankCorrAccount](#PayeeBankCorrAccount)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayeeBankName](#PayeeBankName)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayeeINN](#PayeeINN)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Recipient](#Recipient)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayeeRegistryReasonCode](#PayeeRegistryReasonCode)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayerAccountNumber](#PayerAccountNumber)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayerBankAccountNumber](#PayerBankAccountNumber)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayerBankAddress](#PayerBankAddress)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayerBankBIC](#PayerBankBIC)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayerBankCorrAccount](#PayerBankCorrAccount)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayerBankName](#PayerBankName)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayerINN](#PayerINN)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Payer](#Payer)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PayerRegistryReasonCode](#PayerRegistryReasonCode)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PaymentDirection](#PaymentDirection)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PurposeText](#PurposeText)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Posted](#Posted)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PostingProfile](#PostingProfile)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[PrepaymentJournalVoucher](#PrepaymentJournalVoucher)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[ReceiptDate](#ReceiptDate)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[QuittanceContent](#QuittanceContent)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[QuittanceDate](#QuittanceDate)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[QuittanceTime](#QuittanceTime)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[ItemSalesTaxGroup](#ItemSalesTaxGroup)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[CurrencyOfConversion](#CurrencyOfConversion)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[AmbiguousText](#AmbiguousText)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[ErrorCause](#ErrorCause)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Error](#Error)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Voucher](#Voucher)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[WithdrawalDate](#WithdrawalDate)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[UCI](#UCI)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[AgreementId](#AgreementId)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[BackingTable_BankClientPayment_RURelationshipId](#BackingTable_BankClientPayment_RURelationshipId)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankClientPaymentEntity.md" target="_blank">CashAndBankManagement/BankClientPaymentEntity</a>|

### <a href=#BankAccount name="BankAccount">BankAccount</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementNumberLocking name="AgreementNumberLocking">AgreementNumberLocking</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementNumberLocking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankExchangeRate name="BankExchangeRate">BankExchangeRate</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankTransactionType name="BankTransactionType">BankTransactionType</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

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

### <a href=#Currency name="Currency">Currency</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Counteragent name="Counteragent">Counteragent</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Counteragent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension name="Dimension">Dimension</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

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

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentType name="DocumentType">DocumentType</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

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

### <a href=#Include name="Include">Include</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Include attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CounteragentType name="CounteragentType">CounteragentType</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CounteragentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeAccountNumber name="PayeeAccountNumber">PayeeAccountNumber</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankAccountNumber name="PayeeBankAccountNumber">PayeeBankAccountNumber</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankAddress name="PayeeBankAddress">PayeeBankAddress</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankBIC name="PayeeBankBIC">PayeeBankBIC</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankBIC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankCorrAccount name="PayeeBankCorrAccount">PayeeBankCorrAccount</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankCorrAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeBankName name="PayeeBankName">PayeeBankName</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeINN name="PayeeINN">PayeeINN</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeINN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Recipient name="Recipient">Recipient</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Recipient attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeRegistryReasonCode name="PayeeRegistryReasonCode">PayeeRegistryReasonCode</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeRegistryReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerAccountNumber name="PayerAccountNumber">PayerAccountNumber</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankAccountNumber name="PayerBankAccountNumber">PayerBankAccountNumber</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankAddress name="PayerBankAddress">PayerBankAddress</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankBIC name="PayerBankBIC">PayerBankBIC</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankBIC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankCorrAccount name="PayerBankCorrAccount">PayerBankCorrAccount</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankCorrAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerBankName name="PayerBankName">PayerBankName</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerINN name="PayerINN">PayerINN</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerINN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Payer name="Payer">Payer</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Payer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayerRegistryReasonCode name="PayerRegistryReasonCode">PayerRegistryReasonCode</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayerRegistryReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDirection name="PaymentDirection">PaymentDirection</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurposeText name="PurposeText">PurposeText</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurposeText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

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

### <a href=#PrepaymentJournalVoucher name="PrepaymentJournalVoucher">PrepaymentJournalVoucher</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentJournalVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptDate name="ReceiptDate">ReceiptDate</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuittanceContent name="QuittanceContent">QuittanceContent</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuittanceContent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuittanceDate name="QuittanceDate">QuittanceDate</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuittanceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuittanceTime name="QuittanceTime">QuittanceTime</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuittanceTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroup name="ItemSalesTaxGroup">ItemSalesTaxGroup</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyOfConversion name="CurrencyOfConversion">CurrencyOfConversion</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyOfConversion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmbiguousText name="AmbiguousText">AmbiguousText</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmbiguousText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorCause name="ErrorCause">ErrorCause</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorCause attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Error name="Error">Error</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Error attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

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

### <a href=#WithdrawalDate name="WithdrawalDate">WithdrawalDate</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithdrawalDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UCI name="UCI">UCI</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UCI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementId name="AgreementId">AgreementId</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BankClientPayment_RURelationshipId name="BackingTable_BankClientPayment_RURelationshipId">BackingTable_BankClientPayment_RURelationshipId</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankClientPayment_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Transaction/BankClientPayment_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankClientPayment_RU.cdm.json/BankClientPayment_RU</a></td><td><a href="../../../Tables/Finance/Bank/Transaction/BankClientPayment_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankClientPaymentEntity (this entity)  

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
