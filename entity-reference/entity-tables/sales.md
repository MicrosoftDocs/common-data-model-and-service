---
title: "Sales reference | Microsoft Docs"
description: "The sales entities let you create end-to-end sales solutions."
author: "robinarh"
manager: "robinarh"
ms.date: "05/08/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "9ba908bd-88f9-4236-96be-401c9da4d3a2"
ms.reviewer: robinr
ms.author: robinr
---

# Sales reference 
## Account (Account) Entity 
A person or organization that buys offered goods or services. 

Field | Description
---|---
AccountGroup | Lookup: AccountGroup
AccountId<br>Primary key | Number sequence: <br>Unique, Searchable
Birthdate | Data: Date
BusinessUnit | Lookup: BusinessUnit
CreditLimitAmount | Data: Currency<br>Decimal places: 6
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
EmployeeCount | Data: Integer
FacebookIdentity | Data: Text<br>Maximum length: 128
FreightTerms | Picklist: FreightTerms<br>Values: FOB, NoCharge
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, Nonspecific, NotSpecified
IndustryCode | Picklist: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
MaritalStatus | Picklist: MaritalStatus<br>Values: Divorced, Married, None, Single, Widowed
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Organization | Lookup: Organization
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
ParentAccount | Lookup: Account
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PaymentTerms | Picklist: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
PersonInformation | Data: Text<br>Maximum length: 2048
PersonName | Data: PersonName<br>Description: Given name
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhoneFax | Data: Phone
PhonePrimary | Data: Phone
PrimaryContact | Lookup: Contact
SalesCurrencyCode | Picklist: CurrencyCode<br>Values: AED, AFN, ALL, AMD, ANG, AOA, ARS, AUD, AWG, AZN, BAM, BBD, BDT, BGN, BHD, BIF, BMD, BND, BOB, BOV, BRL, BSD, BTN, BWP, BYN, BYR, BZD, CAD, CDF, CHE, CHF, CHW, CLF, CLP, CNY, COP, COU, CRC, CUC, CUP, CVE, CZK, DJF, DKK, DOP, DZD, EGP, ERN, ETB, EUR, FJD, FKP, GBP, GEL, GHS, GIP, GMD, GNF, GTQ, GYD, HKD, HNL, HRK, HTG, HUF, IDR, ILS, INR, IQD, IRR, ISK, JMD, JOD, JPY, KES, KGS, KHR, KMF, KPW, KRW, KWD, KYD, KZT, LAK, LBP, LKR, LRD, LSL, LYD, MAD, MDL, MGA, MKD, MMK, MNT, MOP, MRO, MUR, MVR, MWK, MXN, MXV, MYR, MZN, NAD, NGN, NIO, NOK, NPR, NZD, OMR, PAB, PEN, PGK, PHP, PKR, PLN, PYG, QAR, RON, RSD, RUB, RWF, SAR, SBD, SCR, SDG, SEK, SGD, SHP, SLL, SOS, SRD, SSP, STD, SVC, SYP, SZL, THB, TJS, TMT, TND, TOP, TRY, TTD, TWD, TZS, UAH, UGX, USD, USN, UYI, UYU, UZS, VEF, VND, VUV, WST, XAF, XAG, XAU, XBA, XBB, XBC, XBD, XCD, XDR, XOF, XPD, XPF, XPT, XSU, XTS, XUA, XXX, YER, ZAR, ZMW, ZWL
SatoriId | Data: Text<br>Maximum length: 128
ShippingMethod | Picklist: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: AccountStatus<br>Values: Active, Inactive<br>Required
StockExchange | Picklist: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Contact|Primary contact|OneToMany|Association
Account|Parent account|OneToMany|Association
AccountGroup|Account group|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|FullName<br>PersonName<br>Status<br>ParentAccount<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary<br>PartyType<br>Source<br>IsEmailContactAllowed<br>IsPhoneContactAllowed
DefaultList|DefaultList field group|AccountId<br>FullName<br>Status<br>PhonePrimary<br>WebsiteURL
DefaultCard|DefaultCard field group|AccountId<br>FullName<br>Status
DefaultDetails|DefaultDetails field group|AccountId<br>FullName<br>PersonName<br>Status<br>ParentAccount<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary<br>MailingPostalAddress<br>ShippingPostalAddress
DefaultLookup|DefaultLookup field group|AccountId<br>FullName<br>Status
DefaultReport|DefaultReport field group|AccountId<br>FullName<br>PersonName<br>Status<br>ParentAccount<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultIdentification|DefaultIdentification field group|AccountId<br>FullName

## AccountContact (Account contact) Entity 
Associates an account and a contact. This entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Account<br>Primary key | Lookup: Account<br>Required
Contact | Lookup: Contact<br>Required
DataSource | Picklist: Source<br>Values: Default<br>Required<br>Description: Source
Description | Data: Text<br>Maximum length: 128

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Account|Account|OneToMany|Association
Contact|Contact|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Account<br>Contact<br>DataSource<br>Description
DefaultList|DefaultList field group|Account<br>Contact<br>DataSource<br>Description
DefaultCard|DefaultCard field group|Account<br>Contact<br>DataSource<br>Description
DefaultDetails|DefaultDetails field group|Account<br>Contact<br>DataSource<br>Description
DefaultLookup|DefaultLookup field group|Account<br>Contact<br>DataSource<br>Description
DefaultReport|DefaultReport field group|Account<br>Contact<br>DataSource<br>Description
DefaultIdentification|DefaultIdentification field group|Account<br>Contact

## AccountGroup (Account group) Entity 
A collection of accounts. 

Field | Description
---|---
AccountGroupId<br>Primary key | Number sequence: <br>Unique, Searchable
Description | Data: Text<br>Maximum length: 128
Name | Data: Text<br>Required, Searchable, Maximum length: 128
Organization | Lookup: Organization

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|AccountGroupId<br>Name<br>Description
DefaultList|DefaultList field group|AccountGroupId<br>Name
DefaultCard|DefaultCard field group|AccountGroupId<br>Name
DefaultDetails|DefaultDetails field group|AccountGroupId<br>Name<br>Description
DefaultLookup|DefaultLookup field group|AccountGroupId<br>Name
DefaultReport|DefaultReport field group|AccountGroupId<br>Name
DefaultIdentification|DefaultIdentification field group|AccountGroupId<br>Name

