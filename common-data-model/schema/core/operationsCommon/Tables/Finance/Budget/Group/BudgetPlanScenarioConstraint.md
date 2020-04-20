---
title: BudgetPlanScenarioConstraint - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# BudgetPlanScenarioConstraint

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanScenarioConstraint.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanScenarioConstraint/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetPlanScenarioConstraint.md" target="_blank">Group/BudgetPlanScenarioConstraint</a>|
|[AccessLevel](#AccessLevel)||<a href="BudgetPlanScenarioConstraint.md" target="_blank">Group/BudgetPlanScenarioConstraint</a>|
|[BudgetPlanningWorkflowStage](#BudgetPlanningWorkflowStage)||<a href="BudgetPlanScenarioConstraint.md" target="_blank">Group/BudgetPlanScenarioConstraint</a>|
|[BudgetPlanScenario](#BudgetPlanScenario)||<a href="BudgetPlanScenarioConstraint.md" target="_blank">Group/BudgetPlanScenarioConstraint</a>|
|[Relationship_BudgetPlanningWorkflowStageRelationshipId](#Relationship_BudgetPlanningWorkflowStageRelationshipId)||<a href="BudgetPlanScenarioConstraint.md" target="_blank">Group/BudgetPlanScenarioConstraint</a>|
|[Relationship_BudgetPlanScenarioRelationshipId](#Relationship_BudgetPlanScenarioRelationshipId)||<a href="BudgetPlanScenarioConstraint.md" target="_blank">Group/BudgetPlanScenarioConstraint</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/BudgetPlanScenarioConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanScenarioConstraint/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccessLevel name="AccessLevel">AccessLevel</a>

First included in: Group/BudgetPlanScenarioConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccessLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetPlanningWorkflowStage name="BudgetPlanningWorkflowStage">BudgetPlanningWorkflowStage</a>

First included in: Group/BudgetPlanScenarioConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningWorkflowStage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetPlanScenario name="BudgetPlanScenario">BudgetPlanScenario</a>

First included in: Group/BudgetPlanScenarioConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanScenario attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_BudgetPlanningWorkflowStageRelationshipId name="Relationship_BudgetPlanningWorkflowStageRelationshipId">Relationship_BudgetPlanningWorkflowStageRelationshipId</a>

First included in: Group/BudgetPlanScenarioConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetPlanningWorkflowStageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetPlanningWorkflowStage.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanningWorkflowStage.cdm.json/BudgetPlanningWorkflowStage</a></td><td><a href="BudgetPlanningWorkflowStage.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetPlanScenarioRelationshipId name="Relationship_BudgetPlanScenarioRelationshipId">Relationship_BudgetPlanScenarioRelationshipId</a>

First included in: Group/BudgetPlanScenarioConstraint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetPlanScenarioRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetPlanScenario.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanScenario.cdm.json/BudgetPlanScenario</a></td><td><a href="BudgetPlanScenario.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
