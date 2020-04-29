---
title: HcmEmployeeEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Employee

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmEmployeeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Employee</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PersonnelNumber](#PersonnelNumber)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Person](#Person)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PartyNumber](#PartyNumber)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[KnownAs](#KnownAs)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[LanguageId](#LanguageId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Name](#Name)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[NameAlias](#NameAlias)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PhoneticFirstName](#PhoneticFirstName)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PhoneticLastName](#PhoneticLastName)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PhoneticMiddleName](#PhoneticMiddleName)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryAddressLocation](#PrimaryAddressLocation)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactEmail](#PrimaryContactEmail)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactEmailDescription](#PrimaryContactEmailDescription)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactEmailIsIM](#PrimaryContactEmailIsIM)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactEmailIsPrivate](#PrimaryContactEmailIsPrivate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactEmailPurpose](#PrimaryContactEmailPurpose)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactFax](#PrimaryContactFax)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactFaxDescription](#PrimaryContactFaxDescription)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactFaxExtension](#PrimaryContactFaxExtension)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactFaxIsPrivate](#PrimaryContactFaxIsPrivate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactFaxPurpose](#PrimaryContactFaxPurpose)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactPhone](#PrimaryContactPhone)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactPhoneDescription](#PrimaryContactPhoneDescription)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactPhoneExtension](#PrimaryContactPhoneExtension)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactPhoneIsMobile](#PrimaryContactPhoneIsMobile)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactPhoneIsPrivate](#PrimaryContactPhoneIsPrivate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactPhonePurpose](#PrimaryContactPhonePurpose)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactURL](#PrimaryContactURL)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactURLDescription](#PrimaryContactURLDescription)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactURLIsPrivate](#PrimaryContactURLIsPrivate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactURLPurpose](#PrimaryContactURLPurpose)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactFacebook](#PrimaryContactFacebook)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactFacebookDescription](#PrimaryContactFacebookDescription)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactFacebookIsPrivate](#PrimaryContactFacebookIsPrivate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactFacebookPurpose](#PrimaryContactFacebookPurpose)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactLinkedIn](#PrimaryContactLinkedIn)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactLinkedInDescription](#PrimaryContactLinkedInDescription)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactLinkedInIsPrivate](#PrimaryContactLinkedInIsPrivate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactLinkedInPurpose](#PrimaryContactLinkedInPurpose)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactTwitter](#PrimaryContactTwitter)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactTwitterDescription](#PrimaryContactTwitterDescription)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactTwitterIsPrivate](#PrimaryContactTwitterIsPrivate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PrimaryContactTwitterPurpose](#PrimaryContactTwitterPurpose)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[ProfessionalSuffix](#ProfessionalSuffix)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[ProfessionalTitle](#ProfessionalTitle)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PersonalTitle](#PersonalTitle)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PersonalSuffix](#PersonalSuffix)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Title](#Title)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[TitleId](#TitleId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[OriginalHireDateTime](#OriginalHireDateTime)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[SeniorityDate](#SeniorityDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AnniversaryDateTime](#AnniversaryDateTime)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[OfficeLocation](#OfficeLocation)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[OfficeLocationId](#OfficeLocationId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[SummaryValidFrom](#SummaryValidFrom)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[SummaryValidTo](#SummaryValidTo)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[BirthDate](#BirthDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[CitizenshipCountryRegion](#CitizenshipCountryRegion)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[NationalityCountryRegion](#NationalityCountryRegion)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[DeceasedDate](#DeceasedDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[DisabledVerificationDate](#DisabledVerificationDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Education](#Education)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EthnicOrigin](#EthnicOrigin)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EthnicOriginId](#EthnicOriginId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[FatherBirthCountryRegion](#FatherBirthCountryRegion)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Gender](#Gender)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[IsDisabled](#IsDisabled)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[IsFulltimeStudent](#IsFulltimeStudent)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[MotherBirthCountryRegion](#MotherBirthCountryRegion)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[NativeLanguage](#NativeLanguage)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[NativeLanguageId](#NativeLanguageId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PersonBirthCountryRegion](#PersonBirthCountryRegion)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PersonBirthCity](#PersonBirthCity)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[IsDisabledVeteran](#IsDisabledVeteran)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[IsExpatriateRulingApplicable](#IsExpatriateRulingApplicable)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[ExpatriateRulingValidFrom](#ExpatriateRulingValidFrom)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[ExpatriateRulingValidTo](#ExpatriateRulingValidTo)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[MaritalStatus](#MaritalStatus)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[NumberOfDependents](#NumberOfDependents)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[MilitaryServiceStartDate](#MilitaryServiceStartDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[MilitaryServiceEndDate](#MilitaryServiceEndDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[VeteranStatus](#VeteranStatus)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[VeteranStatusId](#VeteranStatusId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PersonDetailsValidFrom](#PersonDetailsValidFrom)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PersonDetailsValidTo](#PersonDetailsValidTo)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressBooks](#AddressBooks)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressCity](#AddressCity)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressCountryRegionId](#AddressCountryRegionId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressCountryRegionISOCode](#AddressCountryRegionISOCode)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressCounty](#AddressCounty)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressLocationId](#AddressLocationId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressLocationRoles](#AddressLocationRoles)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressNameDescription](#AddressNameDescription)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressState](#AddressState)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressStreet](#AddressStreet)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressValidFrom](#AddressValidFrom)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AddressValidTo](#AddressValidTo)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[FirstName](#FirstName)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[MiddleName](#MiddleName)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[LastNamePrefix](#LastNamePrefix)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[LastName](#LastName)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[NameValidFrom](#NameValidFrom)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[NameValidTo](#NameValidTo)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PartyType](#PartyType)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[NameSequenceDisplayAs](#NameSequenceDisplayAs)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentStartDate](#EmploymentStartDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentEndDate](#EmploymentEndDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentLegalEntity](#EmploymentLegalEntity)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentLegalEntityId](#EmploymentLegalEntityId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[RegulatoryEstablishment](#RegulatoryEstablishment)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[RegulatoryEstablishmentId](#RegulatoryEstablishmentId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[StartDate](#StartDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AdjustedWorkerStartDate](#AdjustedWorkerStartDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[LastDateWorked](#LastDateWorked)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[TerminationReason](#TerminationReason)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[TerminationReasonCodeId](#TerminationReasonCodeId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[TerminationDate](#TerminationDate)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentNoticeEmployerQuantity](#EmploymentNoticeEmployerQuantity)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentNoticeEmployerUnit](#EmploymentNoticeEmployerUnit)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentNoticeWorkerQuantity](#EmploymentNoticeWorkerQuantity)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentNoticeWorkerUnit](#EmploymentNoticeWorkerUnit)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentDetailsEffective](#EmploymentDetailsEffective)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmploymentDetailsExpiration](#EmploymentDetailsExpiration)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PensionEnrollment](#PensionEnrollment)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[PensionStart](#PensionStart)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[ProbationPeriod](#ProbationPeriod)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[RelocationReimbursement](#RelocationReimbursement)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmployeeDetailsEffective](#EmployeeDetailsEffective)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[EmployeeDetailsExpiration](#EmployeeDetailsExpiration)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Dimension](#Dimension)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[ElectronicLocationId](#ElectronicLocationId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[AllowRehire](#AllowRehire)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[WorksFromHome](#WorksFromHome)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[CalendarId](#CalendarId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[CalendarDataAreaId](#CalendarDataAreaId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Relationship_TitleRelationshipId](#Relationship_TitleRelationshipId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Relationship_LanguageRelationshipId](#Relationship_LanguageRelationshipId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Relationship_PersonRelationshipId](#Relationship_PersonRelationshipId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Relationship_EthnicOriginRelationshipId](#Relationship_EthnicOriginRelationshipId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|
|[Relationship_WorkCalendarRelationshipId](#Relationship_WorkCalendarRelationshipId)||<a href="HcmEmployeeEntity.md" target="_blank">HRM/HcmEmployeeEntity</a>|

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Person name="Person">Person</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Person attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#KnownAs name="KnownAs">KnownAs</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KnownAs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#NameAlias name="NameAlias">NameAlias</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameAlias attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneticFirstName name="PhoneticFirstName">PhoneticFirstName</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneticFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneticLastName name="PhoneticLastName">PhoneticLastName</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneticLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneticMiddleName name="PhoneticMiddleName">PhoneticMiddleName</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneticMiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocation name="PrimaryAddressLocation">PrimaryAddressLocation</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmail name="PrimaryContactEmail">PrimaryContactEmail</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailDescription name="PrimaryContactEmailDescription">PrimaryContactEmailDescription</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailIsIM name="PrimaryContactEmailIsIM">PrimaryContactEmailIsIM</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailIsIM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailIsPrivate name="PrimaryContactEmailIsPrivate">PrimaryContactEmailIsPrivate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailPurpose name="PrimaryContactEmailPurpose">PrimaryContactEmailPurpose</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFax name="PrimaryContactFax">PrimaryContactFax</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxDescription name="PrimaryContactFaxDescription">PrimaryContactFaxDescription</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxExtension name="PrimaryContactFaxExtension">PrimaryContactFaxExtension</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxIsPrivate name="PrimaryContactFaxIsPrivate">PrimaryContactFaxIsPrivate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxPurpose name="PrimaryContactFaxPurpose">PrimaryContactFaxPurpose</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhone name="PrimaryContactPhone">PrimaryContactPhone</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneDescription name="PrimaryContactPhoneDescription">PrimaryContactPhoneDescription</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneExtension name="PrimaryContactPhoneExtension">PrimaryContactPhoneExtension</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneIsMobile name="PrimaryContactPhoneIsMobile">PrimaryContactPhoneIsMobile</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneIsMobile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneIsPrivate name="PrimaryContactPhoneIsPrivate">PrimaryContactPhoneIsPrivate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhonePurpose name="PrimaryContactPhonePurpose">PrimaryContactPhonePurpose</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhonePurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURL name="PrimaryContactURL">PrimaryContactURL</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLDescription name="PrimaryContactURLDescription">PrimaryContactURLDescription</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLIsPrivate name="PrimaryContactURLIsPrivate">PrimaryContactURLIsPrivate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLPurpose name="PrimaryContactURLPurpose">PrimaryContactURLPurpose</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebook name="PrimaryContactFacebook">PrimaryContactFacebook</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebook attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebookDescription name="PrimaryContactFacebookDescription">PrimaryContactFacebookDescription</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebookDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebookIsPrivate name="PrimaryContactFacebookIsPrivate">PrimaryContactFacebookIsPrivate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebookIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebookPurpose name="PrimaryContactFacebookPurpose">PrimaryContactFacebookPurpose</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebookPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedIn name="PrimaryContactLinkedIn">PrimaryContactLinkedIn</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedIn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedInDescription name="PrimaryContactLinkedInDescription">PrimaryContactLinkedInDescription</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedInDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedInIsPrivate name="PrimaryContactLinkedInIsPrivate">PrimaryContactLinkedInIsPrivate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedInIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedInPurpose name="PrimaryContactLinkedInPurpose">PrimaryContactLinkedInPurpose</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedInPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitter name="PrimaryContactTwitter">PrimaryContactTwitter</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitterDescription name="PrimaryContactTwitterDescription">PrimaryContactTwitterDescription</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitterDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitterIsPrivate name="PrimaryContactTwitterIsPrivate">PrimaryContactTwitterIsPrivate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitterIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitterPurpose name="PrimaryContactTwitterPurpose">PrimaryContactTwitterPurpose</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitterPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfessionalSuffix name="ProfessionalSuffix">ProfessionalSuffix</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfessionalSuffix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfessionalTitle name="ProfessionalTitle">ProfessionalTitle</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfessionalTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonalTitle name="PersonalTitle">PersonalTitle</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonalTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonalSuffix name="PersonalSuffix">PersonalSuffix</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonalSuffix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Title name="Title">Title</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Title attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TitleId name="TitleId">TitleId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TitleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalHireDateTime name="OriginalHireDateTime">OriginalHireDateTime</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalHireDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SeniorityDate name="SeniorityDate">SeniorityDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeniorityDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnniversaryDateTime name="AnniversaryDateTime">AnniversaryDateTime</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnniversaryDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfficeLocation name="OfficeLocation">OfficeLocation</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfficeLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfficeLocationId name="OfficeLocationId">OfficeLocationId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfficeLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SummaryValidFrom name="SummaryValidFrom">SummaryValidFrom</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Summary effective</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummaryValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Summary effective</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SummaryValidTo name="SummaryValidTo">SummaryValidTo</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Summary expiration</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummaryValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Summary expiration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BirthDate name="BirthDate">BirthDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BirthDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CitizenshipCountryRegion name="CitizenshipCountryRegion">CitizenshipCountryRegion</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CitizenshipCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NationalityCountryRegion name="NationalityCountryRegion">NationalityCountryRegion</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NationalityCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeceasedDate name="DeceasedDate">DeceasedDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeceasedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisabledVerificationDate name="DisabledVerificationDate">DisabledVerificationDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisabledVerificationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Education name="Education">Education</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Education attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EthnicOrigin name="EthnicOrigin">EthnicOrigin</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EthnicOrigin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EthnicOriginId name="EthnicOriginId">EthnicOriginId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EthnicOriginId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FatherBirthCountryRegion name="FatherBirthCountryRegion">FatherBirthCountryRegion</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FatherBirthCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Gender name="Gender">Gender</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Gender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDisabled name="IsDisabled">IsDisabled</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDisabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFulltimeStudent name="IsFulltimeStudent">IsFulltimeStudent</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFulltimeStudent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MotherBirthCountryRegion name="MotherBirthCountryRegion">MotherBirthCountryRegion</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MotherBirthCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NativeLanguage name="NativeLanguage">NativeLanguage</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NativeLanguage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NativeLanguageId name="NativeLanguageId">NativeLanguageId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Native language</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NativeLanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Native language</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonBirthCountryRegion name="PersonBirthCountryRegion">PersonBirthCountryRegion</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonBirthCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonBirthCity name="PersonBirthCity">PersonBirthCity</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonBirthCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDisabledVeteran name="IsDisabledVeteran">IsDisabledVeteran</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDisabledVeteran attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExpatriateRulingApplicable name="IsExpatriateRulingApplicable">IsExpatriateRulingApplicable</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExpatriateRulingApplicable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpatriateRulingValidFrom name="ExpatriateRulingValidFrom">ExpatriateRulingValidFrom</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpatriateRulingValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpatriateRulingValidTo name="ExpatriateRulingValidTo">ExpatriateRulingValidTo</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpatriateRulingValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaritalStatus name="MaritalStatus">MaritalStatus</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaritalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfDependents name="NumberOfDependents">NumberOfDependents</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfDependents attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MilitaryServiceStartDate name="MilitaryServiceStartDate">MilitaryServiceStartDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MilitaryServiceStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MilitaryServiceEndDate name="MilitaryServiceEndDate">MilitaryServiceEndDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MilitaryServiceEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VeteranStatus name="VeteranStatus">VeteranStatus</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VeteranStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VeteranStatusId name="VeteranStatusId">VeteranStatusId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VeteranStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidFrom name="PersonDetailsValidFrom">PersonDetailsValidFrom</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Personal information effective</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Personal information effective</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidTo name="PersonDetailsValidTo">PersonDetailsValidTo</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Personal information expiration</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Personal information expiration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBooks name="AddressBooks">AddressBooks</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address books</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBooks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address books</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#AddressCountryRegionId name="AddressCountryRegionId">AddressCountryRegionId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#AddressCounty name="AddressCounty">AddressCounty</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#AddressLocationId name="AddressLocationId">AddressLocationId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#AddressLocationRoles name="AddressLocationRoles">AddressLocationRoles</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address purpose</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationRoles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address purpose</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressNameDescription name="AddressNameDescription">AddressNameDescription</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address name or description</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressNameDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address name or description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressState name="AddressState">AddressState</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#AddressValidFrom name="AddressValidFrom">AddressValidFrom</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address effective</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address effective</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidTo name="AddressValidTo">AddressValidTo</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address expiration</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address expiration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstName name="FirstName">FirstName</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MiddleName name="MiddleName">MiddleName</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastNamePrefix name="LastNamePrefix">LastNamePrefix</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastNamePrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastName name="LastName">LastName</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NameValidFrom name="NameValidFrom">NameValidFrom</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name change effective</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name change effective</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NameValidTo name="NameValidTo">NameValidTo</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name change expiration</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name change expiration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyType name="PartyType">PartyType</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#NameSequenceDisplayAs name="NameSequenceDisplayAs">NameSequenceDisplayAs</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameSequenceDisplayAs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentStartDate name="EmploymentStartDate">EmploymentStartDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentEndDate name="EmploymentEndDate">EmploymentEndDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentLegalEntity name="EmploymentLegalEntity">EmploymentLegalEntity</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentLegalEntityId name="EmploymentLegalEntityId">EmploymentLegalEntityId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegulatoryEstablishment name="RegulatoryEstablishment">RegulatoryEstablishment</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegulatoryEstablishment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegulatoryEstablishmentId name="RegulatoryEstablishmentId">RegulatoryEstablishmentId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegulatoryEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdjustedWorkerStartDate name="AdjustedWorkerStartDate">AdjustedWorkerStartDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustedWorkerStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastDateWorked name="LastDateWorked">LastDateWorked</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastDateWorked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TerminationReason name="TerminationReason">TerminationReason</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminationReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TerminationReasonCodeId name="TerminationReasonCodeId">TerminationReasonCodeId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminationReasonCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TerminationDate name="TerminationDate">TerminationDate</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentNoticeEmployerQuantity name="EmploymentNoticeEmployerQuantity">EmploymentNoticeEmployerQuantity</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentNoticeEmployerQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentNoticeEmployerUnit name="EmploymentNoticeEmployerUnit">EmploymentNoticeEmployerUnit</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentNoticeEmployerUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentNoticeWorkerQuantity name="EmploymentNoticeWorkerQuantity">EmploymentNoticeWorkerQuantity</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentNoticeWorkerQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentNoticeWorkerUnit name="EmploymentNoticeWorkerUnit">EmploymentNoticeWorkerUnit</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentNoticeWorkerUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailsEffective name="EmploymentDetailsEffective">EmploymentDetailsEffective</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employment detail effective</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailsEffective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Employment detail effective</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailsExpiration name="EmploymentDetailsExpiration">EmploymentDetailsExpiration</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employment detail expiraton</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailsExpiration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Employment detail expiraton</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PensionEnrollment name="PensionEnrollment">PensionEnrollment</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PensionEnrollment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PensionStart name="PensionStart">PensionStart</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PensionStart attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProbationPeriod name="ProbationPeriod">ProbationPeriod</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProbationPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelocationReimbursement name="RelocationReimbursement">RelocationReimbursement</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelocationReimbursement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmployeeDetailsEffective name="EmployeeDetailsEffective">EmployeeDetailsEffective</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee detail effective</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployeeDetailsEffective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Employee detail effective</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmployeeDetailsExpiration name="EmployeeDetailsExpiration">EmployeeDetailsExpiration</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee detail expiration</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployeeDetailsExpiration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Employee detail expiration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension name="Dimension">Dimension</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicLocationId name="ElectronicLocationId">ElectronicLocationId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowRehire name="AllowRehire">AllowRehire</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowRehire attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorksFromHome name="WorksFromHome">WorksFromHome</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorksFromHome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarId name="CalendarId">CalendarId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarDataAreaId name="CalendarDataAreaId">CalendarDataAreaId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TitleRelationshipId name="Relationship_TitleRelationshipId">Relationship_TitleRelationshipId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TitleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LanguageRelationshipId name="Relationship_LanguageRelationshipId">Relationship_LanguageRelationshipId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LanguageRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PersonRelationshipId name="Relationship_PersonRelationshipId">Relationship_PersonRelationshipId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PersonRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EthnicOriginRelationshipId name="Relationship_EthnicOriginRelationshipId">Relationship_EthnicOriginRelationshipId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EthnicOriginRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WorkerRelationshipId name="Relationship_WorkerRelationshipId">Relationship_WorkerRelationshipId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

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

### <a href=#Relationship_WorkCalendarRelationshipId name="Relationship_WorkCalendarRelationshipId">Relationship_WorkCalendarRelationshipId</a>

First included in: HRM/HcmEmployeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkCalendarRelationshipId attribute are listed below.</summary>

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
