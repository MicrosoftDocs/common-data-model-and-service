---
title: "Person, organization, or group reference | Common Data Model"
description: ""
author: ""
manager: "robinarh"
ms.date: "10/25/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "cb6723ce-88d9-4e54-81a0-2f532965d3be"
---

# Person, organization, or group

## Alumnus (Alumnus) Entity
A graduate of a school.

Field | Description
---|---
AlumnusId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Birthdate | Data: Date
BusinessPostalAddress | Data: Address<br>Description: Business postal address line 1
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Data: Picklist
Generation | Data: Text<br>Maximum length: 128
GraduationClass | Data: Text<br>Maximum length: 128
GraduationDate | Data: Date
HomePostalAddress | Data: Address<br>Description: Home postal address line 1
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Data: Picklist<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
SocialNetwork01 | Data: Picklist
SocialNetwork02 | Data: Picklist
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>GraduationClass<br>Status<br>EmailPrimary<br>HomePostalAddress<br>Description<br>FacebookIdentity<br>TwitterIdentity
DefaultList|Auto generated DefaultList field group|FullName<br>GraduationClass<br>Status<br>EmailPrimary
DefaultCard|Auto generated DefaultCard field group|FullName<br>GraduationClass<br>PhonePrimary
DefaultDetails|Auto generated DefaultDetails field group|AlumnusId<br>Name<br>GraduationClass<br>Status<br>EmailPrimary<br>HomePostalAddress<br>Description<br>FacebookIdentity<br>TwitterIdentity
DefaultLookup|Auto generated DefaultLookup field group|AlumnusId<br>FullName<br>GraduationClass<br>Status
DefaultReport|Auto generated DefaultReport field group|AlumnusId<br>Name<br>GraduationClass<br>Status<br>EmailPrimary<br>Description<br>FacebookIdentity<br>TwitterIdentity
DefaultIdentification|Auto generated DefaultIdentification field group|AlumnusId<br>FullName
## ApplicationUser (Application user) Entity


Field | Description
---|---
AADUserOID<br>Primary key | Data: Text<br>Required, Unique, Maximum length: 36<br>Description: AAD user object ID
ApplicationUserId | Number sequence: <br>Unique
Birthdate | Data: Date
BusinessPostalAddress | Data: Address<br>Description: Business postal address line 1
BusinessUnit | Lookup: BusinessUnit<br>Required
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Required, Unique
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Data: Picklist
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address<br>Description: Home postal address line 1
IsAdmin | Data: Boolean<br>Required
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Middle name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Data: Picklist<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
SocialNetwork01 | Data: Picklist
SocialNetwork02 | Data: Picklist
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>EmailPrimary<br>Description<br>SocialNetwork01<br>SocialNetworkIdentity01
DefaultList|Auto generated DefaultList field group|ApplicationUserId<br>FullName<br>Status
DefaultCard|Auto generated DefaultCard field group|ApplicationUserId<br>FullName<br>EmailPrimary
DefaultDetails|Auto generated DefaultDetails field group|ApplicationUserId<br>FullName<br>Name<br>EmailPrimary<br>Description<br>SocialNetwork01<br>SocialNetworkIdentity01
DefaultLookup|Auto generated DefaultLookup field group|ApplicationUserId<br>FullName<br>EmailPrimary
DefaultReport|Auto generated DefaultReport field group|ApplicationUserId<br>FullName<br>Name<br>EmailPrimary<br>Description<br>SocialNetwork01<br>SocialNetworkIdentity01
DefaultIdentification|Auto generated DefaultIdentification field group|ApplicationUserId<br>FullName
## ApplicationUserGroup (Application user group) Entity


