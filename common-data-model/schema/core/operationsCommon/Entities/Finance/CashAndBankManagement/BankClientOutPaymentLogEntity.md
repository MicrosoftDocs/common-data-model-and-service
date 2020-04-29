---
title: BankClientOutPaymentLogEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Exported payments

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankClientOutPaymentLogEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exported payments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AmountInTransactionCurrency](#AmountInTransactionCurrency)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[BankAccount](#BankAccount)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[Currency](#Currency)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[Counteragent](#Counteragent)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[DocumentType](#DocumentType)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[DateAndTime](#DateAndTime)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[JournalNumber](#JournalNumber)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[AccountType](#AccountType)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[OrderDate](#OrderDate)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[OrderNumber](#OrderNumber)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[MethodOfPayment](#MethodOfPayment)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[PaymentOrderStatus](#PaymentOrderStatus)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[Date](#Date)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[Voucher](#Voucher)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[BankCurrencyTransfer](#BankCurrencyTransfer)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[PaymentOrderNumber](#PaymentOrderNumber)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[PaymentOrderDate](#PaymentOrderDate)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[BackingTable_BankClientOutPaymentLog_RURelationshipId](#BackingTable_BankClientOutPaymentLog_RURelationshipId)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankClientOutPaymentLogEntity.md" target="_blank">CashAndBankManagement/BankClientOutPaymentLogEntity</a>|

### <a href=#AmountInTransactionCurrency name="AmountInTransactionCurrency">AmountInTransactionCurrency</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccount name="BankAccount">BankAccount</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

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

### <a href=#Currency name="Currency">Currency</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

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

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

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

### <a href=#DocumentType name="DocumentType">DocumentType</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

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

### <a href=#DateAndTime name="DateAndTime">DateAndTime</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateAndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

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

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderDate name="OrderDate">OrderDate</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderNumber name="OrderNumber">OrderNumber</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MethodOfPayment name="MethodOfPayment">MethodOfPayment</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

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

### <a href=#PaymentOrderStatus name="PaymentOrderStatus">PaymentOrderStatus</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Date name="Date">Date</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Date attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

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

### <a href=#BankCurrencyTransfer name="BankCurrencyTransfer">BankCurrencyTransfer</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCurrencyTransfer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentOrderNumber name="PaymentOrderNumber">PaymentOrderNumber</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentOrderDate name="PaymentOrderDate">PaymentOrderDate</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentOrderDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BankClientOutPaymentLog_RURelationshipId name="BackingTable_BankClientOutPaymentLog_RURelationshipId">BackingTable_BankClientOutPaymentLog_RURelationshipId</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankClientOutPaymentLog_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Transaction/BankClientOutPaymentLog_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankClientOutPaymentLog_RU.cdm.json/BankClientOutPaymentLog_RU</a></td><td><a href="../../../Tables/Finance/Bank/Transaction/BankClientOutPaymentLog_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankClientOutPaymentLogEntity (this entity)  

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
