---
title: BankStatementLineEntity in CashAndBankManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Bank statement report entry in CashAndBankManagement(BankStatementLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankStatementLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank statement report entry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LineAmount](#LineAmount)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[AccountServicerReference](#AccountServicerReference)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[AdditionalEntryInformation](#AdditionalEntryInformation)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[AmountCreditDebitIndicator](#AmountCreditDebitIndicator)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankStatementCounterCurrency](#BankStatementCounterCurrency)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankStatementCounterCurrencyAmount](#BankStatementCounterCurrencyAmount)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankDocumentNumber](#BankDocumentNumber)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankStatementCounterExchangeRate](#BankStatementCounterExchangeRate)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BookingDateTime](#BookingDateTime)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[EntryReference](#EntryReference)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankStatementLineStatus](#BankStatementLineStatus)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[ProprietaryBankTransactionCode](#ProprietaryBankTransactionCode)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[ReferenceNumber](#ReferenceNumber)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[RelatedBankName](#RelatedBankName)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[RelatedBankAccount](#RelatedBankAccount)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[ReversalIndicator](#ReversalIndicator)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[TradingParty](#TradingParty)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankStmtISOAccountStatement](#BankStmtISOAccountStatement)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[ReportEntryTradingPartyName](#ReportEntryTradingPartyName)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[ReportEntryTradingPartyId](#ReportEntryTradingPartyId)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankStmtISOReportEntry](#BankStmtISOReportEntry)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[AmountLineAmount](#AmountLineAmount)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[AmountActualDate](#AmountActualDate)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[AmountNumberOfDays](#AmountNumberOfDays)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[StatementLineLineNum](#StatementLineLineNum)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[AmountLineNum](#AmountLineNum)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[DocumentLineNum](#DocumentLineNum)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[StatementLineNum](#StatementLineNum)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankStatementInstructedCurrency](#BankStatementInstructedCurrency)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankStatementInstructedCurrencyAmt](#BankStatementInstructedCurrencyAmt)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BankStatementInstructedExchangeRate](#BankStatementInstructedExchangeRate)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[CreditorReferenceInformation](#CreditorReferenceInformation)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[Relationship_BankStatementEntityRelationshipId](#Relationship_BankStatementEntityRelationshipId)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[BackingTable_BankStmtISOReportEntryRelationshipId](#BackingTable_BankStmtISOReportEntryRelationshipId)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankStatementLineEntity.md" target="_blank">CashAndBankManagement/BankStatementLineEntity</a>|

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountServicerReference name="AccountServicerReference">AccountServicerReference</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountServicerReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdditionalEntryInformation name="AdditionalEntryInformation">AdditionalEntryInformation</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdditionalEntryInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountCreditDebitIndicator name="AmountCreditDebitIndicator">AmountCreditDebitIndicator</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCreditDebitIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementCounterCurrency name="BankStatementCounterCurrency">BankStatementCounterCurrency</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementCounterCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementCounterCurrencyAmount name="BankStatementCounterCurrencyAmount">BankStatementCounterCurrencyAmount</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementCounterCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankDocumentNumber name="BankDocumentNumber">BankDocumentNumber</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementCounterExchangeRate name="BankStatementCounterExchangeRate">BankStatementCounterExchangeRate</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementCounterExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookingDateTime name="BookingDateTime">BookingDateTime</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookingDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryReference name="EntryReference">EntryReference</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementLineStatus name="BankStatementLineStatus">BankStatementLineStatus</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementLineStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProprietaryBankTransactionCode name="ProprietaryBankTransactionCode">ProprietaryBankTransactionCode</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProprietaryBankTransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceNumber name="ReferenceNumber">ReferenceNumber</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelatedBankName name="RelatedBankName">RelatedBankName</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelatedBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelatedBankAccount name="RelatedBankAccount">RelatedBankAccount</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelatedBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReversalIndicator name="ReversalIndicator">ReversalIndicator</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversalIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradingParty name="TradingParty">TradingParty</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradingParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStmtISOAccountStatement name="BankStmtISOAccountStatement">BankStmtISOAccountStatement</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStmtISOAccountStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportEntryTradingPartyName name="ReportEntryTradingPartyName">ReportEntryTradingPartyName</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportEntryTradingPartyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportEntryTradingPartyId name="ReportEntryTradingPartyId">ReportEntryTradingPartyId</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportEntryTradingPartyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStmtISOReportEntry name="BankStmtISOReportEntry">BankStmtISOReportEntry</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStmtISOReportEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountLineAmount name="AmountLineAmount">AmountLineAmount</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountActualDate name="AmountActualDate">AmountActualDate</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountActualDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountNumberOfDays name="AmountNumberOfDays">AmountNumberOfDays</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountNumberOfDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementLineLineNum name="StatementLineLineNum">StatementLineLineNum</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementLineLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountLineNum name="AmountLineNum">AmountLineNum</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentLineNum name="DocumentLineNum">DocumentLineNum</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementLineNum name="StatementLineNum">StatementLineNum</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementInstructedCurrency name="BankStatementInstructedCurrency">BankStatementInstructedCurrency</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementInstructedCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementInstructedCurrencyAmt name="BankStatementInstructedCurrencyAmt">BankStatementInstructedCurrencyAmt</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementInstructedCurrencyAmt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementInstructedExchangeRate name="BankStatementInstructedExchangeRate">BankStatementInstructedExchangeRate</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementInstructedExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditorReferenceInformation name="CreditorReferenceInformation">CreditorReferenceInformation</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditorReferenceInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankStatementEntityRelationshipId name="Relationship_BankStatementEntityRelationshipId">Relationship_BankStatementEntityRelationshipId</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankStatementEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BankStmtISOReportEntryRelationshipId name="BackingTable_BankStmtISOReportEntryRelationshipId">BackingTable_BankStmtISOReportEntryRelationshipId</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankStmtISOReportEntryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Transaction/BankStmtISOReportEntry.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankStmtISOReportEntry.cdm.json/BankStmtISOReportEntry</a></td><td><a href="../../../Tables/Finance/Bank/Transaction/BankStmtISOReportEntry.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankStatementLineEntity (this entity)  

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
