---
title: TMSTransportationRouteGuideEntity in Transportation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Transportation route guides in Transportation(TMSTransportationRouteGuideEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSTransportationRouteGuideEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation route guides</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[OriginAddressCountryRegionIdCriterion](#OriginAddressCountryRegionIdCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[OriginTransportationHubIdCriterion](#OriginTransportationHubIdCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[OriginTransportationZoneMasterCodeCriterion](#OriginTransportationZoneMasterCodeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[IsRouteGuideActive](#IsRouteGuideActive)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[ShippingCarrierId](#ShippingCarrierId)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[ShippingCarrierServiceGroupId](#ShippingCarrierServiceGroupId)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[ShippingCarrierServiceId](#ShippingCarrierServiceId)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[MaximumContainerAmountCriterion](#MaximumContainerAmountCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[MinimumContainerAmountCriterion](#MinimumContainerAmountCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[OrderCustomerAccountNumberCriterion](#OrderCustomerAccountNumberCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[InvoiceCustomerAccountNumberCriterion](#InvoiceCustomerAccountNumberCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[DestinationAddressCountryRegionIdCriterion](#DestinationAddressCountryRegionIdCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[DestinationTransportationHubIdCriterion](#DestinationTransportationHubIdCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[DestinationToAddressZipCodeCriterion](#DestinationToAddressZipCodeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[DestinationFromAddressZipCodeCriterion](#DestinationFromAddressZipCodeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[DestinationTransportationZoneIdCriterion](#DestinationTransportationZoneIdCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[DestinationTransportationZoneMasterCodeCriterion](#DestinationTransportationZoneMasterCodeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[ProductMovementDirectionRule](#ProductMovementDirectionRule)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[EffectiveStartDateTimeCriterion](#EffectiveStartDateTimeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[EffectiveEndDateTimeCriterion](#EffectiveEndDateTimeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[TransportationEquipmentCodeCriterion](#TransportationEquipmentCodeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[ResultTransportationEquipmentCode](#ResultTransportationEquipmentCode)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[ShippingWarehouseIdCriterion](#ShippingWarehouseIdCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[ShippingSiteIdCriterion](#ShippingSiteIdCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[TransportationModeCode](#TransportationModeCode)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[GuideName](#GuideName)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[OriginAddressZipCodeCriterion](#OriginAddressZipCodeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[OriginTransportationZoneIdCriterion](#OriginTransportationZoneIdCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[IsResidentialAddressCriterion](#IsResidentialAddressCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[TransportationRoutePlanId](#TransportationRoutePlanId)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[GuideId](#GuideId)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[OrderVendorAccountNumberCriterion](#OrderVendorAccountNumberCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[InvoiceVendorAccountNumberCriterion](#InvoiceVendorAccountNumberCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[MaximumLoadVolumeCriterion](#MaximumLoadVolumeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[MinimumLoadVolumeCriterion](#MinimumLoadVolumeCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[MaximumWeightCriterion](#MaximumWeightCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[MinimumWeightCriterion](#MinimumWeightCriterion)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[BackingTable_TMSRouteGuideRelationshipId](#BackingTable_TMSRouteGuideRelationshipId)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationRouteGuideEntity.md" target="_blank">Transportation/TMSTransportationRouteGuideEntity</a>|

### <a href=#OriginAddressCountryRegionIdCriterion name="OriginAddressCountryRegionIdCriterion">OriginAddressCountryRegionIdCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginAddressCountryRegionIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginTransportationHubIdCriterion name="OriginTransportationHubIdCriterion">OriginTransportationHubIdCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginTransportationHubIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginTransportationZoneMasterCodeCriterion name="OriginTransportationZoneMasterCodeCriterion">OriginTransportationZoneMasterCodeCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginTransportationZoneMasterCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRouteGuideActive name="IsRouteGuideActive">IsRouteGuideActive</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRouteGuideActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierId name="ShippingCarrierId">ShippingCarrierId</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

### <a href=#MaximumContainerAmountCriterion name="MaximumContainerAmountCriterion">MaximumContainerAmountCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumContainerAmountCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumContainerAmountCriterion name="MinimumContainerAmountCriterion">MinimumContainerAmountCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumContainerAmountCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderCustomerAccountNumberCriterion name="OrderCustomerAccountNumberCriterion">OrderCustomerAccountNumberCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderCustomerAccountNumberCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCustomerAccountNumberCriterion name="InvoiceCustomerAccountNumberCriterion">InvoiceCustomerAccountNumberCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

### <a href=#DestinationAddressCountryRegionIdCriterion name="DestinationAddressCountryRegionIdCriterion">DestinationAddressCountryRegionIdCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressCountryRegionIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationTransportationHubIdCriterion name="DestinationTransportationHubIdCriterion">DestinationTransportationHubIdCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationTransportationHubIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationToAddressZipCodeCriterion name="DestinationToAddressZipCodeCriterion">DestinationToAddressZipCodeCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationToAddressZipCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationFromAddressZipCodeCriterion name="DestinationFromAddressZipCodeCriterion">DestinationFromAddressZipCodeCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationFromAddressZipCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationTransportationZoneIdCriterion name="DestinationTransportationZoneIdCriterion">DestinationTransportationZoneIdCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationTransportationZoneIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationTransportationZoneMasterCodeCriterion name="DestinationTransportationZoneMasterCodeCriterion">DestinationTransportationZoneMasterCodeCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationTransportationZoneMasterCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductMovementDirectionRule name="ProductMovementDirectionRule">ProductMovementDirectionRule</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductMovementDirectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveStartDateTimeCriterion name="EffectiveStartDateTimeCriterion">EffectiveStartDateTimeCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

### <a href=#ResultTransportationEquipmentCode name="ResultTransportationEquipmentCode">ResultTransportationEquipmentCode</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultTransportationEquipmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCode name="DeliveryTermsCode">DeliveryTermsCode</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

### <a href=#ShippingWarehouseIdCriterion name="ShippingWarehouseIdCriterion">ShippingWarehouseIdCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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

### <a href=#TransportationModeCode name="TransportationModeCode">TransportationModeCode</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuideName name="GuideName">GuideName</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuideName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginAddressZipCodeCriterion name="OriginAddressZipCodeCriterion">OriginAddressZipCodeCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginAddressZipCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginTransportationZoneIdCriterion name="OriginTransportationZoneIdCriterion">OriginTransportationZoneIdCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginTransportationZoneIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsResidentialAddressCriterion name="IsResidentialAddressCriterion">IsResidentialAddressCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsResidentialAddressCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationRoutePlanId name="TransportationRoutePlanId">TransportationRoutePlanId</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationRoutePlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuideId name="GuideId">GuideId</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuideId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderVendorAccountNumberCriterion name="OrderVendorAccountNumberCriterion">OrderVendorAccountNumberCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderVendorAccountNumberCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceVendorAccountNumberCriterion name="InvoiceVendorAccountNumberCriterion">InvoiceVendorAccountNumberCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceVendorAccountNumberCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumLoadVolumeCriterion name="MaximumLoadVolumeCriterion">MaximumLoadVolumeCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumLoadVolumeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumLoadVolumeCriterion name="MinimumLoadVolumeCriterion">MinimumLoadVolumeCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumLoadVolumeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWeightCriterion name="MaximumWeightCriterion">MaximumWeightCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWeightCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumWeightCriterion name="MinimumWeightCriterion">MinimumWeightCriterion</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumWeightCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TMSRouteGuideRelationshipId name="BackingTable_TMSRouteGuideRelationshipId">BackingTable_TMSRouteGuideRelationshipId</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSRouteGuideRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSRouteGuide.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSRouteGuide.cdm.json/TMSRouteGuide</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSRouteGuide.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationRouteGuideEntity (this entity)  

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
