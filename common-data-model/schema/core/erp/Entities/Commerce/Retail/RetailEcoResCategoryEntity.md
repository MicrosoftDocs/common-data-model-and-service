---
title: RetailEcoResCategoryEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @SYS134266

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailEcoResCategoryEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@SYS134266</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[ChangeStatus](#ChangeStatus)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[Code](#Code)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[DefaultProjectGlobalCategory](#DefaultProjectGlobalCategory)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[DefaultThreshold_PSN](#DefaultThreshold_PSN)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[IsActive](#IsActive)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[IsCategoryAttributesInherited](#IsCategoryAttributesInherited)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[IsTangible](#IsTangible)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[Level](#Level)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[Name](#Name)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[NestedSetLeft](#NestedSetLeft)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[NestedSetRight](#NestedSetRight)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[ParentCategory](#ParentCategory)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[PKWiUCode](#PKWiUCode)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[SharedCategory_CategoryId](#SharedCategory_CategoryId)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[EcoResCategoryHierarchy_Name](#EcoResCategoryHierarchy_Name)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[EcoResCategory1_CategoryHierarchy](#EcoResCategory1_CategoryHierarchy)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[EcoResCategory1_Name](#EcoResCategory1_Name)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[EcoResCategoryHierarchy1_Name](#EcoResCategoryHierarchy1_Name)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[AxRecId](#AxRecId)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|
|[BackingTable_EcoResCategoryRelationshipId](#BackingTable_EcoResCategoryRelationshipId)||<a href="RetailEcoResCategoryEntity.md" target="_blank">Retail/RetailEcoResCategoryEntity</a>|

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

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

### <a href=#ChangeStatus name="ChangeStatus">ChangeStatus</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Code name="Code">Code</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Code attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProjectGlobalCategory name="DefaultProjectGlobalCategory">DefaultProjectGlobalCategory</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProjectGlobalCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultThreshold_PSN name="DefaultThreshold_PSN">DefaultThreshold_PSN</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultThreshold_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActive name="IsActive">IsActive</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

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

### <a href=#IsCategoryAttributesInherited name="IsCategoryAttributesInherited">IsCategoryAttributesInherited</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCategoryAttributesInherited attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTangible name="IsTangible">IsTangible</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTangible attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level name="Level">Level</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

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

### <a href=#NestedSetLeft name="NestedSetLeft">NestedSetLeft</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NestedSetLeft attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NestedSetRight name="NestedSetRight">NestedSetRight</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NestedSetRight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentCategory name="ParentCategory">ParentCategory</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PKWiUCode name="PKWiUCode">PKWiUCode</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PKWiUCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SharedCategory_CategoryId name="SharedCategory_CategoryId">SharedCategory_CategoryId</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedCategory_CategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EcoResCategoryHierarchy_Name name="EcoResCategoryHierarchy_Name">EcoResCategoryHierarchy_Name</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

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

### <a href=#EcoResCategory1_CategoryHierarchy name="EcoResCategory1_CategoryHierarchy">EcoResCategory1_CategoryHierarchy</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResCategory1_CategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EcoResCategory1_Name name="EcoResCategory1_Name">EcoResCategory1_Name</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResCategory1_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EcoResCategoryHierarchy1_Name name="EcoResCategoryHierarchy1_Name">EcoResCategoryHierarchy1_Name</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResCategoryHierarchy1_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AxRecId name="AxRecId">AxRecId</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AxRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResCategoryRelationshipId name="BackingTable_EcoResCategoryRelationshipId">BackingTable_EcoResCategoryRelationshipId</a>

First included in: Retail/RetailEcoResCategoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResCategoryRelationshipId attribute are listed below.</summary>

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
