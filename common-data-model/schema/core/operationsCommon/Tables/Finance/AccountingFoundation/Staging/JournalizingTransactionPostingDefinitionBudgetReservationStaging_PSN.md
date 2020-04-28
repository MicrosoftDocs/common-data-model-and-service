---
title: JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Journalizing definition general budget reservation

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountingFoundation/Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journalizing definition general budget reservation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[BudgetReservationType_Name](#BudgetReservationType_Name)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[DefinitionGroup](#DefinitionGroup)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[ExecutionId](#ExecutionId)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[IsSelected](#IsSelected)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[TransferStatus](#TransferStatus)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[BudgetReservationJournalizingType](#BudgetReservationJournalizingType)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[BudgetReservationTypeCode](#BudgetReservationTypeCode)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[PostingDefinition](#PostingDefinition)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[BudgetReservationTypeName](#BudgetReservationTypeName)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|
|[Relationship_JournalizingDefinitionRelationshipId](#Relationship_JournalizingDefinitionRelationshipId)||<a href="JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN.md" target="_blank">Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetReservationType_Name name="BudgetReservationType_Name">BudgetReservationType_Name</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationType_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefinitionGroup name="DefinitionGroup">DefinitionGroup</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefinitionGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionId name="ExecutionId">ExecutionId</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSelected name="IsSelected">IsSelected</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSelected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransferStatus name="TransferStatus">TransferStatus</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetReservationJournalizingType name="BudgetReservationJournalizingType">BudgetReservationJournalizingType</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationJournalizingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetReservationTypeCode name="BudgetReservationTypeCode">BudgetReservationTypeCode</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting definition type</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationTypeCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting definition type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PostingDefinition name="PostingDefinition">PostingDefinition</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationTypeName name="BudgetReservationTypeName">BudgetReservationTypeName</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JournalizingDefinitionRelationshipId name="Relationship_JournalizingDefinitionRelationshipId">Relationship_JournalizingDefinitionRelationshipId</a>

First included in: Staging/JournalizingTransactionPostingDefinitionBudgetReservationStaging_PSN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/JournalizingDefinition.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Main/JournalizingDefinition.cdm.json/JournalizingDefinition</a></td><td><a href="../Main/JournalizingDefinition.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
