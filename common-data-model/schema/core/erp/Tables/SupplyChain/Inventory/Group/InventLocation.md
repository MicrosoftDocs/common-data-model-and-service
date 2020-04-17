---
title: InventLocation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# InventLocation

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventLocation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[ActivityType_RU](#ActivityType_RU)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[AllowLaborStandards](#AllowLaborStandards)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[AllowMarkingReservationRemoval](#AllowMarkingReservationRemoval)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[BranchNumber](#BranchNumber)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[ConsolidateShipAtRTW](#ConsolidateShipAtRTW)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[CustAccount_BR](#CustAccount_BR)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[CustAccount_HU](#CustAccount_HU)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[CycleCountAllowPalletMove](#CycleCountAllowPalletMove)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DecrementLoadLine](#DecrementLoadLine)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DefaultKanbanFinishedGoodsLocation](#DefaultKanbanFinishedGoodsLocation)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DefaultProductionFinishGoodsLocation](#DefaultProductionFinishGoodsLocation)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DefaultShipMaintenanceLoc](#DefaultShipMaintenanceLoc)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DefaultStatusId](#DefaultStatusId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[FSHStore](#FSHStore)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventCountingGroup_BR](#InventCountingGroup_BR)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventLocationId](#InventLocationId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventLocationIdGoodsInRoute_RU](#InventLocationIdGoodsInRoute_RU)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventLocationIdQuarantine](#InventLocationIdQuarantine)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventLocationIdReqMain](#InventLocationIdReqMain)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventLocationIdTransit](#InventLocationIdTransit)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventLocationLevel](#InventLocationLevel)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventLocationType](#InventLocationType)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventProfileId_RU](#InventProfileId_RU)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventProfileType_RU](#InventProfileType_RU)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[InventSiteId](#InventSiteId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Manual](#Manual)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Name](#Name)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[NumberSequenceGroup_RU](#NumberSequenceGroup_RU)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[PrintBOLBeforeShipConfirm](#PrintBOLBeforeShipConfirm)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[ProdReserveOnlyWhse](#ProdReserveOnlyWhse)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[RBODefaultInventProfileId_RU](#RBODefaultInventProfileId_RU)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[RBODefaultWMSLocationId](#RBODefaultWMSLocationId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[RemoveInventBlockingOnStatusChange](#RemoveInventBlockingOnStatusChange)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[ReqCalendarId](#ReqCalendarId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[ReqRefill](#ReqRefill)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[ReserveAtLoadPost](#ReserveAtLoadPost)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[RetailInventNegFinancial](#RetailInventNegFinancial)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[RetailInventNegPhysical](#RetailInventNegPhysical)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[RetailWeightEx1](#RetailWeightEx1)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[RetailWMSLocationIdDefaultReturn](#RetailWMSLocationIdDefaultReturn)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[UniqueCheckDigits](#UniqueCheckDigits)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[VendAccount](#VendAccount)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[VendAccountCustom_RU](#VendAccountCustom_RU)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WHSEnabled](#WHSEnabled)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WHSRawMaterialPolicy](#WHSRawMaterialPolicy)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSAisleNameActive](#WMSAisleNameActive)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSLevelFormat](#WMSLevelFormat)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSLevelNameActive](#WMSLevelNameActive)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSlocationIdDefaultIssue](#WMSlocationIdDefaultIssue)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSLocationIdDefaultReceipt](#WMSLocationIdDefaultReceipt)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSLocationIdGoodsInRoute_RU](#WMSLocationIdGoodsInRoute_RU)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSPositionFormat](#WMSPositionFormat)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSPositionNameActive](#WMSPositionNameActive)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSRackFormat](#WMSRackFormat)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WMSRackNameActive](#WMSRackNameActive)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WarehouseAutoReleaseReservation](#WarehouseAutoReleaseReservation)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DefaultProductionInputLocation](#DefaultProductionInputLocation)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DefaultReturnCreditOnlyLocation](#DefaultReturnCreditOnlyLocation)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DefaultContainerTypeCode](#DefaultContainerTypeCode)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[ReleaseToWarehouseRule](#ReleaseToWarehouseRule)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[WorkProcessingPolicyName](#WorkProcessingPolicyName)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[AutoUpdateShipment](#AutoUpdateShipment)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DefaultQualityMaintenanceLocation](#DefaultQualityMaintenanceLocation)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[EnableQualityManagement](#EnableQualityManagement)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[RejectOrderFulfillment](#RejectOrderFulfillment)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[DataAreaId](#DataAreaId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_CustomPartners_VendAccountCustom_RURelationshipId](#Relationship_CustomPartners_VendAccountCustom_RURelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_CustTable_CustAccount_HURelationshipId](#Relationship_CustTable_CustAccount_HURelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_EmptyPalletLocationRelationshipId](#Relationship_EmptyPalletLocationRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_InventProfile_RURelationshipId](#Relationship_InventProfile_RURelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_InventSiteRelationshipId](#Relationship_InventSiteRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_NumberSequenceGroup_RURelationshipId](#Relationship_NumberSequenceGroup_RURelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_RBODefaultInventProfileId_RURelationshipId](#Relationship_RBODefaultInventProfileId_RURelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_RetailWMSlocationDefaultReturnRelationshipId](#Relationship_RetailWMSlocationDefaultReturnRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_VendTable_VendAccountCustom_RURelationshipId](#Relationship_VendTable_VendAccountCustom_RURelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_WHSInventStatusRelationshipId](#Relationship_WHSInventStatusRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_WMSLocationIdDefaultIssueRelationshipId](#Relationship_WMSLocationIdDefaultIssueRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_WMSLocationIdDefaultReceiptRelationshipId](#Relationship_WMSLocationIdDefaultReceiptRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_WMSLocationIdGoodsInRoute_RURelationshipId](#Relationship_WMSLocationIdGoodsInRoute_RURelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_WorkCalendarTableRelationshipId](#Relationship_WorkCalendarTableRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_DefaultReturnLocationRelationshipId](#Relationship_DefaultReturnLocationRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_WHSContainerTypeRelationshipId](#Relationship_WHSContainerTypeRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_DefaultKanbanFinishedGoodsLocationRelationshipId](#Relationship_DefaultKanbanFinishedGoodsLocationRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_DefaultProductionFinishGoodsLocationRelationshipId](#Relationship_DefaultProductionFinishGoodsLocationRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_DefaultShipMaintenanceLocRelationshipId](#Relationship_DefaultShipMaintenanceLocRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_DefaultReturnCreditOnlyLocationRelationshipId](#Relationship_DefaultReturnCreditOnlyLocationRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_DefaultProductionInputLocationRelationshipId](#Relationship_DefaultProductionInputLocationRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_WHSWorkProcessingPolicyRelationshipId](#Relationship_WHSWorkProcessingPolicyRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_DefaultQualityMaintenanceLocationRelationshipId](#Relationship_DefaultQualityMaintenanceLocationRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_RetailInfocodeTable_RejectOrderFulfillmentRelationshipId](#Relationship_RetailInfocodeTable_RejectOrderFulfillmentRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventLocation.md" target="_blank">Group/InventLocation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventLocation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActivityType_RU name="ActivityType_RU">ActivityType_RU</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityType_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowLaborStandards name="AllowLaborStandards">AllowLaborStandards</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowLaborStandards attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowMarkingReservationRemoval name="AllowMarkingReservationRemoval">AllowMarkingReservationRemoval</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMarkingReservationRemoval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BranchNumber name="BranchNumber">BranchNumber</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BranchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsolidateShipAtRTW name="ConsolidateShipAtRTW">ConsolidateShipAtRTW</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidateShipAtRTW attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustAccount_BR name="CustAccount_BR">CustAccount_BR</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccount_HU name="CustAccount_HU">CustAccount_HU</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount_HU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CycleCountAllowPalletMove name="CycleCountAllowPalletMove">CycleCountAllowPalletMove</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CycleCountAllowPalletMove attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DecrementLoadLine name="DecrementLoadLine">DecrementLoadLine</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecrementLoadLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultKanbanFinishedGoodsLocation name="DefaultKanbanFinishedGoodsLocation">DefaultKanbanFinishedGoodsLocation</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultKanbanFinishedGoodsLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductionFinishGoodsLocation name="DefaultProductionFinishGoodsLocation">DefaultProductionFinishGoodsLocation</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionFinishGoodsLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShipMaintenanceLoc name="DefaultShipMaintenanceLoc">DefaultShipMaintenanceLoc</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShipMaintenanceLoc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultStatusId name="DefaultStatusId">DefaultStatusId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FSHStore name="FSHStore">FSHStore</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FSHStore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventCountingGroup_BR name="InventCountingGroup_BR">InventCountingGroup_BR</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventCountingGroup_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationIdGoodsInRoute_RU name="InventLocationIdGoodsInRoute_RU">InventLocationIdGoodsInRoute_RU</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdGoodsInRoute_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationIdQuarantine name="InventLocationIdQuarantine">InventLocationIdQuarantine</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdQuarantine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationIdReqMain name="InventLocationIdReqMain">InventLocationIdReqMain</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdReqMain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationIdTransit name="InventLocationIdTransit">InventLocationIdTransit</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdTransit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationLevel name="InventLocationLevel">InventLocationLevel</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#InventLocationType name="InventLocationType">InventLocationType</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventProfileId_RU name="InventProfileId_RU">InventProfileId_RU</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventProfileType_RU name="InventProfileType_RU">InventProfileType_RU</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventSiteId name="InventSiteId">InventSiteId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Manual name="Manual">Manual</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Manual attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroup_RU name="NumberSequenceGroup_RU">NumberSequenceGroup_RU</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroup_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBOLBeforeShipConfirm name="PrintBOLBeforeShipConfirm">PrintBOLBeforeShipConfirm</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBOLBeforeShipConfirm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProdReserveOnlyWhse name="ProdReserveOnlyWhse">ProdReserveOnlyWhse</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdReserveOnlyWhse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RBODefaultInventProfileId_RU name="RBODefaultInventProfileId_RU">RBODefaultInventProfileId_RU</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RBODefaultInventProfileId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RBODefaultWMSLocationId name="RBODefaultWMSLocationId">RBODefaultWMSLocationId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RBODefaultWMSLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemoveInventBlockingOnStatusChange name="RemoveInventBlockingOnStatusChange">RemoveInventBlockingOnStatusChange</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemoveInventBlockingOnStatusChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReqCalendarId name="ReqCalendarId">ReqCalendarId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqRefill name="ReqRefill">ReqRefill</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqRefill attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReserveAtLoadPost name="ReserveAtLoadPost">ReserveAtLoadPost</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReserveAtLoadPost attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInventNegFinancial name="RetailInventNegFinancial">RetailInventNegFinancial</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInventNegFinancial attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInventNegPhysical name="RetailInventNegPhysical">RetailInventNegPhysical</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInventNegPhysical attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailWeightEx1 name="RetailWeightEx1">RetailWeightEx1</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailWeightEx1 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RetailWMSLocationIdDefaultReturn name="RetailWMSLocationIdDefaultReturn">RetailWMSLocationIdDefaultReturn</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailWMSLocationIdDefaultReturn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UniqueCheckDigits name="UniqueCheckDigits">UniqueCheckDigits</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UniqueCheckDigits attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendAccountCustom_RU name="VendAccountCustom_RU">VendAccountCustom_RU</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccountCustom_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WHSEnabled name="WHSEnabled">WHSEnabled</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WHSEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WHSRawMaterialPolicy name="WHSRawMaterialPolicy">WHSRawMaterialPolicy</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WHSRawMaterialPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WMSAisleNameActive name="WMSAisleNameActive">WMSAisleNameActive</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSAisleNameActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WMSLevelFormat name="WMSLevelFormat">WMSLevelFormat</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSLevelFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSLevelNameActive name="WMSLevelNameActive">WMSLevelNameActive</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSLevelNameActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WMSlocationIdDefaultIssue name="WMSlocationIdDefaultIssue">WMSlocationIdDefaultIssue</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSlocationIdDefaultIssue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSLocationIdDefaultReceipt name="WMSLocationIdDefaultReceipt">WMSLocationIdDefaultReceipt</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSLocationIdDefaultReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSLocationIdGoodsInRoute_RU name="WMSLocationIdGoodsInRoute_RU">WMSLocationIdGoodsInRoute_RU</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSLocationIdGoodsInRoute_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSPositionFormat name="WMSPositionFormat">WMSPositionFormat</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSPositionFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSPositionNameActive name="WMSPositionNameActive">WMSPositionNameActive</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSPositionNameActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WMSRackFormat name="WMSRackFormat">WMSRackFormat</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSRackFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSRackNameActive name="WMSRackNameActive">WMSRackNameActive</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSRackNameActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WarehouseAutoReleaseReservation name="WarehouseAutoReleaseReservation">WarehouseAutoReleaseReservation</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseAutoReleaseReservation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultProductionInputLocation name="DefaultProductionInputLocation">DefaultProductionInputLocation</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionInputLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReturnCreditOnlyLocation name="DefaultReturnCreditOnlyLocation">DefaultReturnCreditOnlyLocation</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReturnCreditOnlyLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultContainerTypeCode name="DefaultContainerTypeCode">DefaultContainerTypeCode</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultContainerTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleaseToWarehouseRule name="ReleaseToWarehouseRule">ReleaseToWarehouseRule</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleaseToWarehouseRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WorkProcessingPolicyName name="WorkProcessingPolicyName">WorkProcessingPolicyName</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkProcessingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoUpdateShipment name="AutoUpdateShipment">AutoUpdateShipment</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoUpdateShipment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultQualityMaintenanceLocation name="DefaultQualityMaintenanceLocation">DefaultQualityMaintenanceLocation</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultQualityMaintenanceLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableQualityManagement name="EnableQualityManagement">EnableQualityManagement</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableQualityManagement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RejectOrderFulfillment name="RejectOrderFulfillment">RejectOrderFulfillment</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RejectOrderFulfillment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomPartners_VendAccountCustom_RURelationshipId name="Relationship_CustomPartners_VendAccountCustom_RURelationshipId">Relationship_CustomPartners_VendAccountCustom_RURelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomPartners_VendAccountCustom_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/CustomPartners_RU.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Main/CustomPartners_RU.cdm.json/CustomPartners_RU</a></td><td><a href="../../../Finance/AccountsReceivable/Main/CustomPartners_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/erp/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTable_CustAccount_HURelationshipId name="Relationship_CustTable_CustAccount_HURelationshipId">Relationship_CustTable_CustAccount_HURelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTable_CustAccount_HURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/erp/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EmptyPalletLocationRelationshipId name="Relationship_EmptyPalletLocationRelationshipId">Relationship_EmptyPalletLocationRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EmptyPalletLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventProfile_RURelationshipId name="Relationship_InventProfile_RURelationshipId">Relationship_InventProfile_RURelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventProfile_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventProfile_RU.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventProfile_RU.cdm.json/InventProfile_RU</a></td><td><a href="InventProfile_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSiteRelationshipId name="Relationship_InventSiteRelationshipId">Relationship_InventSiteRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventSiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventSite.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventSite.cdm.json/InventSite</a></td><td><a href="InventSite.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceGroup_RURelationshipId name="Relationship_NumberSequenceGroup_RURelationshipId">Relationship_NumberSequenceGroup_RURelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceGroup_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Framework/NumberSequenceGroup.cdm.json/NumberSequenceGroup</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RBODefaultInventProfileId_RURelationshipId name="Relationship_RBODefaultInventProfileId_RURelationshipId">Relationship_RBODefaultInventProfileId_RURelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RBODefaultInventProfileId_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventProfile_RU.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventProfile_RU.cdm.json/InventProfile_RU</a></td><td><a href="InventProfile_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailWMSlocationDefaultReturnRelationshipId name="Relationship_RetailWMSlocationDefaultReturnRelationshipId">Relationship_RetailWMSlocationDefaultReturnRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailWMSlocationDefaultReturnRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/erp/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTable_VendAccountCustom_RURelationshipId name="Relationship_VendTable_VendAccountCustom_RURelationshipId">Relationship_VendTable_VendAccountCustom_RURelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTable_VendAccountCustom_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/erp/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSInventStatusRelationshipId name="Relationship_WHSInventStatusRelationshipId">Relationship_WHSInventStatusRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSInventStatusRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WHSInventStatus.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WHSInventStatus.cdm.json/WHSInventStatus</a></td><td><a href="../Main/WHSInventStatus.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSLocationIdDefaultIssueRelationshipId name="Relationship_WMSLocationIdDefaultIssueRelationshipId">Relationship_WMSLocationIdDefaultIssueRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSLocationIdDefaultIssueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSLocationIdDefaultReceiptRelationshipId name="Relationship_WMSLocationIdDefaultReceiptRelationshipId">Relationship_WMSLocationIdDefaultReceiptRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSLocationIdDefaultReceiptRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSLocationIdGoodsInRoute_RURelationshipId name="Relationship_WMSLocationIdGoodsInRoute_RURelationshipId">Relationship_WMSLocationIdGoodsInRoute_RURelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSLocationIdGoodsInRoute_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkCalendarTableRelationshipId name="Relationship_WorkCalendarTableRelationshipId">Relationship_WorkCalendarTableRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkCalendarTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Group/WorkCalendarTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Group/WorkCalendarTable.cdm.json/WorkCalendarTable</a></td><td><a href="../../ProductionControl/Group/WorkCalendarTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultReturnLocationRelationshipId name="Relationship_DefaultReturnLocationRelationshipId">Relationship_DefaultReturnLocationRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultReturnLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSContainerTypeRelationshipId name="Relationship_WHSContainerTypeRelationshipId">Relationship_WHSContainerTypeRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSContainerTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSContainerType.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/WHSContainerType.cdm.json/WHSContainerType</a></td><td><a href="WHSContainerType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultKanbanFinishedGoodsLocationRelationshipId name="Relationship_DefaultKanbanFinishedGoodsLocationRelationshipId">Relationship_DefaultKanbanFinishedGoodsLocationRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultKanbanFinishedGoodsLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultProductionFinishGoodsLocationRelationshipId name="Relationship_DefaultProductionFinishGoodsLocationRelationshipId">Relationship_DefaultProductionFinishGoodsLocationRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultProductionFinishGoodsLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultShipMaintenanceLocRelationshipId name="Relationship_DefaultShipMaintenanceLocRelationshipId">Relationship_DefaultShipMaintenanceLocRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultShipMaintenanceLocRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultReturnCreditOnlyLocationRelationshipId name="Relationship_DefaultReturnCreditOnlyLocationRelationshipId">Relationship_DefaultReturnCreditOnlyLocationRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultReturnCreditOnlyLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultProductionInputLocationRelationshipId name="Relationship_DefaultProductionInputLocationRelationshipId">Relationship_DefaultProductionInputLocationRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultProductionInputLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSWorkProcessingPolicyRelationshipId name="Relationship_WHSWorkProcessingPolicyRelationshipId">Relationship_WHSWorkProcessingPolicyRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSWorkProcessingPolicyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSWorkProcessingPolicy.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/WHSWorkProcessingPolicy.cdm.json/WHSWorkProcessingPolicy</a></td><td><a href="WHSWorkProcessingPolicy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultQualityMaintenanceLocationRelationshipId name="Relationship_DefaultQualityMaintenanceLocationRelationshipId">Relationship_DefaultQualityMaintenanceLocationRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultQualityMaintenanceLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable_RejectOrderFulfillmentRelationshipId name="Relationship_RetailInfocodeTable_RejectOrderFulfillmentRelationshipId">Relationship_RetailInfocodeTable_RejectOrderFulfillmentRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable_RejectOrderFulfillmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Main/RetailInfocode.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../Commerce/Retail/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/InventLocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
