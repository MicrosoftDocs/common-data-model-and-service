---
title: InventWarehouseEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Warehouses in InventoryAndWarehouseManagement(InventWarehouseEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventWarehouseEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouses</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AreLaborStandardsAllowed](#AreLaborStandardsAllowed)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[InventoryStatusChangeReservationRemovalLevel](#InventoryStatusChangeReservationRemovalLevel)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WillOrderReleasingConsolidateShipments](#WillOrderReleasingConsolidateShipments)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[IsPalletMovementDuringCycleCountingAllowed](#IsPalletMovementDuringCycleCountingAllowed)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WillShippingCancellationDecrementLoadQuanity](#WillShippingCancellationDecrementLoadQuanity)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WarehouseSpecificDefaultInventoryStatusId](#WarehouseSpecificDefaultInventoryStatusId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[IsRetailStoreWarehouse](#IsRetailStoreWarehouse)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WarehouseId](#WarehouseId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[QuarantineWarehouseId](#QuarantineWarehouseId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[MainRefillingWarehouseId](#MainRefillingWarehouseId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[TransitWarehouseId](#TransitWarehouseId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WarehouseType](#WarehouseType)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[OperationalSiteId](#OperationalSiteId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[AreItemsCoveragePlannedManually](#AreItemsCoveragePlannedManually)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WarehouseName](#WarehouseName)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[IsBillOfLadingPrintingBeforeShipmentConfirmationEnabled](#IsBillOfLadingPrintingBeforeShipmentConfirmationEnabled)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WillProductionBOMsReserveWarehouseLevelOnly](#WillProductionBOMsReserveWarehouseLevelOnly)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WillInventoryStatusChangeRemoveBlocking](#WillInventoryStatusChangeRemoveBlocking)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[MasterPlanningWorkCalendardId](#MasterPlanningWorkCalendardId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[IsRefilledFromMainWarehouse](#IsRefilledFromMainWarehouse)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WillManualLoadReleaseReserveInventory](#WillManualLoadReleaseReserveInventory)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[IsFinancialNegativeRetailStoreInventoryAllowed](#IsFinancialNegativeRetailStoreInventoryAllowed)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[IsPhysicalNegativeRetailStoreInventoryAllowed](#IsPhysicalNegativeRetailStoreInventoryAllowed)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[RetailStoreQuantityAllocationReplenismentRuleWeight](#RetailStoreQuantityAllocationReplenismentRuleWeight)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[AreWarehouseLocationCheckDigitsUnique](#AreWarehouseLocationCheckDigitsUnique)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[ExternallyLocatedWarehouseVendorAccountNumber](#ExternallyLocatedWarehouseVendorAccountNumber)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[AreAdvancedWarehouseManagementProcessesEnabled](#AreAdvancedWarehouseManagementProcessesEnabled)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[RawMaterialPickingInventoryIssueStatus](#RawMaterialPickingInventoryIssueStatus)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[ShouldWarehouseLocationIdIncludeAisleId](#ShouldWarehouseLocationIdIncludeAisleId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WarehouseLocationIdShelfIdFormat](#WarehouseLocationIdShelfIdFormat)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WillWarehouseLocationIdIncludeShelfIdByDefault](#WillWarehouseLocationIdIncludeShelfIdByDefault)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WarehouseLocationIdBinIdFormat](#WarehouseLocationIdBinIdFormat)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WillWarehouseLocationIdIncludeBinIdByDefault](#WillWarehouseLocationIdIncludeBinIdByDefault)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WarehouseLocationIdRackIdFormat](#WarehouseLocationIdRackIdFormat)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WillWarehouseLocationIdIncludeRackIdByDefault](#WillWarehouseLocationIdIncludeRackIdByDefault)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WillAutomaticLoadReleaseReserveInventory](#WillAutomaticLoadReleaseReserveInventory)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[MaximumPickingListLineQuantity](#MaximumPickingListLineQuantity)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[MaximumBatchPickingListQuantity](#MaximumBatchPickingListQuantity)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[ArePickingListsDeliveryModeSpecific](#ArePickingListsDeliveryModeSpecific)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[ArePickingListsShipmentSpecificOnly](#ArePickingListsShipmentSpecificOnly)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PickingWorkbenchWarehouseId](#PickingWorkbenchWarehouseId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[IsFallbackWarehouse](#IsFallbackWarehouse)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[FallbackWarehouseId](#FallbackWarehouseId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[FallbackOperationalSiteId](#FallbackOperationalSiteId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressDescription](#PrimaryAddressDescription)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressValidFrom](#PrimaryAddressValidFrom)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressValidTo](#PrimaryAddressValidTo)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[FormattedPrimaryAddress](#FormattedPrimaryAddress)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressCity](#PrimaryAddressCity)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressCityInKana](#PrimaryAddressCityInKana)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressCountryRegionId](#PrimaryAddressCountryRegionId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressCountyId](#PrimaryAddressCountyId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressDistrictName](#PrimaryAddressDistrictName)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressLatitude](#PrimaryAddressLatitude)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressLongitude](#PrimaryAddressLongitude)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressStateId](#PrimaryAddressStateId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressStreet](#PrimaryAddressStreet)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressStreetInKana](#PrimaryAddressStreetInKana)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressStreetNumber](#PrimaryAddressStreetNumber)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressTimeZone](#PrimaryAddressTimeZone)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressZipCode](#PrimaryAddressZipCode)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressBuildingCompliment](#PrimaryAddressBuildingCompliment)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressPostBox](#PrimaryAddressPostBox)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressLocationSalesTaxGroupCode](#PrimaryAddressLocationSalesTaxGroupCode)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[IsPrimaryAddressAssigned](#IsPrimaryAddressAssigned)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[PrimaryAddressLocationRoles](#PrimaryAddressLocationRoles)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[ExternallyLocatedWarehouseCustomerAccountNumber](#ExternallyLocatedWarehouseCustomerAccountNumber)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[IdentificationGroup](#IdentificationGroup)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[DefaultContainerTypeId](#DefaultContainerTypeId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[InventoryCountingReasonCodePolicyName](#InventoryCountingReasonCodePolicyName)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[InventCountingReasonCodePolicyRecId](#InventCountingReasonCodePolicyRecId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WarehouseReleaseReservationRequirementRule](#WarehouseReleaseReservationRequirementRule)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[WarehouseWorkProcessingPolicyName](#WarehouseWorkProcessingPolicyName)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[AutoUpdateShipmentRule](#AutoUpdateShipmentRule)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[Relationship_ExternallyLocatedWarehouseCustomerRelationshipId](#Relationship_ExternallyLocatedWarehouseCustomerRelationshipId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[Relationship_OperationalSiteRelationshipId](#Relationship_OperationalSiteRelationshipId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[Relationship_ExternallyLocatedWarehouseVendorRelationshipId](#Relationship_ExternallyLocatedWarehouseVendorRelationshipId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[Relationship_WarehouseSpecificDefaultInventoryStatusRelationshipId](#Relationship_WarehouseSpecificDefaultInventoryStatusRelationshipId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[Relationship_MasterPlanningWorkCalendarRelationshipId](#Relationship_MasterPlanningWorkCalendarRelationshipId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[Relationship_DefaultContainerTypeRelationshipId](#Relationship_DefaultContainerTypeRelationshipId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[Relationship_InventoryCountingReasonCodePolicyRelationshipId](#Relationship_InventoryCountingReasonCodePolicyRelationshipId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[BackingTable_InventLocationRelationshipId](#BackingTable_InventLocationRelationshipId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventWarehouseEntity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseEntity</a>|

### <a href=#AreLaborStandardsAllowed name="AreLaborStandardsAllowed">AreLaborStandardsAllowed</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreLaborStandardsAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryStatusChangeReservationRemovalLevel name="InventoryStatusChangeReservationRemovalLevel">InventoryStatusChangeReservationRemovalLevel</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryStatusChangeReservationRemovalLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOrderReleasingConsolidateShipments name="WillOrderReleasingConsolidateShipments">WillOrderReleasingConsolidateShipments</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOrderReleasingConsolidateShipments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPalletMovementDuringCycleCountingAllowed name="IsPalletMovementDuringCycleCountingAllowed">IsPalletMovementDuringCycleCountingAllowed</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPalletMovementDuringCycleCountingAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillShippingCancellationDecrementLoadQuanity name="WillShippingCancellationDecrementLoadQuanity">WillShippingCancellationDecrementLoadQuanity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillShippingCancellationDecrementLoadQuanity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseSpecificDefaultInventoryStatusId name="WarehouseSpecificDefaultInventoryStatusId">WarehouseSpecificDefaultInventoryStatusId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseSpecificDefaultInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRetailStoreWarehouse name="IsRetailStoreWarehouse">IsRetailStoreWarehouse</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRetailStoreWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuarantineWarehouseId name="QuarantineWarehouseId">QuarantineWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuarantineWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainRefillingWarehouseId name="MainRefillingWarehouseId">MainRefillingWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainRefillingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransitWarehouseId name="TransitWarehouseId">TransitWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransitWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseType name="WarehouseType">WarehouseType</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationalSiteId name="OperationalSiteId">OperationalSiteId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreItemsCoveragePlannedManually name="AreItemsCoveragePlannedManually">AreItemsCoveragePlannedManually</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreItemsCoveragePlannedManually attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseName name="WarehouseName">WarehouseName</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBillOfLadingPrintingBeforeShipmentConfirmationEnabled name="IsBillOfLadingPrintingBeforeShipmentConfirmationEnabled">IsBillOfLadingPrintingBeforeShipmentConfirmationEnabled</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBillOfLadingPrintingBeforeShipmentConfirmationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionBOMsReserveWarehouseLevelOnly name="WillProductionBOMsReserveWarehouseLevelOnly">WillProductionBOMsReserveWarehouseLevelOnly</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionBOMsReserveWarehouseLevelOnly attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInventoryStatusChangeRemoveBlocking name="WillInventoryStatusChangeRemoveBlocking">WillInventoryStatusChangeRemoveBlocking</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInventoryStatusChangeRemoveBlocking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MasterPlanningWorkCalendardId name="MasterPlanningWorkCalendardId">MasterPlanningWorkCalendardId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MasterPlanningWorkCalendardId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRefilledFromMainWarehouse name="IsRefilledFromMainWarehouse">IsRefilledFromMainWarehouse</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRefilledFromMainWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillManualLoadReleaseReserveInventory name="WillManualLoadReleaseReserveInventory">WillManualLoadReleaseReserveInventory</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillManualLoadReleaseReserveInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFinancialNegativeRetailStoreInventoryAllowed name="IsFinancialNegativeRetailStoreInventoryAllowed">IsFinancialNegativeRetailStoreInventoryAllowed</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinancialNegativeRetailStoreInventoryAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPhysicalNegativeRetailStoreInventoryAllowed name="IsPhysicalNegativeRetailStoreInventoryAllowed">IsPhysicalNegativeRetailStoreInventoryAllowed</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPhysicalNegativeRetailStoreInventoryAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailStoreQuantityAllocationReplenismentRuleWeight name="RetailStoreQuantityAllocationReplenismentRuleWeight">RetailStoreQuantityAllocationReplenismentRuleWeight</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailStoreQuantityAllocationReplenismentRuleWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreWarehouseLocationCheckDigitsUnique name="AreWarehouseLocationCheckDigitsUnique">AreWarehouseLocationCheckDigitsUnique</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreWarehouseLocationCheckDigitsUnique attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternallyLocatedWarehouseVendorAccountNumber name="ExternallyLocatedWarehouseVendorAccountNumber">ExternallyLocatedWarehouseVendorAccountNumber</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternallyLocatedWarehouseVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreAdvancedWarehouseManagementProcessesEnabled name="AreAdvancedWarehouseManagementProcessesEnabled">AreAdvancedWarehouseManagementProcessesEnabled</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreAdvancedWarehouseManagementProcessesEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RawMaterialPickingInventoryIssueStatus name="RawMaterialPickingInventoryIssueStatus">RawMaterialPickingInventoryIssueStatus</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RawMaterialPickingInventoryIssueStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShouldWarehouseLocationIdIncludeAisleId name="ShouldWarehouseLocationIdIncludeAisleId">ShouldWarehouseLocationIdIncludeAisleId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShouldWarehouseLocationIdIncludeAisleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationIdShelfIdFormat name="WarehouseLocationIdShelfIdFormat">WarehouseLocationIdShelfIdFormat</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationIdShelfIdFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillWarehouseLocationIdIncludeShelfIdByDefault name="WillWarehouseLocationIdIncludeShelfIdByDefault">WillWarehouseLocationIdIncludeShelfIdByDefault</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWarehouseLocationIdIncludeShelfIdByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationIdBinIdFormat name="WarehouseLocationIdBinIdFormat">WarehouseLocationIdBinIdFormat</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationIdBinIdFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillWarehouseLocationIdIncludeBinIdByDefault name="WillWarehouseLocationIdIncludeBinIdByDefault">WillWarehouseLocationIdIncludeBinIdByDefault</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWarehouseLocationIdIncludeBinIdByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationIdRackIdFormat name="WarehouseLocationIdRackIdFormat">WarehouseLocationIdRackIdFormat</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationIdRackIdFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillWarehouseLocationIdIncludeRackIdByDefault name="WillWarehouseLocationIdIncludeRackIdByDefault">WillWarehouseLocationIdIncludeRackIdByDefault</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWarehouseLocationIdIncludeRackIdByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAutomaticLoadReleaseReserveInventory name="WillAutomaticLoadReleaseReserveInventory">WillAutomaticLoadReleaseReserveInventory</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAutomaticLoadReleaseReserveInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumPickingListLineQuantity name="MaximumPickingListLineQuantity">MaximumPickingListLineQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumPickingListLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumBatchPickingListQuantity name="MaximumBatchPickingListQuantity">MaximumBatchPickingListQuantity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumBatchPickingListQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePickingListsDeliveryModeSpecific name="ArePickingListsDeliveryModeSpecific">ArePickingListsDeliveryModeSpecific</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePickingListsDeliveryModeSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePickingListsShipmentSpecificOnly name="ArePickingListsShipmentSpecificOnly">ArePickingListsShipmentSpecificOnly</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePickingListsShipmentSpecificOnly attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PickingWorkbenchWarehouseId name="PickingWorkbenchWarehouseId">PickingWorkbenchWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickingWorkbenchWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFallbackWarehouse name="IsFallbackWarehouse">IsFallbackWarehouse</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fallback warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFallbackWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fallback warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FallbackWarehouseId name="FallbackWarehouseId">FallbackWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

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

### <a href=#FallbackOperationalSiteId name="FallbackOperationalSiteId">FallbackOperationalSiteId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FallbackOperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressDescription name="PrimaryAddressDescription">PrimaryAddressDescription</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressValidFrom name="PrimaryAddressValidFrom">PrimaryAddressValidFrom</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressValidTo name="PrimaryAddressValidTo">PrimaryAddressValidTo</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedPrimaryAddress name="FormattedPrimaryAddress">FormattedPrimaryAddress</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedPrimaryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCity name="PrimaryAddressCity">PrimaryAddressCity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCityInKana name="PrimaryAddressCityInKana">PrimaryAddressCityInKana</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCountryRegionId name="PrimaryAddressCountryRegionId">PrimaryAddressCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCountyId name="PrimaryAddressCountyId">PrimaryAddressCountyId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressDistrictName name="PrimaryAddressDistrictName">PrimaryAddressDistrictName</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLatitude name="PrimaryAddressLatitude">PrimaryAddressLatitude</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLongitude name="PrimaryAddressLongitude">PrimaryAddressLongitude</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStateId name="PrimaryAddressStateId">PrimaryAddressStateId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStreet name="PrimaryAddressStreet">PrimaryAddressStreet</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStreetInKana name="PrimaryAddressStreetInKana">PrimaryAddressStreetInKana</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStreetNumber name="PrimaryAddressStreetNumber">PrimaryAddressStreetNumber</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressTimeZone name="PrimaryAddressTimeZone">PrimaryAddressTimeZone</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressZipCode name="PrimaryAddressZipCode">PrimaryAddressZipCode</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressBuildingCompliment name="PrimaryAddressBuildingCompliment">PrimaryAddressBuildingCompliment</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressPostBox name="PrimaryAddressPostBox">PrimaryAddressPostBox</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocationSalesTaxGroupCode name="PrimaryAddressLocationSalesTaxGroupCode">PrimaryAddressLocationSalesTaxGroupCode</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLocationSalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryAddressAssigned name="IsPrimaryAddressAssigned">IsPrimaryAddressAssigned</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryAddressAssigned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocationRoles name="PrimaryAddressLocationRoles">PrimaryAddressLocationRoles</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLocationRoles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternallyLocatedWarehouseCustomerAccountNumber name="ExternallyLocatedWarehouseCustomerAccountNumber">ExternallyLocatedWarehouseCustomerAccountNumber</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternallyLocatedWarehouseCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentificationGroup name="IdentificationGroup">IdentificationGroup</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentificationGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultContainerTypeId name="DefaultContainerTypeId">DefaultContainerTypeId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

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

### <a href=#InventoryCountingReasonCodePolicyName name="InventoryCountingReasonCodePolicyName">InventoryCountingReasonCodePolicyName</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

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

### <a href=#WarehouseReleaseReservationRequirementRule name="WarehouseReleaseReservationRequirementRule">WarehouseReleaseReservationRequirementRule</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseReleaseReservationRequirementRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkProcessingPolicyName name="WarehouseWorkProcessingPolicyName">WarehouseWorkProcessingPolicyName</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkProcessingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoUpdateShipmentRule name="AutoUpdateShipmentRule">AutoUpdateShipmentRule</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoUpdateShipmentRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExternallyLocatedWarehouseCustomerRelationshipId name="Relationship_ExternallyLocatedWarehouseCustomerRelationshipId">Relationship_ExternallyLocatedWarehouseCustomerRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExternallyLocatedWarehouseCustomerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OperationalSiteRelationshipId name="Relationship_OperationalSiteRelationshipId">Relationship_OperationalSiteRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OperationalSiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ExternallyLocatedWarehouseVendorRelationshipId name="Relationship_ExternallyLocatedWarehouseVendorRelationshipId">Relationship_ExternallyLocatedWarehouseVendorRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExternallyLocatedWarehouseVendorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseSpecificDefaultInventoryStatusRelationshipId name="Relationship_WarehouseSpecificDefaultInventoryStatusRelationshipId">Relationship_WarehouseSpecificDefaultInventoryStatusRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseSpecificDefaultInventoryStatusRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MasterPlanningWorkCalendarRelationshipId name="Relationship_MasterPlanningWorkCalendarRelationshipId">Relationship_MasterPlanningWorkCalendarRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MasterPlanningWorkCalendarRelationshipId attribute are listed below.</summary>

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

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

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

### <a href=#Relationship_InventoryCountingReasonCodePolicyRelationshipId name="Relationship_InventoryCountingReasonCodePolicyRelationshipId">Relationship_InventoryCountingReasonCodePolicyRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

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

### <a href=#BackingTable_InventLocationRelationshipId name="BackingTable_InventLocationRelationshipId">BackingTable_InventLocationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseEntity (this entity)  

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
