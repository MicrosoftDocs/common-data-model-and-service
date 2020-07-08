---
title: JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Manufacturing execution production order defaults by site in ProductionControl(JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manufacturing execution production order defaults by site</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InventDimId](#InventDimId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionSiteId](#ProductionSiteId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultProductionStartRouteCardProductionJournalNameId](#DefaultProductionStartRouteCardProductionJournalNameId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsOverlapJobRegistrationAllowed](#IsOverlapJobRegistrationAllowed)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsProcessJobRegistrationAllowed](#IsProcessJobRegistrationAllowed)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsQueueAfterJobRegistrationAllowed](#IsQueueAfterJobRegistrationAllowed)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsQueueBeforeJobRegistrationAllowed](#IsQueueBeforeJobRegistrationAllowed)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsSetupJobRegistrationAllowed](#IsSetupJobRegistrationAllowed)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsTransportJobRegistrationAllowed](#IsTransportJobRegistrationAllowed)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[AreAssistantsAssignedSecondaryOperations](#AreAssistantsAssignedSecondaryOperations)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackOpenPickingListJournal](#WillOperationFeedbackOpenPickingListJournal)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultOperationFeedbackPickingListProductionJournalNameId](#DefaultOperationFeedbackPickingListProductionJournalNameId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackAutomaticallyPostPickingList](#WillOperationFeedbackAutomaticallyPostPickingList)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillCostCalculationUseRouteCostCategory](#WillCostCalculationUseRouteCostCategory)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackAcceptSurplusDeviation](#WillOperationFeedbackAcceptSurplusDeviation)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackAcceptShortageDeviation](#WillOperationFeedbackAcceptShortageDeviation)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[MaximumAcceptedOperationFeedbackSurplusDeviationPercentage](#MaximumAcceptedOperationFeedbackSurplusDeviationPercentage)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[MaximumAcceptedOperationFeedbackShortageDeviationPercentage](#MaximumAcceptedOperationFeedbackShortageDeviationPercentage)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[OperationFeedbackQuantityValidationMethod](#OperationFeedbackQuantityValidationMethod)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[MaximumReportAsFinishedQuantity](#MaximumReportAsFinishedQuantity)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillRegistrationTransferAutomatiallyPostTimeJobCardJournal](#WillRegistrationTransferAutomatiallyPostTimeJobCardJournal)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionRegistrationLedgerDimensionSelectionRule](#ProductionRegistrationLedgerDimensionSelectionRule)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillReportAsFinishedPostingAcceptQuantityError](#WillReportAsFinishedPostingAcceptQuantityError)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ReportAsFinishedAutomaticBOMConsumptionRule](#ReportAsFinishedAutomaticBOMConsumptionRule)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultReportAsFinishedPickingListProductionJournalNameId](#DefaultReportAsFinishedPickingListProductionJournalNameId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsReportAsFinishedJobFinalByDefault](#IsReportAsFinishedJobFinalByDefault)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillReportAsFinishedCreatePickingListJournalWithEndMarkedOperations](#WillReportAsFinishedCreatePickingListJournalWithEndMarkedOperations)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillReportAsFinishedCreateRouteCardJournalWithEndMarkedLines](#WillReportAsFinishedCreateRouteCardJournalWithEndMarkedLines)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultReportAsFinishedProductionJournalNameId](#DefaultReportAsFinishedProductionJournalNameId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ReportAsFinishedAutomaticRouteConsumptionRule](#ReportAsFinishedAutomaticRouteConsumptionRule)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultReportAsFinishedRouteCardProductionJournalNameId](#DefaultReportAsFinishedRouteCardProductionJournalNameId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ReportAsFinishedProductionOrderUpdateMethod](#ReportAsFinishedProductionOrderUpdateMethod)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsReportAsFinishedUsingProductionOrderDefaults](#IsReportAsFinishedUsingProductionOrderDefaults)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartAcceptQuantityDeviation](#WillProductionStartAcceptQuantityDeviation)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartAutomaticBOMConsumptionRule](#ProductionStartAutomaticBOMConsumptionRule)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultProductionStartPickingListProductionJournalNameId](#DefaultProductionStartPickingListProductionJournalNameId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionPickingListJournalLineGroupingMethod](#ProductionPickingListJournalLineGroupingMethod)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionPickingListPostingUpdateBOMItemsFinishedPickingStatus](#WillProductionPickingListPostingUpdateBOMItemsFinishedPickingStatus)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionPickingListPostingAllowNegativeInventory](#WillProductionPickingListPostingAllowNegativeInventory)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartCreatePickingListJournalWithEndMarkedOperations](#WillProductionStartCreatePickingListJournalWithEndMarkedOperations)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartCreateRouteCardJournalWithEndMarkedLines](#WillProductionStartCreateRouteCardJournalWithEndMarkedLines)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartMaximumAcceptedQuantityDeviationPercentage](#ProductionStartMaximumAcceptedQuantityDeviationPercentage)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartAutomaticallyPostPickingList](#WillProductionStartAutomaticallyPostPickingList)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartAutomaticallyPostRouteCard](#WillProductionStartAutomaticallyPostRouteCard)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartUpdateStartedQuantity](#WillProductionStartUpdateStartedQuantity)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionPickingListPostingReduceToAvailableQuantity](#WillProductionPickingListPostingReduceToAvailableQuantity)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartStartReferencedProductionOrders](#WillProductionStartStartReferencedProductionOrders)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartAutomaticRouteConsumptionRule](#ProductionStartAutomaticRouteConsumptionRule)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartOpenPickingListJournals](#WillProductionStartOpenPickingListJournals)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartProductionOrderUpdateMethod](#ProductionStartProductionOrderUpdateMethod)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillProductionStartUseProductionOrderDefaults](#WillProductionStartUseProductionOrderDefaults)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[ProductionStartQuantityValidationMethod](#ProductionStartQuantityValidationMethod)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[OperationFeedbackAutomaticBOMConsumptionRule](#OperationFeedbackAutomaticBOMConsumptionRule)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[DefaultOperationFeedbackRouteCardJournalNameId](#DefaultOperationFeedbackRouteCardJournalNameId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[WillOperationFeedbackPostRouteCardJournal](#WillOperationFeedbackPostRouteCardJournal)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[TimeJobCardProductionJournalNameId](#TimeJobCardProductionJournalNameId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsOperationFeedbackQuantityValidated](#IsOperationFeedbackQuantityValidated)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[IsProductionstartQuantityValidated](#IsProductionstartQuantityValidated)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[BackingTable_JmgProdParametersDimRelationshipId](#BackingTable_JmgProdParametersDimRelationshipId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity.md" target="_blank">ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity</a>|

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

### <a href=#DefaultProductionStartRouteCardProductionJournalNameId name="DefaultProductionStartRouteCardProductionJournalNameId">DefaultProductionStartRouteCardProductionJournalNameId</a>

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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

### <a href=#BackingTable_JmgProdParametersDimRelationshipId name="BackingTable_JmgProdParametersDimRelationshipId">BackingTable_JmgProdParametersDimRelationshipId</a>

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgProdParametersDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgProdParametersDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/JmgProdParametersDim.cdm.json/JmgProdParametersDim</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgProdParametersDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgSiteSpecificManufacturingExecutionProductionOrderDefaultsEntity (this entity)  

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
