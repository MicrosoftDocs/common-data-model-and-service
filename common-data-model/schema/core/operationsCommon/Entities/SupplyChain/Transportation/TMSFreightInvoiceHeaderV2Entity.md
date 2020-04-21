---
title: TMSFreightInvoiceHeaderV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# TMSFreightInvoiceHeaderV2Entity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSFreightInvoiceHeaderV2Entity.cdm.json" target="_blank">GitHub</a>.  

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
|[ShippingCarrierVendorAccountNumber](#ShippingCarrierVendorAccountNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DestinationCountryRegionId](#DestinationCountryRegionId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[IsInvoiceAutomaticallyMatched](#IsInvoiceAutomaticallyMatched)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultBillOfLadingId](#DefaultBillOfLadingId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultBookingNumber](#DefaultBookingNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultShippingCarrierId](#DefaultShippingCarrierId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultShippingCarrierServiceId](#DefaultShippingCarrierServiceId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultCosigneeName](#DefaultCosigneeName)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DestinationCountryRegionISOCode](#DestinationCountryRegionISOCode)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultLastCycleCountingDateTime](#DefaultLastCycleCountingDateTime)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[CashDiscountAmount](#CashDiscountAmount)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[TransportationDistance](#TransportationDistance)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[TransportationDistanceUnitId](#TransportationDistanceUnitId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DocumentDate](#DocumentDate)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DocumentNumber](#DocumentNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DueDateTime](#DueDateTime)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[InternalInvoiceNumber](#InternalInvoiceNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[ReferenceNumber](#ReferenceNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[InvoiceStatus](#InvoiceStatus)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[LoadId](#LoadId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[OriginalQuoteId](#OriginalQuoteId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[PayeeVendorAccountNumber](#PayeeVendorAccountNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[PaymentId](#PaymentId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[ProNumberCode](#ProNumberCode)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[TotalFreightQuantity](#TotalFreightQuantity)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultRelatedAccountNumber](#DefaultRelatedAccountNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultRelatedOrderNumber](#DefaultRelatedOrderNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[TransportationRouteCode](#TransportationRouteCode)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[SCACCode](#SCACCode)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultShipmentId](#DefaultShipmentId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultFreightHeldUntilDateTime](#DefaultFreightHeldUntilDateTime)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultTrailerNumber](#DefaultTrailerNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[InvoiceVendorAccountNumber](#InvoiceVendorAccountNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[InvoiceNumber](#InvoiceNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[VendorReference](#VendorReference)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultVesselName](#DefaultVesselName)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[DefaultVoyageNumber](#DefaultVoyageNumber)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[TotalFreightWeight](#TotalFreightWeight)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[FreightWeightUnitId](#FreightWeightUnitId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[BackingTable_TMSInvoiceTableRelationshipId](#BackingTable_TMSInvoiceTableRelationshipId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSFreightInvoiceHeaderV2Entity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderV2Entity</a>|

### <a href=#ShippingCarrierVendorAccountNumber name="ShippingCarrierVendorAccountNumber">ShippingCarrierVendorAccountNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#DestinationCountryRegionId name="DestinationCountryRegionId">DestinationCountryRegionId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#IsInvoiceAutomaticallyMatched name="IsInvoiceAutomaticallyMatched">IsInvoiceAutomaticallyMatched</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoiceAutomaticallyMatched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBillOfLadingId name="DefaultBillOfLadingId">DefaultBillOfLadingId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBillOfLadingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBookingNumber name="DefaultBookingNumber">DefaultBookingNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBookingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShippingCarrierId name="DefaultShippingCarrierId">DefaultShippingCarrierId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShippingCarrierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShippingCarrierServiceId name="DefaultShippingCarrierServiceId">DefaultShippingCarrierServiceId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShippingCarrierServiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCosigneeName name="DefaultCosigneeName">DefaultCosigneeName</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCosigneeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationCountryRegionISOCode name="DestinationCountryRegionISOCode">DestinationCountryRegionISOCode</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLastCycleCountingDateTime name="DefaultLastCycleCountingDateTime">DefaultLastCycleCountingDateTime</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLastCycleCountingDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountAmount name="CashDiscountAmount">CashDiscountAmount</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDistance name="TransportationDistance">TransportationDistance</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#TransportationDistanceUnitId name="TransportationDistanceUnitId">TransportationDistanceUnitId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDistanceUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueDateTime name="DueDateTime">DueDateTime</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalInvoiceNumber name="InternalInvoiceNumber">InternalInvoiceNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#InvoiceAmount name="InvoiceAmount">InvoiceAmount</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#ReferenceNumber name="ReferenceNumber">ReferenceNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceStatus name="InvoiceStatus">InvoiceStatus</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadId name="LoadId">LoadId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#OriginalQuoteId name="OriginalQuoteId">OriginalQuoteId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalQuoteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayeeVendorAccountNumber name="PayeeVendorAccountNumber">PayeeVendorAccountNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayeeVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentId name="PaymentId">PaymentId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProNumberCode name="ProNumberCode">ProNumberCode</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#TotalFreightQuantity name="TotalFreightQuantity">TotalFreightQuantity</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalFreightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRelatedAccountNumber name="DefaultRelatedAccountNumber">DefaultRelatedAccountNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRelatedAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRelatedOrderNumber name="DefaultRelatedOrderNumber">DefaultRelatedOrderNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRelatedOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationRouteCode name="TransportationRouteCode">TransportationRouteCode</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#SCACCode name="SCACCode">SCACCode</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SCACCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShipmentId name="DefaultShipmentId">DefaultShipmentId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShipmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultFreightHeldUntilDateTime name="DefaultFreightHeldUntilDateTime">DefaultFreightHeldUntilDateTime</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFreightHeldUntilDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTrailerNumber name="DefaultTrailerNumber">DefaultTrailerNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTrailerNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceVendorAccountNumber name="InvoiceVendorAccountNumber">InvoiceVendorAccountNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#InvoiceNumber name="InvoiceNumber">InvoiceNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorReference name="VendorReference">VendorReference</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVesselName name="DefaultVesselName">DefaultVesselName</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVesselName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVoyageNumber name="DefaultVoyageNumber">DefaultVoyageNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVoyageNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalFreightWeight name="TotalFreightWeight">TotalFreightWeight</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalFreightWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightWeightUnitId name="FreightWeightUnitId">FreightWeightUnitId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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

### <a href=#BackingTable_TMSInvoiceTableRelationshipId name="BackingTable_TMSInvoiceTableRelationshipId">BackingTable_TMSInvoiceTableRelationshipId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSInvoiceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/WorksheetHeader/TMSInvoiceTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/WorksheetHeader/TMSInvoiceTable.cdm.json/TMSInvoiceTable</a></td><td><a href="../../../Tables/SupplyChain/Transportation/WorksheetHeader/TMSInvoiceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSFreightInvoiceHeaderV2Entity (this entity)  

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
