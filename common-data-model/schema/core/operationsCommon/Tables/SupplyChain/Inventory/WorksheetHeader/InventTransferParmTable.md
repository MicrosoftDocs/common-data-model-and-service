---
title: InventTransferParmTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# InventTransferParmTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferParmTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTransferParmTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[AutoReceiveQty](#AutoReceiveQty)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[CargoDescription_RU](#CargoDescription_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[CargoPacking_RU](#CargoPacking_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[CarrierCode_RU](#CarrierCode_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[CarrierType_RU](#CarrierType_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[CurrencyCode_RU](#CurrencyCode_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[DeliveryDate_RU](#DeliveryDate_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[DriverContact_RU](#DriverContact_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[DriverName_RU](#DriverName_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[DrivingLicenseNum_RU](#DrivingLicenseNum_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[EditLines](#EditLines)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[ExecutedDateTime](#ExecutedDateTime)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[ExplodeLines](#ExplodeLines)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[InventDimFixedPickList](#InventDimFixedPickList)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[InventDimFixedReceiveList](#InventDimFixedReceiveList)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[InventDimFixedShipList](#InventDimFixedShipList)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[JobStatus](#JobStatus)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[LadingPostalAddress_RU](#LadingPostalAddress_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[LicenseCardNum_RU](#LicenseCardNum_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[LicenseCardRegNum_RU](#LicenseCardRegNum_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[LicenseCardSeries_RU](#LicenseCardSeries_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[LicenseCardType_RU](#LicenseCardType_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[LineNum](#LineNum)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Num_LT](#Num_LT)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[OffSessionId_RU](#OffSessionId_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[ParmId](#ParmId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PartyAccountNum_RU](#PartyAccountNum_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PartyAgreementHeaderExt_RU](#PartyAgreementHeaderExt_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PickUpdateQty](#PickUpdateQty)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PriceGroupId_RU](#PriceGroupId_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PrintBillOfLading_RU](#PrintBillOfLading_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PrintInvoice_RU](#PrintInvoice_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PrintProductLabel](#PrintProductLabel)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PrintShelfLabel](#PrintShelfLabel)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PrintTransferPickingList](#PrintTransferPickingList)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PrintTransferReceipt](#PrintTransferReceipt)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PrintTransferShipment](#PrintTransferShipment)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PrintTransportInvoice_RU](#PrintTransportInvoice_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[ReceiveUpdateQty](#ReceiveUpdateQty)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Reservation](#Reservation)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[SetupPrintPickList](#SetupPrintPickList)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[SetupPrintReceiveList](#SetupPrintReceiveList)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[SetupPrintShipList](#SetupPrintShipList)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[ShipUpdateQty](#ShipUpdateQty)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[TrackingId](#TrackingId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[TransDate](#TransDate)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[TransferId](#TransferId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[TransferType_RU](#TransferType_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[TransportationPayer_RU](#TransportationPayer_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[TransportationPayerType_RU](#TransportationPayerType_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[TransportationType_RU](#TransportationType_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[TransportInvoiceType_RU](#TransportInvoiceType_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[UnladingPostalAddress_RU](#UnladingPostalAddress_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[UpdatedByWorker](#UpdatedByWorker)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[UpdateType](#UpdateType)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[UsePrintManagementDestination](#UsePrintManagementDestination)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[VehicleModel_RU](#VehicleModel_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[VehiclePlateNum_RU](#VehiclePlateNum_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[VoucherShipmentId](#VoucherShipmentId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[WaybillNum_RU](#WaybillNum_RU)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[PackedExtensions](#PackedExtensions)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[CFDIEnabled_MX](#CFDIEnabled_MX)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[DataAreaId](#DataAreaId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_Carrier_CustTable_RURelationshipId](#Relationship_Carrier_CustTable_RURelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_Carrier_VendTable_RURelationshipId](#Relationship_Carrier_VendTable_RURelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_InventTransferJourRelationshipId](#Relationship_InventTransferJourRelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_InventTransferParmUpdateRelationshipId](#Relationship_InventTransferParmUpdateRelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_InventTransferTableRelationshipId](#Relationship_InventTransferTableRelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_LadingPostalAddress_RURelationshipId](#Relationship_LadingPostalAddress_RURelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_OfficialsTransRelationshipId](#Relationship_OfficialsTransRelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_PartyAgreementHeaderExt_RURelationshipId](#Relationship_PartyAgreementHeaderExt_RURelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_PartyVendTable_RURelationshipId](#Relationship_PartyVendTable_RURelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_Payer_CustTable_RURelationshipId](#Relationship_Payer_CustTable_RURelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_PriceDiscGroupRelationshipId](#Relationship_PriceDiscGroupRelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_TransportationTypeTable_RURelationshipId](#Relationship_TransportationTypeTable_RURelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_UnladingPostalAddress_RURelationshipId](#Relationship_UnladingPostalAddress_RURelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_VehicleModelTable_WRelationshipId](#Relationship_VehicleModelTable_WRelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventTransferParmTable.md" target="_blank">WorksheetHeader/InventTransferParmTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTransferParmTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AutoReceiveQty name="AutoReceiveQty">AutoReceiveQty</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoReceiveQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CargoDescription_RU name="CargoDescription_RU">CargoDescription_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CurrencyCode_RU name="CurrencyCode_RU">CurrencyCode_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDate_RU name="DeliveryDate_RU">DeliveryDate_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DriverContact_RU name="DriverContact_RU">DriverContact_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