## AccountLead (Account lead) Entity 
Associates a account and a lead. this entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Account<br>Primary key | Lookup: Account<br>Required
Lead | Lookup: Lead<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Lead|Lead|OneToMany|Association
Account|Account|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Account<br>Lead
DefaultCreate|DefaultCreate field group|Account<br>Lead
DefaultDetails|DefaultDetails field group|Account<br>Lead
DefaultIdentification|DefaultIdentification field group|Account<br>Lead
DefaultList|DefaultList field group|Account<br>Lead
DefaultLookup|DefaultLookup field group|Account<br>Lead
DefaultReport|DefaultReport field group|Account<br>Lead

## AccountOtherPostalAddress (Account other postal address) Entity 
A postal address that is associated with an account. It is separate from the shipping address and the mailing address. 

Field | Description
---|---
Account | Lookup: Account<br>Required
AddressId<br>Primary key | Number sequence: <br>Unique, Searchable
Description | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Account|Account|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Account<br>Description<br>OtherPostalAddress
DefaultList|DefaultList field group|Account<br>Description<br>OtherPostalAddress
DefaultCard|DefaultCard field group|Account<br>Description<br>OtherPostalAddress
DefaultDetails|DefaultDetails field group|Account<br>Description<br>OtherPostalAddress
DefaultLookup|DefaultLookup field group|Account<br>Description<br>OtherPostalAddress
DefaultReport|DefaultReport field group|Account<br>Description<br>OtherPostalAddress
DefaultIdentification|DefaultIdentification field group|AddressId<br>Account

## Competitor (Competitor) Entity 
Business competing for the sale represented by a lead or opportunity. 

Field | Description
---|---
CompetitorId<br>Primary key | Number sequence: <br>Unique, Searchable
Description | Data: Text<br>Maximum length: 2048
DUNSNumber | Data: Text<br>Maximum length: 2048
EmailAlternate | Data: Text<br>Maximum length: 80
EmailPrimary | Data: Text<br>Maximum length: 80
FacebookIdentity | Data: Text<br>Maximum length: 2048
FullName | Data: Text<br>Maximum length: 2048
IndustryCode | Picklist: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
KeyProductName | Data: Text<br>Maximum length: 2048
LinkedInIdentity | Data: Text<br>Maximum length: 2048
MailingPostalAddress | Data: Address
OpportunityDescription | Data: Memo
Organization | Lookup: Organization
OrganizationName | Data: Text<br>Maximum length: 2048
OtherPostalAddress | Data: Address
OverviewDescription | Data: Memo
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person
PersonName | Data: PersonName<br>Description: Given name
Phone01 | Data: Text<br>Maximum length: 32
Phone02 | Data: Text<br>Maximum length: 32
Phone03 | Data: Text<br>Maximum length: 32
PrimaryContact | Lookup: Contact
ReferenceInfoURL | Data: Text<br>Maximum length: 2048
ReportedAnnualRevenue | Data: Currency<br>Decimal places: 6
ReportingQuarter | Data: Integer
ReportingYear | Data: Integer
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 2048
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 2048
Source | Picklist: Source<br>Values: Default
Status | Picklist: CompetitorStatus<br>Values: Active, Inactive
StockExchange | Data: Text<br>Maximum length: 2048
StockTicker | Data: Text<br>Maximum length: 2048
StrengthDescription | Data: Memo
ThreatDescription | Data: Memo
TransactionCurrency | Picklist: CurrencyCode<br>Values: AED, AFN, ALL, AMD, ANG, AOA, ARS, AUD, AWG, AZN, BAM, BBD, BDT, BGN, BHD, BIF, BMD, BND, BOB, BOV, BRL, BSD, BTN, BWP, BYN, BYR, BZD, CAD, CDF, CHE, CHF, CHW, CLF, CLP, CNY, COP, COU, CRC, CUC, CUP, CVE, CZK, DJF, DKK, DOP, DZD, EGP, ERN, ETB, EUR, FJD, FKP, GBP, GEL, GHS, GIP, GMD, GNF, GTQ, GYD, HKD, HNL, HRK, HTG, HUF, IDR, ILS, INR, IQD, IRR, ISK, JMD, JOD, JPY, KES, KGS, KHR, KMF, KPW, KRW, KWD, KYD, KZT, LAK, LBP, LKR, LRD, LSL, LYD, MAD, MDL, MGA, MKD, MMK, MNT, MOP, MRO, MUR, MVR, MWK, MXN, MXV, MYR, MZN, NAD, NGN, NIO, NOK, NPR, NZD, OMR, PAB, PEN, PGK, PHP, PKR, PLN, PYG, QAR, RON, RSD, RUB, RWF, SAR, SBD, SCR, SDG, SEK, SGD, SHP, SLL, SOS, SRD, SSP, STD, SVC, SYP, SZL, THB, TJS, TMT, TND, TOP, TRY, TTD, TWD, TZS, UAH, UGX, USD, USN, UYI, UYU, UZS, VEF, VND, VUV, WST, XAF, XAG, XAU, XBA, XBB, XBC, XBD, XCD, XDR, XOF, XPD, XPF, XPT, XSU, XTS, XUA, XXX, YER, ZAR, ZMW, ZWL
TwitterIdentity | Data: Text<br>Maximum length: 2048
Weaknesses | Data: Memo<br>Description: Weakness
WebsiteURL | Data: Text<br>Maximum length: 2048
WinPercentage | Data: Integer

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Contact|Primary contact|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|CompetitorId<br>OrganizationName
DefaultCreate|DefaultCreate field group|CompetitorId<br>OrganizationName<br>Status<br>OverviewDescription
DefaultDetails|DefaultDetails field group|CompetitorId<br>OrganizationName<br>Status<br>OverviewDescription
DefaultIdentification|DefaultIdentification field group|CompetitorId<br>OrganizationName
DefaultList|DefaultList field group|CompetitorId<br>OrganizationName<br>Status
DefaultLookup|DefaultLookup field group|CompetitorId<br>OrganizationName
DefaultReport|DefaultReport field group|CompetitorId<br>OrganizationName<br>Status<br>OverviewDescription

## CompetitorOtherPostalAddress (Competitor other postal address) Entity 
Additional addresses for a competitor. 

