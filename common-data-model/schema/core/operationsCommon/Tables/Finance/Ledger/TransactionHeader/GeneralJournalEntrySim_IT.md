---
title: GeneralJournalEntrySim_IT in TransactionHeader - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# General journal entry in TransactionHeader(GeneralJournalEntrySim_IT)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/TransactionHeader/GeneralJournalEntrySim_IT.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalEntrySim_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>General journal entry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[AccountingDate](#AccountingDate)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[AcknowledgementDate](#AcknowledgementDate)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[DocumentDate](#DocumentDate)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[DocumentNumber](#DocumentNumber)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[FiscalCalendarPeriod](#FiscalCalendarPeriod)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[FiscalCalendarYear](#FiscalCalendarYear)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[JournalCategory](#JournalCategory)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[JournalNumber](#JournalNumber)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[Ledger](#Ledger)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[LedgerEntryJournal](#LedgerEntryJournal)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[LedgerPostingJournal](#LedgerPostingJournal)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[LedgerPostingJournalDataAreaId](#LedgerPostingJournalDataAreaId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[PostingLayer](#PostingLayer)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[SimulationJournalNameDataAreaId](#SimulationJournalNameDataAreaId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[SimulationJournalNameId](#SimulationJournalNameId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[SubledgerVoucher](#SubledgerVoucher)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[SubledgerVoucherDataAreaId](#SubledgerVoucherDataAreaId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[TransferId](#TransferId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[Relationship_FiscalCalendarPeriodRelationshipId](#Relationship_FiscalCalendarPeriodRelationshipId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[Relationship_FiscalCalendarYearRelationshipId](#Relationship_FiscalCalendarYearRelationshipId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[Relationship_LedgerRelationshipId](#Relationship_LedgerRelationshipId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[Relationship_LedgerEntryJournalSim_ITRelationshipId](#Relationship_LedgerEntryJournalSim_ITRelationshipId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|
|[Relationship_TransactionLogRelationshipId](#Relationship_TransactionLogRelationshipId)||<a href="GeneralJournalEntrySim_IT.md" target="_blank">TransactionHeader/GeneralJournalEntrySim_IT</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalEntrySim_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

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

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcknowledgementDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarPeriod name="FiscalCalendarPeriod">FiscalCalendarPeriod</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalCalendarYear name="FiscalCalendarYear">FiscalCalendarYear</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#JournalCategory name="JournalCategory">JournalCategory</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

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

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerEntryJournal name="LedgerEntryJournal">LedgerEntryJournal</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerEntryJournal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerPostingJournal name="LedgerPostingJournal">LedgerPostingJournal</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPostingJournalDataAreaId name="LedgerPostingJournalDataAreaId">LedgerPostingJournalDataAreaId</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingJournalDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingLayer name="PostingLayer">PostingLayer</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLayer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SimulationJournalNameDataAreaId name="SimulationJournalNameDataAreaId">SimulationJournalNameDataAreaId</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SimulationJournalNameDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SimulationJournalNameId name="SimulationJournalNameId">SimulationJournalNameId</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SimulationJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubledgerVoucher name="SubledgerVoucher">SubledgerVoucher</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubledgerVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubledgerVoucherDataAreaId name="SubledgerVoucherDataAreaId">SubledgerVoucherDataAreaId</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubledgerVoucherDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferId name="TransferId">TransferId</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_FiscalCalendarPeriodRelationshipId name="Relationship_FiscalCalendarPeriodRelationshipId">Relationship_FiscalCalendarPeriodRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

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

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

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

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

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

### <a href=#Relationship_LedgerEntryJournalSim_ITRelationshipId name="Relationship_LedgerEntryJournalSim_ITRelationshipId">Relationship_LedgerEntryJournalSim_ITRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerEntryJournalSim_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/LedgerEntryJournalSim_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Transaction/LedgerEntryJournalSim_IT.cdm.json/LedgerEntryJournalSim_IT</a></td><td><a href="../Transaction/LedgerEntryJournalSim_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransactionLogRelationshipId name="Relationship_TransactionLogRelationshipId">Relationship_TransactionLogRelationshipId</a>

First included in: TransactionHeader/GeneralJournalEntrySim_IT (this entity)  

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
