---
title: InventPackingMaterialAllocationLineV2Entity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Packing material allocation lines V2 in InventoryAndWarehouseManagement(InventPackingMaterialAllocationLineV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packing material allocation lines V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PackingUnitRecID](#PackingUnitRecID)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[PackingUnitWeight](#PackingUnitWeight)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[PackingMaterialCode](#PackingMaterialCode)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[PackingMaterialGroupId](#PackingMaterialGroupId)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[PackingUnitSymbol](#PackingUnitSymbol)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[BackingTable_InventPackagingUnitMaterialRelationshipId](#BackingTable_InventPackagingUnitMaterialRelationshipId)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventPackingMaterialAllocationLineV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity</a>|

### <a href=#PackingUnitRecID name="PackingUnitRecID">PackingUnitRecID</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingUnitRecID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingUnitWeight name="PackingUnitWeight">PackingUnitWeight</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingUnitWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingMaterialCode name="PackingMaterialCode">PackingMaterialCode</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingMaterialCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

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

### <a href=#PackingMaterialGroupId name="PackingMaterialGroupId">PackingMaterialGroupId</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingMaterialGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingUnitSymbol name="PackingUnitSymbol">PackingUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventPackagingUnitMaterialRelationshipId name="BackingTable_InventPackagingUnitMaterialRelationshipId">BackingTable_InventPackagingUnitMaterialRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventPackagingUnitMaterialRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventPackagingUnitMaterial.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventPackagingUnitMaterial.cdm.json/InventPackagingUnitMaterial</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventPackagingUnitMaterial.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventPackingMaterialAllocationLineV2Entity (this entity)  

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
