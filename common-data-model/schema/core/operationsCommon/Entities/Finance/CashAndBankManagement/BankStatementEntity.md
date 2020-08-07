---
title: BankStatementEntity in CashAndBankManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Bank statement account statement in CashAndBankManagement(BankStatementEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankStatementEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank statement account statement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountCurrency](#AccountCurrency)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[AccountIdOtherId](#AccountIdOtherId)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[AsOfDateModifier](#AsOfDateModifier)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[BankStatementType](#BankStatementType)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[FromDateTime](#FromDateTime)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[GroupControlTotal](#GroupControlTotal)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[GroupStatus](#GroupStatus)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[IBAN](#IBAN)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[Identification](#Identification)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[SwiftNo](#SwiftNo)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[ToDateTime](#ToDateTime)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[TotalAccountsInGroup](#TotalAccountsInGroup)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[TotalRecordsInGroup](#TotalRecordsInGroup)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[TotalEntriesNumberOfEntries](#TotalEntriesNumberOfEntries)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[OriginatorName](#OriginatorName)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[OriginatorId](#OriginatorId)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[UltimateReceiverName](#UltimateReceiverName)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[UltimateReceiverId](#UltimateReceiverId)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[OriginatorParty](#OriginatorParty)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[UltimateReceiverParty](#UltimateReceiverParty)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[StatementLineNum](#StatementLineNum)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[DocumentLineNum](#DocumentLineNum)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[BankStmtISODocument](#BankStmtISODocument)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[BankStatementRecId](#BankStatementRecId)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[BankAccountTable](#BankAccountTable)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[Relationship_BankStatementDocumentEntityRelationshipId](#Relationship_BankStatementDocumentEntityRelationshipId)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[BackingTable_BankStmtISOAccountStatementRelationshipId](#BackingTable_BankStmtISOAccountStatementRelationshipId)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankStatementEntity.md" target="_blank">CashAndBankManagement/BankStatementEntity</a>|

### <a href=#AccountCurrency name="AccountCurrency">AccountCurrency</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountIdOtherId name="AccountIdOtherId">AccountIdOtherId</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountIdOtherId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AsOfDateModifier name="AsOfDateModifier">AsOfDateModifier</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AsOfDateModifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementType name="BankStatementType">BankStatementType</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromDateTime name="FromDateTime">FromDateTime</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupControlTotal name="GroupControlTotal">GroupControlTotal</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupControlTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupStatus name="GroupStatus">GroupStatus</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IBAN name="IBAN">IBAN</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IBAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Identification name="Identification">Identification</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Identification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SwiftNo name="SwiftNo">SwiftNo</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SwiftNo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToDateTime name="ToDateTime">ToDateTime</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalAccountsInGroup name="TotalAccountsInGroup">TotalAccountsInGroup</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAccountsInGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalRecordsInGroup name="TotalRecordsInGroup">TotalRecordsInGroup</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRecordsInGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalEntriesNumberOfEntries name="TotalEntriesNumberOfEntries">TotalEntriesNumberOfEntries</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalEntriesNumberOfEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatorName name="OriginatorName">OriginatorName</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatorId name="OriginatorId">OriginatorId</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UltimateReceiverName name="UltimateReceiverName">UltimateReceiverName</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UltimateReceiverName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UltimateReceiverId name="UltimateReceiverId">UltimateReceiverId</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UltimateReceiverId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatorParty name="OriginatorParty">OriginatorParty</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatorParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UltimateReceiverParty name="UltimateReceiverParty">UltimateReceiverParty</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UltimateReceiverParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementLineNum name="StatementLineNum">StatementLineNum</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

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

### <a href=#DocumentLineNum name="DocumentLineNum">DocumentLineNum</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

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

### <a href=#BankStmtISODocument name="BankStmtISODocument">BankStmtISODocument</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStmtISODocument attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatementRecId name="BankStatementRecId">BankStatementRecId</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountTable name="BankAccountTable">BankAccountTable</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

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

### <a href=#Relationship_BankStatementDocumentEntityRelationshipId name="Relationship_BankStatementDocumentEntityRelationshipId">Relationship_BankStatementDocumentEntityRelationshipId</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankStatementDocumentEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BankStmtISOAccountStatementRelationshipId name="BackingTable_BankStmtISOAccountStatementRelationshipId">BackingTable_BankStmtISOAccountStatementRelationshipId</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankStmtISOAccountStatementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Transaction/BankStmtISOAccountStatement.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankStmtISOAccountStatement.cdm.json/BankStmtISOAccountStatement</a></td><td><a href="../../../Tables/Finance/Bank/Transaction/BankStmtISOAccountStatement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankStatementEntity (this entity)  

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
