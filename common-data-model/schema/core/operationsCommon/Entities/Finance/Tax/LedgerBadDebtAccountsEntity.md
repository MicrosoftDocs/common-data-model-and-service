---
title: LedgerBadDebtAccountsEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Tax reporting accounts in Tax(LedgerBadDebtAccountsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/LedgerBadDebtAccountsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax reporting accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BadDebtMainAccountDisplayValue](#BadDebtMainAccountDisplayValue)||<a href="LedgerBadDebtAccountsEntity.md" target="_blank">Tax/LedgerBadDebtAccountsEntity</a>|
|[CollectedBadDebtMainAccountDisplayValue](#CollectedBadDebtMainAccountDisplayValue)||<a href="LedgerBadDebtAccountsEntity.md" target="_blank">Tax/LedgerBadDebtAccountsEntity</a>|
|[BadDebtMainAccount](#BadDebtMainAccount)||<a href="LedgerBadDebtAccountsEntity.md" target="_blank">Tax/LedgerBadDebtAccountsEntity</a>|
|[CollectedBadDebtMainAccount](#CollectedBadDebtMainAccount)||<a href="LedgerBadDebtAccountsEntity.md" target="_blank">Tax/LedgerBadDebtAccountsEntity</a>|
|[Company](#Company)||<a href="LedgerBadDebtAccountsEntity.md" target="_blank">Tax/LedgerBadDebtAccountsEntity</a>|
|[BackingTable_LedgerBadDebtAccounts_JPRelationshipId](#BackingTable_LedgerBadDebtAccounts_JPRelationshipId)||<a href="LedgerBadDebtAccountsEntity.md" target="_blank">Tax/LedgerBadDebtAccountsEntity</a>|

### <a href=#BadDebtMainAccountDisplayValue name="BadDebtMainAccountDisplayValue">BadDebtMainAccountDisplayValue</a>

First included in: Tax/LedgerBadDebtAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bad debt</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BadDebtMainAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bad debt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectedBadDebtMainAccountDisplayValue name="CollectedBadDebtMainAccountDisplayValue">CollectedBadDebtMainAccountDisplayValue</a>

First included in: Tax/LedgerBadDebtAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Collected bad debt</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectedBadDebtMainAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Collected bad debt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BadDebtMainAccount name="BadDebtMainAccount">BadDebtMainAccount</a>

First included in: Tax/LedgerBadDebtAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BadDebtMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectedBadDebtMainAccount name="CollectedBadDebtMainAccount">CollectedBadDebtMainAccount</a>

First included in: Tax/LedgerBadDebtAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectedBadDebtMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Tax/LedgerBadDebtAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LedgerBadDebtAccounts_JPRelationshipId name="BackingTable_LedgerBadDebtAccounts_JPRelationshipId">BackingTable_LedgerBadDebtAccounts_JPRelationshipId</a>

First included in: Tax/LedgerBadDebtAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerBadDebtAccounts_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Reference/LedgerBadDebtAccounts_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Reference/LedgerBadDebtAccounts_JP.cdm.json/LedgerBadDebtAccounts_JP</a></td><td><a href="../../../Tables/Finance/Ledger/Reference/LedgerBadDebtAccounts_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
