---
title: RetailOfflineProfileEntity in ChannelManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Offline profile in ChannelManagement(RetailOfflineProfileEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/RetailOfflineProfileEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offline profile</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AddressBook](#AddressBook)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[Assortment](#Assortment)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[CheckNewDBInterval](#CheckNewDBInterval)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[DBExportPath](#DBExportPath)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[Description](#Description)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ImagePath](#ImagePath)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[Name](#Name)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[UploadTransactionSize](#UploadTransactionSize)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ReconnectInterval](#ReconnectInterval)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[Timeout](#Timeout)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[CustomerByAddress](#CustomerByAddress)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[CustomerBySalesAmount](#CustomerBySalesAmount)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[CustomerBySalesAmountDayLimit](#CustomerBySalesAmountDayLimit)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[CustomerBySalesAmountNumLimit](#CustomerBySalesAmountNumLimit)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[CustomerByVisits](#CustomerByVisits)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[CustomerByVisitsDayLimit](#CustomerByVisitsDayLimit)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[CustomerByVisitsNumLimit](#CustomerByVisitsNumLimit)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[LimitAssortedProducts](#LimitAssortedProducts)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[LimitAvailableCustomers](#LimitAvailableCustomers)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductSalesAmountLimit](#ProductSalesAmountLimit)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductSalesAmountLimitDays](#ProductSalesAmountLimitDays)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductSalesQuantityLimit](#ProductSalesQuantityLimit)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductSalesQuantityLimitDays](#ProductSalesQuantityLimitDays)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductsArrivalLimit](#ProductsArrivalLimit)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductsArrivalLimitDays](#ProductsArrivalLimitDays)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductsByRecentArrival](#ProductsByRecentArrival)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductsBySalesAmount](#ProductsBySalesAmount)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductsBySalesQuantity](#ProductsBySalesQuantity)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[ProductsBySpecificCategory](#ProductsBySpecificCategory)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[TrxUploadInterval](#TrxUploadInterval)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[DirAddressBook_Name](#DirAddressBook_Name)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[RetailAssortmentTable_AssortmentID](#RetailAssortmentTable_AssortmentID)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[PromptOnSeamlessOffline](#PromptOnSeamlessOffline)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[RetryCountToOffline](#RetryCountToOffline)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[AllowManualOfflineBeforeSignIn](#AllowManualOfflineBeforeSignIn)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[EnableAdvancedOfflineSwitching](#EnableAdvancedOfflineSwitching)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[SystemHealthCheckInterval](#SystemHealthCheckInterval)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[PauseOfflineSync](#PauseOfflineSync)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|
|[BackingTable_RetailOfflineProfileRelationshipId](#BackingTable_RetailOfflineProfileRelationshipId)||<a href="RetailOfflineProfileEntity.md" target="_blank">ChannelManagement/RetailOfflineProfileEntity</a>|

### <a href=#AddressBook name="AddressBook">AddressBook</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offline customer address book</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBook attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offline customer address book</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Assortment name="Assortment">Assortment</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offline assortment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Assortment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offline assortment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckNewDBInterval name="CheckNewDBInterval">CheckNewDBInterval</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckNewDBInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DBExportPath name="DBExportPath">DBExportPath</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DBExportPath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImagePath name="ImagePath">ImagePath</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImagePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UploadTransactionSize name="UploadTransactionSize">UploadTransactionSize</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UploadTransactionSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReconnectInterval name="ReconnectInterval">ReconnectInterval</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconnectInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Timeout name="Timeout">Timeout</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timeout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerByAddress name="CustomerByAddress">CustomerByAddress</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerByAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerBySalesAmount name="CustomerBySalesAmount">CustomerBySalesAmount</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerBySalesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerBySalesAmountDayLimit name="CustomerBySalesAmountDayLimit">CustomerBySalesAmountDayLimit</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerBySalesAmountDayLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerBySalesAmountNumLimit name="CustomerBySalesAmountNumLimit">CustomerBySalesAmountNumLimit</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerBySalesAmountNumLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerByVisits name="CustomerByVisits">CustomerByVisits</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerByVisits attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerByVisitsDayLimit name="CustomerByVisitsDayLimit">CustomerByVisitsDayLimit</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerByVisitsDayLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerByVisitsNumLimit name="CustomerByVisitsNumLimit">CustomerByVisitsNumLimit</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerByVisitsNumLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LimitAssortedProducts name="LimitAssortedProducts">LimitAssortedProducts</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitAssortedProducts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LimitAvailableCustomers name="LimitAvailableCustomers">LimitAvailableCustomers</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitAvailableCustomers attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSalesAmountLimit name="ProductSalesAmountLimit">ProductSalesAmountLimit</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesAmountLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSalesAmountLimitDays name="ProductSalesAmountLimitDays">ProductSalesAmountLimitDays</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesAmountLimitDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSalesQuantityLimit name="ProductSalesQuantityLimit">ProductSalesQuantityLimit</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesQuantityLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSalesQuantityLimitDays name="ProductSalesQuantityLimitDays">ProductSalesQuantityLimitDays</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesQuantityLimitDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductsArrivalLimit name="ProductsArrivalLimit">ProductsArrivalLimit</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsArrivalLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductsArrivalLimitDays name="ProductsArrivalLimitDays">ProductsArrivalLimitDays</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsArrivalLimitDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductsByRecentArrival name="ProductsByRecentArrival">ProductsByRecentArrival</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsByRecentArrival attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductsBySalesAmount name="ProductsBySalesAmount">ProductsBySalesAmount</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsBySalesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductsBySalesQuantity name="ProductsBySalesQuantity">ProductsBySalesQuantity</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsBySalesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductsBySpecificCategory name="ProductsBySpecificCategory">ProductsBySpecificCategory</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductsBySpecificCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrxUploadInterval name="TrxUploadInterval">TrxUploadInterval</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrxUploadInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirAddressBook_Name name="DirAddressBook_Name">DirAddressBook_Name</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirAddressBook_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailAssortmentTable_AssortmentID name="RetailAssortmentTable_AssortmentID">RetailAssortmentTable_AssortmentID</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailAssortmentTable_AssortmentID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PromptOnSeamlessOffline name="PromptOnSeamlessOffline">PromptOnSeamlessOffline</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prompt on seamless offline</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptOnSeamlessOffline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prompt on seamless offline</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetryCountToOffline name="RetryCountToOffline">RetryCountToOffline</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retry count to offline</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetryCountToOffline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retry count to offline</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowManualOfflineBeforeSignIn name="AllowManualOfflineBeforeSignIn">AllowManualOfflineBeforeSignIn</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowManualOfflineBeforeSignIn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableAdvancedOfflineSwitching name="EnableAdvancedOfflineSwitching">EnableAdvancedOfflineSwitching</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableAdvancedOfflineSwitching attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SystemHealthCheckInterval name="SystemHealthCheckInterval">SystemHealthCheckInterval</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemHealthCheckInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PauseOfflineSync name="PauseOfflineSync">PauseOfflineSync</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PauseOfflineSync attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailOfflineProfileRelationshipId name="BackingTable_RetailOfflineProfileRelationshipId">BackingTable_RetailOfflineProfileRelationshipId</a>

First included in: ChannelManagement/RetailOfflineProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailOfflineProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/ChannelManagement/Miscellaneous/RetailOfflineProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/Miscellaneous/RetailOfflineProfile.cdm.json/RetailOfflineProfile</a></td><td><a href="../../../Tables/Commerce/ChannelManagement/Miscellaneous/RetailOfflineProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
