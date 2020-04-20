---
title: SubledgerVoucherGeneralJournalEntrySim_IT - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# SubledgerVoucherGeneralJournalEntrySim_IT

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Transaction/SubledgerVoucherGeneralJournalEntrySim_IT.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SubledgerVoucherGeneralJournalEntrySim_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SubledgerVoucherGeneralJournalEntrySim_IT.md" target="_blank">Transaction/SubledgerVoucherGeneralJournalEntrySim_IT</a>|
|[AccountingDate](#AccountingDate)||<a href="SubledgerVoucherGeneralJournalEntrySim_IT.md" target="_blank">Transaction/SubledgerVoucherGeneralJournalEntrySim_IT</a>|
|[GeneralJournalEntry](#GeneralJournalEntry)||<a href="SubledgerVoucherGeneralJournalEntrySim_IT.md" target="_blank">Transaction/SubledgerVoucherGeneralJournalEntrySim_IT</a>|
|[Voucher](#Voucher)||<a href="SubledgerVoucherGeneralJournalEntrySim_IT.md" target="_blank">Transaction/SubledgerVoucherGeneralJournalEntrySim_IT</a>|
|[VoucherDataAreaId](#VoucherDataAreaId)||<a href="SubledgerVoucherGeneralJournalEntrySim_IT.md" target="_blank">Transaction/SubledgerVoucherGeneralJournalEntrySim_IT</a>|
|[Relationship_GeneralJournalEntrySim_ITRelationshipId](#Relationship_GeneralJournalEntrySim_ITRelationshipId)||<a href="SubledgerVoucherGeneralJournalEntrySim_IT.md" target="_blank">Transaction/SubledgerVoucherGeneralJournalEntrySim_IT</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/SubledgerVoucherGeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SubledgerVoucherGeneralJournalEntrySim_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: Transaction/SubledgerVoucherGeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#GeneralJournalEntry name="GeneralJournalEntry">GeneralJournalEntry</a>

First included in: Transaction/SubledgerVoucherGeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralJournalEntry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/SubledgerVoucherGeneralJournalEntrySim_IT (this entity)  

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

### <a href=#VoucherDataAreaId name="VoucherDataAreaId">VoucherDataAreaId</a>

First included in: Transaction/SubledgerVoucherGeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GeneralJournalEntrySim_ITRelationshipId name="Relationship_GeneralJournalEntrySim_ITRelationshipId">Relationship_GeneralJournalEntrySim_ITRelationshipId</a>

First included in: Transaction/SubledgerVoucherGeneralJournalEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneralJournalEntrySim_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/GeneralJournalEntrySim_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/TransactionHeader/GeneralJournalEntrySim_IT.cdm.json/GeneralJournalEntrySim_IT</a></td><td><a href="../TransactionHeader/GeneralJournalEntrySim_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
