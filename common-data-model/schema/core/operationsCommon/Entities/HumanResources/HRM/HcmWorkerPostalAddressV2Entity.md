---
title: HcmWorkerPostalAddressV2Entity in HRM - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Worker postal addresses V2 in HRM(HcmWorkerPostalAddressV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmWorkerPostalAddressV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Worker postal addresses V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PersonnelNumber](#PersonnelNumber)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[FormattedAddress](#FormattedAddress)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AttentionToAddressLine](#AttentionToAddressLine)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[BuildingCompliment](#BuildingCompliment)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressApartment](#AddressApartment)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressBuilding](#AddressBuilding)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressCity](#AddressCity)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressCityInKana](#AddressCityInKana)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressCountryRegionId](#AddressCountryRegionId)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressCountryRegionISOCode](#AddressCountryRegionISOCode)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressCountyId](#AddressCountyId)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressDescription](#AddressDescription)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressLatitude](#AddressLatitude)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressLocationId](#AddressLocationId)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressLongitude](#AddressLongitude)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressPostBox](#AddressPostBox)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressState](#AddressState)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressStreet](#AddressStreet)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressStreetInKana](#AddressStreetInKana)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressStreetNumber](#AddressStreetNumber)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressTimeZone](#AddressTimeZone)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[AddressLocationRoles](#AddressLocationRoles)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[DunsNumber](#DunsNumber)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsLocationOwner](#IsLocationOwner)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsPostalAddress](#IsPostalAddress)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsPrimary](#IsPrimary)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsPrimaryTaxRegistration](#IsPrimaryTaxRegistration)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsPrivate](#IsPrivate)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsPrivatePostalAddress](#IsPrivatePostalAddress)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsRoleBusiness](#IsRoleBusiness)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsRoleDelivery](#IsRoleDelivery)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsRoleHome](#IsRoleHome)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[IsRoleInvoice](#IsRoleInvoice)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[Effective](#Effective)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[Expiration](#Expiration)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|
|[BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId](#BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId)||<a href="HcmWorkerPostalAddressV2Entity.md" target="_blank">HRM/HcmWorkerPostalAddressV2Entity</a>|

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedAddress name="FormattedAddress">FormattedAddress</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttentionToAddressLine name="AttentionToAddressLine">AttentionToAddressLine</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttentionToAddressLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuildingCompliment name="BuildingCompliment">BuildingCompliment</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressApartment name="AddressApartment">AddressApartment</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressApartment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBuilding name="AddressBuilding">AddressBuilding</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBuilding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCityInKana name="AddressCityInKana">AddressCityInKana</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionId name="AddressCountryRegionId">AddressCountryRegionId</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionISOCode name="AddressCountryRegionISOCode">AddressCountryRegionISOCode</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountyId name="AddressCountyId">AddressCountyId</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDescription name="AddressDescription">AddressDescription</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLatitude name="AddressLatitude">AddressLatitude</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationId name="AddressLocationId">AddressLocationId</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLongitude name="AddressLongitude">AddressLongitude</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressPostBox name="AddressPostBox">AddressPostBox</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressState name="AddressState">AddressState</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetInKana name="AddressStreetInKana">AddressStreetInKana</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetNumber name="AddressStreetNumber">AddressStreetNumber</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressTimeZone name="AddressTimeZone">AddressTimeZone</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationRoles name="AddressLocationRoles">AddressLocationRoles</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationRoles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DunsNumber name="DunsNumber">DunsNumber</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationOwner name="IsLocationOwner">IsLocationOwner</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationOwner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPostalAddress name="IsPostalAddress">IsPostalAddress</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimary name="IsPrimary">IsPrimary</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryTaxRegistration name="IsPrimaryTaxRegistration">IsPrimaryTaxRegistration</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryTaxRegistration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrivate name="IsPrivate">IsPrivate</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrivatePostalAddress name="IsPrivatePostalAddress">IsPrivatePostalAddress</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrivatePostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRoleBusiness name="IsRoleBusiness">IsRoleBusiness</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRoleBusiness attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRoleDelivery name="IsRoleDelivery">IsRoleDelivery</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRoleDelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRoleHome name="IsRoleHome">IsRoleHome</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRoleHome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRoleInvoice name="IsRoleInvoice">IsRoleInvoice</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRoleInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Effective name="Effective">Effective</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Effective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Expiration name="Expiration">Expiration</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Expiration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkerRelationshipId name="Relationship_WorkerRelationshipId">Relationship_WorkerRelationshipId</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId name="BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId">BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId</a>

First included in: HRM/HcmWorkerPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId attribute are listed below.</summary>

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
