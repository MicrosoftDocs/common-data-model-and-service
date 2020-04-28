---
title: SysEmailAttachmentData - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Email attachment notification

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Framework/SysEmailAttachmentData.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysEmailAttachmentData/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email attachment notification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[DataSourceName](#DataSourceName)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[Description](#Description)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[DueDateTime](#DueDateTime)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[EmailId](#EmailId)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[MenuItemName](#MenuItemName)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[Subject](#Subject)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[User](#User)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[WorkflowAssociationType](#WorkflowAssociationType)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[WorkflowElementName](#WorkflowElementName)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[WorkflowWorkItemTable](#WorkflowWorkItemTable)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[WorkItemContext](#WorkItemContext)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|
|[Relationship_WorkItemTableRelationshipId](#Relationship_WorkItemTableRelationshipId)||<a href="SysEmailAttachmentData.md" target="_blank">Framework/SysEmailAttachmentData</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysEmailAttachmentData/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataSourceName name="DataSourceName">DataSourceName</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataSourceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueDateTime name="DueDateTime">DueDateTime</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EmailId name="EmailId">EmailId</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MenuItemName name="MenuItemName">MenuItemName</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Subject name="Subject">Subject</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Subject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#User name="User">User</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

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

### <a href=#WorkflowAssociationType name="WorkflowAssociationType">WorkflowAssociationType</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowAssociationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WorkflowElementName name="WorkflowElementName">WorkflowElementName</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowElementName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowWorkItemTable name="WorkflowWorkItemTable">WorkflowWorkItemTable</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowWorkItemTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkItemContext name="WorkItemContext">WorkItemContext</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkItemContext attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkItemTableRelationshipId name="Relationship_WorkItemTableRelationshipId">Relationship_WorkItemTableRelationshipId</a>

First included in: Framework/SysEmailAttachmentData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkItemTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Workflow/Framework/WorkflowWorkItemTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowWorkItemTable.cdm.json/WorkflowWorkItemTable</a></td><td><a href="../../Workflow/Framework/WorkflowWorkItemTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
