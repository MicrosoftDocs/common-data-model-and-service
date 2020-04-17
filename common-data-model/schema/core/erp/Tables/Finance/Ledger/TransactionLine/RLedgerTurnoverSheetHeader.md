---
title: RLedgerTurnoverSheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RLedgerTurnoverSheetHeader

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Ledger/TransactionLine/RLedgerTurnoverSheetHeader.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RLedgerTurnoverSheetHeader/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[BalanceCreditEnd](#BalanceCreditEnd)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[BalanceCreditStart](#BalanceCreditStart)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[BalanceDebitEnd](#BalanceDebitEnd)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[BalanceDebitStart](#BalanceDebitStart)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[Description](#Description)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[DocumentDate](#DocumentDate)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[DocumentNum](#DocumentNum)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[GroupParam](#GroupParam)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[Name](#Name)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[RangeStr](#RangeStr)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[RefRecId](#RefRecId)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[SettlementCredit](#SettlementCredit)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[SettlementDebit](#SettlementDebit)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[Title](#Title)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[TransDate](#TransDate)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[TurnoverCredit](#TurnoverCredit)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[TurnoverDebit](#TurnoverDebit)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[Txt](#Txt)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[DataAreaId](#DataAreaId)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[Relationship_RLedgerTurnoverSheetRelationshipId](#Relationship_RLedgerTurnoverSheetRelationshipId)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RLedgerTurnoverSheetHeader.md" target="_blank">TransactionLine/RLedgerTurnoverSheetHeader</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RLedgerTurnoverSheetHeader/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BalanceCreditEnd name="BalanceCreditEnd">BalanceCreditEnd</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceCreditEnd attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceCreditStart name="BalanceCreditStart">BalanceCreditStart</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceCreditStart attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceDebitEnd name="BalanceDebitEnd">BalanceDebitEnd</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceDebitEnd attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceDebitStart name="BalanceDebitStart">BalanceDebitStart</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceDebitStart attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

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

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

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

### <a href=#DocumentNum name="DocumentNum">DocumentNum</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupParam name="GroupParam">GroupParam</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupParam attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RangeStr name="RangeStr">RangeStr</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RangeStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SettlementCredit name="SettlementCredit">SettlementCredit</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementDebit name="SettlementDebit">SettlementDebit</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementDebit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Title name="Title">Title</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Title attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TurnoverCredit name="TurnoverCredit">TurnoverCredit</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TurnoverCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TurnoverDebit name="TurnoverDebit">TurnoverDebit</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TurnoverDebit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Txt name="Txt">Txt</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

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

### <a href=#Relationship_RLedgerTurnoverSheetRelationshipId name="Relationship_RLedgerTurnoverSheetRelationshipId">Relationship_RLedgerTurnoverSheetRelationshipId</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RLedgerTurnoverSheetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/RLedgerTurnoverSheet.md" target="_blank">/core/erp/Tables/Finance/Ledger/TransactionHeader/RLedgerTurnoverSheet.cdm.json/RLedgerTurnoverSheet</a></td><td><a href="../TransactionHeader/RLedgerTurnoverSheet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionLine/RLedgerTurnoverSheetHeader (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