Field | Description
---|---
ApplicationUserGroupId<br>Primary key | Number sequence: <br>Unique
BusinessUnit | Lookup: BusinessUnit<br>Required
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FullName | Data: Text<br>Maximum length: 128
IsSecurityPrincipal | Data: Boolean<br>Required
MailingPostalAddress | Data: Address<br>Description: Mailing postal address line 1
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OtherPostalAddress | Data: Address<br>Description: Other postal address line 1
PartyType | Data: Picklist<br>Required
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Status<br>BusinessUnit
DefaultList|Auto generated DefaultList field group|ApplicationUserGroupId<br>FullName<br>Status
DefaultCard|Auto generated DefaultCard field group|ApplicationUserGroupId<br>FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|ApplicationUserGroupId<br>FullName<br>Status<br>BusinessUnit
DefaultLookup|Auto generated DefaultLookup field group|ApplicationUserGroupId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|ApplicationUserGroupId<br>FullName<br>Status<br>BusinessUnit
DefaultIdentification|Auto generated DefaultIdentification field group|ApplicationUserGroupId<br>FullName
## Constituent (Constituent) Entity
A member of a group.

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address<br>Description: Business postal address line 1
ConstituentId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Data: Picklist
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address<br>Description: Home postal address line 1
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Data: Picklist<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
SocialNetwork01 | Data: Picklist
SocialNetwork02 | Data: Picklist
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary<br>Description<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultList|Auto generated DefaultList field group|FullName<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary
DefaultCard|Auto generated DefaultCard field group|ConstituentId<br>FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|ConstituentId<br>FullName<br>Name<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary<br>Description<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultLookup|Auto generated DefaultLookup field group|ConstituentId<br>FullName
DefaultReport|Auto generated DefaultReport field group|ConstituentId<br>FullName<br>Name<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultIdentification|Auto generated DefaultIdentification field group|ConstituentId<br>FullName
## Contact (Contact) Entity
An individual that a company has a relationship with, such as a customer, a supplier, or a colleague, and the related attributes�postal, electronic, social�attributes for that individual.

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address<br>Description: Business postal address line 1
ContactId<br>Primary key | Number sequence: <br>Unique
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Data: Picklist
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address<br>Description: Home postal address line 1
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Data: Picklist<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
SocialNetwork01 | Data: Picklist
SocialNetwork02 | Data: Picklist
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>PhoneCell<br>PhoneBusiness<br>PhoneHome<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>BusinessPostalAddress<br>WebsiteURL
DefaultList|Auto generated DefaultList field group|FullName<br>EmailPrimary<br>PhoneBusiness<br>PhoneCell
DefaultCard|Auto generated DefaultCard field group|FullName<br>PhoneCell<br>EmailPrimary
DefaultDetails|Auto generated DefaultDetails field group|ContactId<br>FullName<br>Name<br>PhoneCell<br>PhoneBusiness<br>PhoneHome<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>BusinessPostalAddress<br>WebsiteURL
DefaultLookup|Auto generated DefaultLookup field group|ContactId<br>FullName<br>EmailPrimary
DefaultReport|Auto generated DefaultReport field group|ContactId<br>FullName<br>Name<br>PhoneCell<br>PhoneBusiness<br>PhoneHome<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>BusinessPostalAddress<br>WebsiteURL
DefaultIdentification|Auto generated DefaultIdentification field group|FullName<br>EmailPrimary
## Family (Family) Entity
A group of related people. Individual family members are described in the FamilyMember entity.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FamilyId<br>Primary key | Number sequence: <br>Unique
FamilyName | Data: Text<br>Maximum length: 128<br>Description: Organization name
FullName | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address<br>Description: Mailing postal address line 1
OtherPostalAddress | Data: Address<br>Description: Other postal address line 1
PartyType | Data: Picklist<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultList|Auto generated DefaultList field group|FamilyId<br>FullName<br>Status<br>PhonePrimary
DefaultCard|Auto generated DefaultCard field group|FamilyId<br>FullName<br>Status<br>PhonePrimary
DefaultDetails|Auto generated DefaultDetails field group|FamilyId<br>FullName<br>Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultLookup|Auto generated DefaultLookup field group|FamilyId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|FamilyId<br>FullName<br>Status<br>PhonePrimary
DefaultIdentification|Auto generated DefaultIdentification field group|FamilyId<br>FullName
## FamilyMember (Family member) Entity
A person who is a member of a family.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Family<br>Primary key | Lookup: Family<br>Required
Person | Lookup: Person<br>Required
PrimaryRole | Data: Picklist<br>Required
Status | Data: Picklist<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Person<br>PrimaryRole<br>Family<br>Description
DefaultList|Auto generated DefaultList field group|Person<br>PrimaryRole<br>Family
DefaultCard|Auto generated DefaultCard field group|Person<br>PrimaryRole<br>Family
DefaultDetails|Auto generated DefaultDetails field group|Person<br>PrimaryRole<br>Family<br>Description
DefaultLookup|Auto generated DefaultLookup field group|Person<br>PrimaryRole<br>Family
DefaultReport|Auto generated DefaultReport field group|Person<br>PrimaryRole<br>Family<br>Description
DefaultIdentification|Auto generated DefaultIdentification field group|Person<br>Family
## Fan (Fan) Entity
A fan of a person, organization, or group.

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address<br>Description: Business postal address line 1
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FanId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
FanSince | Data: Date
FavoritePlayer | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Data: Picklist
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address<br>Description: Home postal address line 1
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Data: Picklist<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
SocialNetwork01 | Data: Picklist
SocialNetwork02 | Data: Picklist
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required<br>Description: Fan status
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>Status<br>FanSince<br>FavoritePlayer
DefaultList|Auto generated DefaultList field group|FullName<br>Status<br>FanSince<br>FavoritePlayer
DefaultCard|Auto generated DefaultCard field group|FanId<br>FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|FanId<br>FullName<br>Name<br>Status<br>FanSince<br>FavoritePlayer
DefaultLookup|Auto generated DefaultLookup field group|FanId<br>FullName<br>Status<br>FanSince
DefaultReport|Auto generated DefaultReport field group|FanId<br>FullName<br>Name<br>Status<br>FanSince<br>FavoritePlayer
DefaultIdentification|Auto generated DefaultIdentification field group|FanId<br>FullName
## Household (Household) Entity
A group of individuals who share a living space. Individual household members are described in the HouseholdMember entity.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FullName | Data: Text<br>Maximum length: 128
HouseholdId<br>Primary key | Number sequence: <br>Unique
HouseholdName | Data: Text<br>Maximum length: 128<br>Description: Organization name
MailingPostalAddress | Data: Address<br>Description: Mailing postal address line 1
OtherPostalAddress | Data: Address<br>Description: Other postal address line 1
PartyType | Data: Picklist<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultList|Auto generated DefaultList field group|FullName<br>Status<br>PhonePrimary
DefaultCard|Auto generated DefaultCard field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary
DefaultDetails|Auto generated DefaultDetails field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultLookup|Auto generated DefaultLookup field group|HouseholdId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary<br>Description
DefaultIdentification|Auto generated DefaultIdentification field group|HouseholdId<br>FullName
## HouseholdMember (Household member) Entity
A person who is a member of a household.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Household<br>Primary key | Lookup: Household<br>Required
Person | Lookup: Person<br>Required
PrimaryRole | Data: Picklist<br>Required
Status | Data: Picklist<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Household<br>Person<br>PrimaryRole<br>Description
DefaultList|Auto generated DefaultList field group|Person<br>Household<br>PrimaryRole
DefaultCard|Auto generated DefaultCard field group|Household<br>Person<br>PrimaryRole
DefaultDetails|Auto generated DefaultDetails field group|Household<br>Person<br>PrimaryRole<br>Description
DefaultLookup|Auto generated DefaultLookup field group|Household<br>Person<br>PrimaryRole
DefaultReport|Auto generated DefaultReport field group|Household<br>Person<br>PrimaryRole
DefaultIdentification|Auto generated DefaultIdentification field group|Person<br>Household
## Organization (Organization) Entity


Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
IndustryCode | Data: Picklist
IsEmailContactAllowed | Data: Boolean<br>Required
IsInternal | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address<br>Description: Mailing postal address line 1
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OrganizationId<br>Primary key | Number sequence: <br>Unique
OtherPostalAddress | Data: Address<br>Description: Other postal address line 1
ParentOrganization | Lookup: Organization
PartyType | Data: Picklist<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
PrimaryContact | Lookup: Contact<br>Required
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
SocialNetwork01 | Data: Picklist
SocialNetwork02 | Data: Picklist
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
StockExchange | Data: Picklist
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
Type | Data: Picklist<br>Required<br>Description: OrganizationType
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Description<br>ParentOrganization<br>PhonePrimary<br>EmailPrimary<br>MailingPostalAddress
DefaultList|Auto generated DefaultList field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization
DefaultCard|Auto generated DefaultCard field group|OrganizationId<br>FullName
DefaultDetails|Auto generated DefaultDetails field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization<br>PhonePrimary<br>EmailPrimary<br>MailingPostalAddress<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>TaxIdentificationNumber<br>StockTicker
DefaultLookup|Auto generated DefaultLookup field group|OrganizationId<br>FullName
DefaultReport|Auto generated DefaultReport field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization<br>PhonePrimary<br>EmailPrimary<br>TaxIdentificationNumber<br>StockTicker
DefaultIdentification|Auto generated DefaultIdentification field group|OrganizationId<br>FullName
## Team (Team) Entity
A team in an organization or group. Individual team members are described in the TeamMember entity.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FullName | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address<br>Description: Mailing postal address line 1
OtherPostalAddress | Data: Address<br>Description: Other postal address line 1
PartyType | Data: Picklist<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
TeamId<br>Primary key | Number sequence: <br>Unique
TeamName | Data: Text<br>Maximum length: 128<br>Description: Organization name
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Description<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultList|Auto generated DefaultList field group|FullName<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultCard|Auto generated DefaultCard field group|FullName<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultDetails|Auto generated DefaultDetails field group|TeamId<br>FullName<br>Description<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultLookup|Auto generated DefaultLookup field group|TeamId<br>FullName<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultReport|Auto generated DefaultReport field group|TeamId<br>FullName<br>Description<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultIdentification|Auto generated DefaultIdentification field group|TeamId<br>FullName
## TeamMember (Team member) Entity
A person who is a member of a team.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Person | Lookup: Person<br>Required
PrimaryRole | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
Team<br>Primary key | Lookup: Team<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Person<br>Team<br>PrimaryRole
DefaultList|Auto generated DefaultList field group|Person<br>Team<br>PrimaryRole
DefaultCard|Auto generated DefaultCard field group|Person<br>Team<br>PrimaryRole
DefaultDetails|Auto generated DefaultDetails field group|Person<br>Team<br>PrimaryRole
DefaultLookup|Auto generated DefaultLookup field group|Person<br>Team<br>PrimaryRole
DefaultReport|Auto generated DefaultReport field group|Person<br>Team<br>PrimaryRole
DefaultIdentification|Auto generated DefaultIdentification field group|Person<br>Team
## Tenant (Tenant) Entity
A person, organization, or group that leases space.

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address<br>Description: Business postal address line 1
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Data: Picklist
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address<br>Description: Home postal address line 1
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Data: Picklist<br>Required
PersonName | Data: PersonName<br>Description: Given name
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
SocialNetwork01 | Data: Picklist
SocialNetwork02 | Data: Picklist
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TenantId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|PersonName<br>Status<br>PhonePrimary<br>HomePostalAddress
DefaultList|Auto generated DefaultList field group|FullName<br>Status
DefaultCard|Auto generated DefaultCard field group|FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|TenantId<br>FullName<br>PersonName<br>Status<br>PhonePrimary<br>HomePostalAddress
DefaultLookup|Auto generated DefaultLookup field group|TenantId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|TenantId<br>FullName<br>PersonName<br>Status<br>PhonePrimary<br>HomePostalAddress
DefaultIdentification|Auto generated DefaultIdentification field group|TenantId<br>FullName
## Worker (Worker) Entity


