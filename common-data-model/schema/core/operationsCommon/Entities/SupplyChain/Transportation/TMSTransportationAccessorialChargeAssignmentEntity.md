---
title: TMSTransportationAccessorialChargeAssignmentEntity in Transportation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Transportation accessorial charge assignments in Transportation(TMSTransportationAccessorialChargeAssignmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSTransportationAccessorialChargeAssignmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation accessorial charge assignments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChargeAssignmentLevel](#ChargeAssignmentLevel)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[WillChargeCalculationIncludeTransportationDiscounts](#WillChargeCalculationIncludeTransportationDiscounts)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[AreChargeAssignmentCriteriaIgnored](#AreChargeAssignmentCriteriaIgnored)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[TransportationBillingGroupId](#TransportationBillingGroupId)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ShippingCarrierAccessorialChargeId](#ShippingCarrierAccessorialChargeId)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ShippingCarrierId](#ShippingCarrierId)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[AddressCountryRegionIdCriterion](#AddressCountryRegionIdCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ChargeCurrencyCode](#ChargeCurrencyCode)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[OrderingCustomerAccountNumberCriterion](#OrderingCustomerAccountNumberCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[InvoiceCustomerAccountNumberCriterion](#InvoiceCustomerAccountNumberCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[EffectiveStartDateTimeCriterion](#EffectiveStartDateTimeCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[EffectiveEndDateTimeCriterion](#EffectiveEndDateTimeCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[TransportationEquipmentCodeCriterion](#TransportationEquipmentCodeCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[FlatChargeAmount](#FlatChargeAmount)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ChargeType](#ChargeType)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[DeliveryTermsCodeCriterion](#DeliveryTermsCodeCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[FuelSurchargeFuelIndexRegionId](#FuelSurchargeFuelIndexRegionId)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[TransportationHubAccessorialChargeId](#TransportationHubAccessorialChargeId)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[TransportationHubId](#TransportationHubId)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ShippingWarehouseIdCriterion](#ShippingWarehouseIdCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ShippingSiteIdCriterion](#ShippingSiteIdCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[MaximumChargeAmount](#MaximumChargeAmount)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ChargeTransportationMileageEngineId](#ChargeTransportationMileageEngineId)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[MinimumChargeAmount](#MinimumChargeAmount)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ChargeAssignmentName](#ChargeAssignmentName)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[FuelSurchargeOffsetDays](#FuelSurchargeOffsetDays)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ChargePercentage](#ChargePercentage)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ToAddressZipCodeCriterion](#ToAddressZipCodeCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[FromAddressZipCodeCriterion](#FromAddressZipCodeCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[IsResidentialShipCriterion](#IsResidentialShipCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[DropOffAddressStateIdCriterion](#DropOffAddressStateIdCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ChargeAccessorialUnit](#ChargeAccessorialUnit)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[ChargeAccessorialUnitDivisor](#ChargeAccessorialUnitDivisor)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[MaximumFreightValueCriterion](#MaximumFreightValueCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[MinimumFreightValueCriterion](#MinimumFreightValueCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[MaximumFreightWeightCriterion](#MaximumFreightWeightCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[MinimumFreightWeightCriterion](#MinimumFreightWeightCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[TransportationZoneIdCriterion](#TransportationZoneIdCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[TransportationZoneMasterCodeCriterion](#TransportationZoneMasterCodeCriterion)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[BackingTable_TMSAccessorialAssignmentRelationshipId](#BackingTable_TMSAccessorialAssignmentRelationshipId)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationAccessorialChargeAssignmentEntity.md" target="_blank">Transportation/TMSTransportationAccessorialChargeAssignmentEntity</a>|

### <a href=#ChargeAssignmentLevel name="ChargeAssignmentLevel">ChargeAssignmentLevel</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeAssignmentLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillChargeCalculationIncludeTransportationDiscounts name="WillChargeCalculationIncludeTransportationDiscounts">WillChargeCalculationIncludeTransportationDiscounts</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillChargeCalculationIncludeTransportationDiscounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreChargeAssignmentCriteriaIgnored name="AreChargeAssignmentCriteriaIgnored">AreChargeAssignmentCriteriaIgnored</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreChargeAssignmentCriteriaIgnored attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationBillingGroupId name="TransportationBillingGroupId">TransportationBillingGroupId</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationBillingGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierAccessorialChargeId name="ShippingCarrierAccessorialChargeId">ShippingCarrierAccessorialChargeId</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierAccessorialChargeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierId name="ShippingCarrierId">ShippingCarrierId</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

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

### <a href=#AddressCountryRegionIdCriterion name="AddressCountryRegionIdCriterion">AddressCountryRegionIdCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCurrencyCode name="ChargeCurrencyCode">ChargeCurrencyCode</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderingCustomerAccountNumberCriterion name="OrderingCustomerAccountNumberCriterion">OrderingCustomerAccountNumberCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingCustomerAccountNumberCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCustomerAccountNumberCriterion name="InvoiceCustomerAccountNumberCriterion">InvoiceCustomerAccountNumberCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCustomerAccountNumberCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveStartDateTimeCriterion name="EffectiveStartDateTimeCriterion">EffectiveStartDateTimeCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveStartDateTimeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveEndDateTimeCriterion name="EffectiveEndDateTimeCriterion">EffectiveEndDateTimeCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveEndDateTimeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationEquipmentCodeCriterion name="TransportationEquipmentCodeCriterion">TransportationEquipmentCodeCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationEquipmentCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlatChargeAmount name="FlatChargeAmount">FlatChargeAmount</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlatChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeType name="ChargeType">ChargeType</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCodeCriterion name="DeliveryTermsCodeCriterion">DeliveryTermsCodeCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FuelSurchargeFuelIndexRegionId name="FuelSurchargeFuelIndexRegionId">FuelSurchargeFuelIndexRegionId</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuelSurchargeFuelIndexRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationHubAccessorialChargeId name="TransportationHubAccessorialChargeId">TransportationHubAccessorialChargeId</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationHubAccessorialChargeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationHubId name="TransportationHubId">TransportationHubId</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationHubId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingWarehouseIdCriterion name="ShippingWarehouseIdCriterion">ShippingWarehouseIdCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingWarehouseIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingSiteIdCriterion name="ShippingSiteIdCriterion">ShippingSiteIdCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingSiteIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumChargeAmount name="MaximumChargeAmount">MaximumChargeAmount</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeTransportationMileageEngineId name="ChargeTransportationMileageEngineId">ChargeTransportationMileageEngineId</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeTransportationMileageEngineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumChargeAmount name="MinimumChargeAmount">MinimumChargeAmount</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeAssignmentName name="ChargeAssignmentName">ChargeAssignmentName</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeAssignmentName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FuelSurchargeOffsetDays name="FuelSurchargeOffsetDays">FuelSurchargeOffsetDays</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuelSurchargeOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargePercentage name="ChargePercentage">ChargePercentage</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToAddressZipCodeCriterion name="ToAddressZipCodeCriterion">ToAddressZipCodeCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToAddressZipCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromAddressZipCodeCriterion name="FromAddressZipCodeCriterion">FromAddressZipCodeCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromAddressZipCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsResidentialShipCriterion name="IsResidentialShipCriterion">IsResidentialShipCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsResidentialShipCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DropOffAddressStateIdCriterion name="DropOffAddressStateIdCriterion">DropOffAddressStateIdCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DropOffAddressStateIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeAccessorialUnit name="ChargeAccessorialUnit">ChargeAccessorialUnit</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeAccessorialUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeAccessorialUnitDivisor name="ChargeAccessorialUnitDivisor">ChargeAccessorialUnitDivisor</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeAccessorialUnitDivisor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumFreightValueCriterion name="MaximumFreightValueCriterion">MaximumFreightValueCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumFreightValueCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumFreightValueCriterion name="MinimumFreightValueCriterion">MinimumFreightValueCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumFreightValueCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumFreightWeightCriterion name="MaximumFreightWeightCriterion">MaximumFreightWeightCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumFreightWeightCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumFreightWeightCriterion name="MinimumFreightWeightCriterion">MinimumFreightWeightCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumFreightWeightCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationZoneIdCriterion name="TransportationZoneIdCriterion">TransportationZoneIdCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationZoneIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationZoneMasterCodeCriterion name="TransportationZoneMasterCodeCriterion">TransportationZoneMasterCodeCriterion</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationZoneMasterCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TMSAccessorialAssignmentRelationshipId name="BackingTable_TMSAccessorialAssignmentRelationshipId">BackingTable_TMSAccessorialAssignmentRelationshipId</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSAccessorialAssignmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Main/TMSAccessorialAssignment.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSAccessorialAssignment.cdm.json/TMSAccessorialAssignment</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Main/TMSAccessorialAssignment.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationAccessorialChargeAssignmentEntity (this entity)  

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
