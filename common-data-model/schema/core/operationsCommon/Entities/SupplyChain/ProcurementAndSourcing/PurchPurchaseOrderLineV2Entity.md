---
title: PurchPurchaseOrderLineV2Entity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Purchase order lines V2 in ProcurementAndSourcing(PurchPurchaseOrderLineV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order lines V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PurchaseOrderLineStatus](#PurchaseOrderLineStatus)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[SalesTaxItemGroupCode](#SalesTaxItemGroupCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[AccountingDistributionTemplate](#AccountingDistributionTemplate)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[AccountingDistributionTemplateName](#AccountingDistributionTemplateName)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[FixedAssetValueModelId](#FixedAssetValueModelId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[FixedAssetGroupId](#FixedAssetGroupId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[FixedAssetNumber](#FixedAssetNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[FixedAssetTransactionType](#FixedAssetTransactionType)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Barcode](#Barcode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[BarCodeSetupId](#BarCodeSetupId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IsLineStopped](#IsLineStopped)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IsPartialDeliveryPrevented](#IsPartialDeliveryPrevented)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ConfirmedDeliveryDate](#ConfirmedDeliveryDate)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IsNewFixedAsset](#IsNewFixedAsset)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[CustomerReference](#CustomerReference)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[CustomerRequisitionNumber](#CustomerRequisitionNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[RequestedDeliveryDate](#RequestedDeliveryDate)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ExternalItemNumber](#ExternalItemNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[GSTHSTTaxType](#GSTHSTTaxType)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[BOMId](#BOMId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[RouteId](#RouteId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[MainAccountId](#MainAccountId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[LineAmount](#LineAmount)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[LineDiscountAmount](#LineDiscountAmount)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[LineNumber](#LineNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[LineDiscountPercentage](#LineDiscountPercentage)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[VendorInvoiceMatchingPolicy](#VendorInvoiceMatchingPolicy)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[MultilineDiscountAmount](#MultilineDiscountAmount)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[MultilineDiscountPercentage](#MultilineDiscountPercentage)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[LineDescription](#LineDescription)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DIOTOperationType](#DIOTOperationType)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[AllowedOverdeliveryPercentage](#AllowedOverdeliveryPercentage)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[OrderedCatchWeightQuantity](#OrderedCatchWeightQuantity)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[PurchasePriceQuantity](#PurchasePriceQuantity)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProcurementProductCategoryRecId](#ProcurementProductCategoryRecId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProcurementProductCategoryName](#ProcurementProductCategoryName)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[FixedPriceCharges](#FixedPriceCharges)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[PurchasePrice](#PurchasePrice)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[OrderedPurchaseQuantity](#OrderedPurchaseQuantity)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[PurchaseUnitSymbol](#PurchaseUnitSymbol)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ConfirmedShippingDate](#ConfirmedShippingDate)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[RequestedShippingDate](#RequestedShippingDate)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[PurchaseRebateVendorGroupId](#PurchaseRebateVendorGroupId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099Amount](#Tax1099Amount)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099StateId](#Tax1099StateId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099StateAmount](#Tax1099StateAmount)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IntrastatPortId](#IntrastatPortId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IntrastatCommodity](#IntrastatCommodity)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IntrastatCommodityCode](#IntrastatCommodityCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IntrastatStatisticsProcedureCode](#IntrastatStatisticsProcedureCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IsIntrastatTriangularDeal](#IsIntrastatTriangularDeal)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IntrastatTransactionCode](#IntrastatTransactionCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IntrastatTransportModeCode](#IntrastatTransportModeCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[OriginCountryRegionId](#OriginCountryRegionId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[OriginStateId](#OriginStateId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[AllowedUnderdeliveryPercentage](#AllowedUnderdeliveryPercentage)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[RetailProductVariantNumber](#RetailProductVariantNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[MainAccountIdDisplayValue](#MainAccountIdDisplayValue)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryPostalAddressRecId](#DeliveryPostalAddressRecId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IsDeliveryAddressOrderSpecific](#IsDeliveryAddressOrderSpecific)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[FormattedDelveryAddress](#FormattedDelveryAddress)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryBuildingCompliment](#DeliveryBuildingCompliment)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryCityInKana](#DeliveryCityInKana)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryStreetInKana](#DeliveryStreetInKana)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryValidFrom](#DeliveryValidFrom)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryValidTo](#DeliveryValidTo)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ReceivingWarehouseId](#ReceivingWarehouseId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ReceivingSiteId](#ReceivingSiteId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[OrderedInventoryStatusId](#OrderedInventoryStatusId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099Fields](#Tax1099Fields)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099Type](#Tax1099Type)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099BoxId](#Tax1099BoxId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099GVendorStateId](#Tax1099GVendorStateId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099GVendorStateTaxId](#Tax1099GVendorStateTaxId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099GStateTaxWithheldAmount](#Tax1099GStateTaxWithheldAmount)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099GTaxYear](#Tax1099GTaxYear)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IsTax1099GTradeOrBusinessIncome](#IsTax1099GTradeOrBusinessIncome)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099SClosingDate](#Tax1099SClosingDate)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099SAddressOrLegalDescription](#Tax1099SAddressOrLegalDescription)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IsTax1099SPropertyOrServices](#IsTax1099SPropertyOrServices)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Tax1099SBuyerPartOfRealEstateTaxAmount](#Tax1099SBuyerPartOfRealEstateTaxAmount)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[UnitWeight](#UnitWeight)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[NGPCodeRecId](#NGPCodeRecId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[NGPCode](#NGPCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[WillProductReceivingCrossDockProducts](#WillProductReceivingCrossDockProducts)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[CatchWeightUnitSymbol](#CatchWeightUnitSymbol)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[RequesterRecId](#RequesterRecId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[RequesterPersonnelNumber](#RequesterPersonnelNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectId](#ProjectId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectSalesCurrencyCode](#ProjectSalesCurrencyCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectTaxGroupCode](#ProjectTaxGroupCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectTaxItemGroupCode](#ProjectTaxItemGroupCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectSalesUnitSymbol](#ProjectSalesUnitSymbol)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectWorkerPersonnelNumber](#ProjectWorkerPersonnelNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectLinePropertyId](#ProjectLinePropertyId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectSalesPrice](#ProjectSalesPrice)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IsProjectPayWhenPaid](#IsProjectPayWhenPaid)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IntrastatStatisticValue](#IntrastatStatisticValue)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[IntrastatSpecialMovementCode](#IntrastatSpecialMovementCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[WithholdingTaxGroupCode](#WithholdingTaxGroupCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ItemWithholdingTaxGroupCode](#ItemWithholdingTaxGroupCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[PurchaseOrderLineCreationMethod](#PurchaseOrderLineCreationMethod)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[CFOPCode](#CFOPCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[CFOPTableRecId](#CFOPTableRecId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ServiceFiscalInformationCode](#ServiceFiscalInformationCode)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ProjectActivityNumber](#ProjectActivityNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[BudgetReservationLineRecId](#BudgetReservationLineRecId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[BudgetReservationLineNumber](#BudgetReservationLineNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[BudgetReservationDocumentNumber](#BudgetReservationDocumentNumber)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[PurchaseRequisitionId](#PurchaseRequisitionId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[SkipCreateAutoCharges](#SkipCreateAutoCharges)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[ReceivingWarehouseLocationId](#ReceivingWarehouseLocationId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[VendorRetentionTermRuleId](#VendorRetentionTermRuleId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[VendorRetentionTermRuleDescription](#VendorRetentionTermRuleDescription)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[InventoryLotId](#InventoryLotId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Relationship_LedgerDimensionCombinationRelationshipId](#Relationship_LedgerDimensionCombinationRelationshipId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Relationship_PurchaseOrderHeaderRelationshipId](#Relationship_PurchaseOrderHeaderRelationshipId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Relationship_ProjectRelationshipId](#Relationship_ProjectRelationshipId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[BackingTable_PurchLineRelationshipId](#BackingTable_PurchLineRelationshipId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPurchaseOrderLineV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity</a>|

### <a href=#PurchaseOrderLineStatus name="PurchaseOrderLineStatus">PurchaseOrderLineStatus</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderLineStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroupCode name="SalesTaxItemGroupCode">SalesTaxItemGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplate name="AccountingDistributionTemplate">AccountingDistributionTemplate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplateName name="AccountingDistributionTemplateName">AccountingDistributionTemplateName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetValueModelId name="FixedAssetValueModelId">FixedAssetValueModelId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetValueModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetGroupId name="FixedAssetGroupId">FixedAssetGroupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetNumber name="FixedAssetNumber">FixedAssetNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetTransactionType name="FixedAssetTransactionType">FixedAssetTransactionType</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Barcode name="Barcode">Barcode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Barcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCodeSetupId name="BarCodeSetupId">BarCodeSetupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLineStopped name="IsLineStopped">IsLineStopped</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLineStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPartialDeliveryPrevented name="IsPartialDeliveryPrevented">IsPartialDeliveryPrevented</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPartialDeliveryPrevented attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmedDeliveryDate name="ConfirmedDeliveryDate">ConfirmedDeliveryDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedDeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNewFixedAsset name="IsNewFixedAsset">IsNewFixedAsset</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNewFixedAsset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerReference name="CustomerReference">CustomerReference</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisitionNumber name="CustomerRequisitionNumber">CustomerRequisitionNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisitionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

### <a href=#RequestedDeliveryDate name="RequestedDeliveryDate">RequestedDeliveryDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedDeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressName name="DeliveryAddressName">DeliveryAddressName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address name </td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address name </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalItemNumber name="ExternalItemNumber">ExternalItemNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External item number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>External item number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTHSTTaxType name="GSTHSTTaxType">GSTHSTTaxType</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTHSTTaxType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMId name="BOMId">BOMId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

### <a href=#RouteId name="RouteId">RouteId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountAmount name="LineDiscountAmount">LineDiscountAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

### <a href=#LineDiscountPercentage name="LineDiscountPercentage">LineDiscountPercentage</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceMatchingPolicy name="VendorInvoiceMatchingPolicy">VendorInvoiceMatchingPolicy</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceMatchingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountAmount name="MultilineDiscountAmount">MultilineDiscountAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountPercentage name="MultilineDiscountPercentage">MultilineDiscountPercentage</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DIOTOperationType name="DIOTOperationType">DIOTOperationType</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DIOTOperationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedOverdeliveryPercentage name="AllowedOverdeliveryPercentage">AllowedOverdeliveryPercentage</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedOverdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderedCatchWeightQuantity name="OrderedCatchWeightQuantity">OrderedCatchWeightQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceQuantity name="PurchasePriceQuantity">PurchasePriceQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementProductCategoryRecId name="ProcurementProductCategoryRecId">ProcurementProductCategoryRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementProductCategoryRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementProductCategoryName name="ProcurementProductCategoryName">ProcurementProductCategoryName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Procurement category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedPriceCharges name="FixedPriceCharges">FixedPriceCharges</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePrice name="PurchasePrice">PurchasePrice</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderedPurchaseQuantity name="OrderedPurchaseQuantity">OrderedPurchaseQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedPurchaseQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseUnitSymbol name="PurchaseUnitSymbol">PurchaseUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmedShippingDate name="ConfirmedShippingDate">ConfirmedShippingDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShippingDate name="RequestedShippingDate">RequestedShippingDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseRebateVendorGroupId name="PurchaseRebateVendorGroupId">PurchaseRebateVendorGroupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRebateVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Amount name="Tax1099Amount">Tax1099Amount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099StateId name="Tax1099StateId">Tax1099StateId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099StateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099StateAmount name="Tax1099StateAmount">Tax1099StateAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099StateAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatPortId name="IntrastatPortId">IntrastatPortId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatPortId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatCommodity name="IntrastatCommodity">IntrastatCommodity</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatCommodity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatCommodityCode name="IntrastatCommodityCode">IntrastatCommodityCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commodity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatCommodityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commodity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatStatisticsProcedureCode name="IntrastatStatisticsProcedureCode">IntrastatStatisticsProcedureCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatStatisticsProcedureCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntrastatTriangularDeal name="IsIntrastatTriangularDeal">IsIntrastatTriangularDeal</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntrastatTriangularDeal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransactionCode name="IntrastatTransactionCode">IntrastatTransactionCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransportModeCode name="IntrastatTransportModeCode">IntrastatTransportModeCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransportModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginCountryRegionId name="OriginCountryRegionId">OriginCountryRegionId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginStateId name="OriginStateId">OriginStateId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedUnderdeliveryPercentage name="AllowedUnderdeliveryPercentage">AllowedUnderdeliveryPercentage</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedUnderdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailProductVariantNumber name="RetailProductVariantNumber">RetailProductVariantNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailProductVariantNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial dimensions</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial dimensions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdDisplayValue name="MainAccountIdDisplayValue">MainAccountIdDisplayValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddressRecId name="DeliveryPostalAddressRecId">DeliveryPostalAddressRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressOrderSpecific name="IsDeliveryAddressOrderSpecific">IsDeliveryAddressOrderSpecific</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>One time delivery address</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressOrderSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>One time delivery address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedDelveryAddress name="FormattedDelveryAddress">FormattedDelveryAddress</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedDelveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryBuildingCompliment name="DeliveryBuildingCompliment">DeliveryBuildingCompliment</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCityInKana name="DeliveryCityInKana">DeliveryCityInKana</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionISOCode name="DeliveryAddressCountryRegionISOCode">DeliveryAddressCountryRegionISOCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountyId name="DeliveryAddressCountyId">DeliveryAddressCountyId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDescription name="DeliveryAddressDescription">DeliveryAddressDescription</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDunsNumber name="DeliveryAddressDunsNumber">DeliveryAddressDunsNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressPrivate name="IsDeliveryAddressPrivate">IsDeliveryAddressPrivate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is delivery address private</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is delivery address private</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLongitude name="DeliveryAddressLongitude">DeliveryAddressLongitude</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressPostBox name="DeliveryAddressPostBox">DeliveryAddressPostBox</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStateId name="DeliveryAddressStateId">DeliveryAddressStateId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreet name="DeliveryAddressStreet">DeliveryAddressStreet</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryStreetInKana name="DeliveryStreetInKana">DeliveryStreetInKana</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidFrom name="DeliveryValidFrom">DeliveryValidFrom</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidTo name="DeliveryValidTo">DeliveryValidTo</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingWarehouseId name="ReceivingWarehouseId">ReceivingWarehouseId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingSiteId name="ReceivingSiteId">ReceivingSiteId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

### <a href=#OrderedInventoryStatusId name="OrderedInventoryStatusId">OrderedInventoryStatusId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Fields name="Tax1099Fields">Tax1099Fields</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Fields attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Type name="Tax1099Type">Tax1099Type</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099BoxId name="Tax1099BoxId">Tax1099BoxId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099BoxId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099GVendorStateId name="Tax1099GVendorStateId">Tax1099GVendorStateId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099GVendorStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099GVendorStateTaxId name="Tax1099GVendorStateTaxId">Tax1099GVendorStateTaxId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099GVendorStateTaxId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099GStateTaxWithheldAmount name="Tax1099GStateTaxWithheldAmount">Tax1099GStateTaxWithheldAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099GStateTaxWithheldAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099GTaxYear name="Tax1099GTaxYear">Tax1099GTaxYear</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099GTaxYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTax1099GTradeOrBusinessIncome name="IsTax1099GTradeOrBusinessIncome">IsTax1099GTradeOrBusinessIncome</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTax1099GTradeOrBusinessIncome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099SClosingDate name="Tax1099SClosingDate">Tax1099SClosingDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099SClosingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099SAddressOrLegalDescription name="Tax1099SAddressOrLegalDescription">Tax1099SAddressOrLegalDescription</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099SAddressOrLegalDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTax1099SPropertyOrServices name="IsTax1099SPropertyOrServices">IsTax1099SPropertyOrServices</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTax1099SPropertyOrServices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099SBuyerPartOfRealEstateTaxAmount name="Tax1099SBuyerPartOfRealEstateTaxAmount">Tax1099SBuyerPartOfRealEstateTaxAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099SBuyerPartOfRealEstateTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitWeight name="UnitWeight">UnitWeight</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NGPCodeRecId name="NGPCodeRecId">NGPCodeRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NGPCodeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NGPCode name="NGPCode">NGPCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NGPCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductReceivingCrossDockProducts name="WillProductReceivingCrossDockProducts">WillProductReceivingCrossDockProducts</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductReceivingCrossDockProducts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightUnitSymbol name="CatchWeightUnitSymbol">CatchWeightUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequesterRecId name="RequesterRecId">RequesterRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequesterRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequesterPersonnelNumber name="RequesterPersonnelNumber">RequesterPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequesterPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requester</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesCurrencyCode name="ProjectSalesCurrencyCode">ProjectSalesCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectSalesCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectTaxGroupCode name="ProjectTaxGroupCode">ProjectTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectTaxItemGroupCode name="ProjectTaxItemGroupCode">ProjectTaxItemGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesUnitSymbol name="ProjectSalesUnitSymbol">ProjectSalesUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectSalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectWorkerPersonnelNumber name="ProjectWorkerPersonnelNumber">ProjectWorkerPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectLinePropertyId name="ProjectLinePropertyId">ProjectLinePropertyId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectLinePropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesPrice name="ProjectSalesPrice">ProjectSalesPrice</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectSalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectPayWhenPaid name="IsProjectPayWhenPaid">IsProjectPayWhenPaid</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectPayWhenPaid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatStatisticValue name="IntrastatStatisticValue">IntrastatStatisticValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatStatisticValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatSpecialMovementCode name="IntrastatSpecialMovementCode">IntrastatSpecialMovementCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatSpecialMovementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxGroupCode name="WithholdingTaxGroupCode">WithholdingTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemWithholdingTaxGroupCode name="ItemWithholdingTaxGroupCode">ItemWithholdingTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemWithholdingTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderLineCreationMethod name="PurchaseOrderLineCreationMethod">PurchaseOrderLineCreationMethod</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderLineCreationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPCode name="CFOPCode">CFOPCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPTableRecId name="CFOPTableRecId">CFOPTableRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPTableRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceFiscalInformationCode name="ServiceFiscalInformationCode">ServiceFiscalInformationCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceFiscalInformationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectActivityNumber name="ProjectActivityNumber">ProjectActivityNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationLineRecId name="BudgetReservationLineRecId">BudgetReservationLineRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationLineRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationLineNumber name="BudgetReservationLineNumber">BudgetReservationLineNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationDocumentNumber name="BudgetReservationDocumentNumber">BudgetReservationDocumentNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseRequisitionId name="PurchaseRequisitionId">PurchaseRequisitionId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRequisitionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipCreateAutoCharges name="SkipCreateAutoCharges">SkipCreateAutoCharges</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Skip charges</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipCreateAutoCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Skip charges</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingWarehouseLocationId name="ReceivingWarehouseLocationId">ReceivingWarehouseLocationId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorRetentionTermRuleId name="VendorRetentionTermRuleId">VendorRetentionTermRuleId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor retention term</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorRetentionTermRuleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor retention term</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorRetentionTermRuleDescription name="VendorRetentionTermRuleDescription">VendorRetentionTermRuleDescription</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor retention term description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorRetentionTermRuleDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor retention term description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryLotId name="InventoryLotId">InventoryLotId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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

### <a href=#Relationship_LedgerDimensionCombinationRelationshipId name="Relationship_LedgerDimensionCombinationRelationshipId">Relationship_LedgerDimensionCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseOrderHeaderRelationshipId name="Relationship_PurchaseOrderHeaderRelationshipId">Relationship_PurchaseOrderHeaderRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseOrderHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjectRelationshipId name="Relationship_ProjectRelationshipId">Relationship_ProjectRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PurchLineRelationshipId name="BackingTable_PurchLineRelationshipId">BackingTable_PurchLineRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.cdm.json/PurchLine</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderLineV2Entity (this entity)  

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
