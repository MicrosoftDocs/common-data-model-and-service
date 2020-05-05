---
title: BudgetPlanAlternateLayoutEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Budget plan alternate layouts

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetPlanAlternateLayoutEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget plan alternate layouts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BudgetPlanLayoutId](#BudgetPlanLayoutId)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BudgetPlanningStageRule](#BudgetPlanningStageRule)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BudgetPlanLayout](#BudgetPlanLayout)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BudgetPlanningProcessName](#BudgetPlanningProcessName)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BudgetPlanningWorkflowStage](#BudgetPlanningWorkflowStage)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BudgetPlanningProcess](#BudgetPlanningProcess)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BudgetPlanningStageId](#BudgetPlanningStageId)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BudgetPlanningWorkflowId](#BudgetPlanningWorkflowId)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BudgetPlanningStage](#BudgetPlanningStage)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BudgetPlanningWorkflow](#BudgetPlanningWorkflow)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|
|[BackingTable_BudgetPlanAlternateLayoutRelationshipId](#BackingTable_BudgetPlanAlternateLayoutRelationshipId)||<a href="BudgetPlanAlternateLayoutEntity.md" target="_blank">Budgeting/BudgetPlanAlternateLayoutEntity</a>|

### <a href=#BudgetPlanLayoutId name="BudgetPlanLayoutId">BudgetPlanLayoutId</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningStageRule name="BudgetPlanningStageRule">BudgetPlanningStageRule</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningStageRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanLayout name="BudgetPlanLayout">BudgetPlanLayout</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningProcessName name="BudgetPlanningProcessName">BudgetPlanningProcessName</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningProcessName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningWorkflowStage name="BudgetPlanningWorkflowStage">BudgetPlanningWorkflowStage</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningWorkflowStage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningProcess name="BudgetPlanningProcess">BudgetPlanningProcess</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningStageId name="BudgetPlanningStageId">BudgetPlanningStageId</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningStageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningWorkflowId name="BudgetPlanningWorkflowId">BudgetPlanningWorkflowId</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningWorkflowId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningStage name="BudgetPlanningStage">BudgetPlanningStage</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningStage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningWorkflow name="BudgetPlanningWorkflow">BudgetPlanningWorkflow</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningWorkflow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetPlanAlternateLayoutRelationshipId name="BackingTable_BudgetPlanAlternateLayoutRelationshipId">BackingTable_BudgetPlanAlternateLayoutRelationshipId</a>

First included in: Budgeting/BudgetPlanAlternateLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetPlanAlternateLayoutRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanAlternateLayout.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanAlternateLayout.cdm.json/BudgetPlanAlternateLayout</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanAlternateLayout.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
