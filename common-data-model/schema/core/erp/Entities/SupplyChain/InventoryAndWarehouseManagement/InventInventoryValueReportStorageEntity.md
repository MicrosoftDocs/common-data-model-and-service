---
title: InventInventoryValueReportStorageEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# InventInventoryValueReportStorageEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[COGSFinancialAmount](#COGSFinancialAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[COGSFinancialQuantity](#COGSFinancialQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[DeferredCOGSPhysicalNonPostedAmount](#DeferredCOGSPhysicalNonPostedAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[DeferredCOGSPhysicalNonPostedQuantity](#DeferredCOGSPhysicalNonPostedQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[DeferredCOGSPhysicalPostedAmount](#DeferredCOGSPhysicalPostedAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[DeferredCOGSPhysicalPostedQuantity](#DeferredCOGSPhysicalPostedQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[DeferredCOGSAmount](#DeferredCOGSAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[DeferredCOGSQuantity](#DeferredCOGSQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[WarehouseId](#WarehouseId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryFinancialAmount](#InventoryFinancialAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryFinancialQuantity](#InventoryFinancialQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryPhysicalNonPostedAmount](#InventoryPhysicalNonPostedAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryPhysicalNonPostedQuantity](#InventoryPhysicalNonPostedQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryPhysicalPostedAmount](#InventoryPhysicalPostedAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryPhysicalPostedQuantity](#InventoryPhysicalPostedQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryAmount](#InventoryAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryQuantity](#InventoryQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryProfileId](#InventoryProfileId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[OperationalSiteId](#OperationalSiteId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[InventoryLotId](#InventoryLotId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[LicensePlateNumber](#LicensePlateNumber)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[LineType](#LineType)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[PLFinancialAmount](#PLFinancialAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[PLFinancialQuantity](#PLFinancialQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[LineReferenceNumber](#LineReferenceNumber)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[LineReferenceType](#LineReferenceType)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[CostResourceGroupId](#CostResourceGroupId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[CostResourceNumber](#CostResourceNumber)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[CostResourceType](#CostResourceType)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[TransactionTime](#TransactionTime)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[VoucherNumber](#VoucherNumber)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[WIPPhysicalNonPostedAmount](#WIPPhysicalNonPostedAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[WIPPhysicalNonPostedQuantity](#WIPPhysicalNonPostedQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[WIPPhysicalPostedAmount](#WIPPhysicalPostedAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[WIPPhysicalPostedQuantity](#WIPPhysicalPostedQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[WIPAmount](#WIPAmount)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[WIPQuantity](#WIPQuantity)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[AverageUnitCost](#AverageUnitCost)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[WarehouseLocationId](#WarehouseLocationId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[ExecutionName](#ExecutionName)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[ExecutionTime](#ExecutionTime)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[BackingTable_InventValueReportTmpLineRelationshipId](#BackingTable_InventValueReportTmpLineRelationshipId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryValueReportStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity</a>|

### <a href=#COGSFinancialAmount name="COGSFinancialAmount">COGSFinancialAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the COGSFinancialAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#COGSFinancialQuantity name="COGSFinancialQuantity">COGSFinancialQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the COGSFinancialQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#DeferredCOGSPhysicalNonPostedAmount name="DeferredCOGSPhysicalNonPostedAmount">DeferredCOGSPhysicalNonPostedAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredCOGSPhysicalNonPostedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredCOGSPhysicalNonPostedQuantity name="DeferredCOGSPhysicalNonPostedQuantity">DeferredCOGSPhysicalNonPostedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredCOGSPhysicalNonPostedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredCOGSPhysicalPostedAmount name="DeferredCOGSPhysicalPostedAmount">DeferredCOGSPhysicalPostedAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredCOGSPhysicalPostedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredCOGSPhysicalPostedQuantity name="DeferredCOGSPhysicalPostedQuantity">DeferredCOGSPhysicalPostedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredCOGSPhysicalPostedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredCOGSAmount name="DeferredCOGSAmount">DeferredCOGSAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredCOGSAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredCOGSQuantity name="DeferredCOGSQuantity">DeferredCOGSQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredCOGSQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#InventoryFinancialAmount name="InventoryFinancialAmount">InventoryFinancialAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryFinancialAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryFinancialQuantity name="InventoryFinancialQuantity">InventoryFinancialQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryFinancialQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryPhysicalNonPostedAmount name="InventoryPhysicalNonPostedAmount">InventoryPhysicalNonPostedAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPhysicalNonPostedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryPhysicalNonPostedQuantity name="InventoryPhysicalNonPostedQuantity">InventoryPhysicalNonPostedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPhysicalNonPostedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryPhysicalPostedAmount name="InventoryPhysicalPostedAmount">InventoryPhysicalPostedAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPhysicalPostedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryPhysicalPostedQuantity name="InventoryPhysicalPostedQuantity">InventoryPhysicalPostedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPhysicalPostedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryAmount name="InventoryAmount">InventoryAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryQuantity name="InventoryQuantity">InventoryQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOwnerId name="InventoryOwnerId">InventoryOwnerId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#OperationalSiteId name="OperationalSiteId">OperationalSiteId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#InventoryStatusId name="InventoryStatusId">InventoryStatusId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#InventoryLotId name="InventoryLotId">InventoryLotId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicensePlateNumber name="LicensePlateNumber">LicensePlateNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#LineType name="LineType">LineType</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLFinancialAmount name="PLFinancialAmount">PLFinancialAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLFinancialAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLFinancialQuantity name="PLFinancialQuantity">PLFinancialQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLFinancialQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineReferenceNumber name="LineReferenceNumber">LineReferenceNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineReferenceType name="LineReferenceType">LineReferenceType</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineReferenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostResourceGroupId name="CostResourceGroupId">CostResourceGroupId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostResourceNumber name="CostResourceNumber">CostResourceNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostResourceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostResourceType name="CostResourceType">CostResourceType</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostResourceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionTime name="TransactionTime">TransactionTime</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherNumber name="VoucherNumber">VoucherNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPPhysicalNonPostedAmount name="WIPPhysicalNonPostedAmount">WIPPhysicalNonPostedAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPPhysicalNonPostedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPPhysicalNonPostedQuantity name="WIPPhysicalNonPostedQuantity">WIPPhysicalNonPostedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPPhysicalNonPostedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPPhysicalPostedAmount name="WIPPhysicalPostedAmount">WIPPhysicalPostedAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPPhysicalPostedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPPhysicalPostedQuantity name="WIPPhysicalPostedQuantity">WIPPhysicalPostedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPPhysicalPostedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPAmount name="WIPAmount">WIPAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPQuantity name="WIPQuantity">WIPQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AverageUnitCost name="AverageUnitCost">AverageUnitCost</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#WarehouseLocationId name="WarehouseLocationId">WarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#ExecutionName name="ExecutionName">ExecutionName</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#ExecutionTime name="ExecutionTime">ExecutionTime</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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

### <a href=#BackingTable_InventValueReportTmpLineRelationshipId name="BackingTable_InventValueReportTmpLineRelationshipId">BackingTable_InventValueReportTmpLineRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventValueReportTmpLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Transaction/InventValueReportTmpLine.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Transaction/InventValueReportTmpLine.cdm.json/InventValueReportTmpLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Transaction/InventValueReportTmpLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportStorageEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
