---
title: "Sales reference"
description: ""
author: ""
manager: "robinarh"
ms.date: "08/24/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataModel"
ms.technology: "CommonDataModel"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "9ba908bd-88f9-4236-96be-401c9da4d3a2"
---

# Sales
## Account (@Foundation.Account) Entity 
@Sales.AccountHelp 

Field | Description
---|---
AccountId<br>Primary key | Number sequence: <br>Unique
Birthdate | Data: Date
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
IndustryCode | Enumeration: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
ParentAccount | Lookup: Account
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PersonName | Data: PersonName
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
PrimaryContact | Lookup: Contact
PrimaryContact_Name | Data: Text<br>Maximum length: 128<br>Description: Primary contact name
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: AccountStatus<br>Values: Active, Inactive<br>Required
StockExchange | Enumeration: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|AccountId<br>FullName<br>PersonName<br>Status<br>ParentAccount<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultList|Auto generated DefaultList field group|AccountId<br>FullName<br>Status<br>PhonePrimary<br>WebsiteURL
DefaultCard|Auto generated DefaultCard field group|AccountId<br>FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|AccountId<br>FullName<br>PersonName<br>Status<br>ParentAccount<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultLookup|Auto generated DefaultLookup field group|AccountId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|AccountId<br>FullName<br>PersonName<br>Status<br>ParentAccount<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultIdentification|Auto generated DefaultIdentification field group|AccountId<br>FullName
## Lead (@Foundation.Lead) Entity 
A person who is interested in receiving information about the products or services that the company offers. 

Field | Description
---|---
Birthdate | Data: Date
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Maximum length: 128
Gender | Enumeration: Gender<br>Values: Female, Male, NotSpecified
Generation | Data: Text<br>Maximum length: 128
IndustryCode | Enumeration: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LeadId<br>Primary key | Number sequence: <br>Unique
LinkedinIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
PersonName | Data: PersonName
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
Status | Enumeration: LeadStatus<br>Values: Cancelled, Contacted, Disqualified, New, NoLongerInterested, Qualified<br>Required
StockExchange | Enumeration: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|LeadId<br>FullName<br>PersonName<br>Status<br>WebsiteURL
DefaultList|Auto generated DefaultList field group|LeadId<br>FullName<br>Status<br>WebsiteURL<br>Source
DefaultCard|Auto generated DefaultCard field group|LeadId<br>FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|LeadId<br>FullName<br>PersonName<br>Status<br>WebsiteURL<br>Source<br>Description<br>PhonePrimary<br>EmailPrimary<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity
DefaultLookup|Auto generated DefaultLookup field group|LeadId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|LeadId<br>FullName<br>PersonName<br>Status<br>WebsiteURL<br>Source<br>PhonePrimary<br>EmailPrimary
DefaultIdentification|Auto generated DefaultIdentification field group|LeadId<br>FullName
## Opportunity (@Sales.Opportunity) Entity 
Information about potential sales to new or established customers. 

