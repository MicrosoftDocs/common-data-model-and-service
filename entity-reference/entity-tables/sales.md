---
title: "Sales reference | Common Data Model"
description: "The sales entities let you create end-to-end sales solutions."
author: "robinarh"
manager: "robinarh"
ms.date: "11/03/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "9ba908bd-88f9-4236-96be-401c9da4d3a2"
---

# Sales reference 
## Account (Account) Entity 
A person or organization that buys offered goods or services. 

Field | Description
---|---
AccountId<br>Primary key | Number sequence: <br>Unique, Searchable
Birthdate | Data: Date
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Data: Picklist
IndustryCode | Data: Picklist
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address<br>Description: Mailing postal address line 1
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address<br>Description: Other postal address line 1
ParentAccount | Lookup: Account
PartyType | Data: Picklist<br>Required
PersonName | Data: PersonName<br>Description: Given name
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
PrimaryContact | Lookup: Contact
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
WebsiteURL | Data: Text<br>Maximum length: 255

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|FullName<br>PersonName<br>Status<br>ParentAccount<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultList|DefaultList field group|AccountId<br>FullName<br>Status<br>PhonePrimary<br>WebsiteURL
DefaultCard|DefaultCard field group|AccountId<br>FullName<br>Status
DefaultDetails|DefaultDetails field group|AccountId<br>FullName<br>PersonName<br>Status<br>ParentAccount<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary<br>MailingPostalAddress<br>ShippingPostalAddress
DefaultLookup|DefaultLookup field group|AccountId<br>FullName<br>Status
DefaultReport|DefaultReport field group|AccountId<br>FullName<br>PersonName<br>Status<br>ParentAccount<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultIdentification|DefaultIdentification field group|AccountId<br>FullName
## Lead (Lead) Entity 
Lead table can store information about individuals who are interested in receiving information about the products or services offered by the company. 

Field | Description
---|---
Birthdate | Data: Date
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Data: Picklist
Generation | Data: Text<br>Maximum length: 128
IndustryCode | Data: Picklist
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LeadId<br>Primary key | Number sequence: <br>Unique, Searchable
LinkedInIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address<br>Description: Mailing postal address line 1
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address<br>Description: Other postal address line 1
PartyType | Data: Picklist<br>Required
PersonName | Data: PersonName<br>Description: Given name
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
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
StockExchange | Data: Picklist
StockTicker | Data: Text<br>Maximum length: 128
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PersonName<br>Status<br>WebsiteURL
DefaultList|DefaultList field group|LeadId<br>FullName<br>Status<br>WebsiteURL<br>Source
DefaultCard|DefaultCard field group|LeadId<br>FullName<br>Status
DefaultDetails|DefaultDetails field group|LeadId<br>FullName<br>PersonName<br>Status<br>WebsiteURL<br>Source<br>Description<br>PhonePrimary<br>EmailPrimary<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity
DefaultLookup|DefaultLookup field group|LeadId<br>FullName<br>Status
DefaultReport|DefaultReport field group|LeadId<br>FullName<br>PersonName<br>Status<br>WebsiteURL<br>Source<br>PhonePrimary<br>EmailPrimary
DefaultIdentification|DefaultIdentification field group|LeadId<br>FullName
## Opportunity (Opportunity) Entity 
Opportunity table can track information about potential sales to new or established customers. 

