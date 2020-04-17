---
title: ReqMasterPlanningParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# ReqMasterPlanningParametersEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/MasterPlanning/ReqMasterPlanningParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WillCompletedStaticPlanBeCopiedToDynamicPlan](#WillCompletedStaticPlanBeCopiedToDynamicPlan)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[MaximumBundleSize](#MaximumBundleSize)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[JobSchedulingStartTimeRule](#JobSchedulingStartTimeRule)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[CurrentForecastPlanId](#CurrentForecastPlanId)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[CurrentDynamicMasterPlanId](#CurrentDynamicMasterPlanId)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[CurrentStaticMasterPlanId](#CurrentStaticMasterPlanId)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[DefaultTransferOrderPeriodGroupingRule](#DefaultTransferOrderPeriodGroupingRule)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[DefaultInventoryMarkingRule](#DefaultInventoryMarkingRule)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[WillMasterPlanningCalculateDynamicNegativeDays](#WillMasterPlanningCalculateDynamicNegativeDays)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[IsSafetyMarginsUsingWorkingDays](#IsSafetyMarginsUsingWorkingDays)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[WillErrorsAbortFirmingByDefault](#WillErrorsAbortFirmingByDefault)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[DefaultPurchaseOrderPeriodGroupingRule](#DefaultPurchaseOrderPeriodGroupingRule)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[ArePurchaseOrdersCombinedPerBuyerGroupByDefault](#ArePurchaseOrdersCombinedPerBuyerGroupByDefault)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[ArePurchaseOrdersCombinedPerPurchaseAgreementByDefault](#ArePurchaseOrdersCombinedPerPurchaseAgreementByDefault)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[ArePurchaseOrdersCombinedPerVendorByDefault](#ArePurchaseOrdersCombinedPerVendorByDefault)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[ArePurchaseOrdersAssignedPurchaseAgreements](#ArePurchaseOrdersAssignedPurchaseAgreements)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[WillVendorSelectionConsiderPriceAgreements](#WillVendorSelectionConsiderPriceAgreements)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[PriceAgreementVendorSelectionRule](#PriceAgreementVendorSelectionRule)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[DelayStartTime](#DelayStartTime)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[DefaultPlannedOrderReceiptTime](#DefaultPlannedOrderReceiptTime)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[DefaultMasterPlanningProductCoverageGroupId](#DefaultMasterPlanningProductCoverageGroupId)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[TodaysWorkCalendarId](#TodaysWorkCalendarId)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[CachingLevel](#CachingLevel)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[WillSchedulingConsiderProductionOrderCapacityReservations](#WillSchedulingConsiderProductionOrderCapacityReservations)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[WillSchedulingConsiderProjectCapacityReservations](#WillSchedulingConsiderProjectCapacityReservations)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[AreAllPlanningProcessesDisabled](#AreAllPlanningProcessesDisabled)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[DefaultNumberOfThreads](#DefaultNumberOfThreads)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[FirmingBundleSize](#FirmingBundleSize)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[WillPostProcessingAutomaticallyFilterItems](#WillPostProcessingAutomaticallyFilterItems)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[WillPreProcessingAutomaticallyFilterItems](#WillPreProcessingAutomaticallyFilterItems)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[DefaultTransferOrderStockTransferPriceType_IN](#DefaultTransferOrderStockTransferPriceType_IN)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[DefaultTranferOrderTransferType_IN](#DefaultTranferOrderTransferType_IN)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[BackingTable_ReqParametersRelationshipId](#BackingTable_ReqParametersRelationshipId)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ReqMasterPlanningParametersEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningParametersEntity</a>|