Field | Description
---|---
ActualCloseDate | Data: DateTime
ActualValueAmount | Data: Currency<br>Required, Decimal places: 6
CreatedDate | Data: Date<br>Required
Description | Data: Text<br>Maximum length: 128
EstimatedCloseDate | Data: DateTime
EstimatedValueAmount | Data: Currency<br>Required, Decimal places: 6
IndustryCode | Enumeration: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale<br>Required
Name | Data: Text<br>Required, Maximum length: 128
NextFollowupDate | Data: Date<br>Description: Next follow-up date
OpportunityId<br>Primary key | Number sequence: <br>Unique
OriginalEstimatedValueAmount | Data: Currency<br>Required, Decimal places: 6
ParentOpportunity | Lookup: Opportunity
PurchaseProcess | Enumeration: Process<br>Values: Committee, Individual, Unknown<br>Required
PurchaseTimeFrame | Enumeration: TimeFrame<br>Values: Day, HalfYear, Hour, Month, Quarter, Trimester, Week, Year<br>Required
RatingCode | Enumeration: HotWarmCold<br>Values: Cold, Hot, Warm<br>Required
SalesStage | Enumeration: OpportunityState<br>Values: Lost, Open, Won
Source | Enumeration: OpportunitySource<br>Values: Advertisement, EmployeeReferral, ExternalReferral, Other, Partner, PublicRelations, Seminar, TradeShow, Web, WordOfMouth<br>Required
Status | Enumeration: OpportunityStatus<br>Values: Canceled, InProgress, OnHold, OutSold, Won<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|OpportunityId<br>Name<br>Status<br>OriginalEstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame<br>PurchaseProcess<br>SalesStage<br>Description
DefaultList|Auto generated DefaultList field group|OpportunityId<br>Name<br>Status<br>OriginalEstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame
DefaultCard|Auto generated DefaultCard field group|OpportunityId<br>Name<br>Status
DefaultDetails|Auto generated DefaultDetails field group|OpportunityId<br>Name<br>Status<br>OriginalEstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame<br>PurchaseProcess<br>SalesStage<br>Description<br>CreatedDate<br>Source<br>IndustryCode<br>RatingCode
DefaultLookup|Auto generated DefaultLookup field group|OpportunityId<br>Name<br>Status
DefaultReport|Auto generated DefaultReport field group|OpportunityId<br>Name<br>Status<br>OriginalEstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame<br>PurchaseProcess<br>SalesStage<br>Description<br>CreatedDate<br>Source<br>IndustryCode<br>RatingCode
DefaultIdentification|Auto generated DefaultIdentification field group|OpportunityId<br>Name
## OpportunityPartyRole (@Sales.OpportunityPartyRole) Entity 
@Sales.OpportunityPartyRole 

Field | Description
---|---
Opportunity<br>Primary key | Lookup: Opportunity<br>Required
OpportunityRole | Enumeration: OpportunityRole<br>Values: Default<br>Required
PartyRole | Enumeration: PartyRole<br>Values: Account, Alumnus, ApplicationUser, ApplicationUserGroup, BusinessUnit, Constituent, Contact, Family, Fan, Household, Lead, Organization, Partner, Person, Team, Tenant, Vendor, Worker<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Opportunity<br>OpportunityRole<br>PartyRole
DefaultList|Auto generated DefaultList field group|Opportunity<br>OpportunityRole<br>PartyRole
DefaultCard|Auto generated DefaultCard field group|Opportunity<br>OpportunityRole<br>PartyRole
DefaultDetails|Auto generated DefaultDetails field group|Opportunity<br>OpportunityRole<br>PartyRole
DefaultLookup|Auto generated DefaultLookup field group|Opportunity<br>OpportunityRole<br>PartyRole
DefaultReport|Auto generated DefaultReport field group|Opportunity<br>OpportunityRole<br>PartyRole
DefaultIdentification|Auto generated DefaultIdentification field group|Opportunity<br>OpportunityRole<br>PartyRole
## Partner (@Foundation.Partner) Entity 
A person, organization, or group that a company partners with. 

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
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedinIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
ParentPartner | Lookup: Partner
PartnerId<br>Primary key | Number sequence: <br>Unique
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
PrimaryContact | Lookup: Contact
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
SocialNetwork01 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetwork02 | Enumeration: SocialNetwork<br>Values: Facebook, Konnects, LinkedIn, Myspace, Twitter, XING
SocialNetworkIdentity01 | Data: Text<br>Maximum length: 128
SocialNetworkIdentity02 | Data: Text<br>Maximum length: 128
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: PartnerStatus<br>Values: Active, Inactive<br>Required
StockExchange | Enumeration: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL
DefaultList|Auto generated DefaultList field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL
DefaultCard|Auto generated DefaultCard field group|PartnerId<br>FullName<br>PhonePrimary
DefaultDetails|Auto generated DefaultDetails field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL<br>Description<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity<br>MailingPostalAddress<br>StockTicker
DefaultLookup|Auto generated DefaultLookup field group|PartnerId<br>FullName<br>PhonePrimary
DefaultReport|Auto generated DefaultReport field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL<br>FacebookIdentity<br>LinkedinIdentity<br>TwitterIdentity<br>MailingPostalAddress<br>StockTicker
DefaultIdentification|Auto generated DefaultIdentification field group|PartnerId<br>FullName
## SalesInvoice (@Sales.SalesInvoice) Entity 
A sales invoice. 