Field | Description
---|---
AddressId<br>Primary key | Number sequence: <br>Unique, Searchable
Competitor | Lookup: Competitor
Description | Data: Text<br>Maximum length: 2048
OtherPostalAddress | Data: Address

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Competitor|Competitor|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|AddressId<br>Description
DefaultCreate|DefaultCreate field group|AddressId<br>Description<br>OtherPostalAddress<br>Competitor
DefaultDetails|DefaultDetails field group|AddressId<br>Description<br>OtherPostalAddress<br>Competitor
DefaultIdentification|DefaultIdentification field group|AddressId<br>Description
DefaultList|DefaultList field group|AddressId<br>Description<br>Competitor
DefaultLookup|DefaultLookup field group|AddressId<br>Description
DefaultReport|DefaultReport field group|AddressId<br>Description<br>OtherPostalAddress<br>Competitor

## CompetitorProduct (Competitor product) Entity 
Association between a competitor and a product offered by the competitor. 

Field | Description
---|---
Competitor<br>Primary key | Lookup: Competitor<br>Required
CompetitorProductId | Data: Text<br>Maximum length: 2048
Product | Lookup: Product<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Product|Product|OneToMany|Association
Competitor|Competitor|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Competitor<br>Product
DefaultCreate|DefaultCreate field group|Competitor<br>Product
DefaultDetails|DefaultDetails field group|Competitor<br>Product
DefaultIdentification|DefaultIdentification field group|Competitor<br>Product
DefaultList|DefaultList field group|Competitor<br>Product
DefaultLookup|DefaultLookup field group|Competitor<br>Product
DefaultReport|DefaultReport field group|Competitor<br>Product

## ContactLead (Contact lead) Entity 
Associates a contract and a lead. this entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Contact<br>Primary key | Lookup: Contact<br>Required
Lead | Lookup: Lead<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Lead|Lead|OneToMany|Association
Contact|Contact|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Contact<br>Lead
DefaultCreate|DefaultCreate field group|Contact<br>Lead
DefaultDetails|DefaultDetails field group|Contact<br>Lead
DefaultIdentification|DefaultIdentification field group|Contact<br>Lead
DefaultList|DefaultList field group|Contact<br>Lead
DefaultLookup|DefaultLookup field group|Contact<br>Lead
DefaultReport|DefaultReport field group|Contact<br>Lead

## Lead (Lead) Entity 
A person who is interested in receiving information about the products or services that the company offers. 

Field | Description
---|---
Account | Lookup: Account
AnnualRevenue | Data: Currency<br>Decimal places: 6
Birthdate | Data: Date
BudgetAmount | Data: Currency<br>Decimal places: 6
BudgetStatus | Picklist: BudgetStatus<br>Values: CanBuy, MayBuy, NoCommittedBudget, WillBuy
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
EstimatedAmount | Data: Currency<br>Decimal places: 6
EstimatedCloseDate | Data: DateTime
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, Nonspecific, NotSpecified
Generation | Data: Text<br>Maximum length: 128
IndustryCode | Picklist: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
IsDecisionMaker | Data: Boolean
IsEmailContactAllowed | Data: Boolean<br>Required
IsInterestConfirmed | Data: Boolean<br>Description: Interest confirmed
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LastCampaignDate | Data: DateTime
LeadId<br>Primary key | Number sequence: <br>Unique, Searchable
LeadRating | Picklist: LeadRating<br>Values: Cold, Hot, Warm<br>Description: Rating
LeadSource | Picklist: LeadSource<br>Values: Advertisement, EmployeeReferral, ExternalReferral, Other, Partner, PublicRelations, Seminar, TradeShow, Web, WordOfMouth
LinkedInIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Organization | Lookup: Organization
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PersonName | Data: PersonName<br>Description: Given name
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
PreferredContactMethod | Picklist: ContactMethod<br>Values: Any, Email, Fax, Mail, Phone
Profession | Data: Text<br>Maximum length: 128
PurchaseTimeline | Picklist: PurchaseTimeframe<br>Values: Immediate, NextQuarter, ThisQuarter, ThisYear, Unknown
QualificationDescription | Data: Memo
QualifyingOpportunity | Lookup: Opportunity
SatoriId | Data: Text<br>Maximum length: 128
ScheduleFollowUpProspect | Data: DateTime<br>Description: Schedule propsect follow up
ScheduleFollowUpQualify | Data: DateTime<br>Description: Schedule qualify follow up
ShippingPostalAddress | Data: Address
SIC | Data: Text<br>Maximum length: 2048<br>Description: SIC code
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: LeadStatus<br>Values: Cancelled, Contacted, Disqualified, New, NoLongerInterested, Qualified<br>Required
StockExchange | Picklist: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
BusinessUnit|Business unit|OneToMany|Association
Opportunity|Qualifying opportunity|OneToMany|Association
Account|Account|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PersonName<br>Status<br>WebsiteURL<br>PartyType<br>Source<br>IsEmailContactAllowed<br>IsPhoneContactAllowed<br>IsSecurityPrincipal
DefaultList|DefaultList field group|LeadId<br>FullName<br>Status<br>WebsiteURL<br>Source
DefaultCard|DefaultCard field group|LeadId<br>FullName<br>Status
DefaultDetails|DefaultDetails field group|LeadId<br>FullName<br>PersonName<br>Status<br>WebsiteURL<br>Source<br>Description<br>PhonePrimary<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultLookup|DefaultLookup field group|LeadId<br>FullName<br>Status
DefaultReport|DefaultReport field group|LeadId<br>FullName<br>PersonName<br>Status<br>WebsiteURL<br>Source<br>PhonePrimary<br>EmailPrimary
DefaultIdentification|DefaultIdentification field group|LeadId<br>FullName

## LeadCompetitor (Lead competitor) Entity 
Associates a lead and a competitor. this entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Competitor<br>Primary key | Lookup: Competitor<br>Required
Lead | Lookup: Lead<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Lead|Lead|OneToMany|Association
Competitor|Competitor|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Competitor<br>Lead
DefaultCreate|DefaultCreate field group|Competitor<br>Lead
DefaultDetails|DefaultDetails field group|Competitor<br>Lead
DefaultIdentification|DefaultIdentification field group|Competitor<br>Lead
DefaultList|DefaultList field group|Competitor<br>Lead
DefaultLookup|DefaultLookup field group|Competitor<br>Lead
DefaultReport|DefaultReport field group|Competitor<br>Lead

