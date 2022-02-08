---
title: WorkflowWorkItemQueueGroupRelationEntity in Workflow - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Workflow work item queue relation table in Workflow(WorkflowWorkItemQueueGroupRelationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/Workflow/WorkflowWorkItemQueueGroupRelationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workflow work item queue relation table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WorkflowWorkitemQueue](#WorkflowWorkitemQueue)||<a href="WorkflowWorkItemQueueGroupRelationEntity.md" target="_blank">Workflow/WorkflowWorkItemQueueGroupRelationEntity</a>|
|[WorkflowWorkitemQueueGroup](#WorkflowWorkitemQueueGroup)||<a href="WorkflowWorkItemQueueGroupRelationEntity.md" target="_blank">Workflow/WorkflowWorkItemQueueGroupRelationEntity</a>|
|[WorkItemQueueName](#WorkItemQueueName)||<a href="WorkflowWorkItemQueueGroupRelationEntity.md" target="_blank">Workflow/WorkflowWorkItemQueueGroupRelationEntity</a>|
|[WorkItemQueueType](#WorkItemQueueType)||<a href="WorkflowWorkItemQueueGroupRelationEntity.md" target="_blank">Workflow/WorkflowWorkItemQueueGroupRelationEntity</a>|
|[WorkItemQueueGroupName](#WorkItemQueueGroupName)||<a href="WorkflowWorkItemQueueGroupRelationEntity.md" target="_blank">Workflow/WorkflowWorkItemQueueGroupRelationEntity</a>|
|[BackingTable_WorkflowWorkItemQueueGroupRelationRelationshipId](#BackingTable_WorkflowWorkItemQueueGroupRelationRelationshipId)||<a href="WorkflowWorkItemQueueGroupRelationEntity.md" target="_blank">Workflow/WorkflowWorkItemQueueGroupRelationEntity</a>|

### <a href=#WorkflowWorkitemQueue name="WorkflowWorkitemQueue">WorkflowWorkitemQueue</a>

First included in: Workflow/WorkflowWorkItemQueueGroupRelationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowWorkitemQueue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowWorkitemQueueGroup name="WorkflowWorkitemQueueGroup">WorkflowWorkitemQueueGroup</a>

First included in: Workflow/WorkflowWorkItemQueueGroupRelationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowWorkitemQueueGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkItemQueueName name="WorkItemQueueName">WorkItemQueueName</a>

First included in: Workflow/WorkflowWorkItemQueueGroupRelationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkItemQueueName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkItemQueueType name="WorkItemQueueType">WorkItemQueueType</a>

First included in: Workflow/WorkflowWorkItemQueueGroupRelationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkItemQueueType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkItemQueueGroupName name="WorkItemQueueGroupName">WorkItemQueueGroupName</a>

First included in: Workflow/WorkflowWorkItemQueueGroupRelationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkItemQueueGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WorkflowWorkItemQueueGroupRelationRelationshipId name="BackingTable_WorkflowWorkItemQueueGroupRelationRelationshipId">BackingTable_WorkflowWorkItemQueueGroupRelationRelationshipId</a>

First included in: Workflow/WorkflowWorkItemQueueGroupRelationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WorkflowWorkItemQueueGroupRelationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/Workflow/Framework/WorkflowWorkItemQueueGroupRelation.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowWorkItemQueueGroupRelation.cdm.json/WorkflowWorkItemQueueGroupRelation</a></td><td><a href="../../../Tables/System/Workflow/Framework/WorkflowWorkItemQueueGroupRelation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
