---
title: TMSFreightInvoiceLineV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# TMSFreightInvoiceLineV2Entity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSFreightInvoiceLineV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DestinationCountryRegionId](#DestinationCountryRegionId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[TransportationBillingGroupId](#TransportationBillingGroupId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[BillOfLadingId](#BillOfLadingId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[BookingNumber](#BookingNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[ShippingCarrierId](#ShippingCarrierId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[ShippingCarrierServiceId](#ShippingCarrierServiceId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[CosigneeName](#CosigneeName)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[DestinationCountryRegionISOCode](#DestinationCountryRegionISOCode)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[LastCycleCountingDateTime](#LastCycleCountingDateTime)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[DescriptionLine2](#DescriptionLine2)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[DescriptionLine1](#DescriptionLine1)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[TransportationDistance](#TransportationDistance)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[ExternalCode](#ExternalCode)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[FreightBillTypeId](#FreightBillTypeId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[IsLineHeaderCharge](#IsLineHeaderCharge)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[WarehouseId](#WarehouseId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[InventorySiteId](#InventorySiteId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[LineStatus](#LineStatus)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[LineNumber](#LineNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[LineType](#LineType)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[LoadId](#LoadId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[NetAmount](#NetAmount)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[ProNumberCode](#ProNumberCode)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[FreightQuantity](#FreightQuantity)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[TMSFreightInvoiceRecId](#TMSFreightInvoiceRecId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[RelatedAccountNumber](#RelatedAccountNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[RelatedOrderNumber](#RelatedOrderNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[TransportationRouteCode](#TransportationRouteCode)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[TrackingNumber](#TrackingNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[ShipmentId](#ShipmentId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[FreightHeldUntilDateTime](#FreightHeldUntilDateTime)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[TrailerNumber](#TrailerNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[UnitPrice](#UnitPrice)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[FreightWeightUnitId](#FreightWeightUnitId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[ShippingCarrierVendorAccountNumber](#ShippingCarrierVendorAccountNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[InvoiceVendorAccountNumber](#InvoiceVendorAccountNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[VesselName](#VesselName)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[VoyageNumber](#VoyageNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[FreightWeight](#FreightWeight)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[Direction](#Direction)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[InternalInvoiceNumber](#InternalInvoiceNumber)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[Relationship_FreightInvoiceHeaderRelationshipId](#Relationship_FreightInvoiceHeaderRelationshipId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[BackingTable_TMSInvoiceLineRelationshipId](#BackingTable_TMSInvoiceLineRelationshipId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSFreightInvoiceLineV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceLineV2Entity</a>|

### <a href=#DestinationCountryRegionId name="DestinationCountryRegionId">DestinationCountryRegionId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationBillingGroupId name="TransportationBillingGroupId">TransportationBillingGroupId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationBillingGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfLadingId name="BillOfLadingId">BillOfLadingId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfLadingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookingNumber name="BookingNumber">BookingNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierId name="ShippingCarrierId">ShippingCarrierId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceId name="ShippingCarrierServiceId">ShippingCarrierServiceId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CosigneeName name="CosigneeName">CosigneeName</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CosigneeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationCountryRegionISOCode name="DestinationCountryRegionISOCode">DestinationCountryRegionISOCode</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastCycleCountingDateTime name="LastCycleCountingDateTime">LastCycleCountingDateTime</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastCycleCountingDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DescriptionLine2 name="DescriptionLine2">DescriptionLine2</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DescriptionLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DescriptionLine1 name="DescriptionLine1">DescriptionLine1</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DescriptionLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDistance name="TransportationDistance">TransportationDistance</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDistance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalCode name="ExternalCode">ExternalCode</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightBillTypeId name="FreightBillTypeId">FreightBillTypeId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightBillTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLineHeaderCharge name="IsLineHeaderCharge">IsLineHeaderCharge</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLineHeaderCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventorySiteId name="InventorySiteId">InventorySiteId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineStatus name="LineStatus">LineStatus</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadId name="LoadId">LoadId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCode name="DeliveryModeCode">DeliveryModeCode</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProNumberCode name="ProNumberCode">ProNumberCode</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProNumberCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightQuantity name="FreightQuantity">FreightQuantity</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TMSFreightInvoiceRecId name="TMSFreightInvoiceRecId">TMSFreightInvoiceRecId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMSFreightInvoiceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelatedAccountNumber name="RelatedAccountNumber">RelatedAccountNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelatedAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelatedOrderNumber name="RelatedOrderNumber">RelatedOrderNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelatedOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationRouteCode name="TransportationRouteCode">TransportationRouteCode</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationRouteCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingNumber name="TrackingNumber">TrackingNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipmentId name="ShipmentId">ShipmentId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightHeldUntilDateTime name="FreightHeldUntilDateTime">FreightHeldUntilDateTime</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightHeldUntilDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrailerNumber name="TrailerNumber">TrailerNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrailerNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightWeightUnitId name="FreightWeightUnitId">FreightWeightUnitId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightWeightUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierVendorAccountNumber name="ShippingCarrierVendorAccountNumber">ShippingCarrierVendorAccountNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceVendorAccountNumber name="InvoiceVendorAccountNumber">InvoiceVendorAccountNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VesselName name="VesselName">VesselName</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VesselName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoyageNumber name="VoyageNumber">VoyageNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoyageNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightWeight name="FreightWeight">FreightWeight</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalInvoiceNumber name="InternalInvoiceNumber">InternalInvoiceNumber</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalInvoiceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FreightInvoiceHeaderRelationshipId name="Relationship_FreightInvoiceHeaderRelationshipId">Relationship_FreightInvoiceHeaderRelationshipId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FreightInvoiceHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TMSInvoiceLineRelationshipId name="BackingTable_TMSInvoiceLineRelationshipId">BackingTable_TMSInvoiceLineRelationshipId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSInvoiceLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/WorksheetLine/TMSInvoiceLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/WorksheetLine/TMSInvoiceLine.cdm.json/TMSInvoiceLine</a></td><td><a href="../../../Tables/SupplyChain/Transportation/WorksheetLine/TMSInvoiceLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSFreightInvoiceLineV2Entity (this entity)  

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
