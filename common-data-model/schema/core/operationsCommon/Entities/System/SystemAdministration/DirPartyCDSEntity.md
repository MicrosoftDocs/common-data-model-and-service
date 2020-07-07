---
title: DirPartyCDSEntity in SystemAdministration - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# CDS Parties in SystemAdministration

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/SystemAdministration/DirPartyCDSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDS Parties</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PartyNumber](#PartyNumber)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PartyType](#PartyType)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[NameAlias](#NameAlias)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[KnownAs](#KnownAs)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[LanguageId](#LanguageId)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[AddressBooks](#AddressBooks)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[OrganizationName](#OrganizationName)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[OrganizationABCCode](#OrganizationABCCode)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[OrganizationNumOfEmployees](#OrganizationNumOfEmployees)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[OrganizationNumber](#OrganizationNumber)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[OrganizationPhoneticName](#OrganizationPhoneticName)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonFirstName](#PersonFirstName)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonMiddleName](#PersonMiddleName)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonLastNamePrefix](#PersonLastNamePrefix)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonLastName](#PersonLastName)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonInitials](#PersonInitials)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonPersonalSuffix](#PersonPersonalSuffix)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonPersonalTitle](#PersonPersonalTitle)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonProfessionalTitle](#PersonProfessionalTitle)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonProfessionalSuffix](#PersonProfessionalSuffix)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonPhoneticFirstName](#PersonPhoneticFirstName)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonPhoneticMiddleName](#PersonPhoneticMiddleName)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonPhoneticLastName](#PersonPhoneticLastName)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonGender](#PersonGender)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonMaritalStatus](#PersonMaritalStatus)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonHobbies](#PersonHobbies)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonChildrenNames](#PersonChildrenNames)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonAnniversaryDay](#PersonAnniversaryDay)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonAnniversaryMonth](#PersonAnniversaryMonth)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonAnniversaryYear](#PersonAnniversaryYear)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonBirthDay](#PersonBirthDay)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonBirthMonth](#PersonBirthMonth)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[PersonBirthYear](#PersonBirthYear)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[DirPersonNameRecId](#DirPersonNameRecId)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|
|[BackingTable_DirPartyBaseEntityRelationshipId](#BackingTable_DirPartyBaseEntityRelationshipId)||<a href="DirPartyCDSEntity.md" target="_blank">SystemAdministration/DirPartyCDSEntity</a>|

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyType name="PartyType">PartyType</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

### <a href=#NameAlias name="NameAlias">NameAlias</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

### <a href=#AddressBooks name="AddressBooks">AddressBooks</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationABCCode name="OrganizationABCCode">OrganizationABCCode</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

### <a href=#PersonPhoneticMiddleName name="PersonPhoneticMiddleName">PersonPhoneticMiddleName</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

### <a href=#PersonPhoneticLastName name="PersonPhoneticLastName">PersonPhoneticLastName</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

### <a href=#PersonGender name="PersonGender">PersonGender</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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

### <a href=#DirPersonNameRecId name="DirPersonNameRecId">DirPersonNameRecId</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirPersonNameRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DirPartyBaseEntityRelationshipId name="BackingTable_DirPartyBaseEntityRelationshipId">BackingTable_DirPartyBaseEntityRelationshipId</a>

First included in: SystemAdministration/DirPartyCDSEntity (this entity)  

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
