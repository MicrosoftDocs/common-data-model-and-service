---
title: ""
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
ms.assetid: ""
---

# Sales
## Accounts (Accounts) Entity
Accounts table can store individual accounts of a business such as customers, competitors, and partners.

Field | Description
---|---
AccountNumber<br>Primary key | Data: Text<br>Required, Unique, Maximum length: 10<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
AccountStatus | Enumeration: AccountStatusValues: Active, InActive
Address | Data: Text<br>Maximum length: 250
DefaultCurrency | Lookup: Currency
FirstName | Data: Text<br>Maximum length: 25
IndustryCode | Enumeration: IndustryCodeValues: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
KnownAs | Data: Text<br>Maximum length: 20
LastName | Data: Text<br>Maximum length: 25
MainPhoneNumber | Data: Phone<br>Description: Type the main phone number for this account.
MiddleName | Data: Text<br>Maximum length: 25
Name | Data: Text<br>Required, Maximum length: 60<br>Description: Type the company or business name.
NameAlias | Data: Text<br>Maximum length: 20
PostalAddress | Data: Address
PrimaryContact | Lookup: Contacts
PrimaryEmail | Data: Email<br>Description: Type the primary email for this account.
PrimaryFax | Data: Text<br>Maximum length: 20<br>Description: Type the fax number for this account.
Type | Enumeration: AccountTypeValues: Organization, Person
WebsiteURL | Data: Text<br>Maximum length: 255
## Contacts (Contacts) Entity
Contact table can store information about individuals, with whom the company has a relationship, such as a customer, a supplier, or a colleague.

Field | Description
---|---
Account | Lookup: Accounts
Address | Data: Text<br>Maximum length: 250
BusinessPhone | Data: Phone
ContactNumber<br>Primary key | Data: Text<br>Required, Unique, Maximum length: 100
Email | Data: Email
FirstName | Data: Text<br>Maximum length: 25
KnownAs | Data: Text<br>Maximum length: 20
LastName | Data: Text<br>Maximum length: 25
MainPhoneNumber | Data: Phone<br>Description: Type the main phone number for this account.
MiddleName | Data: Text<br>Maximum length: 25
MobilePhoneNumber | Data: Text<br>Maximum length: 20<br>Description: Type the main phone number for this account.
Name | Data: Text<br>Maximum length: 60
PrimaryEmail | Data: Email<br>Description: Type the primary email for this account.
PrimaryFax | Data: Text<br>Maximum length: 20<br>Description: Type the fax number for this account.
SecondaryEmail | Data: Email<br>Description: Type the primary email for this account.
## Customer (Customer) Entity
An individual or organization that interacts with the company to buy the goods and services that it offers.

Field | Description
---|---
BillingPostalAddress | Data: Address
BusinessPhone | Data: Phone
CellPhone | Data: Phone
CustomerId<br>Primary key | Number sequence: <br>Unique
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
HomePhone | Data: Phone
LastName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
Linkedin | Data: Text<br>Maximum length: 128
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
ParentCustomer | Lookup: Customer
PartyType | Enumeration: PartyTypeValues: Group, Organization, Person<br>Required
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
Status | Enumeration: CustomerStatusValues: Active, Blocked, Inactive
StockExchange | Enumeration: StockExchangeValues: NYSE
Thumbnail | Data: Image
Ticker | Data: Text<br>Maximum length: 10
Twitter | Data: Text<br>Maximum length: 128
WebSite | Data: WebsiteUrl
## Lead (Lead) Entity
A person who is interested in receiving information about the products or services that the company offers.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
FullName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
HomePhone | Data: Phone
LastName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
LeadId<br>Primary key | Number sequence: <br>Unique
Linkedin | Data: Text<br>Maximum length: 128
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
PartyType | Enumeration: PartyTypeValues: Group, Organization, Person
PostalAddress | Data: Address
SatoriId | Data: Text<br>Maximum length: 128
SocialScore | Data: Integer
Source | Enumeration: LeadSourceValues: Advertisement, EmployeeReferral, ExternalReferral, Other, Partner, PublicRelations, Seminar, TradeShow, Web, WordOfMouth
Status | Enumeration: LeadStatusValues: Cancelled, Contacted, Disqualified, New, NoLongerInterested, Qualified
StockExchange | Enumeration: StockExchangeValues: NYSE
Thumbnail | Data: Image
Ticker | Data: Text<br>Maximum length: 10
Twitter | Data: Text<br>Maximum length: 128
WebSite | Data: WebsiteUrl
## Opportunity (Opportunity) Entity
Information about potential sales to new or established customers.

