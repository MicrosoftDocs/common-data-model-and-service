---
title: GeneralJournalAccountEntry_W - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# GeneralJournalAccountEntry_W

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Ledger/TransactionLine/GeneralJournalAccountEntry_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalAccountEntry_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|
|[BondBatchTrans_RU](#BondBatchTrans_RU)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|
|[ConsolidatedRefRecId_BR](#ConsolidatedRefRecId_BR)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|
|[ConsolidatedVoucher_BR](#ConsolidatedVoucher_BR)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|
|[GeneralJournalAccountEntry](#GeneralJournalAccountEntry)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|
|[GeneralJournalEntry](#GeneralJournalEntry)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|
|[IsAccountingClosing_BR](#IsAccountingClosing_BR)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|
|[Relationship_ConsolidatedGenJrnAcctEntRelationshipId](#Relationship_ConsolidatedGenJrnAcctEntRelationshipId)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|
|[Relationship_GeneralJournalAccountEntryRelationshipId](#Relationship_GeneralJournalAccountEntryRelationshipId)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|
|[Relationship_GeneralJournalEntryRelationshipId](#Relationship_GeneralJournalEntryRelationshipId)||<a href="GeneralJournalAccountEntry_W.md" target="_blank">TransactionLine/GeneralJournalAccountEntry_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalAccountEntry_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BondBatchTrans_RU name="BondBatchTrans_RU">BondBatchTrans_RU</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BondBatchTrans_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConsolidatedRefRecId_BR name="ConsolidatedRefRecId_BR">ConsolidatedRefRecId_BR</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidatedRefRecId_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConsolidatedVoucher_BR name="ConsolidatedVoucher_BR">ConsolidatedVoucher_BR</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidatedVoucher_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralJournalAccountEntry name="GeneralJournalAccountEntry">GeneralJournalAccountEntry</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralJournalAccountEntry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GeneralJournalEntry name="GeneralJournalEntry">GeneralJournalEntry</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

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

### <a href=#IsAccountingClosing_BR name="IsAccountingClosing_BR">IsAccountingClosing_BR</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAccountingClosing_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_ConsolidatedGenJrnAcctEntRelationshipId name="Relationship_ConsolidatedGenJrnAcctEntRelationshipId">Relationship_ConsolidatedGenJrnAcctEntRelationshipId</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConsolidatedGenJrnAcctEntRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="GeneralJournalAccountEntry.md" target="_blank">/core/erp/Tables/Finance/Ledger/TransactionLine/GeneralJournalAccountEntry.cdm.json/GeneralJournalAccountEntry</a></td><td><a href="GeneralJournalAccountEntry.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GeneralJournalAccountEntryRelationshipId name="Relationship_GeneralJournalAccountEntryRelationshipId">Relationship_GeneralJournalAccountEntryRelationshipId</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneralJournalAccountEntryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="GeneralJournalAccountEntry.md" target="_blank">/core/erp/Tables/Finance/Ledger/TransactionLine/GeneralJournalAccountEntry.cdm.json/GeneralJournalAccountEntry</a></td><td><a href="GeneralJournalAccountEntry.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GeneralJournalEntryRelationshipId name="Relationship_GeneralJournalEntryRelationshipId">Relationship_GeneralJournalEntryRelationshipId</a>

First included in: TransactionLine/GeneralJournalAccountEntry_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneralJournalEntryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/GeneralJournalEntry.md" target="_blank">/core/erp/Tables/Finance/Ledger/TransactionHeader/GeneralJournalEntry.cdm.json/GeneralJournalEntry</a></td><td><a href="../TransactionHeader/GeneralJournalEntry.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
