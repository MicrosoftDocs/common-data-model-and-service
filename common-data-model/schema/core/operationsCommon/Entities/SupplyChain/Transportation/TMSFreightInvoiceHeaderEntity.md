---
title: TMSFreightInvoiceHeaderEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Freight invoice headers

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSFreightInvoiceHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Freight invoice headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ShippingCarrierVendorAccountNumber](#ShippingCarrierVendorAccountNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DestinationCountryRegionId](#DestinationCountryRegionId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[IsInvoiceAutomaticallyMatched](#IsInvoiceAutomaticallyMatched)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultBillOfLadingId](#DefaultBillOfLadingId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultBookingNumber](#DefaultBookingNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultShippingCarrierId](#DefaultShippingCarrierId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultShippingCarrierServiceId](#DefaultShippingCarrierServiceId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultCosigneeName](#DefaultCosigneeName)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DestinationCountryRegionISOCode](#DestinationCountryRegionISOCode)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultLastCycleCountingDateTime](#DefaultLastCycleCountingDateTime)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[CashDiscountAmount](#CashDiscountAmount)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[TransportationDistance](#TransportationDistance)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[TransportationDistanceUnitId](#TransportationDistanceUnitId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DocumentNumber](#DocumentNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DueDateTime](#DueDateTime)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[InternalInvoiceNumber](#InternalInvoiceNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[ReferenceNumber](#ReferenceNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[InvoiceStatus](#InvoiceStatus)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[LoadId](#LoadId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[OriginalQuoteId](#OriginalQuoteId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[PayeeVendorAccountNumber](#PayeeVendorAccountNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[PaymentId](#PaymentId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[ProNumberCode](#ProNumberCode)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[TotalFreightQuantity](#TotalFreightQuantity)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultRelatedAccountNumber](#DefaultRelatedAccountNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultRelatedOrderNumber](#DefaultRelatedOrderNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[TransportationRouteCode](#TransportationRouteCode)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[SCACCode](#SCACCode)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultShipmentId](#DefaultShipmentId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultFreightHeldUntilDateTime](#DefaultFreightHeldUntilDateTime)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultTrailerNumber](#DefaultTrailerNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[InvoiceVendorAccountNumber](#InvoiceVendorAccountNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[InvoiceNumber](#InvoiceNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[VendorReference](#VendorReference)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultVesselName](#DefaultVesselName)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[DefaultVoyageNumber](#DefaultVoyageNumber)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[TotalFreightWeight](#TotalFreightWeight)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[FreightWeightUnitId](#FreightWeightUnitId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[BackingTable_TMSInvoiceTableRelationshipId](#BackingTable_TMSInvoiceTableRelationshipId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSFreightInvoiceHeaderEntity.md" target="_blank">Transportation/TMSFreightInvoiceHeaderEntity</a>|

### <a href=#ShippingCarrierVendorAccountNumber name="ShippingCarrierVendorAccountNumber">ShippingCarrierVendorAccountNumber</a>

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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

First included in: Transportation/TMSFreightInvoiceHeaderEntity (this entity)  

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