Field | Description
---|---
Account | Lookup: Account<br>Required
AccountContact | Lookup: Contact
BillingAddress | Data: Address
CustomerPurchaseOrderReference | Data: Text<br>Maximum length: 20
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
FreightTerms | Enumeration: FreightTerms<br>Values: FOB, NoCharge
InvoiceDate | Data: DateTime<br>Required
Name | Data: Text<br>Maximum length: 60
Opportunity | Lookup: Opportunity
PaymentTerms | Enumeration: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
SalesInvoiceId<br>Primary key | Number sequence: <br>Unique<br>Description: Invoice number
SalesOrder | Lookup: SalesOrder
SalesPersonWorker | Lookup: Worker
ShippingMethod | Enumeration: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Enumeration: InvoiceStatus<br>Values: Cancelled, Created, Hold, Paid<br>Description: Invoice status
TotalAmount | Data: Currency<br>Decimal places: 6
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total charges
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total taxes

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Description<br>Account<br>CustomerPurchaseOrderReference<br>AccountContact<br>Status
DefaultList|Auto generated DefaultList field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Account<br>CustomerPurchaseOrderReference<br>Status<br>TotalAmount
DefaultCard|Auto generated DefaultCard field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Account<br>Status<br>TotalAmount
DefaultDetails|Auto generated DefaultDetails field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Description<br>Account<br>CustomerPurchaseOrderReference<br>AccountContact<br>Status<br>TotalAmount<br>FreightTerms<br>PaymentTerms<br>SalesPersonWorker<br>ShippingMethod<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultLookup|Auto generated DefaultLookup field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Account
DefaultReport|Auto generated DefaultReport field group|InvoiceDate<br>SalesInvoiceId<br>Name<br>Description<br>Account<br>CustomerPurchaseOrderReference<br>AccountContact<br>Status<br>TotalAmount<br>FreightTerms<br>PaymentTerms<br>SalesPersonWorker<br>ShippingMethod<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultIdentification|Auto generated DefaultIdentification field group|SalesInvoiceId<br>Name
## SalesInvoiceCharge (@Sales.SalesInvoiceCharge) Entity 
A sales invoice charge. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total charges
ChargeType | Enumeration: InvoiceChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesInvoice<br>Primary key | Lookup: SalesInvoice<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SalesInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|Auto generated DefaultList field group|SalesInvoice<br>ChargeType<br>Name<br>Amount
DefaultCard|Auto generated DefaultCard field group|SalesInvoice<br>ChargeType<br>Name<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|SalesInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|Auto generated DefaultLookup field group|SalesInvoice<br>ChargeType<br>Amount
DefaultReport|Auto generated DefaultReport field group|SalesInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|SalesInvoice<br>Name
## SalesInvoiceLine (@Sales.SalesInvoiceLine) Entity 
A sales invoice line item. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
ExpectedShipDate | Data: DateTime
LineAmount | Data: Currency<br>Required, Decimal places: 6
MostRecentActualShipDate | Data: DateTime
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Product
ProductName | Data: Text<br>Required, Maximum length: 60
ProductUnitOfMeasure_UOM | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard<br>Description: Product unit of measure
PromisedShipDate | Data: DateTime
Quantity | Data: Quantity<br>Required
SalesInvoice<br>Primary key | Lookup: SalesInvoice<br>Required
Sequence | Data: Integer<br>Required
Status | Enumeration: InvoiceLineStatus<br>Values: Active, Confirmed, Invoice, PackingSlip, Quote<br>Required<br>Description: Invoice line status
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total charges
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total taxes
UnitPrice | Data: Currency<br>Required, Decimal places: 6

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SalesInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity
DefaultList|Auto generated DefaultList field group|SalesInvoice<br>Product<br>Name<br>Status<br>Quantity<br>LineAmount
DefaultCard|Auto generated DefaultCard field group|SalesInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultDetails|Auto generated DefaultDetails field group|SalesInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|Auto generated DefaultLookup field group|SalesInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultReport|Auto generated DefaultReport field group|SalesInvoice<br>Product<br>Name<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultIdentification|Auto generated DefaultIdentification field group|SalesInvoice<br>Sequence<br>Product
## SalesInvoiceLineCharge (@Sales.SalesInvoiceLineCharge) Entity 
A sales invoice line item charge. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total invoice line charges
ChargeType | Enumeration: InvoiceLineChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesInvoiceLine<br>Primary key | Lookup: SalesInvoiceLine<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SalesInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|Auto generated DefaultList field group|ChargeType<br>Name<br>Amount
DefaultCard|Auto generated DefaultCard field group|ChargeType<br>Name<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|SalesInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|Auto generated DefaultLookup field group|ChargeType<br>Amount
DefaultReport|Auto generated DefaultReport field group|SalesInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|SalesInvoiceLine<br>Name
## SalesInvoiceLineTax (@Sales.SalesInvoiceLineTax) Entity 
A sales invoice line item tax. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total invoice line taxes
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesInvoiceLine<br>Primary key | Lookup: SalesInvoiceLine<br>Required
TaxType | Enumeration: InvoiceLineTaxType<br>Values: Others, SalesTax, VAT<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultList|Auto generated DefaultList field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|Auto generated DefaultCard field group|Name<br>TaxType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>SalesInvoiceLine
DefaultLookup|Auto generated DefaultLookup field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|Auto generated DefaultReport field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>SalesInvoiceLine
DefaultIdentification|Auto generated DefaultIdentification field group|SalesInvoiceLine<br>Name
## SalesInvoiceTax (@Sales.SalesInvoiceTax) Entity 
The tax on a sales invoice. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total taxes
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesInvoice<br>Primary key | Lookup: SalesInvoice<br>Required
TaxType | Enumeration: InvoiceTaxType<br>Values: Others, SalesTax, VAT<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SalesInvoice<br>RateCode<br>TaxType<br>Name<br>Amount<br>Description
DefaultList|Auto generated DefaultList field group|SalesInvoice<br>RateCode<br>TaxType<br>Amount
DefaultCard|Auto generated DefaultCard field group|SalesInvoice<br>TaxType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|SalesInvoice<br>RateCode<br>TaxType<br>Name<br>Amount<br>Description
DefaultLookup|Auto generated DefaultLookup field group|SalesInvoice<br>RateCode<br>Amount
DefaultReport|Auto generated DefaultReport field group|SalesInvoice<br>RateCode<br>TaxType<br>Name<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|SalesInvoice<br>TaxType<br>RateCode
## SalesOrder (@Sales.SalesOrder) Entity 
A sales order. 

