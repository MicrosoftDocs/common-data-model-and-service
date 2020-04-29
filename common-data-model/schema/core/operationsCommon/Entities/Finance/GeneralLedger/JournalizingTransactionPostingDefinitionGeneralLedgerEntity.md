---
title: JournalizingTransactionPostingDefinitionGeneralLedgerEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Transaction posting definition general ledger

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction posting definition general ledger</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FundClass](#FundClass)||<a href="JournalizingTransactionPostingDefinitionGeneralLedgerEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity</a>|
|[PostingDefinition](#PostingDefinition)||<a href="JournalizingTransactionPostingDefinitionGeneralLedgerEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity</a>|
|[LedgerTransactionType](#LedgerTransactionType)||<a href="JournalizingTransactionPostingDefinitionGeneralLedgerEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity</a>|
|[PostingDefinitionId](#PostingDefinitionId)||<a href="JournalizingTransactionPostingDefinitionGeneralLedgerEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity</a>|
|[BackingTable_JournalizingDefinitionGeneralLedgerTransRelationshipId](#BackingTable_JournalizingDefinitionGeneralLedgerTransRelationshipId)||<a href="JournalizingTransactionPostingDefinitionGeneralLedgerEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JournalizingTransactionPostingDefinitionGeneralLedgerEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity</a>|

### <a href=#FundClass name="FundClass">FundClass</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundClass attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDefinition name="PostingDefinition">PostingDefinition</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting definition</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting definition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerTransactionType name="LedgerTransactionType">LedgerTransactionType</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDefinitionId name="PostingDefinitionId">PostingDefinitionId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting definition</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinitionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting definition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JournalizingDefinitionGeneralLedgerTransRelationshipId name="BackingTable_JournalizingDefinitionGeneralLedgerTransRelationshipId">BackingTable_JournalizingDefinitionGeneralLedgerTransRelationshipId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JournalizingDefinitionGeneralLedgerTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountingFoundation/Group/JournalizingDefinitionGeneralLedgerTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/JournalizingDefinitionGeneralLedgerTrans.cdm.json/JournalizingDefinitionGeneralLedgerTrans</a></td><td><a href="../../../Tables/Finance/AccountingFoundation/Group/JournalizingDefinitionGeneralLedgerTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionGeneralLedgerEntity (this entity)  

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
