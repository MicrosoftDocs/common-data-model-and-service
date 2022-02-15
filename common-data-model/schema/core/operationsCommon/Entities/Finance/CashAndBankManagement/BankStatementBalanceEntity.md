---
title: BankStatementBalanceEntity in CashAndBankManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Bank statement cash balance in CashAndBankManagement(BankStatementBalanceEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankStatementBalanceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank statement cash balance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BalanceLineNum](#BalanceLineNum)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[AvailibilityLineNum](#AvailibilityLineNum)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[BalanceType](#BalanceType)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[BalanceIndicator](#BalanceIndicator)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[BalanceAmount](#BalanceAmount)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[BalanceItemCount](#BalanceItemCount)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[BalanceTypeCode](#BalanceTypeCode)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[BalanceFundsType](#BalanceFundsType)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[BankStmtISOAccountStatement](#BankStmtISOAccountStatement)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[BankStmtISOCashBalance](#BankStmtISOCashBalance)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[AvailibilityAmount](#AvailibilityAmount)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[AvailibilityActualDate](#AvailibilityActualDate)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[AvailibilityNumberOfDays](#AvailibilityNumberOfDays)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[StatementLineNum](#StatementLineNum)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[DocumentLineNum](#DocumentLineNum)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[Relationship_BankStatementEntityRelationshipId](#Relationship_BankStatementEntityRelationshipId)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[BackingTable_BankStmtISOCashBalanceRelationshipId](#BackingTable_BankStmtISOCashBalanceRelationshipId)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankStatementBalanceEntity.md" target="_blank">CashAndBankManagement/BankStatementBalanceEntity</a>|

### <a href=#BalanceLineNum name="BalanceLineNum">BalanceLineNum</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailibilityLineNum name="AvailibilityLineNum">AvailibilityLineNum</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailibilityLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceType name="BalanceType">BalanceType</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceIndicator name="BalanceIndicator">BalanceIndicator</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceAmount name="BalanceAmount">BalanceAmount</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceItemCount name="BalanceItemCount">BalanceItemCount</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceItemCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceTypeCode name="BalanceTypeCode">BalanceTypeCode</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceFundsType name="BalanceFundsType">BalanceFundsType</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceFundsType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankStmtISOAccountStatement name="BankStmtISOAccountStatement">BankStmtISOAccountStatement</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

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

### <a href=#BankStmtISOCashBalance name="BankStmtISOCashBalance">BankStmtISOCashBalance</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankStmtISOCashBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailibilityAmount name="AvailibilityAmount">AvailibilityAmount</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailibilityAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailibilityActualDate name="AvailibilityActualDate">AvailibilityActualDate</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailibilityActualDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailibilityNumberOfDays name="AvailibilityNumberOfDays">AvailibilityNumberOfDays</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailibilityNumberOfDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementLineNum name="StatementLineNum">StatementLineNum</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

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

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

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

### <a href=#Relationship_BankStatementEntityRelationshipId name="Relationship_BankStatementEntityRelationshipId">Relationship_BankStatementEntityRelationshipId</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

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

### <a href=#BackingTable_BankStmtISOCashBalanceRelationshipId name="BackingTable_BankStmtISOCashBalanceRelationshipId">BackingTable_BankStmtISOCashBalanceRelationshipId</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankStmtISOCashBalanceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Transaction/BankStmtISOCashBalance.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/BankStmtISOCashBalance.cdm.json/BankStmtISOCashBalance</a></td><td><a href="../../../Tables/Finance/Bank/Transaction/BankStmtISOCashBalance.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankStatementBalanceEntity (this entity)  

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
