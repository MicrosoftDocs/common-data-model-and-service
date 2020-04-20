---
title: RetailOfflineProfile - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailOfflineProfile

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailOfflineProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailOfflineProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[AddressBook](#AddressBook)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[Assortment](#Assortment)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[CheckNewDBInterval](#CheckNewDBInterval)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[DBExportPath](#DBExportPath)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[Description](#Description)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ImagePath](#ImagePath)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[Name](#Name)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[UploadTransactionSize](#UploadTransactionSize)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ReconnectInterval](#ReconnectInterval)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[Timeout](#Timeout)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[CustomerByAddress](#CustomerByAddress)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[CustomerBySalesAmount](#CustomerBySalesAmount)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[CustomerBySalesAmountDayLimit](#CustomerBySalesAmountDayLimit)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[CustomerBySalesAmountNumLimit](#CustomerBySalesAmountNumLimit)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[CustomerByVisits](#CustomerByVisits)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[CustomerByVisitsDayLimit](#CustomerByVisitsDayLimit)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[CustomerByVisitsNumLimit](#CustomerByVisitsNumLimit)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[LimitAssortedProducts](#LimitAssortedProducts)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[LimitAvailableCustomers](#LimitAvailableCustomers)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductSalesAmountLimit](#ProductSalesAmountLimit)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductSalesAmountLimitDays](#ProductSalesAmountLimitDays)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductSalesQuantityLimit](#ProductSalesQuantityLimit)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductSalesQuantityLimitDays](#ProductSalesQuantityLimitDays)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductsArrivalLimit](#ProductsArrivalLimit)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductsArrivalLimitDays](#ProductsArrivalLimitDays)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductsByRecentArrival](#ProductsByRecentArrival)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductsBySalesAmount](#ProductsBySalesAmount)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductsBySalesQuantity](#ProductsBySalesQuantity)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[ProductsBySpecificCategory](#ProductsBySpecificCategory)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[TrxUploadInterval](#TrxUploadInterval)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[PromptOnSeamlessOffline](#PromptOnSeamlessOffline)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[RetryCountToOffline](#RetryCountToOffline)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[AllowManualOfflineBeforeSignIn](#AllowManualOfflineBeforeSignIn)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[EnableAdvancedOfflineSwitching](#EnableAdvancedOfflineSwitching)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[SystemHealthCheckInterval](#SystemHealthCheckInterval)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[PauseOfflineSync](#PauseOfflineSync)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[Relationship_DirAddressBookRelationshipId](#Relationship_DirAddressBookRelationshipId)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|
|[Relationship_RetailAssortmentTableRelationshipId](#Relationship_RetailAssortmentTableRelationshipId)||<a href="RetailOfflineProfile.md" target="_blank">Miscellaneous/RetailOfflineProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailOfflineProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AddressBook name="AddressBook">AddressBook</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBook attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Assortment name="Assortment">Assortment</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Assortment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CheckNewDBInterval name="CheckNewDBInterval">CheckNewDBInterval</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckNewDBInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DBExportPath name="DBExportPath">DBExportPath</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DBExportPath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImagePath name="ImagePath">ImagePath</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImagePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

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

### <a href=#UploadTransactionSize name="UploadTransactionSize">UploadTransactionSize</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UploadTransactionSize attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReconnectInterval name="ReconnectInterval">ReconnectInterval</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconnectInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Timeout name="Timeout">Timeout</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timeout attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerByAddress name="CustomerByAddress">CustomerByAddress</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerByAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerBySalesAmount name="CustomerBySalesAmount">CustomerBySalesAmount</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerBySalesAmount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerBySalesAmountDayLimit name="CustomerBySalesAmountDayLimit">CustomerBySalesAmountDayLimit</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerBySalesAmountDayLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerBySalesAmountNumLimit name="CustomerBySalesAmountNumLimit">CustomerBySalesAmountNumLimit</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerBySalesAmountNumLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerByVisits name="CustomerByVisits">CustomerByVisits</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerByVisits attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerByVisitsDayLimit name="CustomerByVisitsDayLimit">CustomerByVisitsDayLimit</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerByVisitsDayLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerByVisitsNumLimit name="CustomerByVisitsNumLimit">CustomerByVisitsNumLimit</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerByVisitsNumLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LimitAssortedProducts name="LimitAssortedProducts">LimitAssortedProducts</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitAssortedProducts attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LimitAvailableCustomers name="LimitAvailableCustomers">LimitAvailableCustomers</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitAvailableCustomers attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductSalesAmountLimit name="ProductSalesAmountLimit">ProductSalesAmountLimit</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesAmountLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductSalesAmountLimitDays name="ProductSalesAmountLimitDays">ProductSalesAmountLimitDays</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesAmountLimitDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductSalesQuantityLimit name="ProductSalesQuantityLimit">ProductSalesQuantityLimit</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesQuantityLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductSalesQuantityLimitDays name="ProductSalesQuantityLimitDays">ProductSalesQuantityLimitDays</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesQuantityLimitDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductsArrivalLimit name="ProductsArrivalLimit">ProductsArrivalLimit</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsArrivalLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductsArrivalLimitDays name="ProductsArrivalLimitDays">ProductsArrivalLimitDays</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsArrivalLimitDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductsByRecentArrival name="ProductsByRecentArrival">ProductsByRecentArrival</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsByRecentArrival attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductsBySalesAmount name="ProductsBySalesAmount">ProductsBySalesAmount</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsBySalesAmount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductsBySalesQuantity name="ProductsBySalesQuantity">ProductsBySalesQuantity</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsBySalesQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductsBySpecificCategory name="ProductsBySpecificCategory">ProductsBySpecificCategory</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsBySpecificCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TrxUploadInterval name="TrxUploadInterval">TrxUploadInterval</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrxUploadInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PromptOnSeamlessOffline name="PromptOnSeamlessOffline">PromptOnSeamlessOffline</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptOnSeamlessOffline attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetryCountToOffline name="RetryCountToOffline">RetryCountToOffline</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetryCountToOffline attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowManualOfflineBeforeSignIn name="AllowManualOfflineBeforeSignIn">AllowManualOfflineBeforeSignIn</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowManualOfflineBeforeSignIn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableAdvancedOfflineSwitching name="EnableAdvancedOfflineSwitching">EnableAdvancedOfflineSwitching</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableAdvancedOfflineSwitching attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SystemHealthCheckInterval name="SystemHealthCheckInterval">SystemHealthCheckInterval</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemHealthCheckInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PauseOfflineSync name="PauseOfflineSync">PauseOfflineSync</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PauseOfflineSync attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_DirAddressBookRelationshipId name="Relationship_DirAddressBookRelationshipId">Relationship_DirAddressBookRelationshipId</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DirAddressBookRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/DirAddressBook.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/DirAddressBook.cdm.json/DirAddressBook</a></td><td><a href="../../../Common/GAB/Group/DirAddressBook.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailAssortmentTableRelationshipId name="Relationship_RetailAssortmentTableRelationshipId">Relationship_RetailAssortmentTableRelationshipId</a>

First included in: Miscellaneous/RetailOfflineProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailAssortmentTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailAssortmentTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailAssortmentTable.cdm.json/RetailAssortmentTable</a></td><td><a href="../Main/RetailAssortmentTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
