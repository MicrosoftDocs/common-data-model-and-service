---
title: PurchPurchaseOrderConfirmationLineEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Purchase order confirmation lines in ProcurementAndSourcing(PurchPurchaseOrderConfirmationLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order confirmation lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PurchaseOrderLineStatus](#PurchaseOrderLineStatus)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[SalesTaxItemGroupCode](#SalesTaxItemGroupCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[AccountingDistributionTemplateName](#AccountingDistributionTemplateName)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[FixedAssetValueModelId](#FixedAssetValueModelId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[FixedAssetGroupId](#FixedAssetGroupId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[FixedAssetNumber](#FixedAssetNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[FixedAssetTransactionType](#FixedAssetTransactionType)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Barcode](#Barcode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[BarCodeSetupId](#BarCodeSetupId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IsLineStopped](#IsLineStopped)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IsPartialDeliveryPrevented](#IsPartialDeliveryPrevented)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ConfirmedDeliveryDate](#ConfirmedDeliveryDate)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IsNewFixedAsset](#IsNewFixedAsset)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[CustomerReference](#CustomerReference)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[CustomerRequisitionNumber](#CustomerRequisitionNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[RequestedDeliveryDate](#RequestedDeliveryDate)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ExternalItemNumber](#ExternalItemNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[GSTHSTTaxType](#GSTHSTTaxType)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[BOMId](#BOMId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[RouteId](#RouteId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[MainAccountId](#MainAccountId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[LineAmount](#LineAmount)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[LineDiscountAmount](#LineDiscountAmount)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[LineDiscountPercentage](#LineDiscountPercentage)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[VendorInvoiceMatchingPolicy](#VendorInvoiceMatchingPolicy)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[MultilineDiscountAmount](#MultilineDiscountAmount)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[MultilineDiscountPercentage](#MultilineDiscountPercentage)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[LineDescription](#LineDescription)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[AllowedOverdeliveryPercentage](#AllowedOverdeliveryPercentage)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[OrderedCatchWeightQuantity](#OrderedCatchWeightQuantity)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[PurchasePriceQuantity](#PurchasePriceQuantity)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProcurementProductCategoryName](#ProcurementProductCategoryName)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[FixedPriceCharges](#FixedPriceCharges)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[PurchasePrice](#PurchasePrice)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[OrderedPurchaseQuantity](#OrderedPurchaseQuantity)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[PurchaseUnitSymbol](#PurchaseUnitSymbol)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ConfirmedShippingDate](#ConfirmedShippingDate)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[RequestedShippingDate](#RequestedShippingDate)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Tax1099Amount](#Tax1099Amount)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Tax1099StateId](#Tax1099StateId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Tax1099StateAmount](#Tax1099StateAmount)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IntrastatPortId](#IntrastatPortId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IntrastatCommodityCode](#IntrastatCommodityCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IntrastatStatisticsProcedureCode](#IntrastatStatisticsProcedureCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IsIntrastatTriangularDeal](#IsIntrastatTriangularDeal)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IntrastatTransactionCode](#IntrastatTransactionCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IntrastatTransportModeCode](#IntrastatTransportModeCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[OriginCountryRegionId](#OriginCountryRegionId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[OriginStateId](#OriginStateId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[AllowedUnderdeliveryPercentage](#AllowedUnderdeliveryPercentage)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[MainAccountIdDisplayValue](#MainAccountIdDisplayValue)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressBuildingCompliment](#DeliveryAddressBuildingCompliment)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryCityInKana](#DeliveryCityInKana)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressStreetInKana](#DeliveryAddressStreetInKana)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressValidFrom](#DeliveryAddressValidFrom)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressValidTo](#DeliveryAddressValidTo)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ReceivingWarehouseId](#ReceivingWarehouseId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ReceivingSiteId](#ReceivingSiteId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[OrderedInventoryStatusId](#OrderedInventoryStatusId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Tax1099Type](#Tax1099Type)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Tax1099BoxId](#Tax1099BoxId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[CatchWeightUnitSymbol](#CatchWeightUnitSymbol)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[RequesterPersonnelNumber](#RequesterPersonnelNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProjectId](#ProjectId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProjectSalesCurrencyCode](#ProjectSalesCurrencyCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProjectTaxGroupCode](#ProjectTaxGroupCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProjectTaxItemGroupCode](#ProjectTaxItemGroupCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProjectSalesUnitSymbol](#ProjectSalesUnitSymbol)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProjectLinePropertyId](#ProjectLinePropertyId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProjectSalesPrice](#ProjectSalesPrice)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[WithholdingTaxGroupCode](#WithholdingTaxGroupCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ItemWithholdingTaxGroupCode](#ItemWithholdingTaxGroupCode)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[PurchaseOrderLineCreationMethod](#PurchaseOrderLineCreationMethod)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ProjectActivityNumber](#ProjectActivityNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[InvoiceVendorAccountNumber](#InvoiceVendorAccountNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[OrderVendorAccountNumber](#OrderVendorAccountNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ConfirmationNumber](#ConfirmationNumber)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ConfirmationDate](#ConfirmationDate)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[ArePricesIncludingSalesTax](#ArePricesIncludingSalesTax)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[TotalLineSalesTaxAmount](#TotalLineSalesTaxAmount)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Relationship_LedgerDimensionCombinationRelationshipId](#Relationship_LedgerDimensionCombinationRelationshipId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Relationship_ProjectRelationshipId](#Relationship_ProjectRelationshipId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Relationship_InvoiceVendorRelationshipId](#Relationship_InvoiceVendorRelationshipId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Relationship_OrderVendorRelationshipId](#Relationship_OrderVendorRelationshipId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Relationship_PurchaseOrderConfirmationHeaderRelationshipId](#Relationship_PurchaseOrderConfirmationHeaderRelationshipId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[BackingTable_VendPurchOrderJourRelationshipId](#BackingTable_VendPurchOrderJourRelationshipId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPurchaseOrderConfirmationLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity</a>|

### <a href=#PurchaseOrderLineStatus name="PurchaseOrderLineStatus">PurchaseOrderLineStatus</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#AccountingDistributionTemplateName name="AccountingDistributionTemplateName">AccountingDistributionTemplateName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Asset value model id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetValueModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Asset value model id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetGroupId name="FixedAssetGroupId">FixedAssetGroupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirmed delivery date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedDeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confirmed delivery date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNewFixedAsset name="IsNewFixedAsset">IsNewFixedAsset</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedOverdeliveryPercentage name="AllowedOverdeliveryPercentage">AllowedOverdeliveryPercentage</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#ProcurementProductCategoryName name="ProcurementProductCategoryName">ProcurementProductCategoryName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedPurchaseQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseUnitSymbol name="PurchaseUnitSymbol">PurchaseUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#Tax1099Amount name="Tax1099Amount">Tax1099Amount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#IntrastatCommodityCode name="IntrastatCommodityCode">IntrastatCommodityCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#FormattedDeliveryAddress name="FormattedDeliveryAddress">FormattedDeliveryAddress</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedDeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressBuildingCompliment name="DeliveryAddressBuildingCompliment">DeliveryAddressBuildingCompliment</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address description </td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address description </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#DeliveryAddressStreetInKana name="DeliveryAddressStreetInKana">DeliveryAddressStreetInKana</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#DeliveryAddressValidFrom name="DeliveryAddressValidFrom">DeliveryAddressValidFrom</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressValidTo name="DeliveryAddressValidTo">DeliveryAddressValidTo</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#Tax1099Type name="Tax1099Type">Tax1099Type</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#CatchWeightUnitSymbol name="CatchWeightUnitSymbol">CatchWeightUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#RequesterPersonnelNumber name="RequesterPersonnelNumber">RequesterPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesCurrencyCode name="ProjectSalesCurrencyCode">ProjectSalesCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#ProjectLinePropertyId name="ProjectLinePropertyId">ProjectLinePropertyId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#WithholdingTaxGroupCode name="WithholdingTaxGroupCode">WithholdingTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#ProjectActivityNumber name="ProjectActivityNumber">ProjectActivityNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#InvoiceVendorAccountNumber name="InvoiceVendorAccountNumber">InvoiceVendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderVendorAccountNumber name="OrderVendorAccountNumber">OrderVendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmationNumber name="ConfirmationNumber">ConfirmationNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmationDate name="ConfirmationDate">ConfirmationDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirmation date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confirmation date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePricesIncludingSalesTax name="ArePricesIncludingSalesTax">ArePricesIncludingSalesTax</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePricesIncludingSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalLineSalesTaxAmount name="TotalLineSalesTaxAmount">TotalLineSalesTaxAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax included in amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalLineSalesTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax included in amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#Relationship_ProjectRelationshipId name="Relationship_ProjectRelationshipId">Relationship_ProjectRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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

### <a href=#Relationship_InvoiceVendorRelationshipId name="Relationship_InvoiceVendorRelationshipId">Relationship_InvoiceVendorRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceVendorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OrderVendorRelationshipId name="Relationship_OrderVendorRelationshipId">Relationship_OrderVendorRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrderVendorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseOrderConfirmationHeaderRelationshipId name="Relationship_PurchaseOrderConfirmationHeaderRelationshipId">Relationship_PurchaseOrderConfirmationHeaderRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseOrderConfirmationHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_VendPurchOrderJourRelationshipId name="BackingTable_VendPurchOrderJourRelationshipId">BackingTable_VendPurchOrderJourRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendPurchOrderJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPurchOrderJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPurchOrderJour.cdm.json/VendPurchOrderJour</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPurchOrderJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationLineEntity (this entity)  

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
