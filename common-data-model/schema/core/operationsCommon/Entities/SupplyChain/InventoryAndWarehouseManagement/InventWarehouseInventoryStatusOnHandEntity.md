---
title: InventWarehouseInventoryStatusOnHandEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# InventWarehouseInventoryStatusOnHandEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ItemNumber](#ItemNumber)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[ProductName](#ProductName)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[InventorySiteId](#InventorySiteId)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[InventoryWarehouseId](#InventoryWarehouseId)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[OnHandQuantity](#OnHandQuantity)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[ReservedOnHandQuantityMapped](#ReservedOnHandQuantityMapped)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[ReservedOnHandQuantity](#ReservedOnHandQuantity)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[AvailableOnHandQuantityMapped](#AvailableOnHandQuantityMapped)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[AvailableOnHandQuantity](#AvailableOnHandQuantity)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[OrderedQuantityMapped](#OrderedQuantityMapped)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[OrderedQuantity](#OrderedQuantity)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[ReservedOrderedQuantityMapped](#ReservedOrderedQuantityMapped)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[ReservedOrderedQuantity](#ReservedOrderedQuantity)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[AvailableOrderedQuantityMapped](#AvailableOrderedQuantityMapped)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[AvailableOrderedQuantity](#AvailableOrderedQuantity)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[OnOrderQuantity](#OnOrderQuantity)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[TotalAvailableQuantity](#TotalAvailableQuantity)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[AreWarehouseManagementProcessesUsed](#AreWarehouseManagementProcessesUsed)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventWarehouseInventoryStatusOnHandEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity</a>|

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

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

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

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

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

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

### <a href=#InventorySiteId name="InventorySiteId">InventorySiteId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryWarehouseId name="InventoryWarehouseId">InventoryWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryStatusId name="InventoryStatusId">InventoryStatusId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHandQuantity name="OnHandQuantity">OnHandQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHandQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservedOnHandQuantityMapped name="ReservedOnHandQuantityMapped">ReservedOnHandQuantityMapped</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservedOnHandQuantityMapped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservedOnHandQuantity name="ReservedOnHandQuantity">ReservedOnHandQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservedOnHandQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailableOnHandQuantityMapped name="AvailableOnHandQuantityMapped">AvailableOnHandQuantityMapped</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailableOnHandQuantityMapped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailableOnHandQuantity name="AvailableOnHandQuantity">AvailableOnHandQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailableOnHandQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderedQuantityMapped name="OrderedQuantityMapped">OrderedQuantityMapped</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedQuantityMapped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderedQuantity name="OrderedQuantity">OrderedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservedOrderedQuantityMapped name="ReservedOrderedQuantityMapped">ReservedOrderedQuantityMapped</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservedOrderedQuantityMapped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservedOrderedQuantity name="ReservedOrderedQuantity">ReservedOrderedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservedOrderedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailableOrderedQuantityMapped name="AvailableOrderedQuantityMapped">AvailableOrderedQuantityMapped</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailableOrderedQuantityMapped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailableOrderedQuantity name="AvailableOrderedQuantity">AvailableOrderedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailableOrderedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnOrderQuantity name="OnOrderQuantity">OnOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalAvailableQuantity name="TotalAvailableQuantity">TotalAvailableQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAvailableQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreWarehouseManagementProcessesUsed name="AreWarehouseManagementProcessesUsed">AreWarehouseManagementProcessesUsed</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreWarehouseManagementProcessesUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseInventoryStatusOnHandEntity (this entity)  

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
