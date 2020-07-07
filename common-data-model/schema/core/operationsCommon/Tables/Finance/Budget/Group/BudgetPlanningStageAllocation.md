---
title: BudgetPlanningStageAllocation in Group - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Budget planning allocation stages in Group

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanningStageAllocation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanningStageAllocation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget planning allocation stages</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetPlanningStageAllocation.md" target="_blank">Group/BudgetPlanningStageAllocation</a>|
|[BudgetPlanningAllocationSchedule](#BudgetPlanningAllocationSchedule)||<a href="BudgetPlanningStageAllocation.md" target="_blank">Group/BudgetPlanningStageAllocation</a>|
|[BudgetPlanningWorkflowStage](#BudgetPlanningWorkflowStage)||<a href="BudgetPlanningStageAllocation.md" target="_blank">Group/BudgetPlanningStageAllocation</a>|
|[Ordinal](#Ordinal)||<a href="BudgetPlanningStageAllocation.md" target="_blank">Group/BudgetPlanningStageAllocation</a>|
|[Relationship_BudgetPlanningAllocationScheduleRelationshipId](#Relationship_BudgetPlanningAllocationScheduleRelationshipId)||<a href="BudgetPlanningStageAllocation.md" target="_blank">Group/BudgetPlanningStageAllocation</a>|
|[Relationship_BudgetPlanningWorkflowStageRelationshipId](#Relationship_BudgetPlanningWorkflowStageRelationshipId)||<a href="BudgetPlanningStageAllocation.md" target="_blank">Group/BudgetPlanningStageAllocation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/BudgetPlanningStageAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanningStageAllocation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetPlanningAllocationSchedule name="BudgetPlanningAllocationSchedule">BudgetPlanningAllocationSchedule</a>

First included in: Group/BudgetPlanningStageAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningAllocationSchedule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetPlanningWorkflowStage name="BudgetPlanningWorkflowStage">BudgetPlanningWorkflowStage</a>

First included in: Group/BudgetPlanningStageAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget planning workflow and stage</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningWorkflowStage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget planning workflow and stage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Ordinal name="Ordinal">Ordinal</a>

First included in: Group/BudgetPlanningStageAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ordinal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_BudgetPlanningAllocationScheduleRelationshipId name="Relationship_BudgetPlanningAllocationScheduleRelationshipId">Relationship_BudgetPlanningAllocationScheduleRelationshipId</a>

First included in: Group/BudgetPlanningStageAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetPlanningAllocationScheduleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetPlanningAllocationSchedule.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanningAllocationSchedule.cdm.json/BudgetPlanningAllocationSchedule</a></td><td><a href="BudgetPlanningAllocationSchedule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetPlanningWorkflowStageRelationshipId name="Relationship_BudgetPlanningWorkflowStageRelationshipId">Relationship_BudgetPlanningWorkflowStageRelationshipId</a>

First included in: Group/BudgetPlanningStageAllocation (this entity)  

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
