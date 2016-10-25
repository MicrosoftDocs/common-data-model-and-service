---
title: "Person, organization, or group reference"
description: ""
author: ""
manager: "robinarh"
ms.date: "10/25/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataModel"
ms.technology: "CommonDataModel"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "cb6723ce-88d9-4e54-81a0-2f532965d3be"
---

# Person, organization, or group
## Alumnus (@Foundation.Alumnus) Entity 
A graduate of a school. 

Field | Description
---|---
AlumnusId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
GraduationClass | Data: Text<br>Maximum length: 128
GraduationDate | Data: Date
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: AlumnusStatus<br>Values: Current, Inactive, Past<br>Required
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
## ApplicationUser (@Foundation.ApplicationUser) Entity 
@Foundation.ApplicationUser 

Field | Description
---|---
AADUserOID<br>Primary key | Data: Text<br>Required, Unique, Maximum length: 36<br>Description: AAD user object id
ApplicationUserId | Number sequence: <br>Unique
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit<br>Required
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Required, Unique
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsAdmin | Data: Boolean<br>Required
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: ApplicationUserStatus<br>Values: Active, Inactive<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|FullName<br>Name<br>EmailPrimary<br>Description<br>SocialNetwork01<br>SocialNetworkIdentity01
DefaultList|Auto generated DefaultList field group|FullName<br>ApplicationUserId<br>Status
DefaultCard|Auto generated DefaultCard field group|ApplicationUserId<br>FullName<br>EmailPrimary
DefaultDetails|Auto generated DefaultDetails field group|ApplicationUserId<br>FullName<br>Name<br>EmailPrimary<br>Description<br>SocialNetwork01<br>SocialNetworkIdentity01
DefaultLookup|Auto generated DefaultLookup field group|ApplicationUserId<br>FullName<br>EmailPrimary
DefaultReport|Auto generated DefaultReport field group|ApplicationUserId<br>FullName<br>Name<br>EmailPrimary<br>Description<br>SocialNetwork01<br>SocialNetworkIdentity01
DefaultIdentification|Auto generated DefaultIdentification field group|ApplicationUserId<br>FullName
## ApplicationUserGroup (@Foundation.ApplicationUserGroup) Entity 
@Foundation.ApplicationUserGroup 