### <a href=#EditLines name="EditLines">EditLines</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EditLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExecutedDateTime name="ExecutedDateTime">ExecutedDateTime</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ExplodeLines name="ExplodeLines">ExplodeLines</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExplodeLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimFixedPickList name="InventDimFixedPickList">InventDimFixedPickList</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimFixedPickList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimFixedReceiveList name="InventDimFixedReceiveList">InventDimFixedReceiveList</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimFixedReceiveList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimFixedShipList name="InventDimFixedShipList">InventDimFixedShipList</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimFixedShipList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JobStatus name="JobStatus">JobStatus</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LadingPostalAddress_RU name="LadingPostalAddress_RU">LadingPostalAddress_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LadingPostalAddress_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LicenseCardNum_RU name="LicenseCardNum_RU">LicenseCardNum_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicenseCardType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Num_LT name="Num_LT">Num_LT</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Num_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffSessionId_RU name="OffSessionId_RU">OffSessionId_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffSessionId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParmId name="ParmId">ParmId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParmId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyAccountNum_RU name="PartyAccountNum_RU">PartyAccountNum_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyAccountNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyAgreementHeaderExt_RU name="PartyAgreementHeaderExt_RU">PartyAgreementHeaderExt_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyAgreementHeaderExt_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PickUpdateQty name="PickUpdateQty">PickUpdateQty</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickUpdateQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PriceGroupId_RU name="PriceGroupId_RU">PriceGroupId_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceGroupId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBillOfLading_RU name="PrintBillOfLading_RU">PrintBillOfLading_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBillOfLading_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintInvoice_RU name="PrintInvoice_RU">PrintInvoice_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintInvoice_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintProductLabel name="PrintProductLabel">PrintProductLabel</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintProductLabel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintShelfLabel name="PrintShelfLabel">PrintShelfLabel</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintShelfLabel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintTransferPickingList name="PrintTransferPickingList">PrintTransferPickingList</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTransferPickingList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintTransferReceipt name="PrintTransferReceipt">PrintTransferReceipt</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTransferReceipt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintTransferShipment name="PrintTransferShipment">PrintTransferShipment</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTransferShipment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintTransportInvoice_RU name="PrintTransportInvoice_RU">PrintTransportInvoice_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTransportInvoice_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReceiveUpdateQty name="ReceiveUpdateQty">ReceiveUpdateQty</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiveUpdateQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Reservation name="Reservation">Reservation</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reservation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SetupPrintPickList name="SetupPrintPickList">SetupPrintPickList</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupPrintPickList attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SetupPrintReceiveList name="SetupPrintReceiveList">SetupPrintReceiveList</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupPrintReceiveList attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SetupPrintShipList name="SetupPrintShipList">SetupPrintShipList</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupPrintShipList attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#ShipUpdateQty name="ShipUpdateQty">ShipUpdateQty</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipUpdateQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TrackingId name="TrackingId">TrackingId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TransferId name="TransferId">TransferId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferType_RU name="TransferType_RU">TransferType_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#TransportationPayer_RU name="TransportationPayer_RU">TransportationPayer_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationPayerType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransportationType_RU name="TransportationType_RU">TransportationType_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportInvoiceType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UnladingPostalAddress_RU name="UnladingPostalAddress_RU">UnladingPostalAddress_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnladingPostalAddress_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UpdatedByWorker name="UpdatedByWorker">UpdatedByWorker</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdatedByWorker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UpdateType name="UpdateType">UpdateType</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UsePrintManagementDestination name="UsePrintManagementDestination">UsePrintManagementDestination</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsePrintManagementDestination attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VehicleModel_RU name="VehicleModel_RU">VehicleModel_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

