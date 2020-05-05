---
title: ProjCollaborationWorkspaceSettingsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Project general settings for collaboration workspaces

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project general settings for collaboration workspaces</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsWorkspaceAutoCreatedForCost](#IsWorkspaceAutoCreatedForCost)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[IsWorkspaceAutoCreatedForFixedPrice](#IsWorkspaceAutoCreatedForFixedPrice)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[IsWorkspaceAutoCreatedForInternal](#IsWorkspaceAutoCreatedForInternal)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[IsWorkspaceAutoCreatedForInvestment](#IsWorkspaceAutoCreatedForInvestment)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[IsWorkspaceAutoCreated](#IsWorkspaceAutoCreated)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[IsWorkspaceAutoCreatedForTime](#IsWorkspaceAutoCreatedForTime)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[IsWorkspaceAutoCreatedForTimeMaterial](#IsWorkspaceAutoCreatedForTimeMaterial)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[BusinessArea](#BusinessArea)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[IsCreatingWorkspacePrompted](#IsCreatingWorkspacePrompted)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[IsDeletingWorkspacePrompted](#IsDeletingWorkspacePrompted)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[WorkspaceHomePage](#WorkspaceHomePage)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[SharePointVersion](#SharePointVersion)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[StoreMSProjectFiles](#StoreMSProjectFiles)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[SyncTaskLists](#SyncTaskLists)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[Template](#Template)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[BackingTable_CollabSiteParametersRelationshipId](#BackingTable_CollabSiteParametersRelationshipId)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjCollaborationWorkspaceSettingsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity</a>|

### <a href=#IsWorkspaceAutoCreatedForCost name="IsWorkspaceAutoCreatedForCost">IsWorkspaceAutoCreatedForCost</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkspaceAutoCreatedForCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkspaceAutoCreatedForFixedPrice name="IsWorkspaceAutoCreatedForFixedPrice">IsWorkspaceAutoCreatedForFixedPrice</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkspaceAutoCreatedForFixedPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkspaceAutoCreatedForInternal name="IsWorkspaceAutoCreatedForInternal">IsWorkspaceAutoCreatedForInternal</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkspaceAutoCreatedForInternal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkspaceAutoCreatedForInvestment name="IsWorkspaceAutoCreatedForInvestment">IsWorkspaceAutoCreatedForInvestment</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkspaceAutoCreatedForInvestment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkspaceAutoCreated name="IsWorkspaceAutoCreated">IsWorkspaceAutoCreated</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkspaceAutoCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkspaceAutoCreatedForTime name="IsWorkspaceAutoCreatedForTime">IsWorkspaceAutoCreatedForTime</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkspaceAutoCreatedForTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkspaceAutoCreatedForTimeMaterial name="IsWorkspaceAutoCreatedForTimeMaterial">IsWorkspaceAutoCreatedForTimeMaterial</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkspaceAutoCreatedForTimeMaterial attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessArea name="BusinessArea">BusinessArea</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreatingWorkspacePrompted name="IsCreatingWorkspacePrompted">IsCreatingWorkspacePrompted</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreatingWorkspacePrompted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeletingWorkspacePrompted name="IsDeletingWorkspacePrompted">IsDeletingWorkspacePrompted</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeletingWorkspacePrompted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkspaceHomePage name="WorkspaceHomePage">WorkspaceHomePage</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkspaceHomePage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SharePointVersion name="SharePointVersion">SharePointVersion</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharePointVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreMSProjectFiles name="StoreMSProjectFiles">StoreMSProjectFiles</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreMSProjectFiles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SyncTaskLists name="SyncTaskLists">SyncTaskLists</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SyncTaskLists attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Template name="Template">Template</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Template attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CollabSiteParametersRelationshipId name="BackingTable_CollabSiteParametersRelationshipId">BackingTable_CollabSiteParametersRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CollabSiteParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/Project/Parameter/CollabSiteParameters.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/Project/Parameter/CollabSiteParameters.cdm.json/CollabSiteParameters</a></td><td><a href="../../../Tables/ProfessionalServices/Project/Parameter/CollabSiteParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjCollaborationWorkspaceSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
