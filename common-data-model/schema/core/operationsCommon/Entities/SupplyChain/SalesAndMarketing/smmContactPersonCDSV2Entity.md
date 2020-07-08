---
title: smmContactPersonCDSV2Entity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# CDS Contacts V2 in SalesAndMarketing(smmContactPersonCDSV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/smmContactPersonCDSV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDS Contacts V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ContactPersonPartyNumber](#ContactPersonPartyNumber)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[AssociatedPartyNumber](#AssociatedPartyNumber)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[BirthDay](#BirthDay)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[BirthMonth](#BirthMonth)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[BirthYear](#BirthYear)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressCity](#PrimaryAddressCity)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressCountryRegionId](#PrimaryAddressCountryRegionId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressCountryRegionISOCode](#PrimaryAddressCountryRegionISOCode)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressCountyId](#PrimaryAddressCountyId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressDescription](#PrimaryAddressDescription)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressLocationRoles](#PrimaryAddressLocationRoles)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressStateId](#PrimaryAddressStateId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressStreet](#PrimaryAddressStreet)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressStreetNumber](#PrimaryAddressStreetNumber)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressZipCode](#PrimaryAddressZipCode)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[EmploymentDepartment](#EmploymentDepartment)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[Notes](#Notes)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[Gender](#Gender)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[FirstName](#FirstName)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[GovernmentIdentificationNumber](#GovernmentIdentificationNumber)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[IsReceivingDirectMail](#IsReceivingDirectMail)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[MaritalStatus](#MaritalStatus)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[MiddleName](#MiddleName)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[ContactPersonPartyType](#ContactPersonPartyType)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryEmailAddress](#PrimaryEmailAddress)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryPhoneNumber](#PrimaryPhoneNumber)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryFaxNumber](#PrimaryFaxNumber)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryFacebook](#PrimaryFacebook)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryLinkedIn](#PrimaryLinkedIn)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryTwitter](#PrimaryTwitter)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[DecisionMakingRoleCode](#DecisionMakingRoleCode)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[EmploymentProfession](#EmploymentProfession)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[IsInactive](#IsInactive)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[LastName](#LastName)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryURL](#PrimaryURL)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[ContactPersonResponsiblePersonnelNumber](#ContactPersonResponsiblePersonnelNumber)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[IsContactPersonExternallyMaintained](#IsContactPersonExternallyMaintained)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[SpouseName](#SpouseName)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[AssociatedContactType](#AssociatedContactType)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[AssociatedContactNumber](#AssociatedContactNumber)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryPostalAddressRecId](#PrimaryPostalAddressRecId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryContactEmailRecordId](#PrimaryContactEmailRecordId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryContactFaxRecordId](#PrimaryContactFaxRecordId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryContactLinkedInRecordId](#PrimaryContactLinkedInRecordId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryContactTwitterRecordId](#PrimaryContactTwitterRecordId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryContactFacebookRecordId](#PrimaryContactFacebookRecordId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryContactPhoneRecordId](#PrimaryContactPhoneRecordId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryContactTelexRecordId](#PrimaryContactTelexRecordId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryContactURLRecordId](#PrimaryContactURLRecordId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PrimaryAddressLocation](#PrimaryAddressLocation)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[PartyRecordId](#PartyRecordId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[BackingTable_smmContactPersonV2EntityRelationshipId](#BackingTable_smmContactPersonV2EntityRelationshipId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="smmContactPersonCDSV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonCDSV2Entity</a>|

### <a href=#ContactPersonPartyNumber name="ContactPersonPartyNumber">ContactPersonPartyNumber</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssociatedPartyNumber name="AssociatedPartyNumber">AssociatedPartyNumber</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociatedPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BirthDay name="BirthDay">BirthDay</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BirthDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BirthMonth name="BirthMonth">BirthMonth</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BirthMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BirthYear name="BirthYear">BirthYear</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BirthYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCity name="PrimaryAddressCity">PrimaryAddressCity</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

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

### <a href=#PrimaryAddressCountryRegionId name="PrimaryAddressCountryRegionId">PrimaryAddressCountryRegionId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

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

### <a href=#PrimaryAddressCountyId name="PrimaryAddressCountyId">PrimaryAddressCountyId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressDescription name="PrimaryAddressDescription">PrimaryAddressDescription</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

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

