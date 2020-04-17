---
title: SalesOrderLineCDSEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# SalesOrderLineCDSEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/SalesAndMarketing/SalesOrderLineCDSEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[SalesOrderNumber](#SalesOrderNumber)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[LineCreationSequenceNumber](#LineCreationSequenceNumber)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[SalesOrderLineStatus](#SalesOrderLineStatus)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[IsLineStopped](#IsLineStopped)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[LineAmount](#LineAmount)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[LineDiscountAmount](#LineDiscountAmount)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[LineDiscountPercentage](#LineDiscountPercentage)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[MultilineDiscountAmount](#MultilineDiscountAmount)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[MultilineDiscountPercentage](#MultilineDiscountPercentage)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[LineDescription](#LineDescription)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[SalesPriceQuantity](#SalesPriceQuantity)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[RequestedReceiptDate](#RequestedReceiptDate)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[FixedPriceCharges](#FixedPriceCharges)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[SalesPrice](#SalesPrice)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[OrderedSalesQuantity](#OrderedSalesQuantity)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[SalesUnitSymbol](#SalesUnitSymbol)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ConfirmedShippingDate](#ConfirmedShippingDate)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[RequestedShippingDate](#RequestedShippingDate)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ShippingWarehouseId](#ShippingWarehouseId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ShippingSiteId](#ShippingSiteId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[OrderedInventoryStatusId](#OrderedInventoryStatusId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[TotalTaxAmount](#TotalTaxAmount)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[TotalChargesAmount](#TotalChargesAmount)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ProductNumber](#ProductNumber)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[AreTotalsCalculated](#AreTotalsCalculated)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryBuildingCompliment](#DeliveryBuildingCompliment)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[IsDeliveryAddressOrderSpecific](#IsDeliveryAddressOrderSpecific)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ProductName](#ProductName)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[SalesOrderProcessingStatus](#SalesOrderProcessingStatus)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[OrderingCustomerIsExternallyMaintained](#OrderingCustomerIsExternallyMaintained)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[InvoiceCustomerIsExternallyMaintained](#InvoiceCustomerIsExternallyMaintained)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[AreSalesOrderTotalsUpdated](#AreSalesOrderTotalsUpdated)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[AllowedOverdeliveryPercentage](#AllowedOverdeliveryPercentage)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[AllowedUnderdeliveryPercentage](#AllowedUnderdeliveryPercentage)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ConfirmedReceiptDate](#ConfirmedReceiptDate)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryTermsId](#DeliveryTermsId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ExternalItemNumber](#ExternalItemNumber)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[SalesOrderPromisingMethod](#SalesOrderPromisingMethod)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[SalesProductCategoryName](#SalesProductCategoryName)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[SalesOrderOriginType](#SalesOrderOriginType)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[PickedQuantity](#PickedQuantity)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ProjectId](#ProjectId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[ProjectLinePropertyId](#ProjectLinePropertyId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[SalesProductCategoryHierarchyName](#SalesProductCategoryHierarchyName)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[DeliveryPostalAddressRecId](#DeliveryPostalAddressRecId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[Relationship_SalesOrderHeaderCDSRelationshipId](#Relationship_SalesOrderHeaderCDSRelationshipId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[BackingTable_SalesOrderLineV2EntityRelationshipId](#BackingTable_SalesOrderLineV2EntityRelationshipId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesOrderLineCDSEntity.md" target="_blank">SalesAndMarketing/SalesOrderLineCDSEntity</a>|

