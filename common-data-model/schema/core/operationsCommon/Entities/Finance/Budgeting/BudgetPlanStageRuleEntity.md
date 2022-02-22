---
title: BudgetPlanStageRuleEntity in Budgeting - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Budget plan stage rule in Budgeting(BudgetPlanStageRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetPlanStageRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget plan stage rule</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BudgetPlanningProcess](#BudgetPlanningProcess)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[BudgetPlanningWorkflowStage](#BudgetPlanningWorkflowStage)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[CanAddBudgetPlanLines](#CanAddBudgetPlanLines)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[CanAddChildBudgetPlans](#CanAddChildBudgetPlans)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[CanModifyBudgetPlanLines](#CanModifyBudgetPlanLines)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[LayoutRecId](#LayoutRecId)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[Process](#Process)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[BudgetPlanningStage](#BudgetPlanningStage)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[BudgetPlanningWorkflow](#BudgetPlanningWorkflow)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[Stage](#Stage)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[Workflow](#Workflow)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[Layout](#Layout)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|
|[BackingTable_BudgetPlanningStageRuleRelationshipId](#BackingTable_BudgetPlanningStageRuleRelationshipId)||<a href="BudgetPlanStageRuleEntity.md" target="_blank">Budgeting/BudgetPlanStageRuleEntity</a>|

### <a href=#BudgetPlanningProcess name="BudgetPlanningProcess">BudgetPlanningProcess</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningWorkflowStage name="BudgetPlanningWorkflowStage">BudgetPlanningWorkflowStage</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

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

### <a href=#CanAddBudgetPlanLines name="CanAddBudgetPlanLines">CanAddBudgetPlanLines</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanAddBudgetPlanLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanAddChildBudgetPlans name="CanAddChildBudgetPlans">CanAddChildBudgetPlans</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanAddChildBudgetPlans attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanModifyBudgetPlanLines name="CanModifyBudgetPlanLines">CanModifyBudgetPlanLines</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanModifyBudgetPlanLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutRecId name="LayoutRecId">LayoutRecId</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Process name="Process">Process</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Process attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningStage name="BudgetPlanningStage">BudgetPlanningStage</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningStage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningWorkflow name="BudgetPlanningWorkflow">BudgetPlanningWorkflow</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningWorkflow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Stage name="Stage">Stage</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Stage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Workflow name="Workflow">Workflow</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Workflow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Layout name="Layout">Layout</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Layout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetPlanningStageRuleRelationshipId name="BackingTable_BudgetPlanningStageRuleRelationshipId">BackingTable_BudgetPlanningStageRuleRelationshipId</a>

First included in: Budgeting/BudgetPlanStageRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetPlanningStageRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanningStageRule.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanningStageRule.cdm.json/BudgetPlanningStageRule</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanningStageRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
