---
title: smmContactPersonV2Entity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Contacts V2 in SalesAndMarketing(smmContactPersonV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/smmContactPersonV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contacts V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ContactPersonId](#ContactPersonId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ContactPersonPartyNumber](#ContactPersonPartyNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ContactPersonName](#ContactPersonName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ContactPersonPartyType](#ContactPersonPartyType)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ContactForParty](#ContactForParty)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AssociatedPartyNumber](#AssociatedPartyNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[FirstName](#FirstName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[MiddleName](#MiddleName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[LastName](#LastName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[SearchName](#SearchName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AddressBookNames](#AddressBookNames)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ContactInformationLanguageId](#ContactInformationLanguageId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ChildrenNames](#ChildrenNames)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[Hobbies](#Hobbies)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[Initials](#Initials)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[KnownAsName](#KnownAsName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ProfessionalTitle](#ProfessionalTitle)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ProfessionalSuffix](#ProfessionalSuffix)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PhoneticFirstName](#PhoneticFirstName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PhoneticMiddleName](#PhoneticMiddleName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PhoneticLastName](#PhoneticLastName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[Gender](#Gender)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[MaritalStatus](#MaritalStatus)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[BirthDay](#BirthDay)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[BirthMonth](#BirthMonth)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[BirthYear](#BirthYear)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AnniversaryDay](#AnniversaryDay)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AnniversaryMonth](#AnniversaryMonth)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AnniversaryYear](#AnniversaryYear)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressDescription](#PrimaryAddressDescription)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressCity](#PrimaryAddressCity)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressCityInKana](#PrimaryAddressCityInKana)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressCountryRegionId](#PrimaryAddressCountryRegionId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressCountryRegionISOCode](#PrimaryAddressCountryRegionISOCode)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressCountyId](#PrimaryAddressCountyId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressDistrictName](#PrimaryAddressDistrictName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressLatitude](#PrimaryAddressLatitude)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressLocationId](#PrimaryAddressLocationId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressLocationRoles](#PrimaryAddressLocationRoles)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressLongitude](#PrimaryAddressLongitude)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressStateId](#PrimaryAddressStateId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressStreet](#PrimaryAddressStreet)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressStreetInKana](#PrimaryAddressStreetInKana)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressTimeZone](#PrimaryAddressTimeZone)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressZipCode](#PrimaryAddressZipCode)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressPostBox](#PrimaryAddressPostBox)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressBuildingCompliment](#PrimaryAddressBuildingCompliment)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressStreetNumber](#PrimaryAddressStreetNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[FormattedPrimaryAddress](#FormattedPrimaryAddress)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressValidFrom](#PrimaryAddressValidFrom)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressValidTo](#PrimaryAddressValidTo)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryEmailAddress](#PrimaryEmailAddress)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryEmailAddressDescription](#PrimaryEmailAddressDescription)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IsPrimaryEmailAddressIMEnabled](#IsPrimaryEmailAddressIMEnabled)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryEmailAddressPurpose](#PrimaryEmailAddressPurpose)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryFaxNumber](#PrimaryFaxNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryFaxNumberDescription](#PrimaryFaxNumberDescription)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryFaxNumberExtension](#PrimaryFaxNumberExtension)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryFaxNumberPurpose](#PrimaryFaxNumberPurpose)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryPhoneNumber](#PrimaryPhoneNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryPhoneNumberDescription](#PrimaryPhoneNumberDescription)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryPhoneNumberExtension](#PrimaryPhoneNumberExtension)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IsPrimaryPhoneNumberMobile](#IsPrimaryPhoneNumberMobile)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryPhoneNumberPurpose](#PrimaryPhoneNumberPurpose)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryTelex](#PrimaryTelex)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryTelexDescription](#PrimaryTelexDescription)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryTelexPurpose](#PrimaryTelexPurpose)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryURL](#PrimaryURL)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryURLDescription](#PrimaryURLDescription)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryURLPurpose](#PrimaryURLPurpose)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryFacebook](#PrimaryFacebook)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryFacebookDescription](#PrimaryFacebookDescription)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryFacebookPurpose](#PrimaryFacebookPurpose)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryLinkedIn](#PrimaryLinkedIn)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryLinkedInDescription](#PrimaryLinkedInDescription)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryLinkedInPurpose](#PrimaryLinkedInPurpose)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryTwitter](#PrimaryTwitter)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryTwitterDescription](#PrimaryTwitterDescription)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryTwitterPurpose](#PrimaryTwitterPurpose)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[EmploymentJobTitle](#EmploymentJobTitle)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[EmploymentJobFunctionName](#EmploymentJobFunctionName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[EmploymentProfession](#EmploymentProfession)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[EmploymentDepartment](#EmploymentDepartment)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[EmploymentOfficeLocation](#EmploymentOfficeLocation)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[EmploymentComputerNetworkName](#EmploymentComputerNetworkName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AvailableFromTime](#AvailableFromTime)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AvailableToTime](#AvailableToTime)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[MicrosoftOutlookCategories](#MicrosoftOutlookCategories)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ContactActivitySensitivityLevel](#ContactActivitySensitivityLevel)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ManagerContactPersonId](#ManagerContactPersonId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[MainResponsibleWorker](#MainResponsibleWorker)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ContactPersonResponsiblePersonnelNumber](#ContactPersonResponsiblePersonnelNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IsReceivingDirectMail](#IsReceivingDirectMail)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[Notes](#Notes)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimarySalutationPhrase](#PrimarySalutationPhrase)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AlternateSalutationPhrase](#AlternateSalutationPhrase)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryComplimentaryClosingPhrase](#PrimaryComplimentaryClosingPhrase)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AlternateComplimentaryClosingPhrase](#AlternateComplimentaryClosingPhrase)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[OrganizationIdentificationNumber](#OrganizationIdentificationNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[GovernmentIdentificationNumber](#GovernmentIdentificationNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[MileageDistance](#MileageDistance)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[LoyaltyLevelPhrase](#LoyaltyLevelPhrase)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[DecisionMakingRoleCode](#DecisionMakingRoleCode)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PersonalCharacterTypeCode](#PersonalCharacterTypeCode)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IsVIP](#IsVIP)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AssistantName](#AssistantName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[AssistantPhoneNumber](#AssistantPhoneNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[BillingInformation](#BillingInformation)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IsImported](#IsImported)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IsInactive](#IsInactive)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[LastEditDateTime](#LastEditDateTime)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IsDefaultContactPerson](#IsDefaultContactPerson)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IdentityCardNumber](#IdentityCardNumber)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[SpouseName](#SpouseName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[UserRole](#UserRole)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[HasRequestedInternetAccess](#HasRequestedInternetAccess)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[NameValidFrom](#NameValidFrom)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[NameValidTo](#NameValidTo)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[DisplayNameSequencePatternName](#DisplayNameSequencePatternName)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[ElectronicLocationId](#ElectronicLocationId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IsVendorPortalAccessAllowed](#IsVendorPortalAccessAllowed)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[IsContactPersonExternallyMaintained](#IsContactPersonExternallyMaintained)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryPostalAddressRecId](#PrimaryPostalAddressRecId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryContactEmailRecordId](#PrimaryContactEmailRecordId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryContactFaxRecordId](#PrimaryContactFaxRecordId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryContactPhoneRecordId](#PrimaryContactPhoneRecordId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryContactTelexRecordId](#PrimaryContactTelexRecordId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryContactURLRecordId](#PrimaryContactURLRecordId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryContactFacebookRecordId](#PrimaryContactFacebookRecordId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryContactTwitterRecordId](#PrimaryContactTwitterRecordId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryContactLinkedInRecordId](#PrimaryContactLinkedInRecordId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PrimaryAddressLocation](#PrimaryAddressLocation)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[PartyRecordId](#PartyRecordId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[BackingTable_ContactPersonRelationshipId](#BackingTable_ContactPersonRelationshipId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="smmContactPersonV2Entity.md" target="_blank">SalesAndMarketing/smmContactPersonV2Entity</a>|

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#ContactPersonPartyNumber name="ContactPersonPartyNumber">ContactPersonPartyNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#ContactPersonName name="ContactPersonName">ContactPersonName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonPartyType name="ContactPersonPartyType">ContactPersonPartyType</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact person party type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonPartyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contact person party type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactForParty name="ContactForParty">ContactForParty</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactForParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssociatedPartyNumber name="AssociatedPartyNumber">AssociatedPartyNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Associated party number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociatedPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Associated party number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstName name="FirstName">FirstName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#MiddleName name="MiddleName">MiddleName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#LastName name="LastName">LastName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#SearchName name="SearchName">SearchName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#AddressBookNames name="AddressBookNames">AddressBookNames</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBookNames attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactInformationLanguageId name="ContactInformationLanguageId">ContactInformationLanguageId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactInformationLanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChildrenNames name="ChildrenNames">ChildrenNames</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChildrenNames attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Hobbies name="Hobbies">Hobbies</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hobbies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Initials name="Initials">Initials</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Initials attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KnownAsName name="KnownAsName">KnownAsName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KnownAsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfessionalTitle name="ProfessionalTitle">ProfessionalTitle</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfessionalTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfessionalSuffix name="ProfessionalSuffix">ProfessionalSuffix</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfessionalSuffix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneticFirstName name="PhoneticFirstName">PhoneticFirstName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneticFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneticMiddleName name="PhoneticMiddleName">PhoneticMiddleName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneticMiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneticLastName name="PhoneticLastName">PhoneticLastName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneticLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Gender name="Gender">Gender</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#MaritalStatus name="MaritalStatus">MaritalStatus</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#BirthDay name="BirthDay">BirthDay</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#AnniversaryDay name="AnniversaryDay">AnniversaryDay</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnniversaryDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnniversaryMonth name="AnniversaryMonth">AnniversaryMonth</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnniversaryMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnniversaryYear name="AnniversaryYear">AnniversaryYear</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnniversaryYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressDescription name="PrimaryAddressDescription">PrimaryAddressDescription</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryAddressCity name="PrimaryAddressCity">PrimaryAddressCity</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryAddressCityInKana name="PrimaryAddressCityInKana">PrimaryAddressCityInKana</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCountryRegionId name="PrimaryAddressCountryRegionId">PrimaryAddressCountryRegionId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryAddressDistrictName name="PrimaryAddressDistrictName">PrimaryAddressDistrictName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLatitude name="PrimaryAddressLatitude">PrimaryAddressLatitude</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocationId name="PrimaryAddressLocationId">PrimaryAddressLocationId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocationRoles name="PrimaryAddressLocationRoles">PrimaryAddressLocationRoles</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryAddressLongitude name="PrimaryAddressLongitude">PrimaryAddressLongitude</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStateId name="PrimaryAddressStateId">PrimaryAddressStateId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryAddressStreetInKana name="PrimaryAddressStreetInKana">PrimaryAddressStreetInKana</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressTimeZone name="PrimaryAddressTimeZone">PrimaryAddressTimeZone</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressZipCode name="PrimaryAddressZipCode">PrimaryAddressZipCode</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryAddressPostBox name="PrimaryAddressPostBox">PrimaryAddressPostBox</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressBuildingCompliment name="PrimaryAddressBuildingCompliment">PrimaryAddressBuildingCompliment</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStreetNumber name="PrimaryAddressStreetNumber">PrimaryAddressStreetNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#FormattedPrimaryAddress name="FormattedPrimaryAddress">FormattedPrimaryAddress</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedPrimaryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressValidFrom name="PrimaryAddressValidFrom">PrimaryAddressValidFrom</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryEmailAddress name="PrimaryEmailAddress">PrimaryEmailAddress</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryEmailAddressDescription name="PrimaryEmailAddressDescription">PrimaryEmailAddressDescription</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryEmailAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryEmailAddressIMEnabled name="IsPrimaryEmailAddressIMEnabled">IsPrimaryEmailAddressIMEnabled</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryEmailAddressIMEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryEmailAddressPurpose name="PrimaryEmailAddressPurpose">PrimaryEmailAddressPurpose</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryEmailAddressPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFaxNumber name="PrimaryFaxNumber">PrimaryFaxNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryFaxNumberDescription name="PrimaryFaxNumberDescription">PrimaryFaxNumberDescription</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFaxNumberDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFaxNumberExtension name="PrimaryFaxNumberExtension">PrimaryFaxNumberExtension</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFaxNumberExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFaxNumberPurpose name="PrimaryFaxNumberPurpose">PrimaryFaxNumberPurpose</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFaxNumberPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPhoneNumber name="PrimaryPhoneNumber">PrimaryPhoneNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryPhoneNumberDescription name="PrimaryPhoneNumberDescription">PrimaryPhoneNumberDescription</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPhoneNumberDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPhoneNumberExtension name="PrimaryPhoneNumberExtension">PrimaryPhoneNumberExtension</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPhoneNumberExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryPhoneNumberMobile name="IsPrimaryPhoneNumberMobile">IsPrimaryPhoneNumberMobile</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryPhoneNumberMobile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPhoneNumberPurpose name="PrimaryPhoneNumberPurpose">PrimaryPhoneNumberPurpose</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPhoneNumberPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTelex name="PrimaryTelex">PrimaryTelex</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTelex attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTelexDescription name="PrimaryTelexDescription">PrimaryTelexDescription</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTelexDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTelexPurpose name="PrimaryTelexPurpose">PrimaryTelexPurpose</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTelexPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryURL name="PrimaryURL">PrimaryURL</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryURLDescription name="PrimaryURLDescription">PrimaryURLDescription</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryURLDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryURLPurpose name="PrimaryURLPurpose">PrimaryURLPurpose</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryURLPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFacebook name="PrimaryFacebook">PrimaryFacebook</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryFacebookDescription name="PrimaryFacebookDescription">PrimaryFacebookDescription</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFacebookDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFacebookPurpose name="PrimaryFacebookPurpose">PrimaryFacebookPurpose</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFacebookPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryLinkedIn name="PrimaryLinkedIn">PrimaryLinkedIn</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryLinkedInDescription name="PrimaryLinkedInDescription">PrimaryLinkedInDescription</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryLinkedInDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryLinkedInPurpose name="PrimaryLinkedInPurpose">PrimaryLinkedInPurpose</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryLinkedInPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTwitter name="PrimaryTwitter">PrimaryTwitter</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryTwitterDescription name="PrimaryTwitterDescription">PrimaryTwitterDescription</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTwitterDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTwitterPurpose name="PrimaryTwitterPurpose">PrimaryTwitterPurpose</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTwitterPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentJobTitle name="EmploymentJobTitle">EmploymentJobTitle</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentJobTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentJobFunctionName name="EmploymentJobFunctionName">EmploymentJobFunctionName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentJobFunctionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentProfession name="EmploymentProfession">EmploymentProfession</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#EmploymentDepartment name="EmploymentDepartment">EmploymentDepartment</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#EmploymentOfficeLocation name="EmploymentOfficeLocation">EmploymentOfficeLocation</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentOfficeLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentComputerNetworkName name="EmploymentComputerNetworkName">EmploymentComputerNetworkName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentComputerNetworkName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailableFromTime name="AvailableFromTime">AvailableFromTime</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailableFromTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AvailableToTime name="AvailableToTime">AvailableToTime</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AvailableToTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MicrosoftOutlookCategories name="MicrosoftOutlookCategories">MicrosoftOutlookCategories</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MicrosoftOutlookCategories attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactActivitySensitivityLevel name="ContactActivitySensitivityLevel">ContactActivitySensitivityLevel</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactActivitySensitivityLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManagerContactPersonId name="ManagerContactPersonId">ManagerContactPersonId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManagerContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainResponsibleWorker name="MainResponsibleWorker">MainResponsibleWorker</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainResponsibleWorker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonResponsiblePersonnelNumber name="ContactPersonResponsiblePersonnelNumber">ContactPersonResponsiblePersonnelNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#IsReceivingDirectMail name="IsReceivingDirectMail">IsReceivingDirectMail</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#Notes name="Notes">Notes</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimarySalutationPhrase name="PrimarySalutationPhrase">PrimarySalutationPhrase</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimarySalutationPhrase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternateSalutationPhrase name="AlternateSalutationPhrase">AlternateSalutationPhrase</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternateSalutationPhrase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryComplimentaryClosingPhrase name="PrimaryComplimentaryClosingPhrase">PrimaryComplimentaryClosingPhrase</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryComplimentaryClosingPhrase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternateComplimentaryClosingPhrase name="AlternateComplimentaryClosingPhrase">AlternateComplimentaryClosingPhrase</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternateComplimentaryClosingPhrase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationIdentificationNumber name="OrganizationIdentificationNumber">OrganizationIdentificationNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationIdentificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GovernmentIdentificationNumber name="GovernmentIdentificationNumber">GovernmentIdentificationNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#MileageDistance name="MileageDistance">MileageDistance</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MileageDistance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyLevelPhrase name="LoyaltyLevelPhrase">LoyaltyLevelPhrase</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyLevelPhrase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DecisionMakingRoleCode name="DecisionMakingRoleCode">DecisionMakingRoleCode</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PersonalCharacterTypeCode name="PersonalCharacterTypeCode">PersonalCharacterTypeCode</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonalCharacterTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVIP name="IsVIP">IsVIP</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVIP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssistantName name="AssistantName">AssistantName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssistantName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssistantPhoneNumber name="AssistantPhoneNumber">AssistantPhoneNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssistantPhoneNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingInformation name="BillingInformation">BillingInformation</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsImported name="IsImported">IsImported</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsImported attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInactive name="IsInactive">IsInactive</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#LastEditDateTime name="LastEditDateTime">LastEditDateTime</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastEditDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultContactPerson name="IsDefaultContactPerson">IsDefaultContactPerson</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultContactPerson attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentityCardNumber name="IdentityCardNumber">IdentityCardNumber</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentityCardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpouseName name="SpouseName">SpouseName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#UserRole name="UserRole">UserRole</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserRole attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasRequestedInternetAccess name="HasRequestedInternetAccess">HasRequestedInternetAccess</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasRequestedInternetAccess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NameValidFrom name="NameValidFrom">NameValidFrom</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NameValidTo name="NameValidTo">NameValidTo</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayNameSequencePatternName name="DisplayNameSequencePatternName">DisplayNameSequencePatternName</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayNameSequencePatternName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicLocationId name="ElectronicLocationId">ElectronicLocationId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#IsVendorPortalAccessAllowed name="IsVendorPortalAccessAllowed">IsVendorPortalAccessAllowed</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVendorPortalAccessAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsContactPersonExternallyMaintained name="IsContactPersonExternallyMaintained">IsContactPersonExternallyMaintained</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryPostalAddressRecId name="PrimaryPostalAddressRecId">PrimaryPostalAddressRecId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryContactPhoneRecordId name="PrimaryContactPhoneRecordId">PrimaryContactPhoneRecordId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryContactFacebookRecordId name="PrimaryContactFacebookRecordId">PrimaryContactFacebookRecordId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryContactTwitterRecordId name="PrimaryContactTwitterRecordId">PrimaryContactTwitterRecordId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryContactLinkedInRecordId name="PrimaryContactLinkedInRecordId">PrimaryContactLinkedInRecordId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#PrimaryAddressLocation name="PrimaryAddressLocation">PrimaryAddressLocation</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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

### <a href=#BackingTable_ContactPersonRelationshipId name="BackingTable_ContactPersonRelationshipId">BackingTable_ContactPersonRelationshipId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ContactPersonRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/ContactPerson.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/ContactPerson.cdm.json/ContactPerson</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/ContactPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/smmContactPersonV2Entity (this entity)  

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
