---
title: ProdProductionControlParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Production control parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdProductionControlParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production control parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Key](#Key)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[ParameterUsageLevel](#ParameterUsageLevel)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillLastOperationEndingExecuteReportAsFinishedByDefault](#WillLastOperationEndingExecuteReportAsFinishedByDefault)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillProductionPickingListPostingAllowNegativeInventory](#WillProductionPickingListPostingAllowNegativeInventory)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillProductionPickingListPostingReduceToAvailableQuantity](#WillProductionPickingListPostingReduceToAvailableQuantity)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillPickingListJournalLineProposedQuantityOverrideConsumptionQuantityByDefault](#WillPickingListJournalLineProposedQuantityOverrideConsumptionQuantityByDefault)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[ProductionCostRecalculationProductionOrderBundleSize](#ProductionCostRecalculationProductionOrderBundleSize)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultProductionOrderAutoReservationMode](#DefaultProductionOrderAutoReservationMode)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillReportAsFinishedPostingAcceptQuantityErrorByDefault](#WillReportAsFinishedPostingAcceptQuantityErrorByDefault)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsLeanCostingFullBatchParallelizationEnabled](#IsLeanCostingFullBatchParallelizationEnabled)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillLeanBatchProcessingSplitLedgerVoucherTransactions](#WillLeanBatchProcessingSplitLedgerVoucherTransactions)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillNonStandardRouteVersionBatchOrderUsageAlertUser](#WillNonStandardRouteVersionBatchOrderUsageAlertUser)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultBurdenRouteCostCategoryId](#DefaultBurdenRouteCostCategoryId)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillReportAsFinishedPostingAutomaticallyPostPickingListByDefault](#WillReportAsFinishedPostingAutomaticallyPostPickingListByDefault)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillEstimationPurchaseOrderCreationGroupByBuyerGroup](#WillEstimationPurchaseOrderCreationGroupByBuyerGroup)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillEstimationPurchaseOrderCreationGroupByPurchaseAgreement](#WillEstimationPurchaseOrderCreationGroupByPurchaseAgreement)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillEstimationPurchaseOrderCreationGroupByVendor](#WillEstimationPurchaseOrderCreationGroupByVendor)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillEstimationPurchaseOrderCreationFindPurchaseAgreements](#WillEstimationPurchaseOrderCreationFindPurchaseAgreements)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultProductionOrderLedgerPostingRule](#DefaultProductionOrderLedgerPostingRule)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultProductionFlowQuantityUnit](#DefaultProductionFlowQuantityUnit)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultProductionFlowQuantityUnitSymbol](#DefaultProductionFlowQuantityUnitSymbol)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultProductionFlowTimeUnit](#DefaultProductionFlowTimeUnit)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultProductionFlowTimeUnitSymbol](#DefaultProductionFlowTimeUnitSymbol)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[KanbanProductionInstructionDocumenAttachmentTypeCode](#KanbanProductionInstructionDocumenAttachmentTypeCode)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultProductionOrderWarehouseReleaseReservationRequirementRule](#DefaultProductionOrderWarehouseReleaseReservationRequirementRule)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultProductionOrderProfitSettingMethod](#DefaultProductionOrderProfitSettingMethod)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillRouteCardPostingAutomaticallyPostPickingListByDefault](#WillRouteCardPostingAutomaticallyPostPickingListByDefault)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillOnlyProductionEndingUpdateCostCalculation](#WillOnlyProductionEndingUpdateCostCalculation)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[TimeCalculationDaysUnitSymbol](#TimeCalculationDaysUnitSymbol)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[TimeCalculationDaysUnit](#TimeCalculationDaysUnit)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[TimeCalculationHoursUnitSymbol](#TimeCalculationHoursUnitSymbol)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[TimeCalculationHoursUnit](#TimeCalculationHoursUnit)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[TimeCalculationMinutesUnitSymbol](#TimeCalculationMinutesUnitSymbol)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[TimeCalculationMinutesUnit](#TimeCalculationMinutesUnit)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[TimeCalculationSecondsUnitSymbol](#TimeCalculationSecondsUnitSymbol)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[TimeCalculationSecondsUnit](#TimeCalculationSecondsUnit)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsCreatedToEstimatedStatusChangedAllowed](#IsCreatedToEstimatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsCreatedToOperationsScheduledStatusChangedAllowed](#IsCreatedToOperationsScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsCreatedToJobScheduledStatusChangedAllowed](#IsCreatedToJobScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsCreatedToReleasedStatusChangedAllowed](#IsCreatedToReleasedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsCreatedToStartedStatusChangedAllowed](#IsCreatedToStartedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsCreatedToReportedAsFinishedStatusChangedAllowed](#IsCreatedToReportedAsFinishedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsCreatedToEndedStatusChangedAllowed](#IsCreatedToEndedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsEstimatedToCreatedStatusChangedAllowed](#IsEstimatedToCreatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsEstimatedToOperationsScheduledStatusChangedAllowed](#IsEstimatedToOperationsScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsEstimatedToJobScheduledStatusChangedAllowed](#IsEstimatedToJobScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsEstimatedToReleasedStatusChangedAllowed](#IsEstimatedToReleasedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsEstimatedToStartedStatusChangedAllowed](#IsEstimatedToStartedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsEstimatedToReportedAsFinishedStatusChangedAllowed](#IsEstimatedToReportedAsFinishedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsEstimatedToEndedStatusChangedAllowed](#IsEstimatedToEndedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsOperationsScheduledToCreatedStatusChangedAllowed](#IsOperationsScheduledToCreatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsOperationsScheduledToEstimatedStatusChangedAllowed](#IsOperationsScheduledToEstimatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsOperationsScheduledToJobScheduledStatusChangedAllowed](#IsOperationsScheduledToJobScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsOperationsScheduledToReleasedStatusChangedAllowed](#IsOperationsScheduledToReleasedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsOperationsScheduledToStartedStatusChangedAllowed](#IsOperationsScheduledToStartedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsOperationsScheduledToReportedAsFinishedStatusChangedAllowed](#IsOperationsScheduledToReportedAsFinishedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsOperationsScheduledToEndedStatusChangedAllowed](#IsOperationsScheduledToEndedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsJobScheduledToCreatedStatusChangedAllowed](#IsJobScheduledToCreatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsJobScheduledToEstimatedStatusChangedAllowed](#IsJobScheduledToEstimatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsJobScheduledToOperationsScheduledStatusChangedAllowed](#IsJobScheduledToOperationsScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsJobScheduledToReleasedStatusChangedAllowed](#IsJobScheduledToReleasedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsJobScheduledToStartedStatusChangedAllowed](#IsJobScheduledToStartedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsJobScheduledToReportedAsFinishedStatusChangedAllowed](#IsJobScheduledToReportedAsFinishedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsJobScheduledToEndedStatusChangedAllowed](#IsJobScheduledToEndedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReleasedToCreatedStatusChangedAllowed](#IsReleasedToCreatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReleasedToEstimatedStatusChangedAllowed](#IsReleasedToEstimatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReleasedToOperationsScheduledStatusChangedAllowed](#IsReleasedToOperationsScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReleasedToJobScheduledStatusChangedAllowed](#IsReleasedToJobScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReleasedToStartedStatusChangedAllowed](#IsReleasedToStartedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReleasedToReportedAsFinishedStatusChangedAllowed](#IsReleasedToReportedAsFinishedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReleasedToEndedStatusChangedAllowed](#IsReleasedToEndedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsStartedToCreatedStatusChangedAllowed](#IsStartedToCreatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsStartedToEstimatedStatusChangedAllowed](#IsStartedToEstimatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsStartedToOperationsScheduledStatusChangedAllowed](#IsStartedToOperationsScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsStartedToJobScheduledStatusChangedAllowed](#IsStartedToJobScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsStartedToReleasedStatusChangedAllowed](#IsStartedToReleasedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsStartedToReportedAsFinishedStatusChangedAllowed](#IsStartedToReportedAsFinishedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsStartedToEndedStatusChangedAllowed](#IsStartedToEndedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToCreatedStatusChangedAllowed](#IsReportedAsFinishedToCreatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToEstimatedStatusChangedAllowed](#IsReportedAsFinishedToEstimatedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToOperationsScheduledStatusChangedAllowed](#IsReportedAsFinishedToOperationsScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToJobScheduledStatusChangedAllowed](#IsReportedAsFinishedToJobScheduledStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToReleasedStatusChangedAllowed](#IsReportedAsFinishedToReleasedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToStartedStatusChangedAllowed](#IsReportedAsFinishedToStartedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToEndedStatusChangedAllowed](#IsReportedAsFinishedToEndedStatusChangedAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[PurchaseProductReceiptAutomaticBOMConsumptionRule](#PurchaseProductReceiptAutomaticBOMConsumptionRule)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[ReportAsFinishedAutomaticBOMConsumptionRule](#ReportAsFinishedAutomaticBOMConsumptionRule)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[ProductionStartAutomaticBOMConsumptionRule](#ProductionStartAutomaticBOMConsumptionRule)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultPickingListProductionJournalNameId](#DefaultPickingListProductionJournalNameId)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillSchedulingConsiderFiniteCapacityByDefault](#WillSchedulingConsiderFiniteCapacityByDefault)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[ProductionEndingScrapMethod](#ProductionEndingScrapMethod)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillReportedAsFinishedDeleteCapacityReservations](#WillReportedAsFinishedDeleteCapacityReservations)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillReportAsFinishedIncreaseRemainingQuantityWithErrorQuantity](#WillReportAsFinishedIncreaseRemainingQuantityWithErrorQuantity)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultJobCardProductionJournalNameId](#DefaultJobCardProductionJournalNameId)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillRouteCardPostingUpdateCapacityPlan](#WillRouteCardPostingUpdateCapacityPlan)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillCapacityPlanningIncludePlannedOrders](#WillCapacityPlanningIncludePlannedOrders)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillCapacityPlanningIncludeProjectHourForecasts](#WillCapacityPlanningIncludeProjectHourForecasts)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsRouteCardHourCostCategoryMandatory](#IsRouteCardHourCostCategoryMandatory)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsRouteCardQuantityCostCategoryMandatory](#IsRouteCardQuantityCostCategoryMandatory)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillSchedulingConsiderFiniteMaterialsByDefault](#WillSchedulingConsiderFiniteMaterialsByDefault)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[MaximumJobSchedulingJobLeadTimeDays](#MaximumJobSchedulingJobLeadTimeDays)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillReportAsFinishedUseEstimatedUnitCost](#WillReportAsFinishedUseEstimatedUnitCost)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillProductionPostingExcludeTransactionType](#WillProductionPostingExcludeTransactionType)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillProductionPickingListPostInLedger](#WillProductionPickingListPostInLedger)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillReportAsFinishedPostInLedger](#WillReportAsFinishedPostInLedger)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultProductionJournalNameId](#DefaultProductionJournalNameId)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[ProductionLineReleaseToWarehousePrinciple](#ProductionLineReleaseToWarehousePrinciple)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillSchedulingConsiderFinitePropertyByDefault](#WillSchedulingConsiderFinitePropertyByDefault)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillPurchaseProductReceiptDisplayRouteCardInformation](#WillPurchaseProductReceiptDisplayRouteCardInformation)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[PurchaseProductReceiptAutomaticRouteConsumptionRule](#PurchaseProductReceiptAutomaticRouteConsumptionRule)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[ReportAsFinishedAutomaticRouteConsumptionRule](#ReportAsFinishedAutomaticRouteConsumptionRule)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[ProductionStartAutomaticRouteConsumptionRule](#ProductionStartAutomaticRouteConsumptionRule)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[DefaultRouteCardProductionJournalNameId](#DefaultRouteCardProductionJournalNameId)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[AutomaticSchedulingMethod](#AutomaticSchedulingMethod)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[WillProductionEstimationCalculateEstimatedUnitCost](#WillProductionEstimationCalculateEstimatedUnitCost)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsApprovedRouteEditingAllowed](#IsApprovedRouteEditingAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[IsRouteApprovalRemovalAllowed](#IsRouteApprovalRemovalAllowed)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[AreRouteVersionValidDatesMandatory](#AreRouteVersionValidDatesMandatory)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[AreRouteNetworksEnabled](#AreRouteNetworksEnabled)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[BackingTable_ProdParametersRelationshipId](#BackingTable_ProdParametersRelationshipId)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdProductionControlParametersEntity</a>|

### <a href=#Key name="Key">Key</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParameterUsageLevel name="ParameterUsageLevel">ParameterUsageLevel</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParameterUsageLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillLastOperationEndingExecuteReportAsFinishedByDefault name="WillLastOperationEndingExecuteReportAsFinishedByDefault">WillLastOperationEndingExecuteReportAsFinishedByDefault</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillLastOperationEndingExecuteReportAsFinishedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionPickingListPostingAllowNegativeInventory name="WillProductionPickingListPostingAllowNegativeInventory">WillProductionPickingListPostingAllowNegativeInventory</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionPickingListPostingAllowNegativeInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionPickingListPostingReduceToAvailableQuantity name="WillProductionPickingListPostingReduceToAvailableQuantity">WillProductionPickingListPostingReduceToAvailableQuantity</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionPickingListPostingReduceToAvailableQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPickingListJournalLineProposedQuantityOverrideConsumptionQuantityByDefault name="WillPickingListJournalLineProposedQuantityOverrideConsumptionQuantityByDefault">WillPickingListJournalLineProposedQuantityOverrideConsumptionQuantityByDefault</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPickingListJournalLineProposedQuantityOverrideConsumptionQuantityByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionCostRecalculationProductionOrderBundleSize name="ProductionCostRecalculationProductionOrderBundleSize">ProductionCostRecalculationProductionOrderBundleSize</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionCostRecalculationProductionOrderBundleSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionOrderAutoReservationMode name="DefaultProductionOrderAutoReservationMode">DefaultProductionOrderAutoReservationMode</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionOrderAutoReservationMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedPostingAcceptQuantityErrorByDefault name="WillReportAsFinishedPostingAcceptQuantityErrorByDefault">WillReportAsFinishedPostingAcceptQuantityErrorByDefault</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedPostingAcceptQuantityErrorByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLeanCostingFullBatchParallelizationEnabled name="IsLeanCostingFullBatchParallelizationEnabled">IsLeanCostingFullBatchParallelizationEnabled</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLeanCostingFullBatchParallelizationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillLeanBatchProcessingSplitLedgerVoucherTransactions name="WillLeanBatchProcessingSplitLedgerVoucherTransactions">WillLeanBatchProcessingSplitLedgerVoucherTransactions</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillLeanBatchProcessingSplitLedgerVoucherTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillNonStandardRouteVersionBatchOrderUsageAlertUser name="WillNonStandardRouteVersionBatchOrderUsageAlertUser">WillNonStandardRouteVersionBatchOrderUsageAlertUser</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillNonStandardRouteVersionBatchOrderUsageAlertUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBurdenRouteCostCategoryId name="DefaultBurdenRouteCostCategoryId">DefaultBurdenRouteCostCategoryId</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBurdenRouteCostCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedPostingAutomaticallyPostPickingListByDefault name="WillReportAsFinishedPostingAutomaticallyPostPickingListByDefault">WillReportAsFinishedPostingAutomaticallyPostPickingListByDefault</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedPostingAutomaticallyPostPickingListByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillEstimationPurchaseOrderCreationGroupByBuyerGroup name="WillEstimationPurchaseOrderCreationGroupByBuyerGroup">WillEstimationPurchaseOrderCreationGroupByBuyerGroup</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillEstimationPurchaseOrderCreationGroupByBuyerGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillEstimationPurchaseOrderCreationGroupByPurchaseAgreement name="WillEstimationPurchaseOrderCreationGroupByPurchaseAgreement">WillEstimationPurchaseOrderCreationGroupByPurchaseAgreement</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillEstimationPurchaseOrderCreationGroupByPurchaseAgreement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillEstimationPurchaseOrderCreationGroupByVendor name="WillEstimationPurchaseOrderCreationGroupByVendor">WillEstimationPurchaseOrderCreationGroupByVendor</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillEstimationPurchaseOrderCreationGroupByVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillEstimationPurchaseOrderCreationFindPurchaseAgreements name="WillEstimationPurchaseOrderCreationFindPurchaseAgreements">WillEstimationPurchaseOrderCreationFindPurchaseAgreements</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillEstimationPurchaseOrderCreationFindPurchaseAgreements attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionOrderLedgerPostingRule name="DefaultProductionOrderLedgerPostingRule">DefaultProductionOrderLedgerPostingRule</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionOrderLedgerPostingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionFlowQuantityUnit name="DefaultProductionFlowQuantityUnit">DefaultProductionFlowQuantityUnit</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionFlowQuantityUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionFlowQuantityUnitSymbol name="DefaultProductionFlowQuantityUnitSymbol">DefaultProductionFlowQuantityUnitSymbol</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionFlowQuantityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionFlowTimeUnit name="DefaultProductionFlowTimeUnit">DefaultProductionFlowTimeUnit</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionFlowTimeUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionFlowTimeUnitSymbol name="DefaultProductionFlowTimeUnitSymbol">DefaultProductionFlowTimeUnitSymbol</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionFlowTimeUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KanbanProductionInstructionDocumenAttachmentTypeCode name="KanbanProductionInstructionDocumenAttachmentTypeCode">KanbanProductionInstructionDocumenAttachmentTypeCode</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KanbanProductionInstructionDocumenAttachmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionOrderWarehouseReleaseReservationRequirementRule name="DefaultProductionOrderWarehouseReleaseReservationRequirementRule">DefaultProductionOrderWarehouseReleaseReservationRequirementRule</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionOrderWarehouseReleaseReservationRequirementRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionOrderProfitSettingMethod name="DefaultProductionOrderProfitSettingMethod">DefaultProductionOrderProfitSettingMethod</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionOrderProfitSettingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRouteCardPostingAutomaticallyPostPickingListByDefault name="WillRouteCardPostingAutomaticallyPostPickingListByDefault">WillRouteCardPostingAutomaticallyPostPickingListByDefault</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRouteCardPostingAutomaticallyPostPickingListByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOnlyProductionEndingUpdateCostCalculation name="WillOnlyProductionEndingUpdateCostCalculation">WillOnlyProductionEndingUpdateCostCalculation</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOnlyProductionEndingUpdateCostCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeCalculationDaysUnitSymbol name="TimeCalculationDaysUnitSymbol">TimeCalculationDaysUnitSymbol</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeCalculationDaysUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Days</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeCalculationDaysUnit name="TimeCalculationDaysUnit">TimeCalculationDaysUnit</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeCalculationDaysUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeCalculationHoursUnitSymbol name="TimeCalculationHoursUnitSymbol">TimeCalculationHoursUnitSymbol</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hours</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeCalculationHoursUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Hours</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeCalculationHoursUnit name="TimeCalculationHoursUnit">TimeCalculationHoursUnit</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeCalculationHoursUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeCalculationMinutesUnitSymbol name="TimeCalculationMinutesUnitSymbol">TimeCalculationMinutesUnitSymbol</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minutes</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeCalculationMinutesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minutes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeCalculationMinutesUnit name="TimeCalculationMinutesUnit">TimeCalculationMinutesUnit</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeCalculationMinutesUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeCalculationSecondsUnitSymbol name="TimeCalculationSecondsUnitSymbol">TimeCalculationSecondsUnitSymbol</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeCalculationSecondsUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeCalculationSecondsUnit name="TimeCalculationSecondsUnit">TimeCalculationSecondsUnit</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeCalculationSecondsUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreatedToEstimatedStatusChangedAllowed name="IsCreatedToEstimatedStatusChangedAllowed">IsCreatedToEstimatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow status change from created to estimated</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreatedToEstimatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow status change from created to estimated</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreatedToOperationsScheduledStatusChangedAllowed name="IsCreatedToOperationsScheduledStatusChangedAllowed">IsCreatedToOperationsScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from created to operations scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreatedToOperationsScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from created to operations scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreatedToJobScheduledStatusChangedAllowed name="IsCreatedToJobScheduledStatusChangedAllowed">IsCreatedToJobScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from created to job scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreatedToJobScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from created to job scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreatedToReleasedStatusChangedAllowed name="IsCreatedToReleasedStatusChangedAllowed">IsCreatedToReleasedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from created to released</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreatedToReleasedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from created to released</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreatedToStartedStatusChangedAllowed name="IsCreatedToStartedStatusChangedAllowed">IsCreatedToStartedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from created to started</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreatedToStartedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from created to started</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreatedToReportedAsFinishedStatusChangedAllowed name="IsCreatedToReportedAsFinishedStatusChangedAllowed">IsCreatedToReportedAsFinishedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from created to reported as finished</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreatedToReportedAsFinishedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from created to reported as finished</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreatedToEndedStatusChangedAllowed name="IsCreatedToEndedStatusChangedAllowed">IsCreatedToEndedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from created to ended</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreatedToEndedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from created to ended</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEstimatedToCreatedStatusChangedAllowed name="IsEstimatedToCreatedStatusChangedAllowed">IsEstimatedToCreatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from estimated to created</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEstimatedToCreatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from estimated to created</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEstimatedToOperationsScheduledStatusChangedAllowed name="IsEstimatedToOperationsScheduledStatusChangedAllowed">IsEstimatedToOperationsScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from estimated to operations scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEstimatedToOperationsScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from estimated to operations scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEstimatedToJobScheduledStatusChangedAllowed name="IsEstimatedToJobScheduledStatusChangedAllowed">IsEstimatedToJobScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from estimated to job scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEstimatedToJobScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from estimated to job scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEstimatedToReleasedStatusChangedAllowed name="IsEstimatedToReleasedStatusChangedAllowed">IsEstimatedToReleasedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from estimated to released</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEstimatedToReleasedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from estimated to released</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEstimatedToStartedStatusChangedAllowed name="IsEstimatedToStartedStatusChangedAllowed">IsEstimatedToStartedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from estimated to started</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEstimatedToStartedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from estimated to started</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEstimatedToReportedAsFinishedStatusChangedAllowed name="IsEstimatedToReportedAsFinishedStatusChangedAllowed">IsEstimatedToReportedAsFinishedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from estimated to reported as finished</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEstimatedToReportedAsFinishedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from estimated to reported as finished</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEstimatedToEndedStatusChangedAllowed name="IsEstimatedToEndedStatusChangedAllowed">IsEstimatedToEndedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from estimated to ended</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEstimatedToEndedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from estimated to ended</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationsScheduledToCreatedStatusChangedAllowed name="IsOperationsScheduledToCreatedStatusChangedAllowed">IsOperationsScheduledToCreatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from operations scheduled to created</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationsScheduledToCreatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from operations scheduled to created</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationsScheduledToEstimatedStatusChangedAllowed name="IsOperationsScheduledToEstimatedStatusChangedAllowed">IsOperationsScheduledToEstimatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from operations scheduled to estimated</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationsScheduledToEstimatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from operations scheduled to estimated</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationsScheduledToJobScheduledStatusChangedAllowed name="IsOperationsScheduledToJobScheduledStatusChangedAllowed">IsOperationsScheduledToJobScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from operations scheduled to job scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationsScheduledToJobScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from operations scheduled to job scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationsScheduledToReleasedStatusChangedAllowed name="IsOperationsScheduledToReleasedStatusChangedAllowed">IsOperationsScheduledToReleasedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from operations scheduled to released</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationsScheduledToReleasedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from operations scheduled to released</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationsScheduledToStartedStatusChangedAllowed name="IsOperationsScheduledToStartedStatusChangedAllowed">IsOperationsScheduledToStartedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from operations scheduled to started</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationsScheduledToStartedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from operations scheduled to started</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationsScheduledToReportedAsFinishedStatusChangedAllowed name="IsOperationsScheduledToReportedAsFinishedStatusChangedAllowed">IsOperationsScheduledToReportedAsFinishedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from operations scheduled to reported as finished</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationsScheduledToReportedAsFinishedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from operations scheduled to reported as finished</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationsScheduledToEndedStatusChangedAllowed name="IsOperationsScheduledToEndedStatusChangedAllowed">IsOperationsScheduledToEndedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from operations scheduled to ended</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationsScheduledToEndedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from operations scheduled to ended</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobScheduledToCreatedStatusChangedAllowed name="IsJobScheduledToCreatedStatusChangedAllowed">IsJobScheduledToCreatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from job scheduled to created</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobScheduledToCreatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from job scheduled to created</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobScheduledToEstimatedStatusChangedAllowed name="IsJobScheduledToEstimatedStatusChangedAllowed">IsJobScheduledToEstimatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from job scheduled to estimated</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobScheduledToEstimatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from job scheduled to estimated</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobScheduledToOperationsScheduledStatusChangedAllowed name="IsJobScheduledToOperationsScheduledStatusChangedAllowed">IsJobScheduledToOperationsScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from job scheduled to operations scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobScheduledToOperationsScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from job scheduled to operations scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobScheduledToReleasedStatusChangedAllowed name="IsJobScheduledToReleasedStatusChangedAllowed">IsJobScheduledToReleasedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from job scheduled to released</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobScheduledToReleasedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from job scheduled to released</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobScheduledToStartedStatusChangedAllowed name="IsJobScheduledToStartedStatusChangedAllowed">IsJobScheduledToStartedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from job scheduled to started</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobScheduledToStartedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from job scheduled to started</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobScheduledToReportedAsFinishedStatusChangedAllowed name="IsJobScheduledToReportedAsFinishedStatusChangedAllowed">IsJobScheduledToReportedAsFinishedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from job scheduled to reported as finished</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobScheduledToReportedAsFinishedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from job scheduled to reported as finished</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobScheduledToEndedStatusChangedAllowed name="IsJobScheduledToEndedStatusChangedAllowed">IsJobScheduledToEndedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from job scheduled to ended</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobScheduledToEndedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from job scheduled to ended</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReleasedToCreatedStatusChangedAllowed name="IsReleasedToCreatedStatusChangedAllowed">IsReleasedToCreatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from released to created</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReleasedToCreatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from released to created</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReleasedToEstimatedStatusChangedAllowed name="IsReleasedToEstimatedStatusChangedAllowed">IsReleasedToEstimatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from released to estimated</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReleasedToEstimatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from released to estimated</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReleasedToOperationsScheduledStatusChangedAllowed name="IsReleasedToOperationsScheduledStatusChangedAllowed">IsReleasedToOperationsScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from released to operations scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReleasedToOperationsScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from released to operations scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReleasedToJobScheduledStatusChangedAllowed name="IsReleasedToJobScheduledStatusChangedAllowed">IsReleasedToJobScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from released to to job scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReleasedToJobScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from released to to job scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReleasedToStartedStatusChangedAllowed name="IsReleasedToStartedStatusChangedAllowed">IsReleasedToStartedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from released to started</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReleasedToStartedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from released to started</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReleasedToReportedAsFinishedStatusChangedAllowed name="IsReleasedToReportedAsFinishedStatusChangedAllowed">IsReleasedToReportedAsFinishedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from released to reported as finished</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReleasedToReportedAsFinishedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from released to reported as finished</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReleasedToEndedStatusChangedAllowed name="IsReleasedToEndedStatusChangedAllowed">IsReleasedToEndedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from released to ended</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReleasedToEndedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from released to ended</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStartedToCreatedStatusChangedAllowed name="IsStartedToCreatedStatusChangedAllowed">IsStartedToCreatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from started to created</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStartedToCreatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from started to created</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStartedToEstimatedStatusChangedAllowed name="IsStartedToEstimatedStatusChangedAllowed">IsStartedToEstimatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from started to estimated</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStartedToEstimatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from started to estimated</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStartedToOperationsScheduledStatusChangedAllowed name="IsStartedToOperationsScheduledStatusChangedAllowed">IsStartedToOperationsScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from started to operations scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStartedToOperationsScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from started to operations scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStartedToJobScheduledStatusChangedAllowed name="IsStartedToJobScheduledStatusChangedAllowed">IsStartedToJobScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from started to job scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStartedToJobScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from started to job scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStartedToReleasedStatusChangedAllowed name="IsStartedToReleasedStatusChangedAllowed">IsStartedToReleasedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from started to released</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStartedToReleasedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from started to released</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStartedToReportedAsFinishedStatusChangedAllowed name="IsStartedToReportedAsFinishedStatusChangedAllowed">IsStartedToReportedAsFinishedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from started to reported as finished</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStartedToReportedAsFinishedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from started to reported as finished</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStartedToEndedStatusChangedAllowed name="IsStartedToEndedStatusChangedAllowed">IsStartedToEndedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from started to ended</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStartedToEndedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from started to ended</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportedAsFinishedToCreatedStatusChangedAllowed name="IsReportedAsFinishedToCreatedStatusChangedAllowed">IsReportedAsFinishedToCreatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from reported as finished to created</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportedAsFinishedToCreatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from reported as finished to created</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportedAsFinishedToEstimatedStatusChangedAllowed name="IsReportedAsFinishedToEstimatedStatusChangedAllowed">IsReportedAsFinishedToEstimatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from reported as finished to estimated</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportedAsFinishedToEstimatedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from reported as finished to estimated</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportedAsFinishedToOperationsScheduledStatusChangedAllowed name="IsReportedAsFinishedToOperationsScheduledStatusChangedAllowed">IsReportedAsFinishedToOperationsScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from reported as finished to operations scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportedAsFinishedToOperationsScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from reported as finished to operations scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportedAsFinishedToJobScheduledStatusChangedAllowed name="IsReportedAsFinishedToJobScheduledStatusChangedAllowed">IsReportedAsFinishedToJobScheduledStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from reported as finished to job scheduled</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportedAsFinishedToJobScheduledStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from reported as finished to job scheduled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportedAsFinishedToReleasedStatusChangedAllowed name="IsReportedAsFinishedToReleasedStatusChangedAllowed">IsReportedAsFinishedToReleasedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from reported as finished to released</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportedAsFinishedToReleasedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from reported as finished to released</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportedAsFinishedToStartedStatusChangedAllowed name="IsReportedAsFinishedToStartedStatusChangedAllowed">IsReportedAsFinishedToStartedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from reported as finished to started as finished</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportedAsFinishedToStartedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from reported as finished to started as finished</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportedAsFinishedToEndedStatusChangedAllowed name="IsReportedAsFinishedToEndedStatusChangedAllowed">IsReportedAsFinishedToEndedStatusChangedAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow production order status change from reported as finished to ended</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportedAsFinishedToEndedStatusChangedAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow production order status change from reported as finished to ended</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseProductReceiptAutomaticBOMConsumptionRule name="PurchaseProductReceiptAutomaticBOMConsumptionRule">PurchaseProductReceiptAutomaticBOMConsumptionRule</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseProductReceiptAutomaticBOMConsumptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportAsFinishedAutomaticBOMConsumptionRule name="ReportAsFinishedAutomaticBOMConsumptionRule">ReportAsFinishedAutomaticBOMConsumptionRule</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportAsFinishedAutomaticBOMConsumptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionStartAutomaticBOMConsumptionRule name="ProductionStartAutomaticBOMConsumptionRule">ProductionStartAutomaticBOMConsumptionRule</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionStartAutomaticBOMConsumptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPickingListProductionJournalNameId name="DefaultPickingListProductionJournalNameId">DefaultPickingListProductionJournalNameId</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPickingListProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSchedulingConsiderFiniteCapacityByDefault name="WillSchedulingConsiderFiniteCapacityByDefault">WillSchedulingConsiderFiniteCapacityByDefault</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSchedulingConsiderFiniteCapacityByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionEndingScrapMethod name="ProductionEndingScrapMethod">ProductionEndingScrapMethod</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionEndingScrapMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportedAsFinishedDeleteCapacityReservations name="WillReportedAsFinishedDeleteCapacityReservations">WillReportedAsFinishedDeleteCapacityReservations</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportedAsFinishedDeleteCapacityReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedIncreaseRemainingQuantityWithErrorQuantity name="WillReportAsFinishedIncreaseRemainingQuantityWithErrorQuantity">WillReportAsFinishedIncreaseRemainingQuantityWithErrorQuantity</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedIncreaseRemainingQuantityWithErrorQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultJobCardProductionJournalNameId name="DefaultJobCardProductionJournalNameId">DefaultJobCardProductionJournalNameId</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultJobCardProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRouteCardPostingUpdateCapacityPlan name="WillRouteCardPostingUpdateCapacityPlan">WillRouteCardPostingUpdateCapacityPlan</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRouteCardPostingUpdateCapacityPlan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCapacityPlanningIncludePlannedOrders name="WillCapacityPlanningIncludePlannedOrders">WillCapacityPlanningIncludePlannedOrders</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCapacityPlanningIncludePlannedOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCapacityPlanningIncludeProjectHourForecasts name="WillCapacityPlanningIncludeProjectHourForecasts">WillCapacityPlanningIncludeProjectHourForecasts</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCapacityPlanningIncludeProjectHourForecasts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRouteCardHourCostCategoryMandatory name="IsRouteCardHourCostCategoryMandatory">IsRouteCardHourCostCategoryMandatory</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRouteCardHourCostCategoryMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRouteCardQuantityCostCategoryMandatory name="IsRouteCardQuantityCostCategoryMandatory">IsRouteCardQuantityCostCategoryMandatory</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRouteCardQuantityCostCategoryMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSchedulingConsiderFiniteMaterialsByDefault name="WillSchedulingConsiderFiniteMaterialsByDefault">WillSchedulingConsiderFiniteMaterialsByDefault</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSchedulingConsiderFiniteMaterialsByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumJobSchedulingJobLeadTimeDays name="MaximumJobSchedulingJobLeadTimeDays">MaximumJobSchedulingJobLeadTimeDays</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumJobSchedulingJobLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedUseEstimatedUnitCost name="WillReportAsFinishedUseEstimatedUnitCost">WillReportAsFinishedUseEstimatedUnitCost</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedUseEstimatedUnitCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionPostingExcludeTransactionType name="WillProductionPostingExcludeTransactionType">WillProductionPostingExcludeTransactionType</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionPostingExcludeTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionPickingListPostInLedger name="WillProductionPickingListPostInLedger">WillProductionPickingListPostInLedger</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionPickingListPostInLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedPostInLedger name="WillReportAsFinishedPostInLedger">WillReportAsFinishedPostInLedger</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedPostInLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionJournalNameId name="DefaultProductionJournalNameId">DefaultProductionJournalNameId</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionLineReleaseToWarehousePrinciple name="ProductionLineReleaseToWarehousePrinciple">ProductionLineReleaseToWarehousePrinciple</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionLineReleaseToWarehousePrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSchedulingConsiderFinitePropertyByDefault name="WillSchedulingConsiderFinitePropertyByDefault">WillSchedulingConsiderFinitePropertyByDefault</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSchedulingConsiderFinitePropertyByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchaseProductReceiptDisplayRouteCardInformation name="WillPurchaseProductReceiptDisplayRouteCardInformation">WillPurchaseProductReceiptDisplayRouteCardInformation</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseProductReceiptDisplayRouteCardInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseProductReceiptAutomaticRouteConsumptionRule name="PurchaseProductReceiptAutomaticRouteConsumptionRule">PurchaseProductReceiptAutomaticRouteConsumptionRule</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseProductReceiptAutomaticRouteConsumptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportAsFinishedAutomaticRouteConsumptionRule name="ReportAsFinishedAutomaticRouteConsumptionRule">ReportAsFinishedAutomaticRouteConsumptionRule</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportAsFinishedAutomaticRouteConsumptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionStartAutomaticRouteConsumptionRule name="ProductionStartAutomaticRouteConsumptionRule">ProductionStartAutomaticRouteConsumptionRule</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionStartAutomaticRouteConsumptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRouteCardProductionJournalNameId name="DefaultRouteCardProductionJournalNameId">DefaultRouteCardProductionJournalNameId</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRouteCardProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticSchedulingMethod name="AutomaticSchedulingMethod">AutomaticSchedulingMethod</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticSchedulingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionEstimationCalculateEstimatedUnitCost name="WillProductionEstimationCalculateEstimatedUnitCost">WillProductionEstimationCalculateEstimatedUnitCost</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionEstimationCalculateEstimatedUnitCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsApprovedRouteEditingAllowed name="IsApprovedRouteEditingAllowed">IsApprovedRouteEditingAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsApprovedRouteEditingAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRouteApprovalRemovalAllowed name="IsRouteApprovalRemovalAllowed">IsRouteApprovalRemovalAllowed</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRouteApprovalRemovalAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreRouteVersionValidDatesMandatory name="AreRouteVersionValidDatesMandatory">AreRouteVersionValidDatesMandatory</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreRouteVersionValidDatesMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreRouteNetworksEnabled name="AreRouteNetworksEnabled">AreRouteNetworksEnabled</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreRouteNetworksEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProdParametersRelationshipId name="BackingTable_ProdParametersRelationshipId">BackingTable_ProdParametersRelationshipId</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProdParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/ProdParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/ProdParameters.cdm.json/ProdParameters</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/ProdParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdProductionControlParametersEntity (this entity)  

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