Field | Description
---|---
ActualCloseDate | Data: DateTime
ActualValueAmount | Data: Currency<br>Decimal places: 6<br>Description: Actual Value
ActualValueAmountCurrency | Lookup: Currency
CreatedDate | Data: Date
Description | Data: Text<br>Maximum length: 128
EstimatedCloseDate | Data: DateTime
EstimatedValueAmount | Data: Currency<br>Decimal places: 6<br>Description: Estimated Value
EstimatedValueAmountCurrency | Lookup: Currency
IndustryCode | Enumeration: IndustryCodeValues: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
Name | Data: Text<br>Maximum length: 128
NextFollowupDate | Data: Date
OpportunityId<br>Primary key | Number sequence: <br>Unique
OriginalEstimatedValueAmount | Data: Currency<br>Decimal places: 6<br>Description: Original Estimated Value
OriginalEstimatedValueAmountCurrency | Lookup: Currency
ParentOpportunity | Lookup: Opportunity
PurchaseProcess | Enumeration: ProcessValues: Committee, Individual, Unknown<br>Description: Purcahse process
PurchaseTimeFrame | Enumeration: TimeFrameValues: Day, HalfYear, Hour, Month, Quarter, Trimester, Week, Year
RatingCode | Enumeration: HotWarmColdValues: Cold, Hot, Warm
SalesStage | Enumeration: OpportunityStateValues: Lost, Open, Won
Source | Enumeration: OpportunitySourceValues: Advertisement, EmployeeReferral, ExternalReferral, Other, Partner, PublicRelations, Seminar, TradeShow, Web, WordOfMouth
Status | Enumeration: OpportunityStatusValues: Canceled, InProgress, OnHold, OutSold, Won
## OpportunityPartyRole (OpportunityPartyRole) Entity
OpportunityPartyRole

Field | Description
---|---
Opportunity | Lookup: Opportunity<br>Required
OpportunityPartyRoleId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
OpportunityRole | Enumeration: OpportunityRoleValues: Default
PartyRole | Enumeration: PartyRoleValues: Alumnus, Company, Constituent, Contractor, Customer, Donor, Employee, Fan, Member, NonProfit, Supplier, Tenant, Vendor, Volunteer
## Partner (Partner) Entity
A person, organization, or group that a company partners with.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Required, Maximum length: 128<br>Description: Type the company or business name.
Linkedin | Data: Text<br>Maximum length: 128
ParentPartner | Lookup: Partner
PartnerId<br>Primary key | Number sequence: <br>Unique
PostalAddress | Data: Address
SatoriId | Data: Text<br>Maximum length: 128
StockExchange | Enumeration: StockExchangeValues: NYSE
Thumbnail | Data: Image
Ticker | Data: Text<br>Maximum length: 10
Twitter | Data: Text<br>Maximum length: 128
WebSite | Data: WebsiteUrl
## SalesInvoice (Sales Invoice) Entity
A sales invoice.

