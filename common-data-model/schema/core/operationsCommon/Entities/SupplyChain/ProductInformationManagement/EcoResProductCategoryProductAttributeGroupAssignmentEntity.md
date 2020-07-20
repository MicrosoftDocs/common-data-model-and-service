---
title: EcoResProductCategoryProductAttributeGroupAssignmentEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Product category product attribute group assignments in ProductInformationManagement(EcoResProductCategoryProductAttributeGroupAssignmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product category product attribute group assignments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[EcoResCategory_CategoryHierarchy](#EcoResCategory_CategoryHierarchy)||<a href="EcoResProductCategoryProductAttributeGroupAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity</a>|
|[ProductCategoryHierarchyName](#ProductCategoryHierarchyName)||<a href="EcoResProductCategoryProductAttributeGroupAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity</a>|
|[Category](#Category)||<a href="EcoResProductCategoryProductAttributeGroupAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity</a>|
|[ProductCategoryName](#ProductCategoryName)||<a href="EcoResProductCategoryProductAttributeGroupAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity</a>|
|[AttributeGroup](#AttributeGroup)||<a href="EcoResProductCategoryProductAttributeGroupAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity</a>|
|[ProductAttributeGroupName](#ProductAttributeGroupName)||<a href="EcoResProductCategoryProductAttributeGroupAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity</a>|
|[RetailChannelNavigationAttributeGroupType](#RetailChannelNavigationAttributeGroupType)||<a href="EcoResProductCategoryProductAttributeGroupAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity</a>|
|[ProductAttributeGroupDisplayOrder](#ProductAttributeGroupDisplayOrder)||<a href="EcoResProductCategoryProductAttributeGroupAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity</a>|
|[BackingTable_EcoResCategoryAttributeGroupRelationshipId](#BackingTable_EcoResCategoryAttributeGroupRelationshipId)||<a href="EcoResProductCategoryProductAttributeGroupAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity</a>|

### <a href=#EcoResCategory_CategoryHierarchy name="EcoResCategory_CategoryHierarchy">EcoResCategory_CategoryHierarchy</a>

First included in: ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResCategory_CategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCategoryHierarchyName name="ProductCategoryHierarchyName">ProductCategoryHierarchyName</a>

First included in: ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity (this entity)  

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

### <a href=#ProductCategoryName name="ProductCategoryName">ProductCategoryName</a>

First included in: ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeGroup name="AttributeGroup">AttributeGroup</a>

First included in: ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAttributeGroupName name="ProductAttributeGroupName">ProductAttributeGroupName</a>

First included in: ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAttributeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelNavigationAttributeGroupType name="RetailChannelNavigationAttributeGroupType">RetailChannelNavigationAttributeGroupType</a>

First included in: ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelNavigationAttributeGroupType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAttributeGroupDisplayOrder name="ProductAttributeGroupDisplayOrder">ProductAttributeGroupDisplayOrder</a>

First included in: ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAttributeGroupDisplayOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResCategoryAttributeGroupRelationshipId name="BackingTable_EcoResCategoryAttributeGroupRelationshipId">BackingTable_EcoResCategoryAttributeGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductCategoryProductAttributeGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResCategoryAttributeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryAttributeGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryAttributeGroup.cdm.json/EcoResCategoryAttributeGroup</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryAttributeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
