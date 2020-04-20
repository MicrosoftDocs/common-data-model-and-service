---
title: JournalizingDefinitionBudgetTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# JournalizingDefinitionBudgetTrans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountingFoundation/Main/JournalizingDefinitionBudgetTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JournalizingDefinitionBudgetTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="JournalizingDefinitionBudgetTrans.md" target="_blank">Main/JournalizingDefinitionBudgetTrans</a>|
|[BudgetTransactionCode](#BudgetTransactionCode)||<a href="JournalizingDefinitionBudgetTrans.md" target="_blank">Main/JournalizingDefinitionBudgetTrans</a>|
|[BudgetTransactionType](#BudgetTransactionType)||<a href="JournalizingDefinitionBudgetTrans.md" target="_blank">Main/JournalizingDefinitionBudgetTrans</a>|
|[BudgetTransactionTypeCode](#BudgetTransactionTypeCode)||<a href="JournalizingDefinitionBudgetTrans.md" target="_blank">Main/JournalizingDefinitionBudgetTrans</a>|
|[JournalizingDefinition](#JournalizingDefinition)||<a href="JournalizingDefinitionBudgetTrans.md" target="_blank">Main/JournalizingDefinitionBudgetTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="JournalizingDefinitionBudgetTrans.md" target="_blank">Main/JournalizingDefinitionBudgetTrans</a>|
|[Relationship_BudgetTransactionCodeRelationshipId](#Relationship_BudgetTransactionCodeRelationshipId)||<a href="JournalizingDefinitionBudgetTrans.md" target="_blank">Main/JournalizingDefinitionBudgetTrans</a>|
|[Relationship_JournalizingDefinitionRelationshipId](#Relationship_JournalizingDefinitionRelationshipId)||<a href="JournalizingDefinitionBudgetTrans.md" target="_blank">Main/JournalizingDefinitionBudgetTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="JournalizingDefinitionBudgetTrans.md" target="_blank">Main/JournalizingDefinitionBudgetTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/JournalizingDefinitionBudgetTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JournalizingDefinitionBudgetTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetTransactionCode name="BudgetTransactionCode">BudgetTransactionCode</a>

First included in: Main/JournalizingDefinitionBudgetTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetTransactionCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetTransactionType name="BudgetTransactionType">BudgetTransactionType</a>

First included in: Main/JournalizingDefinitionBudgetTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetTransactionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetTransactionTypeCode name="BudgetTransactionTypeCode">BudgetTransactionTypeCode</a>

First included in: Main/JournalizingDefinitionBudgetTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetTransactionTypeCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalizingDefinition name="JournalizingDefinition">JournalizingDefinition</a>

First included in: Main/JournalizingDefinitionBudgetTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalizingDefinition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/JournalizingDefinitionBudgetTrans (this entity)  

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

### <a href=#Relationship_BudgetTransactionCodeRelationshipId name="Relationship_BudgetTransactionCodeRelationshipId">Relationship_BudgetTransactionCodeRelationshipId</a>

First included in: Main/JournalizingDefinitionBudgetTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetTransactionCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Budget/Group/BudgetTransactionCode.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetTransactionCode.cdm.json/BudgetTransactionCode</a></td><td><a href="../../Budget/Group/BudgetTransactionCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JournalizingDefinitionRelationshipId name="Relationship_JournalizingDefinitionRelationshipId">Relationship_JournalizingDefinitionRelationshipId</a>

First included in: Main/JournalizingDefinitionBudgetTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JournalizingDefinitionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="JournalizingDefinition.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Main/JournalizingDefinition.cdm.json/JournalizingDefinition</a></td><td><a href="JournalizingDefinition.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/JournalizingDefinitionBudgetTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
