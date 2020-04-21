---
title: InventTransferLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# InventTransferLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventTransferLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTransferLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[AmountValue](#AmountValue)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ATPApplyDemandTimeFence](#ATPApplyDemandTimeFence)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ATPApplySupplyTimeFence](#ATPApplySupplyTimeFence)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ATPBackwardDemandTimeFence](#ATPBackwardDemandTimeFence)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ATPBackwardSupplyTimeFence](#ATPBackwardSupplyTimeFence)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ATPInclPlannedOrders](#ATPInclPlannedOrders)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ATPTimeFence](#ATPTimeFence)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[AutoReservation](#AutoReservation)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[CombinedTransferOrderLineDelivery](#CombinedTransferOrderLineDelivery)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[DeliveryDateControlType](#DeliveryDateControlType)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[HHTHandheldUserId](#HHTHandheldUserId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[HHTTransDate](#HHTTransDate)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[HHTTransTime](#HHTTransTime)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[IntrastatCommodity](#IntrastatCommodity)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[IntrastatFulfillmentDate_HU](#IntrastatFulfillmentDate_HU)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[IntrastatSpecMove_CZ](#IntrastatSpecMove_CZ)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[InventDimId](#InventDimId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[InventDimIdTo_RU](#InventDimIdTo_RU)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[InventTransId](#InventTransId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[InventTransIdReceive](#InventTransIdReceive)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[InventTransIdScrap](#InventTransIdScrap)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[InventTransIdTransitFrom](#InventTransIdTransitFrom)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[InventTransIdTransitTo](#InventTransIdTransitTo)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ItemId](#ItemId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[LineAmount_RU](#LineAmount_RU)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[LineNum](#LineNum)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[OrigCountryRegionId](#OrigCountryRegionId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[OrigCountyId](#OrigCountyId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[OrigStateId](#OrigStateId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[OverDeliveryPct](#OverDeliveryPct)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PackedExtensions](#PackedExtensions)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PdsCWQtyReceived](#PdsCWQtyReceived)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PdsCWQtyReceiveNow](#PdsCWQtyReceiveNow)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PdsCWQtyRemainReceive](#PdsCWQtyRemainReceive)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PdsCWQtyRemainShip](#PdsCWQtyRemainShip)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PdsCWQtyScrapped](#PdsCWQtyScrapped)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PdsCWQtyShipNow](#PdsCWQtyShipNow)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PdsCWQtyShipped](#PdsCWQtyShipped)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PdsCWQtyTransfer](#PdsCWQtyTransfer)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PdsOverrideFEFO](#PdsOverrideFEFO)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Port](#Port)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Price_RU](#Price_RU)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PriceUnit_RU](#PriceUnit_RU)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[QtyReceived](#QtyReceived)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[QtyReceiveNow](#QtyReceiveNow)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[QtyRemainReceive](#QtyRemainReceive)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[QtyRemainShip](#QtyRemainShip)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[QtyScrapped](#QtyScrapped)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[QtyShipNow](#QtyShipNow)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[QtyShipped](#QtyShipped)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[QtyTransfer](#QtyTransfer)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ReceiveDate](#ReceiveDate)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[RemainStatus](#RemainStatus)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[RetailAreaId](#RetailAreaId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[RetailInfocodeIdEx2](#RetailInfocodeIdEx2)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[RetailInformationSubcodeIdEx2](#RetailInformationSubcodeIdEx2)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[RetailReplenishRefRecId](#RetailReplenishRefRecId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[RetailReplenishRefTableId](#RetailReplenishRefTableId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ShipDate](#ShipDate)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[StatisticalValue](#StatisticalValue)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[StatProcId](#StatProcId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[TransactionCode](#TransactionCode)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[TransferId](#TransferId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Transport](#Transport)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[UnderDeliveryPct](#UnderDeliveryPct)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[UnitId](#UnitId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[DimensionDefaultShipFrom](#DimensionDefaultShipFrom)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[DimensionDefaultShipTo](#DimensionDefaultShipTo)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Intracode](#Intracode)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[CurrencyCode_IN](#CurrencyCode_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[DefaultDimension_IN](#DefaultDimension_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ExciseTariffCodes_IN](#ExciseTariffCodes_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Exempt_IN](#Exempt_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[FromDirectSettlement_IN](#FromDirectSettlement_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[FromDSA_IN](#FromDSA_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[FromExciseRecordType_IN](#FromExciseRecordType_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[FromExciseType_IN](#FromExciseType_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[HSNCodeTable_IN](#HSNCodeTable_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[InvntCostPrice_IN](#InvntCostPrice_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ITCCategory_IN](#ITCCategory_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[NetAmount_IN](#NetAmount_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[NonBusinessUsagePercentage_IN](#NonBusinessUsagePercentage_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PriceType_IN](#PriceType_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[PurchPrice_IN](#PurchPrice_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Retention_IN](#Retention_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[SalesTaxFormTypes_IN](#SalesTaxFormTypes_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ServiceAccountingCodeTable_IN](#ServiceAccountingCodeTable_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ServiceCategory_IN](#ServiceCategory_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[TaxGroup_IN](#TaxGroup_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[TaxItemGroup_IN](#TaxItemGroup_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ToDirectSettlement_IN](#ToDirectSettlement_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ToDSA_IN](#ToDSA_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ToExciseRecordType_IN](#ToExciseRecordType_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ToExciseType_IN](#ToExciseType_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[ToITCCategory_IN](#ToITCCategory_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[UnitId_IN](#UnitId_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[UnitPrice_IN](#UnitPrice_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[VATPriceType_IN](#VATPriceType_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[VATRetentionCode_IN](#VATRetentionCode_IN)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[NetAmount](#NetAmount)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[UnitPrice](#UnitPrice)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[DataAreaId](#DataAreaId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_CombinedTransferOrderLineDeliveryRelationshipId](#Relationship_CombinedTransferOrderLineDeliveryRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_IntrastatCommodityRelationshipId](#Relationship_IntrastatCommodityRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_IntrastatPortRelationshipId](#Relationship_IntrastatPortRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_IntrastatSpecMovement_CZRelationshipId](#Relationship_IntrastatSpecMovement_CZRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_IntrastatStatProcRelationshipId](#Relationship_IntrastatStatProcRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_IntrastatTransactionCodeRelationshipId](#Relationship_IntrastatTransactionCodeRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_IntrastatTransportModeRelationshipId](#Relationship_IntrastatTransportModeRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_InventDimTo_RURelationshipId](#Relationship_InventDimTo_RURelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_InventTransferTableRelationshipId](#Relationship_InventTransferTableRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_OriginCountryRegionRelationshipId](#Relationship_OriginCountryRegionRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_OriginCountyRelationshipId](#Relationship_OriginCountyRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_OriginStateRelationshipId](#Relationship_OriginStateRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_ReceiveInventTransOriginRelationshipId](#Relationship_ReceiveInventTransOriginRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_ScrapInventTransOriginRelationshipId](#Relationship_ScrapInventTransOriginRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_ShipmentInventTransOriginRelationshipId](#Relationship_ShipmentInventTransOriginRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_TransitFromInventTransOriginRelationshipId](#Relationship_TransitFromInventTransOriginRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_TransitToInventTransOriginRelationshipId](#Relationship_TransitToInventTransOriginRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_DimensionDefaultShipFromRelationshipId](#Relationship_DimensionDefaultShipFromRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_DimensionDefaultShipToRelationshipId](#Relationship_DimensionDefaultShipToRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventTransferLine.md" target="_blank">WorksheetLine/InventTransferLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTransferLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountValue name="AmountValue">AmountValue</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ATPApplyDemandTimeFence name="ATPApplyDemandTimeFence">ATPApplyDemandTimeFence</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPApplyDemandTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPApplySupplyTimeFence name="ATPApplySupplyTimeFence">ATPApplySupplyTimeFence</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPApplySupplyTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPBackwardDemandTimeFence name="ATPBackwardDemandTimeFence">ATPBackwardDemandTimeFence</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPBackwardDemandTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPBackwardSupplyTimeFence name="ATPBackwardSupplyTimeFence">ATPBackwardSupplyTimeFence</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPBackwardSupplyTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPInclPlannedOrders name="ATPInclPlannedOrders">ATPInclPlannedOrders</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPInclPlannedOrders attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPTimeFence name="ATPTimeFence">ATPTimeFence</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AutoReservation name="AutoReservation">AutoReservation</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoReservation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CombinedTransferOrderLineDelivery name="CombinedTransferOrderLineDelivery">CombinedTransferOrderLineDelivery</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CombinedTransferOrderLineDelivery attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeliveryDateControlType name="DeliveryDateControlType">DeliveryDateControlType</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDateControlType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HHTHandheldUserId name="HHTHandheldUserId">HHTHandheldUserId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HHTHandheldUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HHTTransDate name="HHTTransDate">HHTTransDate</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HHTTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#HHTTransTime name="HHTTransTime">HHTTransTime</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HHTTransTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.readOnly**  
**is.dataFormat.time**  
</details>

