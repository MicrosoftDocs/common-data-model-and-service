---
title: WorkflowSubWorkflow - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# WorkflowSubWorkflow

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowSubWorkflow.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowSubWorkflow/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[DocumentKeyField](#DocumentKeyField)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[DocumentKeyTable](#DocumentKeyTable)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[ElementId](#ElementId)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[ElementName](#ElementName)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[ElementType](#ElementType)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[LineItemType](#LineItemType)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[Name](#Name)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[ParallelBranchTable](#ParallelBranchTable)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[WaitForComplete](#WaitForComplete)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[WorkflowTable](#WorkflowTable)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[WorkflowVersionTable](#WorkflowVersionTable)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[Relationship_WorkflowParallelBranchTableRelationshipId](#Relationship_WorkflowParallelBranchTableRelationshipId)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[Relationship_WorkflowTableRelationshipId](#Relationship_WorkflowTableRelationshipId)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|
|[Relationship_WorkflowVersionTableRelationshipId](#Relationship_WorkflowVersionTableRelationshipId)||<a href="WorkflowSubWorkflow.md" target="_blank">Framework/WorkflowSubWorkflow</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowSubWorkflow/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocumentKeyField name="DocumentKeyField">DocumentKeyField</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentKeyField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentKeyTable name="DocumentKeyTable">DocumentKeyTable</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentKeyTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElementId name="ElementId">ElementId</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElementName name="ElementName">ElementName</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElementType name="ElementType">ElementType</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineItemType name="LineItemType">LineItemType</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineItemType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParallelBranchTable name="ParallelBranchTable">ParallelBranchTable</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParallelBranchTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WaitForComplete name="WaitForComplete">WaitForComplete</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaitForComplete attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WorkflowTable name="WorkflowTable">WorkflowTable</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowVersionTable name="WorkflowVersionTable">WorkflowVersionTable</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowVersionTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_WorkflowParallelBranchTableRelationshipId name="Relationship_WorkflowParallelBranchTableRelationshipId">Relationship_WorkflowParallelBranchTableRelationshipId</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowParallelBranchTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowParallelBranchTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowParallelBranchTable.cdm.json/WorkflowParallelBranchTable</a></td><td><a href="WorkflowParallelBranchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowTableRelationshipId name="Relationship_WorkflowTableRelationshipId">Relationship_WorkflowTableRelationshipId</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowTable.cdm.json/WorkflowTable</a></td><td><a href="WorkflowTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowVersionTableRelationshipId name="Relationship_WorkflowVersionTableRelationshipId">Relationship_WorkflowVersionTableRelationshipId</a>

First included in: Framework/WorkflowSubWorkflow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowVersionTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowVersionTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowVersionTable.cdm.json/WorkflowVersionTable</a></td><td><a href="WorkflowVersionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
