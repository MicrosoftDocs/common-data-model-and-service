---
title: InventTransferJour in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Transfer order history in Transaction(InventTransferJour)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransferJour.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTransferJour/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transfer order history</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[AutoReceiveQty](#AutoReceiveQty)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[BillOfLadingId_RU](#BillOfLadingId_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[CargoDescription_RU](#CargoDescription_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[CargoPacking_RU](#CargoPacking_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[CarrierCode_RU](#CarrierCode_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[CarrierType_RU](#CarrierType_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[CurrencyCode_RU](#CurrencyCode_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[DeliveryDate_RU](#DeliveryDate_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[DlvModeId](#DlvModeId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[DlvTermId](#DlvTermId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[DriverContact_RU](#DriverContact_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[DriverName_RU](#DriverName_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[DrivingLicenseNum_RU](#DrivingLicenseNum_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[FreightSlipType](#FreightSlipType)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[FreightZoneId](#FreightZoneId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[FromAddressName](#FromAddressName)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[FromContactPerson](#FromContactPerson)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[FromPostalAddress](#FromPostalAddress)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[IntrastatDispatch](#IntrastatDispatch)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[InventLocationIdFrom](#InventLocationIdFrom)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[InventLocationIdTo](#InventLocationIdTo)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[InventLocationIdTransit](#InventLocationIdTransit)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[LadingPostalAddress_RU](#LadingPostalAddress_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[LicenseCardNum_RU](#LicenseCardNum_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[LicenseCardRegNum_RU](#LicenseCardRegNum_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[LicenseCardSeries_RU](#LicenseCardSeries_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[LicenseCardType_RU](#LicenseCardType_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Num_LT](#Num_LT)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Numbering_W](#Numbering_W)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[OffSessionId_RU](#OffSessionId_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[PartyAccountNum_RU](#PartyAccountNum_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[PartyAgreementHeaderExt_RU](#PartyAgreementHeaderExt_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[PriceGroupId_RU](#PriceGroupId_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[ReasonTableRef_BR](#ReasonTableRef_BR)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Return_RU](#Return_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Storno_RU](#Storno_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[ToAddressName](#ToAddressName)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[ToContactPerson](#ToContactPerson)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[ToPostalAddress](#ToPostalAddress)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[TrackingId](#TrackingId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[TransDate](#TransDate)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[TransferId](#TransferId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[TransferType_RU](#TransferType_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[TransportationType_RU](#TransportationType_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[TransportInvoiceType_RU](#TransportInvoiceType_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[UnladingPostalAddress_RU](#UnladingPostalAddress_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[UpdatedByWorker](#UpdatedByWorker)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[UpdateType](#UpdateType)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[VehicleModel_RU](#VehicleModel_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[VehiclePlateNum_RU](#VehiclePlateNum_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[VoucherId](#VoucherId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[WaybillNum_RU](#WaybillNum_RU)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[PackedExtensions](#PackedExtensions)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[DataAreaId](#DataAreaId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_DlvModeRelationshipId](#Relationship_DlvModeRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_DlvTermRelationshipId](#Relationship_DlvTermRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_FromInventLocationRelationshipId](#Relationship_FromInventLocationRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_FromLogisticsPostalAddressRelationshipId](#Relationship_FromLogisticsPostalAddressRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_InventTransferTableRelationshipId](#Relationship_InventTransferTableRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_LadingPostalAddress_RURelationshipId](#Relationship_LadingPostalAddress_RURelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_OfficialsTransRelationshipId](#Relationship_OfficialsTransRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_PartyAgreementHeaderExt_RURelationshipId](#Relationship_PartyAgreementHeaderExt_RURelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_PartyVendTable_RURelationshipId](#Relationship_PartyVendTable_RURelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_PriceDiscGroupRelationshipId](#Relationship_PriceDiscGroupRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_ReasonTableRefRelationshipId](#Relationship_ReasonTableRefRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_ToInventLocationRelationshipId](#Relationship_ToInventLocationRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_ToLogisticsPostalAddressRelationshipId](#Relationship_ToLogisticsPostalAddressRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_TransitInventLocationRelationshipId](#Relationship_TransitInventLocationRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_TransportationTypeTable_RURelationshipId](#Relationship_TransportationTypeTable_RURelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_UnladingPostalAddress_RURelationshipId](#Relationship_UnladingPostalAddress_RURelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_VehicleModelTable_WRelationshipId](#Relationship_VehicleModelTable_WRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_WMSBillOfLadingRelationshipId](#Relationship_WMSBillOfLadingRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventTransferJour.md" target="_blank">Transaction/InventTransferJour</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTransferJour/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AutoReceiveQty name="AutoReceiveQty">AutoReceiveQty</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoReceiveQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BillOfLadingId_RU name="BillOfLadingId_RU">BillOfLadingId_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfLadingId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CargoDescription_RU name="CargoDescription_RU">CargoDescription_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CargoDescription_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CargoPacking_RU name="CargoPacking_RU">CargoPacking_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CargoPacking_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierCode_RU name="CarrierCode_RU">CarrierCode_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierType_RU name="CarrierType_RU">CarrierType_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CurrencyCode_RU name="CurrencyCode_RU">CurrencyCode_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDate_RU name="DeliveryDate_RU">DeliveryDate_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DlvModeId name="DlvModeId">DlvModeId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvModeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DlvTermId name="DlvTermId">DlvTermId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvTermId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DriverContact_RU name="DriverContact_RU">DriverContact_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DriverContact_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DriverName_RU name="DriverName_RU">DriverName_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DriverName_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DrivingLicenseNum_RU name="DrivingLicenseNum_RU">DrivingLicenseNum_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DrivingLicenseNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightSlipType name="FreightSlipType">FreightSlipType</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightSlipType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FreightZoneId name="FreightZoneId">FreightZoneId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightZoneId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromAddressName name="FromAddressName">FromAddressName</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromContactPerson name="FromContactPerson">FromContactPerson</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromContactPerson attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FromPostalAddress name="FromPostalAddress">FromPostalAddress</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IntrastatDispatch name="IntrastatDispatch">IntrastatDispatch</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatDispatch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationIdFrom name="InventLocationIdFrom">InventLocationIdFrom</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationIdTo name="InventLocationIdTo">InventLocationIdTo</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationIdTransit name="InventLocationIdTransit">InventLocationIdTransit</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdTransit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LadingPostalAddress_RU name="LadingPostalAddress_RU">LadingPostalAddress_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LadingPostalAddress_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LicenseCardNum_RU name="LicenseCardNum_RU">LicenseCardNum_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicenseCardNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicenseCardRegNum_RU name="LicenseCardRegNum_RU">LicenseCardRegNum_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicenseCardRegNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicenseCardSeries_RU name="LicenseCardSeries_RU">LicenseCardSeries_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicenseCardSeries_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicenseCardType_RU name="LicenseCardType_RU">LicenseCardType_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicenseCardType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Num_LT name="Num_LT">Num_LT</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packing slip number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Num_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packing slip number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Numbering_W name="Numbering_W">Numbering_W</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packing slip numbering code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Numbering_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packing slip numbering code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffSessionId_RU name="OffSessionId_RU">OffSessionId_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffSessionId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyAccountNum_RU name="PartyAccountNum_RU">PartyAccountNum_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyAccountNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyAgreementHeaderExt_RU name="PartyAgreementHeaderExt_RU">PartyAgreementHeaderExt_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyAgreementHeaderExt_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PriceGroupId_RU name="PriceGroupId_RU">PriceGroupId_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceGroupId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonTableRef_BR name="ReasonTableRef_BR">ReasonTableRef_BR</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonTableRef_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Return_RU name="Return_RU">Return_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goods return</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Return_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Goods return</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Storno_RU name="Storno_RU">Storno_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit correction</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Storno_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit correction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ToAddressName name="ToAddressName">ToAddressName</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToContactPerson name="ToContactPerson">ToContactPerson</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToContactPerson attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ToPostalAddress name="ToPostalAddress">ToPostalAddress</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TrackingId name="TrackingId">TrackingId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#TransferId name="TransferId">TransferId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferType_RU name="TransferType_RU">TransferType_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransportationType_RU name="TransportationType_RU">TransportationType_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationType_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportInvoiceType_RU name="TransportInvoiceType_RU">TransportInvoiceType_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportInvoiceType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UnladingPostalAddress_RU name="UnladingPostalAddress_RU">UnladingPostalAddress_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnladingPostalAddress_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UpdatedByWorker name="UpdatedByWorker">UpdatedByWorker</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdatedByWorker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UpdateType name="UpdateType">UpdateType</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VehicleModel_RU name="VehicleModel_RU">VehicleModel_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleModel_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VehiclePlateNum_RU name="VehiclePlateNum_RU">VehiclePlateNum_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehiclePlateNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherId name="VoucherId">VoucherId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WaybillNum_RU name="WaybillNum_RU">WaybillNum_RU</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaybillNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackedExtensions name="PackedExtensions">PackedExtensions</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedExtensions attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/InventTransferJour (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

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

### <a href=#Relationship_DlvModeRelationshipId name="Relationship_DlvModeRelationshipId">Relationship_DlvModeRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DlvModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/DlvMode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/DlvMode.cdm.json/DlvMode</a></td><td><a href="../../SalesAndMarketing/Group/DlvMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DlvTermRelationshipId name="Relationship_DlvTermRelationshipId">Relationship_DlvTermRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DlvTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/DlvTerm.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/DlvTerm.cdm.json/DlvTerm</a></td><td><a href="../../SalesAndMarketing/Group/DlvTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FromInventLocationRelationshipId name="Relationship_FromInventLocationRelationshipId">Relationship_FromInventLocationRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FromInventLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FromLogisticsPostalAddressRelationshipId name="Relationship_FromLogisticsPostalAddressRelationshipId">Relationship_FromLogisticsPostalAddressRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FromLogisticsPostalAddressRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventTransferTableRelationshipId name="Relationship_InventTransferTableRelationshipId">Relationship_InventTransferTableRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventTransferTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferTable.cdm.json/InventTransferTable</a></td><td><a href="../WorksheetHeader/InventTransferTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LadingPostalAddress_RURelationshipId name="Relationship_LadingPostalAddress_RURelationshipId">Relationship_LadingPostalAddress_RURelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

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

First included in: Transaction/InventTransferJour (this entity)  

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

First included in: Transaction/InventTransferJour (this entity)  

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

First included in: Transaction/InventTransferJour (this entity)  

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

### <a href=#Relationship_PriceDiscGroupRelationshipId name="Relationship_PriceDiscGroupRelationshipId">Relationship_PriceDiscGroupRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

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

### <a href=#Relationship_ReasonTableRefRelationshipId name="Relationship_ReasonTableRefRelationshipId">Relationship_ReasonTableRefRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReasonTableRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Transaction/ReasonTableRef.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Transaction/ReasonTableRef.cdm.json/ReasonTableRef</a></td><td><a href="../../../Finance/Ledger/Transaction/ReasonTableRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ToInventLocationRelationshipId name="Relationship_ToInventLocationRelationshipId">Relationship_ToInventLocationRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ToInventLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ToLogisticsPostalAddressRelationshipId name="Relationship_ToLogisticsPostalAddressRelationshipId">Relationship_ToLogisticsPostalAddressRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ToLogisticsPostalAddressRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TransitInventLocationRelationshipId name="Relationship_TransitInventLocationRelationshipId">Relationship_TransitInventLocationRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransitInventLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TransportationTypeTable_RURelationshipId name="Relationship_TransportationTypeTable_RURelationshipId">Relationship_TransportationTypeTable_RURelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

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

First included in: Transaction/InventTransferJour (this entity)  

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

First included in: Transaction/InventTransferJour (this entity)  

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

### <a href=#Relationship_WMSBillOfLadingRelationshipId name="Relationship_WMSBillOfLadingRelationshipId">Relationship_WMSBillOfLadingRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSBillOfLadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/WMSBillOfLading.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/TransactionHeader/WMSBillOfLading.cdm.json/WMSBillOfLading</a></td><td><a href="../TransactionHeader/WMSBillOfLading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/InventTransferJour (this entity)  

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
