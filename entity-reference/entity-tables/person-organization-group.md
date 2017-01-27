---
title: "Person, organization, and group reference | Microsoft Docs"
description: "The people, organizations, and groups entities encompass a rich set of people and organizations that you might interact with."
author: "robinarh"
manager: "robinarh"
ms.date: "01/26/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "cb6723ce-88d9-4e54-81a0-2f532965d3be"
---

# Person, organization, and group reference 
## Alumnus (Alumnus) Entity 
A graduate of a school. 

Field | Description
---|---
AlumnusId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
GraduationClass | Data: Text<br>Maximum length: 128
GraduationDate | Data: Date
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: AlumnusStatus<br>Values: Current, Inactive, Past<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>GraduationClass<br>Status<br>EmailPrimary<br>HomePostalAddress<br>Description<br>FacebookIdentity<br>TwitterIdentity
DefaultList|DefaultList field group|FullName<br>GraduationClass<br>Status<br>EmailPrimary
DefaultCard|DefaultCard field group|FullName<br>GraduationClass<br>PhonePrimary
DefaultDetails|DefaultDetails field group|AlumnusId<br>Name<br>GraduationClass<br>Status<br>EmailPrimary<br>HomePostalAddress<br>Description<br>FacebookIdentity<br>TwitterIdentity
DefaultLookup|DefaultLookup field group|AlumnusId<br>FullName<br>GraduationClass<br>Status
DefaultReport|DefaultReport field group|AlumnusId<br>Name<br>GraduationClass<br>Status<br>EmailPrimary<br>Description<br>FacebookIdentity<br>TwitterIdentity
DefaultIdentification|DefaultIdentification field group|AlumnusId<br>FullName
## ApplicationUser (Application user) Entity 
 

Field | Description
---|---
AADUserOID<br>Primary key | Data: Text<br>Required, Unique, Searchable, Maximum length: 36<br>Description: AAD user object id
ApplicationUserId | Number sequence: <br>Unique, Searchable
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit<br>Required
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Required, Unique, Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsAdmin | Data: Boolean<br>Required
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: ApplicationUserStatus<br>Values: Active, Inactive<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>EmailPrimary<br>Description<br>SocialNetwork01<br>SocialNetworkIdentity01
DefaultList|DefaultList field group|ApplicationUserId<br>FullName<br>Status
DefaultCard|DefaultCard field group|ApplicationUserId<br>FullName<br>EmailPrimary
DefaultDetails|DefaultDetails field group|ApplicationUserId<br>FullName<br>Name<br>EmailPrimary<br>Description<br>SocialNetwork01<br>SocialNetworkIdentity01
DefaultLookup|DefaultLookup field group|ApplicationUserId<br>FullName<br>EmailPrimary
DefaultReport|DefaultReport field group|ApplicationUserId<br>FullName<br>Name<br>EmailPrimary<br>Description<br>SocialNetwork01<br>SocialNetworkIdentity01
DefaultIdentification|DefaultIdentification field group|ApplicationUserId<br>FullName
## ApplicationUserContact (@Foundation.ApplicationUserContact) Entity 
 

Field | Description
---|---
ApplicationUser<br>Primary key | Lookup: ApplicationUser<br>Required
Contact | Lookup: Contact<br>Required
DataSource | Picklist: Source<br>Values: Default<br>Required<br>Description: Source
Description | Data: Text<br>Maximum length: 128
IsOwner | Data: Boolean<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
ApplicationUser|Application user|OneToMany|Association
Contact|Contact|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|DataSource<br>Description<br>IsOwner<br>Contact<br>ApplicationUser
DefaultList|DefaultList field group|DataSource<br>Description<br>IsOwner<br>Contact<br>ApplicationUser
DefaultCard|DefaultCard field group|DataSource<br>Description<br>IsOwner<br>Contact<br>ApplicationUser
DefaultDetails|DefaultDetails field group|DataSource<br>Description<br>IsOwner<br>Contact<br>ApplicationUser
DefaultLookup|DefaultLookup field group|Description<br>IsOwner<br>Contact<br>ApplicationUser
DefaultReport|DefaultReport field group|DataSource<br>Description<br>IsOwner<br>Contact<br>ApplicationUser
DefaultIdentification|DefaultIdentification field group|ApplicationUser<br>Contact
## ApplicationUserGroup (Application user group) Entity 
 

