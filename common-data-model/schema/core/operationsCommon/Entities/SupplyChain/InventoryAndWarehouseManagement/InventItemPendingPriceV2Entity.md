---
title: InventItemPendingPriceV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Pending item prices V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pending item prices V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FromDate](#FromDate)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[FixedPriceCharges](#FixedPriceCharges)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[Price](#Price)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[IsPriceIncludingCharges](#IsPriceIncludingCharges)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[PriceChargesQuantity](#PriceChargesQuantity)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[PriceType](#PriceType)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[PriceQuantity](#PriceQuantity)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[ProductUnitSymbol](#ProductUnitSymbol)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[CostingVersionId](#CostingVersionId)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[PriceSiteId](#PriceSiteId)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[BackingTable_InventItemPriceSimRelationshipId](#BackingTable_InventItemPriceSimRelationshipId)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventItemPendingPriceV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity</a>|

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

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

### <a href=#FixedPriceCharges name="FixedPriceCharges">FixedPriceCharges</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Price name="Price">Price</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Price attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPriceIncludingCharges name="IsPriceIncludingCharges">IsPriceIncludingCharges</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPriceIncludingCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceChargesQuantity name="PriceChargesQuantity">PriceChargesQuantity</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceChargesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceType name="PriceType">PriceType</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceQuantity name="PriceQuantity">PriceQuantity</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductUnitSymbol name="ProductUnitSymbol">ProductUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostingVersionId name="CostingVersionId">CostingVersionId</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostingVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceSiteId name="PriceSiteId">PriceSiteId</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

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

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventItemPriceSimRelationshipId name="BackingTable_InventItemPriceSimRelationshipId">BackingTable_InventItemPriceSimRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventItemPriceSimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Worksheet/InventItemPriceSim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Worksheet/InventItemPriceSim.cdm.json/InventItemPriceSim</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Worksheet/InventItemPriceSim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemPendingPriceV2Entity (this entity)  

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