### <a href=#IntrastatCommodity name="IntrastatCommodity">IntrastatCommodity</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatCommodity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IntrastatFulfillmentDate_HU name="IntrastatFulfillmentDate_HU">IntrastatFulfillmentDate_HU</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatFulfillmentDate_HU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#IntrastatSpecMove_CZ name="IntrastatSpecMove_CZ">IntrastatSpecMove_CZ</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatSpecMove_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimIdTo_RU name="InventDimIdTo_RU">InventDimIdTo_RU</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimIdTo_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransId name="InventTransId">InventTransId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransIdReceive name="InventTransIdReceive">InventTransIdReceive</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransIdReceive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransIdScrap name="InventTransIdScrap">InventTransIdScrap</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransIdScrap attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransIdTransitFrom name="InventTransIdTransitFrom">InventTransIdTransitFrom</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransIdTransitFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransIdTransitTo name="InventTransIdTransitTo">InventTransIdTransitTo</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransIdTransitTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmount_RU name="LineAmount_RU">LineAmount_RU</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OrigCountryRegionId name="OrigCountryRegionId">OrigCountryRegionId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrigCountyId name="OrigCountyId">OrigCountyId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrigStateId name="OrigStateId">OrigStateId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverDeliveryPct name="OverDeliveryPct">OverDeliveryPct</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PackedExtensions name="PackedExtensions">PackedExtensions</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedExtensions attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#PdsCWQtyReceived name="PdsCWQtyReceived">PdsCWQtyReceived</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQtyReceived attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWQtyReceiveNow name="PdsCWQtyReceiveNow">PdsCWQtyReceiveNow</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQtyReceiveNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWQtyRemainReceive name="PdsCWQtyRemainReceive">PdsCWQtyRemainReceive</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQtyRemainReceive attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWQtyRemainShip name="PdsCWQtyRemainShip">PdsCWQtyRemainShip</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQtyRemainShip attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWQtyScrapped name="PdsCWQtyScrapped">PdsCWQtyScrapped</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQtyScrapped attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWQtyShipNow name="PdsCWQtyShipNow">PdsCWQtyShipNow</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQtyShipNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWQtyShipped name="PdsCWQtyShipped">PdsCWQtyShipped</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQtyShipped attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWQtyTransfer name="PdsCWQtyTransfer">PdsCWQtyTransfer</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQtyTransfer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsOverrideFEFO name="PdsOverrideFEFO">PdsOverrideFEFO</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsOverrideFEFO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Port name="Port">Port</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Port attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Price_RU name="Price_RU">Price_RU</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Price_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PriceUnit_RU name="PriceUnit_RU">PriceUnit_RU</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceUnit_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyReceived name="QtyReceived">QtyReceived</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyReceived attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyReceiveNow name="QtyReceiveNow">QtyReceiveNow</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyReceiveNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyRemainReceive name="QtyRemainReceive">QtyRemainReceive</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyRemainReceive attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyRemainShip name="QtyRemainShip">QtyRemainShip</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyRemainShip attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyScrapped name="QtyScrapped">QtyScrapped</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyScrapped attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyShipNow name="QtyShipNow">QtyShipNow</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyShipNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyShipped name="QtyShipped">QtyShipped</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyShipped attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyTransfer name="QtyTransfer">QtyTransfer</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyTransfer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReceiveDate name="ReceiveDate">ReceiveDate</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiveDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#RemainStatus name="RemainStatus">RemainStatus</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailAreaId name="RetailAreaId">RetailAreaId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailInfocodeIdEx2 name="RetailInfocodeIdEx2">RetailInfocodeIdEx2</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInfocodeIdEx2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailInformationSubcodeIdEx2 name="RetailInformationSubcodeIdEx2">RetailInformationSubcodeIdEx2</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInformationSubcodeIdEx2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailReplenishRefRecId name="RetailReplenishRefRecId">RetailReplenishRefRecId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReplenishRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailReplenishRefTableId name="RetailReplenishRefTableId">RetailReplenishRefTableId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReplenishRefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ShipDate name="ShipDate">ShipDate</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#StatisticalValue name="StatisticalValue">StatisticalValue</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StatProcId name="StatProcId">StatProcId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatProcId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCode name="TransactionCode">TransactionCode</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferId name="TransferId">TransferId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transport name="Transport">Transport</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnderDeliveryPct name="UnderDeliveryPct">UnderDeliveryPct</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnderDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UnitId name="UnitId">UnitId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDefaultShipFrom name="DimensionDefaultShipFrom">DimensionDefaultShipFrom</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDefaultShipFrom attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DimensionDefaultShipTo name="DimensionDefaultShipTo">DimensionDefaultShipTo</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDefaultShipTo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Intracode name="Intracode">Intracode</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Intracode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode_IN name="CurrencyCode_IN">CurrencyCode_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension_IN name="DefaultDimension_IN">DefaultDimension_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExciseTariffCodes_IN name="ExciseTariffCodes_IN">ExciseTariffCodes_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTariffCodes_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Exempt_IN name="Exempt_IN">Exempt_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Exempt_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FromDirectSettlement_IN name="FromDirectSettlement_IN">FromDirectSettlement_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDirectSettlement_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FromDSA_IN name="FromDSA_IN">FromDSA_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDSA_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FromExciseRecordType_IN name="FromExciseRecordType_IN">FromExciseRecordType_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromExciseRecordType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FromExciseType_IN name="FromExciseType_IN">FromExciseType_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromExciseType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HSNCodeTable_IN name="HSNCodeTable_IN">HSNCodeTable_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InvntCostPrice_IN name="InvntCostPrice_IN">InvntCostPrice_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvntCostPrice_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ITCCategory_IN name="ITCCategory_IN">ITCCategory_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ITCCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NetAmount_IN name="NetAmount_IN">NetAmount_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NonBusinessUsagePercentage_IN name="NonBusinessUsagePercentage_IN">NonBusinessUsagePercentage_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonBusinessUsagePercentage_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PriceType_IN name="PriceType_IN">PriceType_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchPrice_IN name="PurchPrice_IN">PurchPrice_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchPrice_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Retention_IN name="Retention_IN">Retention_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Retention_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesTaxFormTypes_IN name="SalesTaxFormTypes_IN">SalesTaxFormTypes_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxFormTypes_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceAccountingCodeTable_IN name="ServiceAccountingCodeTable_IN">ServiceAccountingCodeTable_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCategory_IN name="ServiceCategory_IN">ServiceCategory_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxGroup_IN name="TaxGroup_IN">TaxGroup_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup_IN name="TaxItemGroup_IN">TaxItemGroup_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToDirectSettlement_IN name="ToDirectSettlement_IN">ToDirectSettlement_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDirectSettlement_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ToDSA_IN name="ToDSA_IN">ToDSA_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDSA_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ToExciseRecordType_IN name="ToExciseRecordType_IN">ToExciseRecordType_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToExciseRecordType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ToExciseType_IN name="ToExciseType_IN">ToExciseType_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToExciseType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ToITCCategory_IN name="ToITCCategory_IN">ToITCCategory_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToITCCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UnitId_IN name="UnitId_IN">UnitId_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitId_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPrice_IN name="UnitPrice_IN">UnitPrice_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VATPriceType_IN name="VATPriceType_IN">VATPriceType_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATPriceType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VATRetentionCode_IN name="VATRetentionCode_IN">VATRetentionCode_IN</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATRetentionCode_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CombinedTransferOrderLineDeliveryRelationshipId name="Relationship_CombinedTransferOrderLineDeliveryRelationshipId">Relationship_CombinedTransferOrderLineDeliveryRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CombinedTransferOrderLineDeliveryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventTransferCombinedLineDelivery.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventTransferCombinedLineDelivery.cdm.json/InventTransferCombinedLineDelivery</a></td><td><a href="InventTransferCombinedLineDelivery.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatCommodityRelationshipId name="Relationship_IntrastatCommodityRelationshipId">Relationship_IntrastatCommodityRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatCommodityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatPortRelationshipId name="Relationship_IntrastatPortRelationshipId">Relationship_IntrastatPortRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatPortRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatPort.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatPort.cdm.json/IntrastatPort</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatPort.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatSpecMovement_CZRelationshipId name="Relationship_IntrastatSpecMovement_CZRelationshipId">Relationship_IntrastatSpecMovement_CZRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatSpecMovement_CZRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatSpecMovement_CZ.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatSpecMovement_CZ.cdm.json/IntrastatSpecMovement_CZ</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatSpecMovement_CZ.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatStatProcRelationshipId name="Relationship_IntrastatStatProcRelationshipId">Relationship_IntrastatStatProcRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatStatProcRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatStatProc.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatStatProc.cdm.json/IntrastatStatProc</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatStatProc.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatTransactionCodeRelationshipId name="Relationship_IntrastatTransactionCodeRelationshipId">Relationship_IntrastatTransactionCodeRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatTransactionCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatTransactionCode.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatTransactionCode.cdm.json/IntrastatTransactionCode</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatTransactionCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatTransportModeRelationshipId name="Relationship_IntrastatTransportModeRelationshipId">Relationship_IntrastatTransportModeRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatTransportModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatTransportMode.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatTransportMode.cdm.json/IntrastatTransportMode</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatTransportMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimTo_RURelationshipId name="Relationship_InventDimTo_RURelationshipId">Relationship_InventDimTo_RURelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventDimTo_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransferTableRelationshipId name="Relationship_InventTransferTableRelationshipId">Relationship_InventTransferTableRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransferTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventTransferTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferTable.cdm.json/InventTransferTable</a></td><td><a href="../WorksheetHeader/InventTransferTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginCountryRegionRelationshipId name="Relationship_OriginCountryRegionRelationshipId">Relationship_OriginCountryRegionRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginCountyRelationshipId name="Relationship_OriginCountyRelationshipId">Relationship_OriginCountyRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginCountyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCounty.cdm.json/LogisticsAddressCounty</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginStateRelationshipId name="Relationship_OriginStateRelationshipId">Relationship_OriginStateRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginStateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressState.cdm.json/LogisticsAddressState</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReceiveInventTransOriginRelationshipId name="Relationship_ReceiveInventTransOriginRelationshipId">Relationship_ReceiveInventTransOriginRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReceiveInventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ScrapInventTransOriginRelationshipId name="Relationship_ScrapInventTransOriginRelationshipId">Relationship_ScrapInventTransOriginRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ScrapInventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ShipmentInventTransOriginRelationshipId name="Relationship_ShipmentInventTransOriginRelationshipId">Relationship_ShipmentInventTransOriginRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ShipmentInventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransitFromInventTransOriginRelationshipId name="Relationship_TransitFromInventTransOriginRelationshipId">Relationship_TransitFromInventTransOriginRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransitFromInventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransitToInventTransOriginRelationshipId name="Relationship_TransitToInventTransOriginRelationshipId">Relationship_TransitToInventTransOriginRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransitToInventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDefaultShipFromRelationshipId name="Relationship_DimensionDefaultShipFromRelationshipId">Relationship_DimensionDefaultShipFromRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDefaultShipFromRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDefaultShipToRelationshipId name="Relationship_DimensionDefaultShipToRelationshipId">Relationship_DimensionDefaultShipToRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDefaultShipToRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/InventTransferLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