Field | Description
---|---
ApplicationUserGroupId<br>Primary key | Number sequence: <br>Unique
BusinessUnit | Lookup: BusinessUnit<br>Required
BusinessUnit_Name | Data: Text<br>Maximum length: 128<br>Description: Business unit name
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FullName | Data: Text<br>Maximum length: 128
IsSecurityPrincipal | Data: Boolean<br>Required
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OtherPostalAddress | Data: Address
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
ShippingPostalAddress | Data: Address
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: ApplicationUserGroupStatus<br>Values: Active, Inactive<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|ApplicationUserGroupId<br>FullName<br>Status<br>BusinessUnit<br>BusinessUnit_Name
DefaultList|Auto generated DefaultList field group|ApplicationUserGroupId<br>FullName<br>Status
DefaultCard|Auto generated DefaultCard field group|ApplicationUserGroupId<br>FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|ApplicationUserGroupId<br>FullName<br>Status<br>BusinessUnit<br>BusinessUnit_Name
DefaultLookup|Auto generated DefaultLookup field group|ApplicationUserGroupId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|ApplicationUserGroupId<br>FullName<br>Status<br>BusinessUnit<br>BusinessUnit_Name
DefaultIdentification|Auto generated DefaultIdentification field group|ApplicationUserGroupId<br>FullName
## Constituent (@Foundation.Constituent) Entity 
A member of a group. 

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
ConstituentId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: ConstituentStatus<br>Values: Active, Inactive<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|ConstituentId<br>FullName<br>Name<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary<br>Description<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity
DefaultList|Auto generated DefaultList field group|FullName<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary
DefaultCard|Auto generated DefaultCard field group|ConstituentId<br>FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|ConstituentId<br>FullName<br>Name<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary<br>Description<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity
DefaultLookup|Auto generated DefaultLookup field group|ConstituentId<br>FullName
DefaultReport|Auto generated DefaultReport field group|ConstituentId<br>FullName<br>Name<br>Status<br>PhoneCell<br>PhoneBusiness<br>EmailPrimary<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity
DefaultIdentification|Auto generated DefaultIdentification field group|ConstituentId<br>FullName
## Contact (@Foundation.Contact) Entity 
An individual that a company has a relationship with, such as a customer, a supplier, or a colleague, and the related attributes�postal, electronic, social�attributes for that individual. 

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
ContactId<br>Primary key | Number sequence: <br>Unique
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
ModifiedByUser | Data: Text<br>Maximum length: 36
ModifiedOnDateTime | Data: DateTime
Name | Data: PersonName
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: Status<br>Values: Active, Inactive<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|ContactId<br>FullName<br>Name<br>PhoneCell<br>PhoneBusiness<br>PhoneHome<br>EmailPrimary<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity<br>BusinessPostalAddress<br>WebsiteURL
DefaultList|Auto generated DefaultList field group|FullName<br>EmailPrimary<br>PhoneBusiness<br>PhoneCell
DefaultCard|Auto generated DefaultCard field group|FullName<br>PhoneCell<br>EmailPrimary
DefaultDetails|Auto generated DefaultDetails field group|ContactId<br>FullName<br>Name<br>PhoneCell<br>PhoneBusiness<br>PhoneHome<br>EmailPrimary<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity<br>BusinessPostalAddress<br>WebsiteURL
DefaultLookup|Auto generated DefaultLookup field group|FullName<br>EmailPrimary
DefaultReport|Auto generated DefaultReport field group|ContactId<br>FullName<br>Name<br>PhoneCell<br>PhoneBusiness<br>PhoneHome<br>EmailPrimary<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity<br>BusinessPostalAddress<br>WebsiteURL
DefaultIdentification|Auto generated DefaultIdentification field group|FullName<br>EmailPrimary
## Family (@Foundation.Family) Entity 
A group of related people. Individual family members are described in the FamilyMember entity. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FamilyId<br>Primary key | Number sequence: <br>Unique<br>Description: Family number
FamilyName | Data: Text<br>Maximum length: 128<br>Description: Organization name
FullName | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OtherPostalAddress | Data: Address
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
ShippingPostalAddress | Data: Address
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: FamilyStatus<br>Values: Active, Inactive<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|FamilyId<br>FullName<br>Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultList|Auto generated DefaultList field group|FamilyId<br>FullName<br>Status<br>PhonePrimary
DefaultCard|Auto generated DefaultCard field group|FamilyId<br>FullName<br>Status<br>PhonePrimary
DefaultDetails|Auto generated DefaultDetails field group|FamilyId<br>FullName<br>Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultLookup|Auto generated DefaultLookup field group|FamilyId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|FamilyId<br>FullName<br>Status<br>PhonePrimary
DefaultIdentification|Auto generated DefaultIdentification field group|FamilyId<br>FullName
## FamilyMember (@Group.FamilyMember) Entity 
A person who is a member of a family. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Family<br>Primary key | Lookup: Family<br>Required
FamilyName | Data: Text<br>Maximum length: 128
Person | Lookup: Person<br>Required
PersonName | Data: Text<br>Maximum length: 128
PrimaryRole | Enumeration: FamilyRole<br>Values: ElderSiblings, Father, GrandParents, Mother, YoungerSiblings<br>Required
Status | Enumeration: FamilyMemberStatus<br>Values: Active, Inactive<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Person<br>PersonName<br>PrimaryRole<br>Family<br>Description
DefaultList|Auto generated DefaultList field group|Person<br>PrimaryRole<br>Family
DefaultCard|Auto generated DefaultCard field group|Person<br>PersonName<br>PrimaryRole<br>Family
DefaultDetails|Auto generated DefaultDetails field group|Person<br>PersonName<br>PrimaryRole<br>Family<br>Description
DefaultLookup|Auto generated DefaultLookup field group|Person<br>PersonName<br>PrimaryRole<br>Family
DefaultReport|Auto generated DefaultReport field group|Person<br>PersonName<br>PrimaryRole<br>Family<br>Description
DefaultIdentification|Auto generated DefaultIdentification field group|Person<br>PersonName
## Fan (@Foundation.Fan) Entity 
A fan of a person, organization, or group. 

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FanId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
FanSince | Data: Date
FavoritePlayer | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
Name | Data: PersonName
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: FanStatus<br>Values: Bronze, Club, Gold, Platinum, PreferenceTicket, SeasonTicketHolder, Silver<br>Required<br>Description: Fan status
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|FanId<br>FullName<br>Name<br>Status<br>FanSince<br>FavoritePlayer
DefaultList|Auto generated DefaultList field group|FullName<br>Status<br>FanSince<br>FavoritePlayer
DefaultCard|Auto generated DefaultCard field group|FanId<br>FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|FanId<br>FullName<br>Name<br>Status<br>FanSince<br>FavoritePlayer
DefaultLookup|Auto generated DefaultLookup field group|FanId<br>FullName<br>Status<br>FanSince
DefaultReport|Auto generated DefaultReport field group|FanId<br>FullName<br>Name<br>Status<br>FanSince<br>FavoritePlayer
DefaultIdentification|Auto generated DefaultIdentification field group|FanId<br>FullName
## Household (@Foundation.Household) Entity 
A group of individuals who share a living space. Individual household members are described in the HouseholdMember entity. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FullName | Data: Text<br>Maximum length: 128
HouseholdId<br>Primary key | Number sequence: <br>Unique<br>Description: Household number
HouseholdName | Data: Text<br>Maximum length: 128<br>Description: Organization name
MailingPostalAddress | Data: Address
OtherPostalAddress | Data: Address
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
ShippingPostalAddress | Data: Address
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: HouseholdStatus<br>Values: Active, Inactive<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultList|Auto generated DefaultList field group|FullName<br>Status<br>PhonePrimary
DefaultCard|Auto generated DefaultCard field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary
DefaultDetails|Auto generated DefaultDetails field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary<br>Description<br>MailingPostalAddress
DefaultLookup|Auto generated DefaultLookup field group|HouseholdId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|HouseholdId<br>FullName<br>Status<br>PhonePrimary<br>Description
DefaultIdentification|Auto generated DefaultIdentification field group|HouseholdId<br>FullName
## HouseholdMember (@Group.HouseholdMember) Entity 
A person who is a member of a household. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Household<br>Primary key | Lookup: Household<br>Required
HouseholdName | Data: Text<br>Maximum length: 128
Person | Lookup: Person<br>Required
PersonName | Data: Text<br>Maximum length: 128
PrimaryRole | Enumeration: HouseholdRole<br>Values: ElderSiblings, Father, GrandParents, Mother, YoungerSiblings<br>Required
Status | Enumeration: HouseholdMemberStatus<br>Values: Active, Inactive<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Person<br>Household<br>PersonName<br>PrimaryRole<br>Description
DefaultList|Auto generated DefaultList field group|Person<br>Household<br>PrimaryRole
DefaultCard|Auto generated DefaultCard field group|Household<br>Person<br>PrimaryRole
DefaultDetails|Auto generated DefaultDetails field group|Person<br>Household<br>PersonName<br>PrimaryRole<br>Description
DefaultLookup|Auto generated DefaultLookup field group|Household<br>Person<br>PrimaryRole
DefaultReport|Auto generated DefaultReport field group|Person<br>Household<br>PersonName<br>PrimaryRole
DefaultIdentification|Auto generated DefaultIdentification field group|Person<br>Household
## Organization (@Foundation.Organization) Entity 
@Foundation.Organization 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
IndustryCode | Enumeration: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
IsEmailContactAllowed | Data: Boolean<br>Required
IsInternal | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OrganizationId<br>Primary key | Number sequence: <br>Unique<br>Description: Organization number
OtherPostalAddress | Data: Address
ParentOrganization | Lookup: Organization
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
PrimaryContact | Lookup: Contact<br>Required
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: OrganizationStatus<br>Values: Active, Inactive<br>Required
StockExchange | Enumeration: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
Type | Enumeration: OrganizationType<br>Values: Corporation, Government, NonProfit, Other<br>Required<br>Description: OrganizationType
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization<br>PhonePrimary<br>EmailPrimary<br>MailingPostalAddress
DefaultList|Auto generated DefaultList field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization
DefaultCard|Auto generated DefaultCard field group|OrganizationId<br>FullName
DefaultDetails|Auto generated DefaultDetails field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization<br>PhonePrimary<br>EmailPrimary<br>MailingPostalAddress<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity<br>TaxIdentificationNumber<br>StockTicker
DefaultLookup|Auto generated DefaultLookup field group|OrganizationId<br>FullName
DefaultReport|Auto generated DefaultReport field group|OrganizationId<br>FullName<br>Description<br>ParentOrganization<br>PhonePrimary<br>EmailPrimary<br>TaxIdentificationNumber<br>StockTicker
DefaultIdentification|Auto generated DefaultIdentification field group|OrganizationId<br>FullName
## Person (@Foundation.Member) Entity 
@Person.MemberHelp 

