---
title: WorkflowWorkItemDelegationParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# WorkflowWorkItemDelegationParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/Workflow/Parameter/WorkflowWorkItemDelegationParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowWorkItemDelegationParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[User](#User)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[CategoryName](#CategoryName)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[CommentId](#CommentId)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[ConfigurationSequenceNumber](#ConfigurationSequenceNumber)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[DelegateTo](#DelegateTo)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[Enabled](#Enabled)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[FromDate](#FromDate)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[Id](#Id)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[ToDate](#ToDate)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[Type](#Type)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[Relationship_WorkflowTableRelationshipId](#Relationship_WorkflowTableRelationshipId)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|
|[Relationship_WorkflowWorkItemCommentTableRelationshipId](#Relationship_WorkflowWorkItemCommentTableRelationshipId)||<a href="WorkflowWorkItemDelegationParameters.md" target="_blank">Parameter/WorkflowWorkItemDelegationParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowWorkItemDelegationParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#User name="User">User</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

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

### <a href=#CategoryName name="CategoryName">CategoryName</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

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

### <a href=#CommentId name="CommentId">CommentId</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigurationSequenceNumber name="ConfigurationSequenceNumber">ConfigurationSequenceNumber</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigurationSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DelegateTo name="DelegateTo">DelegateTo</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DelegateTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Enabled name="Enabled">Enabled</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Enabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Id name="Id">Id</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_WorkflowTableRelationshipId name="Relationship_WorkflowTableRelationshipId">Relationship_WorkflowTableRelationshipId</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Framework/WorkflowTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowTable.cdm.json/WorkflowTable</a></td><td><a href="../Framework/WorkflowTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowWorkItemCommentTableRelationshipId name="Relationship_WorkflowWorkItemCommentTableRelationshipId">Relationship_WorkflowWorkItemCommentTableRelationshipId</a>

First included in: Parameter/WorkflowWorkItemDelegationParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowWorkItemCommentTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Framework/WorkflowWorkItemCommentTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowWorkItemCommentTable.cdm.json/WorkflowWorkItemCommentTable</a></td><td><a href="../Framework/WorkflowWorkItemCommentTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
