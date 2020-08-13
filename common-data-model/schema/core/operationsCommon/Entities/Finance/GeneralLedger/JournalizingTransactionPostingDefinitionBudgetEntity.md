---
title: JournalizingTransactionPostingDefinitionBudgetEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Transaction posting definition budget in GeneralLedger(JournalizingTransactionPostingDefinitionBudgetEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction posting definition budget</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BudgetTransactionCode](#BudgetTransactionCode)||<a href="JournalizingTransactionPostingDefinitionBudgetEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity</a>|
|[BudgetType](#BudgetType)||<a href="JournalizingTransactionPostingDefinitionBudgetEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity</a>|
|[BudgetCodeTableAll](#BudgetCodeTableAll)||<a href="JournalizingTransactionPostingDefinitionBudgetEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity</a>|
|[PostingDefinition](#PostingDefinition)||<a href="JournalizingTransactionPostingDefinitionBudgetEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity</a>|
|[BudgetCodeRelationName](#BudgetCodeRelationName)||<a href="JournalizingTransactionPostingDefinitionBudgetEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity</a>|
|[PostingDefinitionId](#PostingDefinitionId)||<a href="JournalizingTransactionPostingDefinitionBudgetEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity</a>|
|[BackingTable_JournalizingDefinitionBudgetTransRelationshipId](#BackingTable_JournalizingDefinitionBudgetTransRelationshipId)||<a href="JournalizingTransactionPostingDefinitionBudgetEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JournalizingTransactionPostingDefinitionBudgetEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity</a>|

### <a href=#BudgetTransactionCode name="BudgetTransactionCode">BudgetTransactionCode</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetTransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetType name="BudgetType">BudgetType</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Select</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCodeTableAll name="BudgetCodeTableAll">BudgetCodeTableAll</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCodeTableAll attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDefinition name="PostingDefinition">PostingDefinition</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCodeRelationName name="BudgetCodeRelationName">BudgetCodeRelationName</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget code relation</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCodeRelationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget code relation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDefinitionId name="PostingDefinitionId">PostingDefinitionId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinitionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JournalizingDefinitionBudgetTransRelationshipId name="BackingTable_JournalizingDefinitionBudgetTransRelationshipId">BackingTable_JournalizingDefinitionBudgetTransRelationshipId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JournalizingDefinitionBudgetTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountingFoundation/Main/JournalizingDefinitionBudgetTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Main/JournalizingDefinitionBudgetTrans.cdm.json/JournalizingDefinitionBudgetTrans</a></td><td><a href="../../../Tables/Finance/AccountingFoundation/Main/JournalizingDefinitionBudgetTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionBudgetEntity (this entity)  

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