Field | Description
---|---
Account | Lookup: Account<br>Required
AccountContact | Lookup: Contact
BillingAddress | Data: Address
CustomerPurchaseOrderReference | Data: Text<br>Maximum length: 20
DeliveryAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
FreightTerms | Enumeration: FreightTerms<br>Values: FOB, NoCharge
Name | Data: Text<br>Maximum length: 60
Opportunity | Lookup: Opportunity
OrderDate | Data: DateTime<br>Required
PaymentTerms | Enumeration: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
SalesOrderId<br>Primary key | Number sequence: <br>Unique<br>Description: Order number
SalesPersonWorker | Lookup: Worker
ShippingMethod | Enumeration: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Enumeration: OrderStatus<br>Values: Active, Confirmed, Invoice, PackingSlip, Quote<br>Required<br>Description: Order status
TotalAmount | Data: Currency<br>Required, Decimal places: 6
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total charges
TotalChargeCurrency_CurrencyCode | Enumeration: CurrencyCode<br>Values: AED, AFN, ALL, AMD, ANG, AOA, ARS, AUD, AWG, AZN, BAM, BBD, BDT, BGN, BHD, BIF, BMD, BND, BOB, BOV, BRL, BSD, BTN, BWP, BYN, BYR, BZD, CAD, CDF, CHE, CHF, CHW, CLF, CLP, CNY, COP, COU, CRC, CUC, CUP, CVE, CZK, DJF, DKK, DOP, DZD, EGP, ERN, ETB, EUR, FJD, FKP, GBP, GEL, GHS, GIP, GMD, GNF, GTQ, GYD, HKD, HNL, HRK, HTG, HUF, IDR, ILS, INR, IQD, IRR, ISK, JMD, JOD, JPY, KES, KGS, KHR, KMF, KPW, KRW, KWD, KYD, KZT, LAK, LBP, LKR, LRD, LSL, LYD, MAD, MDL, MGA, MKD, MMK, MNT, MOP, MRO, MUR, MVR, MWK, MXN, MXV, MYR, MZN, NAD, NGN, NIO, NOK, NPR, NZD, OMR, PAB, PEN, PGK, PHP, PKR, PLN, PYG, QAR, RON, RSD, RUB, RWF, SAR, SBD, SCR, SDG, SEK, SGD, SHP, SLL, SOS, SRD, SSP, STD, SVC, SYP, SZL, THB, TJS, TMT, TND, TOP, TRY, TTD, TWD, TZS, UAH, UGX, USD, USN, UYI, UYU, UZS, VEF, VND, VUV, WST, XAF, XAG, XAU, XBA, XBB, XBC, XBD, XCD, XDR, XOF, XPD, XPF, XPT, XSU, XTS, XUA, XXX, YER, ZAR, ZMW, ZWL<br>Required<br>Description: Total charges currency code
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total taxes
TotalTaxCurrency_CurrencyCode | Enumeration: CurrencyCode<br>Values: AED, AFN, ALL, AMD, ANG, AOA, ARS, AUD, AWG, AZN, BAM, BBD, BDT, BGN, BHD, BIF, BMD, BND, BOB, BOV, BRL, BSD, BTN, BWP, BYN, BYR, BZD, CAD, CDF, CHE, CHF, CHW, CLF, CLP, CNY, COP, COU, CRC, CUC, CUP, CVE, CZK, DJF, DKK, DOP, DZD, EGP, ERN, ETB, EUR, FJD, FKP, GBP, GEL, GHS, GIP, GMD, GNF, GTQ, GYD, HKD, HNL, HRK, HTG, HUF, IDR, ILS, INR, IQD, IRR, ISK, JMD, JOD, JPY, KES, KGS, KHR, KMF, KPW, KRW, KWD, KYD, KZT, LAK, LBP, LKR, LRD, LSL, LYD, MAD, MDL, MGA, MKD, MMK, MNT, MOP, MRO, MUR, MVR, MWK, MXN, MXV, MYR, MZN, NAD, NGN, NIO, NOK, NPR, NZD, OMR, PAB, PEN, PGK, PHP, PKR, PLN, PYG, QAR, RON, RSD, RUB, RWF, SAR, SBD, SCR, SDG, SEK, SGD, SHP, SLL, SOS, SRD, SSP, STD, SVC, SYP, SZL, THB, TJS, TMT, TND, TOP, TRY, TTD, TWD, TZS, UAH, UGX, USD, USN, UYI, UYU, UZS, VEF, VND, VUV, WST, XAF, XAG, XAU, XBA, XBB, XBC, XBD, XCD, XDR, XOF, XPD, XPF, XPT, XSU, XTS, XUA, XXX, YER, ZAR, ZMW, ZWL<br>Required<br>Description: Total taxes currency code

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SalesOrderId<br>Account<br>OrderDate<br>CustomerPurchaseOrderReference<br>Status<br>Name<br>Description<br>SalesPersonWorker<br>AccountContact
DefaultList|Auto generated DefaultList field group|SalesOrderId<br>Account<br>OrderDate<br>CustomerPurchaseOrderReference<br>Status<br>SalesPersonWorker<br>TotalAmount
DefaultCard|Auto generated DefaultCard field group|SalesOrderId<br>Account<br>OrderDate<br>Status<br>TotalAmount
DefaultDetails|Auto generated DefaultDetails field group|SalesOrderId<br>Account<br>OrderDate<br>CustomerPurchaseOrderReference<br>Status<br>Name<br>Description<br>SalesPersonWorker<br>AccountContact<br>TotalAmount<br>FreightTerms<br>ShippingMethod<br>TotalChargeAmount<br>TotalChargeCurrency_CurrencyCode<br>TotalDiscountAmount<br>TotalTaxAmount<br>TotalTaxCurrency_CurrencyCode
DefaultLookup|Auto generated DefaultLookup field group|SalesOrderId<br>Account<br>OrderDate<br>Status<br>TotalAmount
DefaultReport|Auto generated DefaultReport field group|SalesOrderId<br>Account<br>OrderDate<br>CustomerPurchaseOrderReference<br>Status<br>Name<br>Description<br>SalesPersonWorker<br>AccountContact<br>TotalAmount
DefaultIdentification|Auto generated DefaultIdentification field group|SalesOrderId<br>Name
## SalesOrderCharge (@Sales.SalesOrderCharge) Entity 
A sales order charge. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total charges
ChargeType | Enumeration: ChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesOrder<br>Primary key | Lookup: SalesOrder<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SalesOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|Auto generated DefaultList field group|SalesOrder<br>ChargeType<br>Amount
DefaultCard|Auto generated DefaultCard field group|SalesOrder<br>ChargeType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|SalesOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|Auto generated DefaultLookup field group|SalesOrder<br>ChargeType<br>Amount
DefaultReport|Auto generated DefaultReport field group|SalesOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|SalesOrder<br>ChargeType<br>Name
## SalesOrderLine (@Sales.SalesOrderLines) Entity 
A sales order line. 

