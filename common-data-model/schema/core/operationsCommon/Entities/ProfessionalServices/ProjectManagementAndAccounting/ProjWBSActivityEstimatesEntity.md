---
title: ProjWBSActivityEstimatesEntity in ProjectManagementAndAccounting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Project work breakdown structure - Draft estimates in ProjectManagementAndAccounting(ProjWBSActivityEstimatesEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project work breakdown structure - Draft estimates</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProjectId](#ProjectId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[HierarchyId](#HierarchyId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[TaskId](#TaskId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[WBSId](#WBSId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[TaskName](#TaskName)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[Description](#Description)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[LineProperty](#LineProperty)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[Category](#Category)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[TransactionType](#TransactionType)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[Quantity](#Quantity)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[ResourceCategoryRecId](#ResourceCategoryRecId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[SalesCategoryRecId](#SalesCategoryRecId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[UnitCostPrice](#UnitCostPrice)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[UnitSalesPrice](#UnitSalesPrice)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[ResourceCategory](#ResourceCategory)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[SalesCategory](#SalesCategory)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[TotalCostPrice](#TotalCostPrice)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[TotalSalesPrice](#TotalSalesPrice)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[Relationship_ProjectRelationshipId](#Relationship_ProjectRelationshipId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[Relationship_ProjectCategoryRelationshipId](#Relationship_ProjectCategoryRelationshipId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[Relationship_ResourceCategoryRelationshipId](#Relationship_ResourceCategoryRelationshipId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[BackingTable_PSAActivityEstimatesRelationshipId](#BackingTable_PSAActivityEstimatesRelationshipId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjWBSActivityEstimatesEntity.md" target="_blank">ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity</a>|

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyId name="HierarchyId">HierarchyId</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

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

### <a href=#TaskName name="TaskName">TaskName</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineProperty name="LineProperty">LineProperty</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

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

### <a href=#TransactionType name="TransactionType">TransactionType</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCategoryRecId name="ResourceCategoryRecId">ResourceCategoryRecId</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategoryRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCategoryRecId name="SalesCategoryRecId">SalesCategoryRecId</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCategoryRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCostPrice name="UnitCostPrice">UnitCostPrice</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCostPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitSalesPrice name="UnitSalesPrice">UnitSalesPrice</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitSalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCategory name="ResourceCategory">ResourceCategory</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategory attribute are listed below.</summary>

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

### <a href=#SalesCategory name="SalesCategory">SalesCategory</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalCostPrice name="TotalCostPrice">TotalCostPrice</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCostPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalSalesPrice name="TotalSalesPrice">TotalSalesPrice</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalSalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjectRelationshipId name="Relationship_ProjectRelationshipId">Relationship_ProjectRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjectCategoryRelationshipId name="Relationship_ProjectCategoryRelationshipId">Relationship_ProjectCategoryRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

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

### <a href=#BackingTable_PSAActivityEstimatesRelationshipId name="BackingTable_PSAActivityEstimatesRelationshipId">BackingTable_PSAActivityEstimatesRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PSAActivityEstimatesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/Project/Miscellaneous/PSAActivityEstimates.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/Project/Miscellaneous/PSAActivityEstimates.cdm.json/PSAActivityEstimates</a></td><td><a href="../../../Tables/ProfessionalServices/Project/Miscellaneous/PSAActivityEstimates.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjWBSActivityEstimatesEntity (this entity)  

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