## LeadContact (Lead contact) Entity 
Associates a lead and a contact. This entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Contact | Lookup: Contact<br>Required
DataSource | Picklist: Source<br>Values: Default<br>Required<br>Description: Source
Description | Data: Text<br>Maximum length: 128
Lead<br>Primary key | Lookup: Lead<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Lead|Lead|OneToMany|Association
Contact|Contact|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Lead<br>Contact<br>DataSource<br>Description
DefaultList|DefaultList field group|Lead<br>Contact<br>DataSource<br>Description
DefaultCard|DefaultCard field group|Lead<br>Contact<br>DataSource<br>Description
DefaultDetails|DefaultDetails field group|Lead<br>Contact<br>DataSource<br>Description
DefaultLookup|DefaultLookup field group|Lead<br>Contact<br>DataSource<br>Description
DefaultReport|DefaultReport field group|Lead<br>Contact<br>DataSource<br>Description
DefaultIdentification|DefaultIdentification field group|Lead<br>Contact

## LeadOtherPostalAddress (Lead other postal address) Entity 
Additional addresses for a lead. 

Field | Description
---|---
AddressId<br>Primary key | Number sequence: <br>Unique, Searchable
Description | Data: Text<br>Maximum length: 2048
Lead | Lookup: Lead
OtherPostalAddress | Data: Address

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Lead|Lead|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|AddressId<br>Description
DefaultCreate|DefaultCreate field group|AddressId<br>Description<br>OtherPostalAddress<br>Lead
DefaultDetails|DefaultDetails field group|AddressId<br>Description<br>OtherPostalAddress<br>Lead
DefaultIdentification|DefaultIdentification field group|AddressId<br>Description
DefaultList|DefaultList field group|AddressId<br>Description<br>Lead
DefaultLookup|DefaultLookup field group|AddressId<br>Description
DefaultReport|DefaultReport field group|AddressId<br>Description<br>OtherPostalAddress<br>Lead

## LeadProduct (Lead product) Entity 
Associates a lead and a product. this entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Lead<br>Primary key | Lookup: Lead<br>Required
Product | Lookup: Product<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Product|Product|OneToMany|Association
Lead|Lead|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Lead<br>Product
DefaultCreate|DefaultCreate field group|Lead<br>Product
DefaultDetails|DefaultDetails field group|Lead<br>Product
DefaultIdentification|DefaultIdentification field group|Lead<br>Product
DefaultList|DefaultList field group|Lead<br>Product
DefaultLookup|DefaultLookup field group|Lead<br>Product
DefaultReport|DefaultReport field group|Lead<br>Product

## Opportunity (Opportunity) Entity 
Information about potential sales to new or established customers. 

Field | Description
---|---
ActualCloseDate | Data: DateTime
ActualValueAmount | Data: Currency<br>Required, Decimal places: 6
BudgetAmount | Data: Currency<br>Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
CloseProbability | Data: Integer
CompetitorsIdentified | Data: Boolean
Contact | Lookup: Contact
CreatedDate | Data: Date<br>Required
CurrentSituationDescription | Data: Memo
CustomerContactsIdentified | Data: Boolean
CustomerNeedDescription | Data: Memo
CustomerPainPointsDescription | Data: Memo
Description | Data: Text<br>Maximum length: 128
DiscountAmount | Data: Currency<br>Decimal places: 6
DiscountPercentage | Data: Integer
EstimatedCloseDate | Data: DateTime
EstimatedValueAmount | Data: Currency<br>Required, Decimal places: 6
FollowupProspectDate | Data: DateTime
FollowupQualifyDate | Data: DateTime
IndustryCode | Picklist: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale<br>Required
IsDecisionMaker | Data: Boolean
Name | Data: Text<br>Required, Maximum length: 128
NextFollowupDate | Data: Date<br>Description: Next follow-up date
OpportunityId<br>Primary key | Number sequence: <br>Unique, Searchable
Organization | Lookup: Organization
OriginalEstimatedValueAmount | Data: Currency<br>Required, Decimal places: 6
OriginatingLead | Lookup: Lead
ParentOpportunity | Lookup: Opportunity
ProposalMeetingDate | Data: DateTime
ProposedSolutionDescription | Data: Memo
PurchaseProcess | Picklist: Process<br>Values: Committee, Individual, Unknown<br>Required
PurchaseTimeFrame | Picklist: TimeFrame<br>Values: Day, HalfYear, Hour, Month, Quarter, Trimester, Week, Year<br>Required
QualificationDescription | Data: Memo
RatingCode | Picklist: HotWarmCold<br>Values: Cold, Hot, Warm<br>Required
SalesStage | Picklist: OpportunityState<br>Values: Lost, Open, Won
SalesTeamIdentified | Data: Boolean
Source | Picklist: OpportunitySource<br>Values: Advertisement, EmployeeReferral, ExternalReferral, Other, Partner, PublicRelations, Seminar, TradeShow, Web, WordOfMouth<br>Required
Status | Picklist: OpportunityStatus<br>Values: Canceled, InProgress, OnHold, OutSold, Won<br>Required
Timeline | Picklist: PurchaseTimeframe<br>Values: Immediate, NextQuarter, ThisQuarter, ThisYear, Unknown

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Opportunity|Parent opportunity|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association
Lead|Originating lead|OneToMany|Association
Contact|Contact|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>Status<br>EstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame<br>PurchaseProcess<br>SalesStage<br>Description<br>CreatedDate<br>IndustryCode<br>RatingCode<br>Source
DefaultList|DefaultList field group|OpportunityId<br>Name<br>Status<br>EstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame
DefaultCard|DefaultCard field group|OpportunityId<br>Name<br>Status
DefaultDetails|DefaultDetails field group|OpportunityId<br>Name<br>Status<br>EstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame<br>PurchaseProcess<br>SalesStage<br>Description<br>CreatedDate<br>Source<br>IndustryCode<br>RatingCode
DefaultLookup|DefaultLookup field group|OpportunityId<br>Name<br>Status
DefaultReport|DefaultReport field group|OpportunityId<br>Name<br>Status<br>EstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame<br>PurchaseProcess<br>SalesStage<br>Description<br>CreatedDate<br>Source<br>IndustryCode<br>RatingCode
DefaultIdentification|DefaultIdentification field group|OpportunityId<br>Name

## OpportunityCompetitor (Opportunity competitor) Entity 
Associates a opportunity and a competitor. this entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Competitor<br>Primary key | Lookup: Competitor<br>Required
Opportunity | Lookup: Opportunity<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Opportunity|Opportunity|OneToMany|Association
Competitor|Competitor|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Competitor<br>Opportunity
DefaultCreate|DefaultCreate field group|Competitor<br>Opportunity
DefaultDetails|DefaultDetails field group|Competitor<br>Opportunity
DefaultIdentification|DefaultIdentification field group|Competitor<br>Opportunity
DefaultList|DefaultList field group|Competitor<br>Opportunity
DefaultLookup|DefaultLookup field group|Competitor<br>Opportunity
DefaultReport|DefaultReport field group|Competitor<br>Opportunity

