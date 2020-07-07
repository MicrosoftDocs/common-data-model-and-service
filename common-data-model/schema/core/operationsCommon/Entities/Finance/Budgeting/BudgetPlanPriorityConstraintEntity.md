---
title: BudgetPlanPriorityConstraintEntity in Budgeting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Budget plan priority constraint in Budgeting

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetPlanPriorityConstraintEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget plan priority constraint</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BudgetPlanningProcess](#BudgetPlanningProcess)||<a href="BudgetPlanPriorityConstraintEntity.md" target="_blank">Budgeting/BudgetPlanPriorityConstraintEntity</a>|
|[BudgetPlanPriority](#BudgetPlanPriority)||<a href="BudgetPlanPriorityConstraintEntity.md" target="_blank">Budgeting/BudgetPlanPriorityConstraintEntity</a>|
|[Process](#Process)||<a href="BudgetPlanPriorityConstraintEntity.md" target="_blank">Budgeting/BudgetPlanPriorityConstraintEntity</a>|
|[Priority](#Priority)||<a href="BudgetPlanPriorityConstraintEntity.md" target="_blank">Budgeting/BudgetPlanPriorityConstraintEntity</a>|
|[BackingTable_BudgetPlanPriorityConstraintRelationshipId](#BackingTable_BudgetPlanPriorityConstraintRelationshipId)||<a href="BudgetPlanPriorityConstraintEntity.md" target="_blank">Budgeting/BudgetPlanPriorityConstraintEntity</a>|

### <a href=#BudgetPlanningProcess name="BudgetPlanningProcess">BudgetPlanningProcess</a>

First included in: Budgeting/BudgetPlanPriorityConstraintEntity (this entity)  

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

### <a href=#BudgetPlanPriority name="BudgetPlanPriority">BudgetPlanPriority</a>

First included in: Budgeting/BudgetPlanPriorityConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Process name="Process">Process</a>

First included in: Budgeting/BudgetPlanPriorityConstraintEntity (this entity)  

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

### <a href=#Priority name="Priority">Priority</a>

First included in: Budgeting/BudgetPlanPriorityConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Priority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetPlanPriorityConstraintRelationshipId name="BackingTable_BudgetPlanPriorityConstraintRelationshipId">BackingTable_BudgetPlanPriorityConstraintRelationshipId</a>

First included in: Budgeting/BudgetPlanPriorityConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetPlanPriorityConstraintRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanPriorityConstraint.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanPriorityConstraint.cdm.json/BudgetPlanPriorityConstraint</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanPriorityConstraint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