### <a href=#SalesOrderNumber name="SalesOrderNumber">SalesOrderNumber</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineCreationSequenceNumber name="LineCreationSequenceNumber">LineCreationSequenceNumber</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineCreationSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderLineStatus name="SalesOrderLineStatus">SalesOrderLineStatus</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderLineStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLineStopped name="IsLineStopped">IsLineStopped</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLineStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressName name="DeliveryAddressName">DeliveryAddressName</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

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

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountAmount name="LineDiscountAmount">LineDiscountAmount</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountPercentage name="LineDiscountPercentage">LineDiscountPercentage</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountAmount name="MultilineDiscountAmount">MultilineDiscountAmount</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountPercentage name="MultilineDiscountPercentage">MultilineDiscountPercentage</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceQuantity name="SalesPriceQuantity">SalesPriceQuantity</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedReceiptDate name="RequestedReceiptDate">RequestedReceiptDate</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedPriceCharges name="FixedPriceCharges">FixedPriceCharges</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderedSalesQuantity name="OrderedSalesQuantity">OrderedSalesQuantity</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedSalesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitSymbol name="SalesUnitSymbol">SalesUnitSymbol</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmedShippingDate name="ConfirmedShippingDate">ConfirmedShippingDate</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShippingDate name="RequestedShippingDate">RequestedShippingDate</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingWarehouseId name="ShippingWarehouseId">ShippingWarehouseId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingSiteId name="ShippingSiteId">ShippingSiteId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderedInventoryStatusId name="OrderedInventoryStatusId">OrderedInventoryStatusId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalTaxAmount name="TotalTaxAmount">TotalTaxAmount</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalChargesAmount name="TotalChargesAmount">TotalChargesAmount</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalChargesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreTotalsCalculated name="AreTotalsCalculated">AreTotalsCalculated</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreTotalsCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionISOCode name="DeliveryAddressCountryRegionISOCode">DeliveryAddressCountryRegionISOCode</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountyId name="DeliveryAddressCountyId">DeliveryAddressCountyId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDescription name="DeliveryAddressDescription">DeliveryAddressDescription</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDunsNumber name="DeliveryAddressDunsNumber">DeliveryAddressDunsNumber</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLongitude name="DeliveryAddressLongitude">DeliveryAddressLongitude</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressPostBox name="DeliveryAddressPostBox">DeliveryAddressPostBox</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStateId name="DeliveryAddressStateId">DeliveryAddressStateId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreet name="DeliveryAddressStreet">DeliveryAddressStreet</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryBuildingCompliment name="DeliveryBuildingCompliment">DeliveryBuildingCompliment</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedDeliveryAddress name="FormattedDeliveryAddress">FormattedDeliveryAddress</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedDeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressPrivate name="IsDeliveryAddressPrivate">IsDeliveryAddressPrivate</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressOrderSpecific name="IsDeliveryAddressOrderSpecific">IsDeliveryAddressOrderSpecific</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressOrderSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

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

### <a href=#SalesOrderProcessingStatus name="SalesOrderProcessingStatus">SalesOrderProcessingStatus</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderProcessingStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderingCustomerIsExternallyMaintained name="OrderingCustomerIsExternallyMaintained">OrderingCustomerIsExternallyMaintained</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingCustomerIsExternallyMaintained attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCustomerIsExternallyMaintained name="InvoiceCustomerIsExternallyMaintained">InvoiceCustomerIsExternallyMaintained</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCustomerIsExternallyMaintained attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderTotalsUpdated name="AreSalesOrderTotalsUpdated">AreSalesOrderTotalsUpdated</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderTotalsUpdated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedOverdeliveryPercentage name="AllowedOverdeliveryPercentage">AllowedOverdeliveryPercentage</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedOverdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedUnderdeliveryPercentage name="AllowedUnderdeliveryPercentage">AllowedUnderdeliveryPercentage</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedUnderdeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmedReceiptDate name="ConfirmedReceiptDate">ConfirmedReceiptDate</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCode name="DeliveryModeCode">DeliveryModeCode</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

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

### <a href=#DeliveryTermsId name="DeliveryTermsId">DeliveryTermsId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalItemNumber name="ExternalItemNumber">ExternalItemNumber</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPromisingMethod name="SalesOrderPromisingMethod">SalesOrderPromisingMethod</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderPromisingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesProductCategoryName name="SalesProductCategoryName">SalesProductCategoryName</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderOriginType name="SalesOrderOriginType">SalesOrderOriginType</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderOriginType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PickedQuantity name="PickedQuantity">PickedQuantity</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectLinePropertyId name="ProjectLinePropertyId">ProjectLinePropertyId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectLinePropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesProductCategoryHierarchyName name="SalesProductCategoryHierarchyName">SalesProductCategoryHierarchyName</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesProductCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddressRecId name="DeliveryPostalAddressRecId">DeliveryPostalAddressRecId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesOrderHeaderCDSRelationshipId name="Relationship_SalesOrderHeaderCDSRelationshipId">Relationship_SalesOrderHeaderCDSRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesOrderHeaderCDSRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_SalesOrderLineV2EntityRelationshipId name="BackingTable_SalesOrderLineV2EntityRelationshipId">BackingTable_SalesOrderLineV2EntityRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesOrderLineV2EntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderLineCDSEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
