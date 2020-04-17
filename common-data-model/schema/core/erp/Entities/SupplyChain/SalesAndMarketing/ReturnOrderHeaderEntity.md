---
title: ReturnOrderHeaderEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# ReturnOrderHeaderEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/SalesAndMarketing/ReturnOrderHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ReturnOrderNumber](#ReturnOrderNumber)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[CustomersOrderReference](#CustomersOrderReference)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[Email](#Email)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[DefaultReturnWarehouseId](#DefaultReturnWarehouseId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[DefaultReturnSiteId](#DefaultReturnSiteId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[LanguageId](#LanguageId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[IsReturnProcessingStopped](#IsReturnProcessingStopped)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[CustomerRequisitionNumber](#CustomerRequisitionNumber)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnDeadline](#ReturnDeadline)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[RMANumber](#RMANumber)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[CustomerReturnReasonCode](#CustomerReturnReasonCode)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[IsReplacementSalesOrderCreated](#IsReplacementSalesOrderCreated)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReplacementSalesOrderNumber](#ReplacementSalesOrderNumber)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressName](#ReturnAddressName)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnOrderStatus](#ReturnOrderStatus)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnPostalAddressRecId](#ReturnPostalAddressRecId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[IsReturnAddressOrderSpecific](#IsReturnAddressOrderSpecific)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[FormattedReturnAddress](#FormattedReturnAddress)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressBuildingCompliment](#ReturnAddressBuildingCompliment)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressCity](#ReturnAddressCity)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressCountryRegionId](#ReturnAddressCountryRegionId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressCountryRegionISOCode](#ReturnAddressCountryRegionISOCode)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressCountyId](#ReturnAddressCountyId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressDescription](#ReturnAddressDescription)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressDistrictName](#ReturnAddressDistrictName)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressDunsNumber](#ReturnAddressDunsNumber)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[IsReturnAddressPrivate](#IsReturnAddressPrivate)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressLatitude](#ReturnAddressLatitude)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressLocationId](#ReturnAddressLocationId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressLongitude](#ReturnAddressLongitude)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressPostBox](#ReturnAddressPostBox)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressStateId](#ReturnAddressStateId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressStreet](#ReturnAddressStreet)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressStreetNumber](#ReturnAddressStreetNumber)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressValidFrom](#ReturnAddressValidFrom)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressValidTo](#ReturnAddressValidTo)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressTimeZone](#ReturnAddressTimeZone)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressZipCode](#ReturnAddressZipCode)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressCityInKana](#ReturnAddressCityInKana)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[ReturnAddressStreetInKana](#ReturnAddressStreetInKana)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[BackingTable_SalesTableRelationshipId](#BackingTable_SalesTableRelationshipId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ReturnOrderHeaderEntity.md" target="_blank">SalesAndMarketing/ReturnOrderHeaderEntity</a>|

### <a href=#ReturnOrderNumber name="ReturnOrderNumber">ReturnOrderNumber</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

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

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomersOrderReference name="CustomersOrderReference">CustomersOrderReference</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomersOrderReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReturnWarehouseId name="DefaultReturnWarehouseId">DefaultReturnWarehouseId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReturnWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReturnSiteId name="DefaultReturnSiteId">DefaultReturnSiteId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReturnSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReturnProcessingStopped name="IsReturnProcessingStopped">IsReturnProcessingStopped</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReturnProcessingStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisitionNumber name="CustomerRequisitionNumber">CustomerRequisitionNumber</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisitionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnDeadline name="ReturnDeadline">ReturnDeadline</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnDeadline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RMANumber name="RMANumber">RMANumber</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RMANumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerReturnReasonCode name="CustomerReturnReasonCode">CustomerReturnReasonCode</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerReturnReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReplacementSalesOrderCreated name="IsReplacementSalesOrderCreated">IsReplacementSalesOrderCreated</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReplacementSalesOrderCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplacementSalesOrderNumber name="ReplacementSalesOrderNumber">ReplacementSalesOrderNumber</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplacementSalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressName name="ReturnAddressName">ReturnAddressName</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnOrderStatus name="ReturnOrderStatus">ReturnOrderStatus</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnPostalAddressRecId name="ReturnPostalAddressRecId">ReturnPostalAddressRecId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReturnAddressOrderSpecific name="IsReturnAddressOrderSpecific">IsReturnAddressOrderSpecific</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReturnAddressOrderSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedReturnAddress name="FormattedReturnAddress">FormattedReturnAddress</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedReturnAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressBuildingCompliment name="ReturnAddressBuildingCompliment">ReturnAddressBuildingCompliment</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressCity name="ReturnAddressCity">ReturnAddressCity</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressCountryRegionId name="ReturnAddressCountryRegionId">ReturnAddressCountryRegionId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressCountryRegionISOCode name="ReturnAddressCountryRegionISOCode">ReturnAddressCountryRegionISOCode</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressCountyId name="ReturnAddressCountyId">ReturnAddressCountyId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressDescription name="ReturnAddressDescription">ReturnAddressDescription</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressDistrictName name="ReturnAddressDistrictName">ReturnAddressDistrictName</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressDunsNumber name="ReturnAddressDunsNumber">ReturnAddressDunsNumber</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReturnAddressPrivate name="IsReturnAddressPrivate">IsReturnAddressPrivate</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReturnAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressLatitude name="ReturnAddressLatitude">ReturnAddressLatitude</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressLocationId name="ReturnAddressLocationId">ReturnAddressLocationId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressLongitude name="ReturnAddressLongitude">ReturnAddressLongitude</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressPostBox name="ReturnAddressPostBox">ReturnAddressPostBox</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressStateId name="ReturnAddressStateId">ReturnAddressStateId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressStreet name="ReturnAddressStreet">ReturnAddressStreet</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressStreetNumber name="ReturnAddressStreetNumber">ReturnAddressStreetNumber</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressValidFrom name="ReturnAddressValidFrom">ReturnAddressValidFrom</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressValidTo name="ReturnAddressValidTo">ReturnAddressValidTo</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressTimeZone name="ReturnAddressTimeZone">ReturnAddressTimeZone</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressZipCode name="ReturnAddressZipCode">ReturnAddressZipCode</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressCityInKana name="ReturnAddressCityInKana">ReturnAddressCityInKana</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnAddressStreetInKana name="ReturnAddressStreetInKana">ReturnAddressStreetInKana</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SalesTableRelationshipId name="BackingTable_SalesTableRelationshipId">BackingTable_SalesTableRelationshipId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/ReturnOrderHeaderEntity (this entity)  

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
