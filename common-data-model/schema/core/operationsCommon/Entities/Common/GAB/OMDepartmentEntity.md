---
title: OMDepartmentEntity in GAB - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Department in GAB(OMDepartmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/GAB/OMDepartmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Department</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PartyType](#PartyType)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[KnownAs](#KnownAs)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[Language](#Language)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[Name](#Name)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[Memo](#Memo)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[SearchName](#SearchName)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PartyNumber](#PartyNumber)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[OrganizationType](#OrganizationType)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[OperatingUnitTypes](#OperatingUnitTypes)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressCountryRegionId](#PrimaryAddressCountryRegionId)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressCountryRegionISOCode](#PrimaryAddressCountryRegionISOCode)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressCounty](#PrimaryAddressCounty)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressCity](#PrimaryAddressCity)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressDescription](#PrimaryAddressDescription)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressValidFrom](#PrimaryAddressValidFrom)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressValidTo](#PrimaryAddressValidTo)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressZipCode](#PrimaryAddressZipCode)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressState](#PrimaryAddressState)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryAddressStreet](#PrimaryAddressStreet)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactEmail](#PrimaryContactEmail)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactEmailIsIM](#PrimaryContactEmailIsIM)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactFax](#PrimaryContactFax)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactPhone](#PrimaryContactPhone)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactPhoneExtension](#PrimaryContactPhoneExtension)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactPhoneIsMobile](#PrimaryContactPhoneIsMobile)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactTelex](#PrimaryContactTelex)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactURL](#PrimaryContactURL)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[AddressLocationRoles](#AddressLocationRoles)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactPhonePurpose](#PrimaryContactPhonePurpose)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactFaxPurpose](#PrimaryContactFaxPurpose)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactEmailPurpose](#PrimaryContactEmailPurpose)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactTelexPurpose](#PrimaryContactTelexPurpose)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactURLPurpose](#PrimaryContactURLPurpose)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactEmailDescription](#PrimaryContactEmailDescription)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactFaxDescription](#PrimaryContactFaxDescription)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactFaxExtension](#PrimaryContactFaxExtension)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactPhoneDescription](#PrimaryContactPhoneDescription)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactTelexDescription](#PrimaryContactTelexDescription)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactURLDescription](#PrimaryContactURLDescription)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactFacebookPurpose](#PrimaryContactFacebookPurpose)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactFacebookIsPrivate](#PrimaryContactFacebookIsPrivate)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactFacebookDescription](#PrimaryContactFacebookDescription)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactFacebook](#PrimaryContactFacebook)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactTwitterPurpose](#PrimaryContactTwitterPurpose)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactTwitterIsPrivate](#PrimaryContactTwitterIsPrivate)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactTwitterDescription](#PrimaryContactTwitterDescription)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactTwitter](#PrimaryContactTwitter)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactLinkedInPurpose](#PrimaryContactLinkedInPurpose)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactLinkedInIsPrivate](#PrimaryContactLinkedInIsPrivate)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactLinkedInDescription](#PrimaryContactLinkedInDescription)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[PrimaryContactLinkedIn](#PrimaryContactLinkedIn)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|
|[BackingTable_DirPartyBaseEntityRelationshipId](#BackingTable_DirPartyBaseEntityRelationshipId)||<a href="OMDepartmentEntity.md" target="_blank">GAB/OMDepartmentEntity</a>|

### <a href=#PartyType name="PartyType">PartyType</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KnownAs name="KnownAs">KnownAs</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KnownAs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Language name="Language">Language</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Language attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: GAB/OMDepartmentEntity (this entity)  

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

### <a href=#Memo name="Memo">Memo</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Memo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SearchName name="SearchName">SearchName</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: GAB/OMDepartmentEntity (this entity)  

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

### <a href=#OrganizationType name="OrganizationType">OrganizationType</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Department number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Department number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitTypes name="OperatingUnitTypes">OperatingUnitTypes</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitTypes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCountryRegionId name="PrimaryAddressCountryRegionId">PrimaryAddressCountryRegionId</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCountryRegionISOCode name="PrimaryAddressCountryRegionISOCode">PrimaryAddressCountryRegionISOCode</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCounty name="PrimaryAddressCounty">PrimaryAddressCounty</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCity name="PrimaryAddressCity">PrimaryAddressCity</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressDescription name="PrimaryAddressDescription">PrimaryAddressDescription</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressValidFrom name="PrimaryAddressValidFrom">PrimaryAddressValidFrom</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressValidTo name="PrimaryAddressValidTo">PrimaryAddressValidTo</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressZipCode name="PrimaryAddressZipCode">PrimaryAddressZipCode</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressState name="PrimaryAddressState">PrimaryAddressState</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStreet name="PrimaryAddressStreet">PrimaryAddressStreet</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmail name="PrimaryContactEmail">PrimaryContactEmail</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailIsIM name="PrimaryContactEmailIsIM">PrimaryContactEmailIsIM</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailIsIM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFax name="PrimaryContactFax">PrimaryContactFax</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhone name="PrimaryContactPhone">PrimaryContactPhone</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneExtension name="PrimaryContactPhoneExtension">PrimaryContactPhoneExtension</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneIsMobile name="PrimaryContactPhoneIsMobile">PrimaryContactPhoneIsMobile</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneIsMobile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTelex name="PrimaryContactTelex">PrimaryContactTelex</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelex attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURL name="PrimaryContactURL">PrimaryContactURL</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationRoles name="AddressLocationRoles">AddressLocationRoles</a>

First included in: GAB/OMDepartmentEntity (this entity)  

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

### <a href=#PrimaryContactPhonePurpose name="PrimaryContactPhonePurpose">PrimaryContactPhonePurpose</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhonePurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxPurpose name="PrimaryContactFaxPurpose">PrimaryContactFaxPurpose</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailPurpose name="PrimaryContactEmailPurpose">PrimaryContactEmailPurpose</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTelexPurpose name="PrimaryContactTelexPurpose">PrimaryContactTelexPurpose</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelexPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLPurpose name="PrimaryContactURLPurpose">PrimaryContactURLPurpose</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailDescription name="PrimaryContactEmailDescription">PrimaryContactEmailDescription</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxDescription name="PrimaryContactFaxDescription">PrimaryContactFaxDescription</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxExtension name="PrimaryContactFaxExtension">PrimaryContactFaxExtension</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneDescription name="PrimaryContactPhoneDescription">PrimaryContactPhoneDescription</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTelexDescription name="PrimaryContactTelexDescription">PrimaryContactTelexDescription</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelexDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLDescription name="PrimaryContactURLDescription">PrimaryContactURLDescription</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebookPurpose name="PrimaryContactFacebookPurpose">PrimaryContactFacebookPurpose</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebookPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebookIsPrivate name="PrimaryContactFacebookIsPrivate">PrimaryContactFacebookIsPrivate</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebookIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebookDescription name="PrimaryContactFacebookDescription">PrimaryContactFacebookDescription</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebookDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebook name="PrimaryContactFacebook">PrimaryContactFacebook</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebook attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitterPurpose name="PrimaryContactTwitterPurpose">PrimaryContactTwitterPurpose</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitterPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitterIsPrivate name="PrimaryContactTwitterIsPrivate">PrimaryContactTwitterIsPrivate</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitterIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitterDescription name="PrimaryContactTwitterDescription">PrimaryContactTwitterDescription</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitterDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitter name="PrimaryContactTwitter">PrimaryContactTwitter</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedInPurpose name="PrimaryContactLinkedInPurpose">PrimaryContactLinkedInPurpose</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedInPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedInIsPrivate name="PrimaryContactLinkedInIsPrivate">PrimaryContactLinkedInIsPrivate</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedInIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedInDescription name="PrimaryContactLinkedInDescription">PrimaryContactLinkedInDescription</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedInDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedIn name="PrimaryContactLinkedIn">PrimaryContactLinkedIn</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedIn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DirPartyBaseEntityRelationshipId name="BackingTable_DirPartyBaseEntityRelationshipId">BackingTable_DirPartyBaseEntityRelationshipId</a>

First included in: GAB/OMDepartmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DirPartyBaseEntityRelationshipId attribute are listed below.</summary>

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
