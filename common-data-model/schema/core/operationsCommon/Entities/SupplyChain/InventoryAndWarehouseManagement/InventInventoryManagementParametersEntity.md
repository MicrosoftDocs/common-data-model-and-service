---
title: InventInventoryManagementParametersEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Inventory parameters in InventoryAndWarehouseManagement(InventInventoryManagementParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WillOrderPickingAutomaticallyEndInventoryOutputOrders](#WillOrderPickingAutomaticallyEndInventoryOutputOrders)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[PrintedPickingListPickingRouteIdBarcodeSetupId](#PrintedPickingListPickingRouteIdBarcodeSetupId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[IsOrderedInventoryQuantityReservationAllowed](#IsOrderedInventoryQuantityReservationAllowed)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[WillInventoryCountingLockItems](#WillInventoryCountingLockItems)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultInventoryUnitSymbol](#DefaultInventoryUnitSymbol)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[ArePackingMaterialFeesCalculated](#ArePackingMaterialFeesCalculated)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[FallbackWarehouseId](#FallbackWarehouseId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[IsItemSalesTaxGroupMandatory](#IsItemSalesTaxGroupMandatory)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[WillPickingWorkbenchApplyBoxingLogic](#WillPickingWorkbenchApplyBoxingLogic)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultInventoryMovementJournalNameId](#DefaultInventoryMovementJournalNameId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultInventoryAdjustmentJournalNameId](#DefaultInventoryAdjustmentJournalNameId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultInventoryTransferJournalNameId](#DefaultInventoryTransferJournalNameId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultInventoryCountingJournalNameId](#DefaultInventoryCountingJournalNameId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultBOMJournalNameId](#DefaultBOMJournalNameId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultInventoryTagCountingJournalNameId](#DefaultInventoryTagCountingJournalNameId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultCatchWeightJournalNameId](#DefaultCatchWeightJournalNameId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultOwnershipChangeJournalNameId](#DefaultOwnershipChangeJournalNameId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[DefaultBatchMergeBOMJournalNameId](#DefaultBatchMergeBOMJournalNameId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[PriceActivationItemBundleSize](#PriceActivationItemBundleSize)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[PostPhysicalSalesTax](#PostPhysicalSalesTax)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[WillInventoryUpdateAutomaticallyAggregateTransactions](#WillInventoryUpdateAutomaticallyAggregateTransactions)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[MaximumAllowedUnitCost](#MaximumAllowedUnitCost)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[SaveLastPriceHistory](#SaveLastPriceHistory)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[InventoryClosingExtraBatchHelperAmount](#InventoryClosingExtraBatchHelperAmount)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[InventoryClosingHelperBatchGroupId](#InventoryClosingHelperBatchGroupId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[InventoryClosingItemBundleSize](#InventoryClosingItemBundleSize)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[CostBreakdownType](#CostBreakdownType)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[ProductionVarianceCalculationModel](#ProductionVarianceCalculationModel)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[WillTransferOrderEntryAutomaticallyReserveItems](#WillTransferOrderEntryAutomaticallyReserveItems)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[OverrideFEFODateControlForTransferOrders](#OverrideFEFODateControlForTransferOrders)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[WillTransferOrderProcessesAcceptOverdelivery](#WillTransferOrderProcessesAcceptOverdelivery)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[WillTransferOrderProcessesAcceptUnderdelivery](#WillTransferOrderProcessesAcceptUnderdelivery)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[TransferOrderPickingRouteStatusOnUpdate](#TransferOrderPickingRouteStatusOnUpdate)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[WillQualityTestResultsUpdateBatchAttributes](#WillQualityTestResultsUpdateBatchAttributes)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[AreQualityManagementProcessesEnabled](#AreQualityManagementProcessesEnabled)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[QualityTestHourlyRate](#QualityTestHourlyRate)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[AreSiteSpecificMainAccountsEnabled](#AreSiteSpecificMainAccountsEnabled)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[MassDefinedUnitSymbol](#MassDefinedUnitSymbol)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[VolumeDefinedUnitSymbol](#VolumeDefinedUnitSymbol)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[LengthDefinedUnitSymbol](#LengthDefinedUnitSymbol)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_DefaultBatchMergeBOMJournalNameRelationshipId](#Relationship_DefaultBatchMergeBOMJournalNameRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_DefaultBillOfMaterialsJournalNameRelationshipId](#Relationship_DefaultBillOfMaterialsJournalNameRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_DefaultInventoryCountingJournalNameRelationshipId](#Relationship_DefaultInventoryCountingJournalNameRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_FallbackWarehouseRelationshipId](#Relationship_FallbackWarehouseRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_DefaultInventoryAdjustmentJournalNameRelationshipId](#Relationship_DefaultInventoryAdjustmentJournalNameRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_DefaultInventoryMovementJournalNameRelationshipId](#Relationship_DefaultInventoryMovementJournalNameRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_DefaultInventoryTransferJournalNameRelationshipId](#Relationship_DefaultInventoryTransferJournalNameRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_DefaultInventoryTagCountingJournalNameRelationshipId](#Relationship_DefaultInventoryTagCountingJournalNameRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_DefaultInventoryUnitOfMeasureRelationshipId](#Relationship_DefaultInventoryUnitOfMeasureRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_DefaultInventoryOwnershipChangeJournalNameRelationshipId](#Relationship_DefaultInventoryOwnershipChangeJournalNameRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_MassDefinedUnitOfMeasureRelationshipId](#Relationship_MassDefinedUnitOfMeasureRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_LengthDefinedUnitOfMeasureRelationshipId](#Relationship_LengthDefinedUnitOfMeasureRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_VolumeDefinedUnitOfMeasureRelationshipId](#Relationship_VolumeDefinedUnitOfMeasureRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[BackingTable_InventParametersRelationshipId](#BackingTable_InventParametersRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity</a>|

### <a href=#WillOrderPickingAutomaticallyEndInventoryOutputOrders name="WillOrderPickingAutomaticallyEndInventoryOutputOrders">WillOrderPickingAutomaticallyEndInventoryOutputOrders</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOrderPickingAutomaticallyEndInventoryOutputOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintedPickingListPickingRouteIdBarcodeSetupId name="PrintedPickingListPickingRouteIdBarcodeSetupId">PrintedPickingListPickingRouteIdBarcodeSetupId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintedPickingListPickingRouteIdBarcodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOrderedInventoryQuantityReservationAllowed name="IsOrderedInventoryQuantityReservationAllowed">IsOrderedInventoryQuantityReservationAllowed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOrderedInventoryQuantityReservationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInventoryCountingLockItems name="WillInventoryCountingLockItems">WillInventoryCountingLockItems</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInventoryCountingLockItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryUnitSymbol name="DefaultInventoryUnitSymbol">DefaultInventoryUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePackingMaterialFeesCalculated name="ArePackingMaterialFeesCalculated">ArePackingMaterialFeesCalculated</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePackingMaterialFeesCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FallbackWarehouseId name="FallbackWarehouseId">FallbackWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FallbackWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemSalesTaxGroupMandatory name="IsItemSalesTaxGroupMandatory">IsItemSalesTaxGroupMandatory</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemSalesTaxGroupMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPickingWorkbenchApplyBoxingLogic name="WillPickingWorkbenchApplyBoxingLogic">WillPickingWorkbenchApplyBoxingLogic</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

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

### <a href=#DefaultInventoryMovementJournalNameId name="DefaultInventoryMovementJournalNameId">DefaultInventoryMovementJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryMovementJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryAdjustmentJournalNameId name="DefaultInventoryAdjustmentJournalNameId">DefaultInventoryAdjustmentJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryAdjustmentJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryTransferJournalNameId name="DefaultInventoryTransferJournalNameId">DefaultInventoryTransferJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryTransferJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryCountingJournalNameId name="DefaultInventoryCountingJournalNameId">DefaultInventoryCountingJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryCountingJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBOMJournalNameId name="DefaultBOMJournalNameId">DefaultBOMJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBOMJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryTagCountingJournalNameId name="DefaultInventoryTagCountingJournalNameId">DefaultInventoryTagCountingJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryTagCountingJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCatchWeightJournalNameId name="DefaultCatchWeightJournalNameId">DefaultCatchWeightJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCatchWeightJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOwnershipChangeJournalNameId name="DefaultOwnershipChangeJournalNameId">DefaultOwnershipChangeJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOwnershipChangeJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBatchMergeBOMJournalNameId name="DefaultBatchMergeBOMJournalNameId">DefaultBatchMergeBOMJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBatchMergeBOMJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceActivationItemBundleSize name="PriceActivationItemBundleSize">PriceActivationItemBundleSize</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceActivationItemBundleSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostPhysicalSalesTax name="PostPhysicalSalesTax">PostPhysicalSalesTax</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostPhysicalSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInventoryUpdateAutomaticallyAggregateTransactions name="WillInventoryUpdateAutomaticallyAggregateTransactions">WillInventoryUpdateAutomaticallyAggregateTransactions</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInventoryUpdateAutomaticallyAggregateTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAllowedUnitCost name="MaximumAllowedUnitCost">MaximumAllowedUnitCost</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAllowedUnitCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SaveLastPriceHistory name="SaveLastPriceHistory">SaveLastPriceHistory</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaveLastPriceHistory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryClosingExtraBatchHelperAmount name="InventoryClosingExtraBatchHelperAmount">InventoryClosingExtraBatchHelperAmount</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryClosingExtraBatchHelperAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryClosingHelperBatchGroupId name="InventoryClosingHelperBatchGroupId">InventoryClosingHelperBatchGroupId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryClosingHelperBatchGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryClosingItemBundleSize name="InventoryClosingItemBundleSize">InventoryClosingItemBundleSize</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryClosingItemBundleSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostBreakdownType name="CostBreakdownType">CostBreakdownType</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostBreakdownType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionVarianceCalculationModel name="ProductionVarianceCalculationModel">ProductionVarianceCalculationModel</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionVarianceCalculationModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTransferOrderEntryAutomaticallyReserveItems name="WillTransferOrderEntryAutomaticallyReserveItems">WillTransferOrderEntryAutomaticallyReserveItems</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTransferOrderEntryAutomaticallyReserveItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverrideFEFODateControlForTransferOrders name="OverrideFEFODateControlForTransferOrders">OverrideFEFODateControlForTransferOrders</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideFEFODateControlForTransferOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTransferOrderProcessesAcceptOverdelivery name="WillTransferOrderProcessesAcceptOverdelivery">WillTransferOrderProcessesAcceptOverdelivery</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTransferOrderProcessesAcceptOverdelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTransferOrderProcessesAcceptUnderdelivery name="WillTransferOrderProcessesAcceptUnderdelivery">WillTransferOrderProcessesAcceptUnderdelivery</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTransferOrderProcessesAcceptUnderdelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderPickingRouteStatusOnUpdate name="TransferOrderPickingRouteStatusOnUpdate">TransferOrderPickingRouteStatusOnUpdate</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderPickingRouteStatusOnUpdate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillQualityTestResultsUpdateBatchAttributes name="WillQualityTestResultsUpdateBatchAttributes">WillQualityTestResultsUpdateBatchAttributes</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillQualityTestResultsUpdateBatchAttributes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreQualityManagementProcessesEnabled name="AreQualityManagementProcessesEnabled">AreQualityManagementProcessesEnabled</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreQualityManagementProcessesEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestHourlyRate name="QualityTestHourlyRate">QualityTestHourlyRate</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestHourlyRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSiteSpecificMainAccountsEnabled name="AreSiteSpecificMainAccountsEnabled">AreSiteSpecificMainAccountsEnabled</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSiteSpecificMainAccountsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MassDefinedUnitSymbol name="MassDefinedUnitSymbol">MassDefinedUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Weight unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MassDefinedUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Weight unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VolumeDefinedUnitSymbol name="VolumeDefinedUnitSymbol">VolumeDefinedUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Volume unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VolumeDefinedUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Volume unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LengthDefinedUnitSymbol name="LengthDefinedUnitSymbol">LengthDefinedUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Length unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LengthDefinedUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Length unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultBatchMergeBOMJournalNameRelationshipId name="Relationship_DefaultBatchMergeBOMJournalNameRelationshipId">Relationship_DefaultBatchMergeBOMJournalNameRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultBatchMergeBOMJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultBillOfMaterialsJournalNameRelationshipId name="Relationship_DefaultBillOfMaterialsJournalNameRelationshipId">Relationship_DefaultBillOfMaterialsJournalNameRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultBillOfMaterialsJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryCountingJournalNameRelationshipId name="Relationship_DefaultInventoryCountingJournalNameRelationshipId">Relationship_DefaultInventoryCountingJournalNameRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryCountingJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FallbackWarehouseRelationshipId name="Relationship_FallbackWarehouseRelationshipId">Relationship_FallbackWarehouseRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FallbackWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryAdjustmentJournalNameRelationshipId name="Relationship_DefaultInventoryAdjustmentJournalNameRelationshipId">Relationship_DefaultInventoryAdjustmentJournalNameRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryAdjustmentJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryMovementJournalNameRelationshipId name="Relationship_DefaultInventoryMovementJournalNameRelationshipId">Relationship_DefaultInventoryMovementJournalNameRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryMovementJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryTransferJournalNameRelationshipId name="Relationship_DefaultInventoryTransferJournalNameRelationshipId">Relationship_DefaultInventoryTransferJournalNameRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryTransferJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryTagCountingJournalNameRelationshipId name="Relationship_DefaultInventoryTagCountingJournalNameRelationshipId">Relationship_DefaultInventoryTagCountingJournalNameRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryTagCountingJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryUnitOfMeasureRelationshipId name="Relationship_DefaultInventoryUnitOfMeasureRelationshipId">Relationship_DefaultInventoryUnitOfMeasureRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryOwnershipChangeJournalNameRelationshipId name="Relationship_DefaultInventoryOwnershipChangeJournalNameRelationshipId">Relationship_DefaultInventoryOwnershipChangeJournalNameRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryOwnershipChangeJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MassDefinedUnitOfMeasureRelationshipId name="Relationship_MassDefinedUnitOfMeasureRelationshipId">Relationship_MassDefinedUnitOfMeasureRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MassDefinedUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LengthDefinedUnitOfMeasureRelationshipId name="Relationship_LengthDefinedUnitOfMeasureRelationshipId">Relationship_LengthDefinedUnitOfMeasureRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LengthDefinedUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VolumeDefinedUnitOfMeasureRelationshipId name="Relationship_VolumeDefinedUnitOfMeasureRelationshipId">Relationship_VolumeDefinedUnitOfMeasureRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VolumeDefinedUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventParametersRelationshipId name="BackingTable_InventParametersRelationshipId">BackingTable_InventParametersRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/InventParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Parameter/InventParameters.cdm.json/InventParameters</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/InventParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryManagementParametersEntity (this entity)  

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
