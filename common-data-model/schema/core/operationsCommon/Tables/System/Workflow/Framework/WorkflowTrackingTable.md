---
title: WorkflowTrackingTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# WorkflowTrackingTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowTrackingTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowTrackingTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[ElementId](#ElementId)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[Name](#Name)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[StepId](#StepId)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[TrackingContext](#TrackingContext)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[TrackingDateTimeTickCount](#TrackingDateTimeTickCount)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[TrackingId](#TrackingId)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[TrackingType](#TrackingType)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[User](#User)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[WorkflowElementTable](#WorkflowElementTable)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[WorkflowParallelBranchTable](#WorkflowParallelBranchTable)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[WorkflowStepTable](#WorkflowStepTable)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[WorkflowSubWorkflow](#WorkflowSubWorkflow)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[WorkflowTrackingStatusTable](#WorkflowTrackingStatusTable)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[Relationship_ParallelBranchRelationshipId](#Relationship_ParallelBranchRelationshipId)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[Relationship_SubWorkflowRelationshipId](#Relationship_SubWorkflowRelationshipId)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[Relationship_TrackingStatusRelationshipId](#Relationship_TrackingStatusRelationshipId)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[Relationship_WorkflowElementRelationshipId](#Relationship_WorkflowElementRelationshipId)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|
|[Relationship_WorkflowStepRelationshipId](#Relationship_WorkflowStepRelationshipId)||<a href="WorkflowTrackingTable.md" target="_blank">Framework/WorkflowTrackingTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowTrackingTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ElementId name="ElementId">ElementId</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

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

### <a href=#Name name="Name">Name</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

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

### <a href=#StepId name="StepId">StepId</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StepId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingContext name="TrackingContext">TrackingContext</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingContext attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TrackingDateTimeTickCount name="TrackingDateTimeTickCount">TrackingDateTimeTickCount</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingDateTimeTickCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TrackingId name="TrackingId">TrackingId</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingType name="TrackingType">TrackingType</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#User name="User">User</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the User attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowElementTable name="WorkflowElementTable">WorkflowElementTable</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowElementTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowParallelBranchTable name="WorkflowParallelBranchTable">WorkflowParallelBranchTable</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowParallelBranchTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowStepTable name="WorkflowStepTable">WorkflowStepTable</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowStepTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowSubWorkflow name="WorkflowSubWorkflow">WorkflowSubWorkflow</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowSubWorkflow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowTrackingStatusTable name="WorkflowTrackingStatusTable">WorkflowTrackingStatusTable</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowTrackingStatusTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_ParallelBranchRelationshipId name="Relationship_ParallelBranchRelationshipId">Relationship_ParallelBranchRelationshipId</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ParallelBranchRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SubWorkflowRelationshipId name="Relationship_SubWorkflowRelationshipId">Relationship_SubWorkflowRelationshipId</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SubWorkflowRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowSubWorkflow.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowSubWorkflow.cdm.json/WorkflowSubWorkflow</a></td><td><a href="WorkflowSubWorkflow.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TrackingStatusRelationshipId name="Relationship_TrackingStatusRelationshipId">Relationship_TrackingStatusRelationshipId</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrackingStatusRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowTrackingStatusTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowTrackingStatusTable.cdm.json/WorkflowTrackingStatusTable</a></td><td><a href="WorkflowTrackingStatusTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowElementRelationshipId name="Relationship_WorkflowElementRelationshipId">Relationship_WorkflowElementRelationshipId</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowElementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowElementTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowElementTable.cdm.json/WorkflowElementTable</a></td><td><a href="WorkflowElementTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowStepRelationshipId name="Relationship_WorkflowStepRelationshipId">Relationship_WorkflowStepRelationshipId</a>

First included in: Framework/WorkflowTrackingTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowStepRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowStepTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowStepTable.cdm.json/WorkflowStepTable</a></td><td><a href="WorkflowStepTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
