---
title: RetailEcoResCategoryHierarchyRoleEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @SYS130839

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailEcoResCategoryHierarchyRoleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@SYS130839</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Retail/RetailEcoResCategoryHierarchyRoleEntity</a>|
|[NamedCategoryHierarchyRole](#NamedCategoryHierarchyRole)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Retail/RetailEcoResCategoryHierarchyRoleEntity</a>|
|[EcoResCategoryHierarchy_Name](#EcoResCategoryHierarchy_Name)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Retail/RetailEcoResCategoryHierarchyRoleEntity</a>|
|[NamedCategoryHierarchyRoleAsInt](#NamedCategoryHierarchyRoleAsInt)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Retail/RetailEcoResCategoryHierarchyRoleEntity</a>|
|[BackingTable_EcoResCategoryHierarchyRoleRelationshipId](#BackingTable_EcoResCategoryHierarchyRoleRelationshipId)||<a href="RetailEcoResCategoryHierarchyRoleEntity.md" target="_blank">Retail/RetailEcoResCategoryHierarchyRoleEntity</a>|

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: Retail/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NamedCategoryHierarchyRole attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EcoResCategoryHierarchy_Name name="EcoResCategoryHierarchy_Name">EcoResCategoryHierarchy_Name</a>

First included in: Retail/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailEcoResCategoryHierarchyRoleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResCategoryHierarchyRoleRelationshipId attribute are listed below.</summary>

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