Field | Description
---|---
Birthdate | Data: Date
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
Name | Data: PersonName
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OtherPostalAddress | Data: Address
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PersonId<br>Primary key | Number sequence: <br>Unique
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: PersonStatus<br>Values: Active, Inactive<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|FullName<br>Name<br>EmailPrimary<br>PhonePrimary<br>Description
DefaultList|Auto generated DefaultList field group|PersonId<br>FullName<br>Status
DefaultCard|Auto generated DefaultCard field group|FullName<br>EmailPrimary<br>PhonePrimary
DefaultDetails|Auto generated DefaultDetails field group|PersonId<br>FullName<br>Name<br>EmailPrimary<br>PhonePrimary<br>Description
DefaultLookup|Auto generated DefaultLookup field group|PersonId<br>FullName<br>EmailPrimary
DefaultReport|Auto generated DefaultReport field group|PersonId<br>FullName<br>Name<br>EmailPrimary<br>PhonePrimary
DefaultIdentification|Auto generated DefaultIdentification field group|PersonId<br>FullName
## Team (@Foundation.Team) Entity 
A team in an organization or group. Individual team members are described in the TeamMember entity. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FullName | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OtherPostalAddress | Data: Address
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
ShippingPostalAddress | Data: Address
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: TeamStatus<br>Values: Active, Inactive<br>Required
TeamId<br>Primary key | Number sequence: <br>Unique<br>Description: Team number
TeamName | Data: Text<br>Maximum length: 128<br>Description: Organization name
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|FullName<br>Description<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultList|Auto generated DefaultList field group|FullName<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultCard|Auto generated DefaultCard field group|FullName<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultDetails|Auto generated DefaultDetails field group|FullName<br>TeamId<br>Description<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultLookup|Auto generated DefaultLookup field group|FullName<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultReport|Auto generated DefaultReport field group|FullName<br>TeamId<br>Description<br>Status<br>PhonePrimary<br>EmailPrimary
DefaultIdentification|Auto generated DefaultIdentification field group|TeamId<br>FullName
## TeamMember (@Group.TeamMember) Entity 
A person who is a member of a team. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
Person | Lookup: Person<br>Required
PersonName | Data: Text<br>Maximum length: 128
PrimaryRole | Enumeration: TeamRole<br>Values: Coach, Lead, Manager, Player, Reserve, TeamLeader, TeamMember<br>Required
Status | Enumeration: TeamMemberStatus<br>Values: Active, Inactive<br>Required
Team<br>Primary key | Lookup: Team<br>Required
TeamName | Data: Text<br>Maximum length: 128

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Person<br>Team<br>PersonName<br>PrimaryRole
DefaultList|Auto generated DefaultList field group|Person<br>Team<br>PrimaryRole
DefaultCard|Auto generated DefaultCard field group|Person<br>Team<br>PrimaryRole
DefaultDetails|Auto generated DefaultDetails field group|Person<br>Team<br>PersonName<br>PrimaryRole
DefaultLookup|Auto generated DefaultLookup field group|Person<br>Team<br>PrimaryRole
DefaultReport|Auto generated DefaultReport field group|PrimaryRole<br>Person<br>Team<br>PersonName
DefaultIdentification|Auto generated DefaultIdentification field group|Person<br>Team
## Tenant (@Foundation.Tenant) Entity 
A person, organization, or group that leases space. 