## OpportunityProduct (Opportunity product) Entity 
Associates a opportunity and a product. this entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Description | Data: Memo
DiscountAmount | Data: Currency<br>Decimal places: 6
IsPriceOverridden | Data: Boolean
LineAmount | Data: Currency<br>Decimal places: 6
Opportunity<br>Primary key | Lookup: Opportunity<br>Required
Product | Lookup: Product<br>Required
Quantity | Data: Quantity
Sequence | Data: Integer
TotalTaxAmount | Data: Currency<br>Decimal places: 6
UnitPrice | Data: Currency<br>Decimal places: 6

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Product|Product|OneToMany|Association
Opportunity|Opportunity|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Product<br>Opportunity<br>Description
DefaultCreate|DefaultCreate field group|Description<br>LineAmount<br>Opportunity<br>Product
DefaultDetails|DefaultDetails field group|Description<br>LineAmount<br>Opportunity<br>Product
DefaultIdentification|DefaultIdentification field group|Description<br>Product
DefaultList|DefaultList field group|Description<br>LineAmount<br>Opportunity<br>Product
DefaultLookup|DefaultLookup field group|Product<br>Opportunity
DefaultReport|DefaultReport field group|Description<br>LineAmount<br>Opportunity<br>Product

## Partner (Partner) Entity 
An organization that takes part in a business relationship with another organization with shared risks and profits. 

Field | Description
---|---
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
IndustryCode | Picklist: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
Organization | Lookup: Organization
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
ParentPartner | Lookup: Partner
PartnerId<br>Primary key | Number sequence: <br>Unique, Searchable
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
PrimaryContact | Lookup: Contact
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Picklist: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: PartnerStatus<br>Values: Active, Inactive<br>Required
StockExchange | Picklist: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Partner|Parent partner|OneToMany|Association
Contact|Primary contact|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PhonePrimary<br>ParentPartner<br>WebsiteURL<br>PartyType<br>Source<br>IsEmailContactAllowed<br>IsPhoneContactAllowed<br>IsSecurityPrincipal<br>Status
DefaultList|DefaultList field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL
DefaultCard|DefaultCard field group|PartnerId<br>FullName<br>PhonePrimary
DefaultDetails|DefaultDetails field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL<br>Description<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>StockTicker
DefaultLookup|DefaultLookup field group|PartnerId<br>FullName<br>PhonePrimary
DefaultReport|DefaultReport field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>MailingPostalAddress<br>StockTicker
DefaultIdentification|DefaultIdentification field group|PartnerId<br>FullName

## Quotation (Quotation) Entity 
A sales quote prepared for a customer. 

Field | Description
---|---
Account | Lookup: Account<br>Required
AccountContact | Lookup: Contact
BillingAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit
CustomerPurchaseOrderReference | Data: Text<br>Maximum length: 20
DeliveryAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
DiscountPercent | Data: Number<br>Required
ExpectedShipDate | Data: DateTime
ExpirationDate | Data: Date<br>Required
FreightTerms | Picklist: FreightTerms<br>Values: FOB, NoCharge
InvoiceAccount | Lookup: Account
Name | Data: Text<br>Maximum length: 60
Opportunity | Lookup: Opportunity
Organization | Lookup: Organization
PaymentTerms | Picklist: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
QuotationDate | Data: Date<br>Required
QuotationId<br>Primary key | Number sequence: <br>Unique, Searchable
QuotationType | Picklist: QuotationType<br>Values: Maintainence, Product, Service<br>Required<br>Description: Type
RequestedDeliveryDate | Data: DateTime
SalesOrderReference | Data: Text<br>Maximum length: 128
SalesPersonWorker | Lookup: Worker<br>Description: Sales person
ShippingMethod | Picklist: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Picklist: QuotationStatus<br>Values: Active, Closed, Draft, Won<br>Required<br>Description: Quotation status
StatusReason | Picklist: QuotationStatusReason<br>Values: Active, Cancelled, Lost, Open, Revised, Won<br>Description: Quotation status reason
TotalAmount | Data: Currency<br>Required, Decimal places: 6
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6
TotalDiscountAmount | Data: Currency<br>Required, Decimal places: 6
TotalDiscountPercent | Data: Number<br>Required
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Account|Account|OneToMany|Association
Worker|Sales person|OneToMany|Association
Contact|Account contact|OneToMany|Association
Opportunity|Opportunity|OneToMany|Association
Account|Invoice account|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|QuotationId<br>Account<br>QuotationDate<br>CustomerPurchaseOrderReference<br>Status<br>QuotationType<br>Name<br>Description<br>SalesPersonWorker<br>AccountContact<br>ExpirationDate
DefaultList|DefaultList field group|QuotationId<br>Account<br>QuotationDate<br>CustomerPurchaseOrderReference<br>QuotationType<br>Status<br>SalesPersonWorker<br>TotalAmount
DefaultCard|DefaultCard field group|QuotationId<br>Account<br>QuotationDate<br>Status<br>TotalAmount
DefaultDetails|DefaultDetails field group|QuotationId<br>Account<br>QuotationDate<br>CustomerPurchaseOrderReference<br>QuotationType<br>Name<br>Description<br>SalesPersonWorker<br>AccountContact<br>TotalAmount<br>FreightTerms<br>ShippingMethod<br>InvoiceAccount<br>BillingAddress<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|QuotationId<br>Account<br>QuotationDate<br>Status<br>TotalAmount
DefaultReport|DefaultReport field group|QuotationId<br>Account<br>QuotationDate<br>CustomerPurchaseOrderReference<br>Status<br>QuotationType<br>Name<br>Description<br>SalesPersonWorker<br>AccountContact<br>TotalAmount
DefaultIdentification|DefaultIdentification field group|QuotationId<br>Name

## QuotationCharge (Quotation charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the whole quotation. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: ChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
Quotation<br>Primary key | Lookup: Quotation<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Quotation|Quotation|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Quotation<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|ChargeType<br>Quotation<br>Amount
DefaultCard|DefaultCard field group|ChargeType<br>Quotation<br>Amount
DefaultDetails|DefaultDetails field group|Quotation<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|Quotation<br>ChargeType<br>Amount
DefaultReport|DefaultReport field group|Quotation<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|DefaultIdentification field group|Quotation<br>Name

