---
title: PurchaseOrderResponseHeaderEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Purchase order response headers in ProcurementAndSourcing(PurchaseOrderResponseHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order response headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PurchaseOrderResponseLastModificationDateTime](#PurchaseOrderResponseLastModificationDateTime)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[RespondingDateTime](#RespondingDateTime)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[ResponseStatus](#ResponseStatus)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[ResponseNote](#ResponseNote)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryModeId](#DeliveryModeId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[OrderVendorAccountNumber](#OrderVendorAccountNumber)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[TotalDiscountPercentage](#TotalDiscountPercentage)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[VendorPaymentMethodName](#VendorPaymentMethodName)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[InvoiceVendorAccountNumber](#InvoiceVendorAccountNumber)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[PurchaseOrderStatus](#PurchaseOrderStatus)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryTermsId](#DeliveryTermsId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[RequestedDeliveryDate](#RequestedDeliveryDate)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[ConfirmedDeliveryDate](#ConfirmedDeliveryDate)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[PurchaseOrderSentDate](#PurchaseOrderSentDate)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[VendorOrderReference](#VendorOrderReference)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[ResponseProcessingState](#ResponseProcessingState)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressBuildingCompliment](#DeliveryAddressBuildingCompliment)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressCityInKana](#DeliveryAddressCityInKana)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressStreetInKana](#DeliveryAddressStreetInKana)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressValidFrom](#DeliveryAddressValidFrom)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressValidTo](#DeliveryAddressValidTo)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[PurchaseOrderDocumentReference](#PurchaseOrderDocumentReference)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[RespondingPersonPartyNumber](#RespondingPersonPartyNumber)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[Relationship_InvoiceVendorRelationshipId](#Relationship_InvoiceVendorRelationshipId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[Relationship_OrderVendorRelationshipId](#Relationship_OrderVendorRelationshipId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[BackingTable_PurchaseOrderResponseVersionRelationshipId](#BackingTable_PurchaseOrderResponseVersionRelationshipId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchaseOrderResponseHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity</a>|

### <a href=#PurchaseOrderResponseLastModificationDateTime name="PurchaseOrderResponseLastModificationDateTime">PurchaseOrderResponseLastModificationDateTime</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderResponseLastModificationDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RespondingDateTime name="RespondingDateTime">RespondingDateTime</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RespondingDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponseStatus name="ResponseStatus">ResponseStatus</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponseStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponseNote name="ResponseNote">ResponseNote</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponseNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeId name="DeliveryModeId">DeliveryModeId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderVendorAccountNumber name="OrderVendorAccountNumber">OrderVendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountPercentage name="TotalDiscountPercentage">TotalDiscountPercentage</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPaymentMethodName name="VendorPaymentMethodName">VendorPaymentMethodName</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPaymentMethodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceVendorAccountNumber name="InvoiceVendorAccountNumber">InvoiceVendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderStatus name="PurchaseOrderStatus">PurchaseOrderStatus</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsId name="DeliveryTermsId">DeliveryTermsId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedDeliveryDate name="RequestedDeliveryDate">RequestedDeliveryDate</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedDeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmedDeliveryDate name="ConfirmedDeliveryDate">ConfirmedDeliveryDate</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedDeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderSentDate name="PurchaseOrderSentDate">PurchaseOrderSentDate</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderSentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorOrderReference name="VendorOrderReference">VendorOrderReference</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorOrderReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponseProcessingState name="ResponseProcessingState">ResponseProcessingState</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponseProcessingState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedDeliveryAddress name="FormattedDeliveryAddress">FormattedDeliveryAddress</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedDeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressBuildingCompliment name="DeliveryAddressBuildingCompliment">DeliveryAddressBuildingCompliment</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCityInKana name="DeliveryAddressCityInKana">DeliveryAddressCityInKana</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionISOCode name="DeliveryAddressCountryRegionISOCode">DeliveryAddressCountryRegionISOCode</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountyId name="DeliveryAddressCountyId">DeliveryAddressCountyId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDescription name="DeliveryAddressDescription">DeliveryAddressDescription</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address description </td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address description </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDunsNumber name="DeliveryAddressDunsNumber">DeliveryAddressDunsNumber</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressPrivate name="IsDeliveryAddressPrivate">IsDeliveryAddressPrivate</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is delivery address private</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is delivery address private</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLongitude name="DeliveryAddressLongitude">DeliveryAddressLongitude</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressPostBox name="DeliveryAddressPostBox">DeliveryAddressPostBox</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStateId name="DeliveryAddressStateId">DeliveryAddressStateId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreet name="DeliveryAddressStreet">DeliveryAddressStreet</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetInKana name="DeliveryAddressStreetInKana">DeliveryAddressStreetInKana</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressValidFrom name="DeliveryAddressValidFrom">DeliveryAddressValidFrom</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressValidTo name="DeliveryAddressValidTo">DeliveryAddressValidTo</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderDocumentReference name="PurchaseOrderDocumentReference">PurchaseOrderDocumentReference</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderDocumentReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RespondingPersonPartyNumber name="RespondingPersonPartyNumber">RespondingPersonPartyNumber</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Responding person party number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RespondingPersonPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Responding person party number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InvoiceVendorRelationshipId name="Relationship_InvoiceVendorRelationshipId">Relationship_InvoiceVendorRelationshipId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceVendorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OrderVendorRelationshipId name="Relationship_OrderVendorRelationshipId">Relationship_OrderVendorRelationshipId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrderVendorRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PurchaseOrderResponseVersionRelationshipId name="BackingTable_PurchaseOrderResponseVersionRelationshipId">BackingTable_PurchaseOrderResponseVersionRelationshipId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchaseOrderResponseVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/PurchaseOrderResponseVersion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/PurchaseOrderResponseVersion.cdm.json/PurchaseOrderResponseVersion</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/PurchaseOrderResponseVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchaseOrderResponseHeaderEntity (this entity)  

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
