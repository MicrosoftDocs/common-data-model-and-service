---
title: WorkflowVersionNotificationEntity in Workflow - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Workflow version notification in Workflow(WorkflowVersionNotificationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/Workflow/WorkflowVersionNotificationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workflow version notification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Action](#Action)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[Enabled](#Enabled)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[WorkflowId](#WorkflowId)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[WorkflowUserValue](#WorkflowUserValue)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[AssignmentRelationType](#AssignmentRelationType)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[AssignmentType](#AssignmentType)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[HierarchyFilterConditionId](#HierarchyFilterConditionId)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[HierarchyFilterType](#HierarchyFilterType)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[HierarchyProviderName](#HierarchyProviderName)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[HierarchyStopConditionId](#HierarchyStopConditionId)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[HierarchyTokenName](#HierarchyTokenName)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[ParticipantProviderName](#ParticipantProviderName)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[ParticipantTokenName](#ParticipantTokenName)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[QueueProviderName](#QueueProviderName)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[QueueTokenName](#QueueTokenName)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[UserValue](#UserValue)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[Relationship_WorkflowVersionRelationshipId](#Relationship_WorkflowVersionRelationshipId)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|
|[BackingTable_WorkflowVersionNotificationTableRelationshipId](#BackingTable_WorkflowVersionNotificationTableRelationshipId)||<a href="WorkflowVersionNotificationEntity.md" target="_blank">Workflow/WorkflowVersionNotificationEntity</a>|

### <a href=#Action name="Action">Action</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Action attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Enabled name="Enabled">Enabled</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Enabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowId name="WorkflowId">WorkflowId</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

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

### <a href=#WorkflowUserValue name="WorkflowUserValue">WorkflowUserValue</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowUserValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssignmentRelationType name="AssignmentRelationType">AssignmentRelationType</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignmentRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssignmentType name="AssignmentType">AssignmentType</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignmentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyFilterConditionId name="HierarchyFilterConditionId">HierarchyFilterConditionId</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyFilterConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyFilterType name="HierarchyFilterType">HierarchyFilterType</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyFilterType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyProviderName name="HierarchyProviderName">HierarchyProviderName</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyStopConditionId name="HierarchyStopConditionId">HierarchyStopConditionId</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyStopConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyTokenName name="HierarchyTokenName">HierarchyTokenName</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParticipantProviderName name="ParticipantProviderName">ParticipantProviderName</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParticipantProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParticipantTokenName name="ParticipantTokenName">ParticipantTokenName</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParticipantTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueProviderName name="QueueProviderName">QueueProviderName</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueTokenName name="QueueTokenName">QueueTokenName</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserValue name="UserValue">UserValue</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowVersionRelationshipId name="Relationship_WorkflowVersionRelationshipId">Relationship_WorkflowVersionRelationshipId</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WorkflowVersionNotificationTableRelationshipId name="BackingTable_WorkflowVersionNotificationTableRelationshipId">BackingTable_WorkflowVersionNotificationTableRelationshipId</a>

First included in: Workflow/WorkflowVersionNotificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WorkflowVersionNotificationTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/Workflow/Framework/WorkflowVersionNotificationTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowVersionNotificationTable.cdm.json/WorkflowVersionNotificationTable</a></td><td><a href="../../../Tables/System/Workflow/Framework/WorkflowVersionNotificationTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
