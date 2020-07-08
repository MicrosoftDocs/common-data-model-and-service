---
title: WHSWarehouseManagementParametersV2Entity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Warehouse management parameters V2 in WMS(WHSWarehouseManagementParametersV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseManagementParametersV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse management parameters V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GS1CompanyPrefix](#GS1CompanyPrefix)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultUserWarehouseLocationProfileId](#DefaultUserWarehouseLocationProfileId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultStagingWarehouseLocationTypeId](#DefaultStagingWarehouseLocationTypeId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultFinalShippingWarehouseLocationTypeId](#DefaultFinalShippingWarehouseLocationTypeId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[MissingASNItemWorkExceptionCode](#MissingASNItemWorkExceptionCode)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultBarcodeSetupId](#DefaultBarcodeSetupId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultLicensePlateUnitSymbol](#DefaultLicensePlateUnitSymbol)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultWaveProcessingBatchGroup](#DefaultWaveProcessingBatchGroup)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[AreWavesBatchProcessed](#AreWavesBatchProcessed)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsWaveProgressLogCreated](#IsWaveProgressLogCreated)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsWaveProcessingHistoryLogCreated](#IsWaveProcessingHistoryLogCreated)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsContainerizationHistoryLogCreated](#IsContainerizationHistoryLogCreated)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[WaveLockWaitValue](#WaveLockWaitValue)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultInventoryAdjustmentTypeCode](#DefaultInventoryAdjustmentTypeCode)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsTemporaryWorkTableRetained](#IsTemporaryWorkTableRetained)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsWorkCreationHistoryLogCreated](#IsWorkCreationHistoryLogCreated)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultWarehouseWorkPriority](#DefaultWarehouseWorkPriority)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsWorkCancellationUnregisteringRecept](#IsWorkCancellationUnregisteringRecept)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[AllowMixingBatchesDays](#AllowMixingBatchesDays)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[WarehouseMobileDeviceNoteType](#WarehouseMobileDeviceNoteType)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[WarehouseMobileDeviceScannedQuantityLimit](#WarehouseMobileDeviceScannedQuantityLimit)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[AreWarehouseMobileDeviceSessionsLogged](#AreWarehouseMobileDeviceSessionsLogged)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[MaximumStoredWarehouseMobileDeviceErrors](#MaximumStoredWarehouseMobileDeviceErrors)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultInventoryTransferJournalNameId](#DefaultInventoryTransferJournalNameId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultItemArrivalOrderJournalId](#DefaultItemArrivalOrderJournalId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultInventoryStatusId](#DefaultInventoryStatusId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsInventoryStatusDefaultedForOutboundOrders](#IsInventoryStatusDefaultedForOutboundOrders)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsSalesOrderEntryAutomaticallyCreatingLoad](#IsSalesOrderEntryAutomaticallyCreatingLoad)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsTransferOrderEntryAutomaticallyCreatingLoad](#IsTransferOrderEntryAutomaticallyCreatingLoad)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsPurchaseOrderEntryAutomaticallyCreatingLoad](#IsPurchaseOrderEntryAutomaticallyCreatingLoad)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsOrderDeleteAutomaticallyDeletingLoad](#IsOrderDeleteAutomaticallyDeletingLoad)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsWaveProcessingConsolidatingLoads](#IsWaveProcessingConsolidatingLoads)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[LoadSynchronizationPolicy](#LoadSynchronizationPolicy)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[AreWarehouseProcessesCreatingLoadHistoryLog](#AreWarehouseProcessesCreatingLoadHistoryLog)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[AreOrderProcessesCreatingLoadHistoryLog](#AreOrderProcessesCreatingLoadHistoryLog)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultCycleCountingAdjustmentTypeCode](#DefaultCycleCountingAdjustmentTypeCode)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultCycleCountWorkClassId](#DefaultCycleCountWorkClassId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultCycleCountWorkPriority](#DefaultCycleCountWorkPriority)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[AreCustomerFiltersEnabled](#AreCustomerFiltersEnabled)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultCustomerFilterCode](#DefaultCustomerFilterCode)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[AreVendorFiltersEnabled](#AreVendorFiltersEnabled)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultVendorFilterCode](#DefaultVendorFilterCode)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultInventoryFilterWildcard](#DefaultInventoryFilterWildcard)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultBillOfLadingNoteType](#DefaultBillOfLadingNoteType)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultingFreightCountingParty](#DefaultingFreightCountingParty)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[TrailerLoadingParty](#TrailerLoadingParty)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultShipmentPickingListNoteType](#DefaultShipmentPickingListNoteType)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultLoadReportNoteType](#DefaultLoadReportNoteType)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[PackingWarehouseLocationProfileId](#PackingWarehouseLocationProfileId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[PackingWarehouseLocationType](#PackingWarehouseLocationType)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsEarlyToteReuseEnabled](#IsEarlyToteReuseEnabled)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultPackingScreenNoteType](#DefaultPackingScreenNoteType)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[WillWarehouseReleaseDisplayCreditLimitCheckDialog](#WillWarehouseReleaseDisplayCreditLimitCheckDialog)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[DefaultContainerTypeId](#DefaultContainerTypeId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsPendingAllocationLogCreated](#IsPendingAllocationLogCreated)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[SalesOrderFulfillmentPolicyName](#SalesOrderFulfillmentPolicyName)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[SalesOrderFulfillmentPolicy](#SalesOrderFulfillmentPolicy)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[TransferOrderFulfillmentPolicy](#TransferOrderFulfillmentPolicy)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[TransferOrderFulfillmentPolicyName](#TransferOrderFulfillmentPolicyName)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[TransferOrderReceivingProcess](#TransferOrderReceivingProcess)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[MissingASNItemWorkExceptionType](#MissingASNItemWorkExceptionType)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[GeneralWorkProcessingPolicyName](#GeneralWorkProcessingPolicyName)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[WillWaveLabelBuildingGenerateBillOfLadingNumber](#WillWaveLabelBuildingGenerateBillOfLadingNumber)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[OutboundSortingLocationTypeId](#OutboundSortingLocationTypeId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[IsPurchaseOrderRegistrationInExternalReviewEnabled](#IsPurchaseOrderRegistrationInExternalReviewEnabled)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[TransitWarehouseLicensePlatePolicy](#TransitWarehouseLicensePlatePolicy)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultBillOfLadingNoteTypeRelationshipId](#Relationship_DefaultBillOfLadingNoteTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultLoadReportNoteTypeRelationshipId](#Relationship_DefaultLoadReportNoteTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultPackingScreenNoteTypeRelationshipId](#Relationship_DefaultPackingScreenNoteTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_WarehouseMobileDeviceNoteTypeRelationshipId](#Relationship_WarehouseMobileDeviceNoteTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultShipmentPickingListNoteTypeRelationshipId](#Relationship_DefaultShipmentPickingListNoteTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultInventoryTransferJournalNameRelationshipId](#Relationship_DefaultInventoryTransferJournalNameRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultLicensePlateUnitOfMeasureRelationshipId](#Relationship_DefaultLicensePlateUnitOfMeasureRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultCycleCountingAdjustmentTypeRelationshipId](#Relationship_DefaultCycleCountingAdjustmentTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultInventoryAdjustmentTypeRelationshipId](#Relationship_DefaultInventoryAdjustmentTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultInventoryStatusRelationshipId](#Relationship_DefaultInventoryStatusRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_PackingWarehouseLocationProfileRelationshipId](#Relationship_PackingWarehouseLocationProfileRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultUserWarehouseLocationProfileRelationshipId](#Relationship_DefaultUserWarehouseLocationProfileRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultFinalShippingWarehouseLocationTypeRelationshipId](#Relationship_DefaultFinalShippingWarehouseLocationTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultStagingWarehouseLocationTypeRelationshipId](#Relationship_DefaultStagingWarehouseLocationTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultCycleCountWorkClassRelationshipId](#Relationship_DefaultCycleCountWorkClassRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_MissingASNItemWorkExceptionRelationshipId](#Relationship_MissingASNItemWorkExceptionRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultItemArrivalOrderJournalNameRelationshipId](#Relationship_DefaultItemArrivalOrderJournalNameRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_DefaultContainerTypeRelationshipId](#Relationship_DefaultContainerTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_SalesOrderWarehouseFulfillmentPolicyRelationshipId](#Relationship_SalesOrderWarehouseFulfillmentPolicyRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_TransferOrderWarehouseFulfillmentPolicyRelationshipId](#Relationship_TransferOrderWarehouseFulfillmentPolicyRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_OutboundSortingLocationTypeRelationshipId](#Relationship_OutboundSortingLocationTypeRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[BackingTable_WHSParametersRelationshipId](#BackingTable_WHSParametersRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseManagementParametersV2Entity.md" target="_blank">WMS/WHSWarehouseManagementParametersV2Entity</a>|

### <a href=#GS1CompanyPrefix name="GS1CompanyPrefix">GS1CompanyPrefix</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GS1CompanyPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultUserWarehouseLocationProfileId name="DefaultUserWarehouseLocationProfileId">DefaultUserWarehouseLocationProfileId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultUserWarehouseLocationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultStagingWarehouseLocationTypeId name="DefaultStagingWarehouseLocationTypeId">DefaultStagingWarehouseLocationTypeId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultStagingWarehouseLocationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultFinalShippingWarehouseLocationTypeId name="DefaultFinalShippingWarehouseLocationTypeId">DefaultFinalShippingWarehouseLocationTypeId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFinalShippingWarehouseLocationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MissingASNItemWorkExceptionCode name="MissingASNItemWorkExceptionCode">MissingASNItemWorkExceptionCode</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MissingASNItemWorkExceptionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBarcodeSetupId name="DefaultBarcodeSetupId">DefaultBarcodeSetupId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBarcodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLicensePlateUnitSymbol name="DefaultLicensePlateUnitSymbol">DefaultLicensePlateUnitSymbol</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLicensePlateUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultWaveProcessingBatchGroup name="DefaultWaveProcessingBatchGroup">DefaultWaveProcessingBatchGroup</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultWaveProcessingBatchGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreWavesBatchProcessed name="AreWavesBatchProcessed">AreWavesBatchProcessed</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreWavesBatchProcessed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWaveProgressLogCreated name="IsWaveProgressLogCreated">IsWaveProgressLogCreated</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWaveProgressLogCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWaveProcessingHistoryLogCreated name="IsWaveProcessingHistoryLogCreated">IsWaveProcessingHistoryLogCreated</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWaveProcessingHistoryLogCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsContainerizationHistoryLogCreated name="IsContainerizationHistoryLogCreated">IsContainerizationHistoryLogCreated</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsContainerizationHistoryLogCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WaveLockWaitValue name="WaveLockWaitValue">WaveLockWaitValue</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaveLockWaitValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryAdjustmentTypeCode name="DefaultInventoryAdjustmentTypeCode">DefaultInventoryAdjustmentTypeCode</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryAdjustmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTemporaryWorkTableRetained name="IsTemporaryWorkTableRetained">IsTemporaryWorkTableRetained</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTemporaryWorkTableRetained attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkCreationHistoryLogCreated name="IsWorkCreationHistoryLogCreated">IsWorkCreationHistoryLogCreated</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkCreationHistoryLogCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultWarehouseWorkPriority name="DefaultWarehouseWorkPriority">DefaultWarehouseWorkPriority</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultWarehouseWorkPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkCancellationUnregisteringRecept name="IsWorkCancellationUnregisteringRecept">IsWorkCancellationUnregisteringRecept</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkCancellationUnregisteringRecept attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowMixingBatchesDays name="AllowMixingBatchesDays">AllowMixingBatchesDays</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMixingBatchesDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseMobileDeviceNoteType name="WarehouseMobileDeviceNoteType">WarehouseMobileDeviceNoteType</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseMobileDeviceNoteType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseMobileDeviceScannedQuantityLimit name="WarehouseMobileDeviceScannedQuantityLimit">WarehouseMobileDeviceScannedQuantityLimit</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseMobileDeviceScannedQuantityLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreWarehouseMobileDeviceSessionsLogged name="AreWarehouseMobileDeviceSessionsLogged">AreWarehouseMobileDeviceSessionsLogged</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreWarehouseMobileDeviceSessionsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumStoredWarehouseMobileDeviceErrors name="MaximumStoredWarehouseMobileDeviceErrors">MaximumStoredWarehouseMobileDeviceErrors</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumStoredWarehouseMobileDeviceErrors attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryTransferJournalNameId name="DefaultInventoryTransferJournalNameId">DefaultInventoryTransferJournalNameId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

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

### <a href=#DefaultItemArrivalOrderJournalId name="DefaultItemArrivalOrderJournalId">DefaultItemArrivalOrderJournalId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultItemArrivalOrderJournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryStatusId name="DefaultInventoryStatusId">DefaultInventoryStatusId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryStatusDefaultedForOutboundOrders name="IsInventoryStatusDefaultedForOutboundOrders">IsInventoryStatusDefaultedForOutboundOrders</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryStatusDefaultedForOutboundOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesOrderEntryAutomaticallyCreatingLoad name="IsSalesOrderEntryAutomaticallyCreatingLoad">IsSalesOrderEntryAutomaticallyCreatingLoad</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesOrderEntryAutomaticallyCreatingLoad attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransferOrderEntryAutomaticallyCreatingLoad name="IsTransferOrderEntryAutomaticallyCreatingLoad">IsTransferOrderEntryAutomaticallyCreatingLoad</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransferOrderEntryAutomaticallyCreatingLoad attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchaseOrderEntryAutomaticallyCreatingLoad name="IsPurchaseOrderEntryAutomaticallyCreatingLoad">IsPurchaseOrderEntryAutomaticallyCreatingLoad</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseOrderEntryAutomaticallyCreatingLoad attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOrderDeleteAutomaticallyDeletingLoad name="IsOrderDeleteAutomaticallyDeletingLoad">IsOrderDeleteAutomaticallyDeletingLoad</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOrderDeleteAutomaticallyDeletingLoad attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWaveProcessingConsolidatingLoads name="IsWaveProcessingConsolidatingLoads">IsWaveProcessingConsolidatingLoads</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWaveProcessingConsolidatingLoads attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadSynchronizationPolicy name="LoadSynchronizationPolicy">LoadSynchronizationPolicy</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadSynchronizationPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreWarehouseProcessesCreatingLoadHistoryLog name="AreWarehouseProcessesCreatingLoadHistoryLog">AreWarehouseProcessesCreatingLoadHistoryLog</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreWarehouseProcessesCreatingLoadHistoryLog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreOrderProcessesCreatingLoadHistoryLog name="AreOrderProcessesCreatingLoadHistoryLog">AreOrderProcessesCreatingLoadHistoryLog</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreOrderProcessesCreatingLoadHistoryLog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCycleCountingAdjustmentTypeCode name="DefaultCycleCountingAdjustmentTypeCode">DefaultCycleCountingAdjustmentTypeCode</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCycleCountingAdjustmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCycleCountWorkClassId name="DefaultCycleCountWorkClassId">DefaultCycleCountWorkClassId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCycleCountWorkClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCycleCountWorkPriority name="DefaultCycleCountWorkPriority">DefaultCycleCountWorkPriority</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCycleCountWorkPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreCustomerFiltersEnabled name="AreCustomerFiltersEnabled">AreCustomerFiltersEnabled</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreCustomerFiltersEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustomerFilterCode name="DefaultCustomerFilterCode">DefaultCustomerFilterCode</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustomerFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreVendorFiltersEnabled name="AreVendorFiltersEnabled">AreVendorFiltersEnabled</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreVendorFiltersEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVendorFilterCode name="DefaultVendorFilterCode">DefaultVendorFilterCode</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVendorFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryFilterWildcard name="DefaultInventoryFilterWildcard">DefaultInventoryFilterWildcard</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryFilterWildcard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBillOfLadingNoteType name="DefaultBillOfLadingNoteType">DefaultBillOfLadingNoteType</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBillOfLadingNoteType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultingFreightCountingParty name="DefaultingFreightCountingParty">DefaultingFreightCountingParty</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultingFreightCountingParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrailerLoadingParty name="TrailerLoadingParty">TrailerLoadingParty</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrailerLoadingParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShipmentPickingListNoteType name="DefaultShipmentPickingListNoteType">DefaultShipmentPickingListNoteType</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShipmentPickingListNoteType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLoadReportNoteType name="DefaultLoadReportNoteType">DefaultLoadReportNoteType</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLoadReportNoteType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingWarehouseLocationProfileId name="PackingWarehouseLocationProfileId">PackingWarehouseLocationProfileId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingWarehouseLocationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingWarehouseLocationType name="PackingWarehouseLocationType">PackingWarehouseLocationType</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingWarehouseLocationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEarlyToteReuseEnabled name="IsEarlyToteReuseEnabled">IsEarlyToteReuseEnabled</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEarlyToteReuseEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPackingScreenNoteType name="DefaultPackingScreenNoteType">DefaultPackingScreenNoteType</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPackingScreenNoteType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillWarehouseReleaseDisplayCreditLimitCheckDialog name="WillWarehouseReleaseDisplayCreditLimitCheckDialog">WillWarehouseReleaseDisplayCreditLimitCheckDialog</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWarehouseReleaseDisplayCreditLimitCheckDialog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultContainerTypeId name="DefaultContainerTypeId">DefaultContainerTypeId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultContainerTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPendingAllocationLogCreated name="IsPendingAllocationLogCreated">IsPendingAllocationLogCreated</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPendingAllocationLogCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderFulfillmentPolicyName name="SalesOrderFulfillmentPolicyName">SalesOrderFulfillmentPolicyName</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderFulfillmentPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderFulfillmentPolicy name="SalesOrderFulfillmentPolicy">SalesOrderFulfillmentPolicy</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderFulfillmentPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderFulfillmentPolicy name="TransferOrderFulfillmentPolicy">TransferOrderFulfillmentPolicy</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderFulfillmentPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderFulfillmentPolicyName name="TransferOrderFulfillmentPolicyName">TransferOrderFulfillmentPolicyName</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderFulfillmentPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderReceivingProcess name="TransferOrderReceivingProcess">TransferOrderReceivingProcess</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderReceivingProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MissingASNItemWorkExceptionType name="MissingASNItemWorkExceptionType">MissingASNItemWorkExceptionType</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MissingASNItemWorkExceptionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralWorkProcessingPolicyName name="GeneralWorkProcessingPolicyName">GeneralWorkProcessingPolicyName</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralWorkProcessingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillWaveLabelBuildingGenerateBillOfLadingNumber name="WillWaveLabelBuildingGenerateBillOfLadingNumber">WillWaveLabelBuildingGenerateBillOfLadingNumber</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWaveLabelBuildingGenerateBillOfLadingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutboundSortingLocationTypeId name="OutboundSortingLocationTypeId">OutboundSortingLocationTypeId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutboundSortingLocationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchaseOrderRegistrationInExternalReviewEnabled name="IsPurchaseOrderRegistrationInExternalReviewEnabled">IsPurchaseOrderRegistrationInExternalReviewEnabled</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseOrderRegistrationInExternalReviewEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransitWarehouseLicensePlatePolicy name="TransitWarehouseLicensePlatePolicy">TransitWarehouseLicensePlatePolicy</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransitWarehouseLicensePlatePolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultBillOfLadingNoteTypeRelationshipId name="Relationship_DefaultBillOfLadingNoteTypeRelationshipId">Relationship_DefaultBillOfLadingNoteTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultBillOfLadingNoteTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultLoadReportNoteTypeRelationshipId name="Relationship_DefaultLoadReportNoteTypeRelationshipId">Relationship_DefaultLoadReportNoteTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultLoadReportNoteTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultPackingScreenNoteTypeRelationshipId name="Relationship_DefaultPackingScreenNoteTypeRelationshipId">Relationship_DefaultPackingScreenNoteTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultPackingScreenNoteTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseMobileDeviceNoteTypeRelationshipId name="Relationship_WarehouseMobileDeviceNoteTypeRelationshipId">Relationship_WarehouseMobileDeviceNoteTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseMobileDeviceNoteTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultShipmentPickingListNoteTypeRelationshipId name="Relationship_DefaultShipmentPickingListNoteTypeRelationshipId">Relationship_DefaultShipmentPickingListNoteTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultShipmentPickingListNoteTypeRelationshipId attribute are listed below.</summary>

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

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

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

### <a href=#Relationship_DefaultLicensePlateUnitOfMeasureRelationshipId name="Relationship_DefaultLicensePlateUnitOfMeasureRelationshipId">Relationship_DefaultLicensePlateUnitOfMeasureRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultLicensePlateUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultCycleCountingAdjustmentTypeRelationshipId name="Relationship_DefaultCycleCountingAdjustmentTypeRelationshipId">Relationship_DefaultCycleCountingAdjustmentTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultCycleCountingAdjustmentTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryAdjustmentTypeRelationshipId name="Relationship_DefaultInventoryAdjustmentTypeRelationshipId">Relationship_DefaultInventoryAdjustmentTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryAdjustmentTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryStatusRelationshipId name="Relationship_DefaultInventoryStatusRelationshipId">Relationship_DefaultInventoryStatusRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryStatusRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PackingWarehouseLocationProfileRelationshipId name="Relationship_PackingWarehouseLocationProfileRelationshipId">Relationship_PackingWarehouseLocationProfileRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PackingWarehouseLocationProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultUserWarehouseLocationProfileRelationshipId name="Relationship_DefaultUserWarehouseLocationProfileRelationshipId">Relationship_DefaultUserWarehouseLocationProfileRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultUserWarehouseLocationProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultFinalShippingWarehouseLocationTypeRelationshipId name="Relationship_DefaultFinalShippingWarehouseLocationTypeRelationshipId">Relationship_DefaultFinalShippingWarehouseLocationTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultFinalShippingWarehouseLocationTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultStagingWarehouseLocationTypeRelationshipId name="Relationship_DefaultStagingWarehouseLocationTypeRelationshipId">Relationship_DefaultStagingWarehouseLocationTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultStagingWarehouseLocationTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultCycleCountWorkClassRelationshipId name="Relationship_DefaultCycleCountWorkClassRelationshipId">Relationship_DefaultCycleCountWorkClassRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultCycleCountWorkClassRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MissingASNItemWorkExceptionRelationshipId name="Relationship_MissingASNItemWorkExceptionRelationshipId">Relationship_MissingASNItemWorkExceptionRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MissingASNItemWorkExceptionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultItemArrivalOrderJournalNameRelationshipId name="Relationship_DefaultItemArrivalOrderJournalNameRelationshipId">Relationship_DefaultItemArrivalOrderJournalNameRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultItemArrivalOrderJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultContainerTypeRelationshipId name="Relationship_DefaultContainerTypeRelationshipId">Relationship_DefaultContainerTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultContainerTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesOrderWarehouseFulfillmentPolicyRelationshipId name="Relationship_SalesOrderWarehouseFulfillmentPolicyRelationshipId">Relationship_SalesOrderWarehouseFulfillmentPolicyRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesOrderWarehouseFulfillmentPolicyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TransferOrderWarehouseFulfillmentPolicyRelationshipId name="Relationship_TransferOrderWarehouseFulfillmentPolicyRelationshipId">Relationship_TransferOrderWarehouseFulfillmentPolicyRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransferOrderWarehouseFulfillmentPolicyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OutboundSortingLocationTypeRelationshipId name="Relationship_OutboundSortingLocationTypeRelationshipId">Relationship_OutboundSortingLocationTypeRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OutboundSortingLocationTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSParametersRelationshipId name="BackingTable_WHSParametersRelationshipId">BackingTable_WHSParametersRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/WHSParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Parameter/WHSParameters.cdm.json/WHSParameters</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/WHSParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseManagementParametersV2Entity (this entity)  

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
