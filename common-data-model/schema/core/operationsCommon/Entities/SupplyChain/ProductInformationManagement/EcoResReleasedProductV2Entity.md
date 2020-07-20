---
title: EcoResReleasedProductV2Entity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Released products V2 in ProductInformationManagement(EcoResReleasedProductV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResReleasedProductV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Released products V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductType](#ProductType)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductSubType](#ProductSubType)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ServiceType](#ServiceType)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductNumber](#ProductNumber)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductSearchName](#ProductSearchName)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SearchName](#SearchName)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductGroupId](#ProductGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ItemModelGroupId](#ItemModelGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[StorageDimensionGroupName](#StorageDimensionGroupName)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TrackingDimensionGroupName](#TrackingDimensionGroupName)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[StorageDimensionGroupRecId](#StorageDimensionGroupRecId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TrackingDimensionGroupRecId](#TrackingDimensionGroupRecId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[InventoryReservationHierarchyName](#InventoryReservationHierarchyName)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ReservationHierarchyRecId](#ReservationHierarchyRecId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultOrderType](#DefaultOrderType)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[MarginABCCode](#MarginABCCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RevenueABCCode](#RevenueABCCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CarryingCostABCCode](#CarryingCostABCCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ValueABCCode](#ValueABCCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[AlternativeProductUsageCondition](#AlternativeProductUsageCondition)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[AlternativeProductConfigurationId](#AlternativeProductConfigurationId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[AlternativeProductColorId](#AlternativeProductColorId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[AlternativeProductSizeId](#AlternativeProductSizeId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[AlternativeProductStyleId](#AlternativeProductStyleId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[AlternativeProductVersionId](#AlternativeProductVersionId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[AlternativeItemNumber](#AlternativeItemNumber)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WillInventoryIssueAutomaticallyReportAsFinished](#WillInventoryIssueAutomaticallyReportAsFinished)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[BatchMergeDateCalculationMethod](#BatchMergeDateCalculationMethod)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[BatchNumberGroupCode](#BatchNumberGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CostCalculationGroupId](#CostCalculationGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[BOMLevel](#BOMLevel)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[BOMUnitSymbol](#BOMUnitSymbol)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[FlushingPrinciple](#FlushingPrinciple)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WillInventoryReceiptIgnoreFlushingPrinciple](#WillInventoryReceiptIgnoreFlushingPrinciple)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CommissionProductGroupId](#CommissionProductGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CostGroupId](#CostGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsUnitCostAutomaticallyUpdated](#IsUnitCostAutomaticallyUpdated)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductionConsumptionDensityConversionFactor](#ProductionConsumptionDensityConversionFactor)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductionConsumptionDepthConversionFactor](#ProductionConsumptionDepthConversionFactor)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductionConsumptionWidthConversionFactor](#ProductionConsumptionWidthConversionFactor)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductionConsumptionHeightConversionFactor](#ProductionConsumptionHeightConversionFactor)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[GrossDepth](#GrossDepth)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[GrossProductHeight](#GrossProductHeight)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[GrossProductWidth](#GrossProductWidth)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductVolume](#ProductVolume)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[NetProductWeight](#NetProductWeight)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[BuyerGroupId](#BuyerGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsUnitCostProductVariantSpecific](#IsUnitCostProductVariantSpecific)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchasePriceToleranceGroupId](#PurchasePriceToleranceGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[VendorInvoiceLineMatchingPolicy](#VendorInvoiceLineMatchingPolicy)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PackingMaterialGroupId](#PackingMaterialGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[BestBeforePeriodDays](#BestBeforePeriodDays)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[FreightAllocationGroupId](#FreightAllocationGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesRebateProductGroupId](#SalesRebateProductGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PotencyBaseAttributeValueEntryEvent](#PotencyBaseAttributeValueEntryEvent)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ShelfAdvicePeriodDays](#ShelfAdvicePeriodDays)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ShelfLifePeriodDays](#ShelfLifePeriodDays)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PotencyBaseAttibuteTargetValue](#PotencyBaseAttibuteTargetValue)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ApprovedVendorCheckMethod](#ApprovedVendorCheckMethod)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsPhantom](#IsPhantom)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PlanningFormulaItemNumber](#PlanningFormulaItemNumber)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductionType](#ProductionType)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[YieldPercentage](#YieldPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PrimaryVendorAccountNumber](#PrimaryVendorAccountNumber)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductionGroupId](#ProductionGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductionPoolId](#ProductionPoolId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[NecessaryProductionWorkingTimeSchedulingPropertyId](#NecessaryProductionWorkingTimeSchedulingPropertyId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsPurchasePriceAutomaticallyUpdated](#IsPurchasePriceAutomaticallyUpdated)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductCoverageGroupId](#ProductCoverageGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesPriceCalculationModel](#SalesPriceCalculationModel)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[BaseSalesPriceSource](#BaseSalesPriceSource)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesPriceCalculationContributionRatio](#SalesPriceCalculationContributionRatio)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesPriceCalculationChargesPercentage](#SalesPriceCalculationChargesPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ConstantScrapQuantity](#ConstantScrapQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[VariableScrapPercentage](#VariableScrapPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SerialNumberGroupCode](#SerialNumberGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ShippingAndReceivingSortOrderCode](#ShippingAndReceivingSortOrderCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultProductConfigurationId](#DefaultProductConfigurationId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultProductColorId](#DefaultProductColorId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultProductSizeId](#DefaultProductSizeId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultProductStyleId](#DefaultProductStyleId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultProductVersionId](#DefaultProductVersionId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TareProductWeight](#TareProductWeight)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PackingDutyQuantity](#PackingDutyQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ArrivalHandlingTime](#ArrivalHandlingTime)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[MaximumPickQuantity](#MaximumPickQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PackageClassId](#PackageClassId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PackSizeCategoryId](#PackSizeCategoryId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PhysicalDimensionGroupId](#PhysicalDimensionGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WillWorkCenterPickingAllowNegativeInventory](#WillWorkCenterPickingAllowNegativeInventory)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultReceivingQuantity](#DefaultReceivingQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WarehouseMobileDeviceDescriptionLine1](#WarehouseMobileDeviceDescriptionLine1)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WarehouseMobileDeviceDescriptionLine2](#WarehouseMobileDeviceDescriptionLine2)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RawMaterialPickingPrinciple](#RawMaterialPickingPrinciple)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[UnitConversionSequenceGroupId](#UnitConversionSequenceGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CatchWeightUnitSymbol](#CatchWeightUnitSymbol)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[MaximumCatchWeightQuantity](#MaximumCatchWeightQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[MinimumCatchWeightQuantity](#MinimumCatchWeightQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsSalesPriceAdjustmentAllowed](#IsSalesPriceAdjustmentAllowed)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ContinuityEventDuration](#ContinuityEventDuration)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ContinuityScheduleId](#ContinuityScheduleId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsRestrictedForCoupons](#IsRestrictedForCoupons)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultDirectDeliveryWarehouse](#DefaultDirectDeliveryWarehouse)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsDeliveredDirectly](#IsDeliveredDirectly)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsExemptFromAutomaticNotificationAndCancellation](#IsExemptFromAutomaticNotificationAndCancellation)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsInstallmentEligible](#IsInstallmentEligible)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WillPickingWorkbenchApplyBoxingLogic](#WillPickingWorkbenchApplyBoxingLogic)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseRebateProductGroupId](#PurchaseRebateProductGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SellEndDate](#SellEndDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SellStartDate](#SellStartDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsShipAloneEnabled](#IsShipAloneEnabled)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ShipStartDate](#ShipStartDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[BarcodeSetupId](#BarcodeSetupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ComparisonPriceBaseUnitSymbol](#ComparisonPriceBaseUnitSymbol)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsScaleProduct](#IsScaleProduct)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsPOSRegistrationBlocked](#IsPOSRegistrationBlocked)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[POSRegistrationBlockedDate](#POSRegistrationBlockedDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[POSRegistrationPlannedBlockedDate](#POSRegistrationPlannedBlockedDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[POSRegistrationActivationDate](#POSRegistrationActivationDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[KeyInPriceRequirementsAtPOSRegister](#KeyInPriceRequirementsAtPOSRegister)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[KeyInQuantityRequirementsAtPOSRegister](#KeyInQuantityRequirementsAtPOSRegister)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[MustKeyInCommentAtPOSRegister](#MustKeyInCommentAtPOSRegister)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsZeroPricePOSRegistrationAllowed](#IsZeroPricePOSRegistrationAllowed)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsDiscountPOSRegistrationProhibited](#IsDiscountPOSRegistrationProhibited)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsPOSRegistrationQuantityNegative](#IsPOSRegistrationQuantityNegative)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductLifeCycleSeasonCode](#ProductLifeCycleSeasonCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductLifeCycleValidFromDate](#ProductLifeCycleValidFromDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductLifeCycleValidToDate](#ProductLifeCycleValidToDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsVariantShelfLabelsPrintingEnabled](#IsVariantShelfLabelsPrintingEnabled)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TransferOrderOverdeliveryPercentage](#TransferOrderOverdeliveryPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TransferOrderUnderdeliveryPercentage](#TransferOrderUnderdeliveryPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[UnitCost](#UnitCost)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[UnitCostDate](#UnitCostDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[UnitCostQuantity](#UnitCostQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsUnitCostIncludingCharges](#IsUnitCostIncludingCharges)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[FixedCostCharges](#FixedCostCharges)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CostChargesQuantity](#CostChargesQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[InventoryUnitSymbol](#InventoryUnitSymbol)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsIntercompanySalesUsageBlocked](#IsIntercompanySalesUsageBlocked)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesSalesTaxItemGroupCode](#SalesSalesTaxItemGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WillTotalSalesDiscountCalculationIncludeProduct](#WillTotalSalesDiscountCalculationIncludeProduct)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesLineDiscountProductGroupCode](#SalesLineDiscountProductGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesMultilineDiscountProductGroupCode](#SalesMultilineDiscountProductGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesSupplementaryProductProductGroupId](#SalesSupplementaryProductProductGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesChargeProductGroupId](#SalesChargeProductGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesOverdeliveryPercentage](#SalesOverdeliveryPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesUnderdeliveryPercentage](#SalesUnderdeliveryPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesPricingPrecision](#SalesPricingPrecision)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesPrice](#SalesPrice)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesPriceDate](#SalesPriceDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesPriceQuantity](#SalesPriceQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesUnitSymbol](#SalesUnitSymbol)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsSalesPriceIncludingCharges](#IsSalesPriceIncludingCharges)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[FixedSalesPriceCharges](#FixedSalesPriceCharges)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesChargesQuantity](#SalesChargesQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseSalesTaxItemGroupCode](#PurchaseSalesTaxItemGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsIntercompanyPurchaseUsageBlocked](#IsIntercompanyPurchaseUsageBlocked)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseLineDiscountProductGroupCode](#PurchaseLineDiscountProductGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseMultilineDiscountProductGroupCode](#PurchaseMultilineDiscountProductGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WillTotalPurchaseDiscountCalculationIncludeProduct](#WillTotalPurchaseDiscountCalculationIncludeProduct)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseSupplementaryProductProductGroupId](#PurchaseSupplementaryProductProductGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseOverdeliveryPercentage](#PurchaseOverdeliveryPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseUnderdeliveryPercentage](#PurchaseUnderdeliveryPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchasePricingPrecision](#PurchasePricingPrecision)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchasePrice](#PurchasePrice)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchasePriceDate](#PurchasePriceDate)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchasePriceQuantity](#PurchasePriceQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseUnitSymbol](#PurchaseUnitSymbol)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseChargeProductGroupId](#PurchaseChargeProductGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsPurchasePriceIncludingCharges](#IsPurchasePriceIncludingCharges)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[FixedPurchasePriceCharges](#FixedPurchasePriceCharges)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseChargesQuantity](#PurchaseChargesQuantity)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[AreTransportationManagementProcessesEnabled](#AreTransportationManagementProcessesEnabled)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IntrastatCommodityCode](#IntrastatCommodityCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IntrastatChargePercentage](#IntrastatChargePercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[OriginCountryRegionId](#OriginCountryRegionId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[OriginStateId](#OriginStateId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ApproximateSalesTaxPercentage](#ApproximateSalesTaxPercentage)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ItemFiscalClassificationExceptionCode](#ItemFiscalClassificationExceptionCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductFiscalInformationType](#ProductFiscalInformationType)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsICMSTaxAppliedOnService](#IsICMSTaxAppliedOnService)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductTaxationOrigin](#ProductTaxationOrigin)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ItemFiscalClassificationCode](#ItemFiscalClassificationCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ServiceFiscalInformationCode](#ServiceFiscalInformationCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsSalesWithholdingTaxCalculated](#IsSalesWithholdingTaxCalculated)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesItemWithholdingTaxGroupCode](#SalesItemWithholdingTaxGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsPurchaseWithholdingTaxCalculated](#IsPurchaseWithholdingTaxCalculated)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseItemWithholdingTaxGroupCode](#PurchaseItemWithholdingTaxGroupCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesGSTReliefCategoryCode](#SalesGSTReliefCategoryCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PurchaseGSTReliefCategoryCode](#PurchaseGSTReliefCategoryCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[InventoryGSTReliefCategoryCode](#InventoryGSTReliefCategoryCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[NGPCode](#NGPCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TaxGSTReliefCategorySales](#TaxGSTReliefCategorySales)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TaxGSTReliefCategoryInvent](#TaxGSTReliefCategoryInvent)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TaxGSTReliefCategoryPurch](#TaxGSTReliefCategoryPurch)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SADGroup](#SADGroup)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[PKWiUCode](#PKWiUCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsManualDiscountPOSRegistrationProhibited](#IsManualDiscountPOSRegistrationProhibited)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[InventoryCountingReasonCodePolicyName](#InventoryCountingReasonCodePolicyName)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[InventCountingReasonCodePolicyRecId](#InventCountingReasonCodePolicyRecId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[HSNCode](#HSNCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ServiceAccountingCode](#ServiceAccountingCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Exempt](#Exempt)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CustomsImportTariffCode](#CustomsImportTariffCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CustomsExportTariffCode](#CustomsExportTariffCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SATCode](#SATCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ScaleIndicator](#ScaleIndicator)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CNPJ](#CNPJ)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TaxSubstitutionCode](#TaxSubstitutionCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductLifecycleStateId](#ProductLifecycleStateId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[UpdateProductVariantLifecycleState](#UpdateProductVariantLifecycleState)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CatchWeightItemHandlingPolicyName](#CatchWeightItemHandlingPolicyName)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[FirstProductFilterCode](#FirstProductFilterCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SecondProductFilterCode](#SecondProductFilterCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ThirdProductFilterCode](#ThirdProductFilterCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[FourthProductFilterCode](#FourthProductFilterCode)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[FirstProductFilterGroupId](#FirstProductFilterGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SecondProductFilterGroupId](#SecondProductFilterGroupId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[NonGST](#NonGST)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[TaxRateType](#TaxRateType)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[ProductDimensionGroupName](#ProductDimensionGroupName)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsCatchWeightProduct](#IsCatchWeightProduct)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsRetailDiscountPOSRegistrationProhibited](#IsRetailDiscountPOSRegistrationProhibited)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[IsTenderDiscountPOSRegistrationProhibited](#IsTenderDiscountPOSRegistrationProhibited)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WarrantablePriceRangeBaseType](#WarrantablePriceRangeBaseType)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[LowerWarrantablePriceRangeLimit](#LowerWarrantablePriceRangeLimit)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[UpperWarrantablePriceRangeLimit](#UpperWarrantablePriceRangeLimit)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WarrantyDurationTime](#WarrantyDurationTime)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[WarrantyDurationTimeUnit](#WarrantyDurationTimeUnit)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[CostCalculationBOMLevel](#CostCalculationBOMLevel)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesRetailInventoryAvailabilityBuffer](#SalesRetailInventoryAvailabilityBuffer)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[SalesRetailInventoryAvailabilityLevelProfile](#SalesRetailInventoryAvailabilityLevelProfile)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RevRecRevenueType](#RevRecRevenueType)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RevRecDefaultRevenueRecognitionSchedule](#RevRecDefaultRevenueRecognitionSchedule)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RevRecBundle](#RevRecBundle)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RevRecExcludeFromCarveOut](#RevRecExcludeFromCarveOut)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RevRecMedianPrice](#RevRecMedianPrice)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RevRecMedianPriceMaximumTolerance](#RevRecMedianPriceMaximumTolerance)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RevRecMedianPriceMinimumTolerance](#RevRecMedianPriceMinimumTolerance)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[RevRecRevenueRecognitionEnabled](#RevRecRevenueRecognitionEnabled)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId](#Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_EcoResProductV2EntityRelationshipId](#Relationship_EcoResProductV2EntityRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_InventoryCountingReasonCodePolicyRelationshipId](#Relationship_InventoryCountingReasonCodePolicyRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_StorageDimensionGroupRelationshipId](#Relationship_StorageDimensionGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_TrackingDimensionGroupRelationshipId](#Relationship_TrackingDimensionGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_GSTReliefCategoryRelationshipId](#Relationship_GSTReliefCategoryRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_NGPCodeRelationshipId](#Relationship_NGPCodeRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_TaxServiceAccountingCodeRelationshipId](#Relationship_TaxServiceAccountingCodeRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_InventoryReservationHierarchyRelationshipId](#Relationship_InventoryReservationHierarchyRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_AlternativeProductConfigurationRelationshipId](#Relationship_AlternativeProductConfigurationRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_AlternativeProductColorRelationshipId](#Relationship_AlternativeProductColorRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_AlternativeProductSizeRelationshipId](#Relationship_AlternativeProductSizeRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_AlternativeProductStyleRelationshipId](#Relationship_AlternativeProductStyleRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_AlternativeProductVersionRelationshipId](#Relationship_AlternativeProductVersionRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_BatchNumberGroupRelationshipId](#Relationship_BatchNumberGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_CostCalculationGroupRelationshipId](#Relationship_CostCalculationGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_BOMUnitOfMeasureRelationshipId](#Relationship_BOMUnitOfMeasureRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_CommissionProductGroupRelationshipId](#Relationship_CommissionProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_CostGroupRelationshipId](#Relationship_CostGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_BuyerGroupRelationshipId](#Relationship_BuyerGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PurchasePriceToleranceGroupRelationshipId](#Relationship_PurchasePriceToleranceGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PackingMaterialGroupRelationshipId](#Relationship_PackingMaterialGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_SalesRebateProductFreightGroupRelationshipId](#Relationship_SalesRebateProductFreightGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_SalesRebateProductGroupRelationshipId](#Relationship_SalesRebateProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PrimaryVendorV2RelationshipId](#Relationship_PrimaryVendorV2RelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_ProductionGroupRelationshipId](#Relationship_ProductionGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_ProductionPoolRelationshipId](#Relationship_ProductionPoolRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_ProjectCategoryRelationshipId](#Relationship_ProjectCategoryRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_ProductCoverageGroupRelationshipId](#Relationship_ProductCoverageGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_SerialNumberGroupRelationshipId](#Relationship_SerialNumberGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_DefaultProductStyleRelationshipId](#Relationship_DefaultProductStyleRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_DefaultProductVersionRelationshipId](#Relationship_DefaultProductVersionRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_DefaultProductSizeRelationshipId](#Relationship_DefaultProductSizeRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_DefaultProductColorRelationshipId](#Relationship_DefaultProductColorRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_DefaultProductConfigurationRelationshipId](#Relationship_DefaultProductConfigurationRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_WarehousePackageClassRelationshipId](#Relationship_WarehousePackageClassRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PackSizeCategoryRelationshipId](#Relationship_PackSizeCategoryRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PhysicalDimensionGroupRelationshipId](#Relationship_PhysicalDimensionGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_UnitOfMeasureConversionSequenceGroupRelationshipId](#Relationship_UnitOfMeasureConversionSequenceGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_CatchWeightUnitOfMeasureRelationshipId](#Relationship_CatchWeightUnitOfMeasureRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PurchaseRebateProductGroupRelationshipId](#Relationship_PurchaseRebateProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_ComparisonPriceBaseUnitOfMeasureRelationshipId](#Relationship_ComparisonPriceBaseUnitOfMeasureRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_SalesSupplementaryProductProductGroupRelationshipId](#Relationship_SalesSupplementaryProductProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_SalesChargeProductGroupRelationshipId](#Relationship_SalesChargeProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_OriginCountryRegionRelationshipId](#Relationship_OriginCountryRegionRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_OriginStateRelationshipId](#Relationship_OriginStateRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_ServiceFiscalInformationCodeRelationshipId](#Relationship_ServiceFiscalInformationCodeRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_FiscalClassificationCodeRelationshipId](#Relationship_FiscalClassificationCodeRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_SalesMultilineDiscountProductGroupRelationshipId](#Relationship_SalesMultilineDiscountProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_SalesLineDiscountProductGroupRelationshipId](#Relationship_SalesLineDiscountProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_InventoryUnitOfMeasureRelationshipId](#Relationship_InventoryUnitOfMeasureRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_ProductGroupRelationshipId](#Relationship_ProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_InventoryPolicyRelationshipId](#Relationship_InventoryPolicyRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_SalesUnitOfMeasureRelationshipId](#Relationship_SalesUnitOfMeasureRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_DefaultDirectDeliveryWarehouseRelationshipId](#Relationship_DefaultDirectDeliveryWarehouseRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PurchaseLineDiscountProductGroupRelationshipId](#Relationship_PurchaseLineDiscountProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PurchaseMultilineDiscountProductGroupRelationshipId](#Relationship_PurchaseMultilineDiscountProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PurchaseSupplementaryProductGroupRelationshipId](#Relationship_PurchaseSupplementaryProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PurchaseUnitOfMeasureRelationshipId](#Relationship_PurchaseUnitOfMeasureRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PurchaseChargeProductGroupRelationshipId](#Relationship_PurchaseChargeProductGroupRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_ItemFiscalClassificationExceptionRelationshipId](#Relationship_ItemFiscalClassificationExceptionRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_ProductLifecycleStateRelationshipId](#Relationship_ProductLifecycleStateRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_CatchWeightItemHandlingPolicyV2RelationshipId](#Relationship_CatchWeightItemHandlingPolicyV2RelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_WHSFirstProductFilterCodeEntityRelationshipId](#Relationship_WHSFirstProductFilterCodeEntityRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_WHSSecondProductFilterCodeEntityRelationshipId](#Relationship_WHSSecondProductFilterCodeEntityRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_WHSThirdProductFilterCodeEntityRelationshipId](#Relationship_WHSThirdProductFilterCodeEntityRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_WHSFourthProductFilterCodeEntityRelationshipId](#Relationship_WHSFourthProductFilterCodeEntityRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_EcoResEveryProductEntityRelationshipId](#Relationship_EcoResEveryProductEntityRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[BackingTable_InventTableRelationshipId](#BackingTable_InventTableRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="EcoResReleasedProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductV2Entity</a>|

### <a href=#ProductType name="ProductType">ProductType</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

### <a href=#ProductSubType name="ProductSubType">ProductSubType</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSubType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceType name="ServiceType">ServiceType</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSearchName name="ProductSearchName">ProductSearchName</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

### <a href=#SearchName name="SearchName">SearchName</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Storage dimension group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Storage dimension group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingDimensionGroupName name="TrackingDimensionGroupName">TrackingDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tracking dimension group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tracking dimension group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StorageDimensionGroupRecId name="StorageDimensionGroupRecId">StorageDimensionGroupRecId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageDimensionGroupRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingDimensionGroupRecId name="TrackingDimensionGroupRecId">TrackingDimensionGroupRecId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingDimensionGroupRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryReservationHierarchyName name="InventoryReservationHierarchyName">InventoryReservationHierarchyName</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reservation hierarchy</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryReservationHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reservation hierarchy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservationHierarchyRecId name="ReservationHierarchyRecId">ReservationHierarchyRecId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationHierarchyRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOrderType name="DefaultOrderType">DefaultOrderType</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>When to use alternative product</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductUsageCondition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>When to use alternative product</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductConfigurationId name="AlternativeProductConfigurationId">AlternativeProductConfigurationId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alternative product configuration</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alternative product configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductColorId name="AlternativeProductColorId">AlternativeProductColorId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alternative product color</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alternative product color</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductSizeId name="AlternativeProductSizeId">AlternativeProductSizeId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alternative product size</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alternative product size</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductStyleId name="AlternativeProductStyleId">AlternativeProductStyleId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alternative product style</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alternative product style</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeProductVersionId name="AlternativeProductVersionId">AlternativeProductVersionId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alternative product version</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alternative product version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeItemNumber name="AlternativeItemNumber">AlternativeItemNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Batch merge date calculation method</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchMergeDateCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch merge date calculation method</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchNumberGroupCode name="BatchNumberGroupCode">BatchNumberGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>BOM level</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>BOM level</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMUnitSymbol name="BOMUnitSymbol">BOMUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ignore flushing principle on receipt</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInventoryReceiptIgnoreFlushingPrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ignore flushing principle on receipt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionProductGroupId name="CommissionProductGroupId">CommissionProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update the product automatically with the latest cost price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUnitCostAutomaticallyUpdated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update the product automatically with the latest cost price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionConsumptionDensityConversionFactor name="ProductionConsumptionDensityConversionFactor">ProductionConsumptionDensityConversionFactor</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Density conversion factor for production consumption</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionConsumptionDensityConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Density conversion factor for production consumption</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionConsumptionDepthConversionFactor name="ProductionConsumptionDepthConversionFactor">ProductionConsumptionDepthConversionFactor</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depth conversion factor for production consumption</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionConsumptionDepthConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depth conversion factor for production consumption</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionConsumptionWidthConversionFactor name="ProductionConsumptionWidthConversionFactor">ProductionConsumptionWidthConversionFactor</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Width conversion factor for production consumption</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionConsumptionWidthConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Width conversion factor for production consumption</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionConsumptionHeightConversionFactor name="ProductionConsumptionHeightConversionFactor">ProductionConsumptionHeightConversionFactor</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Height conversion factor for production consumption</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionConsumptionHeightConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Height conversion factor for production consumption</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossDepth name="GrossDepth">GrossDepth</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase price tolerance group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceToleranceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase price tolerance group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceLineMatchingPolicy name="VendorInvoiceLineMatchingPolicy">VendorInvoiceLineMatchingPolicy</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor invoice line matching policy</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceLineMatchingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor invoice line matching policy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingMaterialGroupId name="PackingMaterialGroupId">PackingMaterialGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer rebate item group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRebateProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer rebate item group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PotencyBaseAttributeValueEntryEvent name="PotencyBaseAttributeValueEntryEvent">PotencyBaseAttributeValueEntryEvent</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record potency base attribute value at</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PotencyBaseAttributeValueEntryEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record potency base attribute value at</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShelfAdvicePeriodDays name="ShelfAdvicePeriodDays">ShelfAdvicePeriodDays</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target value for potency base attribute</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PotencyBaseAttibuteTargetValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target value for potency base attribute</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovedVendorCheckMethod name="ApprovedVendorCheckMethod">ApprovedVendorCheckMethod</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Necessary property when producing the item</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NecessaryProductionWorkingTimeSchedulingPropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Necessary property when producing the item</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchasePriceAutomaticallyUpdated name="IsPurchasePriceAutomaticallyUpdated">IsPurchasePriceAutomaticallyUpdated</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update the product automatically with the latest purchase price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchasePriceAutomaticallyUpdated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update the product automatically with the latest purchase price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCoverageGroupId name="ProductCoverageGroupId">ProductCoverageGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source of base sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseSalesPriceSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source of base sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceCalculationContributionRatio name="SalesPriceCalculationContributionRatio">SalesPriceCalculationContributionRatio</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contribution ratio to be used when calculating sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceCalculationContributionRatio attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contribution ratio to be used when calculating sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceCalculationChargesPercentage name="SalesPriceCalculationChargesPercentage">SalesPriceCalculationChargesPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Charges percentage to be used when calculating sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceCalculationChargesPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Charges percentage to be used when calculating sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstantScrapQuantity name="ConstantScrapQuantity">ConstantScrapQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping and receiving sort code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAndReceivingSortOrderCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping and receiving sort code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductConfigurationId name="DefaultProductConfigurationId">DefaultProductConfigurationId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity of which packing duty is calculated</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingDutyQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity of which packing duty is calculated</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArrivalHandlingTime name="ArrivalHandlingTime">ArrivalHandlingTime</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow negative picking at work center</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWorkCenterPickingAllowNegativeInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow negative picking at work center</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReceivingQuantity name="DefaultReceivingQuantity">DefaultReceivingQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Warehouse mobile device description line 1</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseMobileDeviceDescriptionLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse mobile device description line 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseMobileDeviceDescriptionLine2 name="WarehouseMobileDeviceDescriptionLine2">WarehouseMobileDeviceDescriptionLine2</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Warehouse mobile device description line 2</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseMobileDeviceDescriptionLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse mobile device description line 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RawMaterialPickingPrinciple name="RawMaterialPickingPrinciple">RawMaterialPickingPrinciple</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

### <a href=#UnitConversionSequenceGroupId name="UnitConversionSequenceGroupId">UnitConversionSequenceGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

### <a href=#CatchWeightUnitSymbol name="CatchWeightUnitSymbol">CatchWeightUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow sales price adjustment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesPriceAdjustmentAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow sales price adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContinuityEventDuration name="ContinuityEventDuration">ContinuityEventDuration</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restrict for coupons</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRestrictedForCoupons attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Restrict for coupons</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDirectDeliveryWarehouse name="DefaultDirectDeliveryWarehouse">DefaultDirectDeliveryWarehouse</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default direct delivery warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDirectDeliveryWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default direct delivery warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveredDirectly name="IsDeliveredDirectly">IsDeliveredDirectly</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default financial dimensions</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default financial dimensions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarcodeSetupId name="BarcodeSetupId">BarcodeSetupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comparison price base unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComparisonPriceBaseUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Comparison price base unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsScaleProduct name="IsScaleProduct">IsScaleProduct</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Block at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPOSRegistrationBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Block at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#POSRegistrationBlockedDate name="POSRegistrationBlockedDate">POSRegistrationBlockedDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date when the product was blocked at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the POSRegistrationBlockedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date when the product was blocked at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#POSRegistrationPlannedBlockedDate name="POSRegistrationPlannedBlockedDate">POSRegistrationPlannedBlockedDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date when the product should be blocked at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the POSRegistrationPlannedBlockedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date when the product should be blocked at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#POSRegistrationActivationDate name="POSRegistrationActivationDate">POSRegistrationActivationDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date of activation at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the POSRegistrationActivationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date of activation at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyInPriceRequirementsAtPOSRegister name="KeyInPriceRequirementsAtPOSRegister">KeyInPriceRequirementsAtPOSRegister</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Key in price at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyInPriceRequirementsAtPOSRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Key in price at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyInQuantityRequirementsAtPOSRegister name="KeyInQuantityRequirementsAtPOSRegister">KeyInQuantityRequirementsAtPOSRegister</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Key in quantity at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyInQuantityRequirementsAtPOSRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Key in quantity at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MustKeyInCommentAtPOSRegister name="MustKeyInCommentAtPOSRegister">MustKeyInCommentAtPOSRegister</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Must key in comment at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MustKeyInCommentAtPOSRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Must key in comment at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsZeroPricePOSRegistrationAllowed name="IsZeroPricePOSRegistrationAllowed">IsZeroPricePOSRegistrationAllowed</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow zero price at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsZeroPricePOSRegistrationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow zero price at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDiscountPOSRegistrationProhibited name="IsDiscountPOSRegistrationProhibited">IsDiscountPOSRegistrationProhibited</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No discount allowed at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDiscountPOSRegistrationProhibited attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>No discount allowed at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPOSRegistrationQuantityNegative name="IsPOSRegistrationQuantityNegative">IsPOSRegistrationQuantityNegative</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity becomes negative at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPOSRegistrationQuantityNegative attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity becomes negative at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductLifeCycleSeasonCode name="ProductLifeCycleSeasonCode">ProductLifeCycleSeasonCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product life cycle season</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductLifeCycleSeasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product life cycle season</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductLifeCycleValidFromDate name="ProductLifeCycleValidFromDate">ProductLifeCycleValidFromDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product life cycle valid from</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductLifeCycleValidFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product life cycle valid from</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductLifeCycleValidToDate name="ProductLifeCycleValidToDate">ProductLifeCycleValidToDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product life cycle valid to</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductLifeCycleValidToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product life cycle valid to</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVariantShelfLabelsPrintingEnabled name="IsVariantShelfLabelsPrintingEnabled">IsVariantShelfLabelsPrintingEnabled</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdelivery percentage for transfer orders</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderOverdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overdelivery percentage for transfer orders</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderUnderdeliveryPercentage name="TransferOrderUnderdeliveryPercentage">TransferOrderUnderdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Underdelivery percentage for transfer orders</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderUnderdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Underdelivery percentage for transfer orders</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCost name="UnitCost">UnitCost</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCostDate name="UnitCostDate">UnitCostDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date of cost</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCostDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date of cost</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCostQuantity name="UnitCostQuantity">UnitCostQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCostQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsUnitCostIncludingCharges name="IsUnitCostIncludingCharges">IsUnitCostIncludingCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include charges in cost</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUnitCostIncludingCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include charges in cost</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedCostCharges name="FixedCostCharges">FixedCostCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost charges</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedCostCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost charges</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostChargesQuantity name="CostChargesQuantity">CostChargesQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost charges quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostChargesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost charges quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryUnitSymbol name="InventoryUnitSymbol">InventoryUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesUsageBlocked name="IsIntercompanySalesUsageBlocked">IsIntercompanySalesUsageBlocked</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Block intercompany sales</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesUsageBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Block intercompany sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSalesTaxItemGroupCode name="SalesSalesTaxItemGroupCode">SalesSalesTaxItemGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item sales tax group for sales</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item sales tax group for sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTotalSalesDiscountCalculationIncludeProduct name="WillTotalSalesDiscountCalculationIncludeProduct">WillTotalSalesDiscountCalculationIncludeProduct</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include in total sales discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTotalSalesDiscountCalculationIncludeProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include in total sales discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineDiscountProductGroupCode name="SalesLineDiscountProductGroupCode">SalesLineDiscountProductGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line discount group for sales</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line discount group for sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesMultilineDiscountProductGroupCode name="SalesMultilineDiscountProductGroupCode">SalesMultilineDiscountProductGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Multiline discount group for sales</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesMultilineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Multiline discount group for sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSupplementaryProductProductGroupId name="SalesSupplementaryProductProductGroupId">SalesSupplementaryProductProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Supplementary item group for sales</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSupplementaryProductProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Supplementary item group for sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesChargeProductGroupId name="SalesChargeProductGroupId">SalesChargeProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales charges group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesChargeProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales charges group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOverdeliveryPercentage name="SalesOverdeliveryPercentage">SalesOverdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdelivery percentage for sales</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOverdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overdelivery percentage for sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnderdeliveryPercentage name="SalesUnderdeliveryPercentage">SalesUnderdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Underdelivery percentage for sales</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnderdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Underdelivery percentage for sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPricingPrecision name="SalesPricingPrecision">SalesPricingPrecision</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales pricing precision</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPricingPrecision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales pricing precision</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceDate name="SalesPriceDate">SalesPriceDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date of sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date of sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceQuantity name="SalesPriceQuantity">SalesPriceQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales price quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales price quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitSymbol name="SalesUnitSymbol">SalesUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesPriceIncludingCharges name="IsSalesPriceIncludingCharges">IsSalesPriceIncludingCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include charges in sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesPriceIncludingCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include charges in sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedSalesPriceCharges name="FixedSalesPriceCharges">FixedSalesPriceCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales price charges</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedSalesPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales price charges</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesChargesQuantity name="SalesChargesQuantity">SalesChargesQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales charges quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesChargesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales charges quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseSalesTaxItemGroupCode name="PurchaseSalesTaxItemGroupCode">PurchaseSalesTaxItemGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item sales tax group for purchases</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseSalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item sales tax group for purchases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseUsageBlocked name="IsIntercompanyPurchaseUsageBlocked">IsIntercompanyPurchaseUsageBlocked</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Block intercompany purchase</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseUsageBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Block intercompany purchase</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseLineDiscountProductGroupCode name="PurchaseLineDiscountProductGroupCode">PurchaseLineDiscountProductGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line discount group for purchases</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseLineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line discount group for purchases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseMultilineDiscountProductGroupCode name="PurchaseMultilineDiscountProductGroupCode">PurchaseMultilineDiscountProductGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Multiline discount group for purchases</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseMultilineDiscountProductGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Multiline discount group for purchases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTotalPurchaseDiscountCalculationIncludeProduct name="WillTotalPurchaseDiscountCalculationIncludeProduct">WillTotalPurchaseDiscountCalculationIncludeProduct</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include in total purchase discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTotalPurchaseDiscountCalculationIncludeProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include in total purchase discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseSupplementaryProductProductGroupId name="PurchaseSupplementaryProductProductGroupId">PurchaseSupplementaryProductProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Supplementary item group for purchases</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseSupplementaryProductProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Supplementary item group for purchases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOverdeliveryPercentage name="PurchaseOverdeliveryPercentage">PurchaseOverdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdelivery percentage for purchases</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOverdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overdelivery percentage for purchases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseUnderdeliveryPercentage name="PurchaseUnderdeliveryPercentage">PurchaseUnderdeliveryPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Underdelivery percentage for purchases</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseUnderdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Underdelivery percentage for purchases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePricingPrecision name="PurchasePricingPrecision">PurchasePricingPrecision</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase pricing precision</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePricingPrecision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase pricing precision</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePrice name="PurchasePrice">PurchasePrice</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceDate name="PurchasePriceDate">PurchasePriceDate</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase price date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase price date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceQuantity name="PurchasePriceQuantity">PurchasePriceQuantity</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase price quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase price quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseUnitSymbol name="PurchaseUnitSymbol">PurchaseUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseChargeProductGroupId name="PurchaseChargeProductGroupId">PurchaseChargeProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase charges group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseChargeProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase charges group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchasePriceIncludingCharges name="IsPurchasePriceIncludingCharges">IsPurchasePriceIncludingCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include charges in purchase price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchasePriceIncludingCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include charges in purchase price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedPurchasePriceCharges name="FixedPurchasePriceCharges">FixedPurchasePriceCharges</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase charges quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseChargesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase charges quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreTransportationManagementProcessesEnabled name="AreTransportationManagementProcessesEnabled">AreTransportationManagementProcessesEnabled</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use transportation management processes</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreTransportationManagementProcessesEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use transportation management processes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatCommodityCode name="IntrastatCommodityCode">IntrastatCommodityCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Intrastat commodity code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatCommodityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intrastat commodity code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatChargePercentage name="IntrastatChargePercentage">IntrastatChargePercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Charges percentage for Intrastat</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatChargePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Charges percentage for Intrastat</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginCountryRegionId name="OriginCountryRegionId">OriginCountryRegionId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/region of origin</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Country/region of origin</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginStateId name="OriginStateId">OriginStateId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State of origin</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>State of origin</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApproximateSalesTaxPercentage name="ApproximateSalesTaxPercentage">ApproximateSalesTaxPercentage</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductFiscalInformationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsICMSTaxAppliedOnService name="IsICMSTaxAppliedOnService">IsICMSTaxAppliedOnService</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesWithholdingTaxCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesItemWithholdingTaxGroupCode name="SalesItemWithholdingTaxGroupCode">SalesItemWithholdingTaxGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseWithholdingTaxCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseItemWithholdingTaxGroupCode name="PurchaseItemWithholdingTaxGroupCode">PurchaseItemWithholdingTaxGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesGSTReliefCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseGSTReliefCategoryCode name="PurchaseGSTReliefCategoryCode">PurchaseGSTReliefCategoryCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseGSTReliefCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryGSTReliefCategoryCode name="InventoryGSTReliefCategoryCode">InventoryGSTReliefCategoryCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryGSTReliefCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NGPCode name="NGPCode">NGPCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

### <a href=#TaxGSTReliefCategorySales name="TaxGSTReliefCategorySales">TaxGSTReliefCategorySales</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGSTReliefCategorySales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGSTReliefCategoryInvent name="TaxGSTReliefCategoryInvent">TaxGSTReliefCategoryInvent</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGSTReliefCategoryInvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGSTReliefCategoryPurch name="TaxGSTReliefCategoryPurch">TaxGSTReliefCategoryPurch</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGSTReliefCategoryPurch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SADGroup name="SADGroup">SADGroup</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SADGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PKWiUCode name="PKWiUCode">PKWiUCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PKWiUCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsManualDiscountPOSRegistrationProhibited name="IsManualDiscountPOSRegistrationProhibited">IsManualDiscountPOSRegistrationProhibited</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No manual discount allowed at POS register</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsManualDiscountPOSRegistrationProhibited attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>No manual discount allowed at POS register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryCountingReasonCodePolicyName name="InventoryCountingReasonCodePolicyName">InventoryCountingReasonCodePolicyName</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory counting reason code policy name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryCountingReasonCodePolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory counting reason code policy name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventCountingReasonCodePolicyRecId name="InventCountingReasonCodePolicyRecId">InventCountingReasonCodePolicyRecId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventCountingReasonCodePolicyRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HSNCode name="HSNCode">HSNCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceAccountingCode name="ServiceAccountingCode">ServiceAccountingCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Exempt name="Exempt">Exempt</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Exempt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsImportTariffCode name="CustomsImportTariffCode">CustomsImportTariffCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsImportTariffCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsExportTariffCode name="CustomsExportTariffCode">CustomsExportTariffCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsExportTariffCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SATCode name="SATCode">SATCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SATCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScaleIndicator name="ScaleIndicator">ScaleIndicator</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScaleIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CNPJ name="CNPJ">CNPJ</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CNPJ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxSubstitutionCode name="TaxSubstitutionCode">TaxSubstitutionCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSubstitutionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductLifecycleStateId name="ProductLifecycleStateId">ProductLifecycleStateId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductLifecycleStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpdateProductVariantLifecycleState name="UpdateProductVariantLifecycleState">UpdateProductVariantLifecycleState</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update Product Variant Lifecycle State</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateProductVariantLifecycleState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update Product Variant Lifecycle State</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightItemHandlingPolicyName name="CatchWeightItemHandlingPolicyName">CatchWeightItemHandlingPolicyName</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightItemHandlingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstProductFilterCode name="FirstProductFilterCode">FirstProductFilterCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstProductFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondProductFilterCode name="SecondProductFilterCode">SecondProductFilterCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondProductFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdProductFilterCode name="ThirdProductFilterCode">ThirdProductFilterCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdProductFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FourthProductFilterCode name="FourthProductFilterCode">FourthProductFilterCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FourthProductFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstProductFilterGroupId name="FirstProductFilterGroupId">FirstProductFilterGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstProductFilterGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondProductFilterGroupId name="SecondProductFilterGroupId">SecondProductFilterGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondProductFilterGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonGST name="NonGST">NonGST</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonGST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRateType name="TaxRateType">TaxRateType</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDimensionGroupName name="ProductDimensionGroupName">ProductDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCatchWeightProduct name="IsCatchWeightProduct">IsCatchWeightProduct</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCatchWeightProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRetailDiscountPOSRegistrationProhibited name="IsRetailDiscountPOSRegistrationProhibited">IsRetailDiscountPOSRegistrationProhibited</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prevent retail discounts</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRetailDiscountPOSRegistrationProhibited attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prevent retail discounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTenderDiscountPOSRegistrationProhibited name="IsTenderDiscountPOSRegistrationProhibited">IsTenderDiscountPOSRegistrationProhibited</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prevent tender based discounts</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTenderDiscountPOSRegistrationProhibited attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prevent tender based discounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantablePriceRangeBaseType name="WarrantablePriceRangeBaseType">WarrantablePriceRangeBaseType</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantablePriceRangeBaseType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowerWarrantablePriceRangeLimit name="LowerWarrantablePriceRangeLimit">LowerWarrantablePriceRangeLimit</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowerWarrantablePriceRangeLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpperWarrantablePriceRangeLimit name="UpperWarrantablePriceRangeLimit">UpperWarrantablePriceRangeLimit</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpperWarrantablePriceRangeLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyDurationTime name="WarrantyDurationTime">WarrantyDurationTime</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyDurationTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyDurationTimeUnit name="WarrantyDurationTimeUnit">WarrantyDurationTimeUnit</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyDurationTimeUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostCalculationBOMLevel name="CostCalculationBOMLevel">CostCalculationBOMLevel</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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

### <a href=#SalesRetailInventoryAvailabilityBuffer name="SalesRetailInventoryAvailabilityBuffer">SalesRetailInventoryAvailabilityBuffer</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRetailInventoryAvailabilityBuffer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRetailInventoryAvailabilityLevelProfile name="SalesRetailInventoryAvailabilityLevelProfile">SalesRetailInventoryAvailabilityLevelProfile</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRetailInventoryAvailabilityLevelProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecRevenueType name="RevRecRevenueType">RevRecRevenueType</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecRevenueType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecDefaultRevenueRecognitionSchedule name="RevRecDefaultRevenueRecognitionSchedule">RevRecDefaultRevenueRecognitionSchedule</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecDefaultRevenueRecognitionSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecBundle name="RevRecBundle">RevRecBundle</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecBundle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecExcludeFromCarveOut name="RevRecExcludeFromCarveOut">RevRecExcludeFromCarveOut</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecExcludeFromCarveOut attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecMedianPrice name="RevRecMedianPrice">RevRecMedianPrice</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecMedianPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecMedianPriceMaximumTolerance name="RevRecMedianPriceMaximumTolerance">RevRecMedianPriceMaximumTolerance</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecMedianPriceMaximumTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecMedianPriceMinimumTolerance name="RevRecMedianPriceMinimumTolerance">RevRecMedianPriceMinimumTolerance</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecMedianPriceMinimumTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecRevenueRecognitionEnabled name="RevRecRevenueRecognitionEnabled">RevRecRevenueRecognitionEnabled</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecRevenueRecognitionEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId name="Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId">Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EcoResProductV2EntityRelationshipId name="Relationship_EcoResProductV2EntityRelationshipId">Relationship_EcoResProductV2EntityRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductV2EntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventoryCountingReasonCodePolicyRelationshipId name="Relationship_InventoryCountingReasonCodePolicyRelationshipId">Relationship_InventoryCountingReasonCodePolicyRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryCountingReasonCodePolicyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_StorageDimensionGroupRelationshipId name="Relationship_StorageDimensionGroupRelationshipId">Relationship_StorageDimensionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StorageDimensionGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TrackingDimensionGroupRelationshipId name="Relationship_TrackingDimensionGroupRelationshipId">Relationship_TrackingDimensionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrackingDimensionGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_GSTReliefCategoryRelationshipId name="Relationship_GSTReliefCategoryRelationshipId">Relationship_GSTReliefCategoryRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GSTReliefCategoryRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_NGPCodeRelationshipId name="Relationship_NGPCodeRelationshipId">Relationship_NGPCodeRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NGPCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxServiceAccountingCodeRelationshipId name="Relationship_TaxServiceAccountingCodeRelationshipId">Relationship_TaxServiceAccountingCodeRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxServiceAccountingCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventoryReservationHierarchyRelationshipId name="Relationship_InventoryReservationHierarchyRelationshipId">Relationship_InventoryReservationHierarchyRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryReservationHierarchyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AlternativeProductConfigurationRelationshipId name="Relationship_AlternativeProductConfigurationRelationshipId">Relationship_AlternativeProductConfigurationRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlternativeProductConfigurationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AlternativeProductColorRelationshipId name="Relationship_AlternativeProductColorRelationshipId">Relationship_AlternativeProductColorRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlternativeProductColorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AlternativeProductSizeRelationshipId name="Relationship_AlternativeProductSizeRelationshipId">Relationship_AlternativeProductSizeRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlternativeProductSizeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AlternativeProductStyleRelationshipId name="Relationship_AlternativeProductStyleRelationshipId">Relationship_AlternativeProductStyleRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlternativeProductStyleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AlternativeProductVersionRelationshipId name="Relationship_AlternativeProductVersionRelationshipId">Relationship_AlternativeProductVersionRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlternativeProductVersionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BatchNumberGroupRelationshipId name="Relationship_BatchNumberGroupRelationshipId">Relationship_BatchNumberGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BatchNumberGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CostCalculationGroupRelationshipId name="Relationship_CostCalculationGroupRelationshipId">Relationship_CostCalculationGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CostCalculationGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BOMUnitOfMeasureRelationshipId name="Relationship_BOMUnitOfMeasureRelationshipId">Relationship_BOMUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CommissionProductGroupRelationshipId name="Relationship_CommissionProductGroupRelationshipId">Relationship_CommissionProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CommissionProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CostGroupRelationshipId name="Relationship_CostGroupRelationshipId">Relationship_CostGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CostGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BuyerGroupRelationshipId name="Relationship_BuyerGroupRelationshipId">Relationship_BuyerGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BuyerGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchasePriceToleranceGroupRelationshipId name="Relationship_PurchasePriceToleranceGroupRelationshipId">Relationship_PurchasePriceToleranceGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchasePriceToleranceGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PackingMaterialGroupRelationshipId name="Relationship_PackingMaterialGroupRelationshipId">Relationship_PackingMaterialGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PackingMaterialGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesRebateProductFreightGroupRelationshipId name="Relationship_SalesRebateProductFreightGroupRelationshipId">Relationship_SalesRebateProductFreightGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesRebateProductFreightGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesRebateProductGroupRelationshipId name="Relationship_SalesRebateProductGroupRelationshipId">Relationship_SalesRebateProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesRebateProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryVendorV2RelationshipId name="Relationship_PrimaryVendorV2RelationshipId">Relationship_PrimaryVendorV2RelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryVendorV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductionGroupRelationshipId name="Relationship_ProductionGroupRelationshipId">Relationship_ProductionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductionPoolRelationshipId name="Relationship_ProductionPoolRelationshipId">Relationship_ProductionPoolRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionPoolRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjectCategoryRelationshipId name="Relationship_ProjectCategoryRelationshipId">Relationship_ProjectCategoryRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectCategoryRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductCoverageGroupRelationshipId name="Relationship_ProductCoverageGroupRelationshipId">Relationship_ProductCoverageGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductCoverageGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SerialNumberGroupRelationshipId name="Relationship_SerialNumberGroupRelationshipId">Relationship_SerialNumberGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SerialNumberGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultProductStyleRelationshipId name="Relationship_DefaultProductStyleRelationshipId">Relationship_DefaultProductStyleRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultProductStyleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultProductVersionRelationshipId name="Relationship_DefaultProductVersionRelationshipId">Relationship_DefaultProductVersionRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultProductVersionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultProductSizeRelationshipId name="Relationship_DefaultProductSizeRelationshipId">Relationship_DefaultProductSizeRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultProductSizeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultProductColorRelationshipId name="Relationship_DefaultProductColorRelationshipId">Relationship_DefaultProductColorRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultProductColorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultProductConfigurationRelationshipId name="Relationship_DefaultProductConfigurationRelationshipId">Relationship_DefaultProductConfigurationRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultProductConfigurationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehousePackageClassRelationshipId name="Relationship_WarehousePackageClassRelationshipId">Relationship_WarehousePackageClassRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehousePackageClassRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PackSizeCategoryRelationshipId name="Relationship_PackSizeCategoryRelationshipId">Relationship_PackSizeCategoryRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PackSizeCategoryRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PhysicalDimensionGroupRelationshipId name="Relationship_PhysicalDimensionGroupRelationshipId">Relationship_PhysicalDimensionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PhysicalDimensionGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnitOfMeasureConversionSequenceGroupRelationshipId name="Relationship_UnitOfMeasureConversionSequenceGroupRelationshipId">Relationship_UnitOfMeasureConversionSequenceGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnitOfMeasureConversionSequenceGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CatchWeightUnitOfMeasureRelationshipId name="Relationship_CatchWeightUnitOfMeasureRelationshipId">Relationship_CatchWeightUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatchWeightUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseRebateProductGroupRelationshipId name="Relationship_PurchaseRebateProductGroupRelationshipId">Relationship_PurchaseRebateProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseRebateProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ComparisonPriceBaseUnitOfMeasureRelationshipId name="Relationship_ComparisonPriceBaseUnitOfMeasureRelationshipId">Relationship_ComparisonPriceBaseUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ComparisonPriceBaseUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesSupplementaryProductProductGroupRelationshipId name="Relationship_SalesSupplementaryProductProductGroupRelationshipId">Relationship_SalesSupplementaryProductProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesSupplementaryProductProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesChargeProductGroupRelationshipId name="Relationship_SalesChargeProductGroupRelationshipId">Relationship_SalesChargeProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesChargeProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OriginCountryRegionRelationshipId name="Relationship_OriginCountryRegionRelationshipId">Relationship_OriginCountryRegionRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginStateRelationshipId name="Relationship_OriginStateRelationshipId">Relationship_OriginStateRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ServiceFiscalInformationCodeRelationshipId name="Relationship_ServiceFiscalInformationCodeRelationshipId">Relationship_ServiceFiscalInformationCodeRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ServiceFiscalInformationCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FiscalClassificationCodeRelationshipId name="Relationship_FiscalClassificationCodeRelationshipId">Relationship_FiscalClassificationCodeRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalClassificationCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesMultilineDiscountProductGroupRelationshipId name="Relationship_SalesMultilineDiscountProductGroupRelationshipId">Relationship_SalesMultilineDiscountProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesMultilineDiscountProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesLineDiscountProductGroupRelationshipId name="Relationship_SalesLineDiscountProductGroupRelationshipId">Relationship_SalesLineDiscountProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesLineDiscountProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventoryUnitOfMeasureRelationshipId name="Relationship_InventoryUnitOfMeasureRelationshipId">Relationship_InventoryUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductGroupRelationshipId name="Relationship_ProductGroupRelationshipId">Relationship_ProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventoryPolicyRelationshipId name="Relationship_InventoryPolicyRelationshipId">Relationship_InventoryPolicyRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryPolicyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesUnitOfMeasureRelationshipId name="Relationship_SalesUnitOfMeasureRelationshipId">Relationship_SalesUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultDirectDeliveryWarehouseRelationshipId name="Relationship_DefaultDirectDeliveryWarehouseRelationshipId">Relationship_DefaultDirectDeliveryWarehouseRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDirectDeliveryWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseLineDiscountProductGroupRelationshipId name="Relationship_PurchaseLineDiscountProductGroupRelationshipId">Relationship_PurchaseLineDiscountProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseLineDiscountProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseMultilineDiscountProductGroupRelationshipId name="Relationship_PurchaseMultilineDiscountProductGroupRelationshipId">Relationship_PurchaseMultilineDiscountProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseMultilineDiscountProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseSupplementaryProductGroupRelationshipId name="Relationship_PurchaseSupplementaryProductGroupRelationshipId">Relationship_PurchaseSupplementaryProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseSupplementaryProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseUnitOfMeasureRelationshipId name="Relationship_PurchaseUnitOfMeasureRelationshipId">Relationship_PurchaseUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseChargeProductGroupRelationshipId name="Relationship_PurchaseChargeProductGroupRelationshipId">Relationship_PurchaseChargeProductGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseChargeProductGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ItemFiscalClassificationExceptionRelationshipId name="Relationship_ItemFiscalClassificationExceptionRelationshipId">Relationship_ItemFiscalClassificationExceptionRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemFiscalClassificationExceptionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductLifecycleStateRelationshipId name="Relationship_ProductLifecycleStateRelationshipId">Relationship_ProductLifecycleStateRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductLifecycleStateRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CatchWeightItemHandlingPolicyV2RelationshipId name="Relationship_CatchWeightItemHandlingPolicyV2RelationshipId">Relationship_CatchWeightItemHandlingPolicyV2RelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatchWeightItemHandlingPolicyV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WHSFirstProductFilterCodeEntityRelationshipId name="Relationship_WHSFirstProductFilterCodeEntityRelationshipId">Relationship_WHSFirstProductFilterCodeEntityRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSFirstProductFilterCodeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WHSSecondProductFilterCodeEntityRelationshipId name="Relationship_WHSSecondProductFilterCodeEntityRelationshipId">Relationship_WHSSecondProductFilterCodeEntityRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSSecondProductFilterCodeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WHSThirdProductFilterCodeEntityRelationshipId name="Relationship_WHSThirdProductFilterCodeEntityRelationshipId">Relationship_WHSThirdProductFilterCodeEntityRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSThirdProductFilterCodeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WHSFourthProductFilterCodeEntityRelationshipId name="Relationship_WHSFourthProductFilterCodeEntityRelationshipId">Relationship_WHSFourthProductFilterCodeEntityRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSFourthProductFilterCodeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EcoResEveryProductEntityRelationshipId name="Relationship_EcoResEveryProductEntityRelationshipId">Relationship_EcoResEveryProductEntityRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResEveryProductEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventTableRelationshipId name="BackingTable_InventTableRelationshipId">BackingTable_InventTableRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductV2Entity (this entity)  

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
