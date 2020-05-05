---
title: ProjQuotationWbsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Project quotation work breakdown structure

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjQuotationWbsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project quotation work breakdown structure</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[QuotationId](#QuotationId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[HierarchyId](#HierarchyId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[TaskId](#TaskId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[WBSId](#WBSId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Note](#Note)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Task](#Task)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Predecessors](#Predecessors)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Category](#Category)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Effort](#Effort)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[StartDate](#StartDate)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[EndDate](#EndDate)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Duration](#Duration)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[NumberOfResources](#NumberOfResources)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Role](#Role)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[IsTaskClosed](#IsTaskClosed)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[IsTaskMandatory](#IsTaskMandatory)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[HierarchyTreeTableRefRecId](#HierarchyTreeTableRefRecId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[TaskSiblingNumber](#TaskSiblingNumber)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[ParentTaskId](#ParentTaskId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[ResourceCategory](#ResourceCategory)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[TaskPriority](#TaskPriority)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[ActivityTaskTimeType](#ActivityTaskTimeType)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[IsCategoryMandatory](#IsCategoryMandatory)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[CalendarId](#CalendarId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[EndNode](#EndNode)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[HierarchyLevel](#HierarchyLevel)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[CalendarStandardWorkDayHours](#CalendarStandardWorkDayHours)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[TaskEffortAtComplete](#TaskEffortAtComplete)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[TaskCostAtComplete](#TaskCostAtComplete)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Relationship_ProjectCategoryRelationshipId](#Relationship_ProjectCategoryRelationshipId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Relationship_ResourceCategoryRelationshipId](#Relationship_ResourceCategoryRelationshipId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[BackingTable_ProjPlanVersionRelationshipId](#BackingTable_ProjPlanVersionRelationshipId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjQuotationWbsEntity.md" target="_blank">ProjectManagementAndAccounting/ProjQuotationWbsEntity</a>|

### <a href=#QuotationId name="QuotationId">QuotationId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quotation Id</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quotation Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyId name="HierarchyId">HierarchyId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaskId name="TaskId">TaskId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WBSId name="WBSId">WBSId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WBSId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Note attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Task name="Task">Task</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Task attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Predecessors name="Predecessors">Predecessors</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Predecessors</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Predecessors attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Predecessors</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Category attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Effort name="Effort">Effort</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Effort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Duration name="Duration">Duration</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Duration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfResources name="NumberOfResources">NumberOfResources</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfResources attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Role name="Role">Role</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Role attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Role</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTaskClosed name="IsTaskClosed">IsTaskClosed</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaskClosed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTaskMandatory name="IsTaskMandatory">IsTaskMandatory</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaskMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyTreeTableRefRecId name="HierarchyTreeTableRefRecId">HierarchyTreeTableRefRecId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyTreeTableRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaskSiblingNumber name="TaskSiblingNumber">TaskSiblingNumber</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskSiblingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentTaskId name="ParentTaskId">ParentTaskId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentTaskId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCategory name="ResourceCategory">ResourceCategory</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaskPriority name="TaskPriority">TaskPriority</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityTaskTimeType name="ActivityTaskTimeType">ActivityTaskTimeType</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityTaskTimeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCategoryMandatory name="IsCategoryMandatory">IsCategoryMandatory</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCategoryMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarId name="CalendarId">CalendarId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndNode name="EndNode">EndNode</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndNode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyLevel name="HierarchyLevel">HierarchyLevel</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarStandardWorkDayHours name="CalendarStandardWorkDayHours">CalendarStandardWorkDayHours</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarStandardWorkDayHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaskEffortAtComplete name="TaskEffortAtComplete">TaskEffortAtComplete</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskEffortAtComplete attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaskCostAtComplete name="TaskCostAtComplete">TaskCostAtComplete</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskCostAtComplete attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjectCategoryRelationshipId name="Relationship_ProjectCategoryRelationshipId">Relationship_ProjectCategoryRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectCategoryRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ResourceCategoryRelationshipId name="Relationship_ResourceCategoryRelationshipId">Relationship_ResourceCategoryRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResourceCategoryRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ProjPlanVersionRelationshipId name="BackingTable_ProjPlanVersionRelationshipId">BackingTable_ProjPlanVersionRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjPlanVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPlanVersion.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPlanVersion.cdm.json/ProjPlanVersion</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPlanVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjQuotationWbsEntity (this entity)  

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
