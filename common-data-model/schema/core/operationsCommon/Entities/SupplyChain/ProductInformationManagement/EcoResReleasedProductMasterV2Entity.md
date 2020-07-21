---
title: EcoResReleasedProductMasterV2Entity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Released product masters V2 in ProductInformationManagement(EcoResReleasedProductMasterV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResReleasedProductMasterV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Released product masters V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductType](#ProductType)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductNumber](#ProductNumber)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductSearchName](#ProductSearchName)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SearchName](#SearchName)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductGroupId](#ProductGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ItemModelGroupId](#ItemModelGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[StorageDimensionGroupName](#StorageDimensionGroupName)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[TrackingDimensionGroupName](#TrackingDimensionGroupName)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[InventoryReservationHierarchyName](#InventoryReservationHierarchyName)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[DefaultOrderType](#DefaultOrderType)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[MarginABCCode](#MarginABCCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[RevenueABCCode](#RevenueABCCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[CarryingCostABCCode](#CarryingCostABCCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ValueABCCode](#ValueABCCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[AlternativeProductUsageCondition](#AlternativeProductUsageCondition)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[AlternativeProductConfigurationId](#AlternativeProductConfigurationId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[AlternativeProductColorId](#AlternativeProductColorId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[AlternativeProductSizeId](#AlternativeProductSizeId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[AlternativeProductStyleId](#AlternativeProductStyleId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[AlternativeProductVersionId](#AlternativeProductVersionId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[AlternativeItemNumber](#AlternativeItemNumber)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[WillInventoryIssueAutomaticallyReportAsFinished](#WillInventoryIssueAutomaticallyReportAsFinished)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[BatchMergeDateCalculationMethod](#BatchMergeDateCalculationMethod)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[BatchNumberGroupCode](#BatchNumberGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[CostCalculationGroupId](#CostCalculationGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[BOMLevel](#BOMLevel)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[BOMUnitSymbol](#BOMUnitSymbol)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[FlushingPrinciple](#FlushingPrinciple)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[WillInventoryReceiptIgnoreFlushingPrinciple](#WillInventoryReceiptIgnoreFlushingPrinciple)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[CommissionProductGroupId](#CommissionProductGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[CostGroupId](#CostGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsUnitCostAutomaticallyUpdated](#IsUnitCostAutomaticallyUpdated)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductionConsumptionDensityConversionFactor](#ProductionConsumptionDensityConversionFactor)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductionConsumptionDepthConversionFactor](#ProductionConsumptionDepthConversionFactor)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductionConsumptionWidthConversionFactor](#ProductionConsumptionWidthConversionFactor)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductionConsumptionHeightConversionFactor](#ProductionConsumptionHeightConversionFactor)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[GrossDepth](#GrossDepth)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[GrossProductHeight](#GrossProductHeight)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[GrossProductWidth](#GrossProductWidth)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductVolume](#ProductVolume)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[NetProductWeight](#NetProductWeight)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[BuyerGroupId](#BuyerGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsUnitCostProductVariantSpecific](#IsUnitCostProductVariantSpecific)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchasePriceToleranceGroupId](#PurchasePriceToleranceGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[VendorInvoiceLineMatchingPolicy](#VendorInvoiceLineMatchingPolicy)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PackingMaterialGroupId](#PackingMaterialGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[BestBeforePeriodDays](#BestBeforePeriodDays)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[FreightAllocationGroupId](#FreightAllocationGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesRebateProductGroupId](#SalesRebateProductGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PotencyBaseAttributeValueEntryEvent](#PotencyBaseAttributeValueEntryEvent)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ShelfAdvicePeriodDays](#ShelfAdvicePeriodDays)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ShelfLifePeriodDays](#ShelfLifePeriodDays)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PotencyBaseAttibuteTargetValue](#PotencyBaseAttibuteTargetValue)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ApprovedVendorCheckMethod](#ApprovedVendorCheckMethod)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsPhantom](#IsPhantom)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PlanningFormulaItemNumber](#PlanningFormulaItemNumber)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductionType](#ProductionType)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[YieldPercentage](#YieldPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PrimaryVendorAccountNumber](#PrimaryVendorAccountNumber)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductionGroupId](#ProductionGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductionPoolId](#ProductionPoolId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[NecessaryProductionWorkingTimeSchedulingPropertyId](#NecessaryProductionWorkingTimeSchedulingPropertyId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsPurchasePriceAutomaticallyUpdated](#IsPurchasePriceAutomaticallyUpdated)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductCoverageGroupId](#ProductCoverageGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesPriceCalculationModel](#SalesPriceCalculationModel)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[BaseSalesPriceSource](#BaseSalesPriceSource)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesPriceCalculationContributionRatio](#SalesPriceCalculationContributionRatio)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesPriceCalculationChargesPercentage](#SalesPriceCalculationChargesPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ConstantScrapQuantity](#ConstantScrapQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[VariableScrapPercentage](#VariableScrapPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SerialNumberGroupCode](#SerialNumberGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ShippingAndReceivingSortOrderCode](#ShippingAndReceivingSortOrderCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[DefaultProductConfigurationId](#DefaultProductConfigurationId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[DefaultProductColorId](#DefaultProductColorId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[DefaultProductSizeId](#DefaultProductSizeId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[DefaultProductStyleId](#DefaultProductStyleId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[DefaultProductVersionId](#DefaultProductVersionId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[TareProductWeight](#TareProductWeight)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PackingDutyQuantity](#PackingDutyQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ArrivalHandlingTime](#ArrivalHandlingTime)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[MaximumPickQuantity](#MaximumPickQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PackageClassId](#PackageClassId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PackSizeCategoryId](#PackSizeCategoryId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PhysicalDimensionGroupId](#PhysicalDimensionGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[WillWorkCenterPickingAllowNegativeInventory](#WillWorkCenterPickingAllowNegativeInventory)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[DefaultReceivingQuantity](#DefaultReceivingQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[WarehouseMobileDeviceDescriptionLine1](#WarehouseMobileDeviceDescriptionLine1)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[WarehouseMobileDeviceDescriptionLine2](#WarehouseMobileDeviceDescriptionLine2)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[UnitConversionSequenceGroupId](#UnitConversionSequenceGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[RawMaterialPickingPrinciple](#RawMaterialPickingPrinciple)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[CatchWeightUnitSymbol](#CatchWeightUnitSymbol)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[MaximumCatchWeightQuantity](#MaximumCatchWeightQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[MinimumCatchWeightQuantity](#MinimumCatchWeightQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsSalesPriceAdjustmentAllowed](#IsSalesPriceAdjustmentAllowed)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ContinuityEventDuration](#ContinuityEventDuration)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ContinuityScheduleId](#ContinuityScheduleId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsRestrictedForCoupons](#IsRestrictedForCoupons)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[DefaultDirectDeliveryWarehouse](#DefaultDirectDeliveryWarehouse)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsDeliveredDirectly](#IsDeliveredDirectly)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsExemptFromAutomaticNotificationAndCancellation](#IsExemptFromAutomaticNotificationAndCancellation)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsInstallmentEligible](#IsInstallmentEligible)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[WillPickingWorkbenchApplyBoxingLogic](#WillPickingWorkbenchApplyBoxingLogic)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseRebateProductGroupId](#PurchaseRebateProductGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SellEndDate](#SellEndDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SellStartDate](#SellStartDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsShipAloneEnabled](#IsShipAloneEnabled)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ShipStartDate](#ShipStartDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[BarcodeSetupId](#BarcodeSetupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ComparisonPriceBaseUnitSymbol](#ComparisonPriceBaseUnitSymbol)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsScaleProduct](#IsScaleProduct)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsPOSRegistrationBlocked](#IsPOSRegistrationBlocked)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[POSRegistrationBlockedDate](#POSRegistrationBlockedDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[POSRegistrationPlannedBlockedDate](#POSRegistrationPlannedBlockedDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[POSRegistrationActivationDate](#POSRegistrationActivationDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[KeyInPriceRequirementsAtPOSRegister](#KeyInPriceRequirementsAtPOSRegister)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[KeyInQuantityRequirementsAtPOSRegister](#KeyInQuantityRequirementsAtPOSRegister)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[MustKeyInCommentAtPOSRegister](#MustKeyInCommentAtPOSRegister)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsZeroPricePOSRegistrationAllowed](#IsZeroPricePOSRegistrationAllowed)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsDiscountPOSRegistrationProhibited](#IsDiscountPOSRegistrationProhibited)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsPOSRegistrationQuantityNegative](#IsPOSRegistrationQuantityNegative)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductLifeCycleSeasonCode](#ProductLifeCycleSeasonCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductLifeCycleValidFromDate](#ProductLifeCycleValidFromDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductLifeCycleValidToDate](#ProductLifeCycleValidToDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsVariantShelfLabelsPrintingEnabled](#IsVariantShelfLabelsPrintingEnabled)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[TransferOrderOverdeliveryPercentage](#TransferOrderOverdeliveryPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[TransferOrderUnderdeliveryPercentage](#TransferOrderUnderdeliveryPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[UnitCost](#UnitCost)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[UnitCostDate](#UnitCostDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[UnitCostQuantity](#UnitCostQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsUnitCostIncludingCharges](#IsUnitCostIncludingCharges)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[FixedCostCharges](#FixedCostCharges)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[CostChargesQuantity](#CostChargesQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[InventoryUnitSymbol](#InventoryUnitSymbol)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsIntercompanySalesUsageBlocked](#IsIntercompanySalesUsageBlocked)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesSalesTaxItemGroupCode](#SalesSalesTaxItemGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[WillTotalSalesDiscountCalculationIncludeProduct](#WillTotalSalesDiscountCalculationIncludeProduct)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesLineDiscountProductGroupCode](#SalesLineDiscountProductGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesMultilineDiscountProductGroupCode](#SalesMultilineDiscountProductGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesSupplementaryProductProductGroupId](#SalesSupplementaryProductProductGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesChargeProductGroupId](#SalesChargeProductGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesOverdeliveryPercentage](#SalesOverdeliveryPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesUnderdeliveryPercentage](#SalesUnderdeliveryPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesPricingPrecision](#SalesPricingPrecision)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesPrice](#SalesPrice)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesPriceDate](#SalesPriceDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesPriceQuantity](#SalesPriceQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesUnitSymbol](#SalesUnitSymbol)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsSalesPriceIncludingCharges](#IsSalesPriceIncludingCharges)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[FixedSalesPriceCharges](#FixedSalesPriceCharges)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesChargesQuantity](#SalesChargesQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseSalesTaxItemGroupCode](#PurchaseSalesTaxItemGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsIntercompanyPurchaseUsageBlocked](#IsIntercompanyPurchaseUsageBlocked)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseLineDiscountProductGroupCode](#PurchaseLineDiscountProductGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseMultilineDiscountProductGroupCode](#PurchaseMultilineDiscountProductGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[WillTotalPurchaseDiscountCalculationIncludeProduct](#WillTotalPurchaseDiscountCalculationIncludeProduct)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseSupplementaryProductProductGroupId](#PurchaseSupplementaryProductProductGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseOverdeliveryPercentage](#PurchaseOverdeliveryPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseUnderdeliveryPercentage](#PurchaseUnderdeliveryPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchasePricingPrecision](#PurchasePricingPrecision)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchasePrice](#PurchasePrice)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchasePriceDate](#PurchasePriceDate)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchasePriceQuantity](#PurchasePriceQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseUnitSymbol](#PurchaseUnitSymbol)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseChargeProductGroupId](#PurchaseChargeProductGroupId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsPurchasePriceIncludingCharges](#IsPurchasePriceIncludingCharges)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[FixedPurchasePriceCharges](#FixedPurchasePriceCharges)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseChargesQuantity](#PurchaseChargesQuantity)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[AreTransportationManagementProcessesEnabled](#AreTransportationManagementProcessesEnabled)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IntrastatCommodityCode](#IntrastatCommodityCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IntrastatChargePercentage](#IntrastatChargePercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[OriginCountryRegionId](#OriginCountryRegionId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[OriginStateId](#OriginStateId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ApproximateSalesTaxPercentage](#ApproximateSalesTaxPercentage)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ItemFiscalClassificationExceptionCode](#ItemFiscalClassificationExceptionCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductFiscalInformationType](#ProductFiscalInformationType)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsICMSTaxAppliedOnService](#IsICMSTaxAppliedOnService)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ProductTaxationOrigin](#ProductTaxationOrigin)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ItemFiscalClassificationCode](#ItemFiscalClassificationCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[ServiceFiscalInformationCode](#ServiceFiscalInformationCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsSalesWithholdingTaxCalculated](#IsSalesWithholdingTaxCalculated)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesItemWithholdingTaxGroupCode](#SalesItemWithholdingTaxGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[IsPurchaseWithholdingTaxCalculated](#IsPurchaseWithholdingTaxCalculated)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseItemWithholdingTaxGroupCode](#PurchaseItemWithholdingTaxGroupCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[SalesGSTReliefCategoryCode](#SalesGSTReliefCategoryCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[PurchaseGSTReliefCategoryCode](#PurchaseGSTReliefCategoryCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[InventoryGSTReliefCategoryCode](#InventoryGSTReliefCategoryCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[NGPCode](#NGPCode)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[CostCalculationBOMLevel](#CostCalculationBOMLevel)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[Relationship_ProductMasterRelationshipId](#Relationship_ProductMasterRelationshipId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[BackingTable_EcoResReleasedProductV2EntityRelationshipId](#BackingTable_EcoResReleasedProductV2EntityRelationshipId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="EcoResReleasedProductMasterV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductMasterV2Entity</a>|

### <a href=#ProductType name="ProductType">ProductType</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSearchName name="ProductSearchName">ProductSearchName</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product search name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product search name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#SearchName name="SearchName">SearchName</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductGroupId name="ProductGroupId">ProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemModelGroupId name="ItemModelGroupId">ItemModelGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemModelGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StorageDimensionGroupName name="StorageDimensionGroupName">StorageDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingDimensionGroupName name="TrackingDimensionGroupName">TrackingDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryReservationHierarchyName name="InventoryReservationHierarchyName">InventoryReservationHierarchyName</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryReservationHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOrderType name="DefaultOrderType">DefaultOrderType</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarginABCCode name="MarginABCCode">MarginABCCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginABCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueABCCode name="RevenueABCCode">RevenueABCCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueABCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarryingCostABCCode name="CarryingCostABCCode">CarryingCostABCCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarryingCostABCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueABCCode name="ValueABCCode">ValueABCCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueABCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductUsageCondition name="AlternativeProductUsageCondition">AlternativeProductUsageCondition</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductUsageCondition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductConfigurationId name="AlternativeProductConfigurationId">AlternativeProductConfigurationId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductColorId name="AlternativeProductColorId">AlternativeProductColorId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductSizeId name="AlternativeProductSizeId">AlternativeProductSizeId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductStyleId name="AlternativeProductStyleId">AlternativeProductStyleId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductVersionId name="AlternativeProductVersionId">AlternativeProductVersionId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeItemNumber name="AlternativeItemNumber">AlternativeItemNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInventoryIssueAutomaticallyReportAsFinished name="WillInventoryIssueAutomaticallyReportAsFinished">WillInventoryIssueAutomaticallyReportAsFinished</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInventoryIssueAutomaticallyReportAsFinished attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchMergeDateCalculationMethod name="BatchMergeDateCalculationMethod">BatchMergeDateCalculationMethod</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchMergeDateCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchNumberGroupCode name="BatchNumberGroupCode">BatchNumberGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchNumberGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostCalculationGroupId name="CostCalculationGroupId">CostCalculationGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostCalculationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMLevel name="BOMLevel">BOMLevel</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMUnitSymbol name="BOMUnitSymbol">BOMUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlushingPrinciple name="FlushingPrinciple">FlushingPrinciple</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlushingPrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInventoryReceiptIgnoreFlushingPrinciple name="WillInventoryReceiptIgnoreFlushingPrinciple">WillInventoryReceiptIgnoreFlushingPrinciple</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInventoryReceiptIgnoreFlushingPrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionProductGroupId name="CommissionProductGroupId">CommissionProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostGroupId name="CostGroupId">CostGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsUnitCostAutomaticallyUpdated name="IsUnitCostAutomaticallyUpdated">IsUnitCostAutomaticallyUpdated</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUnitCostAutomaticallyUpdated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionConsumptionDensityConversionFactor name="ProductionConsumptionDensityConversionFactor">ProductionConsumptionDensityConversionFactor</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionConsumptionDensityConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionConsumptionDepthConversionFactor name="ProductionConsumptionDepthConversionFactor">ProductionConsumptionDepthConversionFactor</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionConsumptionDepthConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionConsumptionWidthConversionFactor name="ProductionConsumptionWidthConversionFactor">ProductionConsumptionWidthConversionFactor</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionConsumptionWidthConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionConsumptionHeightConversionFactor name="ProductionConsumptionHeightConversionFactor">ProductionConsumptionHeightConversionFactor</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionConsumptionHeightConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossDepth name="GrossDepth">GrossDepth</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossDepth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossProductHeight name="GrossProductHeight">GrossProductHeight</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossProductHeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossProductWidth name="GrossProductWidth">GrossProductWidth</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossProductWidth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVolume name="ProductVolume">ProductVolume</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVolume attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetProductWeight name="NetProductWeight">NetProductWeight</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetProductWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerGroupId name="BuyerGroupId">BuyerGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsUnitCostProductVariantSpecific name="IsUnitCostProductVariantSpecific">IsUnitCostProductVariantSpecific</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUnitCostProductVariantSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceToleranceGroupId name="PurchasePriceToleranceGroupId">PurchasePriceToleranceGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceToleranceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceLineMatchingPolicy name="VendorInvoiceLineMatchingPolicy">VendorInvoiceLineMatchingPolicy</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceLineMatchingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingMaterialGroupId name="PackingMaterialGroupId">PackingMaterialGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingMaterialGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BestBeforePeriodDays name="BestBeforePeriodDays">BestBeforePeriodDays</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BestBeforePeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightAllocationGroupId name="FreightAllocationGroupId">FreightAllocationGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightAllocationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRebateProductGroupId name="SalesRebateProductGroupId">SalesRebateProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRebateProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PotencyBaseAttributeValueEntryEvent name="PotencyBaseAttributeValueEntryEvent">PotencyBaseAttributeValueEntryEvent</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PotencyBaseAttributeValueEntryEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShelfAdvicePeriodDays name="ShelfAdvicePeriodDays">ShelfAdvicePeriodDays</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShelfAdvicePeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShelfLifePeriodDays name="ShelfLifePeriodDays">ShelfLifePeriodDays</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShelfLifePeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PotencyBaseAttibuteTargetValue name="PotencyBaseAttibuteTargetValue">PotencyBaseAttibuteTargetValue</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PotencyBaseAttibuteTargetValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovedVendorCheckMethod name="ApprovedVendorCheckMethod">ApprovedVendorCheckMethod</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovedVendorCheckMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPhantom name="IsPhantom">IsPhantom</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPhantom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlanningFormulaItemNumber name="PlanningFormulaItemNumber">PlanningFormulaItemNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlanningFormulaItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionType name="ProductionType">ProductionType</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#YieldPercentage name="YieldPercentage">YieldPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#PrimaryVendorAccountNumber name="PrimaryVendorAccountNumber">PrimaryVendorAccountNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionGroupId name="ProductionGroupId">ProductionGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#NecessaryProductionWorkingTimeSchedulingPropertyId name="NecessaryProductionWorkingTimeSchedulingPropertyId">NecessaryProductionWorkingTimeSchedulingPropertyId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NecessaryProductionWorkingTimeSchedulingPropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchasePriceAutomaticallyUpdated name="IsPurchasePriceAutomaticallyUpdated">IsPurchasePriceAutomaticallyUpdated</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchasePriceAutomaticallyUpdated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCoverageGroupId name="ProductCoverageGroupId">ProductCoverageGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCoverageGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceCalculationModel name="SalesPriceCalculationModel">SalesPriceCalculationModel</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceCalculationModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseSalesPriceSource name="BaseSalesPriceSource">BaseSalesPriceSource</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseSalesPriceSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceCalculationContributionRatio name="SalesPriceCalculationContributionRatio">SalesPriceCalculationContributionRatio</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceCalculationContributionRatio attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceCalculationChargesPercentage name="SalesPriceCalculationChargesPercentage">SalesPriceCalculationChargesPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceCalculationChargesPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstantScrapQuantity name="ConstantScrapQuantity">ConstantScrapQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstantScrapQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariableScrapPercentage name="VariableScrapPercentage">VariableScrapPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariableScrapPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerialNumberGroupCode name="SerialNumberGroupCode">SerialNumberGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerialNumberGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAndReceivingSortOrderCode name="ShippingAndReceivingSortOrderCode">ShippingAndReceivingSortOrderCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAndReceivingSortOrderCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductConfigurationId name="DefaultProductConfigurationId">DefaultProductConfigurationId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductColorId name="DefaultProductColorId">DefaultProductColorId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductSizeId name="DefaultProductSizeId">DefaultProductSizeId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductStyleId name="DefaultProductStyleId">DefaultProductStyleId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductVersionId name="DefaultProductVersionId">DefaultProductVersionId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TareProductWeight name="TareProductWeight">TareProductWeight</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TareProductWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingDutyQuantity name="PackingDutyQuantity">PackingDutyQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingDutyQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArrivalHandlingTime name="ArrivalHandlingTime">ArrivalHandlingTime</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArrivalHandlingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumPickQuantity name="MaximumPickQuantity">MaximumPickQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumPickQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageClassId name="PackageClassId">PackageClassId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackSizeCategoryId name="PackSizeCategoryId">PackSizeCategoryId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackSizeCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalDimensionGroupId name="PhysicalDimensionGroupId">PhysicalDimensionGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalDimensionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillWorkCenterPickingAllowNegativeInventory name="WillWorkCenterPickingAllowNegativeInventory">WillWorkCenterPickingAllowNegativeInventory</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWorkCenterPickingAllowNegativeInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReceivingQuantity name="DefaultReceivingQuantity">DefaultReceivingQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReceivingQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseMobileDeviceDescriptionLine1 name="WarehouseMobileDeviceDescriptionLine1">WarehouseMobileDeviceDescriptionLine1</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseMobileDeviceDescriptionLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseMobileDeviceDescriptionLine2 name="WarehouseMobileDeviceDescriptionLine2">WarehouseMobileDeviceDescriptionLine2</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseMobileDeviceDescriptionLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitConversionSequenceGroupId name="UnitConversionSequenceGroupId">UnitConversionSequenceGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitConversionSequenceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RawMaterialPickingPrinciple name="RawMaterialPickingPrinciple">RawMaterialPickingPrinciple</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RawMaterialPickingPrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightUnitSymbol name="CatchWeightUnitSymbol">CatchWeightUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#MaximumCatchWeightQuantity name="MaximumCatchWeightQuantity">MaximumCatchWeightQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumCatchWeightQuantity name="MinimumCatchWeightQuantity">MinimumCatchWeightQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesPriceAdjustmentAllowed name="IsSalesPriceAdjustmentAllowed">IsSalesPriceAdjustmentAllowed</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesPriceAdjustmentAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContinuityEventDuration name="ContinuityEventDuration">ContinuityEventDuration</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContinuityEventDuration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContinuityScheduleId name="ContinuityScheduleId">ContinuityScheduleId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContinuityScheduleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRestrictedForCoupons name="IsRestrictedForCoupons">IsRestrictedForCoupons</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRestrictedForCoupons attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDirectDeliveryWarehouse name="DefaultDirectDeliveryWarehouse">DefaultDirectDeliveryWarehouse</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDirectDeliveryWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveredDirectly name="IsDeliveredDirectly">IsDeliveredDirectly</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveredDirectly attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExemptFromAutomaticNotificationAndCancellation name="IsExemptFromAutomaticNotificationAndCancellation">IsExemptFromAutomaticNotificationAndCancellation</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromAutomaticNotificationAndCancellation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInstallmentEligible name="IsInstallmentEligible">IsInstallmentEligible</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInstallmentEligible attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPickingWorkbenchApplyBoxingLogic name="WillPickingWorkbenchApplyBoxingLogic">WillPickingWorkbenchApplyBoxingLogic</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPickingWorkbenchApplyBoxingLogic attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseRebateProductGroupId name="PurchaseRebateProductGroupId">PurchaseRebateProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRebateProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SellEndDate name="SellEndDate">SellEndDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SellEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SellStartDate name="SellStartDate">SellStartDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SellStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsShipAloneEnabled name="IsShipAloneEnabled">IsShipAloneEnabled</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsShipAloneEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipStartDate name="ShipStartDate">ShipStartDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#BarcodeSetupId name="BarcodeSetupId">BarcodeSetupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarcodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComparisonPriceBaseUnitSymbol name="ComparisonPriceBaseUnitSymbol">ComparisonPriceBaseUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComparisonPriceBaseUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsScaleProduct name="IsScaleProduct">IsScaleProduct</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsScaleProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPOSRegistrationBlocked name="IsPOSRegistrationBlocked">IsPOSRegistrationBlocked</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPOSRegistrationBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#POSRegistrationBlockedDate name="POSRegistrationBlockedDate">POSRegistrationBlockedDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the POSRegistrationBlockedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#POSRegistrationPlannedBlockedDate name="POSRegistrationPlannedBlockedDate">POSRegistrationPlannedBlockedDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the POSRegistrationPlannedBlockedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#POSRegistrationActivationDate name="POSRegistrationActivationDate">POSRegistrationActivationDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the POSRegistrationActivationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyInPriceRequirementsAtPOSRegister name="KeyInPriceRequirementsAtPOSRegister">KeyInPriceRequirementsAtPOSRegister</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyInPriceRequirementsAtPOSRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyInQuantityRequirementsAtPOSRegister name="KeyInQuantityRequirementsAtPOSRegister">KeyInQuantityRequirementsAtPOSRegister</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyInQuantityRequirementsAtPOSRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MustKeyInCommentAtPOSRegister name="MustKeyInCommentAtPOSRegister">MustKeyInCommentAtPOSRegister</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MustKeyInCommentAtPOSRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsZeroPricePOSRegistrationAllowed name="IsZeroPricePOSRegistrationAllowed">IsZeroPricePOSRegistrationAllowed</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsZeroPricePOSRegistrationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDiscountPOSRegistrationProhibited name="IsDiscountPOSRegistrationProhibited">IsDiscountPOSRegistrationProhibited</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDiscountPOSRegistrationProhibited attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPOSRegistrationQuantityNegative name="IsPOSRegistrationQuantityNegative">IsPOSRegistrationQuantityNegative</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPOSRegistrationQuantityNegative attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductLifeCycleSeasonCode name="ProductLifeCycleSeasonCode">ProductLifeCycleSeasonCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductLifeCycleSeasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductLifeCycleValidFromDate name="ProductLifeCycleValidFromDate">ProductLifeCycleValidFromDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductLifeCycleValidFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductLifeCycleValidToDate name="ProductLifeCycleValidToDate">ProductLifeCycleValidToDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductLifeCycleValidToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVariantShelfLabelsPrintingEnabled name="IsVariantShelfLabelsPrintingEnabled">IsVariantShelfLabelsPrintingEnabled</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVariantShelfLabelsPrintingEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderOverdeliveryPercentage name="TransferOrderOverdeliveryPercentage">TransferOrderOverdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderOverdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderUnderdeliveryPercentage name="TransferOrderUnderdeliveryPercentage">TransferOrderUnderdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderUnderdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCost name="UnitCost">UnitCost</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCostDate name="UnitCostDate">UnitCostDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCostDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCostQuantity name="UnitCostQuantity">UnitCostQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCostQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsUnitCostIncludingCharges name="IsUnitCostIncludingCharges">IsUnitCostIncludingCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUnitCostIncludingCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedCostCharges name="FixedCostCharges">FixedCostCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedCostCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostChargesQuantity name="CostChargesQuantity">CostChargesQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostChargesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryUnitSymbol name="InventoryUnitSymbol">InventoryUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesUsageBlocked name="IsIntercompanySalesUsageBlocked">IsIntercompanySalesUsageBlocked</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesUsageBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSalesTaxItemGroupCode name="SalesSalesTaxItemGroupCode">SalesSalesTaxItemGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTotalSalesDiscountCalculationIncludeProduct name="WillTotalSalesDiscountCalculationIncludeProduct">WillTotalSalesDiscountCalculationIncludeProduct</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTotalSalesDiscountCalculationIncludeProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineDiscountProductGroupCode name="SalesLineDiscountProductGroupCode">SalesLineDiscountProductGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesMultilineDiscountProductGroupCode name="SalesMultilineDiscountProductGroupCode">SalesMultilineDiscountProductGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesMultilineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSupplementaryProductProductGroupId name="SalesSupplementaryProductProductGroupId">SalesSupplementaryProductProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSupplementaryProductProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesChargeProductGroupId name="SalesChargeProductGroupId">SalesChargeProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesChargeProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOverdeliveryPercentage name="SalesOverdeliveryPercentage">SalesOverdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOverdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnderdeliveryPercentage name="SalesUnderdeliveryPercentage">SalesUnderdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnderdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPricingPrecision name="SalesPricingPrecision">SalesPricingPrecision</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPricingPrecision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceDate name="SalesPriceDate">SalesPriceDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceQuantity name="SalesPriceQuantity">SalesPriceQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitSymbol name="SalesUnitSymbol">SalesUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesPriceIncludingCharges name="IsSalesPriceIncludingCharges">IsSalesPriceIncludingCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesPriceIncludingCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedSalesPriceCharges name="FixedSalesPriceCharges">FixedSalesPriceCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedSalesPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesChargesQuantity name="SalesChargesQuantity">SalesChargesQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesChargesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseSalesTaxItemGroupCode name="PurchaseSalesTaxItemGroupCode">PurchaseSalesTaxItemGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseSalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseUsageBlocked name="IsIntercompanyPurchaseUsageBlocked">IsIntercompanyPurchaseUsageBlocked</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseUsageBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseLineDiscountProductGroupCode name="PurchaseLineDiscountProductGroupCode">PurchaseLineDiscountProductGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseLineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseMultilineDiscountProductGroupCode name="PurchaseMultilineDiscountProductGroupCode">PurchaseMultilineDiscountProductGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseMultilineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTotalPurchaseDiscountCalculationIncludeProduct name="WillTotalPurchaseDiscountCalculationIncludeProduct">WillTotalPurchaseDiscountCalculationIncludeProduct</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTotalPurchaseDiscountCalculationIncludeProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseSupplementaryProductProductGroupId name="PurchaseSupplementaryProductProductGroupId">PurchaseSupplementaryProductProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseSupplementaryProductProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOverdeliveryPercentage name="PurchaseOverdeliveryPercentage">PurchaseOverdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOverdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseUnderdeliveryPercentage name="PurchaseUnderdeliveryPercentage">PurchaseUnderdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseUnderdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePricingPrecision name="PurchasePricingPrecision">PurchasePricingPrecision</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePricingPrecision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePrice name="PurchasePrice">PurchasePrice</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#PurchasePriceDate name="PurchasePriceDate">PurchasePriceDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceQuantity name="PurchasePriceQuantity">PurchasePriceQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#PurchaseUnitSymbol name="PurchaseUnitSymbol">PurchaseUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#PurchaseChargeProductGroupId name="PurchaseChargeProductGroupId">PurchaseChargeProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseChargeProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchasePriceIncludingCharges name="IsPurchasePriceIncludingCharges">IsPurchasePriceIncludingCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchasePriceIncludingCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedPurchasePriceCharges name="FixedPurchasePriceCharges">FixedPurchasePriceCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase price charges</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedPurchasePriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase price charges</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseChargesQuantity name="PurchaseChargesQuantity">PurchaseChargesQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseChargesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreTransportationManagementProcessesEnabled name="AreTransportationManagementProcessesEnabled">AreTransportationManagementProcessesEnabled</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreTransportationManagementProcessesEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatCommodityCode name="IntrastatCommodityCode">IntrastatCommodityCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatCommodityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatChargePercentage name="IntrastatChargePercentage">IntrastatChargePercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatChargePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginCountryRegionId name="OriginCountryRegionId">OriginCountryRegionId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#ApproximateSalesTaxPercentage name="ApproximateSalesTaxPercentage">ApproximateSalesTaxPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApproximateSalesTaxPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemFiscalClassificationExceptionCode name="ItemFiscalClassificationExceptionCode">ItemFiscalClassificationExceptionCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemFiscalClassificationExceptionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductFiscalInformationType name="ProductFiscalInformationType">ProductFiscalInformationType</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal product type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductFiscalInformationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal product type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsICMSTaxAppliedOnService name="IsICMSTaxAppliedOnService">IsICMSTaxAppliedOnService</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsICMSTaxAppliedOnService attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductTaxationOrigin name="ProductTaxationOrigin">ProductTaxationOrigin</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductTaxationOrigin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemFiscalClassificationCode name="ItemFiscalClassificationCode">ItemFiscalClassificationCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemFiscalClassificationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceFiscalInformationCode name="ServiceFiscalInformationCode">ServiceFiscalInformationCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#IsSalesWithholdingTaxCalculated name="IsSalesWithholdingTaxCalculated">IsSalesWithholdingTaxCalculated</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculate withholding sales tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesWithholdingTaxCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculate withholding sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesItemWithholdingTaxGroupCode name="SalesItemWithholdingTaxGroupCode">SalesItemWithholdingTaxGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesItemWithholdingTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchaseWithholdingTaxCalculated name="IsPurchaseWithholdingTaxCalculated">IsPurchaseWithholdingTaxCalculated</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculate withholding purchase tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseWithholdingTaxCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculate withholding purchase tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseItemWithholdingTaxGroupCode name="PurchaseItemWithholdingTaxGroupCode">PurchaseItemWithholdingTaxGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseItemWithholdingTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesGSTReliefCategoryCode name="SalesGSTReliefCategoryCode">SalesGSTReliefCategoryCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales GST relief category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesGSTReliefCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales GST relief category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseGSTReliefCategoryCode name="PurchaseGSTReliefCategoryCode">PurchaseGSTReliefCategoryCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase GST relief category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseGSTReliefCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase GST relief category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryGSTReliefCategoryCode name="InventoryGSTReliefCategoryCode">InventoryGSTReliefCategoryCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory GST relief category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryGSTReliefCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory GST relief category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NGPCode name="NGPCode">NGPCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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

### <a href=#CostCalculationBOMLevel name="CostCalculationBOMLevel">CostCalculationBOMLevel</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostCalculationBOMLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductMasterRelationshipId name="Relationship_ProductMasterRelationshipId">Relationship_ProductMasterRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductMasterRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_EcoResReleasedProductV2EntityRelationshipId name="BackingTable_EcoResReleasedProductV2EntityRelationshipId">BackingTable_EcoResReleasedProductV2EntityRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResReleasedProductV2EntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductMasterV2Entity (this entity)  

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
