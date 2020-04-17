---
title: BankCodaAccountStatementEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# BankCodaAccountStatementEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Finance/CashAndBankManagement/BankCodaAccountStatementEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[BankAccount](#BankAccount)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[BankStatementDate](#BankStatementDate)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[BankStatement](#BankStatement)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[OpeningBalance](#OpeningBalance)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[BankTransactionType](#BankTransactionType)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[Currency](#Currency)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[TransferDetails](#TransferDetails)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[EndingBalance](#EndingBalance)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[ClosedDate](#ClosedDate)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[Reconciled](#Reconciled)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[TotalAmount](#TotalAmount)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[IsMovementLinesUpdateDelayed](#IsMovementLinesUpdateDelayed)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[BackingTable_BankCodaAccountStatementRelationshipId](#BackingTable_BankCodaAccountStatementRelationshipId)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankCodaAccountStatementEntity.md" target="_blank">CashAndBankManagement/BankCodaAccountStatementEntity</a>|

### <a href=#BankAccount name="BankAccount">BankAccount</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

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

### <a href=#BankStatementDate name="BankStatementDate">BankStatementDate</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStatement name="BankStatement">BankStatement</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpeningBalance name="OpeningBalance">OpeningBalance</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpeningBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankTransactionType name="BankTransactionType">BankTransactionType</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

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

### <a href=#TransferDetails name="TransferDetails">TransferDetails</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndingBalance name="EndingBalance">EndingBalance</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndingBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedDate name="ClosedDate">ClosedDate</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reconciled name="Reconciled">Reconciled</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reconciled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalAmount name="TotalAmount">TotalAmount</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMovementLinesUpdateDelayed name="IsMovementLinesUpdateDelayed">IsMovementLinesUpdateDelayed</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMovementLinesUpdateDelayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BankCodaAccountStatementRelationshipId name="BackingTable_BankCodaAccountStatementRelationshipId">BackingTable_BankCodaAccountStatementRelationshipId</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankCodaAccountStatementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/TransactionHeader/BankCodaAccountStatement.md" target="_blank">/core/erp/Tables/Finance/Bank/TransactionHeader/BankCodaAccountStatement.cdm.json/BankCodaAccountStatement</a></td><td><a href="../../../Tables/Finance/Bank/TransactionHeader/BankCodaAccountStatement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankCodaAccountStatementEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
