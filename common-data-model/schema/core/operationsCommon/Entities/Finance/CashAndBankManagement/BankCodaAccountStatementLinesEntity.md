---
title: BankCodaAccountStatementLinesEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Bank statement details

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankCodaAccountStatementLinesEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank statement details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BankAccount](#BankAccount)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[BankStatement](#BankStatement)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[AccountType](#AccountType)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[AmountInAccountingCurrency](#AmountInAccountingCurrency)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[AmountImported](#AmountImported)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Amount](#Amount)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[BankReferenceNumber](#BankReferenceNumber)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[CashDiscountLinked](#CashDiscountLinked)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[SettlementType](#SettlementType)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[CustomerReference](#CustomerReference)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Date](#Date)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Detail](#Detail)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[ExternalBankReferenceNumber](#ExternalBankReferenceNumber)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[GlobalizationCODA](#GlobalizationCODA)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[HasProcessErrors](#HasProcessErrors)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[InvoiceNumber](#InvoiceNumber)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Account](#Account)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Note](#Note)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Message](#Message)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[MessageType](#MessageType)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Currency](#Currency)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[OppositePartyAddress](#OppositePartyAddress)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[BankAccountNumber](#BankAccountNumber)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[OppositePartyCity](#OppositePartyCity)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[CustomerOrVendorAccountNumber](#CustomerOrVendorAccountNumber)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[OppositePartyInternalCodes](#OppositePartyInternalCodes)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[OppositePartyName](#OppositePartyName)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Completed](#Completed)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Reference](#Reference)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[BankStatementDate](#BankStatementDate)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[AssociatedPaymentAttachment](#AssociatedPaymentAttachment)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[ItemSalesTaxGroup](#ItemSalesTaxGroup)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Transaction](#Transaction)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[TransactionCategory](#TransactionCategory)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[TransactionGroup](#TransactionGroup)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[TransactionType](#TransactionType)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Date1](#Date1)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[GUID](#GUID)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[BankCodaAccountStatementLines1_LineId](#BankCodaAccountStatementLines1_LineId)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[AccountDisplayValue](#AccountDisplayValue)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[GlobalisationId](#GlobalisationId)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Relationship_AccountCombinationRelationshipId](#Relationship_AccountCombinationRelationshipId)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[BackingTable_BankCodaAccountStatementLinesRelationshipId](#BackingTable_BankCodaAccountStatementLinesRelationshipId)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankCodaAccountStatementLinesEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementLinesEntity</a>|

### <a href=#BankAccount name="BankAccount">BankAccount</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatement name="BankStatement">BankStatement</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInAccountingCurrency name="AmountInAccountingCurrency">AmountInAccountingCurrency</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountImported name="AmountImported">AmountImported</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountImported attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankReferenceNumber name="BankReferenceNumber">BankReferenceNumber</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountLinked name="CashDiscountLinked">CashDiscountLinked</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountLinked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementType name="SettlementType">SettlementType</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerReference name="CustomerReference">CustomerReference</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

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

### <a href=#Date name="Date">Date</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Date attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Detail name="Detail">Detail</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Detail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalBankReferenceNumber name="ExternalBankReferenceNumber">ExternalBankReferenceNumber</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalBankReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GlobalizationCODA name="GlobalizationCODA">GlobalizationCODA</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GlobalizationCODA attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasProcessErrors name="HasProcessErrors">HasProcessErrors</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasProcessErrors attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceNumber name="InvoiceNumber">InvoiceNumber</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Account name="Account">Account</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Account attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Note attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Message name="Message">Message</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Message attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MessageType name="MessageType">MessageType</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OppositePartyAddress name="OppositePartyAddress">OppositePartyAddress</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OppositePartyAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountNumber name="BankAccountNumber">BankAccountNumber</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OppositePartyCity name="OppositePartyCity">OppositePartyCity</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OppositePartyCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerOrVendorAccountNumber name="CustomerOrVendorAccountNumber">CustomerOrVendorAccountNumber</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerOrVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OppositePartyInternalCodes name="OppositePartyInternalCodes">OppositePartyInternalCodes</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OppositePartyInternalCodes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OppositePartyName name="OppositePartyName">OppositePartyName</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OppositePartyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Completed name="Completed">Completed</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Completed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementDate name="BankStatementDate">BankStatementDate</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssociatedPaymentAttachment name="AssociatedPaymentAttachment">AssociatedPaymentAttachment</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociatedPaymentAttachment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

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

### <a href=#ItemSalesTaxGroup name="ItemSalesTaxGroup">ItemSalesTaxGroup</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transaction name="Transaction">Transaction</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCategory name="TransactionCategory">TransactionCategory</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionGroup name="TransactionGroup">TransactionGroup</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionType name="TransactionType">TransactionType</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Date1 name="Date1">Date1</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Date1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GUID name="GUID">GUID</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GUID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankCodaAccountStatementLines1_LineId name="BankCodaAccountStatementLines1_LineId">BankCodaAccountStatementLines1_LineId</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCodaAccountStatementLines1_LineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountDisplayValue name="AccountDisplayValue">AccountDisplayValue</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GlobalisationId name="GlobalisationId">GlobalisationId</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GlobalisationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccountCombinationRelationshipId name="Relationship_AccountCombinationRelationshipId">Relationship_AccountCombinationRelationshipId</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BankCodaAccountStatementLinesRelationshipId name="BackingTable_BankCodaAccountStatementLinesRelationshipId">BackingTable_BankCodaAccountStatementLinesRelationshipId</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankCodaAccountStatementLinesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/TransactionLine/BankCodaAccountStatementLines.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/TransactionLine/BankCodaAccountStatementLines.cdm.json/BankCodaAccountStatementLines</a></td><td><a href="../../../Tables/Finance/Bank/TransactionLine/BankCodaAccountStatementLines.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankCodaAccountStatementLinesEntity (this entity)  

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
