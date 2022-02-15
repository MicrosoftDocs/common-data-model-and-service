---
title: ReqMasterPlanEntity in MasterPlanning - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Master plans in MasterPlanning(ReqMasterPlanEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ReqMasterPlanEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Master plans</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ForecastModelId](#ForecastModelId)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[ForecastRequirementReductionMethod](#ForecastRequirementReductionMethod)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[ContinuityPlanId](#ContinuityPlanId)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[MasterPlanDescription](#MasterPlanDescription)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[MasterPlanId](#MasterPlanId)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningIncludeDemandForecast](#WillMasterPlanningIncludeDemandForecast)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningIncludeSupplyForecast](#WillMasterPlanningIncludeSupplyForecast)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillActionMessageGenerationUsePlannedPurchaseOrderRequirementDateAsPostponedDate](#WillActionMessageGenerationUsePlannedPurchaseOrderRequirementDateAsPostponedDate)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillCapacitySchedulingConsiderBottleneckResourcesAsFinite](#WillCapacitySchedulingConsiderBottleneckResourcesAsFinite)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillCapacitySchedulingConsiderAlreadyReservedCapacity](#WillCapacitySchedulingConsiderAlreadyReservedCapacity)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillCapacitySchedulingUseResourceProperties](#WillCapacitySchedulingUseResourceProperties)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[PlannedProductionOrderSchedulingMethod](#PlannedProductionOrderSchedulingMethod)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[BackwardSchedulingCapacityTimeFenceDays](#BackwardSchedulingCapacityTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningAddCalculatedDelayToPlannedPurchaseOrderRequirementDate](#WillMasterPlanningAddCalculatedDelayToPlannedPurchaseOrderRequirementDate)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningAddCalculatedDelayToPlannedProductionOrderRequirementDate](#WillMasterPlanningAddCalculatedDelayToPlannedProductionOrderRequirementDate)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningAddCalculatedDelayToPlannedTransferOrderRequirementDate](#WillMasterPlanningAddCalculatedDelayToPlannedTransferOrderRequirementDate)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningIncludePurchaseRequisitions](#WillMasterPlanningIncludePurchaseRequisitions)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningIncludeContinuityPlan](#WillMasterPlanningIncludeContinuityPlan)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsContinuityPlanTimeFenceEnabled](#IsContinuityPlanTimeFenceEnabled)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[ContinuityPlanTimeFenceDays](#ContinuityPlanTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[RequirementDateDeductedSafetyIssueMarginDays](#RequirementDateDeductedSafetyIssueMarginDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningIncludeDownstreamDemand](#WillMasterPlanningIncludeDownstreamDemand)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsOnHandConsumptionStrategyEnabled](#IsOnHandConsumptionStrategyEnabled)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[OnHandConsumptionStrategy](#OnHandConsumptionStrategy)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningConsiderShelfLifeDates](#WillMasterPlanningConsiderShelfLifeDates)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[PlannedOrderNumberSequenceRecId](#PlannedOrderNumberSequenceRecId)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[PlannedOrderNumberSequenceCode](#PlannedOrderNumberSequenceCode)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[MasterPlanCalculationSessionNumberSequenceRecId](#MasterPlanCalculationSessionNumberSequenceRecId)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[MasterPlanCalculationSessionNumberSequenceCode](#MasterPlanCalculationSessionNumberSequenceCode)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[ItemLeadTimeAddedReorderMarginDays](#ItemLeadTimeAddedReorderMarginDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[PlannedProductionOrderSequencingTimeFenceDays](#PlannedProductionOrderSequencingTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningSequencePlannedOrders](#WillMasterPlanningSequencePlannedOrders)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[PlannedProductionOrderSequencingBucketType](#PlannedProductionOrderSequencingBucketType)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[PlannedProductionOrderSequencingPeriodType](#PlannedProductionOrderSequencingPeriodType)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[PlannedProductionOrderSequencingCampaignCycleBucketCount](#PlannedProductionOrderSequencingCampaignCycleBucketCount)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[QuotationProbabilityPercentageThreshold](#QuotationProbabilityPercentageThreshold)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningSuggestFuturePlannedOrderDatesOnly](#WillMasterPlanningSuggestFuturePlannedOrderDatesOnly)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningAddCalculatedDelayToPlannedKanbanRequirementDate](#WillMasterPlanningAddCalculatedDelayToPlannedKanbanRequirementDate)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[RequirementDateAddedSafetyReceiptMarginDays](#RequirementDateAddedSafetyReceiptMarginDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsAutomaticFirmingTimeFenceOverridden](#IsAutomaticFirmingTimeFenceOverridden)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[AutomaticFirmingTimeFenceDays](#AutomaticFirmingTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsActionTimeFenceOverridden](#IsActionTimeFenceOverridden)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[ActionTimeFenceDays](#ActionTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[ApprovedRequisitionTimeFenceDays](#ApprovedRequisitionTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[BottleneckResourceFiniteCapacitySchedulingTimeFenceDays](#BottleneckResourceFiniteCapacitySchedulingTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[CoverageTimeFenceDays](#CoverageTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsCapacityTimeFenceOverridden](#IsCapacityTimeFenceOverridden)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[CapacitySchedulingTimeFenceDays](#CapacitySchedulingTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsApprovedRequisitionsTimeFenceOverridden](#IsApprovedRequisitionsTimeFenceOverridden)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[FiniteCapacitySchdedulingTimeFenceDays](#FiniteCapacitySchdedulingTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsCoverageTimeFenceOverridden](#IsCoverageTimeFenceOverridden)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsBOMOrFormulaExplosionTimeFenceOverridden](#IsBOMOrFormulaExplosionTimeFenceOverridden)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[BOMOrFormulaExplosionTimeFenceDays](#BOMOrFormulaExplosionTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[CalculateDelayTimeFenceDays](#CalculateDelayTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsFreezeTimeFenceOverridden](#IsFreezeTimeFenceOverridden)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[FreezeTimeFenceDays](#FreezeTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsForecastDemandPlanTimeFenceOverridden](#IsForecastDemandPlanTimeFenceOverridden)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[ForecastDemandPlanTimeFenceDays](#ForecastDemandPlanTimeFenceDays)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[IsCalculatedDaysTimeFenceOverridden](#IsCalculatedDaysTimeFenceOverridden)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningIncludeOnHand](#WillMasterPlanningIncludeOnHand)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningIncludeExpectedInventoryTransactions](#WillMasterPlanningIncludeExpectedInventoryTransactions)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningIncludeQuotations](#WillMasterPlanningIncludeQuotations)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[WillMasterPlanningIncludeRFQs](#WillMasterPlanningIncludeRFQs)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[BackingTable_ReqPlanSchedRelationshipId](#BackingTable_ReqPlanSchedRelationshipId)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ReqMasterPlanEntity.md" target="_blank">MasterPlanning/ReqMasterPlanEntity</a>|

### <a href=#ForecastModelId name="ForecastModelId">ForecastModelId</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastRequirementReductionMethod name="ForecastRequirementReductionMethod">ForecastRequirementReductionMethod</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastRequirementReductionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContinuityPlanId name="ContinuityPlanId">ContinuityPlanId</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContinuityPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MasterPlanDescription name="MasterPlanDescription">MasterPlanDescription</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MasterPlanDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MasterPlanId name="MasterPlanId">MasterPlanId</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MasterPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningIncludeDemandForecast name="WillMasterPlanningIncludeDemandForecast">WillMasterPlanningIncludeDemandForecast</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningIncludeDemandForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningIncludeSupplyForecast name="WillMasterPlanningIncludeSupplyForecast">WillMasterPlanningIncludeSupplyForecast</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningIncludeSupplyForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillActionMessageGenerationUsePlannedPurchaseOrderRequirementDateAsPostponedDate name="WillActionMessageGenerationUsePlannedPurchaseOrderRequirementDateAsPostponedDate">WillActionMessageGenerationUsePlannedPurchaseOrderRequirementDateAsPostponedDate</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillActionMessageGenerationUsePlannedPurchaseOrderRequirementDateAsPostponedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCapacitySchedulingConsiderBottleneckResourcesAsFinite name="WillCapacitySchedulingConsiderBottleneckResourcesAsFinite">WillCapacitySchedulingConsiderBottleneckResourcesAsFinite</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCapacitySchedulingConsiderBottleneckResourcesAsFinite attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCapacitySchedulingConsiderAlreadyReservedCapacity name="WillCapacitySchedulingConsiderAlreadyReservedCapacity">WillCapacitySchedulingConsiderAlreadyReservedCapacity</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCapacitySchedulingConsiderAlreadyReservedCapacity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCapacitySchedulingUseResourceProperties name="WillCapacitySchedulingUseResourceProperties">WillCapacitySchedulingUseResourceProperties</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCapacitySchedulingUseResourceProperties attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedProductionOrderSchedulingMethod name="PlannedProductionOrderSchedulingMethod">PlannedProductionOrderSchedulingMethod</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedProductionOrderSchedulingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackwardSchedulingCapacityTimeFenceDays name="BackwardSchedulingCapacityTimeFenceDays">BackwardSchedulingCapacityTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackwardSchedulingCapacityTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningAddCalculatedDelayToPlannedPurchaseOrderRequirementDate name="WillMasterPlanningAddCalculatedDelayToPlannedPurchaseOrderRequirementDate">WillMasterPlanningAddCalculatedDelayToPlannedPurchaseOrderRequirementDate</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningAddCalculatedDelayToPlannedPurchaseOrderRequirementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningAddCalculatedDelayToPlannedProductionOrderRequirementDate name="WillMasterPlanningAddCalculatedDelayToPlannedProductionOrderRequirementDate">WillMasterPlanningAddCalculatedDelayToPlannedProductionOrderRequirementDate</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningAddCalculatedDelayToPlannedProductionOrderRequirementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningAddCalculatedDelayToPlannedTransferOrderRequirementDate name="WillMasterPlanningAddCalculatedDelayToPlannedTransferOrderRequirementDate">WillMasterPlanningAddCalculatedDelayToPlannedTransferOrderRequirementDate</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningAddCalculatedDelayToPlannedTransferOrderRequirementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningIncludePurchaseRequisitions name="WillMasterPlanningIncludePurchaseRequisitions">WillMasterPlanningIncludePurchaseRequisitions</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningIncludePurchaseRequisitions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningIncludeContinuityPlan name="WillMasterPlanningIncludeContinuityPlan">WillMasterPlanningIncludeContinuityPlan</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningIncludeContinuityPlan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsContinuityPlanTimeFenceEnabled name="IsContinuityPlanTimeFenceEnabled">IsContinuityPlanTimeFenceEnabled</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsContinuityPlanTimeFenceEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContinuityPlanTimeFenceDays name="ContinuityPlanTimeFenceDays">ContinuityPlanTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContinuityPlanTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequirementDateDeductedSafetyIssueMarginDays name="RequirementDateDeductedSafetyIssueMarginDays">RequirementDateDeductedSafetyIssueMarginDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequirementDateDeductedSafetyIssueMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningIncludeDownstreamDemand name="WillMasterPlanningIncludeDownstreamDemand">WillMasterPlanningIncludeDownstreamDemand</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningIncludeDownstreamDemand attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOnHandConsumptionStrategyEnabled name="IsOnHandConsumptionStrategyEnabled">IsOnHandConsumptionStrategyEnabled</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOnHandConsumptionStrategyEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHandConsumptionStrategy name="OnHandConsumptionStrategy">OnHandConsumptionStrategy</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHandConsumptionStrategy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningConsiderShelfLifeDates name="WillMasterPlanningConsiderShelfLifeDates">WillMasterPlanningConsiderShelfLifeDates</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningConsiderShelfLifeDates attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderNumberSequenceRecId name="PlannedOrderNumberSequenceRecId">PlannedOrderNumberSequenceRecId</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderNumberSequenceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderNumberSequenceCode name="PlannedOrderNumberSequenceCode">PlannedOrderNumberSequenceCode</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderNumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MasterPlanCalculationSessionNumberSequenceRecId name="MasterPlanCalculationSessionNumberSequenceRecId">MasterPlanCalculationSessionNumberSequenceRecId</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MasterPlanCalculationSessionNumberSequenceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MasterPlanCalculationSessionNumberSequenceCode name="MasterPlanCalculationSessionNumberSequenceCode">MasterPlanCalculationSessionNumberSequenceCode</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MasterPlanCalculationSessionNumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemLeadTimeAddedReorderMarginDays name="ItemLeadTimeAddedReorderMarginDays">ItemLeadTimeAddedReorderMarginDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLeadTimeAddedReorderMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedProductionOrderSequencingTimeFenceDays name="PlannedProductionOrderSequencingTimeFenceDays">PlannedProductionOrderSequencingTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedProductionOrderSequencingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningSequencePlannedOrders name="WillMasterPlanningSequencePlannedOrders">WillMasterPlanningSequencePlannedOrders</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningSequencePlannedOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedProductionOrderSequencingBucketType name="PlannedProductionOrderSequencingBucketType">PlannedProductionOrderSequencingBucketType</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedProductionOrderSequencingBucketType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedProductionOrderSequencingPeriodType name="PlannedProductionOrderSequencingPeriodType">PlannedProductionOrderSequencingPeriodType</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedProductionOrderSequencingPeriodType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedProductionOrderSequencingCampaignCycleBucketCount name="PlannedProductionOrderSequencingCampaignCycleBucketCount">PlannedProductionOrderSequencingCampaignCycleBucketCount</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedProductionOrderSequencingCampaignCycleBucketCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationProbabilityPercentageThreshold name="QuotationProbabilityPercentageThreshold">QuotationProbabilityPercentageThreshold</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationProbabilityPercentageThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningSuggestFuturePlannedOrderDatesOnly name="WillMasterPlanningSuggestFuturePlannedOrderDatesOnly">WillMasterPlanningSuggestFuturePlannedOrderDatesOnly</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningSuggestFuturePlannedOrderDatesOnly attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningAddCalculatedDelayToPlannedKanbanRequirementDate name="WillMasterPlanningAddCalculatedDelayToPlannedKanbanRequirementDate">WillMasterPlanningAddCalculatedDelayToPlannedKanbanRequirementDate</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningAddCalculatedDelayToPlannedKanbanRequirementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequirementDateAddedSafetyReceiptMarginDays name="RequirementDateAddedSafetyReceiptMarginDays">RequirementDateAddedSafetyReceiptMarginDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequirementDateAddedSafetyReceiptMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutomaticFirmingTimeFenceOverridden name="IsAutomaticFirmingTimeFenceOverridden">IsAutomaticFirmingTimeFenceOverridden</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutomaticFirmingTimeFenceOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticFirmingTimeFenceDays name="AutomaticFirmingTimeFenceDays">AutomaticFirmingTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticFirmingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActionTimeFenceOverridden name="IsActionTimeFenceOverridden">IsActionTimeFenceOverridden</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActionTimeFenceOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActionTimeFenceDays name="ActionTimeFenceDays">ActionTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovedRequisitionTimeFenceDays name="ApprovedRequisitionTimeFenceDays">ApprovedRequisitionTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovedRequisitionTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BottleneckResourceFiniteCapacitySchedulingTimeFenceDays name="BottleneckResourceFiniteCapacitySchedulingTimeFenceDays">BottleneckResourceFiniteCapacitySchedulingTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BottleneckResourceFiniteCapacitySchedulingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageTimeFenceDays name="CoverageTimeFenceDays">CoverageTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCapacityTimeFenceOverridden name="IsCapacityTimeFenceOverridden">IsCapacityTimeFenceOverridden</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCapacityTimeFenceOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacitySchedulingTimeFenceDays name="CapacitySchedulingTimeFenceDays">CapacitySchedulingTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacitySchedulingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsApprovedRequisitionsTimeFenceOverridden name="IsApprovedRequisitionsTimeFenceOverridden">IsApprovedRequisitionsTimeFenceOverridden</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsApprovedRequisitionsTimeFenceOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiniteCapacitySchdedulingTimeFenceDays name="FiniteCapacitySchdedulingTimeFenceDays">FiniteCapacitySchdedulingTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiniteCapacitySchdedulingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCoverageTimeFenceOverridden name="IsCoverageTimeFenceOverridden">IsCoverageTimeFenceOverridden</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCoverageTimeFenceOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBOMOrFormulaExplosionTimeFenceOverridden name="IsBOMOrFormulaExplosionTimeFenceOverridden">IsBOMOrFormulaExplosionTimeFenceOverridden</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBOMOrFormulaExplosionTimeFenceOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMOrFormulaExplosionTimeFenceDays name="BOMOrFormulaExplosionTimeFenceDays">BOMOrFormulaExplosionTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMOrFormulaExplosionTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculateDelayTimeFenceDays name="CalculateDelayTimeFenceDays">CalculateDelayTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateDelayTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFreezeTimeFenceOverridden name="IsFreezeTimeFenceOverridden">IsFreezeTimeFenceOverridden</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFreezeTimeFenceOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreezeTimeFenceDays name="FreezeTimeFenceDays">FreezeTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreezeTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsForecastDemandPlanTimeFenceOverridden name="IsForecastDemandPlanTimeFenceOverridden">IsForecastDemandPlanTimeFenceOverridden</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsForecastDemandPlanTimeFenceOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastDemandPlanTimeFenceDays name="ForecastDemandPlanTimeFenceDays">ForecastDemandPlanTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastDemandPlanTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCalculatedDaysTimeFenceOverridden name="IsCalculatedDaysTimeFenceOverridden">IsCalculatedDaysTimeFenceOverridden</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCalculatedDaysTimeFenceOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningIncludeOnHand name="WillMasterPlanningIncludeOnHand">WillMasterPlanningIncludeOnHand</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningIncludeOnHand attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningIncludeExpectedInventoryTransactions name="WillMasterPlanningIncludeExpectedInventoryTransactions">WillMasterPlanningIncludeExpectedInventoryTransactions</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningIncludeExpectedInventoryTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningIncludeQuotations name="WillMasterPlanningIncludeQuotations">WillMasterPlanningIncludeQuotations</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningIncludeQuotations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlanningIncludeRFQs name="WillMasterPlanningIncludeRFQs">WillMasterPlanningIncludeRFQs</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlanningIncludeRFQs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ReqPlanSchedRelationshipId name="BackingTable_ReqPlanSchedRelationshipId">BackingTable_ReqPlanSchedRelationshipId</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ReqPlanSchedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/ReqPlanSched.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlanSched.cdm.json/ReqPlanSched</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/ReqPlanSched.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/ReqMasterPlanEntity (this entity)  

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
