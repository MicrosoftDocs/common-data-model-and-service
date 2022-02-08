---
title: WHSWarehouseMobileDeviceMenuItemV3Entity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Warehouse mobile device menu item V3 in WMS(WHSWarehouseMobileDeviceMenuItemV3Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseMobileDeviceMenuItemV3Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse mobile device menu item V3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[MenuItemName](#MenuItemName)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[Title](#Title)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[MenuItemMode](#MenuItemMode)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[UseExistingWork](#UseExistingWork)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[ActivityCode](#ActivityCode)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[DirectedBy](#DirectedBy)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[RecordsPerPage](#RecordsPerPage)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsWorkTransactionTypeUserFilteringAllowed](#IsWorkTransactionTypeUserFilteringAllowed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[WorkCreationProcess](#WorkCreationProcess)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsDefaultDataUsed](#IsDefaultDataUsed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsLicensePlateGenerated](#IsLicensePlateGenerated)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsCancelationConfirmed](#IsCancelationConfirmed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[InventoryAdjustmentTypeId](#InventoryAdjustmentTypeId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsLocationOverflowAllowed](#IsLocationOverflowAllowed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsDispositionCodeDisplayed](#IsDispositionCodeDisplayed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsLabelPrinted](#IsLabelPrinted)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsInventoryStatusDisplayed](#IsInventoryStatusDisplayed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsLicensePlateOverridenDuringPut](#IsLicensePlateOverridenDuringPut)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsGroupPutAwayUsed](#IsGroupPutAwayUsed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[AuditTemplateId](#AuditTemplateId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[WillReportAsFinishedAllowProductionOrderEnding](#WillReportAsFinishedAllowProductionOrderEnding)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[LicensePlateGroupingPolicy](#LicensePlateGroupingPolicy)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[WorkTemplateId](#WorkTemplateId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[DirectiveCode](#DirectiveCode)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsBatchDispositionCodeDisplayed](#IsBatchDispositionCodeDisplayed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsBatchNumberOverriden](#IsBatchNumberOverriden)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsMovementCreated](#IsMovementCreated)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsTotalItemQuantityCountedFirst](#IsTotalItemQuantityCountedFirst)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsAnchoringUsed](#IsAnchoringUsed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[AnchorBy](#AnchorBy)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsWorkSplittingAllowed](#IsWorkSplittingAllowed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsUserKeepingWorkLocked](#IsUserKeepingWorkLocked)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsPickScreenSummaryDisplayed](#IsPickScreenSummaryDisplayed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[AreCycleCountThresholdsDisabled](#AreCycleCountThresholdsDisabled)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[PickOldestBatchCriteria](#PickOldestBatchCriteria)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsOverPickAllowed](#IsOverPickAllowed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsPickAndPackUsed](#IsPickAndPackUsed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsTargetLicensePlateOverriden](#IsTargetLicensePlateOverriden)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsLicensePlateHandlingUsed](#IsLicensePlateHandlingUsed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[GroupingField](#GroupingField)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[GroupingLabel](#GroupingLabel)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[ClusterProfileId](#ClusterProfileId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[WorkListQuery](#WorkListQuery)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsASNItemReceivingPrevented](#IsASNItemReceivingPrevented)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[CanLicensePlateConsolidationCancelRemainingOriginWorkLines](#CanLicensePlateConsolidationCancelRemainingOriginWorkLines)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[MixedLicensePlateReceivingMode](#MixedLicensePlateReceivingMode)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsContainerTypeDisplayed](#IsContainerTypeDisplayed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[WillContainerRemovalCancelRelatedWork](#WillContainerRemovalCancelRelatedWork)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsCancelingReplenishmentWorkWithDependentWorkAllowed](#IsCancelingReplenishmentWorkWithDependentWorkAllowed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[MaximumDisplayedRecords](#MaximumDisplayedRecords)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsWorkListGroupingFilterDisplayed](#IsWorkListGroupingFilterDisplayed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[AreOlderBatchesWithinWarehouseDisplayed](#AreOlderBatchesWithinWarehouseDisplayed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsCountingReasonCodeEditable](#IsCountingReasonCodeEditable)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsCountingReasonCodeDisplayed](#IsCountingReasonCodeDisplayed)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[DefaultCountingReasonCode](#DefaultCountingReasonCode)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsCatchWeightTagGenerated](#IsCatchWeightTagGenerated)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[WillUseProcessGuideFramework](#WillUseProcessGuideFramework)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsGroupPickEnabled](#IsGroupPickEnabled)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[WaveLabelPrintMode](#WaveLabelPrintMode)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[OutboundSortingTemplateId](#OutboundSortingTemplateId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[CartonGroupQuery](#CartonGroupQuery)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[DeferredPutProcessingPolicy](#DeferredPutProcessingPolicy)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[WillReceiptAssignPutawayCluster](#WillReceiptAssignPutawayCluster)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[WillInboundProcessesUseExistingCatchWeightTag](#WillInboundProcessesUseExistingCatchWeightTag)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[ReceivingSummaryPageDisplayRule](#ReceivingSummaryPageDisplayRule)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[IsFastValidationEnabled](#IsFastValidationEnabled)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[Relationship_InventoryAdjustmentTypeRelationshipId](#Relationship_InventoryAdjustmentTypeRelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[Relationship_WarehouseClusterProfileV2RelationshipId](#Relationship_WarehouseClusterProfileV2RelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[Relationship_WarehouseLocationDirectiveCodeRelationshipId](#Relationship_WarehouseLocationDirectiveCodeRelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[Relationship_WarehouseWorkAuditTemplateRelationshipId](#Relationship_WarehouseWorkAuditTemplateRelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[Relationship_InventCountingReasonCodeRelationshipId](#Relationship_InventCountingReasonCodeRelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[Relationship_OutboundSortingTemplateV2RelationshipId](#Relationship_OutboundSortingTemplateV2RelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[BackingTable_WHSRFMenuItemTableRelationshipId](#BackingTable_WHSRFMenuItemTableRelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemV3Entity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemV3Entity</a>|

### <a href=#MenuItemName name="MenuItemName">MenuItemName</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Title name="Title">Title</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Title attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MenuItemMode name="MenuItemMode">MenuItemMode</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseExistingWork name="UseExistingWork">UseExistingWork</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseExistingWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityCode name="ActivityCode">ActivityCode</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectedBy name="DirectedBy">DirectedBy</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecordsPerPage name="RecordsPerPage">RecordsPerPage</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordsPerPage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkTransactionTypeUserFilteringAllowed name="IsWorkTransactionTypeUserFilteringAllowed">IsWorkTransactionTypeUserFilteringAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkTransactionTypeUserFilteringAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkCreationProcess name="WorkCreationProcess">WorkCreationProcess</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkCreationProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultDataUsed name="IsDefaultDataUsed">IsDefaultDataUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultDataUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLicensePlateGenerated name="IsLicensePlateGenerated">IsLicensePlateGenerated</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLicensePlateGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCancelationConfirmed name="IsCancelationConfirmed">IsCancelationConfirmed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCancelationConfirmed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryAdjustmentTypeId name="InventoryAdjustmentTypeId">InventoryAdjustmentTypeId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAdjustmentTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationOverflowAllowed name="IsLocationOverflowAllowed">IsLocationOverflowAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationOverflowAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDispositionCodeDisplayed name="IsDispositionCodeDisplayed">IsDispositionCodeDisplayed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDispositionCodeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLabelPrinted name="IsLabelPrinted">IsLabelPrinted</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLabelPrinted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryStatusDisplayed name="IsInventoryStatusDisplayed">IsInventoryStatusDisplayed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryStatusDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLicensePlateOverridenDuringPut name="IsLicensePlateOverridenDuringPut">IsLicensePlateOverridenDuringPut</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLicensePlateOverridenDuringPut attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsGroupPutAwayUsed name="IsGroupPutAwayUsed">IsGroupPutAwayUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGroupPutAwayUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuditTemplateId name="AuditTemplateId">AuditTemplateId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuditTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedAllowProductionOrderEnding name="WillReportAsFinishedAllowProductionOrderEnding">WillReportAsFinishedAllowProductionOrderEnding</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedAllowProductionOrderEnding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicensePlateGroupingPolicy name="LicensePlateGroupingPolicy">LicensePlateGroupingPolicy</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicensePlateGroupingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkTemplateId name="WorkTemplateId">WorkTemplateId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectiveCode name="DirectiveCode">DirectiveCode</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectiveCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchDispositionCodeDisplayed name="IsBatchDispositionCodeDisplayed">IsBatchDispositionCodeDisplayed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchDispositionCodeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchNumberOverriden name="IsBatchNumberOverriden">IsBatchNumberOverriden</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchNumberOverriden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMovementCreated name="IsMovementCreated">IsMovementCreated</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMovementCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTotalItemQuantityCountedFirst name="IsTotalItemQuantityCountedFirst">IsTotalItemQuantityCountedFirst</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTotalItemQuantityCountedFirst attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAnchoringUsed name="IsAnchoringUsed">IsAnchoringUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAnchoringUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnchorBy name="AnchorBy">AnchorBy</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnchorBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkSplittingAllowed name="IsWorkSplittingAllowed">IsWorkSplittingAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkSplittingAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsUserKeepingWorkLocked name="IsUserKeepingWorkLocked">IsUserKeepingWorkLocked</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUserKeepingWorkLocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickScreenSummaryDisplayed name="IsPickScreenSummaryDisplayed">IsPickScreenSummaryDisplayed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickScreenSummaryDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreCycleCountThresholdsDisabled name="AreCycleCountThresholdsDisabled">AreCycleCountThresholdsDisabled</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreCycleCountThresholdsDisabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PickOldestBatchCriteria name="PickOldestBatchCriteria">PickOldestBatchCriteria</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickOldestBatchCriteria attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOverPickAllowed name="IsOverPickAllowed">IsOverPickAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOverPickAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickAndPackUsed name="IsPickAndPackUsed">IsPickAndPackUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickAndPackUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTargetLicensePlateOverriden name="IsTargetLicensePlateOverriden">IsTargetLicensePlateOverriden</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTargetLicensePlateOverriden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLicensePlateHandlingUsed name="IsLicensePlateHandlingUsed">IsLicensePlateHandlingUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLicensePlateHandlingUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupingField name="GroupingField">GroupingField</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupingField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupingLabel name="GroupingLabel">GroupingLabel</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupingLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClusterProfileId name="ClusterProfileId">ClusterProfileId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkListQuery name="WorkListQuery">WorkListQuery</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkListQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsASNItemReceivingPrevented name="IsASNItemReceivingPrevented">IsASNItemReceivingPrevented</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsASNItemReceivingPrevented attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanLicensePlateConsolidationCancelRemainingOriginWorkLines name="CanLicensePlateConsolidationCancelRemainingOriginWorkLines">CanLicensePlateConsolidationCancelRemainingOriginWorkLines</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanLicensePlateConsolidationCancelRemainingOriginWorkLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixedLicensePlateReceivingMode name="MixedLicensePlateReceivingMode">MixedLicensePlateReceivingMode</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixedLicensePlateReceivingMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsContainerTypeDisplayed name="IsContainerTypeDisplayed">IsContainerTypeDisplayed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsContainerTypeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillContainerRemovalCancelRelatedWork name="WillContainerRemovalCancelRelatedWork">WillContainerRemovalCancelRelatedWork</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillContainerRemovalCancelRelatedWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCancelingReplenishmentWorkWithDependentWorkAllowed name="IsCancelingReplenishmentWorkWithDependentWorkAllowed">IsCancelingReplenishmentWorkWithDependentWorkAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCancelingReplenishmentWorkWithDependentWorkAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumDisplayedRecords name="MaximumDisplayedRecords">MaximumDisplayedRecords</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumDisplayedRecords attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkListGroupingFilterDisplayed name="IsWorkListGroupingFilterDisplayed">IsWorkListGroupingFilterDisplayed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkListGroupingFilterDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreOlderBatchesWithinWarehouseDisplayed name="AreOlderBatchesWithinWarehouseDisplayed">AreOlderBatchesWithinWarehouseDisplayed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreOlderBatchesWithinWarehouseDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingReasonCodeEditable name="IsCountingReasonCodeEditable">IsCountingReasonCodeEditable</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingReasonCodeEditable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingReasonCodeDisplayed name="IsCountingReasonCodeDisplayed">IsCountingReasonCodeDisplayed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingReasonCodeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCountingReasonCode name="DefaultCountingReasonCode">DefaultCountingReasonCode</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCountingReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCatchWeightTagGenerated name="IsCatchWeightTagGenerated">IsCatchWeightTagGenerated</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCatchWeightTagGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillUseProcessGuideFramework name="WillUseProcessGuideFramework">WillUseProcessGuideFramework</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillUseProcessGuideFramework attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsGroupPickEnabled name="IsGroupPickEnabled">IsGroupPickEnabled</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGroupPickEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WaveLabelPrintMode name="WaveLabelPrintMode">WaveLabelPrintMode</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaveLabelPrintMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutboundSortingTemplateId name="OutboundSortingTemplateId">OutboundSortingTemplateId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutboundSortingTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CartonGroupQuery name="CartonGroupQuery">CartonGroupQuery</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CartonGroupQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredPutProcessingPolicy name="DeferredPutProcessingPolicy">DeferredPutProcessingPolicy</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredPutProcessingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReceiptAssignPutawayCluster name="WillReceiptAssignPutawayCluster">WillReceiptAssignPutawayCluster</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReceiptAssignPutawayCluster attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInboundProcessesUseExistingCatchWeightTag name="WillInboundProcessesUseExistingCatchWeightTag">WillInboundProcessesUseExistingCatchWeightTag</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInboundProcessesUseExistingCatchWeightTag attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingSummaryPageDisplayRule name="ReceivingSummaryPageDisplayRule">ReceivingSummaryPageDisplayRule</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingSummaryPageDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFastValidationEnabled name="IsFastValidationEnabled">IsFastValidationEnabled</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFastValidationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventoryAdjustmentTypeRelationshipId name="Relationship_InventoryAdjustmentTypeRelationshipId">Relationship_InventoryAdjustmentTypeRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryAdjustmentTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseClusterProfileV2RelationshipId name="Relationship_WarehouseClusterProfileV2RelationshipId">Relationship_WarehouseClusterProfileV2RelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseClusterProfileV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseLocationDirectiveCodeRelationshipId name="Relationship_WarehouseLocationDirectiveCodeRelationshipId">Relationship_WarehouseLocationDirectiveCodeRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseLocationDirectiveCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseWorkAuditTemplateRelationshipId name="Relationship_WarehouseWorkAuditTemplateRelationshipId">Relationship_WarehouseWorkAuditTemplateRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseWorkAuditTemplateRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventCountingReasonCodeRelationshipId name="Relationship_InventCountingReasonCodeRelationshipId">Relationship_InventCountingReasonCodeRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventCountingReasonCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OutboundSortingTemplateV2RelationshipId name="Relationship_OutboundSortingTemplateV2RelationshipId">Relationship_OutboundSortingTemplateV2RelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OutboundSortingTemplateV2RelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSRFMenuItemTableRelationshipId name="BackingTable_WHSRFMenuItemTableRelationshipId">BackingTable_WHSRFMenuItemTableRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSRFMenuItemTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSRFMenuItemTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSRFMenuItemTable.cdm.json/WHSRFMenuItemTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSRFMenuItemTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemV3Entity (this entity)  

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
