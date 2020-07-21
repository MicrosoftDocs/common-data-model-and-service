---
title: ProdBatchOrderCoProductEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Batch order co-products in ProductionControl(ProdBatchOrderCoProductEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdBatchOrderCoProductEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch order co-products</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BatchOrderRemainderStatus](#BatchOrderRemainderStatus)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[EstimatedDate](#EstimatedDate)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[CoProductQuantity](#CoProductQuantity)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[CoProductQuantityDenominator](#CoProductQuantityDenominator)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[CostAllocationMethod](#CostAllocationMethod)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[CostAllocationPercentage](#CostAllocationPercentage)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[IsFullyConsumed](#IsFullyConsumed)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ReportedAsFinishedDate](#ReportedAsFinishedDate)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[InventDimId](#InventDimId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ReferenceInventoryLotId](#ReferenceInventoryLotId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ReferenceType](#ReferenceType)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[InventoryLotId](#InventoryLotId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[EstimatedCatchWeightQuantity](#EstimatedCatchWeightQuantity)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[StartedCatchWeightQuantity](#StartedCatchWeightQuantity)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[CatchWeightQuantity](#CatchWeightQuantity)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[RemainingCatchWeightQuantity](#RemainingCatchWeightQuantity)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[CoProductBatchOrderNumber](#CoProductBatchOrderNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ProductionType](#ProductionType)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[EstimatedCoProductQuantity](#EstimatedCoProductQuantity)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[StartedCoProductQuantity](#StartedCoProductQuantity)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[EndedDate](#EndedDate)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[RemainingCoProductQuantity](#RemainingCoProductQuantity)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[SourceMasterPlanId](#SourceMasterPlanId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[SourcePlannedOrderNumber](#SourcePlannedOrderNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[RoundingUpMethod](#RoundingUpMethod)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[RoundingUpMultiplesCoProductQuantity](#RoundingUpMultiplesCoProductQuantity)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[StartedDate](#StartedDate)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DemandInventoryJournalLineInventoryLotId](#DemandInventoryJournalLineInventoryLotId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DemandInventoryJournalNumber](#DemandInventoryJournalNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DemandProductionOrderLineNumber](#DemandProductionOrderLineNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DemandProductionOrderHeaderInventoryLotId](#DemandProductionOrderHeaderInventoryLotId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DemandProductionOrderNumber](#DemandProductionOrderNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DemandSalesOrderLineInventoryLotId](#DemandSalesOrderLineInventoryLotId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DemandSalesOrderNumber](#DemandSalesOrderNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DemandTransferOrderLineReceivingInventoryLotId](#DemandTransferOrderLineReceivingInventoryLotId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DemandTransferOrderNumber](#DemandTransferOrderNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[SubcontractingPurchaseOrderNumber](#SubcontractingPurchaseOrderNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[SubcontractingPurchaseOrderLineInventoryLotId](#SubcontractingPurchaseOrderLineInventoryLotId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[BatchOrderNumber](#BatchOrderNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ConsumptionSiteId](#ConsumptionSiteId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ConsumptionWarehouseId](#ConsumptionWarehouseId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[Relationship_ProductionOrderHeaderRelationshipId](#Relationship_ProductionOrderHeaderRelationshipId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[BackingTable_PmfProdCoByRelationshipId](#BackingTable_PmfProdCoByRelationshipId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdBatchOrderCoProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderCoProductEntity</a>|

### <a href=#BatchOrderRemainderStatus name="BatchOrderRemainderStatus">BatchOrderRemainderStatus</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderRemainderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedDate name="EstimatedDate">EstimatedDate</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoProductQuantity name="CoProductQuantity">CoProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoProductQuantityDenominator name="CoProductQuantityDenominator">CoProductQuantityDenominator</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoProductQuantityDenominator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAllocationMethod name="CostAllocationMethod">CostAllocationMethod</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAllocationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAllocationPercentage name="CostAllocationPercentage">CostAllocationPercentage</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAllocationPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFullyConsumed name="IsFullyConsumed">IsFullyConsumed</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFullyConsumed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedAsFinishedDate name="ReportedAsFinishedDate">ReportedAsFinishedDate</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedAsFinishedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceInventoryLotId name="ReferenceInventoryLotId">ReferenceInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceType name="ReferenceType">ReferenceType</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryLotId name="InventoryLotId">InventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

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

### <a href=#EstimatedCatchWeightQuantity name="EstimatedCatchWeightQuantity">EstimatedCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedCatchWeightQuantity name="StartedCatchWeightQuantity">StartedCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightQuantity name="CatchWeightQuantity">CatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingCatchWeightQuantity name="RemainingCatchWeightQuantity">RemainingCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoProductBatchOrderNumber name="CoProductBatchOrderNumber">CoProductBatchOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoProductBatchOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionType name="ProductionType">ProductionType</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCoProductQuantity name="EstimatedCoProductQuantity">EstimatedCoProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCoProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedCoProductQuantity name="StartedCoProductQuantity">StartedCoProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedCoProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndedDate name="EndedDate">EndedDate</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingCoProductQuantity name="RemainingCoProductQuantity">RemainingCoProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingCoProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceMasterPlanId name="SourceMasterPlanId">SourceMasterPlanId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceMasterPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourcePlannedOrderNumber name="SourcePlannedOrderNumber">SourcePlannedOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourcePlannedOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingUpMethod name="RoundingUpMethod">RoundingUpMethod</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingUpMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingUpMultiplesCoProductQuantity name="RoundingUpMultiplesCoProductQuantity">RoundingUpMultiplesCoProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingUpMultiplesCoProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedDate name="StartedDate">StartedDate</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandInventoryJournalLineInventoryLotId name="DemandInventoryJournalLineInventoryLotId">DemandInventoryJournalLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandInventoryJournalLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandInventoryJournalNumber name="DemandInventoryJournalNumber">DemandInventoryJournalNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandInventoryJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderLineNumber name="DemandProductionOrderLineNumber">DemandProductionOrderLineNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderHeaderInventoryLotId name="DemandProductionOrderHeaderInventoryLotId">DemandProductionOrderHeaderInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderHeaderInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderNumber name="DemandProductionOrderNumber">DemandProductionOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandSalesOrderLineInventoryLotId name="DemandSalesOrderLineInventoryLotId">DemandSalesOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSalesOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandSalesOrderNumber name="DemandSalesOrderNumber">DemandSalesOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandTransferOrderLineReceivingInventoryLotId name="DemandTransferOrderLineReceivingInventoryLotId">DemandTransferOrderLineReceivingInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandTransferOrderLineReceivingInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandTransferOrderNumber name="DemandTransferOrderNumber">DemandTransferOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandTransferOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingPurchaseOrderNumber name="SubcontractingPurchaseOrderNumber">SubcontractingPurchaseOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractingPurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingPurchaseOrderLineInventoryLotId name="SubcontractingPurchaseOrderLineInventoryLotId">SubcontractingPurchaseOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractingPurchaseOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderNumber name="BatchOrderNumber">BatchOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionSiteId name="ConsumptionSiteId">ConsumptionSiteId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionWarehouseId name="ConsumptionWarehouseId">ConsumptionWarehouseId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOwnerId name="InventoryOwnerId">InventoryOwnerId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryOwnerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryStatusId name="InventoryStatusId">InventoryStatusId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

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

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

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

### <a href=#Relationship_ProductionOrderHeaderRelationshipId name="Relationship_ProductionOrderHeaderRelationshipId">Relationship_ProductionOrderHeaderRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionOrderHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PmfProdCoByRelationshipId name="BackingTable_PmfProdCoByRelationshipId">BackingTable_PmfProdCoByRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PmfProdCoByRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/PmfProdCoBy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/PmfProdCoBy.cdm.json/PmfProdCoBy</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/PmfProdCoBy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderCoProductEntity (this entity)  

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