Field | Description
---|---
DeliveryPostalAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
ExpectedShipDate | Data: DateTime
LineAmount | Data: Currency<br>Decimal places: 6
MostRecentActualShipDate | Data: DateTime
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Product<br>Required
ProductName | Data: Text<br>Maximum length: 60
ProductUnitOfMeasure_UOM | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard<br>Description: Product unit of measure
PromisedShipDate | Data: DateTime
Quantity | Data: Quantity
SalesOrder<br>Primary key | Lookup: SalesOrder<br>Required
Sequence | Data: Integer<br>Required
Status | Enumeration: OrderLineStatus<br>Values: Active, Confirmed, Invoice, PackingSlip, Quote<br>Description: Order line status
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total charges
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total taxes
UnitPrice | Data: Currency<br>Decimal places: 6

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SalesOrder<br>Sequence<br>Product<br>Description<br>Status<br>Quantity<br>UnitPrice<br>LineAmount
DefaultList|Auto generated DefaultList field group|SalesOrder<br>Product<br>ProductName<br>Status<br>Quantity<br>LineAmount
DefaultCard|Auto generated DefaultCard field group|SalesOrder<br>Product<br>ProductName<br>Status<br>Quantity
DefaultDetails|Auto generated DefaultDetails field group|SalesOrder<br>Sequence<br>Product<br>ProductName<br>Description<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>ExpectedShipDate<br>MostRecentActualShipDate<br>DeliveryPostalAddress<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|Auto generated DefaultLookup field group|SalesOrder<br>ProductName<br>Status<br>Quantity
DefaultReport|Auto generated DefaultReport field group|SalesOrder<br>Product<br>ProductName<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>ExpectedShipDate<br>MostRecentActualShipDate
DefaultIdentification|Auto generated DefaultIdentification field group|SalesOrder<br>Sequence<br>ProductName
## SalesOrderLineCharge (@Sales.SalesOrderLineCharge) Entity 
A sales order line charge. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total line charges
ChargeType | Enumeration: LineChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesOrderLine<br>Primary key | Lookup: SalesOrderLine<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SalesOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|Auto generated DefaultList field group|ChargeType<br>Amount
DefaultCard|Auto generated DefaultCard field group|ChargeType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|SalesOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|Auto generated DefaultLookup field group|ChargeType<br>Amount
DefaultReport|Auto generated DefaultReport field group|SalesOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|SalesOrderLine<br>ChargeType<br>Name
## SalesOrderLineShipment (@Sales.SalesOrderLineShipment) Entity 
Shipment details for a line on sales order. A single line item on a sales order can be split and shipped to different addresses. 