### <a href=#WillCompletedStaticPlanBeCopiedToDynamicPlan name="WillCompletedStaticPlanBeCopiedToDynamicPlan">WillCompletedStaticPlanBeCopiedToDynamicPlan</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCompletedStaticPlanBeCopiedToDynamicPlan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumBundleSize name="MaximumBundleSize">MaximumBundleSize</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumBundleSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobSchedulingStartTimeRule name="JobSchedulingStartTimeRule">JobSchedulingStartTimeRule</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobSchedulingStartTimeRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentForecastPlanId name="CurrentForecastPlanId">CurrentForecastPlanId</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentForecastPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentDynamicMasterPlanId name="CurrentDynamicMasterPlanId">CurrentDynamicMasterPlanId</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentDynamicMasterPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentStaticMasterPlanId name="CurrentStaticMasterPlanId">CurrentStaticMasterPlanId</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentStaticMasterPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTransferOrderPeriodGroupingRule name="DefaultTransferOrderPeriodGroupingRule">DefaultTransferOrderPeriodGroupingRule</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTransferOrderPeriodGroupingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryMarkingRule name="DefaultInventoryMarkingRule">DefaultInventoryMarkingRule</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryMarkingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningCalculateDynamicNegativeDays name="WillMasterPlanningCalculateDynamicNegativeDays">WillMasterPlanningCalculateDynamicNegativeDays</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningCalculateDynamicNegativeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSafetyMarginsUsingWorkingDays name="IsSafetyMarginsUsingWorkingDays">IsSafetyMarginsUsingWorkingDays</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSafetyMarginsUsingWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillErrorsAbortFirmingByDefault name="WillErrorsAbortFirmingByDefault">WillErrorsAbortFirmingByDefault</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillErrorsAbortFirmingByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPurchaseOrderPeriodGroupingRule name="DefaultPurchaseOrderPeriodGroupingRule">DefaultPurchaseOrderPeriodGroupingRule</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPurchaseOrderPeriodGroupingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseOrdersCombinedPerBuyerGroupByDefault name="ArePurchaseOrdersCombinedPerBuyerGroupByDefault">ArePurchaseOrdersCombinedPerBuyerGroupByDefault</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseOrdersCombinedPerBuyerGroupByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseOrdersCombinedPerPurchaseAgreementByDefault name="ArePurchaseOrdersCombinedPerPurchaseAgreementByDefault">ArePurchaseOrdersCombinedPerPurchaseAgreementByDefault</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseOrdersCombinedPerPurchaseAgreementByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseOrdersCombinedPerVendorByDefault name="ArePurchaseOrdersCombinedPerVendorByDefault">ArePurchaseOrdersCombinedPerVendorByDefault</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseOrdersCombinedPerVendorByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseOrdersAssignedPurchaseAgreements name="ArePurchaseOrdersAssignedPurchaseAgreements">ArePurchaseOrdersAssignedPurchaseAgreements</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseOrdersAssignedPurchaseAgreements attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillVendorSelectionConsiderPriceAgreements name="WillVendorSelectionConsiderPriceAgreements">WillVendorSelectionConsiderPriceAgreements</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillVendorSelectionConsiderPriceAgreements attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceAgreementVendorSelectionRule name="PriceAgreementVendorSelectionRule">PriceAgreementVendorSelectionRule</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceAgreementVendorSelectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DelayStartTime name="DelayStartTime">DelayStartTime</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DelayStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPlannedOrderReceiptTime name="DefaultPlannedOrderReceiptTime">DefaultPlannedOrderReceiptTime</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPlannedOrderReceiptTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultMasterPlanningProductCoverageGroupId name="DefaultMasterPlanningProductCoverageGroupId">DefaultMasterPlanningProductCoverageGroupId</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultMasterPlanningProductCoverageGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TodaysWorkCalendarId name="TodaysWorkCalendarId">TodaysWorkCalendarId</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TodaysWorkCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CachingLevel name="CachingLevel">CachingLevel</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CachingLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSchedulingConsiderProductionOrderCapacityReservations name="WillSchedulingConsiderProductionOrderCapacityReservations">WillSchedulingConsiderProductionOrderCapacityReservations</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSchedulingConsiderProductionOrderCapacityReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSchedulingConsiderProjectCapacityReservations name="WillSchedulingConsiderProjectCapacityReservations">WillSchedulingConsiderProjectCapacityReservations</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSchedulingConsiderProjectCapacityReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreAllPlanningProcessesDisabled name="AreAllPlanningProcessesDisabled">AreAllPlanningProcessesDisabled</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreAllPlanningProcessesDisabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultNumberOfThreads name="DefaultNumberOfThreads">DefaultNumberOfThreads</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultNumberOfThreads attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirmingBundleSize name="FirmingBundleSize">FirmingBundleSize</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirmingBundleSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPostProcessingAutomaticallyFilterItems name="WillPostProcessingAutomaticallyFilterItems">WillPostProcessingAutomaticallyFilterItems</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPostProcessingAutomaticallyFilterItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPreProcessingAutomaticallyFilterItems name="WillPreProcessingAutomaticallyFilterItems">WillPreProcessingAutomaticallyFilterItems</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPreProcessingAutomaticallyFilterItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTransferOrderStockTransferPriceType_IN name="DefaultTransferOrderStockTransferPriceType_IN">DefaultTransferOrderStockTransferPriceType_IN</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTransferOrderStockTransferPriceType_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTranferOrderTransferType_IN name="DefaultTranferOrderTransferType_IN">DefaultTranferOrderTransferType_IN</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTranferOrderTransferType_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ReqParametersRelationshipId name="BackingTable_ReqParametersRelationshipId">BackingTable_ReqParametersRelationshipId</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ReqParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Parameter/ReqParameters.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/Parameter/ReqParameters.cdm.json/ReqParameters</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Parameter/ReqParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/ReqMasterPlanningParametersEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
