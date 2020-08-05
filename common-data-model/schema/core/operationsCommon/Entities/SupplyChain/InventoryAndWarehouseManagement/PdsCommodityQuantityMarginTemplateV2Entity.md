---
title: PdsCommodityQuantityMarginTemplateV2Entity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Commodity quantity and margin templates V2 in InventoryAndWarehouseManagement(PdsCommodityQuantityMarginTemplateV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commodity quantity and margin templates V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CommodityPricingTemplateId](#CommodityPricingTemplateId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[MarginAccountCode](#MarginAccountCode)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[MarginAccountRelation](#MarginAccountRelation)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[PriceCustomerGroupCode](#PriceCustomerGroupCode)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[MarginItemCode](#MarginItemCode)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[MarginItemRelation](#MarginItemRelation)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ProductGroupId](#ProductGroupId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[OrderQuantity](#OrderQuantity)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[FromQuantity](#FromQuantity)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ToQuantity](#ToQuantity)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[CostMultiplier](#CostMultiplier)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[MarginAmount](#MarginAmount)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[MarginPercentage](#MarginPercentage)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ShippingSiteId](#ShippingSiteId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ShippingWarehouseId](#ShippingWarehouseId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ShippingWarehouseLocationId](#ShippingWarehouseLocationId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[BackingTable_PdsComdPricingTemplateLineRelationshipId](#BackingTable_PdsComdPricingTemplateLineRelationshipId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PdsCommodityQuantityMarginTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity</a>|

### <a href=#CommodityPricingTemplateId name="CommodityPricingTemplateId">CommodityPricingTemplateId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommodityPricingTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginAccountCode name="MarginAccountCode">MarginAccountCode</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginAccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginAccountRelation name="MarginAccountRelation">MarginAccountRelation</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginAccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceCustomerGroupCode name="PriceCustomerGroupCode">PriceCustomerGroupCode</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginItemCode name="MarginItemCode">MarginItemCode</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginItemRelation name="MarginItemRelation">MarginItemRelation</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

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

### <a href=#ProductGroupId name="ProductGroupId">ProductGroupId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderQuantity name="OrderQuantity">OrderQuantity</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromQuantity name="FromQuantity">FromQuantity</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToQuantity name="ToQuantity">ToQuantity</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostMultiplier name="CostMultiplier">CostMultiplier</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostMultiplier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginAmount name="MarginAmount">MarginAmount</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginPercentage name="MarginPercentage">MarginPercentage</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingSiteId name="ShippingSiteId">ShippingSiteId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingWarehouseId name="ShippingWarehouseId">ShippingWarehouseId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingWarehouseLocationId name="ShippingWarehouseLocationId">ShippingWarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

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

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PdsComdPricingTemplateLineRelationshipId name="BackingTable_PdsComdPricingTemplateLineRelationshipId">BackingTable_PdsComdPricingTemplateLineRelationshipId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsComdPricingTemplateLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/PdsComdPricingTemplateLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/PdsComdPricingTemplateLine.cdm.json/PdsComdPricingTemplateLine</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/PdsComdPricingTemplateLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateV2Entity (this entity)  

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