Field | Description
---|---
ActualCloseDate | Data: DateTime
ActualValueAmount | Data: Currency<br>Required, Decimal places: 6
CreatedDate | Data: Date<br>Required
Description | Data: Text<br>Maximum length: 128
EstimatedCloseDate | Data: DateTime
EstimatedValueAmount | Data: Currency<br>Required, Decimal places: 6
IndustryCode | Data: Picklist<br>Required
Name | Data: Text<br>Required, Maximum length: 128
NextFollowupDate | Data: Date<br>Description: Next follow-up date
OpportunityId<br>Primary key | Number sequence: <br>Unique, Searchable
OriginalEstimatedValueAmount | Data: Currency<br>Required, Decimal places: 6
ParentOpportunity | Lookup: Opportunity
PurchaseProcess | Data: Picklist<br>Required
PurchaseTimeFrame | Data: Picklist<br>Required
RatingCode | Data: Picklist<br>Required
SalesStage | Data: Picklist
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>Status<br>OriginalEstimatedValueAmount<br>EstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame<br>PurchaseProcess<br>SalesStage<br>Description
DefaultList|DefaultList field group|OpportunityId<br>Name<br>Status<br>OriginalEstimatedValueAmount<br>EstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame
DefaultCard|DefaultCard field group|OpportunityId<br>Name<br>Status
DefaultDetails|DefaultDetails field group|OpportunityId<br>Name<br>Status<br>OriginalEstimatedValueAmount<br>EstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame<br>PurchaseProcess<br>SalesStage<br>Description<br>CreatedDate<br>Source<br>IndustryCode<br>RatingCode
DefaultLookup|DefaultLookup field group|OpportunityId<br>Name<br>Status
DefaultReport|DefaultReport field group|OpportunityId<br>Name<br>Status<br>OriginalEstimatedValueAmount<br>EstimatedValueAmount<br>EstimatedCloseDate<br>PurchaseTimeFrame<br>PurchaseProcess<br>SalesStage<br>Description<br>CreatedDate<br>Source<br>IndustryCode<br>RatingCode
DefaultIdentification|DefaultIdentification field group|OpportunityId<br>Name
## Partner (Partner) Entity 
An organization that takes part in a business relationship with another organization with shared risks and profits. 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
IndustryCode | Data: Picklist
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
IsSecurityPrincipal | Data: Boolean<br>Required
LinkedInIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address<br>Description: Mailing postal address line 1
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address<br>Description: Other postal address line 1
ParentPartner | Lookup: Partner
PartnerId<br>Primary key | Number sequence: <br>Unique, Searchable
PartyType | Data: Picklist<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
PrimaryContact | Lookup: Contact
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
WebsiteURL | Data: Text<br>Maximum length: 255

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PhonePrimary<br>ParentPartner<br>WebsiteURL
DefaultList|DefaultList field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL
DefaultCard|DefaultCard field group|PartnerId<br>FullName<br>PhonePrimary
DefaultDetails|DefaultDetails field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL<br>Description<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>MailingPostalAddress<br>StockTicker
DefaultLookup|DefaultLookup field group|PartnerId<br>FullName<br>PhonePrimary
DefaultReport|DefaultReport field group|PartnerId<br>FullName<br>PhonePrimary<br>ParentPartner<br>WebsiteURL<br>FacebookIdentity<br>LinkedInIdentity<br>TwitterIdentity<br>MailingPostalAddress<br>StockTicker
DefaultIdentification|DefaultIdentification field group|PartnerId<br>FullName
## SalesInvoice (Sales invoice) Entity 
An invoice sent to a customer to document the customer's liability for a purchase. 

Field | Description
---|---
Account | Lookup: Account<br>Required
AccountContact | Lookup: Contact
BillingAddress | Data: Address<br>Description: Address line 1
CustomerPurchaseOrderReference | Data: Text<br>Maximum length: 20
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
FreightTerms | Data: Picklist
InvoiceDate | Data: DateTime<br>Required
Name | Data: Text<br>Maximum length: 60
Opportunity | Lookup: Opportunity
PaymentTerms | Data: Picklist
SalesInvoiceId<br>Primary key | Number sequence: <br>Unique, Searchable
SalesOrder | Lookup: SalesOrder
SalesPersonWorker | Lookup: Worker
ShippingMethod | Data: Picklist
Status | Data: Picklist<br>Description: Invoice status
TotalAmount | Data: Currency<br>Decimal places: 6
TotalChargeAmount | Data: Currency<br>Decimal places: 6
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6

###Field groups

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
An indirect charge in addition to product pricing and taxes such as freight, insurance etc., that applies to the whole invoice. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
ChargeType | Data: Picklist<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesInvoice<br>Primary key | Lookup: SalesInvoice<br>Required

