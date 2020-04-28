---
title: VendVendorPostalAddressEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Vendor postal addresses

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsPayable/VendVendorPostalAddressEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor postal addresses</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[VendorLegalEntityId](#VendorLegalEntityId)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[FormattedAddress](#FormattedAddress)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AttentionToAddressLine](#AttentionToAddressLine)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[BuildingCompliment](#BuildingCompliment)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressCity](#AddressCity)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressCityInKana](#AddressCityInKana)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressCountryRegionId](#AddressCountryRegionId)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressCountryRegionISOCode](#AddressCountryRegionISOCode)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressCountyId](#AddressCountyId)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressDescription](#AddressDescription)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressLatitude](#AddressLatitude)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressLocationId](#AddressLocationId)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressLongitude](#AddressLongitude)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressPostBox](#AddressPostBox)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressStateId](#AddressStateId)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressStreet](#AddressStreet)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressStreetInKana](#AddressStreetInKana)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressStreetNumber](#AddressStreetNumber)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressTimeZone](#AddressTimeZone)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressValidFrom](#AddressValidFrom)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressValidTo](#AddressValidTo)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[AddressLocationRoles](#AddressLocationRoles)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsLocationOwner](#IsLocationOwner)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsPostalAddress](#IsPostalAddress)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsPrimary](#IsPrimary)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsPrimaryTaxRegistration](#IsPrimaryTaxRegistration)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsPrivate](#IsPrivate)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsPrivatePostalAddress](#IsPrivatePostalAddress)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsRoleBusiness](#IsRoleBusiness)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsRoleDelivery](#IsRoleDelivery)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsRoleHome](#IsRoleHome)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[IsRoleInvoice](#IsRoleInvoice)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId](#BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendVendorPostalAddressEntity.md" target="_blank">AccountsPayable/VendVendorPostalAddressEntity</a>|

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorLegalEntityId name="VendorLegalEntityId">VendorLegalEntityId</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedAddress name="FormattedAddress">FormattedAddress</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttentionToAddressLine name="AttentionToAddressLine">AttentionToAddressLine</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttentionToAddressLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuildingCompliment name="BuildingCompliment">BuildingCompliment</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCityInKana name="AddressCityInKana">AddressCityInKana</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionId name="AddressCountryRegionId">AddressCountryRegionId</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionISOCode name="AddressCountryRegionISOCode">AddressCountryRegionISOCode</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountyId name="AddressCountyId">AddressCountyId</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDescription name="AddressDescription">AddressDescription</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLatitude name="AddressLatitude">AddressLatitude</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationId name="AddressLocationId">AddressLocationId</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLongitude name="AddressLongitude">AddressLongitude</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressPostBox name="AddressPostBox">AddressPostBox</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStateId name="AddressStateId">AddressStateId</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetInKana name="AddressStreetInKana">AddressStreetInKana</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetNumber name="AddressStreetNumber">AddressStreetNumber</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressTimeZone name="AddressTimeZone">AddressTimeZone</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidFrom name="AddressValidFrom">AddressValidFrom</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidTo name="AddressValidTo">AddressValidTo</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationRoles name="AddressLocationRoles">AddressLocationRoles</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationRoles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationOwner name="IsLocationOwner">IsLocationOwner</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationOwner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPostalAddress name="IsPostalAddress">IsPostalAddress</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimary name="IsPrimary">IsPrimary</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryTaxRegistration name="IsPrimaryTaxRegistration">IsPrimaryTaxRegistration</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryTaxRegistration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrivate name="IsPrivate">IsPrivate</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrivatePostalAddress name="IsPrivatePostalAddress">IsPrivatePostalAddress</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrivatePostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRoleBusiness name="IsRoleBusiness">IsRoleBusiness</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRoleBusiness attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRoleDelivery name="IsRoleDelivery">IsRoleDelivery</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRoleDelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRoleHome name="IsRoleHome">IsRoleHome</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRoleHome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRoleInvoice name="IsRoleInvoice">IsRoleInvoice</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRoleInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId name="BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId">BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsPayable/VendVendorPostalAddressEntity (this entity)  

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
