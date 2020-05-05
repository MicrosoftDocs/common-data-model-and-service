---
title: ProdSiteSpecificProductionControlParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Production control parameters by site

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdSiteSpecificProductionControlParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production control parameters by site</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InventDimId](#InventDimId)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[ProductionSiteId](#ProductionSiteId)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsCreatedToEstimatedStatusChangedAllowed](#IsCreatedToEstimatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsCreatedToOperationsScheduledStatusChangedAllowed](#IsCreatedToOperationsScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsCreatedToJobScheduledStatusChangedAllowed](#IsCreatedToJobScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsCreatedToReleasedStatusChangedAllowed](#IsCreatedToReleasedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsCreatedToStartedStatusChangedAllowed](#IsCreatedToStartedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsCreatedToReportedAsFinishedStatusChangedAllowed](#IsCreatedToReportedAsFinishedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsCreatedToEndedStatusChangedAllowed](#IsCreatedToEndedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsEstimatedToCreatedStatusChangedAllowed](#IsEstimatedToCreatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsEstimatedToOperationsScheduledStatusChangedAllowed](#IsEstimatedToOperationsScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsEstimatedToJobScheduledStatusChangedAllowed](#IsEstimatedToJobScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsEstimatedToReleasedStatusChangedAllowed](#IsEstimatedToReleasedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsEstimatedToStartedStatusChangedAllowed](#IsEstimatedToStartedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsEstimatedToReportedAsFinishedStatusChangedAllowed](#IsEstimatedToReportedAsFinishedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsEstimatedToEndedStatusChangedAllowed](#IsEstimatedToEndedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsOperationsScheduledToCreatedStatusChangedAllowed](#IsOperationsScheduledToCreatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsOperationsScheduledToEstimatedStatusChangedAllowed](#IsOperationsScheduledToEstimatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsOperationsScheduledToJobScheduledStatusChangedAllowed](#IsOperationsScheduledToJobScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsOperationsScheduledToReleasedStatusChangedAllowed](#IsOperationsScheduledToReleasedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsOperationsScheduledToStartedStatusChangedAllowed](#IsOperationsScheduledToStartedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsOperationsScheduledToReportedAsFinishedStatusChangedAllowed](#IsOperationsScheduledToReportedAsFinishedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsOperationsScheduledToEndedStatusChangedAllowed](#IsOperationsScheduledToEndedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsJobScheduledToCreatedStatusChangedAllowed](#IsJobScheduledToCreatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsJobScheduledToEstimatedStatusChangedAllowed](#IsJobScheduledToEstimatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsJobScheduledToOperationsScheduledStatusChangedAllowed](#IsJobScheduledToOperationsScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsJobScheduledToReleasedStatusChangedAllowed](#IsJobScheduledToReleasedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsJobScheduledToStartedStatusChangedAllowed](#IsJobScheduledToStartedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsJobScheduledToReportedAsFinishedStatusChangedAllowed](#IsJobScheduledToReportedAsFinishedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsJobScheduledToEndedStatusChangedAllowed](#IsJobScheduledToEndedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReleasedToCreatedStatusChangedAllowed](#IsReleasedToCreatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReleasedToEstimatedStatusChangedAllowed](#IsReleasedToEstimatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReleasedToOperationsScheduledStatusChangedAllowed](#IsReleasedToOperationsScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReleasedToJobScheduledStatusChangedAllowed](#IsReleasedToJobScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReleasedToStartedStatusChangedAllowed](#IsReleasedToStartedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReleasedToReportedAsFinishedStatusChangedAllowed](#IsReleasedToReportedAsFinishedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReleasedToEndedStatusChangedAllowed](#IsReleasedToEndedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsStartedToCreatedStatusChangedAllowed](#IsStartedToCreatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsStartedToEstimatedStatusChangedAllowed](#IsStartedToEstimatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsStartedToOperationsScheduledStatusChangedAllowed](#IsStartedToOperationsScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsStartedToJobScheduledStatusChangedAllowed](#IsStartedToJobScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsStartedToReleasedStatusChangedAllowed](#IsStartedToReleasedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsStartedToReportedAsFinishedStatusChangedAllowed](#IsStartedToReportedAsFinishedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsStartedToEndedStatusChangedAllowed](#IsStartedToEndedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToCreatedStatusChangedAllowed](#IsReportedAsFinishedToCreatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToEstimatedStatusChangedAllowed](#IsReportedAsFinishedToEstimatedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToOperationsScheduledStatusChangedAllowed](#IsReportedAsFinishedToOperationsScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToJobScheduledStatusChangedAllowed](#IsReportedAsFinishedToJobScheduledStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToReleasedStatusChangedAllowed](#IsReportedAsFinishedToReleasedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToStartedStatusChangedAllowed](#IsReportedAsFinishedToStartedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsReportedAsFinishedToEndedStatusChangedAllowed](#IsReportedAsFinishedToEndedStatusChangedAllowed)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[PurchaseProductReceiptAutomaticBOMConsumptionRule](#PurchaseProductReceiptAutomaticBOMConsumptionRule)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[ReportAsFinishedAutomaticBOMConsumptionRule](#ReportAsFinishedAutomaticBOMConsumptionRule)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[ProductionStartAutomaticBOMConsumptionRule](#ProductionStartAutomaticBOMConsumptionRule)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[DefaultPickingListProductionJournalNameId](#DefaultPickingListProductionJournalNameId)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillSchedulingConsiderFiniteCapacityByDefault](#WillSchedulingConsiderFiniteCapacityByDefault)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[ProductionEndingScrapMethod](#ProductionEndingScrapMethod)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillReportedAsFinishedDeleteCapacityReservations](#WillReportedAsFinishedDeleteCapacityReservations)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillReportAsFinishedIncreaseRemainingQuantityWithErrorQuantity](#WillReportAsFinishedIncreaseRemainingQuantityWithErrorQuantity)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[DefaultJobCardProductionJournalNameId](#DefaultJobCardProductionJournalNameId)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillRouteCardPostingUpdateCapacityPlan](#WillRouteCardPostingUpdateCapacityPlan)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillCapacityPlanningIncludePlannedOrders](#WillCapacityPlanningIncludePlannedOrders)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillCapacityPlanningIncludeProjectHourForecasts](#WillCapacityPlanningIncludeProjectHourForecasts)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsRouteCardHourCostCategoryMandatory](#IsRouteCardHourCostCategoryMandatory)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[IsRouteCardQuantityCostCategoryMandatory](#IsRouteCardQuantityCostCategoryMandatory)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillSchedulingConsiderFiniteMaterialsByDefault](#WillSchedulingConsiderFiniteMaterialsByDefault)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[MaximumJobSchedulingJobLeadTimeDays](#MaximumJobSchedulingJobLeadTimeDays)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillReportAsFinishedUseEstimatedUnitCost](#WillReportAsFinishedUseEstimatedUnitCost)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillProductionPostingExcludeTransactionType](#WillProductionPostingExcludeTransactionType)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillProductionPickingListPostInLedger](#WillProductionPickingListPostInLedger)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillReportAsFinishedPostInLedger](#WillReportAsFinishedPostInLedger)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[DefaultProductionJournalNameId](#DefaultProductionJournalNameId)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[ProductionLineReleaseToWarehousePrinciple](#ProductionLineReleaseToWarehousePrinciple)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillSchedulingConsiderFinitePropertyByDefault](#WillSchedulingConsiderFinitePropertyByDefault)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillPurchaseProductReceiptDisplayRouteCardInformation](#WillPurchaseProductReceiptDisplayRouteCardInformation)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[PurchaseProductReceiptAutomaticRouteConsumptionRule](#PurchaseProductReceiptAutomaticRouteConsumptionRule)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[ReportAsFinishedAutomaticRouteConsumptionRule](#ReportAsFinishedAutomaticRouteConsumptionRule)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[ProductionStartAutomaticRouteConsumptionRule](#ProductionStartAutomaticRouteConsumptionRule)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[DefaultRouteCardProductionJournalNameId](#DefaultRouteCardProductionJournalNameId)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[AutomaticSchedulingMethod](#AutomaticSchedulingMethod)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[WillProductionEstimationCalculateEstimatedUnitCost](#WillProductionEstimationCalculateEstimatedUnitCost)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[BackingTable_ProdParametersDimRelationshipId](#BackingTable_ProdParametersDimRelationshipId)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdSiteSpecificProductionControlParametersEntity.md" target="_blank">ProductionControl/ProdSiteSpecificProductionControlParametersEntity</a>|

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionSiteId name="ProductionSiteId">ProductionSiteId</a>

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreatedToEstimatedStatusChangedAllowed name="IsCreatedToEstimatedStatusChangedAllowed">IsCreatedToEstimatedStatusChangedAllowed</a>

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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

### <a href=#BackingTable_ProdParametersDimRelationshipId name="BackingTable_ProdParametersDimRelationshipId">BackingTable_ProdParametersDimRelationshipId</a>

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProdParametersDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/ProdParametersDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/ProdParametersDim.cdm.json/ProdParametersDim</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/ProdParametersDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdSiteSpecificProductionControlParametersEntity (this entity)  

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