### <a href=#VoucherShipmentId name="VoucherShipmentId">VoucherShipmentId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherShipmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WaybillNum_RU name="WaybillNum_RU">WaybillNum_RU</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

### <a href=#PackedExtensions name="PackedExtensions">PackedExtensions</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedExtensions attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIEnabled_MX name="CFDIEnabled_MX">CFDIEnabled_MX</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIEnabled_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransferJourRelationshipId name="Relationship_InventTransferJourRelationshipId">Relationship_InventTransferJourRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransferJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/InventTransferJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransferJour.cdm.json/InventTransferJour</a></td><td><a href="../Transaction/InventTransferJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransferParmUpdateRelationshipId name="Relationship_InventTransferParmUpdateRelationshipId">Relationship_InventTransferParmUpdateRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransferParmUpdateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/InventTransferParmUpdate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransferParmUpdate.cdm.json/InventTransferParmUpdate</a></td><td><a href="../Transaction/InventTransferParmUpdate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransferTableRelationshipId name="Relationship_InventTransferTableRelationshipId">Relationship_InventTransferTableRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransferTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventTransferTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferTable.cdm.json/InventTransferTable</a></td><td><a href="InventTransferTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LadingPostalAddress_RURelationshipId name="Relationship_LadingPostalAddress_RURelationshipId">Relationship_LadingPostalAddress_RURelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LadingPostalAddress_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OfficialsTransRelationshipId name="Relationship_OfficialsTransRelationshipId">Relationship_OfficialsTransRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OfficialsTransRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PartyAgreementHeaderExt_RURelationshipId name="Relationship_PartyAgreementHeaderExt_RURelationshipId">Relationship_PartyAgreementHeaderExt_RURelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PartyAgreementHeaderExt_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/APARShared/TransactionHeader/AgreementHeaderExt_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/TransactionHeader/AgreementHeaderExt_RU.cdm.json/AgreementHeaderExt_RU</a></td><td><a href="../../../Finance/APARShared/TransactionHeader/AgreementHeaderExt_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PartyVendTable_RURelationshipId name="Relationship_PartyVendTable_RURelationshipId">Relationship_PartyVendTable_RURelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PartyVendTable_RURelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Payer_CustTable_RURelationshipId name="Relationship_Payer_CustTable_RURelationshipId">Relationship_Payer_CustTable_RURelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

### <a href=#Relationship_PriceDiscGroupRelationshipId name="Relationship_PriceDiscGroupRelationshipId">Relationship_PriceDiscGroupRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PriceDiscGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/PriceDiscGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.cdm.json/PriceDiscGroup</a></td><td><a href="../../SalesAndMarketing/Group/PriceDiscGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportationTypeTable_RURelationshipId name="Relationship_TransportationTypeTable_RURelationshipId">Relationship_TransportationTypeTable_RURelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

### <a href=#Relationship_UnladingPostalAddress_RURelationshipId name="Relationship_UnladingPostalAddress_RURelationshipId">Relationship_UnladingPostalAddress_RURelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnladingPostalAddress_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VehicleModelTable_WRelationshipId name="Relationship_VehicleModelTable_WRelationshipId">Relationship_VehicleModelTable_WRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTable (this entity)  

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