Field | Description
---|---
ApplicationUserGroupId<br>Primary key | Number sequence: <br>Unique, Searchable
BusinessUnit | Lookup: BusinessUnit<br>Required
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FullName | Data: Text<br>Searchable, Maximum length: 128
GroupName | Data: Text<br>Maximum length: 128
IsSecurityPrincipal | Data: Boolean<br>Required
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OtherPostalAddress | Data: Address
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
ShippingPostalAddress | Data: Address
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: ApplicationUserGroupStatus<br>Values: Active, Inactive<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Status<br>BusinessUnit
DefaultList|DefaultList field group|ApplicationUserGroupId<br>FullName<br>Status
DefaultCard|DefaultCard field group|ApplicationUserGroupId<br>FullName<br>Status
DefaultDetails|DefaultDetails field group|ApplicationUserGroupId<br>FullName<br>Status<br>BusinessUnit
DefaultLookup|DefaultLookup field group|ApplicationUserGroupId<br>FullName<br>Status
DefaultReport|DefaultReport field group|ApplicationUserGroupId<br>FullName<br>Status<br>BusinessUnit
DefaultIdentification|DefaultIdentification field group|ApplicationUserGroupId<br>FullName
## Constituent (Constituent) Entity 
New Comment 

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
ConstituentId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: ConstituentStatus<br>Values: Active, Inactive<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary<br>Description<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultList|DefaultList field group|FullName<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary
DefaultCard|DefaultCard field group|ConstituentId<br>FullName<br>Status
DefaultDetails|DefaultDetails field group|ConstituentId<br>FullName<br>Name<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary<br>Description<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultLookup|DefaultLookup field group|ConstituentId<br>FullName
DefaultReport|DefaultReport field group|ConstituentId<br>FullName<br>Name<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultIdentification|DefaultIdentification field group|ConstituentId<br>FullName
## Contact (Contact) Entity 
A person who serves as a contact for an organization. 

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
ContactId<br>Primary key | Number sequence: <br>Unique, Searchable
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: Status<br>Values: Active, Inactive<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>PhoneCell<br>PhoneBusiness<br>PhoneHome<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>BusinessPostalAddress<br>WebsiteURL
DefaultList|DefaultList field group|FullName<br>EmailPrimary<br>PhoneBusiness<br>PhoneCell
DefaultCard|DefaultCard field group|FullName<br>PhoneCell<br>EmailPrimary
DefaultDetails|DefaultDetails field group|ContactId<br>FullName<br>Name<br>PhoneCell<br>PhoneBusiness<br>PhoneHome<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>BusinessPostalAddress<br>WebsiteURL
DefaultLookup|DefaultLookup field group|ContactId<br>FullName<br>EmailPrimary
DefaultReport|DefaultReport field group|ContactId<br>FullName<br>Name<br>PhoneCell<br>PhoneBusiness<br>PhoneHome<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>BusinessPostalAddress<br>WebsiteURL
DefaultIdentification|DefaultIdentification field group|FullName<br>EmailPrimary
## Family (Family) Entity 
A group of related people. Individual family members are described in the Family Members table. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FamilyId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Family number
FullName | Data: Text<br>Searchable, Maximum length: 128
GroupName | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OtherPostalAddress | Data: Address
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
ShippingPostalAddress | Data: Address
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: FamilyStatus<br>Values: Active, Inactive<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255

### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultList|DefaultList field group|FamilyId<br>FullName<br>Status<br>PhonePrimary
DefaultCard|DefaultCard field group|FamilyId<br>FullName<br>Status<br>PhonePrimary
DefaultDetails|DefaultDetails field group|FamilyId<br>FullName<br>Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultLookup|DefaultLookup field group|FamilyId<br>FullName<br>Status
DefaultReport|DefaultReport field group|FamilyId<br>FullName<br>Status<br>PhonePrimary
DefaultIdentification|DefaultIdentification field group|FamilyId<br>FullName
## FamilyMember (Family member) Entity 
A person that is a member of a family. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Family<br>Primary key | Lookup: Family<br>Required
Person | Lookup: Person<br>Required
PrimaryRole | Picklist: FamilyRole<br>Values: ElderSiblings, Father, GrandParents, Mother, YoungerSiblings<br>Required
Status | Picklist: FamilyMemberStatus<br>Values: Active, Inactive<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Family|Family|OneToMany|Association
Person|Person|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Person<br>PrimaryRole<br>Family<br>Description
DefaultList|DefaultList field group|Person<br>PrimaryRole<br>Family
DefaultCard|DefaultCard field group|Person<br>PrimaryRole<br>Family
DefaultDetails|DefaultDetails field group|Person<br>PrimaryRole<br>Family<br>Description
DefaultLookup|DefaultLookup field group|Person<br>PrimaryRole<br>Family
DefaultReport|DefaultReport field group|Person<br>PrimaryRole<br>Family<br>Description
DefaultIdentification|DefaultIdentification field group|Person<br>Family
## Fan (Fan) Entity 
A fan of an person, organization, group. 

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FanId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
FanSince | Data: Date
FavoritePlayer | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: FanStatus<br>Values: Bronze, Club, Gold, Platinum, PreferenceTicket, SeasonTicketHolder, Silver<br>Required<br>Description: Fan status
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>Status<br>FanSince<br>FavoritePlayer
DefaultList|DefaultList field group|FullName<br>Status<br>FanSince<br>FavoritePlayer
DefaultCard|DefaultCard field group|FanId<br>FullName<br>Status
DefaultDetails|DefaultDetails field group|FanId<br>FullName<br>Name<br>Status<br>FanSince<br>FavoritePlayer
DefaultLookup|DefaultLookup field group|FanId<br>FullName<br>Status<br>FanSince
DefaultReport|DefaultReport field group|FanId<br>FullName<br>Name<br>Status<br>FanSince<br>FavoritePlayer
DefaultIdentification|DefaultIdentification field group|FanId<br>FullName
## Household (Household) Entity 
A group of individuals that share a living space. Individual household members are described in the HouseholdMember entity. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FullName | Data: Text<br>Searchable, Maximum length: 128
GroupName | Data: Text<br>Maximum length: 128
HouseholdId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Household number
MailingPostalAddress | Data: Address
OtherPostalAddress | Data: Address
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
ShippingPostalAddress | Data: Address
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: HouseholdStatus<br>Values: Active, Inactive<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255

### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultList|DefaultList field group|FullName<br>Status<br>PhonePrimary
DefaultCard|DefaultCard field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary
DefaultDetails|DefaultDetails field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultLookup|DefaultLookup field group|HouseholdId<br>FullName<br>Status
DefaultReport|DefaultReport field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary<br>Description
DefaultIdentification|DefaultIdentification field group|HouseholdId<br>FullName
## HouseholdMember (Household member) Entity 
A person that is a member of a household. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Household<br>Primary key | Lookup: Household<br>Required
Person | Lookup: Person<br>Required
PrimaryRole | Picklist: HouseholdRole<br>Values: ElderSiblings, Father, GrandParents, Mother, YoungerSiblings<br>Required
Status | Picklist: HouseholdMemberStatus<br>Values: Active, Inactive<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Household|Household|OneToMany|Association
Person|Person|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Household<br>Person<br>PrimaryRole<br>Description
DefaultList|DefaultList field group|Person<br>Household<br>PrimaryRole
DefaultCard|DefaultCard field group|Household<br>Person<br>PrimaryRole
DefaultDetails|DefaultDetails field group|Household<br>Person<br>PrimaryRole<br>Description
DefaultLookup|DefaultLookup field group|Household<br>Person<br>PrimaryRole
DefaultReport|DefaultReport field group|Household<br>Person<br>PrimaryRole
DefaultIdentification|DefaultIdentification field group|Person<br>Household
## Organization (Organization) Entity 
 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
IndustryCode | Picklist: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
IsEmailContactAllowed | Data: Boolean<br>Required
IsInternal | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OrganizationId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Organization number
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
ParentOrganization | Lookup: Organization
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
PrimaryContact | Lookup: Contact<br>Required
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: OrganizationStatus<br>Values: Active, Inactive<br>Required
StockExchange | Picklist: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
Type | Picklist: OrganizationType<br>Values: Corporation, Government, NonProfit, Other<br>Required<br>Description: OrganizationType
WebsiteURL | Data: Text<br>Maximum length: 255

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Organization|Parent Organization|OneToMany|Association
Contact|Primary contact|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Description<br>ParentOrganization<br>PhonePrimary<br>EmailPrimary<br>MailingPostalAddress
DefaultList|DefaultList field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization
DefaultCard|DefaultCard field group|OrganizationId<br>FullName
DefaultDetails|DefaultDetails field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization<br>PhonePrimary<br>EmailPrimary<br>MailingPostalAddress<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>TaxIdentificationNumber<br>StockTicker
DefaultLookup|DefaultLookup field group|OrganizationId<br>FullName
DefaultReport|DefaultReport field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization<br>PhonePrimary<br>EmailPrimary<br>TaxIdentificationNumber<br>StockTicker
DefaultIdentification|DefaultIdentification field group|OrganizationId<br>FullName
## OrganizationContact (@Foundation.OrganizationContact) Entity 
 

