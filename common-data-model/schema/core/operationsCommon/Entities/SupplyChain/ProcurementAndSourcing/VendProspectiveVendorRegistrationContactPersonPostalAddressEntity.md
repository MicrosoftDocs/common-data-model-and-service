---
title: VendProspectiveVendorRegistrationContactPersonPostalAddressEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Prospective vendor registration contact person postal addresses in ProcurementAndSourcing(VendProspectiveVendorRegistrationContactPersonPostalAddressEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prospective vendor registration contact person postal addresses</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ContactPersonEmailAddress](#ContactPersonEmailAddress)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressDescription](#AddressDescription)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressLocationId](#AddressLocationId)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[FormattedAddress](#FormattedAddress)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressBuildingCompliment](#AddressBuildingCompliment)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressCity](#AddressCity)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressCountryRegionId](#AddressCountryRegionId)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressCountyId](#AddressCountyId)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[IsAddressPrivate](#IsAddressPrivate)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressLatitude](#AddressLatitude)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressLongitude](#AddressLongitude)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressPostBox](#AddressPostBox)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressStateId](#AddressStateId)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressStreet](#AddressStreet)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressStreetNumber](#AddressStreetNumber)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressTimeZone](#AddressTimeZone)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressValidFrom](#AddressValidFrom)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressValidTo](#AddressValidTo)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AttentionToAddressLine](#AttentionToAddressLine)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[IsLocationOwner](#IsLocationOwner)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[IsAddressPrimary](#IsAddressPrimary)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[IsPrimaryTaxRegistration](#IsPrimaryTaxRegistration)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[IsRoleBusiness](#IsRoleBusiness)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[IsRoleHome](#IsRoleHome)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[IsRoleDelivery](#IsRoleDelivery)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressLocationRoles](#AddressLocationRoles)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressCountryRegionISOCode](#AddressCountryRegionISOCode)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[VendorRegistrationId](#VendorRegistrationId)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressCityInKana](#AddressCityInKana)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[AddressStreetInKana](#AddressStreetInKana)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|
|[BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId](#BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId)||<a href="VendProspectiveVendorRegistrationContactPersonPostalAddressEntity.md" target="_blank">ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity</a>|

### <a href=#ContactPersonEmailAddress name="ContactPersonEmailAddress">ContactPersonEmailAddress</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact person email address</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonEmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contact person email address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDescription name="AddressDescription">AddressDescription</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressLocationId name="AddressLocationId">AddressLocationId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#FormattedAddress name="FormattedAddress">FormattedAddress</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressBuildingCompliment name="AddressBuildingCompliment">AddressBuildingCompliment</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressCountryRegionId name="AddressCountryRegionId">AddressCountryRegionId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressCountyId name="AddressCountyId">AddressCountyId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#IsAddressPrivate name="IsAddressPrivate">IsAddressPrivate</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLatitude name="AddressLatitude">AddressLatitude</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressLongitude name="AddressLongitude">AddressLongitude</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressStateId name="AddressStateId">AddressStateId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressStreetNumber name="AddressStreetNumber">AddressStreetNumber</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressValidFrom name="AddressValidFrom">AddressValidFrom</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidTo name="AddressValidTo">AddressValidTo</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AttentionToAddressLine name="AttentionToAddressLine">AttentionToAddressLine</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#IsAddressPrimary name="IsAddressPrimary">IsAddressPrimary</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAddressPrimary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryTaxRegistration name="IsPrimaryTaxRegistration">IsPrimaryTaxRegistration</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#IsRoleBusiness name="IsRoleBusiness">IsRoleBusiness</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#IsRoleHome name="IsRoleHome">IsRoleHome</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#IsRoleDelivery name="IsRoleDelivery">IsRoleDelivery</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressLocationRoles name="AddressLocationRoles">AddressLocationRoles</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressCountryRegionISOCode name="AddressCountryRegionISOCode">AddressCountryRegionISOCode</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#VendorRegistrationId name="VendorRegistrationId">VendorRegistrationId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prospective vendor registration number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorRegistrationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prospective vendor registration number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCityInKana name="AddressCityInKana">AddressCityInKana</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#AddressStreetInKana name="AddressStreetInKana">AddressStreetInKana</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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

### <a href=#BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId name="BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId">BackingTable_DirPartyLocationPostalAddressV2EntityRelationshipId</a>

First included in: ProcurementAndSourcing/VendProspectiveVendorRegistrationContactPersonPostalAddressEntity (this entity)  

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
