---
title: BudgetPlanWorkflowStagesEntity in Budgeting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Budget plan workflow stage in Budgeting(BudgetPlanWorkflowStagesEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetPlanWorkflowStagesEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget plan workflow stage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BudgetPlanningStage](#BudgetPlanningStage)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[BudgetPlanningWorkflow](#BudgetPlanningWorkflow)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[PriorBudgetPlanningWorkflowStage](#PriorBudgetPlanningWorkflowStage)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[WorkflowName](#WorkflowName)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[WorkflowId](#WorkflowId)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[StageName](#StageName)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[PriorBudgetPlanningStageName](#PriorBudgetPlanningStageName)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[PriorBudgetPlanningWorkflowName](#PriorBudgetPlanningWorkflowName)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[IsParentBudgetPlanRequired](#IsParentBudgetPlanRequired)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[RestrictDeleteBudgetPlan](#RestrictDeleteBudgetPlan)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[RestrictResetBudgetPlan](#RestrictResetBudgetPlan)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[PriorBudgetPlanningStageRecId](#PriorBudgetPlanningStageRecId)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[PriorBudgetPlanningWorkflowRecId](#PriorBudgetPlanningWorkflowRecId)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|
|[BackingTable_BudgetPlanningWorkflowStageRelationshipId](#BackingTable_BudgetPlanningWorkflowStageRelationshipId)||<a href="BudgetPlanWorkflowStagesEntity.md" target="_blank">Budgeting/BudgetPlanWorkflowStagesEntity</a>|

### <a href=#BudgetPlanningStage name="BudgetPlanningStage">BudgetPlanningStage</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

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

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

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

### <a href=#PriorBudgetPlanningWorkflowStage name="PriorBudgetPlanningWorkflowStage">PriorBudgetPlanningWorkflowStage</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriorBudgetPlanningWorkflowStage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowName name="WorkflowName">WorkflowName</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowId name="WorkflowId">WorkflowId</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StageName name="StageName">StageName</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StageName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriorBudgetPlanningStageName name="PriorBudgetPlanningStageName">PriorBudgetPlanningStageName</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Previous budget planning stage</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriorBudgetPlanningStageName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Previous budget planning stage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriorBudgetPlanningWorkflowName name="PriorBudgetPlanningWorkflowName">PriorBudgetPlanningWorkflowName</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriorBudgetPlanningWorkflowName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsParentBudgetPlanRequired name="IsParentBudgetPlanRequired">IsParentBudgetPlanRequired</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsParentBudgetPlanRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestrictDeleteBudgetPlan name="RestrictDeleteBudgetPlan">RestrictDeleteBudgetPlan</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestrictDeleteBudgetPlan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestrictResetBudgetPlan name="RestrictResetBudgetPlan">RestrictResetBudgetPlan</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestrictResetBudgetPlan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriorBudgetPlanningStageRecId name="PriorBudgetPlanningStageRecId">PriorBudgetPlanningStageRecId</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriorBudgetPlanningStageRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriorBudgetPlanningWorkflowRecId name="PriorBudgetPlanningWorkflowRecId">PriorBudgetPlanningWorkflowRecId</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriorBudgetPlanningWorkflowRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetPlanningWorkflowStageRelationshipId name="BackingTable_BudgetPlanningWorkflowStageRelationshipId">BackingTable_BudgetPlanningWorkflowStageRelationshipId</a>

First included in: Budgeting/BudgetPlanWorkflowStagesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetPlanningWorkflowStageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanningWorkflowStage.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanningWorkflowStage.cdm.json/BudgetPlanningWorkflowStage</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanningWorkflowStage.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
