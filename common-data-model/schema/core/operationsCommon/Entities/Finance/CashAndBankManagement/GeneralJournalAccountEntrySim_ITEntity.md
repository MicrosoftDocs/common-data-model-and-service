---
title: GeneralJournalAccountEntrySim_ITEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# GeneralJournalAccountEntrySim_ITEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[JournalNumber](#JournalNumber)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[Voucher](#Voucher)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[AccountingDate](#AccountingDate)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[PostingLayer](#PostingLayer)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[LedgerAccount](#LedgerAccount)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[TransactionCurrencyCode](#TransactionCurrencyCode)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[TransactionCurrencyCreditAmount](#TransactionCurrencyCreditAmount)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[TransactionCurrencyDebitAmount](#TransactionCurrencyDebitAmount)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[TransactionCurrencyAmount](#TransactionCurrencyAmount)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[AccountingCurrencyAmount](#AccountingCurrencyAmount)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[ReportingCurrencyAmount](#ReportingCurrencyAmount)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[Description](#Description)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[Quantity](#Quantity)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[PostingType](#PostingType)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[JournalCategory](#JournalCategory)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[IsCorrection](#IsCorrection)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[IsCredit](#IsCredit)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[AcknowledgementDate](#AcknowledgementDate)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[DocumentNumber](#DocumentNumber)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[LedgerName](#LedgerName)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[DataArea](#DataArea)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[GeneralJournalAccountEntryRecId](#GeneralJournalAccountEntryRecId)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|
|[BackingTable_GeneralJournalAccountEntrySim_ITRelationshipId](#BackingTable_GeneralJournalAccountEntrySim_ITRelationshipId)||<a href="GeneralJournalAccountEntrySim_ITEntity.md" target="_blank">CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity</a>|

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

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

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

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

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingLayer name="PostingLayer">PostingLayer</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLayer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAccount name="LedgerAccount">LedgerAccount</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyCode name="TransactionCurrencyCode">TransactionCurrencyCode</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyCreditAmount name="TransactionCurrencyCreditAmount">TransactionCurrencyCreditAmount</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyCreditAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyDebitAmount name="TransactionCurrencyDebitAmount">TransactionCurrencyDebitAmount</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyDebitAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount name="TransactionCurrencyAmount">TransactionCurrencyAmount</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingCurrencyAmount name="AccountingCurrencyAmount">AccountingCurrencyAmount</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyAmount name="ReportingCurrencyAmount">ReportingCurrencyAmount</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingType name="PostingType">PostingType</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalCategory name="JournalCategory">JournalCategory</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCorrection name="IsCorrection">IsCorrection</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

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

### <a href=#IsCredit name="IsCredit">IsCredit</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcknowledgementDate name="AcknowledgementDate">AcknowledgementDate</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcknowledgementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

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

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

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

### <a href=#LedgerName name="LedgerName">LedgerName</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataArea name="DataArea">DataArea</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralJournalAccountEntryRecId name="GeneralJournalAccountEntryRecId">GeneralJournalAccountEntryRecId</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralJournalAccountEntryRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_GeneralJournalAccountEntrySim_ITRelationshipId name="BackingTable_GeneralJournalAccountEntrySim_ITRelationshipId">BackingTable_GeneralJournalAccountEntrySim_ITRelationshipId</a>

First included in: CashAndBankManagement/GeneralJournalAccountEntrySim_ITEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_GeneralJournalAccountEntrySim_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/TransactionLine/GeneralJournalAccountEntrySim_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/TransactionLine/GeneralJournalAccountEntrySim_IT.cdm.json/GeneralJournalAccountEntrySim_IT</a></td><td><a href="../../../Tables/Finance/Ledger/TransactionLine/GeneralJournalAccountEntrySim_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