Field | Description
---|---
ActualShipDate | Data: Date
Description | Data: Text<br>Maximum length: 60
Quantity | Data: Number
SalesOrderLine<br>Primary key | Lookup: SalesOrderLine<br>Required
Sequence | Data: Integer<br>Required
Status | Enumeration: ShipmentStatus<br>Values: Delivered, Open

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|ActualShipDate<br>SalesOrderLine<br>Description<br>Quantity<br>Status
DefaultList|Auto generated DefaultList field group|ActualShipDate<br>Description<br>Quantity<br>Status
DefaultCard|Auto generated DefaultCard field group|ActualShipDate<br>Description<br>Quantity<br>Status
DefaultDetails|Auto generated DefaultDetails field group|ActualShipDate<br>SalesOrderLine<br>Description<br>Quantity<br>Status
DefaultLookup|Auto generated DefaultLookup field group|ActualShipDate<br>Description<br>Quantity<br>Status
DefaultReport|Auto generated DefaultReport field group|Status<br>ActualShipDate<br>SalesOrderLine<br>Description<br>Quantity
DefaultIdentification|Auto generated DefaultIdentification field group|SalesOrderLine<br>ActualShipDate
## SalesOrderLineTax (@Sales.SalesOrderLineTax) Entity 
The tax on a sale order line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total line taxes
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesOrderLine<br>Primary key | Lookup: SalesOrderLine<br>Required
TaxType | Enumeration: LineTaxType<br>Values: Others, SalesTax, VAT<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|TaxType<br>RateCode<br>SalesOrderLine<br>Name<br>Description<br>Amount
DefaultList|Auto generated DefaultList field group|TaxType<br>RateCode<br>Amount
DefaultCard|Auto generated DefaultCard field group|TaxType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|TaxType<br>RateCode<br>SalesOrderLine<br>Name<br>Description<br>Amount
DefaultLookup|Auto generated DefaultLookup field group|TaxType<br>RateCode<br>Amount
DefaultReport|Auto generated DefaultReport field group|TaxType<br>RateCode<br>SalesOrderLine<br>Name<br>Description<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|SalesOrderLine<br>TaxType<br>RateCode
## SalesOrderTax (@Sales.SalesOrderTax) Entity 
The tax on a sales order. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total taxes
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesOrder<br>Primary key | Lookup: SalesOrder<br>Required
TaxType | Enumeration: TaxType<br>Values: Others, SalesTax, VAT<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultList|Auto generated DefaultList field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|Auto generated DefaultCard field group|SalesOrder<br>Name<br>TaxType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultLookup|Auto generated DefaultLookup field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|Auto generated DefaultReport field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultIdentification|Auto generated DefaultIdentification field group|SalesOrder<br>Name