### <a href=#PrimaryAddressLocationRoles name="PrimaryAddressLocationRoles">PrimaryAddressLocationRoles</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLocationRoles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStateId name="PrimaryAddressStateId">PrimaryAddressStateId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStreet name="PrimaryAddressStreet">PrimaryAddressStreet</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

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

### <a href=#PrimaryAddressStreetNumber name="PrimaryAddressStreetNumber">PrimaryAddressStreetNumber</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressZipCode name="PrimaryAddressZipCode">PrimaryAddressZipCode</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

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

### <a href=#EmploymentDepartment name="EmploymentDepartment">EmploymentDepartment</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDepartment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Gender name="Gender">Gender</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Gender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstName name="FirstName">FirstName</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GovernmentIdentificationNumber name="GovernmentIdentificationNumber">GovernmentIdentificationNumber</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GovernmentIdentificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReceivingDirectMail name="IsReceivingDirectMail">IsReceivingDirectMail</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReceivingDirectMail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaritalStatus name="MaritalStatus">MaritalStatus</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaritalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MiddleName name="MiddleName">MiddleName</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonPartyType name="ContactPersonPartyType">ContactPersonPartyType</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonPartyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryEmailAddress name="PrimaryEmailAddress">PrimaryEmailAddress</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryEmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPhoneNumber name="PrimaryPhoneNumber">PrimaryPhoneNumber</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPhoneNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFaxNumber name="PrimaryFaxNumber">PrimaryFaxNumber</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFaxNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFacebook name="PrimaryFacebook">PrimaryFacebook</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFacebook attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryLinkedIn name="PrimaryLinkedIn">PrimaryLinkedIn</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryLinkedIn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTwitter name="PrimaryTwitter">PrimaryTwitter</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTwitter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DecisionMakingRoleCode name="DecisionMakingRoleCode">DecisionMakingRoleCode</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecisionMakingRoleCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentProfession name="EmploymentProfession">EmploymentProfession</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentProfession attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInactive name="IsInactive">IsInactive</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInactive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastName name="LastName">LastName</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryURL name="PrimaryURL">PrimaryURL</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonResponsiblePersonnelNumber name="ContactPersonResponsiblePersonnelNumber">ContactPersonResponsiblePersonnelNumber</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonResponsiblePersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsContactPersonExternallyMaintained name="IsContactPersonExternallyMaintained">IsContactPersonExternallyMaintained</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsContactPersonExternallyMaintained attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpouseName name="SpouseName">SpouseName</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpouseName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssociatedContactType name="AssociatedContactType">AssociatedContactType</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociatedContactType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssociatedContactNumber name="AssociatedContactNumber">AssociatedContactNumber</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociatedContactNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPostalAddressRecId name="PrimaryPostalAddressRecId">PrimaryPostalAddressRecId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailRecordId name="PrimaryContactEmailRecordId">PrimaryContactEmailRecordId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxRecordId name="PrimaryContactFaxRecordId">PrimaryContactFaxRecordId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedInRecordId name="PrimaryContactLinkedInRecordId">PrimaryContactLinkedInRecordId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedInRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitterRecordId name="PrimaryContactTwitterRecordId">PrimaryContactTwitterRecordId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitterRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebookRecordId name="PrimaryContactFacebookRecordId">PrimaryContactFacebookRecordId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebookRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneRecordId name="PrimaryContactPhoneRecordId">PrimaryContactPhoneRecordId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTelexRecordId name="PrimaryContactTelexRecordId">PrimaryContactTelexRecordId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelexRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLRecordId name="PrimaryContactURLRecordId">PrimaryContactURLRecordId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocation name="PrimaryAddressLocation">PrimaryAddressLocation</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

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

### <a href=#PartyRecordId name="PartyRecordId">PartyRecordId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_smmContactPersonV2EntityRelationshipId name="BackingTable_smmContactPersonV2EntityRelationshipId">BackingTable_smmContactPersonV2EntityRelationshipId</a>

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_smmContactPersonV2EntityRelationshipId attribute are listed below.</summary>

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

First included in: SalesAndMarketing/smmContactPersonCDSV2Entity (this entity)  

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
