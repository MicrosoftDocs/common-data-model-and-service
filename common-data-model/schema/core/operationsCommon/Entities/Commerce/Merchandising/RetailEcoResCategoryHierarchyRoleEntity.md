---
title: RetailEcoResCategoryHierarchyRoleEntity in Merchandising - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Category hierarchy roles in Merchandising(RetailEcoResCategoryHierarchyRoleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Merchandising/RetailEcoResCategoryHierarchyRoleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category hierarchy roles</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Merchandising/RetailEcoResCategoryHierarchyRoleEntity</a>|
|[NamedCategoryHierarchyRole](#NamedCategoryHierarchyRole)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Merchandising/RetailEcoResCategoryHierarchyRoleEntity</a>|
|[EcoResCategoryHierarchy_Name](#EcoResCategoryHierarchy_Name)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Merchandising/RetailEcoResCategoryHierarchyRoleEntity</a>|
|[NamedCategoryHierarchyRoleAsInt](#NamedCategoryHierarchyRoleAsInt)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Merchandising/RetailEcoResCategoryHierarchyRoleEntity</a>|
|[BackingTable_EcoResCategoryHierarchyRoleRelationshipId](#BackingTable_EcoResCategoryHierarchyRoleRelationshipId)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Merchandising/RetailEcoResCategoryHierarchyRoleEntity</a>|

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: Merchandising/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NamedCategoryHierarchyRole name="NamedCategoryHierarchyRole">NamedCategoryHierarchyRole</a>

First included in: Merchandising/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NamedCategoryHierarchyRole attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EcoResCategoryHierarchy_Name name="EcoResCategoryHierarchy_Name">EcoResCategoryHierarchy_Name</a>

First included in: Merchandising/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResCategoryHierarchy_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NamedCategoryHierarchyRoleAsInt name="NamedCategoryHierarchyRoleAsInt">NamedCategoryHierarchyRoleAsInt</a>

First included in: Merchandising/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NamedCategoryHierarchyRoleAsInt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResCategoryHierarchyRoleRelationshipId name="BackingTable_EcoResCategoryHierarchyRoleRelationshipId">BackingTable_EcoResCategoryHierarchyRoleRelationshipId</a>

First included in: Merchandising/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResCategoryHierarchyRoleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchyRole.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchyRole.cdm.json/EcoResCategoryHierarchyRole</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchyRole.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