Field | Description
---|---
Contact | Lookup: Contact<br>Required
DataSource | Picklist: Source<br>Values: Default<br>Required<br>Description: Source
Description | Data: Text<br>Maximum length: 128
Organization<br>Primary key | Lookup: Organization<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Organization|Organization|OneToMany|Association
Contact|Contact|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Organization<br>Contact<br>DataSource<br>Description
DefaultList|DefaultList field group|Organization<br>Contact<br>DataSource<br>Description
DefaultCard|DefaultCard field group|Organization<br>Contact<br>DataSource<br>Description
DefaultDetails|DefaultDetails field group|Organization<br>Contact<br>DataSource<br>Description
DefaultLookup|DefaultLookup field group|Organization<br>Contact<br>DataSource<br>Description
DefaultReport|DefaultReport field group|Organization<br>Contact<br>DataSource<br>Description
DefaultIdentification|DefaultIdentification field group|Organization<br>Contact
## Team (Team) Entity 
A group of persons who participate together in a defined effort. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FullName | Data: Text<br>Searchable, Maximum length: 128
GroupName | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OtherPostalAddress | Data: Address
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
ShippingPostalAddress | Data: Address
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: TeamStatus<br>Values: Active, Inactive<br>Required
TeamId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Team number
WebsiteURL | Data: Text<br>Maximum length: 255

### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Description<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultList|DefaultList field group|FullName<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultCard|DefaultCard field group|FullName<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultDetails|DefaultDetails field group|TeamId<br>FullName<br>Description<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultLookup|DefaultLookup field group|TeamId<br>FullName<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultReport|DefaultReport field group|TeamId<br>FullName<br>Description<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultIdentification|DefaultIdentification field group|TeamId<br>FullName
## TeamMember (Team member) Entity 
A person who is a member of a team. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Person | Lookup: Person<br>Required
PrimaryRole | Picklist: TeamRole<br>Values: Coach, Lead, Manager, Player, Reserve, TeamLeader, TeamMember<br>Required
Status | Picklist: TeamMemberStatus<br>Values: Active, Inactive<br>Required
Team<br>Primary key | Lookup: Team<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Team|Team|OneToMany|Association
Person|Person|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Person<br>Team<br>PrimaryRole
DefaultList|DefaultList field group|Person<br>Team<br>PrimaryRole
DefaultCard|DefaultCard field group|Person<br>Team<br>PrimaryRole
DefaultDetails|DefaultDetails field group|Person<br>Team<br>PrimaryRole
DefaultLookup|DefaultLookup field group|Person<br>Team<br>PrimaryRole
DefaultReport|DefaultReport field group|Person<br>Team<br>PrimaryRole
DefaultIdentification|DefaultIdentification field group|Person<br>Team
## Tenant (Tenant) Entity 
A person or organization that leases space. 

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PersonName | Data: PersonName<br>Description: Given name
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: TenantStatus<br>Values: Active, Inactive<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TenantId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PersonName<br>Status<br>PhonePrimary<br>HomePostalAddress
DefaultList|DefaultList field group|FullName<br>Status
DefaultCard|DefaultCard field group|FullName<br>Status
DefaultDetails|DefaultDetails field group|TenantId<br>FullName<br>PersonName<br>Status<br>PhonePrimary<br>HomePostalAddress
DefaultLookup|DefaultLookup field group|TenantId<br>FullName<br>Status
DefaultReport|DefaultReport field group|TenantId<br>FullName<br>PersonName<br>Status<br>PhonePrimary<br>HomePostalAddress
DefaultIdentification|DefaultIdentification field group|TenantId<br>FullName
## Worker (Worker) Entity 
 

Field | Description
---|---
BusinessPostalAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
Manager | Lookup: Worker
Name | Data: PersonName<br>Description: Given name
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Party_PartyId | Data: Text<br>Maximum length: 128<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: WorkerStatus<br>Values: Active, Inactive<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
Type | Picklist: WorkerType<br>Values: Contractor, Employee, Unspecified, Volunteer<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255
WorkerId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Worker|Manager|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>Status<br>Description<br>Manager<br>BusinessUnit
DefaultList|DefaultList field group|WorkerId<br>FullName<br>Status<br>Manager<br>BusinessUnit
DefaultCard|DefaultCard field group|WorkerId<br>FullName<br>Status<br>Manager<br>BusinessUnit
DefaultDetails|DefaultDetails field group|WorkerId<br>FullName<br>Name<br>Status<br>Description<br>Manager<br>BusinessUnit<br>PhoneCell<br>PhoneBusiness<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>HomePostalAddress
DefaultLookup|DefaultLookup field group|WorkerId<br>FullName<br>Status
DefaultReport|DefaultReport field group|WorkerId<br>FullName<br>Name<br>Status<br>Manager<br>BusinessUnit<br>PhoneCell<br>PhoneBusiness<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultIdentification|DefaultIdentification field group|WorkerId<br>FullName
