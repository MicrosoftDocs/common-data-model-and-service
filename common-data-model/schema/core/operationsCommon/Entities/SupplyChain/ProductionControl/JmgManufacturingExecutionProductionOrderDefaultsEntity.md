---
title: JmgManufacturingExecutionProductionOrderDefaultsEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Manufacturing execution production order defaults in ProductionControl(JmgManufacturingExecutionProductionOrderDefaultsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manufacturing execution production order defaults</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BundledJobsTimeAllocationMethod](#BundledJobsTimeAllocationMethod)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ArePieceworkProductionOrdersSpecifiedSeparately](#ArePieceworkProductionOrdersSpecifiedSeparately)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[PieceworkRateCalculationFormula](#PieceworkRateCalculationFormula)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ParameterUsageLevel](#ParameterUsageLevel)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionOrderSchedulingGranularity](#ProductionOrderSchedulingGranularity)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultProductionStartRouteCardProductionJournalNameId](#DefaultProductionStartRouteCardProductionJournalNameId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsOverlapJobRegistrationAllowed](#IsOverlapJobRegistrationAllowed)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsProcessJobRegistrationAllowed](#IsProcessJobRegistrationAllowed)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsQueueAfterJobRegistrationAllowed](#IsQueueAfterJobRegistrationAllowed)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsQueueBeforeJobRegistrationAllowed](#IsQueueBeforeJobRegistrationAllowed)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsSetupJobRegistrationAllowed](#IsSetupJobRegistrationAllowed)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsTransportJobRegistrationAllowed](#IsTransportJobRegistrationAllowed)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[AreAssistantsAssignedSecondaryOperations](#AreAssistantsAssignedSecondaryOperations)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackOpenPickingListJournal](#WillOperationFeedbackOpenPickingListJournal)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultOperationFeedbackPickingListProductionJournalNameId](#DefaultOperationFeedbackPickingListProductionJournalNameId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackAutomaticallyPostPickingList](#WillOperationFeedbackAutomaticallyPostPickingList)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillCostCalculationUseRouteCostCategory](#WillCostCalculationUseRouteCostCategory)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackAcceptSurplusDeviation](#WillOperationFeedbackAcceptSurplusDeviation)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackAcceptShortageDeviation](#WillOperationFeedbackAcceptShortageDeviation)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[MaximumAcceptedOperationFeedbackSurplusDeviationPercentage](#MaximumAcceptedOperationFeedbackSurplusDeviationPercentage)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[MaximumAcceptedOperationFeedbackShortageDeviationPercentage](#MaximumAcceptedOperationFeedbackShortageDeviationPercentage)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[OperationFeedbackQuantityValidationMethod](#OperationFeedbackQuantityValidationMethod)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[MaximumReportAsFinishedQuantity](#MaximumReportAsFinishedQuantity)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillRegistrationTransferAutomatiallyPostTimeJobCardJournal](#WillRegistrationTransferAutomatiallyPostTimeJobCardJournal)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionRegistrationLedgerDimensionSelectionRule](#ProductionRegistrationLedgerDimensionSelectionRule)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillReportAsFinishedPostingAcceptQuantityError](#WillReportAsFinishedPostingAcceptQuantityError)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ReportAsFinishedAutomaticBOMConsumptionRule](#ReportAsFinishedAutomaticBOMConsumptionRule)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultReportAsFinishedPickingListProductionJournalNameId](#DefaultReportAsFinishedPickingListProductionJournalNameId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsReportAsFinishedJobFinalByDefault](#IsReportAsFinishedJobFinalByDefault)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillReportAsFinishedCreatePickingListJournalWithEndMarkedOperations](#WillReportAsFinishedCreatePickingListJournalWithEndMarkedOperations)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillReportAsFinishedCreateRouteCardJournalWithEndMarkedLines](#WillReportAsFinishedCreateRouteCardJournalWithEndMarkedLines)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultReportAsFinishedProductionJournalNameId](#DefaultReportAsFinishedProductionJournalNameId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ReportAsFinishedAutomaticRouteConsumptionRule](#ReportAsFinishedAutomaticRouteConsumptionRule)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultReportAsFinishedRouteCardProductionJournalNameId](#DefaultReportAsFinishedRouteCardProductionJournalNameId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ReportAsFinishedProductionOrderUpdateMethod](#ReportAsFinishedProductionOrderUpdateMethod)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsReportAsFinishedUsingProductionOrderDefaults](#IsReportAsFinishedUsingProductionOrderDefaults)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartAcceptQuantityDeviation](#WillProductionStartAcceptQuantityDeviation)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartAutomaticBOMConsumptionRule](#ProductionStartAutomaticBOMConsumptionRule)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultProductionStartPickingListProductionJournalNameId](#DefaultProductionStartPickingListProductionJournalNameId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionPickingListJournalLineGroupingMethod](#ProductionPickingListJournalLineGroupingMethod)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionPickingListPostingUpdateBOMItemsFinishedPickingStatus](#WillProductionPickingListPostingUpdateBOMItemsFinishedPickingStatus)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionPickingListPostingAllowNegativeInventory](#WillProductionPickingListPostingAllowNegativeInventory)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartCreatePickingListJournalWithEndMarkedOperations](#WillProductionStartCreatePickingListJournalWithEndMarkedOperations)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartCreateRouteCardJournalWithEndMarkedLines](#WillProductionStartCreateRouteCardJournalWithEndMarkedLines)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartMaximumAcceptedQuantityDeviationPercentage](#ProductionStartMaximumAcceptedQuantityDeviationPercentage)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartAutomaticallyPostPickingList](#WillProductionStartAutomaticallyPostPickingList)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartAutomaticallyPostRouteCard](#WillProductionStartAutomaticallyPostRouteCard)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartUpdateStartedQuantity](#WillProductionStartUpdateStartedQuantity)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionPickingListPostingReduceToAvailableQuantity](#WillProductionPickingListPostingReduceToAvailableQuantity)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartStartReferencedProductionOrders](#WillProductionStartStartReferencedProductionOrders)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartAutomaticRouteConsumptionRule](#ProductionStartAutomaticRouteConsumptionRule)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartOpenPickingListJournals](#WillProductionStartOpenPickingListJournals)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartProductionOrderUpdateMethod](#ProductionStartProductionOrderUpdateMethod)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartUseProductionOrderDefaults](#WillProductionStartUseProductionOrderDefaults)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartQuantityValidationMethod](#ProductionStartQuantityValidationMethod)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[OperationFeedbackAutomaticBOMConsumptionRule](#OperationFeedbackAutomaticBOMConsumptionRule)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultOperationFeedbackRouteCardJournalNameId](#DefaultOperationFeedbackRouteCardJournalNameId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackPostRouteCardJournal](#WillOperationFeedbackPostRouteCardJournal)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[TimeJobCardProductionJournalNameId](#TimeJobCardProductionJournalNameId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsOperationFeedbackQuantityValidated](#IsOperationFeedbackQuantityValidated)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsProductionstartQuantityValidated](#IsProductionstartQuantityValidated)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[BackingTable_JmgProdParametersRelationshipId](#BackingTable_JmgProdParametersRelationshipId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity</a>|

### <a href=#BundledJobsTimeAllocationMethod name="BundledJobsTimeAllocationMethod">BundledJobsTimeAllocationMethod</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BundledJobsTimeAllocationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePieceworkProductionOrdersSpecifiedSeparately name="ArePieceworkProductionOrdersSpecifiedSeparately">ArePieceworkProductionOrdersSpecifiedSeparately</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePieceworkProductionOrdersSpecifiedSeparately attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PieceworkRateCalculationFormula name="PieceworkRateCalculationFormula">PieceworkRateCalculationFormula</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PieceworkRateCalculationFormula attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParameterUsageLevel name="ParameterUsageLevel">ParameterUsageLevel</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

### <a href=#ProductionOrderSchedulingGranularity name="ProductionOrderSchedulingGranularity">ProductionOrderSchedulingGranularity</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderSchedulingGranularity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionStartRouteCardProductionJournalNameId name="DefaultProductionStartRouteCardProductionJournalNameId">DefaultProductionStartRouteCardProductionJournalNameId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionStartRouteCardProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOverlapJobRegistrationAllowed name="IsOverlapJobRegistrationAllowed">IsOverlapJobRegistrationAllowed</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOverlapJobRegistrationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcessJobRegistrationAllowed name="IsProcessJobRegistrationAllowed">IsProcessJobRegistrationAllowed</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcessJobRegistrationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQueueAfterJobRegistrationAllowed name="IsQueueAfterJobRegistrationAllowed">IsQueueAfterJobRegistrationAllowed</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQueueAfterJobRegistrationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQueueBeforeJobRegistrationAllowed name="IsQueueBeforeJobRegistrationAllowed">IsQueueBeforeJobRegistrationAllowed</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQueueBeforeJobRegistrationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSetupJobRegistrationAllowed name="IsSetupJobRegistrationAllowed">IsSetupJobRegistrationAllowed</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSetupJobRegistrationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransportJobRegistrationAllowed name="IsTransportJobRegistrationAllowed">IsTransportJobRegistrationAllowed</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransportJobRegistrationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreAssistantsAssignedSecondaryOperations name="AreAssistantsAssignedSecondaryOperations">AreAssistantsAssignedSecondaryOperations</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreAssistantsAssignedSecondaryOperations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOperationFeedbackOpenPickingListJournal name="WillOperationFeedbackOpenPickingListJournal">WillOperationFeedbackOpenPickingListJournal</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOperationFeedbackOpenPickingListJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationFeedbackPickingListProductionJournalNameId name="DefaultOperationFeedbackPickingListProductionJournalNameId">DefaultOperationFeedbackPickingListProductionJournalNameId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationFeedbackPickingListProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOperationFeedbackAutomaticallyPostPickingList name="WillOperationFeedbackAutomaticallyPostPickingList">WillOperationFeedbackAutomaticallyPostPickingList</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOperationFeedbackAutomaticallyPostPickingList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCostCalculationUseRouteCostCategory name="WillCostCalculationUseRouteCostCategory">WillCostCalculationUseRouteCostCategory</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCostCalculationUseRouteCostCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOperationFeedbackAcceptSurplusDeviation name="WillOperationFeedbackAcceptSurplusDeviation">WillOperationFeedbackAcceptSurplusDeviation</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOperationFeedbackAcceptSurplusDeviation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOperationFeedbackAcceptShortageDeviation name="WillOperationFeedbackAcceptShortageDeviation">WillOperationFeedbackAcceptShortageDeviation</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOperationFeedbackAcceptShortageDeviation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAcceptedOperationFeedbackSurplusDeviationPercentage name="MaximumAcceptedOperationFeedbackSurplusDeviationPercentage">MaximumAcceptedOperationFeedbackSurplusDeviationPercentage</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAcceptedOperationFeedbackSurplusDeviationPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAcceptedOperationFeedbackShortageDeviationPercentage name="MaximumAcceptedOperationFeedbackShortageDeviationPercentage">MaximumAcceptedOperationFeedbackShortageDeviationPercentage</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAcceptedOperationFeedbackShortageDeviationPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationFeedbackQuantityValidationMethod name="OperationFeedbackQuantityValidationMethod">OperationFeedbackQuantityValidationMethod</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationFeedbackQuantityValidationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumReportAsFinishedQuantity name="MaximumReportAsFinishedQuantity">MaximumReportAsFinishedQuantity</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumReportAsFinishedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRegistrationTransferAutomatiallyPostTimeJobCardJournal name="WillRegistrationTransferAutomatiallyPostTimeJobCardJournal">WillRegistrationTransferAutomatiallyPostTimeJobCardJournal</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRegistrationTransferAutomatiallyPostTimeJobCardJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionRegistrationLedgerDimensionSelectionRule name="ProductionRegistrationLedgerDimensionSelectionRule">ProductionRegistrationLedgerDimensionSelectionRule</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionRegistrationLedgerDimensionSelectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedPostingAcceptQuantityError name="WillReportAsFinishedPostingAcceptQuantityError">WillReportAsFinishedPostingAcceptQuantityError</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedPostingAcceptQuantityError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportAsFinishedAutomaticBOMConsumptionRule name="ReportAsFinishedAutomaticBOMConsumptionRule">ReportAsFinishedAutomaticBOMConsumptionRule</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

### <a href=#DefaultReportAsFinishedPickingListProductionJournalNameId name="DefaultReportAsFinishedPickingListProductionJournalNameId">DefaultReportAsFinishedPickingListProductionJournalNameId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReportAsFinishedPickingListProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportAsFinishedJobFinalByDefault name="IsReportAsFinishedJobFinalByDefault">IsReportAsFinishedJobFinalByDefault</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportAsFinishedJobFinalByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedCreatePickingListJournalWithEndMarkedOperations name="WillReportAsFinishedCreatePickingListJournalWithEndMarkedOperations">WillReportAsFinishedCreatePickingListJournalWithEndMarkedOperations</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedCreatePickingListJournalWithEndMarkedOperations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedCreateRouteCardJournalWithEndMarkedLines name="WillReportAsFinishedCreateRouteCardJournalWithEndMarkedLines">WillReportAsFinishedCreateRouteCardJournalWithEndMarkedLines</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedCreateRouteCardJournalWithEndMarkedLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReportAsFinishedProductionJournalNameId name="DefaultReportAsFinishedProductionJournalNameId">DefaultReportAsFinishedProductionJournalNameId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReportAsFinishedProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportAsFinishedAutomaticRouteConsumptionRule name="ReportAsFinishedAutomaticRouteConsumptionRule">ReportAsFinishedAutomaticRouteConsumptionRule</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

### <a href=#DefaultReportAsFinishedRouteCardProductionJournalNameId name="DefaultReportAsFinishedRouteCardProductionJournalNameId">DefaultReportAsFinishedRouteCardProductionJournalNameId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReportAsFinishedRouteCardProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportAsFinishedProductionOrderUpdateMethod name="ReportAsFinishedProductionOrderUpdateMethod">ReportAsFinishedProductionOrderUpdateMethod</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportAsFinishedProductionOrderUpdateMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportAsFinishedUsingProductionOrderDefaults name="IsReportAsFinishedUsingProductionOrderDefaults">IsReportAsFinishedUsingProductionOrderDefaults</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportAsFinishedUsingProductionOrderDefaults attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionStartAcceptQuantityDeviation name="WillProductionStartAcceptQuantityDeviation">WillProductionStartAcceptQuantityDeviation</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionStartAcceptQuantityDeviation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionStartAutomaticBOMConsumptionRule name="ProductionStartAutomaticBOMConsumptionRule">ProductionStartAutomaticBOMConsumptionRule</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

### <a href=#DefaultProductionStartPickingListProductionJournalNameId name="DefaultProductionStartPickingListProductionJournalNameId">DefaultProductionStartPickingListProductionJournalNameId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionStartPickingListProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionPickingListJournalLineGroupingMethod name="ProductionPickingListJournalLineGroupingMethod">ProductionPickingListJournalLineGroupingMethod</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionPickingListJournalLineGroupingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionPickingListPostingUpdateBOMItemsFinishedPickingStatus name="WillProductionPickingListPostingUpdateBOMItemsFinishedPickingStatus">WillProductionPickingListPostingUpdateBOMItemsFinishedPickingStatus</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionPickingListPostingUpdateBOMItemsFinishedPickingStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionPickingListPostingAllowNegativeInventory name="WillProductionPickingListPostingAllowNegativeInventory">WillProductionPickingListPostingAllowNegativeInventory</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

### <a href=#WillProductionStartCreatePickingListJournalWithEndMarkedOperations name="WillProductionStartCreatePickingListJournalWithEndMarkedOperations">WillProductionStartCreatePickingListJournalWithEndMarkedOperations</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionStartCreatePickingListJournalWithEndMarkedOperations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionStartCreateRouteCardJournalWithEndMarkedLines name="WillProductionStartCreateRouteCardJournalWithEndMarkedLines">WillProductionStartCreateRouteCardJournalWithEndMarkedLines</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionStartCreateRouteCardJournalWithEndMarkedLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionStartMaximumAcceptedQuantityDeviationPercentage name="ProductionStartMaximumAcceptedQuantityDeviationPercentage">ProductionStartMaximumAcceptedQuantityDeviationPercentage</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionStartMaximumAcceptedQuantityDeviationPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionStartAutomaticallyPostPickingList name="WillProductionStartAutomaticallyPostPickingList">WillProductionStartAutomaticallyPostPickingList</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionStartAutomaticallyPostPickingList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionStartAutomaticallyPostRouteCard name="WillProductionStartAutomaticallyPostRouteCard">WillProductionStartAutomaticallyPostRouteCard</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionStartAutomaticallyPostRouteCard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionStartUpdateStartedQuantity name="WillProductionStartUpdateStartedQuantity">WillProductionStartUpdateStartedQuantity</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionStartUpdateStartedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionPickingListPostingReduceToAvailableQuantity name="WillProductionPickingListPostingReduceToAvailableQuantity">WillProductionPickingListPostingReduceToAvailableQuantity</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

### <a href=#WillProductionStartStartReferencedProductionOrders name="WillProductionStartStartReferencedProductionOrders">WillProductionStartStartReferencedProductionOrders</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionStartStartReferencedProductionOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionStartAutomaticRouteConsumptionRule name="ProductionStartAutomaticRouteConsumptionRule">ProductionStartAutomaticRouteConsumptionRule</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

### <a href=#WillProductionStartOpenPickingListJournals name="WillProductionStartOpenPickingListJournals">WillProductionStartOpenPickingListJournals</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionStartOpenPickingListJournals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionStartProductionOrderUpdateMethod name="ProductionStartProductionOrderUpdateMethod">ProductionStartProductionOrderUpdateMethod</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionStartProductionOrderUpdateMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionStartUseProductionOrderDefaults name="WillProductionStartUseProductionOrderDefaults">WillProductionStartUseProductionOrderDefaults</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionStartUseProductionOrderDefaults attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionStartQuantityValidationMethod name="ProductionStartQuantityValidationMethod">ProductionStartQuantityValidationMethod</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionStartQuantityValidationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationFeedbackAutomaticBOMConsumptionRule name="OperationFeedbackAutomaticBOMConsumptionRule">OperationFeedbackAutomaticBOMConsumptionRule</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationFeedbackAutomaticBOMConsumptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationFeedbackRouteCardJournalNameId name="DefaultOperationFeedbackRouteCardJournalNameId">DefaultOperationFeedbackRouteCardJournalNameId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationFeedbackRouteCardJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOperationFeedbackPostRouteCardJournal name="WillOperationFeedbackPostRouteCardJournal">WillOperationFeedbackPostRouteCardJournal</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOperationFeedbackPostRouteCardJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeJobCardProductionJournalNameId name="TimeJobCardProductionJournalNameId">TimeJobCardProductionJournalNameId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeJobCardProductionJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationFeedbackQuantityValidated name="IsOperationFeedbackQuantityValidated">IsOperationFeedbackQuantityValidated</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationFeedbackQuantityValidated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductionstartQuantityValidated name="IsProductionstartQuantityValidated">IsProductionstartQuantityValidated</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductionstartQuantityValidated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JmgProdParametersRelationshipId name="BackingTable_JmgProdParametersRelationshipId">BackingTable_JmgProdParametersRelationshipId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgProdParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgProdParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/JmgProdParameters.cdm.json/JmgProdParameters</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgProdParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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
