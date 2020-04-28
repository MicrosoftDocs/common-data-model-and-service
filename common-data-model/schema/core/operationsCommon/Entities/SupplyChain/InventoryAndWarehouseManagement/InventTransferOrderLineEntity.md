---
title: InventTransferOrderLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Transfer order lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventTransferOrderLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transfer order lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IntrastatCostAmount](#IntrastatCostAmount)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ATPDelayedDemandOffsetDays](#ATPDelayedDemandOffsetDays)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ATPDelayedSupplyOffsetDays](#ATPDelayedSupplyOffsetDays)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ATPBackwardDemandTimeFenceDays](#ATPBackwardDemandTimeFenceDays)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ATPBackwardSupplyTimeFenceDays](#ATPBackwardSupplyTimeFenceDays)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[IsATPIncludingPlannedOrders](#IsATPIncludingPlannedOrders)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ATPTimeFenceDays](#ATPTimeFenceDays)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[IsAutomaticallyReserved](#IsAutomaticallyReserved)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[TransferOrderPromisingMethod](#TransferOrderPromisingMethod)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[IntrastatSpecialMovementCode](#IntrastatSpecialMovementCode)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShippingInventoryLotId](#ShippingInventoryLotId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ReceivingInventoryLotId](#ReceivingInventoryLotId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ScrapInventoryLotId](#ScrapInventoryLotId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ReceivingTransitInventoryLotId](#ReceivingTransitInventoryLotId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShippingTransitInventoryLotId](#ShippingTransitInventoryLotId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[OriginCountryRegionId](#OriginCountryRegionId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[OriginCountyId](#OriginCountyId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[OriginStateId](#OriginStateId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[AllowedOverdeliveryPercentage](#AllowedOverdeliveryPercentage)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ReceivedCatchWeightQuantity](#ReceivedCatchWeightQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[RemainingReceivedCatchWeightQuantity](#RemainingReceivedCatchWeightQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[RemainingShippedCatchWeightQuantity](#RemainingShippedCatchWeightQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ScrappedCatchWeightQuantity](#ScrappedCatchWeightQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShippedCatchWeightQuantity](#ShippedCatchWeightQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[TransferCatchWeightQuantity](#TransferCatchWeightQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[OverrideFEFODateControl](#OverrideFEFODateControl)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[IntrastatPortId](#IntrastatPortId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ReceivedQuantity](#ReceivedQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[RemainingReceivedQuantity](#RemainingReceivedQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[RemainingShippedQuantity](#RemainingShippedQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ScrappedQuantity](#ScrappedQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShippedQuantity](#ShippedQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[TransferQuantity](#TransferQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[RequestedReceiptDate](#RequestedReceiptDate)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[LineStatus](#LineStatus)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[RequestedShippingDate](#RequestedShippingDate)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[IntrastatStatisticalValue](#IntrastatStatisticalValue)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[IntrastatStatisticsProcedureCode](#IntrastatStatisticsProcedureCode)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[IntrastatTransactionCode](#IntrastatTransactionCode)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[TransferOrderNumber](#TransferOrderNumber)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[IntrastatTransportModeCode](#IntrastatTransportModeCode)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[AllowedUnderdeliveryPercentage](#AllowedUnderdeliveryPercentage)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[InventoryUnitSymbol](#InventoryUnitSymbol)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShippingLedgerDimension](#ShippingLedgerDimension)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ReceivingLedgerDimension](#ReceivingLedgerDimension)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[IntrastatCommodityCode](#IntrastatCommodityCode)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShippingLedgerDimensionDisplayValue](#ShippingLedgerDimensionDisplayValue)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ReceivingLedgerDimensionDisplayValue](#ReceivingLedgerDimensionDisplayValue)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShippingWarehouseId](#ShippingWarehouseId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShippingSiteId](#ShippingSiteId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[OrderedInventoryStatusId](#OrderedInventoryStatusId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShippingWarehouseLocationId](#ShippingWarehouseLocationId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[WillProductReceivingCrossDockProducts](#WillProductReceivingCrossDockProducts)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ReceiveNowQuantity](#ReceiveNowQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShipNowQuantity](#ShipNowQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ReceiveNowCatchWeightQuantity](#ReceiveNowCatchWeightQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ShipNowCatchWeightQuantity](#ShipNowCatchWeightQuantity)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[AssessableValueTransactionCurrency](#AssessableValueTransactionCurrency)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[InventCostPriceCalculated](#InventCostPriceCalculated)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[InvntCostPrice](#InvntCostPrice)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[MaximumRetailPrice](#MaximumRetailPrice)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[NetAmount](#NetAmount)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[PriceType](#PriceType)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[Retention](#Retention)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[TaxGroup](#TaxGroup)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[UnitId](#UnitId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[UnitPrice](#UnitPrice)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[VATPriceType](#VATPriceType)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[VATRetentionCode](#VATRetentionCode)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[Relationship_DimensionDefaultShipFromDimensionSetRelationshipId](#Relationship_DimensionDefaultShipFromDimensionSetRelationshipId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[Relationship_DimensionDefaultShipToDimensionSetRelationshipId](#Relationship_DimensionDefaultShipToDimensionSetRelationshipId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[Relationship_InventTransferOrderHeaderRelationshipId](#Relationship_InventTransferOrderHeaderRelationshipId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[BackingTable_InventTransferLineRelationshipId](#BackingTable_InventTransferLineRelationshipId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventTransferOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderLineEntity</a>|

### <a href=#IntrastatCostAmount name="IntrastatCostAmount">IntrastatCostAmount</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatCostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATPDelayedDemandOffsetDays name="ATPDelayedDemandOffsetDays">ATPDelayedDemandOffsetDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPDelayedDemandOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATPDelayedSupplyOffsetDays name="ATPDelayedSupplyOffsetDays">ATPDelayedSupplyOffsetDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPDelayedSupplyOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATPBackwardDemandTimeFenceDays name="ATPBackwardDemandTimeFenceDays">ATPBackwardDemandTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPBackwardDemandTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATPBackwardSupplyTimeFenceDays name="ATPBackwardSupplyTimeFenceDays">ATPBackwardSupplyTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPBackwardSupplyTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsATPIncludingPlannedOrders name="IsATPIncludingPlannedOrders">IsATPIncludingPlannedOrders</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsATPIncludingPlannedOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATPTimeFenceDays name="ATPTimeFenceDays">ATPTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutomaticallyReserved name="IsAutomaticallyReserved">IsAutomaticallyReserved</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutomaticallyReserved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderPromisingMethod name="TransferOrderPromisingMethod">TransferOrderPromisingMethod</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderPromisingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatSpecialMovementCode name="IntrastatSpecialMovementCode">IntrastatSpecialMovementCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatSpecialMovementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingInventoryLotId name="ShippingInventoryLotId">ShippingInventoryLotId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingInventoryLotId name="ReceivingInventoryLotId">ReceivingInventoryLotId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScrapInventoryLotId name="ScrapInventoryLotId">ScrapInventoryLotId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScrapInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingTransitInventoryLotId name="ReceivingTransitInventoryLotId">ReceivingTransitInventoryLotId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingTransitInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingTransitInventoryLotId name="ShippingTransitInventoryLotId">ShippingTransitInventoryLotId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingTransitInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

### <a href=#OriginCountryRegionId name="OriginCountryRegionId">OriginCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginCountyId name="OriginCountyId">OriginCountyId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginStateId name="OriginStateId">OriginStateId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedOverdeliveryPercentage name="AllowedOverdeliveryPercentage">AllowedOverdeliveryPercentage</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedOverdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivedCatchWeightQuantity name="ReceivedCatchWeightQuantity">ReceivedCatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingReceivedCatchWeightQuantity name="RemainingReceivedCatchWeightQuantity">RemainingReceivedCatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingReceivedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingShippedCatchWeightQuantity name="RemainingShippedCatchWeightQuantity">RemainingShippedCatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingShippedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScrappedCatchWeightQuantity name="ScrappedCatchWeightQuantity">ScrappedCatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScrappedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippedCatchWeightQuantity name="ShippedCatchWeightQuantity">ShippedCatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferCatchWeightQuantity name="TransferCatchWeightQuantity">TransferCatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverrideFEFODateControl name="OverrideFEFODateControl">OverrideFEFODateControl</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideFEFODateControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatPortId name="IntrastatPortId">IntrastatPortId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatPortId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivedQuantity name="ReceivedQuantity">ReceivedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingReceivedQuantity name="RemainingReceivedQuantity">RemainingReceivedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingReceivedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingShippedQuantity name="RemainingShippedQuantity">RemainingShippedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingShippedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScrappedQuantity name="ScrappedQuantity">ScrappedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScrappedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippedQuantity name="ShippedQuantity">ShippedQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferQuantity name="TransferQuantity">TransferQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedReceiptDate name="RequestedReceiptDate">RequestedReceiptDate</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineStatus name="LineStatus">LineStatus</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShippingDate name="RequestedShippingDate">RequestedShippingDate</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatStatisticalValue name="IntrastatStatisticalValue">IntrastatStatisticalValue</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatStatisticalValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatStatisticsProcedureCode name="IntrastatStatisticsProcedureCode">IntrastatStatisticsProcedureCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatStatisticsProcedureCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransactionCode name="IntrastatTransactionCode">IntrastatTransactionCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderNumber name="TransferOrderNumber">TransferOrderNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransportModeCode name="IntrastatTransportModeCode">IntrastatTransportModeCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransportModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedUnderdeliveryPercentage name="AllowedUnderdeliveryPercentage">AllowedUnderdeliveryPercentage</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedUnderdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryUnitSymbol name="InventoryUnitSymbol">InventoryUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

### <a href=#ShippingLedgerDimension name="ShippingLedgerDimension">ShippingLedgerDimension</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingLedgerDimension name="ReceivingLedgerDimension">ReceivingLedgerDimension</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatCommodityCode name="IntrastatCommodityCode">IntrastatCommodityCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatCommodityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingLedgerDimensionDisplayValue name="ShippingLedgerDimensionDisplayValue">ShippingLedgerDimensionDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping default dimension display value</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping default dimension display value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingLedgerDimensionDisplayValue name="ReceivingLedgerDimensionDisplayValue">ReceivingLedgerDimensionDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving default dimension display value</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving default dimension display value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

### <a href=#ShippingWarehouseId name="ShippingWarehouseId">ShippingWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingSiteId name="ShippingSiteId">ShippingSiteId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

### <a href=#OrderedInventoryStatusId name="OrderedInventoryStatusId">OrderedInventoryStatusId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

### <a href=#ShippingWarehouseLocationId name="ShippingWarehouseLocationId">ShippingWarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductReceivingCrossDockProducts name="WillProductReceivingCrossDockProducts">WillProductReceivingCrossDockProducts</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductReceivingCrossDockProducts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiveNowQuantity name="ReceiveNowQuantity">ReceiveNowQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiveNowQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipNowQuantity name="ShipNowQuantity">ShipNowQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipNowQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiveNowCatchWeightQuantity name="ReceiveNowCatchWeightQuantity">ReceiveNowCatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiveNowCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipNowCatchWeightQuantity name="ShipNowCatchWeightQuantity">ShipNowCatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipNowCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

### <a href=#AssessableValueTransactionCurrency name="AssessableValueTransactionCurrency">AssessableValueTransactionCurrency</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValueTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

### <a href=#InventCostPriceCalculated name="InventCostPriceCalculated">InventCostPriceCalculated</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventCostPriceCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvntCostPrice name="InvntCostPrice">InvntCostPrice</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvntCostPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRetailPrice name="MaximumRetailPrice">MaximumRetailPrice</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRetailPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceType name="PriceType">PriceType</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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

### <a href=#Retention name="Retention">Retention</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Retention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitId name="UnitId">UnitId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATPriceType name="VATPriceType">VATPriceType</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATPriceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATRetentionCode name="VATRetentionCode">VATRetentionCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATRetentionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDefaultShipFromDimensionSetRelationshipId name="Relationship_DimensionDefaultShipFromDimensionSetRelationshipId">Relationship_DimensionDefaultShipFromDimensionSetRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDefaultShipFromDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DimensionDefaultShipToDimensionSetRelationshipId name="Relationship_DimensionDefaultShipToDimensionSetRelationshipId">Relationship_DimensionDefaultShipToDimensionSetRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDefaultShipToDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventTransferOrderHeaderRelationshipId name="Relationship_InventTransferOrderHeaderRelationshipId">Relationship_InventTransferOrderHeaderRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransferOrderHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventTransferLineRelationshipId name="BackingTable_InventTransferLineRelationshipId">BackingTable_InventTransferLineRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventTransferLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventTransferLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventTransferLine.cdm.json/InventTransferLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventTransferLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderLineEntity (this entity)  

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
