---
title: InventInventoryAgingReportStorageEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Inventory aging

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory aging</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ExecutionTime](#ExecutionTime)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ExecutionName](#ExecutionName)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ProductGroupId](#ProductGroupId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ProductName](#ProductName)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[InventoryUnitSymbol](#InventoryUnitSymbol)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[OperationalSiteId](#OperationalSiteId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[WarehouseId](#WarehouseId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[WarehouseLocationId](#WarehouseLocationId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[InventoryGtdId](#InventoryGtdId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[InventoryProfileId](#InventoryProfileId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[LicensePlateNumber](#LicensePlateNumber)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[OnHandQuantity](#OnHandQuantity)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[OnHandAmount](#OnHandAmount)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[InventoryValueQuantity](#InventoryValueQuantity)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[InventoryValueAmount](#InventoryValueAmount)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AverageUnitCost](#AverageUnitCost)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod1Quantity](#AgingPeriod1Quantity)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod1Amount](#AgingPeriod1Amount)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod2Quantity](#AgingPeriod2Quantity)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod2Amount](#AgingPeriod2Amount)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod3Quantity](#AgingPeriod3Quantity)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod3Amount](#AgingPeriod3Amount)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod4Quantity](#AgingPeriod4Quantity)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod4Amount](#AgingPeriod4Amount)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod5Quantity](#AgingPeriod5Quantity)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[AgingPeriod5Amount](#AgingPeriod5Amount)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[BackingTable_InventAgingTmpRelationshipId](#BackingTable_InventAgingTmpRelationshipId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryAgingReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity</a>|

### <a href=#ExecutionTime name="ExecutionTime">ExecutionTime</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionName name="ExecutionName">ExecutionName</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductGroupId name="ProductGroupId">ProductGroupId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

### <a href=#InventoryUnitSymbol name="InventoryUnitSymbol">InventoryUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

### <a href=#OperationalSiteId name="OperationalSiteId">OperationalSiteId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

### <a href=#WarehouseLocationId name="WarehouseLocationId">WarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

### <a href=#InventoryGtdId name="InventoryGtdId">InventoryGtdId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryGtdId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOwnerId name="InventoryOwnerId">InventoryOwnerId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryOwnerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryProfileId name="InventoryProfileId">InventoryProfileId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryStatusId name="InventoryStatusId">InventoryStatusId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

### <a href=#LicensePlateNumber name="LicensePlateNumber">LicensePlateNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicensePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHandQuantity name="OnHandQuantity">OnHandQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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

### <a href=#OnHandAmount name="OnHandAmount">OnHandAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHandAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryValueQuantity name="InventoryValueQuantity">InventoryValueQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryValueQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryValueAmount name="InventoryValueAmount">InventoryValueAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryValueAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AverageUnitCost name="AverageUnitCost">AverageUnitCost</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AverageUnitCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod1Quantity name="AgingPeriod1Quantity">AgingPeriod1Quantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod1Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod1Amount name="AgingPeriod1Amount">AgingPeriod1Amount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod1Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod2Quantity name="AgingPeriod2Quantity">AgingPeriod2Quantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod2Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod2Amount name="AgingPeriod2Amount">AgingPeriod2Amount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod2Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod3Quantity name="AgingPeriod3Quantity">AgingPeriod3Quantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod3Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod3Amount name="AgingPeriod3Amount">AgingPeriod3Amount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod3Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod4Quantity name="AgingPeriod4Quantity">AgingPeriod4Quantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod4Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod4Amount name="AgingPeriod4Amount">AgingPeriod4Amount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod4Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod5Quantity name="AgingPeriod5Quantity">AgingPeriod5Quantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod5Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod5Amount name="AgingPeriod5Amount">AgingPeriod5Amount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod5Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventAgingTmpRelationshipId name="BackingTable_InventAgingTmpRelationshipId">BackingTable_InventAgingTmpRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventAgingTmpRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Miscellaneous/InventAgingTmp.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/InventAgingTmp.cdm.json/InventAgingTmp</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Miscellaneous/InventAgingTmp.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryAgingReportStorageEntity (this entity)  

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
