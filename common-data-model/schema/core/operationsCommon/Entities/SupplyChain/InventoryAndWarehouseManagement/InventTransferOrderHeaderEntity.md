---
title: InventTransferOrderHeaderEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Transfer order headers in InventoryAndWarehouseManagement(InventTransferOrderHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transfer order headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ATPDelayedDemandOffsetDays](#ATPDelayedDemandOffsetDays)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ATPDelayedSupplyOffsetDays](#ATPDelayedSupplyOffsetDays)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ATPBackwardDemandTimeFenceDays](#ATPBackwardDemandTimeFenceDays)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ATPBackwardSupplyTimeFenceDays](#ATPBackwardSupplyTimeFenceDays)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[IsATPIncludingPlannedOrders](#IsATPIncludingPlannedOrders)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ATPTimeFenceDays](#ATPTimeFenceDays)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[AreLinesAutomaticallyReservedByDefault](#AreLinesAutomaticallyReservedByDefault)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[TransferOrderPromisingMethod](#TransferOrderPromisingMethod)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingFreightCompany](#ShippingFreightCompany)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingFreightZone](#ShippingFreightZone)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressName](#ShippingAddressName)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingPostalAddressRecId](#ShippingPostalAddressRecId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[IntrastatSpecialMovementCode](#IntrastatSpecialMovementCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingWarehouseId](#ShippingWarehouseId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingWarehouseId](#ReceivingWarehouseId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[TransitWarehouseId](#TransitWarehouseId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[OverrideFEFODateControl](#OverrideFEFODateControl)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[IntrastatPortId](#IntrastatPortId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[RequestedReceiptDate](#RequestedReceiptDate)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[RequestedShippingDate](#RequestedShippingDate)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[IntrastatStatisticsProcedureCode](#IntrastatStatisticsProcedureCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressName](#ReceivingAddressName)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingPostalAddressRecId](#ReceivingPostalAddressRecId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[IntrastatTransactionCode](#IntrastatTransactionCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[TransferOrderNumber](#TransferOrderNumber)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[TransferOrderStatus](#TransferOrderStatus)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[IntrastatTransportModeCode](#IntrastatTransportModeCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[TransportationDocumentLineId](#TransportationDocumentLineId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingContactPersonnelNumber](#ShippingContactPersonnelNumber)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingContactPersonnelNumber](#ReceivingContactPersonnelNumber)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[FormattedShippingAddress](#FormattedShippingAddress)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingBuildingCompliment](#ShippingBuildingCompliment)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressCity](#ShippingAddressCity)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressCityInKana](#ShippingAddressCityInKana)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressCountryRegionId](#ShippingAddressCountryRegionId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressCountryRegionISOCode](#ShippingAddressCountryRegionISOCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressCountyId](#ShippingAddressCountyId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressDescription](#ShippingAddressDescription)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressDistrictName](#ShippingAddressDistrictName)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressDunsNumber](#ShippingAddressDunsNumber)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[IsShippingAddressPrivate](#IsShippingAddressPrivate)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressLatitude](#ShippingAddressLatitude)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressLocationId](#ShippingAddressLocationId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressLongitude](#ShippingAddressLongitude)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressPostBox](#ShippingAddressPostBox)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressStateId](#ShippingAddressStateId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressStreet](#ShippingAddressStreet)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressStreetInKana](#ShippingAddressStreetInKana)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressStreetNumber](#ShippingAddressStreetNumber)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressTimeZone](#ShippingAddressTimeZone)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressValidFrom](#ShippingAddressValidFrom)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressValidTo](#ShippingAddressValidTo)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingAddressZipCode](#ShippingAddressZipCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[FormattedReceivingAddress](#FormattedReceivingAddress)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingBuildingCompliment](#ReceivingBuildingCompliment)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressCity](#ReceivingAddressCity)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressCityInKana](#ReceivingAddressCityInKana)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressCountryRegionId](#ReceivingAddressCountryRegionId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressCountryRegionISOCode](#ReceivingAddressCountryRegionISOCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressCountyId](#ReceivingAddressCountyId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressDescription](#ReceivingAddressDescription)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressDistrictName](#ReceivingAddressDistrictName)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressDunsNumber](#ReceivingAddressDunsNumber)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[IsReceivingAddressPrivate](#IsReceivingAddressPrivate)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressLatitude](#ReceivingAddressLatitude)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressLocationId](#ReceivingAddressLocationId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressLongitude](#ReceivingAddressLongitude)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressPostBox](#ReceivingAddressPostBox)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressStateId](#ReceivingAddressStateId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressStreet](#ReceivingAddressStreet)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressStreetInKana](#ReceivingAddressStreetInKana)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressStreetNumber](#ReceivingAddressStreetNumber)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressTimeZone](#ReceivingAddressTimeZone)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressValidFrom](#ReceivingAddressValidFrom)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressValidTo](#ReceivingAddressValidTo)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ReceivingAddressZipCode](#ReceivingAddressZipCode)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingCarrierId](#ShippingCarrierId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingCarrierServiceGroupId](#ShippingCarrierServiceGroupId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[ShippingCarrierServiceId](#ShippingCarrierServiceId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[TransportationModeId](#TransportationModeId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[BackingTable_InventTransferTableRelationshipId](#BackingTable_InventTransferTableRelationshipId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventTransferOrderHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity</a>|

### <a href=#ATPDelayedDemandOffsetDays name="ATPDelayedDemandOffsetDays">ATPDelayedDemandOffsetDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPDelayedDemandOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATPDelayedSupplyOffsetDays name="ATPDelayedSupplyOffsetDays">ATPDelayedSupplyOffsetDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPDelayedSupplyOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATPBackwardDemandTimeFenceDays name="ATPBackwardDemandTimeFenceDays">ATPBackwardDemandTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPBackwardDemandTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATPBackwardSupplyTimeFenceDays name="ATPBackwardSupplyTimeFenceDays">ATPBackwardSupplyTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPBackwardSupplyTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsATPIncludingPlannedOrders name="IsATPIncludingPlannedOrders">IsATPIncludingPlannedOrders</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsATPIncludingPlannedOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATPTimeFenceDays name="ATPTimeFenceDays">ATPTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreLinesAutomaticallyReservedByDefault name="AreLinesAutomaticallyReservedByDefault">AreLinesAutomaticallyReservedByDefault</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreLinesAutomaticallyReservedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderPromisingMethod name="TransferOrderPromisingMethod">TransferOrderPromisingMethod</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderPromisingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCode name="DeliveryModeCode">DeliveryModeCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCode name="DeliveryTermsCode">DeliveryTermsCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingFreightCompany name="ShippingFreightCompany">ShippingFreightCompany</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingFreightCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingFreightZone name="ShippingFreightZone">ShippingFreightZone</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingFreightZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressName name="ShippingAddressName">ShippingAddressName</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingPostalAddressRecId name="ShippingPostalAddressRecId">ShippingPostalAddressRecId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatSpecialMovementCode name="IntrastatSpecialMovementCode">IntrastatSpecialMovementCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatSpecialMovementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingWarehouseId name="ShippingWarehouseId">ShippingWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingWarehouseId name="ReceivingWarehouseId">ReceivingWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransitWarehouseId name="TransitWarehouseId">TransitWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

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

### <a href=#OverrideFEFODateControl name="OverrideFEFODateControl">OverrideFEFODateControl</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideFEFODateControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatPortId name="IntrastatPortId">IntrastatPortId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatPortId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedReceiptDate name="RequestedReceiptDate">RequestedReceiptDate</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShippingDate name="RequestedShippingDate">RequestedShippingDate</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatStatisticsProcedureCode name="IntrastatStatisticsProcedureCode">IntrastatStatisticsProcedureCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatStatisticsProcedureCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressName name="ReceivingAddressName">ReceivingAddressName</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingPostalAddressRecId name="ReceivingPostalAddressRecId">ReceivingPostalAddressRecId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransactionCode name="IntrastatTransactionCode">IntrastatTransactionCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderNumber name="TransferOrderNumber">TransferOrderNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderStatus name="TransferOrderStatus">TransferOrderStatus</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransportModeCode name="IntrastatTransportModeCode">IntrastatTransportModeCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransportModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDocumentLineId name="TransportationDocumentLineId">TransportationDocumentLineId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDocumentLineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingContactPersonnelNumber name="ShippingContactPersonnelNumber">ShippingContactPersonnelNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingContactPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingContactPersonnelNumber name="ReceivingContactPersonnelNumber">ReceivingContactPersonnelNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingContactPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedShippingAddress name="FormattedShippingAddress">FormattedShippingAddress</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Formatted shipping address</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedShippingAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Formatted shipping address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingBuildingCompliment name="ShippingBuildingCompliment">ShippingBuildingCompliment</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping building complement</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping building complement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressCity name="ShippingAddressCity">ShippingAddressCity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address city</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address city</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressCityInKana name="ShippingAddressCityInKana">ShippingAddressCityInKana</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address city in Kana</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address city in Kana</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressCountryRegionId name="ShippingAddressCountryRegionId">ShippingAddressCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address country/region</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address country/region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressCountryRegionISOCode name="ShippingAddressCountryRegionISOCode">ShippingAddressCountryRegionISOCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address country/region ISO</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address country/region ISO</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressCountyId name="ShippingAddressCountyId">ShippingAddressCountyId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address county</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address county</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressDescription name="ShippingAddressDescription">ShippingAddressDescription</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressDistrictName name="ShippingAddressDistrictName">ShippingAddressDistrictName</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address district</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address district</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressDunsNumber name="ShippingAddressDunsNumber">ShippingAddressDunsNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address DUNS number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address DUNS number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsShippingAddressPrivate name="IsShippingAddressPrivate">IsShippingAddressPrivate</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is shipping address private</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsShippingAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is shipping address private</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressLatitude name="ShippingAddressLatitude">ShippingAddressLatitude</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address latitude</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address latitude</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressLocationId name="ShippingAddressLocationId">ShippingAddressLocationId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressLongitude name="ShippingAddressLongitude">ShippingAddressLongitude</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address longitude</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address longitude</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressPostBox name="ShippingAddressPostBox">ShippingAddressPostBox</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address post box</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address post box</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressStateId name="ShippingAddressStateId">ShippingAddressStateId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address state</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address state</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressStreet name="ShippingAddressStreet">ShippingAddressStreet</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address street</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address street</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressStreetInKana name="ShippingAddressStreetInKana">ShippingAddressStreetInKana</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address street in Kana</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address street in Kana</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressStreetNumber name="ShippingAddressStreetNumber">ShippingAddressStreetNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address street number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address street number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressTimeZone name="ShippingAddressTimeZone">ShippingAddressTimeZone</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address time zone</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address time zone</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressValidFrom name="ShippingAddressValidFrom">ShippingAddressValidFrom</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressValidTo name="ShippingAddressValidTo">ShippingAddressValidTo</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingAddressZipCode name="ShippingAddressZipCode">ShippingAddressZipCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping address ZIP/postal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping address ZIP/postal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedReceivingAddress name="FormattedReceivingAddress">FormattedReceivingAddress</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Formatted receiving address</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedReceivingAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Formatted receiving address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingBuildingCompliment name="ReceivingBuildingCompliment">ReceivingBuildingCompliment</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving building complement</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving building complement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressCity name="ReceivingAddressCity">ReceivingAddressCity</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address city</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address city</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressCityInKana name="ReceivingAddressCityInKana">ReceivingAddressCityInKana</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address city in Kana</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address city in Kana</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressCountryRegionId name="ReceivingAddressCountryRegionId">ReceivingAddressCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address country/region</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address country/region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressCountryRegionISOCode name="ReceivingAddressCountryRegionISOCode">ReceivingAddressCountryRegionISOCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address country/region ISO</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address country/region ISO</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressCountyId name="ReceivingAddressCountyId">ReceivingAddressCountyId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address county</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address county</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressDescription name="ReceivingAddressDescription">ReceivingAddressDescription</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressDistrictName name="ReceivingAddressDistrictName">ReceivingAddressDistrictName</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address district</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address district</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressDunsNumber name="ReceivingAddressDunsNumber">ReceivingAddressDunsNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address DUNS number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address DUNS number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReceivingAddressPrivate name="IsReceivingAddressPrivate">IsReceivingAddressPrivate</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is receiving address private</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReceivingAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is receiving address private</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressLatitude name="ReceivingAddressLatitude">ReceivingAddressLatitude</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address latitude</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address latitude</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressLocationId name="ReceivingAddressLocationId">ReceivingAddressLocationId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressLongitude name="ReceivingAddressLongitude">ReceivingAddressLongitude</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address longitude</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address longitude</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressPostBox name="ReceivingAddressPostBox">ReceivingAddressPostBox</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address post box</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address post box</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressStateId name="ReceivingAddressStateId">ReceivingAddressStateId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address state</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address state</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressStreet name="ReceivingAddressStreet">ReceivingAddressStreet</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address street</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address street</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressStreetInKana name="ReceivingAddressStreetInKana">ReceivingAddressStreetInKana</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address street in Kana</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address street in Kana</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressStreetNumber name="ReceivingAddressStreetNumber">ReceivingAddressStreetNumber</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address street number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address street number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressTimeZone name="ReceivingAddressTimeZone">ReceivingAddressTimeZone</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address time zone</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address time zone</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressValidFrom name="ReceivingAddressValidFrom">ReceivingAddressValidFrom</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressValidTo name="ReceivingAddressValidTo">ReceivingAddressValidTo</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingAddressZipCode name="ReceivingAddressZipCode">ReceivingAddressZipCode</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receiving address ZIP/postal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receiving address ZIP/postal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierId name="ShippingCarrierId">ShippingCarrierId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceGroupId name="ShippingCarrierServiceGroupId">ShippingCarrierServiceGroupId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceId name="ShippingCarrierServiceId">ShippingCarrierServiceId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationModeId name="TransportationModeId">TransportationModeId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationModeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventTransferTableRelationshipId name="BackingTable_InventTransferTableRelationshipId">BackingTable_InventTransferTableRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventTransferTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferTable.cdm.json/InventTransferTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventTransferOrderHeaderEntity (this entity)  

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
