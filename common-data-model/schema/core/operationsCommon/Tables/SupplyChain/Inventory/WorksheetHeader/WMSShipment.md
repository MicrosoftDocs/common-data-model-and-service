---
title: WMSShipment - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# WMSShipment

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WMSShipment.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WMSShipment/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[autoAddStop](#autoAddStop)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[CargoDescription_RU](#CargoDescription_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[CargoPacking_RU](#CargoPacking_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[CarrierCode_RU](#CarrierCode_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[CarrierType_RU](#CarrierType_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[DeliveryDate_RU](#DeliveryDate_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Driver_RU](#Driver_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[DriverContact_RU](#DriverContact_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[DriverName_RU](#DriverName_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[DrivingLicenseNum_RU](#DrivingLicenseNum_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[inventLocationId](#inventLocationId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[InventSiteId](#InventSiteId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[isShipmentMultiSiteActivated](#isShipmentMultiSiteActivated)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[LicenseCardNum_RU](#LicenseCardNum_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[LicenseCardRegNum_RU](#LicenseCardRegNum_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[LicenseCardSeries_RU](#LicenseCardSeries_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[LicenseCardType_RU](#LicenseCardType_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[name](#name)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[OffSessionId_RU](#OffSessionId_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[outputPort](#outputPort)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[packedQuery](#packedQuery)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[packingType](#packingType)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[pickExpeditionStatus](#pickExpeditionStatus)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[RequestedShipDate](#RequestedShipDate)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[requireAllReserved](#requireAllReserved)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[shipmentId](#shipmentId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[shipmentType](#shipmentType)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[shippingDateTime](#shippingDateTime)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[status](#status)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[TransportationPayer_RU](#TransportationPayer_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[TransportationPayerType_RU](#TransportationPayerType_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[TransportationType_RU](#TransportationType_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[TransportInvoiceType_RU](#TransportInvoiceType_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[VehicleModel_RU](#VehicleModel_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[VehiclePlateNum_RU](#VehiclePlateNum_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[WaybillNum_RU](#WaybillNum_RU)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[DataAreaId](#DataAreaId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_Carrier_CustTable_RURelationshipId](#Relationship_Carrier_CustTable_RURelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_Carrier_VendTable_RURelationshipId](#Relationship_Carrier_VendTable_RURelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_Driver_CustTableRelationshipId](#Relationship_Driver_CustTableRelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_Driver_VendTable_RURelationshipId](#Relationship_Driver_VendTable_RURelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_InventLocationRelationshipId](#Relationship_InventLocationRelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_InventSiteRelationshipId](#Relationship_InventSiteRelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_OffSessionId_RURelationshipId](#Relationship_OffSessionId_RURelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_Payer_CustTable_RURelationshipId](#Relationship_Payer_CustTable_RURelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_TransportationTypeTable_RURelationshipId](#Relationship_TransportationTypeTable_RURelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_VehicleModelTable_WRelationshipId](#Relationship_VehicleModelTable_WRelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_WMSLocationRelationshipId](#Relationship_WMSLocationRelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_WMSOrderTransRelationshipId](#Relationship_WMSOrderTransRelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WMSShipment.md" target="_blank">WorksheetHeader/WMSShipment</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WMSShipment/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#autoAddStop name="autoAddStop">autoAddStop</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the autoAddStop attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CargoDescription_RU name="CargoDescription_RU">CargoDescription_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CargoDescription_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CargoPacking_RU name="CargoPacking_RU">CargoPacking_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CargoPacking_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierCode_RU name="CarrierCode_RU">CarrierCode_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierType_RU name="CarrierType_RU">CarrierType_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeliveryDate_RU name="DeliveryDate_RU">DeliveryDate_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Driver_RU name="Driver_RU">Driver_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Driver_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DriverContact_RU name="DriverContact_RU">DriverContact_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DriverContact_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DriverName_RU name="DriverName_RU">DriverName_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DriverName_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DrivingLicenseNum_RU name="DrivingLicenseNum_RU">DrivingLicenseNum_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DrivingLicenseNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#inventLocationId name="inventLocationId">inventLocationId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteId name="InventSiteId">InventSiteId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

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

### <a href=#isShipmentMultiSiteActivated name="isShipmentMultiSiteActivated">isShipmentMultiSiteActivated</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isShipmentMultiSiteActivated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LicenseCardNum_RU name="LicenseCardNum_RU">LicenseCardNum_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicenseCardNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicenseCardRegNum_RU name="LicenseCardRegNum_RU">LicenseCardRegNum_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicenseCardRegNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicenseCardSeries_RU name="LicenseCardSeries_RU">LicenseCardSeries_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicenseCardSeries_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicenseCardType_RU name="LicenseCardType_RU">LicenseCardType_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicenseCardType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#name name="name">name</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffSessionId_RU name="OffSessionId_RU">OffSessionId_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffSessionId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#outputPort name="outputPort">outputPort</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the outputPort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#packedQuery name="packedQuery">packedQuery</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the packedQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#packingType name="packingType">packingType</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the packingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#pickExpeditionStatus name="pickExpeditionStatus">pickExpeditionStatus</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickExpeditionStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RequestedShipDate name="RequestedShipDate">RequestedShipDate</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShipDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#requireAllReserved name="requireAllReserved">requireAllReserved</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the requireAllReserved attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#shipmentId name="shipmentId">shipmentId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the shipmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#shipmentType name="shipmentType">shipmentType</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the shipmentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#shippingDateTime name="shippingDateTime">shippingDateTime</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the shippingDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#status name="status">status</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#TransportationPayer_RU name="TransportationPayer_RU">TransportationPayer_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationPayer_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationPayerType_RU name="TransportationPayerType_RU">TransportationPayerType_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationPayerType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransportationType_RU name="TransportationType_RU">TransportationType_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationType_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportInvoiceType_RU name="TransportInvoiceType_RU">TransportInvoiceType_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportInvoiceType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VehicleModel_RU name="VehicleModel_RU">VehicleModel_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleModel_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VehiclePlateNum_RU name="VehiclePlateNum_RU">VehiclePlateNum_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehiclePlateNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WaybillNum_RU name="WaybillNum_RU">WaybillNum_RU</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaybillNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

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

### <a href=#Relationship_Carrier_CustTable_RURelationshipId name="Relationship_Carrier_CustTable_RURelationshipId">Relationship_Carrier_CustTable_RURelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Carrier_CustTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Carrier_VendTable_RURelationshipId name="Relationship_Carrier_VendTable_RURelationshipId">Relationship_Carrier_VendTable_RURelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Carrier_VendTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Driver_CustTableRelationshipId name="Relationship_Driver_CustTableRelationshipId">Relationship_Driver_CustTableRelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Driver_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Main/ContactPerson.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/ContactPerson.cdm.json/ContactPerson</a></td><td><a href="../../SalesAndMarketing/Main/ContactPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Driver_VendTable_RURelationshipId name="Relationship_Driver_VendTable_RURelationshipId">Relationship_Driver_VendTable_RURelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Driver_VendTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Main/ContactPerson.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/ContactPerson.cdm.json/ContactPerson</a></td><td><a href="../../SalesAndMarketing/Main/ContactPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLocationRelationshipId name="Relationship_InventLocationRelationshipId">Relationship_InventLocationRelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSiteRelationshipId name="Relationship_InventSiteRelationshipId">Relationship_InventSiteRelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventSite.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventSite.cdm.json/InventSite</a></td><td><a href="../Group/InventSite.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffSessionId_RURelationshipId name="Relationship_OffSessionId_RURelationshipId">Relationship_OffSessionId_RURelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffSessionId_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/APARShared/Transaction/OfficialsTrans_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Transaction/OfficialsTrans_RU.cdm.json/OfficialsTrans_RU</a></td><td><a href="../../../Finance/APARShared/Transaction/OfficialsTrans_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Payer_CustTable_RURelationshipId name="Relationship_Payer_CustTable_RURelationshipId">Relationship_Payer_CustTable_RURelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Payer_CustTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportationTypeTable_RURelationshipId name="Relationship_TransportationTypeTable_RURelationshipId">Relationship_TransportationTypeTable_RURelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportationTypeTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/TransportationTypeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/TransportationTypeTable_RU.cdm.json/TransportationTypeTable_RU</a></td><td><a href="../../../Finance/AccountsReceivable/Main/TransportationTypeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VehicleModelTable_WRelationshipId name="Relationship_VehicleModelTable_WRelationshipId">Relationship_VehicleModelTable_WRelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VehicleModelTable_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/VehicleModelTable_W.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/VehicleModelTable_W.cdm.json/VehicleModelTable_W</a></td><td><a href="../../../Finance/AccountsReceivable/Main/VehicleModelTable_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSLocationRelationshipId name="Relationship_WMSLocationRelationshipId">Relationship_WMSLocationRelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WMSLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSOrderTransRelationshipId name="Relationship_WMSOrderTransRelationshipId">Relationship_WMSOrderTransRelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSOrderTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/WMSOrderTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/WMSOrderTrans.cdm.json/WMSOrderTrans</a></td><td><a href="../Transaction/WMSOrderTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/WMSShipment (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
