---
title: TMSTransportationDiscountEntity in Transportation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Transportation discounts in Transportation

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSTransportationDiscountEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation discounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ShippingCarrierIdCriterion](#ShippingCarrierIdCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[ShippingCarrierServiceIdCriterion](#ShippingCarrierServiceIdCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DiscountCurrencyCode](#DiscountCurrencyCode)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[OrderCustomerAccountNumberCriterion](#OrderCustomerAccountNumberCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[InvoiceCustomerAccountNumberCriterion](#InvoiceCustomerAccountNumberCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DestinationAddressCountryRegionId](#DestinationAddressCountryRegionId)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DestinationToAddressZipCodeCriterion](#DestinationToAddressZipCodeCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DestinationFromAddressZipCodeCriterion](#DestinationFromAddressZipCodeCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DestinationStateIdCriterion](#DestinationStateIdCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[ProductMovementDirectionRule](#ProductMovementDirectionRule)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DiscountCalculationType](#DiscountCalculationType)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DiscountType](#DiscountType)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[EffectiveStartDateTimeCriterion](#EffectiveStartDateTimeCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[EffectiveEndDateTimeCriterion](#EffectiveEndDateTimeCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DeliveryTermsCodeCriterion](#DeliveryTermsCodeCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[ShippingWarehouseIdCriterion](#ShippingWarehouseIdCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[ShippingSiteIdCriterion](#ShippingSiteIdCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[DiscountPercentage](#DiscountPercentage)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[OrderVendorAccountNumberCriterion](#OrderVendorAccountNumberCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[InvoiceVendorAccountNumberCriterion](#InvoiceVendorAccountNumberCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[MaximumFreightWeightCriterion](#MaximumFreightWeightCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[MinimumFreightWeightCriterion](#MinimumFreightWeightCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[TransportationZoneIdCriterion](#TransportationZoneIdCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[TransportationZoneMasterCodeCriterion](#TransportationZoneMasterCodeCriterion)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[BackingTable_TMSDiscountTableRelationshipId](#BackingTable_TMSDiscountTableRelationshipId)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationDiscountEntity.md" target="_blank">Transportation/TMSTransportationDiscountEntity</a>|

### <a href=#ShippingCarrierIdCriterion name="ShippingCarrierIdCriterion">ShippingCarrierIdCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceIdCriterion name="ShippingCarrierServiceIdCriterion">ShippingCarrierServiceIdCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountCurrencyCode name="DiscountCurrencyCode">DiscountCurrencyCode</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderCustomerAccountNumberCriterion name="OrderCustomerAccountNumberCriterion">OrderCustomerAccountNumberCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

### <a href=#DestinationAddressCountryRegionId name="DestinationAddressCountryRegionId">DestinationAddressCountryRegionId</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationToAddressZipCodeCriterion name="DestinationToAddressZipCodeCriterion">DestinationToAddressZipCodeCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

### <a href=#DestinationStateIdCriterion name="DestinationStateIdCriterion">DestinationStateIdCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationStateIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductMovementDirectionRule name="ProductMovementDirectionRule">ProductMovementDirectionRule</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

### <a href=#DiscountCalculationType name="DiscountCalculationType">DiscountCalculationType</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCalculationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountType name="DiscountType">DiscountType</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveStartDateTimeCriterion name="EffectiveStartDateTimeCriterion">EffectiveStartDateTimeCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCodeCriterion name="DeliveryTermsCodeCriterion">DeliveryTermsCodeCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

### <a href=#ShippingWarehouseIdCriterion name="ShippingWarehouseIdCriterion">ShippingWarehouseIdCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

### <a href=#DiscountPercentage name="DiscountPercentage">DiscountPercentage</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderVendorAccountNumberCriterion name="OrderVendorAccountNumberCriterion">OrderVendorAccountNumberCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

### <a href=#MaximumFreightWeightCriterion name="MaximumFreightWeightCriterion">MaximumFreightWeightCriterion</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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

### <a href=#BackingTable_TMSDiscountTableRelationshipId name="BackingTable_TMSDiscountTableRelationshipId">BackingTable_TMSDiscountTableRelationshipId</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSDiscountTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Main/TMSDiscountTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSDiscountTable.cdm.json/TMSDiscountTable</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Main/TMSDiscountTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationDiscountEntity (this entity)  

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