Field | Description
---|---
BusinessPostalAddress | Data: Address<br>Description: Business postal address line 1
BusinessUnit | Lookup: BusinessUnit<br>Required
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Data: Picklist
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address<br>Description: Home postal address line 1
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Manager | Lookup: Worker
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Data: Picklist<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
SocialNetwork01 | Data: Picklist
SocialNetwork02 | Data: Picklist
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
Type | Data: Picklist<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255
WorkerId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>Status<br>Description<br>Manager<br>BusinessUnit
DefaultList|Auto generated DefaultList field group|WorkerId<br>FullName<br>Status<br>Manager<br>BusinessUnit
DefaultCard|Auto generated DefaultCard field group|WorkerId<br>FullName<br>Status<br>Manager<br>BusinessUnit
DefaultDetails|Auto generated DefaultDetails field group|WorkerId<br>FullName<br>Name<br>Status<br>Description<br>Manager<br>BusinessUnit<br>PhoneCell<br>PhoneBusiness<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>HomePostalAddress
DefaultLookup|Auto generated DefaultLookup field group|WorkerId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|WorkerId<br>FullName<br>Name<br>Status<br>Manager<br>BusinessUnit<br>PhoneCell<br>PhoneBusiness<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultIdentification|Auto generated DefaultIdentification field group|WorkerId<br>FullName