## QuotationLine (Quotation line) Entity 
A component of a quotation that contains a portion of the quoted amount including information such as product, quantity, and price. 

Field | Description
---|---
BusinessUnit | Lookup: BusinessUnit
DeliveryAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
DiscountPercent | Data: Number<br>Required
ExpectedShipDate | Data: DateTime
LineAmount | Data: Currency<br>Required, Decimal places: 6
MostRecentActualShipDate | Data: DateTime
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Product<br>Required
ProductName | Data: Text<br>Required, Maximum length: 60
PromisedShipDate | Data: DateTime
Quantity | Data: Quantity<br>Required
Quotation<br>Primary key | Lookup: Quotation<br>Required
RequestedDeliveryDate | Data: DateTime
Sequence | Data: Integer<br>Required
Status | Picklist: QuotationLineStatus<br>Values: Active, Closed, Draft, Won<br>Required<br>Description: Quotation line status
StatusReason | Picklist: QuotationLineStatusReason<br>Values: Active, Cancelled, Lost, Open, Revised, Won<br>Description: Quotation line status reason
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6
UnitPrice | Data: Currency<br>Required, Decimal places: 6

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Quotation|Quotation|OneToMany|Composition
Product|Product|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Quotation<br>Sequence<br>Product<br>Description<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>ProductName
DefaultList|DefaultList field group|Quotation<br>Product<br>ProductName<br>Status<br>Quantity<br>LineAmount
DefaultCard|DefaultCard field group|Quotation<br>Product<br>ProductName<br>Status<br>Quantity
DefaultDetails|DefaultDetails field group|Quotation<br>Sequence<br>Product<br>ProductName<br>Description<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>ExpectedShipDate<br>MostRecentActualShipDate<br>DeliveryAddress<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|Quotation<br>ProductName<br>Status<br>Quantity
DefaultReport|DefaultReport field group|Quotation<br>Product<br>ProductName<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>ExpectedShipDate<br>MostRecentActualShipDate
DefaultIdentification|DefaultIdentification field group|Sequence<br>ProductName

## QuotationLineCharge (Quotation line charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the quotation line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total line charges
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: LineChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
QuotationLine<br>Primary key | Lookup: QuotationLine<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
QuotationLine|Quotation line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|QuotationLine<br>ChargeType<br>Name<br>Amount
DefaultList|DefaultList field group|ChargeType<br>Name<br>Amount
DefaultCard|DefaultCard field group|ChargeType<br>Name<br>Amount
DefaultDetails|DefaultDetails field group|QuotationLine<br>ChargeType<br>Name<br>Amount
DefaultLookup|DefaultLookup field group|ChargeType<br>Name<br>Amount
DefaultReport|DefaultReport field group|QuotationLine<br>ChargeType<br>Name<br>Amount
DefaultIdentification|DefaultIdentification field group|QuotationLine<br>ChargeType

## QuotationLineTax (Quotation line tax) Entity 
Tax charged on a quotation line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total line taxes
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
QuotationLine<br>Primary key | Lookup: QuotationLine<br>Required
RateCode | Data: Text<br>Maximum length: 60
TaxType | Picklist: LineTaxType<br>Values: Others, SalesTax, VAT<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
QuotationLine|Quotation line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|QuotationLine<br>TaxType<br>Name<br>Amount
DefaultList|DefaultList field group|TaxType<br>Name<br>Amount
DefaultCard|DefaultCard field group|TaxType<br>Name<br>Amount
DefaultDetails|DefaultDetails field group|QuotationLine<br>TaxType<br>Name<br>Amount
DefaultLookup|DefaultLookup field group|TaxType<br>Name<br>Amount
DefaultReport|DefaultReport field group|QuotationLine<br>TaxType<br>Name<br>Amount
DefaultIdentification|DefaultIdentification field group|QuotationLine<br>TaxType

## QuotationTax (Quotation tax) Entity 
Tax charged on a quotation as a whole. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
Quotation<br>Primary key | Lookup: Quotation<br>Required
RateCode | Data: Text<br>Maximum length: 60
TaxType | Picklist: TaxType<br>Values: Others, SalesTax, VAT<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Quotation|Quotation|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Quotation<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultList|DefaultList field group|Quotation<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|Quotation<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|Quotation<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultLookup|DefaultLookup field group|Quotation<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|DefaultReport field group|Quotation<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultIdentification|DefaultIdentification field group|Quotation<br>Name

## SalesInvoice (Sales invoice) Entity 
An invoice sent to a customer to document the customer's liability for a purchase. 

Field | Description
---|---
Account | Lookup: Account
AccountContact | Lookup: Contact
BillingAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit
CustomerPurchaseOrderReference | Data: Text<br>Maximum length: 20
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
FreightTerms | Picklist: FreightTerms<br>Values: FOB, NoCharge
InvoiceDate | Data: DateTime<br>Required
Name | Data: Text<br>Maximum length: 60
Opportunity | Lookup: Opportunity
Organization | Lookup: Organization
PaymentTerms | Picklist: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
SalesInvoiceId<br>Primary key | Number sequence: <br>Unique, Searchable
SalesOrder | Lookup: SalesOrder
SalesPersonWorker | Lookup: Worker<br>Description: Sales person
ShippingMethod | Picklist: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Picklist: InvoiceStatus<br>Values: Cancelled, Created, Hold, Paid<br>Description: Invoice status
TotalAmount | Data: Currency<br>Decimal places: 6
TotalChargeAmount | Data: Currency<br>Decimal places: 6
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Account|Account|OneToMany|Association
Worker|Sales person|OneToMany|Association
Contact|Account contact|OneToMany|Association
Opportunity|Opportunity|OneToMany|Association
SalesOrder|Sales order|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|InvoiceDate<br>Name<br>Description<br>Account<br>CustomerPurchaseOrderReference<br>AccountContact<br>Status<br>BillingAddress
DefaultList|DefaultList field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Account<br>CustomerPurchaseOrderReference<br>Status<br>TotalAmount
DefaultCard|DefaultCard field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Account<br>Status<br>TotalAmount
DefaultDetails|DefaultDetails field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Description<br>Account<br>CustomerPurchaseOrderReference<br>AccountContact<br>Status<br>BillingAddress<br>TotalAmount<br>FreightTerms<br>PaymentTerms<br>SalesPersonWorker<br>ShippingMethod<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|SalesInvoiceId<br>InvoiceDate<br>Name<br>Account
DefaultReport|DefaultReport field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Description<br>Account<br>CustomerPurchaseOrderReference<br>AccountContact<br>Status<br>BillingAddress<br>TotalAmount<br>FreightTerms<br>PaymentTerms<br>SalesPersonWorker<br>ShippingMethod<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultIdentification|DefaultIdentification field group|SalesInvoiceId<br>Name