Field | Description
---|---
Birthdate | Data: Date
BusinessPostalAddress | Data: Address
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PersonName | Data: PersonName
PersonName_Surame | Data: Text<br>Maximum length: 128<br>Description: Surname
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: TenantStatus<br>Values: Active, Inactive<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TenantId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|TenantId<br>FullName<br>PersonName<br>PersonName_Surame<br>Status<br>PhonePrimary<br>HomePostalAddress
DefaultList|Auto generated DefaultList field group|FullName<br>Status
DefaultCard|Auto generated DefaultCard field group|FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|TenantId<br>FullName<br>PersonName<br>PersonName_Surame<br>Status<br>PhonePrimary<br>HomePostalAddress
DefaultLookup|Auto generated DefaultLookup field group|FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|TenantId<br>FullName<br>PersonName<br>PersonName_Surame<br>Status<br>PhonePrimary<br>HomePostalAddress
DefaultIdentification|Auto generated DefaultIdentification field group|TenantId<br>FullName
## Worker (@Foundation.Worker) Entity 
@Foundation.Worker 

Field | Description
---|---
BusinessPostalAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit<br>Required
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
HomePostalAddress | Data: Address
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
Manager | Lookup: Worker
Name | Data: PersonName
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PhoneBusiness | Data: Phone<br>Description: Phone 03
PhoneCell | Data: Phone<br>Description: Phone 02
PhoneHome | Data: Phone<br>Description: Phone 01
PhonePrimary | Data: Phone
Profession | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: WorkerStatus<br>Values: Active, Inactive<br>Required
TwitterIdentity | Data: Text<br>Maximum length: 128
Type | Enumeration: WorkerType<br>Values: Contractor, Employee<br>Required
WebsiteURL | Data: Text<br>Maximum length: 255
WorkerId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|FullName<br>Name<br>Status<br>Description<br>Manager<br>BusinessUnit
DefaultList|Auto generated DefaultList field group|WorkerId<br>FullName<br>Status<br>Manager<br>BusinessUnit
DefaultCard|Auto generated DefaultCard field group|WorkerId<br>FullName<br>Status<br>Manager<br>BusinessUnit
DefaultDetails|Auto generated DefaultDetails field group|WorkerId<br>FullName<br>Name<br>Status<br>Description<br>Manager<br>BusinessUnit<br>PhoneCell<br>PhoneBusiness<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity<br>HomePostalAddress
DefaultLookup|Auto generated DefaultLookup field group|WorkerId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|WorkerId<br>FullName<br>Name<br>Status<br>Manager<br>BusinessUnit<br>PhoneCell<br>PhoneBusiness<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity
DefaultIdentification|Auto generated DefaultIdentification field group|WorkerId<br>FullName

