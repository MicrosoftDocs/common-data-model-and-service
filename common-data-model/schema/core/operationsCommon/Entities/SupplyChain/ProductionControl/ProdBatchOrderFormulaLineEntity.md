---
title: ProdBatchOrderFormulaLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Batch order formula lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdBatchOrderFormulaLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch order formula lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WillCostCalculationIncludeLine](#WillCostCalculationIncludeLine)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ConsumptionCalculationConstant](#ConsumptionCalculationConstant)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[IsConstantConsumptionReleased](#IsConstantConsumptionReleased)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[PhysicalProductDensity](#PhysicalProductDensity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[PhysicalProductDepth](#PhysicalProductDepth)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[IsFullyConsumed](#IsFullyConsumed)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[IsConsumedAtOperationComplete](#IsConsumedAtOperationComplete)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ConsumptionCalculationMethod](#ConsumptionCalculationMethod)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[PhysicalProductHeight](#PhysicalProductHeight)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[InventoryLotId](#InventoryLotId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[SubFormulaId](#SubFormulaId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[SubRouteOperationId](#SubRouteOperationId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[RouteOperationNumber](#RouteOperationNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[EstimatedCatchWeightQuantity](#EstimatedCatchWeightQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[StartedCatchWeightQuantity](#StartedCatchWeightQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[CatchWeightQuantity](#CatchWeightQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ReleasedCatchWeightQuantity](#ReleasedCatchWeightQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[RemainingCatchWeightQuantity](#RemainingCatchWeightQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[IngredientType](#IngredientType)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[WillCoProductInheritBatchAttributes](#WillCoProductInheritBatchAttributes)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[WillCoProductInheritShelfLifeDates](#WillCoProductInheritShelfLifeDates)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[WillManufacturedItemInheritBatchAttributes](#WillManufacturedItemInheritBatchAttributes)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[WillManufacturedItemInheritShelfLifeDates](#WillManufacturedItemInheritShelfLifeDates)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[FormulaQuantityPercentage](#FormulaQuantityPercentage)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[IsFormulaLineQuantityPercentageControlled](#IsFormulaLineQuantityPercentageControlled)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[QuantityWithoutYield](#QuantityWithoutYield)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[IsFormulaLineQuantityScalable](#IsFormulaLineQuantityScalable)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[PositionNumber](#PositionNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[FlushingPrinciple](#FlushingPrinciple)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[LineBatchOrderNumber](#LineBatchOrderNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[LineType](#LineType)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[EstimatedFormulaLineQuantity](#EstimatedFormulaLineQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[StartedFormulaLineQuantity](#StartedFormulaLineQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[EstimatedInventoryQuantity](#EstimatedInventoryQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[StartedInventoryQuantity](#StartedInventoryQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[RawMaterialScheduledConsumptionDate](#RawMaterialScheduledConsumptionDate)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[RawMaterialScheduledConsumptionTime](#RawMaterialScheduledConsumptionTime)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ReleasedFormulaLineQuantity](#ReleasedFormulaLineQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[RemainingFormulaLineQuantity](#RemainingFormulaLineQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[RemainingInventoryQuantity](#RemainingInventoryQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[SourceMasterPlanId](#SourceMasterPlanId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[SourcePlannedOrderNumber](#SourcePlannedOrderNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[AutoReservationMode](#AutoReservationMode)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[RoundingUpMethod](#RoundingUpMethod)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[RoundingUpMultiplesFormulaLineQuantity](#RoundingUpMultiplesFormulaLineQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ConstantScrapFormulaLineQuantity](#ConstantScrapFormulaLineQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[VariableScrapPercentage](#VariableScrapPercentage)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[FormulaLineUnitSymbol](#FormulaLineUnitSymbol)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[SubcontractingVendorAccountNumber](#SubcontractingVendorAccountNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[PhysicalProductWidth](#PhysicalProductWidth)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[IsResourceConsumptionUsed](#IsResourceConsumptionUsed)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[BatchOrderNumber](#BatchOrderNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ConsumptionSiteId](#ConsumptionSiteId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ConsumptionWarehouseId](#ConsumptionWarehouseId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandTransferOrderNumber](#DemandTransferOrderNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandInventoryJournalLineInventoryLotId](#DemandInventoryJournalLineInventoryLotId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandInventoryJournalNumber](#DemandInventoryJournalNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandProductionOrderLineInventoryLotId](#DemandProductionOrderLineInventoryLotId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandProductionOrderLineNumber](#DemandProductionOrderLineNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandProductionOrderHeaderInventoryLotId](#DemandProductionOrderHeaderInventoryLotId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandProductionOrderNumber](#DemandProductionOrderNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandSalesOrderLineInventoryLotId](#DemandSalesOrderLineInventoryLotId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandSalesOrderNumber](#DemandSalesOrderNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[DemandTransferOrderLineReceivingInventoryLotId](#DemandTransferOrderLineReceivingInventoryLotId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[SubcontractingPurchaseOrderNumber](#SubcontractingPurchaseOrderNumber)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[SubcontractingPurchaseOrderLineInventoryLotId](#SubcontractingPurchaseOrderLineInventoryLotId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[LineRemainderStatus](#LineRemainderStatus)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[FormulaLineQuantity](#FormulaLineQuantity)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[ConsumptionType](#ConsumptionType)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[SourceFormulaId](#SourceFormulaId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[FormulaLineQuantityDenominator](#FormulaLineQuantityDenominator)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[InventDimId](#InventDimId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[Relationship_ProductionOrderHeaderRelationshipId](#Relationship_ProductionOrderHeaderRelationshipId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[BackingTable_ProdBOMRelationshipId](#BackingTable_ProdBOMRelationshipId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdBatchOrderFormulaLineEntity.md" target="_blank">ProductionControl/ProdBatchOrderFormulaLineEntity</a>|

### <a href=#WillCostCalculationIncludeLine name="WillCostCalculationIncludeLine">WillCostCalculationIncludeLine</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCostCalculationIncludeLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionCalculationConstant name="ConsumptionCalculationConstant">ConsumptionCalculationConstant</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionCalculationConstant attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsConstantConsumptionReleased name="IsConstantConsumptionReleased">IsConstantConsumptionReleased</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsConstantConsumptionReleased attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalProductDensity name="PhysicalProductDensity">PhysicalProductDensity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalProductDensity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalProductDepth name="PhysicalProductDepth">PhysicalProductDepth</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalProductDepth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFullyConsumed name="IsFullyConsumed">IsFullyConsumed</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFullyConsumed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsConsumedAtOperationComplete name="IsConsumedAtOperationComplete">IsConsumedAtOperationComplete</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsConsumedAtOperationComplete attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionCalculationMethod name="ConsumptionCalculationMethod">ConsumptionCalculationMethod</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalProductHeight name="PhysicalProductHeight">PhysicalProductHeight</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalProductHeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryLotId name="InventoryLotId">InventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#SubFormulaId name="SubFormulaId">SubFormulaId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubFormulaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#SubRouteOperationId name="SubRouteOperationId">SubRouteOperationId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubRouteOperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#RouteOperationNumber name="RouteOperationNumber">RouteOperationNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCatchWeightQuantity name="EstimatedCatchWeightQuantity">EstimatedCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedCatchWeightQuantity name="StartedCatchWeightQuantity">StartedCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightQuantity name="CatchWeightQuantity">CatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#ReleasedCatchWeightQuantity name="ReleasedCatchWeightQuantity">ReleasedCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleasedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingCatchWeightQuantity name="RemainingCatchWeightQuantity">RemainingCatchWeightQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IngredientType name="IngredientType">IngredientType</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IngredientType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCoProductInheritBatchAttributes name="WillCoProductInheritBatchAttributes">WillCoProductInheritBatchAttributes</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCoProductInheritBatchAttributes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCoProductInheritShelfLifeDates name="WillCoProductInheritShelfLifeDates">WillCoProductInheritShelfLifeDates</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCoProductInheritShelfLifeDates attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillManufacturedItemInheritBatchAttributes name="WillManufacturedItemInheritBatchAttributes">WillManufacturedItemInheritBatchAttributes</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillManufacturedItemInheritBatchAttributes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillManufacturedItemInheritShelfLifeDates name="WillManufacturedItemInheritShelfLifeDates">WillManufacturedItemInheritShelfLifeDates</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillManufacturedItemInheritShelfLifeDates attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaQuantityPercentage name="FormulaQuantityPercentage">FormulaQuantityPercentage</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaQuantityPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFormulaLineQuantityPercentageControlled name="IsFormulaLineQuantityPercentageControlled">IsFormulaLineQuantityPercentageControlled</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFormulaLineQuantityPercentageControlled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityWithoutYield name="QuantityWithoutYield">QuantityWithoutYield</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityWithoutYield attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFormulaLineQuantityScalable name="IsFormulaLineQuantityScalable">IsFormulaLineQuantityScalable</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFormulaLineQuantityScalable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionNumber name="PositionNumber">PositionNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlushingPrinciple name="FlushingPrinciple">FlushingPrinciple</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlushingPrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineBatchOrderNumber name="LineBatchOrderNumber">LineBatchOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineBatchOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#EstimatedFormulaLineQuantity name="EstimatedFormulaLineQuantity">EstimatedFormulaLineQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedFormulaLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedFormulaLineQuantity name="StartedFormulaLineQuantity">StartedFormulaLineQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedFormulaLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedInventoryQuantity name="EstimatedInventoryQuantity">EstimatedInventoryQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedInventoryQuantity name="StartedInventoryQuantity">StartedInventoryQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RawMaterialScheduledConsumptionDate name="RawMaterialScheduledConsumptionDate">RawMaterialScheduledConsumptionDate</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RawMaterialScheduledConsumptionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RawMaterialScheduledConsumptionTime name="RawMaterialScheduledConsumptionTime">RawMaterialScheduledConsumptionTime</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RawMaterialScheduledConsumptionTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleasedFormulaLineQuantity name="ReleasedFormulaLineQuantity">ReleasedFormulaLineQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleasedFormulaLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingFormulaLineQuantity name="RemainingFormulaLineQuantity">RemainingFormulaLineQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingFormulaLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingInventoryQuantity name="RemainingInventoryQuantity">RemainingInventoryQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceMasterPlanId name="SourceMasterPlanId">SourceMasterPlanId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceMasterPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourcePlannedOrderNumber name="SourcePlannedOrderNumber">SourcePlannedOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourcePlannedOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoReservationMode name="AutoReservationMode">AutoReservationMode</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoReservationMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingUpMethod name="RoundingUpMethod">RoundingUpMethod</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingUpMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingUpMultiplesFormulaLineQuantity name="RoundingUpMultiplesFormulaLineQuantity">RoundingUpMultiplesFormulaLineQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingUpMultiplesFormulaLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstantScrapFormulaLineQuantity name="ConstantScrapFormulaLineQuantity">ConstantScrapFormulaLineQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstantScrapFormulaLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariableScrapPercentage name="VariableScrapPercentage">VariableScrapPercentage</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariableScrapPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaLineUnitSymbol name="FormulaLineUnitSymbol">FormulaLineUnitSymbol</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaLineUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingVendorAccountNumber name="SubcontractingVendorAccountNumber">SubcontractingVendorAccountNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractingVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalProductWidth name="PhysicalProductWidth">PhysicalProductWidth</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalProductWidth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsResourceConsumptionUsed name="IsResourceConsumptionUsed">IsResourceConsumptionUsed</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsResourceConsumptionUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchOrderNumber name="BatchOrderNumber">BatchOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#ConsumptionSiteId name="ConsumptionSiteId">ConsumptionSiteId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionWarehouseId name="ConsumptionWarehouseId">ConsumptionWarehouseId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOwnerId name="InventoryOwnerId">InventoryOwnerId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#DemandTransferOrderNumber name="DemandTransferOrderNumber">DemandTransferOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandTransferOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandInventoryJournalLineInventoryLotId name="DemandInventoryJournalLineInventoryLotId">DemandInventoryJournalLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandInventoryJournalLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandInventoryJournalNumber name="DemandInventoryJournalNumber">DemandInventoryJournalNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandInventoryJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderLineInventoryLotId name="DemandProductionOrderLineInventoryLotId">DemandProductionOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderLineNumber name="DemandProductionOrderLineNumber">DemandProductionOrderLineNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderHeaderInventoryLotId name="DemandProductionOrderHeaderInventoryLotId">DemandProductionOrderHeaderInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderHeaderInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderNumber name="DemandProductionOrderNumber">DemandProductionOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandSalesOrderLineInventoryLotId name="DemandSalesOrderLineInventoryLotId">DemandSalesOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSalesOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandSalesOrderNumber name="DemandSalesOrderNumber">DemandSalesOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandTransferOrderLineReceivingInventoryLotId name="DemandTransferOrderLineReceivingInventoryLotId">DemandTransferOrderLineReceivingInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandTransferOrderLineReceivingInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingPurchaseOrderNumber name="SubcontractingPurchaseOrderNumber">SubcontractingPurchaseOrderNumber</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractingPurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingPurchaseOrderLineInventoryLotId name="SubcontractingPurchaseOrderLineInventoryLotId">SubcontractingPurchaseOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractingPurchaseOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineRemainderStatus name="LineRemainderStatus">LineRemainderStatus</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineRemainderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaLineQuantity name="FormulaLineQuantity">FormulaLineQuantity</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionType name="ConsumptionType">ConsumptionType</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceFormulaId name="SourceFormulaId">SourceFormulaId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceFormulaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaLineQuantityDenominator name="FormulaLineQuantityDenominator">FormulaLineQuantityDenominator</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaLineQuantityDenominator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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

### <a href=#BackingTable_ProdBOMRelationshipId name="BackingTable_ProdBOMRelationshipId">BackingTable_ProdBOMRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProdBOMRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/ProdBOM.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdBOM.cdm.json/ProdBOM</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/ProdBOM.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdBatchOrderFormulaLineEntity (this entity)  

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
