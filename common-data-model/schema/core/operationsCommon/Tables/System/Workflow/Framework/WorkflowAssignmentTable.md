---
title: WorkflowAssignmentTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# WorkflowAssignmentTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowAssignmentTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowAssignmentTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[ActorValue](#ActorValue)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[AssignmentRelationType](#AssignmentRelationType)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[AssignmentType](#AssignmentType)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[HierarchyFilterId](#HierarchyFilterId)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[HierarchyFilterType](#HierarchyFilterType)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[HierarchyProviderName](#HierarchyProviderName)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[HierarchyStopId](#HierarchyStopId)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[HierarchyTokenName](#HierarchyTokenName)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[ParticipantProviderName](#ParticipantProviderName)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[ParticipantTokenName](#ParticipantTokenName)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[QueueProviderName](#QueueProviderName)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[QueueTokenName](#QueueTokenName)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[UserValue](#UserValue)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[WorkflowElementNotificationTable](#WorkflowElementNotificationTable)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[WorkflowEscalationPathTable](#WorkflowEscalationPathTable)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[WorkflowStepTable](#WorkflowStepTable)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[WorkflowVersionNotificationTable](#WorkflowVersionNotificationTable)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[Relationship_FilterConditionRelationshipId](#Relationship_FilterConditionRelationshipId)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[Relationship_StopConditionRelationshipId](#Relationship_StopConditionRelationshipId)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[Relationship_WorkflowElementNotificationTableRelationshipId](#Relationship_WorkflowElementNotificationTableRelationshipId)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[Relationship_WorkflowEscalationPathTableRelationshipId](#Relationship_WorkflowEscalationPathTableRelationshipId)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[Relationship_WorkflowStepTableRelationshipId](#Relationship_WorkflowStepTableRelationshipId)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|
|[Relationship_WorkflowVersionNotificationTableRelationshipId](#Relationship_WorkflowVersionNotificationTableRelationshipId)||<a href="WorkflowAssignmentTable.md" target="_blank">Framework/WorkflowAssignmentTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowAssignmentTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActorValue name="ActorValue">ActorValue</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActorValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssignmentRelationType name="AssignmentRelationType">AssignmentRelationType</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignmentRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssignmentType name="AssignmentType">AssignmentType</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignmentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HierarchyFilterId name="HierarchyFilterId">HierarchyFilterId</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyFilterId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyFilterType name="HierarchyFilterType">HierarchyFilterType</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyFilterType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HierarchyProviderName name="HierarchyProviderName">HierarchyProviderName</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyStopId name="HierarchyStopId">HierarchyStopId</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyStopId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyTokenName name="HierarchyTokenName">HierarchyTokenName</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParticipantProviderName name="ParticipantProviderName">ParticipantProviderName</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParticipantProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParticipantTokenName name="ParticipantTokenName">ParticipantTokenName</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParticipantTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueProviderName name="QueueProviderName">QueueProviderName</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueTokenName name="QueueTokenName">QueueTokenName</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserValue name="UserValue">UserValue</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowElementNotificationTable name="WorkflowElementNotificationTable">WorkflowElementNotificationTable</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowElementNotificationTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowEscalationPathTable name="WorkflowEscalationPathTable">WorkflowEscalationPathTable</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowEscalationPathTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowStepTable name="WorkflowStepTable">WorkflowStepTable</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

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

### <a href=#WorkflowVersionNotificationTable name="WorkflowVersionNotificationTable">WorkflowVersionNotificationTable</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowVersionNotificationTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_FilterConditionRelationshipId name="Relationship_FilterConditionRelationshipId">Relationship_FilterConditionRelationshipId</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FilterConditionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SystemAdministration/Framework/ExpressionTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/ExpressionTable.cdm.json/ExpressionTable</a></td><td><a href="../../SystemAdministration/Framework/ExpressionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_StopConditionRelationshipId name="Relationship_StopConditionRelationshipId">Relationship_StopConditionRelationshipId</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StopConditionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SystemAdministration/Framework/ExpressionTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/ExpressionTable.cdm.json/ExpressionTable</a></td><td><a href="../../SystemAdministration/Framework/ExpressionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowElementNotificationTableRelationshipId name="Relationship_WorkflowElementNotificationTableRelationshipId">Relationship_WorkflowElementNotificationTableRelationshipId</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowElementNotificationTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowElementNotificationTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowElementNotificationTable.cdm.json/WorkflowElementNotificationTable</a></td><td><a href="WorkflowElementNotificationTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowEscalationPathTableRelationshipId name="Relationship_WorkflowEscalationPathTableRelationshipId">Relationship_WorkflowEscalationPathTableRelationshipId</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowEscalationPathTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowEscalationPathTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowEscalationPathTable.cdm.json/WorkflowEscalationPathTable</a></td><td><a href="WorkflowEscalationPathTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowStepTableRelationshipId name="Relationship_WorkflowStepTableRelationshipId">Relationship_WorkflowStepTableRelationshipId</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowStepTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WorkflowVersionNotificationTableRelationshipId name="Relationship_WorkflowVersionNotificationTableRelationshipId">Relationship_WorkflowVersionNotificationTableRelationshipId</a>

First included in: Framework/WorkflowAssignmentTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowVersionNotificationTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowVersionNotificationTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowVersionNotificationTable.cdm.json/WorkflowVersionNotificationTable</a></td><td><a href="WorkflowVersionNotificationTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