Field | Description
---|---
BillingAddress | Data: Address
Customer | Lookup: Customer<br>Required
CustomerContact | Lookup: Customer
CustomerPurchaseOrderReference | Data: Text<br>Maximum length: 20
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
DiscountAmountCurrency | Lookup: Currency
DiscountPercent | Data: Number
FreightTerms | Enumeration: FreightTermsValues: FOB, NoCharge
InvoiceDate | Data: DateTime<br>Required
Name | Data: Text<br>Maximum length: 60
Opportunity | Lookup: Opportunity
PaymentTerms | Enumeration: PaymentTermsValues: Net30, Net45, Net60, TwoPercent10Net30
SalesInvoiceId<br>Primary key | Number sequence: <br>Unique<br>Description: Invoice Number
SalesOrder | Lookup: SalesOrder
SalesPerson | Lookup: Employee
ShippingMethod | Enumeration: ShippingMethodValues: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Enumeration: InvoiceStatusValues: Cancelled, Created, Hold, Paid<br>Description: Invoice Status
TotalAmount | Data: Currency<br>Decimal places: 6
TotalAmountCurrency | Lookup: Currency
TotalCharge | Data: Currency<br>Decimal places: 6<br>Description: Total Charges
TotalChargeCurrency | Lookup: Currency
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalDiscountAmountCurrency | Lookup: Currency
TotalDiscountPercent | Data: Number
TotalTax | Data: Currency<br>Decimal places: 6<br>Description: Total Taxes
TotalTaxCurrency | Lookup: Currency
## SalesInvoiceCharge (Sales Invoice Charges) Entity
A sales invoice charge.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Charges
AmountCurrency | Lookup: Currency<br>Required
ChargeId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Invoice Charge Id
ChargeType | Enumeration: InvoiceChargeTypeValues: Freight, Insurance, Others
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge Name
SalesInvoice | Lookup: SalesInvoice<br>Required
## SalesInvoiceLine (Sales Invoice Lines) Entity
A sales invoice line item.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
DiscountAmountCurrency | Lookup: Currency
DiscountPercent | Data: Number
ExpectedShipDate | Data: DateTime
LineAmount | Data: Currency<br>Decimal places: 6
LineAmountCurrency | Lookup: Currency
MostRecentActualShipDate | Data: DateTime
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Products
ProductName | Data: Text<br>Maximum length: 60
ProductUnitOfMeasure | Lookup: Units
PromisedShipDate | Data: DateTime
Quantity | Data: Number
SalesInvoiceLine | Lookup: SalesInvoice<br>Required
SalesInvoiceLineId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Invoice Line Number
Sequence | Data: Integer
Status | Enumeration: InvoiceLineStatusValues: Active, Confirmed, Invoice, PackingSlip, Quote<br>Description: Invoice Line Status
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Charge
TotalChargesCurrency | Lookup: Currency
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Tax
TotalTaxesCurrency | Lookup: Currency
UnitPrice | Data: Currency<br>Decimal places: 6
UnitPriceCurrency | Lookup: Currency
## SalesInvoiceLineCharge (Sales Invoice Line Charge) Entity
A sales invoice line item charge.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Line Charges
AmountCurrency | Lookup: Currency<br>Required
ChargeId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Invoice Line Charge Id
ChargeType | Enumeration: InvoiceLineChargeTypeValues: Freight, Insurance, Others
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge Name
SalesInvoiceLine | Lookup: SalesInvoiceLine<br>Required
## SalesInvoiceLineTax (Sales Invoice Line Tax) Entity
A sales invoice line item tax.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Invoice Line Taxes
AmountCurrency | Lookup: Currency<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax Name
RateCode | Data: Text<br>Maximum length: 60
SalesInvoiceLine | Lookup: SalesInvoiceLine<br>Required
TaxId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Invoice Line Tax Id
TaxType | Enumeration: InvoiceLineTaxTypeValues: Others, SalesTax, VAT
## SalesInvoiceTax (Sales Invoice Tax) Entity
The tax on a sales invoice.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Taxes
AmountCurrency | Lookup: Currency<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax Name
RateCode | Data: Text<br>Maximum length: 60
SalesInvoice | Lookup: SalesInvoice<br>Required
TaxId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Order Tax Id
TaxType | Enumeration: InvoiceTaxTypeValues: Others, SalesTax, VAT
## SalesOrder (Sales Order) Entity
A sales order.