## SalesInvoiceCharge (Sales invoice charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the whole invoice. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: InvoiceChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesInvoice<br>Primary key | Lookup: SalesInvoice<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesInvoice|Sales invoice|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|SalesInvoice<br>ChargeType<br>Name<br>Amount
DefaultCard|DefaultCard field group|SalesInvoice<br>ChargeType<br>Name<br>Amount
DefaultDetails|DefaultDetails field group|SalesInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|SalesInvoice<br>ChargeType<br>Amount
DefaultReport|DefaultReport field group|SalesInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|DefaultIdentification field group|SalesInvoice<br>Name

## SalesInvoiceLine (Sales invoice line) Entity 
A component of a sales invoice that contains a portion of the invoiced amount including information such as product, quantity, and price. 

Field | Description
---|---
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
ExpectedShipDate | Data: DateTime
LineAmount | Data: Currency<br>Required, Decimal places: 6
MostRecentActualShipDate | Data: DateTime
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Product
ProductName | Data: Text<br>Required, Maximum length: 60
PromisedShipDate | Data: DateTime
Quantity | Data: Quantity<br>Required
SalesInvoice<br>Primary key | Lookup: SalesInvoice<br>Required
Sequence | Data: Integer<br>Required
Status | Picklist: InvoiceLineStatus<br>Values: Active, Confirmed, Invoice, PackingSlip, Quote<br>Required<br>Description: Invoice line status
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6
UnitPrice | Data: Currency<br>Required, Decimal places: 6

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesInvoice|Sales invoice|OneToMany|Composition
Product|Product|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity<br>Sequence<br>ProductName<br>UnitPrice
DefaultList|DefaultList field group|SalesInvoice<br>Product<br>Name<br>Status<br>Quantity<br>LineAmount
DefaultCard|DefaultCard field group|SalesInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultDetails|DefaultDetails field group|SalesInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|SalesInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultReport|DefaultReport field group|SalesInvoice<br>Product<br>Name<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultIdentification|DefaultIdentification field group|SalesInvoice<br>Sequence<br>Product

## SalesInvoiceLineCharge (Sales invoice line charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the invoice line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: InvoiceLineChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesInvoiceLine<br>Primary key | Lookup: SalesInvoiceLine<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesInvoiceLine|Sales invoice line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|ChargeType<br>Name<br>Amount
DefaultCard|DefaultCard field group|ChargeType<br>Name<br>Amount
DefaultDetails|DefaultDetails field group|SalesInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|ChargeType<br>Amount
DefaultReport|DefaultReport field group|SalesInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|DefaultIdentification field group|SalesInvoiceLine<br>Name

## SalesInvoiceLineTax (Sales invoice line tax) Entity 
Tax charged on a sales invoice line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesInvoiceLine<br>Primary key | Lookup: SalesInvoiceLine<br>Required
TaxType | Picklist: InvoiceLineTaxType<br>Values: Others, SalesTax, VAT<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesInvoiceLine|Sales invoice line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>RateCode<br>TaxType<br>Amount<br>SalesInvoiceLine
DefaultList|DefaultList field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|Name<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>SalesInvoiceLine
DefaultLookup|DefaultLookup field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|DefaultReport field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>SalesInvoiceLine
DefaultIdentification|DefaultIdentification field group|SalesInvoiceLine<br>Name

## SalesInvoiceTax (Sales invoice tax) Entity 
Tax charged on a sales invoice as a whole. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesInvoice<br>Primary key | Lookup: SalesInvoice<br>Required
TaxType | Picklist: InvoiceTaxType<br>Values: Others, SalesTax, VAT<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesInvoice|Sales invoice|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesInvoice<br>RateCode<br>TaxType<br>Name<br>Amount<br>Description
DefaultList|DefaultList field group|SalesInvoice<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|SalesInvoice<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|SalesInvoice<br>RateCode<br>TaxType<br>Name<br>Amount<br>Description
DefaultLookup|DefaultLookup field group|SalesInvoice<br>RateCode<br>Amount
DefaultReport|DefaultReport field group|SalesInvoice<br>RateCode<br>TaxType<br>Name<br>Amount
DefaultIdentification|DefaultIdentification field group|SalesInvoice<br>TaxType<br>RateCode

## SalesOrder (Sales order) Entity 
An order issued by a business to a customer for selling products and/or services. 

Field | Description
---|---
Account | Lookup: Account
AccountContact | Lookup: Contact
BillingAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit
CustomerPurchaseOrderReference | Data: Text<br>Maximum length: 20
DeliveryAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
ExpectedShipDate | Data: DateTime
FreightTerms | Picklist: FreightTerms<br>Values: FOB, NoCharge
InvoiceAccount | Lookup: Account
Name | Data: Text<br>Maximum length: 60
Opportunity | Lookup: Opportunity
OrderDate | Data: DateTime<br>Required
Organization | Lookup: Organization
PaymentTerms | Picklist: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
RequestedDeliveryDate | Data: DateTime
SalesOrderId<br>Primary key | Number sequence: <br>Unique, Searchable
SalesPersonWorker | Lookup: Worker<br>Description: Sales person
ShippingMethod | Picklist: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Picklist: OrderStatus<br>Values: Active, Cancelled, Confirmed, Invoice, PackingSlip, PartiallyInvoiced, PartiallyPacked, PartiallyPicked, PartiallyShipped, Picked, Quote, Shipped<br>Required<br>Description: Order status
TotalAmount | Data: Currency<br>Required, Decimal places: 6
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Account|Account|OneToMany|Association
Worker|Sales person|OneToMany|Association
Contact|Account contact|OneToMany|Association
Opportunity|Opportunity|OneToMany|Association
Account|Invoice account|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Account<br>OrderDate<br>CustomerPurchaseOrderReference<br>Status<br>Name<br>Description<br>SalesPersonWorker<br>AccountContact
DefaultList|DefaultList field group|SalesOrderId<br>Account<br>OrderDate<br>CustomerPurchaseOrderReference<br>Status<br>SalesPersonWorker<br>TotalAmount
DefaultCard|DefaultCard field group|SalesOrderId<br>Account<br>OrderDate<br>Status<br>TotalAmount
DefaultDetails|DefaultDetails field group|SalesOrderId<br>Account<br>OrderDate<br>CustomerPurchaseOrderReference<br>Status<br>Name<br>Description<br>SalesPersonWorker<br>AccountContact<br>TotalAmount<br>FreightTerms<br>ShippingMethod<br>DeliveryAddress<br>BillingAddress<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|SalesOrderId<br>Account<br>OrderDate<br>Status<br>TotalAmount
DefaultReport|DefaultReport field group|SalesOrderId<br>Account<br>OrderDate<br>CustomerPurchaseOrderReference<br>Status<br>Name<br>Description<br>SalesPersonWorker<br>AccountContact<br>TotalAmount
DefaultIdentification|DefaultIdentification field group|SalesOrderId<br>Name

