---
title: ProdProductionOrderBillOfMaterialsLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Production bill of materials lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production bill of materials lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AutoReservationMode](#AutoReservationMode)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[BOMLineQuantity](#BOMLineQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[BOMLineQuantityDenominator](#BOMLineQuantityDenominator)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[BOMLineUnitSymbol](#BOMLineUnitSymbol)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ConstantScrapBOMLineQuantity](#ConstantScrapBOMLineQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ReleasedBOMLineQuantity](#ReleasedBOMLineQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ConsumptionCalculationConstant](#ConsumptionCalculationConstant)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ConsumptionCalculationMethod](#ConsumptionCalculationMethod)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ConsumptionSiteId](#ConsumptionSiteId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ConsumptionType](#ConsumptionType)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ConsumptionWarehouseId](#ConsumptionWarehouseId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandInventoryJournalLineInventoryLotId](#DemandInventoryJournalLineInventoryLotId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandInventoryJournalNumber](#DemandInventoryJournalNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandProductionOrderLineInventoryLotId](#DemandProductionOrderLineInventoryLotId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandProductionOrderLineNumber](#DemandProductionOrderLineNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandProductionOrderHeaderInventoryLotId](#DemandProductionOrderHeaderInventoryLotId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandProductionOrderNumber](#DemandProductionOrderNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandSalesOrderLineInventoryLotId](#DemandSalesOrderLineInventoryLotId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandSalesOrderNumber](#DemandSalesOrderNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandTransferOrderLineReceivingInventoryLotId](#DemandTransferOrderLineReceivingInventoryLotId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[DemandTransferOrderNumber](#DemandTransferOrderNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[FlushingPrinciple](#FlushingPrinciple)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[EstimatedInventoryQuantity](#EstimatedInventoryQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[EstimatedBOMLineQuantity](#EstimatedBOMLineQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[InventoryLotId](#InventoryLotId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[IsConstantConsumptionReleased](#IsConstantConsumptionReleased)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[IsConsumedAtOperationComplete](#IsConsumedAtOperationComplete)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[IsFullyConsumed](#IsFullyConsumed)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[IsResourceConsumptionUsed](#IsResourceConsumptionUsed)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[LineProductionOrderNumber](#LineProductionOrderNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[LineRemainderStatus](#LineRemainderStatus)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[LineType](#LineType)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[PhysicalProductDensity](#PhysicalProductDensity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[PhysicalProductDepth](#PhysicalProductDepth)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[PhysicalProductHeight](#PhysicalProductHeight)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[PhysicalProductWidth](#PhysicalProductWidth)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[PositionNumber](#PositionNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[ProductionOrderNumber](#ProductionOrderNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[RawMaterialScheduledConsumptionDate](#RawMaterialScheduledConsumptionDate)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[RawMaterialScheduledConsumptionTime](#RawMaterialScheduledConsumptionTime)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[RemainingBOMLineQuantity](#RemainingBOMLineQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[RemainingInventoryQuantity](#RemainingInventoryQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[RouteOperationNumber](#RouteOperationNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[RoundingUpMethod](#RoundingUpMethod)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[RoundingUpMultiplesBOMLineQuantity](#RoundingUpMultiplesBOMLineQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[SourceBOMId](#SourceBOMId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[SourceMasterPlanId](#SourceMasterPlanId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[SourcePlannedOrderNumber](#SourcePlannedOrderNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[StartedInventoryQuantity](#StartedInventoryQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[StartedBOMLineQuantity](#StartedBOMLineQuantity)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[SubBOMId](#SubBOMId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[SubcontractingPurchaseOrderNumber](#SubcontractingPurchaseOrderNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[SubcontractingPurchaseOrderLineInventoryLotId](#SubcontractingPurchaseOrderLineInventoryLotId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[SubcontractingVendorAccountNumber](#SubcontractingVendorAccountNumber)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[SubRouteOperationId](#SubRouteOperationId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[VariableScrapPercentage](#VariableScrapPercentage)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[WillCostCalculationIncludeLine](#WillCostCalculationIncludeLine)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[Relationship_ProductionOrderHeaderRelationshipId](#Relationship_ProductionOrderHeaderRelationshipId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[BackingTable_ProdBOMRelationshipId](#BackingTable_ProdBOMRelationshipId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdProductionOrderBillOfMaterialsLineEntity.md" target="_blank">ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity</a>|

### <a href=#AutoReservationMode name="AutoReservationMode">AutoReservationMode</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#BOMLineQuantity name="BOMLineQuantity">BOMLineQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity in BOM line unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity in BOM line unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMLineQuantityDenominator name="BOMLineQuantityDenominator">BOMLineQuantityDenominator</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMLineQuantityDenominator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMLineUnitSymbol name="BOMLineUnitSymbol">BOMLineUnitSymbol</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>BOM line unit symbol</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMLineUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>BOM line unit symbol</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstantScrapBOMLineQuantity name="ConstantScrapBOMLineQuantity">ConstantScrapBOMLineQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Constant scrap quantity in BOM line unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstantScrapBOMLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Constant scrap quantity in BOM line unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleasedBOMLineQuantity name="ReleasedBOMLineQuantity">ReleasedBOMLineQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Released quantity in BOM line unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleasedBOMLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Released quantity in BOM line unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionCalculationConstant name="ConsumptionCalculationConstant">ConsumptionCalculationConstant</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#ConsumptionCalculationMethod name="ConsumptionCalculationMethod">ConsumptionCalculationMethod</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#ConsumptionSiteId name="ConsumptionSiteId">ConsumptionSiteId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#ConsumptionType name="ConsumptionType">ConsumptionType</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#ConsumptionWarehouseId name="ConsumptionWarehouseId">ConsumptionWarehouseId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#DemandInventoryJournalLineInventoryLotId name="DemandInventoryJournalLineInventoryLotId">DemandInventoryJournalLineInventoryLotId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lot ID for demand inventory journal line</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandInventoryJournalLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lot ID for demand inventory journal line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandInventoryJournalNumber name="DemandInventoryJournalNumber">DemandInventoryJournalNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand inventory journal number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandInventoryJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand inventory journal number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderLineInventoryLotId name="DemandProductionOrderLineInventoryLotId">DemandProductionOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for demand production order line</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for demand production order line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderLineNumber name="DemandProductionOrderLineNumber">DemandProductionOrderLineNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand production order line number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand production order line number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderHeaderInventoryLotId name="DemandProductionOrderHeaderInventoryLotId">DemandProductionOrderHeaderInventoryLotId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for demand production order line</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderHeaderInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for demand production order line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandProductionOrderNumber name="DemandProductionOrderNumber">DemandProductionOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand production order number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand production order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandSalesOrderLineInventoryLotId name="DemandSalesOrderLineInventoryLotId">DemandSalesOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for demand sales order line</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSalesOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for demand sales order line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandSalesOrderNumber name="DemandSalesOrderNumber">DemandSalesOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand sales order number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand sales order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandTransferOrderLineReceivingInventoryLotId name="DemandTransferOrderLineReceivingInventoryLotId">DemandTransferOrderLineReceivingInventoryLotId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for demand transfer order line receiving</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandTransferOrderLineReceivingInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for demand transfer order line receiving</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandTransferOrderNumber name="DemandTransferOrderNumber">DemandTransferOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand transfer order number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandTransferOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand transfer order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlushingPrinciple name="FlushingPrinciple">FlushingPrinciple</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#EstimatedInventoryQuantity name="EstimatedInventoryQuantity">EstimatedInventoryQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated quantity in inventory unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated quantity in inventory unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedBOMLineQuantity name="EstimatedBOMLineQuantity">EstimatedBOMLineQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated quantity in BOM line unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedBOMLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated quantity in BOM line unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryLotId name="InventoryLotId">InventoryLotId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#InventoryOwnerId name="InventoryOwnerId">InventoryOwnerId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#InventoryStatusId name="InventoryStatusId">InventoryStatusId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#IsConstantConsumptionReleased name="IsConstantConsumptionReleased">IsConstantConsumptionReleased</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#IsConsumedAtOperationComplete name="IsConsumedAtOperationComplete">IsConsumedAtOperationComplete</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#IsFullyConsumed name="IsFullyConsumed">IsFullyConsumed</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#IsResourceConsumptionUsed name="IsResourceConsumptionUsed">IsResourceConsumptionUsed</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#LineProductionOrderNumber name="LineProductionOrderNumber">LineProductionOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineRemainderStatus name="LineRemainderStatus">LineRemainderStatus</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#LineType name="LineType">LineType</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#PhysicalProductDensity name="PhysicalProductDensity">PhysicalProductDensity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#PhysicalProductHeight name="PhysicalProductHeight">PhysicalProductHeight</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#PhysicalProductWidth name="PhysicalProductWidth">PhysicalProductWidth</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#PositionNumber name="PositionNumber">PositionNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#ProductionOrderNumber name="ProductionOrderNumber">ProductionOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RawMaterialScheduledConsumptionDate name="RawMaterialScheduledConsumptionDate">RawMaterialScheduledConsumptionDate</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#RemainingBOMLineQuantity name="RemainingBOMLineQuantity">RemainingBOMLineQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining quantity in BOM line unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingBOMLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remaining quantity in BOM line unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingInventoryQuantity name="RemainingInventoryQuantity">RemainingInventoryQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining quantity in inventory unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remaining quantity in inventory unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationNumber name="RouteOperationNumber">RouteOperationNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#RoundingUpMethod name="RoundingUpMethod">RoundingUpMethod</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#RoundingUpMultiplesBOMLineQuantity name="RoundingUpMultiplesBOMLineQuantity">RoundingUpMultiplesBOMLineQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rounding up multiples quantity in BOM line unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingUpMultiplesBOMLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rounding up multiples quantity in BOM line unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceBOMId name="SourceBOMId">SourceBOMId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceBOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceMasterPlanId name="SourceMasterPlanId">SourceMasterPlanId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned order number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourcePlannedOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planned order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedInventoryQuantity name="StartedInventoryQuantity">StartedInventoryQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Started quantity in inventory unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Started quantity in inventory unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartedBOMLineQuantity name="StartedBOMLineQuantity">StartedBOMLineQuantity</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Started quantity in BOM line unit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartedBOMLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Started quantity in BOM line unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubBOMId name="SubBOMId">SubBOMId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubBOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingPurchaseOrderNumber name="SubcontractingPurchaseOrderNumber">SubcontractingPurchaseOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subcontracting purchase order number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractingPurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subcontracting purchase order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingPurchaseOrderLineInventoryLotId name="SubcontractingPurchaseOrderLineInventoryLotId">SubcontractingPurchaseOrderLineInventoryLotId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory lot ID for subcontracting purchase order line</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractingPurchaseOrderLineInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory lot ID for subcontracting purchase order line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubcontractingVendorAccountNumber name="SubcontractingVendorAccountNumber">SubcontractingVendorAccountNumber</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#SubRouteOperationId name="SubRouteOperationId">SubRouteOperationId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#VariableScrapPercentage name="VariableScrapPercentage">VariableScrapPercentage</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#WillCostCalculationIncludeLine name="WillCostCalculationIncludeLine">WillCostCalculationIncludeLine</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderBillOfMaterialsLineEntity (this entity)  

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