Field | Description
---|---
BillingAddress | Data: Address
Customer | Lookup: Customer<br>Required
CustomerContact | Lookup: Customer
CustomerPurchaseOrderReference | Data: Text<br>Maximum length: 20
DeliveryAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
DiscountAmountCurrency | Lookup: Currency
DiscountPercent | Data: Number
FreightTerms | Enumeration: FreightTermsValues: FOB, NoCharge
Name | Data: Text<br>Maximum length: 60
Opportunity | Lookup: Opportunity
OrderDate | Data: DateTime<br>Required
PaymentTerms | Enumeration: PaymentTermsValues: Net30, Net45, Net60, TwoPercent10Net30
SalesOrderId<br>Primary key | Number sequence: <br>Unique<br>Description: Order number
SalesPerson | Lookup: Employee
ShippingMethod | Enumeration: ShippingMethodValues: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Enumeration: OrderStatusValues: Active, Confirmed, Invoice, PackingSlip, Quote<br>Description: Order Status
TotalAmount | Data: Currency<br>Decimal places: 6
TotalAmountCurrency | Lookup: Currency
TotalCharge | Data: Currency<br>Decimal places: 6<br>Description: Total Charges
TotalChargeCurrency | Lookup: Currency
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalDiscountAmountCurrency | Lookup: Currency
TotalDiscountPercent | Data: Number
TotalTax | Data: Currency<br>Decimal places: 6<br>Description: Total Taxes
TotalTaxCurrency | Lookup: Currency
## SalesOrderCharge (Sales Order Charges) Entity
A sales order charge.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Charges
AmountCurrency | Lookup: Currency<br>Required
ChargeId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Order Charge Id
ChargeType | Enumeration: ChargeTypeValues: Freight, Insurance, Others
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge Name
SalesOrder | Lookup: SalesOrder<br>Required
## SalesOrderLine (Sales Order Lines) Entity
A sales order line.

Field | Description
---|---
DeliveryAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
DiscountAmountCurrency | Lookup: Currency
DiscountPercent | Data: Number
ExpectedShipDate | Data: DateTime
LineAmount | Data: Currency<br>Decimal places: 6
LineAmountCurrency | Lookup: Currency
MostRecentActualShipDate | Data: DateTime
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Products
ProductName | Data: Text<br>Maximum length: 60
ProductUnitOfMeasure | Lookup: Units
PromisedShipDate | Data: DateTime
Quantity | Data: Number
SalesOrder | Lookup: SalesOrder<br>Required
SalesOrderLineId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Order Line Number
Sequence | Data: Integer
Status | Enumeration: OrderLineStatusValues: Active, Confirmed, Invoice, PackingSlip, Quote<br>Description: Order Line Status
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Charge
TotalChargesCurrency | Lookup: Currency
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Tax
TotalTaxesCurrency | Lookup: Currency
UnitPrice | Data: Currency<br>Decimal places: 6
UnitPriceCurrency | Lookup: Currency
## SalesOrderLineCharge (Sales Order Line Charge) Entity
A sales order line charge.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Line Charges
AmountCurrency | Lookup: Currency<br>Required
ChargeId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Order Line Charge Id
ChargeType | Enumeration: LineChargeTypeValues: Freight, Insurance, Others
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge Name
SalesOrderLine | Lookup: SalesOrderLine<br>Required
## SalesOrderLineShipment (Sales Order Line Shipment) Entity
Shipment details for a line on sales order. A single line item on a sales order can be split and shipped to different addresses.

Field | Description
---|---
ActualShipDate | Data: Date
Description | Data: Text<br>Maximum length: 60
Quantity | Data: Number
SalesOrderLine | Lookup: SalesOrderLine<br>Required
SalesOrderLineShipmentId<br>Primary key | Number sequence: <br>Unique
Sequence | Data: Integer
Status | Enumeration: ShipmentStatusValues: Delivered, Open
## SalesOrderLineTax (Sales Order Line Tax) Entity
The tax on a sale order line.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Line Taxes
AmountCurrency | Lookup: Currency<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax Name
RateCode | Data: Text<br>Maximum length: 60
SalesOrderLine | Lookup: SalesOrderLine<br>Required
TaxId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Order Line Tax Id
TaxType | Enumeration: LineTaxTypeValues: Others, SalesTax, VAT
## SalesOrderTax (Sales Order Tax) Entity
The tax on a sales order.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Taxes
AmountCurrency | Lookup: Currency<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax Name
RateCode | Data: Text<br>Maximum length: 60
SalesOrder | Lookup: SalesOrder<br>Required
TaxId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Order Tax Id
TaxType | Enumeration: TaxTypeValues: Others, SalesTax, VAT
