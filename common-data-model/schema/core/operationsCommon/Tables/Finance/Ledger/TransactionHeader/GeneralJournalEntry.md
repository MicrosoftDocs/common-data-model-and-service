---
title: GeneralJournalEntry - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# GeneralJournalEntry

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/TransactionHeader/GeneralJournalEntry.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalEntry/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[AccountingDate](#AccountingDate)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[AcknowledgementDate](#AcknowledgementDate)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[DocumentDate](#DocumentDate)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[DocumentNumber](#DocumentNumber)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[FiscalCalendarPeriod](#FiscalCalendarPeriod)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[FiscalCalendarYear](#FiscalCalendarYear)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[JournalCategory](#JournalCategory)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[JournalNumber](#JournalNumber)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Ledger](#Ledger)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[PostingLayer](#PostingLayer)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[SubledgerJournalEntry](#SubledgerJournalEntry)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[TransferId](#TransferId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[SubledgerVoucher](#SubledgerVoucher)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[SubledgerVoucherDataAreaId](#SubledgerVoucherDataAreaId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[LedgerEntryJournal](#LedgerEntryJournal)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[LedgerPostingJournal](#LedgerPostingJournal)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[LedgerPostingJournalDataAreaId](#LedgerPostingJournalDataAreaId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[BudgetSourceLedgerEntryPosted](#BudgetSourceLedgerEntryPosted)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Relationship_FiscalCalendarPeriodRelationshipId](#Relationship_FiscalCalendarPeriodRelationshipId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Relationship_FiscalCalendarYearRelationshipId](#Relationship_FiscalCalendarYearRelationshipId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Relationship_LedgerRelationshipId](#Relationship_LedgerRelationshipId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Relationship_TransactionLogRelationshipId](#Relationship_TransactionLogRelationshipId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Relationship_LedgerEntryJournalRelationshipId](#Relationship_LedgerEntryJournalRelationshipId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Relationship_LedgerPostingJournalRelationshipId](#Relationship_LedgerPostingJournalRelationshipId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Relationship_CustExchRateAdjustmentRelationshipId](#Relationship_CustExchRateAdjustmentRelationshipId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Relationship_BudgetSourceRelationshipId](#Relationship_BudgetSourceRelationshipId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|
|[Relationship_VendExchRateAdjustmentRelationshipId](#Relationship_VendExchRateAdjustmentRelationshipId)||<a href="GeneralJournalEntry.md" target="_blank">TransactionHeader/GeneralJournalEntry</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalEntry/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AcknowledgementDate name="AcknowledgementDate">AcknowledgementDate</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcknowledgementDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

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

### <a href=#FiscalCalendarPeriod name="FiscalCalendarPeriod">FiscalCalendarPeriod</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalCalendarYear name="FiscalCalendarYear">FiscalCalendarYear</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#JournalCategory name="JournalCategory">JournalCategory</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

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

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PostingLayer name="PostingLayer">PostingLayer</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLayer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SubledgerJournalEntry name="SubledgerJournalEntry">SubledgerJournalEntry</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubledgerJournalEntry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransferId name="TransferId">TransferId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SubledgerVoucher name="SubledgerVoucher">SubledgerVoucher</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubledgerVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubledgerVoucherDataAreaId name="SubledgerVoucherDataAreaId">SubledgerVoucherDataAreaId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubledgerVoucherDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerEntryJournal name="LedgerEntryJournal">LedgerEntryJournal</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerEntryJournal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerPostingJournal name="LedgerPostingJournal">LedgerPostingJournal</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPostingJournalDataAreaId name="LedgerPostingJournalDataAreaId">LedgerPostingJournalDataAreaId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingJournalDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetSourceLedgerEntryPosted name="BudgetSourceLedgerEntryPosted">BudgetSourceLedgerEntryPosted</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetSourceLedgerEntryPosted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_FiscalCalendarPeriodRelationshipId name="Relationship_FiscalCalendarPeriodRelationshipId">Relationship_FiscalCalendarPeriodRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalCalendarPeriodRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/FiscalCalendarPeriod.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Reference/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod</a></td><td><a href="../Reference/FiscalCalendarPeriod.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalCalendarYearRelationshipId name="Relationship_FiscalCalendarYearRelationshipId">Relationship_FiscalCalendarYearRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalCalendarYearRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/FiscalCalendarYear.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Reference/FiscalCalendarYear.cdm.json/FiscalCalendarYear</a></td><td><a href="../Reference/FiscalCalendarYear.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRelationshipId name="Relationship_LedgerRelationshipId">Relationship_LedgerRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/Ledger.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/Ledger.cdm.json/Ledger</a></td><td><a href="../Main/Ledger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransactionLogRelationshipId name="Relationship_TransactionLogRelationshipId">Relationship_TransactionLogRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransactionLogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TransactionLog.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Transaction/TransactionLog.cdm.json/TransactionLog</a></td><td><a href="../Transaction/TransactionLog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerEntryJournalRelationshipId name="Relationship_LedgerEntryJournalRelationshipId">Relationship_LedgerEntryJournalRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerEntryJournalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/LedgerEntryJournal.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Transaction/LedgerEntryJournal.cdm.json/LedgerEntryJournal</a></td><td><a href="../Transaction/LedgerEntryJournal.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerPostingJournalRelationshipId name="Relationship_LedgerPostingJournalRelationshipId">Relationship_LedgerPostingJournalRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerPostingJournalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/LedgerPostingJournal.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerPostingJournal.cdm.json/LedgerPostingJournal</a></td><td><a href="../Group/LedgerPostingJournal.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustExchRateAdjustmentRelationshipId name="Relationship_CustExchRateAdjustmentRelationshipId">Relationship_CustExchRateAdjustmentRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustExchRateAdjustmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Transaction/CustExchRateAdjustment.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/CustExchRateAdjustment.cdm.json/CustExchRateAdjustment</a></td><td><a href="../../Bank/Transaction/CustExchRateAdjustment.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetSourceRelationshipId name="Relationship_BudgetSourceRelationshipId">Relationship_BudgetSourceRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetSourceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Budget/Transaction/BudgetSource.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Transaction/BudgetSource.cdm.json/BudgetSource</a></td><td><a href="../../Budget/Transaction/BudgetSource.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendExchRateAdjustmentRelationshipId name="Relationship_VendExchRateAdjustmentRelationshipId">Relationship_VendExchRateAdjustmentRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendExchRateAdjustmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendExchRateAdjustment.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendExchRateAdjustment.cdm.json/VendExchRateAdjustment</a></td><td><a href="../../AccountsPayable/Transaction/VendExchRateAdjustment.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