## SalesOrderCharge (Sales order charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the whole sales order 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: ChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesOrder<br>Primary key | Lookup: SalesOrder<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesOrder|Sales order|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|SalesOrder<br>ChargeType<br>Amount
DefaultCard|DefaultCard field group|SalesOrder<br>ChargeType<br>Amount
DefaultDetails|DefaultDetails field group|SalesOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|SalesOrder<br>ChargeType<br>Amount
DefaultReport|DefaultReport field group|SalesOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|DefaultIdentification field group|SalesOrder<br>ChargeType<br>Name

## SalesOrderLine (Sales order line) Entity 
A component of a sales order that contains a portion of the order amount including information such as product, quantity, and price. 

Field | Description
---|---
BusinessUnit | Lookup: BusinessUnit
DeliveryPostalAddress | Data: Address<br>Description: Delivery address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
ExpectedShipDate | Data: DateTime
LineAmount | Data: Currency<br>Decimal places: 6
MostRecentActualShipDate | Data: DateTime
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Product<br>Required
ProductName | Data: Text<br>Maximum length: 60
PromisedShipDate | Data: DateTime
Quantity | Data: Quantity
RequestedDeliveryDate | Data: DateTime
SalesOrder<br>Primary key | Lookup: SalesOrder<br>Required
Sequence | Data: Integer<br>Required
Status | Picklist: OrderLineStatus<br>Values: Active, Confirmed, Invoice, PackingSlip, Quote<br>Description: Order line status
TotalChargeAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6
UnitPrice | Data: Currency<br>Decimal places: 6

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesOrder|Sales order|OneToMany|Composition
Product|Product|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesOrder<br>Sequence<br>Product<br>Description<br>Status<br>Quantity<br>UnitPrice<br>LineAmount
DefaultList|DefaultList field group|SalesOrder<br>Product<br>ProductName<br>Status<br>Quantity<br>LineAmount
DefaultCard|DefaultCard field group|SalesOrder<br>Product<br>ProductName<br>Status<br>Quantity
DefaultDetails|DefaultDetails field group|SalesOrder<br>Sequence<br>Product<br>ProductName<br>Description<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>ExpectedShipDate<br>MostRecentActualShipDate<br>DeliveryPostalAddress<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|SalesOrder<br>ProductName<br>Status<br>Quantity
DefaultReport|DefaultReport field group|SalesOrder<br>Product<br>ProductName<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>ExpectedShipDate<br>MostRecentActualShipDate
DefaultIdentification|DefaultIdentification field group|SalesOrder<br>Sequence<br>ProductName

## SalesOrderLineCharge (Sales order line charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the sales order line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: LineChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesOrderLine<br>Primary key | Lookup: SalesOrderLine<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesOrderLine|Sales order line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|ChargeType<br>Amount
DefaultCard|DefaultCard field group|ChargeType<br>Amount
DefaultDetails|DefaultDetails field group|SalesOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|SalesOrderLine<br>Amount<br>ChargeType
DefaultReport|DefaultReport field group|SalesOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|DefaultIdentification field group|SalesOrderLine<br>ChargeType<br>Name

## SalesOrderLineShipment (Sales order line shipment) Entity 
Shipment details for a line on sales order. A single line item on a sales order can be split and shipped to different addresses. 

Field | Description
---|---
ActualShipDate | Data: Date
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Quantity | Data: Quantity
SalesOrderLine<br>Primary key | Lookup: SalesOrderLine<br>Required
Sequence | Data: Integer<br>Required
Status | Picklist: ShipmentStatus<br>Values: Delivered, Open

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesOrderLine|Sales order line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|ActualShipDate<br>SalesOrderLine<br>Description<br>Quantity<br>Status<br>Sequence
DefaultList|DefaultList field group|ActualShipDate<br>Description<br>Quantity<br>Status
DefaultCard|DefaultCard field group|ActualShipDate<br>Description<br>Quantity<br>Status
DefaultDetails|DefaultDetails field group|ActualShipDate<br>SalesOrderLine<br>Description<br>Quantity<br>Status
DefaultLookup|DefaultLookup field group|SalesOrderLine<br>ActualShipDate<br>Description<br>Quantity<br>Status
DefaultReport|DefaultReport field group|Status<br>ActualShipDate<br>SalesOrderLine<br>Description<br>Quantity
DefaultIdentification|DefaultIdentification field group|SalesOrderLine<br>ActualShipDate

## SalesOrderLineTax (Sales order line tax) Entity 
Tax charged on a sales order line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesOrderLine<br>Primary key | Lookup: SalesOrderLine<br>Required
TaxType | Picklist: LineTaxType<br>Values: Others, SalesTax, VAT<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesOrderLine|Sales order line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|TaxType<br>RateCode<br>SalesOrderLine<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|TaxType<br>RateCode<br>Amount
DefaultCard|DefaultCard field group|TaxType<br>Amount
DefaultDetails|DefaultDetails field group|TaxType<br>RateCode<br>SalesOrderLine<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|SalesOrderLine<br>TaxType<br>RateCode<br>Amount
DefaultReport|DefaultReport field group|Amount<br>TaxType<br>RateCode<br>SalesOrderLine<br>Name<br>Description
DefaultIdentification|DefaultIdentification field group|SalesOrderLine<br>TaxType<br>RateCode

## SalesOrderTax (Sales order tax) Entity 
Tax charged on a sales order as a whole. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesOrder<br>Primary key | Lookup: SalesOrder<br>Required
TaxType | Picklist: TaxType<br>Values: Others, SalesTax, VAT<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
SalesOrder|Sales order|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultList|DefaultList field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|SalesOrder<br>Name<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultLookup|DefaultLookup field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|DefaultReport field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultIdentification|DefaultIdentification field group|SalesOrder<br>Name