###Field groups

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
Status | Data: Picklist<br>Required<br>Description: Invoice line status
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6
UnitPrice | Data: Currency<br>Required, Decimal places: 6

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity
DefaultList|DefaultList field group|SalesInvoice<br>Product<br>Name<br>Status<br>Quantity<br>LineAmount
DefaultCard|DefaultCard field group|SalesInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultDetails|DefaultDetails field group|SalesInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|SalesInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultReport|DefaultReport field group|SalesInvoice<br>Product<br>Name<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultIdentification|DefaultIdentification field group|SalesInvoice<br>Sequence<br>Product
## SalesInvoiceLineCharge (Sales invoice line charge) Entity 
An indirect charge in addition to product pricing and taxes such as freight, insurance etc., that applies to the invoice line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
ChargeType | Data: Picklist<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesInvoiceLine<br>Primary key | Lookup: SalesInvoiceLine<br>Required

###Field groups

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
Tax charged on a sales Invoice line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesInvoiceLine<br>Primary key | Lookup: SalesInvoiceLine<br>Required
TaxType | Data: Picklist<br>Required

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultList|DefaultList field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|Name<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>SalesInvoiceLine
DefaultLookup|DefaultLookup field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|DefaultReport field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>SalesInvoiceLine
DefaultIdentification|DefaultIdentification field group|SalesInvoiceLine<br>Name
## SalesInvoiceTax (Sales invoice tax) Entity 
Tax charged on a sales Invoice as a whole. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesInvoice<br>Primary key | Lookup: SalesInvoice<br>Required
TaxType | Data: Picklist<br>Required

###Field groups

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
Account | Lookup: Account<br>Required
AccountContact | Lookup: Contact
BillingAddress | Data: Address<br>Description: Billing address line 1
CustomerPurchaseOrderReference | Data: Text<br>Maximum length: 20
DeliveryAddress | Data: Address<br>Description: Delivery address line 1
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
FreightTerms | Data: Picklist
Name | Data: Text<br>Maximum length: 60
Opportunity | Lookup: Opportunity
OrderDate | Data: DateTime<br>Required
PaymentTerms | Data: Picklist
SalesOrderId<br>Primary key | Number sequence: <br>Unique, Searchable
SalesPersonWorker | Lookup: Worker
ShippingMethod | Data: Picklist
Status | Data: Picklist<br>Required<br>Description: Order status
TotalAmount | Data: Currency<br>Required, Decimal places: 6
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6

###Field groups

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
An indirect charge in addition to product pricing and taxes such as freight, insurance etc., that applies to the whole sales order 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
ChargeType | Data: Picklist<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesOrder<br>Primary key | Lookup: SalesOrder<br>Required

###Field groups

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
DeliveryPostalAddress | Data: Address<br>Description: Delivery postal address line 1
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
SalesOrder<br>Primary key | Lookup: SalesOrder<br>Required
Sequence | Data: Integer<br>Required
Status | Data: Picklist<br>Description: Order line status
TotalChargeAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6
UnitPrice | Data: Currency<br>Decimal places: 6

###Field groups

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
An indirect charge in addition to product pricing and taxes such as freight, insurance etc., that applies to the sales order line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
ChargeType | Data: Picklist<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
SalesOrderLine<br>Primary key | Lookup: SalesOrderLine<br>Required

###Field groups

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
Delivery schedule for a sales order line. 

Field | Description
---|---
ActualShipDate | Data: Date
Description | Data: Text<br>Maximum length: 60
Quantity | Data: Quantity
SalesOrderLine<br>Primary key | Lookup: SalesOrderLine<br>Required
Sequence | Data: Integer<br>Required
Status | Data: Picklist

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|ActualShipDate<br>SalesOrderLine<br>Description<br>Quantity<br>Status
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
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesOrderLine<br>Primary key | Lookup: SalesOrderLine<br>Required
TaxType | Data: Picklist<br>Required

###Field groups

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
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
SalesOrder<br>Primary key | Lookup: SalesOrder<br>Required
TaxType | Data: Picklist<br>Required

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultList|DefaultList field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|SalesOrder<br>Name<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultLookup|DefaultLookup field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|DefaultReport field group|SalesOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultIdentification|DefaultIdentification field group|SalesOrder<br>Name
