---
title: DirPartyV2Entity in GAB - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Global address book V2 in GAB(DirPartyV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/GAB/DirPartyV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Global address book V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PartyNumber](#PartyNumber)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PartyType](#PartyType)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[NameAlias](#NameAlias)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[KnownAs](#KnownAs)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[LanguageId](#LanguageId)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressBooks](#AddressBooks)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[OrganizationName](#OrganizationName)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[OrganizationABCCode](#OrganizationABCCode)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[OrganizationNumOfEmployees](#OrganizationNumOfEmployees)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[OrganizationNumber](#OrganizationNumber)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[OrganizationPhoneticName](#OrganizationPhoneticName)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonFirstName](#PersonFirstName)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonMiddleName](#PersonMiddleName)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonLastNamePrefix](#PersonLastNamePrefix)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonLastName](#PersonLastName)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonInitials](#PersonInitials)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonPersonalSuffix](#PersonPersonalSuffix)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonPersonalTitle](#PersonPersonalTitle)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonProfessionalTitle](#PersonProfessionalTitle)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonProfessionalSuffix](#PersonProfessionalSuffix)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonPhoneticFirstName](#PersonPhoneticFirstName)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonPhoneticLastName](#PersonPhoneticLastName)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonPhoneticMiddleName](#PersonPhoneticMiddleName)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonGender](#PersonGender)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonMaritalStatus](#PersonMaritalStatus)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonHobbies](#PersonHobbies)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonChildrenNames](#PersonChildrenNames)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonAnniversaryDay](#PersonAnniversaryDay)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonAnniversaryMonth](#PersonAnniversaryMonth)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonAnniversaryYear](#PersonAnniversaryYear)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonBirthDay](#PersonBirthDay)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonBirthMonth](#PersonBirthMonth)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PersonBirthYear](#PersonBirthYear)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[LegalEntityDataArea](#LegalEntityDataArea)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[OperatingUnitType](#OperatingUnitType)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[OperatingUnitTypeStr](#OperatingUnitTypeStr)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[TeamType](#TeamType)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[TeamDescription](#TeamDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[TeamMembershipCriterion](#TeamMembershipCriterion)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[FullPrimaryAddress](#FullPrimaryAddress)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressCountryRegionId](#AddressCountryRegionId)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressCountryRegionISOCode](#AddressCountryRegionISOCode)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressStreet](#AddressStreet)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressCity](#AddressCity)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressCounty](#AddressCounty)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressState](#AddressState)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressLatitude](#AddressLatitude)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressLongitude](#AddressLongitude)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressTimeZone](#AddressTimeZone)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressValidFrom](#AddressValidFrom)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressValidTo](#AddressValidTo)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressLocationId](#AddressLocationId)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressLocationRoles](#AddressLocationRoles)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressIsPrivate](#AddressIsPrivate)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[AddressDescription](#AddressDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactEmail](#PrimaryContactEmail)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactEmailDescription](#PrimaryContactEmailDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactEmailIsIM](#PrimaryContactEmailIsIM)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactEmailIsPrivate](#PrimaryContactEmailIsPrivate)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactEmailPurpose](#PrimaryContactEmailPurpose)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactFax](#PrimaryContactFax)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactFaxDescription](#PrimaryContactFaxDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactFaxExtension](#PrimaryContactFaxExtension)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactFaxIsPrivate](#PrimaryContactFaxIsPrivate)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactFaxPurpose](#PrimaryContactFaxPurpose)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactPhone](#PrimaryContactPhone)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactPhoneDescription](#PrimaryContactPhoneDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactPhoneExtension](#PrimaryContactPhoneExtension)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactPhoneIsMobile](#PrimaryContactPhoneIsMobile)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactPhoneIsPrivate](#PrimaryContactPhoneIsPrivate)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactPhonePurpose](#PrimaryContactPhonePurpose)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactTelex](#PrimaryContactTelex)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactTelexDescription](#PrimaryContactTelexDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactTelexIsPrivate](#PrimaryContactTelexIsPrivate)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactTelexPurpose](#PrimaryContactTelexPurpose)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactURL](#PrimaryContactURL)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactURLDescription](#PrimaryContactURLDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactURLIsPrivate](#PrimaryContactURLIsPrivate)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactURLPurpose](#PrimaryContactURLPurpose)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactFacebook](#PrimaryContactFacebook)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactFacebookDescription](#PrimaryContactFacebookDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactFacebookIsPrivate](#PrimaryContactFacebookIsPrivate)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactFacebookPurpose](#PrimaryContactFacebookPurpose)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactLinkedIn](#PrimaryContactLinkedIn)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactLinkedInDescription](#PrimaryContactLinkedInDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactLinkedInIsPrivate](#PrimaryContactLinkedInIsPrivate)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactLinkedInPurpose](#PrimaryContactLinkedInPurpose)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactTwitter](#PrimaryContactTwitter)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactTwitterDescription](#PrimaryContactTwitterDescription)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactTwitterIsPrivate](#PrimaryContactTwitterIsPrivate)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryContactTwitterPurpose](#PrimaryContactTwitterPurpose)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[ElectronicLocationId](#ElectronicLocationId)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[PrimaryAddressLocation](#PrimaryAddressLocation)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[IsPrimaryAddressLocationOwner](#IsPrimaryAddressLocationOwner)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|
|[BackingTable_DirPartyBaseEntityRelationshipId](#BackingTable_DirPartyBaseEntityRelationshipId)||<a href="DirPartyV2Entity.md" target="_blank">GAB/DirPartyV2Entity</a>|

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PartyType name="PartyType">PartyType</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NameAlias name="NameAlias">NameAlias</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameAlias attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KnownAs name="KnownAs">KnownAs</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Known as</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KnownAs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Known as</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBooks name="AddressBooks">AddressBooks</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBooks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationName name="OrganizationName">OrganizationName</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationABCCode name="OrganizationABCCode">OrganizationABCCode</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationABCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationNumOfEmployees name="OrganizationNumOfEmployees">OrganizationNumOfEmployees</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationNumOfEmployees attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationNumber name="OrganizationNumber">OrganizationNumber</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationPhoneticName name="OrganizationPhoneticName">OrganizationPhoneticName</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationPhoneticName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonFirstName name="PersonFirstName">PersonFirstName</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonMiddleName name="PersonMiddleName">PersonMiddleName</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonMiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonLastNamePrefix name="PersonLastNamePrefix">PersonLastNamePrefix</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonLastNamePrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonLastName name="PersonLastName">PersonLastName</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonInitials name="PersonInitials">PersonInitials</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonInitials attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPersonalSuffix name="PersonPersonalSuffix">PersonPersonalSuffix</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPersonalSuffix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPersonalTitle name="PersonPersonalTitle">PersonPersonalTitle</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPersonalTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonProfessionalTitle name="PersonProfessionalTitle">PersonProfessionalTitle</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonProfessionalTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonProfessionalSuffix name="PersonProfessionalSuffix">PersonProfessionalSuffix</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonProfessionalSuffix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPhoneticFirstName name="PersonPhoneticFirstName">PersonPhoneticFirstName</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPhoneticFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPhoneticLastName name="PersonPhoneticLastName">PersonPhoneticLastName</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPhoneticLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPhoneticMiddleName name="PersonPhoneticMiddleName">PersonPhoneticMiddleName</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPhoneticMiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonGender name="PersonGender">PersonGender</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonGender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonMaritalStatus name="PersonMaritalStatus">PersonMaritalStatus</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonMaritalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonHobbies name="PersonHobbies">PersonHobbies</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonHobbies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonChildrenNames name="PersonChildrenNames">PersonChildrenNames</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonChildrenNames attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonAnniversaryDay name="PersonAnniversaryDay">PersonAnniversaryDay</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonAnniversaryDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonAnniversaryMonth name="PersonAnniversaryMonth">PersonAnniversaryMonth</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonAnniversaryMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonAnniversaryYear name="PersonAnniversaryYear">PersonAnniversaryYear</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonAnniversaryYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonBirthDay name="PersonBirthDay">PersonBirthDay</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonBirthDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonBirthMonth name="PersonBirthMonth">PersonBirthMonth</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonBirthMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonBirthYear name="PersonBirthYear">PersonBirthYear</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonBirthYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityDataArea name="LegalEntityDataArea">LegalEntityDataArea</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitType name="OperatingUnitType">OperatingUnitType</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitTypeStr name="OperatingUnitTypeStr">OperatingUnitTypeStr</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitTypeStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TeamType name="TeamType">TeamType</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TeamType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TeamDescription name="TeamDescription">TeamDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TeamDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TeamMembershipCriterion name="TeamMembershipCriterion">TeamMembershipCriterion</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TeamMembershipCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FullPrimaryAddress name="FullPrimaryAddress">FullPrimaryAddress</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullPrimaryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressCountryRegionId name="AddressCountryRegionId">AddressCountryRegionId</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressCounty name="AddressCounty">AddressCounty</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressState name="AddressState">AddressState</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressLatitude name="AddressLatitude">AddressLatitude</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressTimeZone name="AddressTimeZone">AddressTimeZone</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

First included in: GAB/DirPartyV2Entity (this entity)  

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

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressLocationId name="AddressLocationId">AddressLocationId</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressLocationRoles name="AddressLocationRoles">AddressLocationRoles</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#AddressIsPrivate name="AddressIsPrivate">AddressIsPrivate</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDescription name="AddressDescription">AddressDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactEmail name="PrimaryContactEmail">PrimaryContactEmail</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactEmailDescription name="PrimaryContactEmailDescription">PrimaryContactEmailDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary email description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary email description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailIsIM name="PrimaryContactEmailIsIM">PrimaryContactEmailIsIM</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactEmailIsPrivate name="PrimaryContactEmailIsPrivate">PrimaryContactEmailIsPrivate</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailPurpose name="PrimaryContactEmailPurpose">PrimaryContactEmailPurpose</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactFax name="PrimaryContactFax">PrimaryContactFax</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactFaxDescription name="PrimaryContactFaxDescription">PrimaryContactFaxDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary fax description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary fax description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxExtension name="PrimaryContactFaxExtension">PrimaryContactFaxExtension</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary fax extension</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary fax extension</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxIsPrivate name="PrimaryContactFaxIsPrivate">PrimaryContactFaxIsPrivate</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxPurpose name="PrimaryContactFaxPurpose">PrimaryContactFaxPurpose</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactPhone name="PrimaryContactPhone">PrimaryContactPhone</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactPhoneDescription name="PrimaryContactPhoneDescription">PrimaryContactPhoneDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary phone description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary phone description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneExtension name="PrimaryContactPhoneExtension">PrimaryContactPhoneExtension</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary phone extension</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary phone extension</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneIsMobile name="PrimaryContactPhoneIsMobile">PrimaryContactPhoneIsMobile</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactPhoneIsPrivate name="PrimaryContactPhoneIsPrivate">PrimaryContactPhoneIsPrivate</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhonePurpose name="PrimaryContactPhonePurpose">PrimaryContactPhonePurpose</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactTelex name="PrimaryContactTelex">PrimaryContactTelex</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactTelexDescription name="PrimaryContactTelexDescription">PrimaryContactTelexDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary telex description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelexDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary telex description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTelexIsPrivate name="PrimaryContactTelexIsPrivate">PrimaryContactTelexIsPrivate</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelexIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTelexPurpose name="PrimaryContactTelexPurpose">PrimaryContactTelexPurpose</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactURL name="PrimaryContactURL">PrimaryContactURL</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactURLDescription name="PrimaryContactURLDescription">PrimaryContactURLDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary URL description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary URL description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLIsPrivate name="PrimaryContactURLIsPrivate">PrimaryContactURLIsPrivate</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLPurpose name="PrimaryContactURLPurpose">PrimaryContactURLPurpose</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactFacebook name="PrimaryContactFacebook">PrimaryContactFacebook</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactFacebookDescription name="PrimaryContactFacebookDescription">PrimaryContactFacebookDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactFacebookIsPrivate name="PrimaryContactFacebookIsPrivate">PrimaryContactFacebookIsPrivate</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactFacebookPurpose name="PrimaryContactFacebookPurpose">PrimaryContactFacebookPurpose</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactLinkedIn name="PrimaryContactLinkedIn">PrimaryContactLinkedIn</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactLinkedInDescription name="PrimaryContactLinkedInDescription">PrimaryContactLinkedInDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactLinkedInIsPrivate name="PrimaryContactLinkedInIsPrivate">PrimaryContactLinkedInIsPrivate</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactLinkedInPurpose name="PrimaryContactLinkedInPurpose">PrimaryContactLinkedInPurpose</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactTwitter name="PrimaryContactTwitter">PrimaryContactTwitter</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactTwitterDescription name="PrimaryContactTwitterDescription">PrimaryContactTwitterDescription</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactTwitterIsPrivate name="PrimaryContactTwitterIsPrivate">PrimaryContactTwitterIsPrivate</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#PrimaryContactTwitterPurpose name="PrimaryContactTwitterPurpose">PrimaryContactTwitterPurpose</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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

### <a href=#ElectronicLocationId name="ElectronicLocationId">ElectronicLocationId</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocation name="PrimaryAddressLocation">PrimaryAddressLocation</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryAddressLocationOwner name="IsPrimaryAddressLocationOwner">IsPrimaryAddressLocationOwner</a>

First included in: GAB/DirPartyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryAddressLocationOwner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DirPartyBaseEntityRelationshipId name="BackingTable_DirPartyBaseEntityRelationshipId">BackingTable_DirPartyBaseEntityRelationshipId</a>

First included in: GAB/DirPartyV2Entity (this entity)  

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
