---
title: DirPartyLocationPostalAddressV2Entity in GAB - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Party postal address V2 in GAB(DirPartyLocationPostalAddressV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/GAB/DirPartyLocationPostalAddressV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Party postal address V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AttentionToAddressLine](#AttentionToAddressLine)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsLocationOwner](#IsLocationOwner)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsPostalAddress](#IsPostalAddress)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsPrimary](#IsPrimary)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsPrimaryTaxRegistration](#IsPrimaryTaxRegistration)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsPrivate](#IsPrivate)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsRoleBusiness](#IsRoleBusiness)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsRoleDelivery](#IsRoleDelivery)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsRoleHome](#IsRoleHome)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsRoleInvoice](#IsRoleInvoice)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Location](#Location)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Party](#Party)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[PartyNumber](#PartyNumber)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Address](#Address)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Apartment_RU](#Apartment_RU)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Building_RU](#Building_RU)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[BuildingCompliment](#BuildingCompliment)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[City](#City)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[CityInKana](#CityInKana)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[CountryRegionISOCode](#CountryRegionISOCode)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[County](#County)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Description](#Description)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[DistrictName](#DistrictName)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[DunsNumber](#DunsNumber)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[IsPrivatePostalAddress](#IsPrivatePostalAddress)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Latitude](#Latitude)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[LocationId](#LocationId)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Longitude](#Longitude)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[PostBox](#PostBox)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[State](#State)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Street](#Street)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[StreetInKana](#StreetInKana)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[StreetNumber](#StreetNumber)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[TimeZone](#TimeZone)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[ValidFrom](#ValidFrom)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[ValidTo](#ValidTo)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[ZipCode](#ZipCode)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[Roles](#Roles)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[ResolveDuplicateAddress](#ResolveDuplicateAddress)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[TaxGroup](#TaxGroup)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|
|[BackingTable_LogisticsPostalAddressBaseEntityRelationshipId](#BackingTable_LogisticsPostalAddressBaseEntityRelationshipId)||<a href="DirPartyLocationPostalAddressV2Entity.md" target="_blank">GAB/DirPartyLocationPostalAddressV2Entity</a>|

### <a href=#AttentionToAddressLine name="AttentionToAddressLine">AttentionToAddressLine</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

### <a href=#IsLocationOwner name="IsLocationOwner">IsLocationOwner</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

### <a href=#IsRoleBusiness name="IsRoleBusiness">IsRoleBusiness</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

### <a href=#Location name="Location">Location</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Party name="Party">Party</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Party attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Address name="Address">Address</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Address attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Apartment_RU name="Apartment_RU">Apartment_RU</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Apartment_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Building_RU name="Building_RU">Building_RU</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Building_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuildingCompliment name="BuildingCompliment">BuildingCompliment</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

### <a href=#City name="City">City</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the City attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CityInKana name="CityInKana">CityInKana</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionISOCode name="CountryRegionISOCode">CountryRegionISOCode</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#County name="County">County</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the County attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

### <a href=#DistrictName name="DistrictName">DistrictName</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DunsNumber name="DunsNumber">DunsNumber</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

### <a href=#IsPrivatePostalAddress name="IsPrivatePostalAddress">IsPrivatePostalAddress</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

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

### <a href=#Latitude name="Latitude">Latitude</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Latitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationId name="LocationId">LocationId</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Longitude name="Longitude">Longitude</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Longitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostBox name="PostBox">PostBox</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Street name="Street">Street</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Street attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StreetInKana name="StreetInKana">StreetInKana</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StreetNumber name="StreetNumber">StreetNumber</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeZone name="TimeZone">TimeZone</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZipCode name="ZipCode">ZipCode</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Roles name="Roles">Roles</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Roles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResolveDuplicateAddress name="ResolveDuplicateAddress">ResolveDuplicateAddress</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResolveDuplicateAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LogisticsPostalAddressBaseEntityRelationshipId name="BackingTable_LogisticsPostalAddressBaseEntityRelationshipId">BackingTable_LogisticsPostalAddressBaseEntityRelationshipId</a>

First included in: GAB/DirPartyLocationPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LogisticsPostalAddressBaseEntityRelationshipId attribute are listed below.</summary>

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
