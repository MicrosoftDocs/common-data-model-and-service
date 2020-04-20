---
title: PdsCommodityQuantityMarginTemplateEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# PdsCommodityQuantityMarginTemplateEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CommodityPricingTemplateId](#CommodityPricingTemplateId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[MarginAccountCode](#MarginAccountCode)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[MarginAccountRelation](#MarginAccountRelation)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[PriceCustomerGroupCode](#PriceCustomerGroupCode)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[MarginItemCode](#MarginItemCode)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[MarginItemRelation](#MarginItemRelation)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ProductGroupId](#ProductGroupId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[OrderQuantity](#OrderQuantity)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[FromQuantity](#FromQuantity)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ToQuantity](#ToQuantity)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[CostMultiplier](#CostMultiplier)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[MarginAmount](#MarginAmount)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[MarginPercentage](#MarginPercentage)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ShippingSiteId](#ShippingSiteId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ShippingWarehouseId](#ShippingWarehouseId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ShippingWarehouseLocationId](#ShippingWarehouseLocationId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[BackingTable_PdsComdPricingTemplateLineRelationshipId](#BackingTable_PdsComdPricingTemplateLineRelationshipId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PdsCommodityQuantityMarginTemplateEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity</a>|

### <a href=#CommodityPricingTemplateId name="CommodityPricingTemplateId">CommodityPricingTemplateId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommodityPricingTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginAccountCode name="MarginAccountCode">MarginAccountCode</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginAccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginAccountRelation name="MarginAccountRelation">MarginAccountRelation</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginAccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceCustomerGroupCode name="PriceCustomerGroupCode">PriceCustomerGroupCode</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginItemCode name="MarginItemCode">MarginItemCode</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginItemRelation name="MarginItemRelation">MarginItemRelation</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductGroupId name="ProductGroupId">ProductGroupId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderQuantity name="OrderQuantity">OrderQuantity</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromQuantity name="FromQuantity">FromQuantity</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToQuantity name="ToQuantity">ToQuantity</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostMultiplier name="CostMultiplier">CostMultiplier</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostMultiplier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginAmount name="MarginAmount">MarginAmount</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginPercentage name="MarginPercentage">MarginPercentage</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingSiteId name="ShippingSiteId">ShippingSiteId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingWarehouseId name="ShippingWarehouseId">ShippingWarehouseId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingWarehouseLocationId name="ShippingWarehouseLocationId">ShippingWarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PdsComdPricingTemplateLineRelationshipId name="BackingTable_PdsComdPricingTemplateLineRelationshipId">BackingTable_PdsComdPricingTemplateLineRelationshipId</a>

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/PdsCommodityQuantityMarginTemplateEntity (this entity)  

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
