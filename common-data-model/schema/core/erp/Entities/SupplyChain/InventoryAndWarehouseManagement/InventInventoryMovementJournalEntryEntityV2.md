---
title: InventInventoryMovementJournalEntryEntityV2 - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# InventInventoryMovementJournalEntryEntityV2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2.cdm.json" target="_blank">GitHub</a>.  

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
|[CostAmount](#CostAmount)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[FixedCostCharges](#FixedCostCharges)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[UnitCost](#UnitCost)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[ItemNumber](#ItemNumber)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[OffsetMainAccountId](#OffsetMainAccountId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[CatchWeightQuantity](#CatchWeightQuantity)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[UnitCostQuantity](#UnitCostQuantity)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[InventoryQuantity](#InventoryQuantity)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[TransactionDate](#TransactionDate)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[OffsetMainAccountIdDisplayValue](#OffsetMainAccountIdDisplayValue)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[ProductColorId](#ProductColorId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[InventoryWarehouseId](#InventoryWarehouseId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[InventorySiteId](#InventorySiteId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[ProductSizeId](#ProductSizeId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[ProductStyleId](#ProductStyleId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[LicensePlateNumber](#LicensePlateNumber)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[WarehouseLocationId](#WarehouseLocationId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[JournalNameId](#JournalNameId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[LineNumber](#LineNumber)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[JournalNumber](#JournalNumber)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[JournalHeaderVoucherDraw](#JournalHeaderVoucherDraw)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[JournalHeaderOffsetMainAccountId](#JournalHeaderOffsetMainAccountId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[JournalHeaderJournalType](#JournalHeaderJournalType)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[JournalHeaderWorker](#JournalHeaderWorker)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[InventoryGtdId](#InventoryGtdId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[InventoryProfileId](#InventoryProfileId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[Relationship_OffsetMainAccountIdCombinationRelationshipId](#Relationship_OffsetMainAccountIdCombinationRelationshipId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[Relationship_InventoryMovementJournalHeaderRelationshipId](#Relationship_InventoryMovementJournalHeaderRelationshipId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[BackingTable_InventJournalTransRelationshipId](#BackingTable_InventJournalTransRelationshipId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryMovementJournalEntryEntityV2.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2</a>|

### <a href=#CostAmount name="CostAmount">CostAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedCostCharges name="FixedCostCharges">FixedCostCharges</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedCostCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCost name="UnitCost">UnitCost</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#OffsetMainAccountId name="OffsetMainAccountId">OffsetMainAccountId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightQuantity name="CatchWeightQuantity">CatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCostQuantity name="UnitCostQuantity">UnitCostQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCostQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryQuantity name="InventoryQuantity">InventoryQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetMainAccountIdDisplayValue name="OffsetMainAccountIdDisplayValue">OffsetMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#InventoryWarehouseId name="InventoryWarehouseId">InventoryWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#InventorySiteId name="InventorySiteId">InventorySiteId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#LicensePlateNumber name="LicensePlateNumber">LicensePlateNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#WarehouseLocationId name="WarehouseLocationId">WarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalHeaderVoucherDraw name="JournalHeaderVoucherDraw">JournalHeaderVoucherDraw</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalHeaderVoucherDraw attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalHeaderOffsetMainAccountId name="JournalHeaderOffsetMainAccountId">JournalHeaderOffsetMainAccountId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalHeaderOffsetMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalHeaderJournalType name="JournalHeaderJournalType">JournalHeaderJournalType</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalHeaderJournalType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalHeaderWorker name="JournalHeaderWorker">JournalHeaderWorker</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalHeaderWorker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryGtdId name="InventoryGtdId">InventoryGtdId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OffsetMainAccountIdCombinationRelationshipId name="Relationship_OffsetMainAccountIdCombinationRelationshipId">Relationship_OffsetMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventoryMovementJournalHeaderRelationshipId name="Relationship_InventoryMovementJournalHeaderRelationshipId">Relationship_InventoryMovementJournalHeaderRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryMovementJournalHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventJournalTransRelationshipId name="BackingTable_InventJournalTransRelationshipId">BackingTable_InventJournalTransRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventJournalTrans.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/WorksheetLine/InventJournalTrans.cdm.json/InventJournalTrans</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryMovementJournalEntryEntityV2 (this entity)  

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
