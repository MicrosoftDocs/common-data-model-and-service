---
title: WorkflowVersionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# WorkflowVersionEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/System/Workflow/WorkflowVersionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ActivationConditionId](#ActivationConditionId)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[ActivationConditionType](#ActivationConditionType)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[WorkflowId](#WorkflowId)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[IsActive](#IsActive)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[Owner](#Owner)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[Valid](#Valid)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[VersionIdBuild](#VersionIdBuild)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[VersionIdMajor](#VersionIdMajor)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[VersionIdMinor](#VersionIdMinor)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[VersionIdRevision](#VersionIdRevision)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[WorkflowTable](#WorkflowTable)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[EmailTemplateId](#EmailTemplateId)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[AssociationType](#AssociationType)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[CategoryName](#CategoryName)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[DataArea](#DataArea)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[IsDefault](#IsDefault)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[DocumentTableName](#DocumentTableName)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[Module](#Module)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[Name](#Name)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[WorkflowNumber](#WorkflowNumber)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[WorkflowTypeName](#WorkflowTypeName)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[Type](#Type)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[VersionId](#VersionId)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[Relationship_ActiviationConditionRelationshipId](#Relationship_ActiviationConditionRelationshipId)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|
|[BackingTable_WorkflowVersionTableRelationshipId](#BackingTable_WorkflowVersionTableRelationshipId)||<a href="WorkflowVersionEntity.md" target="_blank">Workflow/WorkflowVersionEntity</a>|

### <a href=#ActivationConditionId name="ActivationConditionId">ActivationConditionId</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivationConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivationConditionType name="ActivationConditionType">ActivationConditionType</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivationConditionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowId name="WorkflowId">WorkflowId</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActive name="IsActive">IsActive</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Owner name="Owner">Owner</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Owner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Valid name="Valid">Valid</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Valid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionIdBuild name="VersionIdBuild">VersionIdBuild</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionIdBuild attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionIdMajor name="VersionIdMajor">VersionIdMajor</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionIdMajor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionIdMinor name="VersionIdMinor">VersionIdMinor</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionIdMinor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionIdRevision name="VersionIdRevision">VersionIdRevision</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionIdRevision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowTable name="WorkflowTable">WorkflowTable</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailTemplateId name="EmailTemplateId">EmailTemplateId</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssociationType name="AssociationType">AssociationType</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryName name="CategoryName">CategoryName</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataArea name="DataArea">DataArea</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefault name="IsDefault">IsDefault</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentTableName name="DocumentTableName">DocumentTableName</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Module name="Module">Module</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Module attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

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

### <a href=#WorkflowNumber name="WorkflowNumber">WorkflowNumber</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowTypeName name="WorkflowTypeName">WorkflowTypeName</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionId name="VersionId">VersionId</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ActiviationConditionRelationshipId name="Relationship_ActiviationConditionRelationshipId">Relationship_ActiviationConditionRelationshipId</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ActiviationConditionRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WorkflowVersionTableRelationshipId name="BackingTable_WorkflowVersionTableRelationshipId">BackingTable_WorkflowVersionTableRelationshipId</a>

First included in: Workflow/WorkflowVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WorkflowVersionTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/Workflow/Framework/WorkflowVersionTable.md" target="_blank">/core/erp/Tables/System/Workflow/Framework/WorkflowVersionTable.cdm.json/WorkflowVersionTable</a></td><td><a href="../../../Tables/System/Workflow/Framework/WorkflowVersionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
