---
title: ProjSalesItemRequirementEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Project item requirements

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjSalesItemRequirementEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project item requirements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ActivityNumber](#ActivityNumber)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[BarCode](#BarCode)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[BarCodeType](#BarCodeType)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[IsStatusStopped](#IsStatusStopped)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[IsPartialDeliveryPrevented](#IsPartialDeliveryPrevented)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ShipDate](#ShipDate)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[CostPrice](#CostPrice)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryDateControl](#DeliveryDateControl)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryName](#DeliveryName)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryType](#DeliveryType)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ModeOfDelivery](#ModeOfDelivery)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryTerms](#DeliveryTerms)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[InventDeliverNow](#InventDeliverNow)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ReferenceNumber](#ReferenceNumber)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ReferenceLot](#ReferenceLot)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ReferenceType](#ReferenceType)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[InventTransactionId](#InventTransactionId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[InventTransactionReturnId](#InventTransactionReturnId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ItemBOMId](#ItemBOMId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ItemId](#ItemId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ItemRouteId](#ItemRouteId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[LedgerDimension](#LedgerDimension)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[NetAmount](#NetAmount)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[LineDeliveryType](#LineDeliveryType)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[Name](#Name)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[Overdelivery](#Overdelivery)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[AutoBatchReservation](#AutoBatchReservation)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[SameBatchSelection](#SameBatchSelection)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[PriceUnit](#PriceUnit)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ProjectId](#ProjectId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ProjectLinePropertyId](#ProjectLinePropertyId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ProjectTransactionId](#ProjectTransactionId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[QuantityOrdered](#QuantityOrdered)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ReceiptDateConfirmed](#ReceiptDateConfirmed)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ReceiptDateRequested](#ReceiptDateRequested)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[RemainInventFinancial](#RemainInventFinancial)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[RemainInventPhysical](#RemainInventPhysical)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[Reservation](#Reservation)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[SalesCategory](#SalesCategory)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[SalesPrice](#SalesPrice)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[SalesQuantity](#SalesQuantity)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[SalesStatus](#SalesStatus)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[SalesUnit](#SalesUnit)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[Scrap](#Scrap)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ServiceOrderId](#ServiceOrderId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ShippingDateConfirmed](#ShippingDateConfirmed)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ShippingDateRequested](#ShippingDateRequested)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[TaxGroup](#TaxGroup)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[Underdelivery](#Underdelivery)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[SalesCategoryName](#SalesCategoryName)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryPostalAddressRecId](#DeliveryPostalAddressRecId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[FormattedDelveryAddress](#FormattedDelveryAddress)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryBuildingCompliment](#DeliveryBuildingCompliment)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryValidFrom](#DeliveryValidFrom)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryValidTo](#DeliveryValidTo)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ShippingWarehouseId](#ShippingWarehouseId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ShippingSiteId](#ShippingSiteId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[OrderedInventoryStatusId](#OrderedInventoryStatusId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[IsDeliveryAddressOrderSpecific](#IsDeliveryAddressOrderSpecific)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryCFOP](#DeliveryCFOP)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[DeliveryCFOPId](#DeliveryCFOPId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[Relationship_LedgerDimensionCombinationRelationshipId](#Relationship_LedgerDimensionCombinationRelationshipId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[BackingTable_SalesLineRelationshipId](#BackingTable_SalesLineRelationshipId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjSalesItemRequirementEntity.md" target="_blank">ProjectManagementAndAccounting/ProjSalesItemRequirementEntity</a>|

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCode name="BarCode">BarCode</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCodeType name="BarCodeType">BarCodeType</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCodeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStatusStopped name="IsStatusStopped">IsStatusStopped</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStatusStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPartialDeliveryPrevented name="IsPartialDeliveryPrevented">IsPartialDeliveryPrevented</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPartialDeliveryPrevented attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipDate name="ShipDate">ShipDate</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostPrice name="CostPrice">CostPrice</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDateControl name="DeliveryDateControl">DeliveryDateControl</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDateControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryType name="DeliveryType">DeliveryType</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModeOfDelivery name="ModeOfDelivery">ModeOfDelivery</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModeOfDelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTerms name="DeliveryTerms">DeliveryTerms</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDeliverNow name="InventDeliverNow">InventDeliverNow</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDeliverNow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceNumber name="ReferenceNumber">ReferenceNumber</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#ReferenceLot name="ReferenceLot">ReferenceLot</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceLot attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceType name="ReferenceType">ReferenceType</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransactionId name="InventTransactionId">InventTransactionId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransactionReturnId name="InventTransactionReturnId">InventTransactionReturnId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransactionReturnId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBOMId name="ItemBOMId">ItemBOMId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRouteId name="ItemRouteId">ItemRouteId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRouteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#LineDeliveryType name="LineDeliveryType">LineDeliveryType</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDeliveryType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Overdelivery name="Overdelivery">Overdelivery</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Overdelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoBatchReservation name="AutoBatchReservation">AutoBatchReservation</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoBatchReservation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SameBatchSelection name="SameBatchSelection">SameBatchSelection</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SameBatchSelection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceUnit name="PriceUnit">PriceUnit</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#ProjectTransactionId name="ProjectTransactionId">ProjectTransactionId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityOrdered name="QuantityOrdered">QuantityOrdered</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityOrdered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptDateConfirmed name="ReceiptDateConfirmed">ReceiptDateConfirmed</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptDateConfirmed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptDateRequested name="ReceiptDateRequested">ReceiptDateRequested</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptDateRequested attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainInventFinancial name="RemainInventFinancial">RemainInventFinancial</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainInventFinancial attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainInventPhysical name="RemainInventPhysical">RemainInventPhysical</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainInventPhysical attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reservation name="Reservation">Reservation</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reservation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCategory name="SalesCategory">SalesCategory</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#SalesQuantity name="SalesQuantity">SalesQuantity</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesStatus name="SalesStatus">SalesStatus</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnit name="SalesUnit">SalesUnit</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scrap name="Scrap">Scrap</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scrap attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceOrderId name="ServiceOrderId">ServiceOrderId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceOrderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingDateConfirmed name="ShippingDateConfirmed">ShippingDateConfirmed</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingDateConfirmed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingDateRequested name="ShippingDateRequested">ShippingDateRequested</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingDateRequested attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Underdelivery name="Underdelivery">Underdelivery</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Underdelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCategoryName name="SalesCategoryName">SalesCategoryName</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddressRecId name="DeliveryPostalAddressRecId">DeliveryPostalAddressRecId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#FormattedDelveryAddress name="FormattedDelveryAddress">FormattedDelveryAddress</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedDelveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryBuildingCompliment name="DeliveryBuildingCompliment">DeliveryBuildingCompliment</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#IsDeliveryAddressPrivate name="IsDeliveryAddressPrivate">IsDeliveryAddressPrivate</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#DeliveryValidFrom name="DeliveryValidFrom">DeliveryValidFrom</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidTo name="DeliveryValidTo">DeliveryValidTo</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressOrderSpecific name="IsDeliveryAddressOrderSpecific">IsDeliveryAddressOrderSpecific</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>One time delivery address</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressOrderSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>One time delivery address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCFOP name="DeliveryCFOP">DeliveryCFOP</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCFOP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCFOPId name="DeliveryCFOPId">DeliveryCFOPId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery CFOP</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCFOPId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery CFOP</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerDimensionCombinationRelationshipId name="Relationship_LedgerDimensionCombinationRelationshipId">Relationship_LedgerDimensionCombinationRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_SalesLineRelationshipId name="BackingTable_SalesLineRelationshipId">BackingTable_SalesLineRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.cdm.json/SalesLine</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjSalesItemRequirementEntity (this entity)  

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
