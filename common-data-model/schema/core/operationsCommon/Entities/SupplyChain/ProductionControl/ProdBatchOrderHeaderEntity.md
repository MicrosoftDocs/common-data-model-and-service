---
title: ProdBatchOrderHeaderEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Batch orders in ProductionControl(ProdBatchOrderHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdBatchOrderHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch orders</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AreRouteJobsGenerated](#AreRouteJobsGenerated)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[AutoReservationMode](#AutoReservationMode)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BatchOrderLedgerPostingRule](#BatchOrderLedgerPostingRule)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BatchOrderLevel](#BatchOrderLevel)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BatchOrderName](#BatchOrderName)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BatchOrderNumber](#BatchOrderNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BatchOrderPriority](#BatchOrderPriority)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BatchOrderProfitSettingMethod](#BatchOrderProfitSettingMethod)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BatchOrderStatus](#BatchOrderStatus)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BatchOrderRemainderStatus](#BatchOrderRemainderStatus)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BatchSizeCatchWeightQuantity](#BatchSizeCatchWeightQuantity)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ConsumptionDensityConversionFactor](#ConsumptionDensityConversionFactor)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ConsumptionDepthConversionFactor](#ConsumptionDepthConversionFactor)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ConsumptionHeightConversionFactor](#ConsumptionHeightConversionFactor)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ConsumptionWidthConversionFactor](#ConsumptionWidthConversionFactor)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ConsolidatedBatchOrderNumber](#ConsolidatedBatchOrderNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DeliveryDate](#DeliveryDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DeliveryTime](#DeliveryTime)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandBatchOrderLineInventoryLotId](#DemandBatchOrderLineInventoryLotId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandBatchOrderLineNumber](#DemandBatchOrderLineNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandBatchOrderHeaderInventoryLotId](#DemandBatchOrderHeaderInventoryLotId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandBatchOrderNumber](#DemandBatchOrderNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandInventoryJournalLineInventoryLotId](#DemandInventoryJournalLineInventoryLotId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandInventoryJournalNumber](#DemandInventoryJournalNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandSalesOrderLineInventoryLotId](#DemandSalesOrderLineInventoryLotId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandSalesOrderNumber](#DemandSalesOrderNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandTransferOrderLineReceivingInventoryLotId](#DemandTransferOrderLineReceivingInventoryLotId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[DemandTransferOrderNumber](#DemandTransferOrderNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[EndedDate](#EndedDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[EstimatedCatchWeightQuantity](#EstimatedCatchWeightQuantity)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[EstimatedDate](#EstimatedDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[EstimatedQuantity](#EstimatedQuantity)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[GanttChartColorNumber](#GanttChartColorNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[InventoryLotId](#InventoryLotId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[IsBatchOrderRouteOperationValid](#IsBatchOrderRouteOperationValid)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[IsBatchOrderSchedulingLocked](#IsBatchOrderSchedulingLocked)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[IsBulkOrder](#IsBulkOrder)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[IsCoByProductVariationAllowed](#IsCoByProductVariationAllowed)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[IsReworkBatchOrder](#IsReworkBatchOrder)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[IsTotalCostAllocationEnabled](#IsTotalCostAllocationEnabled)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[LastSchedulingDate](#LastSchedulingDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[LastSchedulingDateDirection](#LastSchedulingDateDirection)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[LastSchedulingTime](#LastSchedulingTime)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[LicensePlateNumber](#LicensePlateNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ParentBatchOrderNumber](#ParentBatchOrderNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[PlannedReceiptWarehouseId](#PlannedReceiptWarehouseId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[PlannedReceiptWarehouseLocationId](#PlannedReceiptWarehouseLocationId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ProductionGroupId](#ProductionGroupId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ProductionPoolId](#ProductionPoolId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ProductionSiteId](#ProductionSiteId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ReleasedDate](#ReleasedDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[RemainingReportAsFinishedCatchWeightQuantity](#RemainingReportAsFinishedCatchWeightQuantity)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[RemainingReportAsFinishedQuantity](#RemainingReportAsFinishedQuantity)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ReportedAsFinishedDate](#ReportedAsFinishedDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ScheduledCatchWeightQuantity](#ScheduledCatchWeightQuantity)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ScheduledDate](#ScheduledDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ScheduledEndDate](#ScheduledEndDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ScheduledEndTime](#ScheduledEndTime)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ScheduledStartTime](#ScheduledStartTime)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ScheduledStartDate](#ScheduledStartDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[ScheduledQuantity](#ScheduledQuantity)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SchedulingMethod](#SchedulingMethod)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SkipCreateBatchOrderFormulaLines](#SkipCreateBatchOrderFormulaLines)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SkipCreateBatchOrderRouteOperations](#SkipCreateBatchOrderRouteOperations)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SourceFormulaVersionValidityDate](#SourceFormulaVersionValidityDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SourceFormulaId](#SourceFormulaId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SourceMasterPlanId](#SourceMasterPlanId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SourcePlannedOrderNumber](#SourcePlannedOrderNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SourceRouteId](#SourceRouteId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[StartedCatchWeightQuantity](#StartedCatchWeightQuantity)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[StartedDate](#StartedDate)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[StartedQuantity](#StartedQuantity)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SubcontractingPurchaseOrderNumber](#SubcontractingPurchaseOrderNumber)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[SubcontractingPurchaseOrderLineInventoryLotId](#SubcontractingPurchaseOrderLineInventoryLotId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[WarehouseReleaseReservationRequirementRule](#WarehouseReleaseReservationRequirementRule)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[WorkingTimeSchedulingPropertyId](#WorkingTimeSchedulingPropertyId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[YieldPercentage](#YieldPercentage)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[BackingTable_ProdTableRelationshipId](#BackingTable_ProdTableRelationshipId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdBatchOrderHeaderEntity.md" target="_blank">ProductionControl/ProdBatchOrderHeaderEntity</a>|

### <a href=#AreRouteJobsGenerated name="AreRouteJobsGenerated">AreRouteJobsGenerated</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreRouteJobsGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoReservationMode name="AutoReservationMode">AutoReservationMode</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoReservationMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderLedgerPostingRule name="BatchOrderLedgerPostingRule">BatchOrderLedgerPostingRule</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderLedgerPostingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderLevel name="BatchOrderLevel">BatchOrderLevel</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Production level</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production level</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderName name="BatchOrderName">BatchOrderName</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderNumber name="BatchOrderNumber">BatchOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Batch number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderPriority name="BatchOrderPriority">BatchOrderPriority</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderProfitSettingMethod name="BatchOrderProfitSettingMethod">BatchOrderProfitSettingMethod</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderProfitSettingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderStatus name="BatchOrderStatus">BatchOrderStatus</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderRemainderStatus name="BatchOrderRemainderStatus">BatchOrderRemainderStatus</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#BatchSizeCatchWeightQuantity name="BatchSizeCatchWeightQuantity">BatchSizeCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchSizeCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionDensityConversionFactor name="ConsumptionDensityConversionFactor">ConsumptionDensityConversionFactor</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionDensityConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionDepthConversionFactor name="ConsumptionDepthConversionFactor">ConsumptionDepthConversionFactor</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionDepthConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionHeightConversionFactor name="ConsumptionHeightConversionFactor">ConsumptionHeightConversionFactor</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionHeightConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionWidthConversionFactor name="ConsumptionWidthConversionFactor">ConsumptionWidthConversionFactor</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionWidthConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsolidatedBatchOrderNumber name="ConsolidatedBatchOrderNumber">ConsolidatedBatchOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidatedBatchOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDate name="DeliveryDate">DeliveryDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTime name="DeliveryTime">DeliveryTime</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandBatchOrderLineInventoryLotId name="DemandBatchOrderLineInventoryLotId">DemandBatchOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for demand batch order line</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandBatchOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for demand batch order line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandBatchOrderLineNumber name="DemandBatchOrderLineNumber">DemandBatchOrderLineNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand batch order line number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandBatchOrderLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand batch order line number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandBatchOrderHeaderInventoryLotId name="DemandBatchOrderHeaderInventoryLotId">DemandBatchOrderHeaderInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for demand batch order</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandBatchOrderHeaderInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for demand batch order</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandBatchOrderNumber name="DemandBatchOrderNumber">DemandBatchOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand batch order number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandBatchOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand batch order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandInventoryJournalLineInventoryLotId name="DemandInventoryJournalLineInventoryLotId">DemandInventoryJournalLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lot ID for demand inventory journal line</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandInventoryJournalLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lot ID for demand inventory journal line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandInventoryJournalNumber name="DemandInventoryJournalNumber">DemandInventoryJournalNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand inventory journal number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandInventoryJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand inventory journal number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandSalesOrderLineInventoryLotId name="DemandSalesOrderLineInventoryLotId">DemandSalesOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for demand sales order line</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSalesOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for demand sales order line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandSalesOrderNumber name="DemandSalesOrderNumber">DemandSalesOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand sales order number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand sales order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandTransferOrderLineReceivingInventoryLotId name="DemandTransferOrderLineReceivingInventoryLotId">DemandTransferOrderLineReceivingInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for demand transfer order line receiving</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandTransferOrderLineReceivingInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for demand transfer order line receiving</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandTransferOrderNumber name="DemandTransferOrderNumber">DemandTransferOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand transfer order number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandTransferOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand transfer order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndedDate name="EndedDate">EndedDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#EstimatedCatchWeightQuantity name="EstimatedCatchWeightQuantity">EstimatedCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#EstimatedDate name="EstimatedDate">EstimatedDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedQuantity name="EstimatedQuantity">EstimatedQuantity</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GanttChartColorNumber name="GanttChartColorNumber">GanttChartColorNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GanttChartColorNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryLotId name="InventoryLotId">InventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#InventoryOwnerId name="InventoryOwnerId">InventoryOwnerId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#IsBatchOrderRouteOperationValid name="IsBatchOrderRouteOperationValid">IsBatchOrderRouteOperationValid</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchOrderRouteOperationValid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchOrderSchedulingLocked name="IsBatchOrderSchedulingLocked">IsBatchOrderSchedulingLocked</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchOrderSchedulingLocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBulkOrder name="IsBulkOrder">IsBulkOrder</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBulkOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCoByProductVariationAllowed name="IsCoByProductVariationAllowed">IsCoByProductVariationAllowed</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCoByProductVariationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReworkBatchOrder name="IsReworkBatchOrder">IsReworkBatchOrder</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReworkBatchOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTotalCostAllocationEnabled name="IsTotalCostAllocationEnabled">IsTotalCostAllocationEnabled</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTotalCostAllocationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#LastSchedulingDate name="LastSchedulingDate">LastSchedulingDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastSchedulingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastSchedulingDateDirection name="LastSchedulingDateDirection">LastSchedulingDateDirection</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastSchedulingDateDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastSchedulingTime name="LastSchedulingTime">LastSchedulingTime</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastSchedulingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicensePlateNumber name="LicensePlateNumber">LicensePlateNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicensePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentBatchOrderNumber name="ParentBatchOrderNumber">ParentBatchOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent batch order number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentBatchOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Parent batch order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedReceiptWarehouseId name="PlannedReceiptWarehouseId">PlannedReceiptWarehouseId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedReceiptWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedReceiptWarehouseLocationId name="PlannedReceiptWarehouseLocationId">PlannedReceiptWarehouseLocationId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedReceiptWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionGroupId name="ProductionGroupId">ProductionGroupId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionPoolId name="ProductionPoolId">ProductionPoolId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionSiteId name="ProductionSiteId">ProductionSiteId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#ReleasedDate name="ReleasedDate">ReleasedDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Released date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleasedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Released date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingReportAsFinishedCatchWeightQuantity name="RemainingReportAsFinishedCatchWeightQuantity">RemainingReportAsFinishedCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingReportAsFinishedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingReportAsFinishedQuantity name="RemainingReportAsFinishedQuantity">RemainingReportAsFinishedQuantity</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining report as finished quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingReportAsFinishedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remaining report as finished quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedAsFinishedDate name="ReportedAsFinishedDate">ReportedAsFinishedDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reported as finished date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedAsFinishedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reported as finished date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledCatchWeightQuantity name="ScheduledCatchWeightQuantity">ScheduledCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledDate name="ScheduledDate">ScheduledDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scheduled date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledEndDate name="ScheduledEndDate">ScheduledEndDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledEndTime name="ScheduledEndTime">ScheduledEndTime</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledEndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledStartTime name="ScheduledStartTime">ScheduledStartTime</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledStartDate name="ScheduledStartDate">ScheduledStartDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledQuantity name="ScheduledQuantity">ScheduledQuantity</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scheduled quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SchedulingMethod name="SchedulingMethod">SchedulingMethod</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedulingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipCreateBatchOrderFormulaLines name="SkipCreateBatchOrderFormulaLines">SkipCreateBatchOrderFormulaLines</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Skip create formula lines</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipCreateBatchOrderFormulaLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Skip create formula lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipCreateBatchOrderRouteOperations name="SkipCreateBatchOrderRouteOperations">SkipCreateBatchOrderRouteOperations</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Skip create route operations</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipCreateBatchOrderRouteOperations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Skip create route operations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceFormulaVersionValidityDate name="SourceFormulaVersionValidityDate">SourceFormulaVersionValidityDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Formula date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceFormulaVersionValidityDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Formula date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceFormulaId name="SourceFormulaId">SourceFormulaId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Formula Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceFormulaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Formula Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceMasterPlanId name="SourceMasterPlanId">SourceMasterPlanId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned order number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourcePlannedOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planned order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceRouteId name="SourceRouteId">SourceRouteId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRouteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedCatchWeightQuantity name="StartedCatchWeightQuantity">StartedCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#StartedDate name="StartedDate">StartedDate</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Started date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Started date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedQuantity name="StartedQuantity">StartedQuantity</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Started quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Started quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingPurchaseOrderNumber name="SubcontractingPurchaseOrderNumber">SubcontractingPurchaseOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subcontracting purchase order number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractingPurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subcontracting purchase order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingPurchaseOrderLineInventoryLotId name="SubcontractingPurchaseOrderLineInventoryLotId">SubcontractingPurchaseOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for subcontracting purchase order line</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractingPurchaseOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for subcontracting purchase order line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseReleaseReservationRequirementRule name="WarehouseReleaseReservationRequirementRule">WarehouseReleaseReservationRequirementRule</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseReleaseReservationRequirementRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkingTimeSchedulingPropertyId name="WorkingTimeSchedulingPropertyId">WorkingTimeSchedulingPropertyId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkingTimeSchedulingPropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YieldPercentage name="YieldPercentage">YieldPercentage</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YieldPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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

### <a href=#BackingTable_ProdTableRelationshipId name="BackingTable_ProdTableRelationshipId">BackingTable_ProdTableRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProdTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetHeader/ProdTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetHeader/ProdTable.cdm.json/ProdTable</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetHeader/ProdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderHeaderEntity (this entity)  

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
