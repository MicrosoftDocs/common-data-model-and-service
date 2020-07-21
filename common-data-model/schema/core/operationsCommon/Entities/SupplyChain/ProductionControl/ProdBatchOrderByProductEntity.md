---
title: ProdBatchOrderByProductEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Batch order by-products  in ProductionControl(ProdBatchOrderByProductEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdBatchOrderByProductEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch order by-products </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BatchOrderRemainderStatus](#BatchOrderRemainderStatus)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[BurdenAllocationMethod](#BurdenAllocationMethod)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[EstimatedDate](#EstimatedDate)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ByProductQuantity](#ByProductQuantity)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ByProductQuantityDenominator](#ByProductQuantityDenominator)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[IsFullyConsumed](#IsFullyConsumed)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ReportedAsFinishedDate](#ReportedAsFinishedDate)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[InventDimId](#InventDimId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ReferenceInventoryLotId](#ReferenceInventoryLotId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ReferenceType](#ReferenceType)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[InventoryLotId](#InventoryLotId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[BurdenAllocationAmount](#BurdenAllocationAmount)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[EstimatedCatchWeightQuantity](#EstimatedCatchWeightQuantity)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[StartedCatchWeightQuantity](#StartedCatchWeightQuantity)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[CatchWeightQuantity](#CatchWeightQuantity)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[RemainingCatchWeightQuantity](#RemainingCatchWeightQuantity)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ByProductBatchOrderNumber](#ByProductBatchOrderNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ProductionType](#ProductionType)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[EstimatedByProductQuantity](#EstimatedByProductQuantity)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[StartedByProductQuantity](#StartedByProductQuantity)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[EndedDate](#EndedDate)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[RemainingByProductQuantity](#RemainingByProductQuantity)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[SourceMasterPlanId](#SourceMasterPlanId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[SourcePlannedOrderNumber](#SourcePlannedOrderNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[RoundingUpMethod](#RoundingUpMethod)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[RoundingUpMultiplesByProductQuantity](#RoundingUpMultiplesByProductQuantity)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[StartedDate](#StartedDate)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DemandInventoryJournalLineInventoryLotId](#DemandInventoryJournalLineInventoryLotId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DemandInventoryJournalNumber](#DemandInventoryJournalNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DemandProductionOrderLineNumber](#DemandProductionOrderLineNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DemandProductionOrderHeaderInventoryLotId](#DemandProductionOrderHeaderInventoryLotId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DemandProductionOrderNumber](#DemandProductionOrderNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DemandSalesOrderLineInventoryLotId](#DemandSalesOrderLineInventoryLotId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DemandSalesOrderNumber](#DemandSalesOrderNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DemandTransferOrderLineReceivingInventoryLotId](#DemandTransferOrderLineReceivingInventoryLotId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DemandTransferOrderNumber](#DemandTransferOrderNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[SubcontractingPurchaseOrderNumber](#SubcontractingPurchaseOrderNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[SubcontractingPurchaseOrderLineInventoryLotId](#SubcontractingPurchaseOrderLineInventoryLotId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[BatchOrderNumber](#BatchOrderNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ConsumptionSiteId](#ConsumptionSiteId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ConsumptionWarehouseId](#ConsumptionWarehouseId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[Relationship_ProductionOrderHeaderRelationshipId](#Relationship_ProductionOrderHeaderRelationshipId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[BackingTable_PmfProdCoByRelationshipId](#BackingTable_PmfProdCoByRelationshipId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdBatchOrderByProductEntity.md" target="_blank">ProductionControl/ProdBatchOrderByProductEntity</a>|

### <a href=#BatchOrderRemainderStatus name="BatchOrderRemainderStatus">BatchOrderRemainderStatus</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

### <a href=#BurdenAllocationMethod name="BurdenAllocationMethod">BurdenAllocationMethod</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BurdenAllocationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedDate name="EstimatedDate">EstimatedDate</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

### <a href=#ByProductQuantity name="ByProductQuantity">ByProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ByProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ByProductQuantityDenominator name="ByProductQuantityDenominator">ByProductQuantityDenominator</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ByProductQuantityDenominator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

### <a href=#BurdenAllocationAmount name="BurdenAllocationAmount">BurdenAllocationAmount</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BurdenAllocationAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCatchWeightQuantity name="EstimatedCatchWeightQuantity">EstimatedCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

### <a href=#ByProductBatchOrderNumber name="ByProductBatchOrderNumber">ByProductBatchOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ByProductBatchOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionType name="ProductionType">ProductionType</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

### <a href=#EstimatedByProductQuantity name="EstimatedByProductQuantity">EstimatedByProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedByProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedByProductQuantity name="StartedByProductQuantity">StartedByProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedByProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndedDate name="EndedDate">EndedDate</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

### <a href=#RemainingByProductQuantity name="RemainingByProductQuantity">RemainingByProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingByProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceMasterPlanId name="SourceMasterPlanId">SourceMasterPlanId</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

### <a href=#RoundingUpMultiplesByProductQuantity name="RoundingUpMultiplesByProductQuantity">RoundingUpMultiplesByProductQuantity</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingUpMultiplesByProductQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedDate name="StartedDate">StartedDate</a>

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderByProductEntity (this entity)  

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
