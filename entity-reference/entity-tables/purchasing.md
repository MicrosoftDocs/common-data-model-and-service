---
title: "Purchasing reference | Microsoft Docs"
description: "The purchasing entities let you create purchasing solutions and track vendor invoices."
author: "robinarh"
manager: "robinarh"
ms.date: "05/08/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "b332c83a-cd81-41c0-8ca5-4cd8da77cccf"
---

# Purchasing reference 
## PurchaseOrder (Purchase order) Entity 
An offer for a commercial engagement issued by the company to a vendor to make a purchase. 

Field | Description
---|---
BillingAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
ExpectedShipDate | Data: DateTime
FreightTerms | Picklist: FreightTerms<br>Values: FOB, NoCharge
OrderDate | Data: DateTime<br>Required
Organization | Lookup: Organization
PaymentTerms | Picklist: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
PurchaseOrderId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Order ID
RequestedDeliveryDate | Data: DateTime
ShippingAddress | Data: Address
ShippingMethod | Picklist: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Picklist: PurchaseOrderStatus<br>Values: Blocked, Closed, Confirmed, Invoiced, Open, Received, Suspended<br>Required<br>Description: Order status
TotalAmount | Data: Currency<br>Decimal places: 6
TotalChargeAmount | Data: Currency<br>Decimal places: 6
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6
Vendor | Lookup: Vendor<br>Required
VendorContact | Lookup: Contact
VendorInvoice | Data: Text<br>Maximum length: 128
WorkerBuyer | Lookup: Worker<br>Description: Purchase person

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Vendor|Vendor|OneToMany|Association
Worker|Purchase person|OneToMany|Association
Contact|Vendor contact|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Vendor<br>OrderDate<br>Description<br>WorkerBuyer<br>VendorContact<br>FreightTerms<br>ShippingMethod<br>ShippingAddress<br>VendorInvoice<br>BillingAddress<br>Status
DefaultList|DefaultList field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>Status<br>WorkerBuyer<br>TotalAmount
DefaultCard|DefaultCard field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>WorkerBuyer
DefaultDetails|DefaultDetails field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>Description<br>Status<br>WorkerBuyer<br>VendorContact<br>TotalAmount<br>FreightTerms<br>ShippingMethod<br>ShippingAddress<br>VendorInvoice<br>BillingAddress<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>Description
DefaultReport|DefaultReport field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>Description<br>WorkerBuyer<br>VendorContact<br>TotalAmount<br>FreightTerms<br>ShippingMethod<br>VendorInvoice
DefaultIdentification|DefaultIdentification field group|PurchaseOrderId<br>Description

## PurchaseOrderCharge (Purchase order charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the whole purchase order. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: ChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
PurchaseOrder<br>Primary key | Lookup: PurchaseOrder<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
PurchaseOrder|Purchase order|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PurchaseOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|PurchaseOrder<br>ChargeType<br>Name<br>Amount
DefaultCard|DefaultCard field group|PurchaseOrder<br>ChargeType<br>Name<br>Amount
DefaultDetails|DefaultDetails field group|PurchaseOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|PurchaseOrder<br>ChargeType<br>Name<br>Amount
DefaultReport|DefaultReport field group|PurchaseOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|DefaultIdentification field group|PurchaseOrder<br>ChargeType

## PurchaseOrderLine (Purchase order line) Entity 
A component of a purchase order that contains a portion of the total amount including information such as product, quantity, and price. 

Field | Description
---|---
BusinessUnit | Lookup: BusinessUnit
DeliveryPostalAddress | Data: Address<br>Description: Delivery address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
ExpectedShipDate | Data: DateTime
LineAmount | Data: Currency<br>Required, Decimal places: 6
MostRecentActualReceiptDate | Data: DateTime<br>Description: Most recent actual ship date
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Product
ProductName | Data: Text<br>Required, Maximum length: 60
PromisedShipDate | Data: DateTime
PurchaseOrder<br>Primary key | Lookup: PurchaseOrder<br>Required
Quantity | Data: Quantity<br>Required
RequestedDeliveryDate | Data: DateTime
Sequence | Data: Integer<br>Required
Status | Picklist: PurchaseOrderLineStatus<br>Values: Blocked, Closed, Confirmed, Invoiced, Open, Received, Suspended<br>Required<br>Description: Order line status
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6
UnitPrice | Data: Currency<br>Required, Decimal places: 6
VendorProductName | Data: Text<br>Maximum length: 60

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
PurchaseOrder|Purchase order|OneToMany|Composition
Product|Product|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PurchaseOrder<br>Sequence<br>Product<br>Description<br>Quantity<br>Status<br>UnitPrice<br>LineAmount<br>ProductName
DefaultList|DefaultList field group|PurchaseOrder<br>Sequence<br>Product<br>ProductName<br>Status<br>Quantity<br>LineAmount
DefaultCard|DefaultCard field group|PurchaseOrder<br>Sequence<br>Product<br>ProductName<br>Status<br>Quantity
DefaultDetails|DefaultDetails field group|PurchaseOrder<br>Sequence<br>Product<br>ProductName<br>Description<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>PromisedShipDate<br>MostRecentActualReceiptDate<br>DeliveryPostalAddress<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|PurchaseOrder<br>Sequence<br>ProductName<br>Status<br>Quantity
DefaultReport|DefaultReport field group|PurchaseOrder<br>Sequence<br>Product<br>ProductName<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>PromisedShipDate<br>MostRecentActualReceiptDate
DefaultIdentification|DefaultIdentification field group|PurchaseOrder<br>Sequence<br>ProductName

## PurchaseOrderLineCharge (Purchase order line charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the purchase order line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: LineChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
PurchaseOrderLine<br>Primary key | Lookup: PurchaseOrderLine<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
PurchaseOrderLine|Purchase order line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Amount
DefaultCard|DefaultCard field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Amount
DefaultDetails|DefaultDetails field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Amount
DefaultReport|DefaultReport field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|DefaultIdentification field group|PurchaseOrderLine<br>ChargeType

## PurchaseOrderLineReceipt (Purchase order line receipt) Entity 
The receipt of product on the line of a purchase order for part or all of the line quantity. 

Field | Description
---|---
ActualReceiptDate | Data: Date<br>Required
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
PurchaseOrderLine<br>Primary key | Lookup: PurchaseOrderLine<br>Required
Quantity | Data: Quantity<br>Required
Sequence | Data: Integer<br>Required
Status | Picklist: ShipmentStatus<br>Values: Delivered, Open<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
PurchaseOrderLine|Purchase order line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PurchaseOrderLine<br>Description<br>Quantity<br>Status<br>ActualReceiptDate<br>Sequence
DefaultList|DefaultList field group|Description<br>Quantity<br>Status<br>ActualReceiptDate
DefaultCard|DefaultCard field group|PurchaseOrderLine<br>Quantity<br>Status<br>ActualReceiptDate
DefaultDetails|DefaultDetails field group|PurchaseOrderLine<br>Description<br>Quantity<br>Status<br>ActualReceiptDate<br>Sequence
DefaultLookup|DefaultLookup field group|PurchaseOrderLine<br>Description<br>Quantity<br>Status<br>ActualReceiptDate
DefaultReport|DefaultReport field group|PurchaseOrderLine<br>Description<br>Quantity<br>Status<br>ActualReceiptDate<br>Sequence
DefaultIdentification|DefaultIdentification field group|PurchaseOrderLine<br>Description

## PurchaseOrderLineTax (Purchase order line tax) Entity 
Tax incurred on a purchase order line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
PurchaseOrderLine<br>Primary key | Lookup: PurchaseOrderLine<br>Required
RateCode | Data: Text<br>Maximum length: 60
TaxType | Picklist: LineTaxType<br>Values: Others, SalesTax, VAT<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
PurchaseOrderLine|Purchase order line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>PurchaseOrderLine
DefaultList|DefaultList field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|Name<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>PurchaseOrderLine
DefaultLookup|DefaultLookup field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|DefaultReport field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>PurchaseOrderLine
DefaultIdentification|DefaultIdentification field group|PurchaseOrderLine<br>Name

## PurchaseOrderTax (Purchase order tax) Entity 
Tax incurred on a purchase order as a whole. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
PurchaseOrder<br>Primary key | Lookup: PurchaseOrder<br>Required
RateCode | Data: Text<br>Maximum length: 60
TaxType | Picklist: TaxType<br>Values: Others, SalesTax, VAT<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
PurchaseOrder|Purchase order|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultList|DefaultList field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|PurchaseOrder<br>Name<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultLookup|DefaultLookup field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|DefaultReport field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultIdentification|DefaultIdentification field group|PurchaseOrder<br>Name

## Vendor (Vendor) Entity 
An organization that has sold products to the customer at least once. 

Field | Description
---|---
Birthdate | Data: Date
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 128
DUNSNumber | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FacebookIdentity | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Searchable, Maximum length: 128
Gender | Picklist: Gender<br>Values: Female, Male, Nonspecific, NotSpecified
IndustryCode | Picklist: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
IsDisabledOwned | Data: Boolean<br>Description: Disabled owned
IsEmailContactAllowed | Data: Boolean<br>Required
IsMinorityOwned | Data: Boolean<br>Description: Minority owned
IsNativeAmOwned | Data: Boolean<br>Description: Native American owned
IsPhoneContactAllowed | Data: Boolean<br>Required
IsWomanOwned | Data: Boolean<br>Description: Woman owned
LinkedInIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Organization | Lookup: Organization
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
ParentVendor | Lookup: Vendor
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
PersonName | Data: PersonName<br>Description: Given name
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
Status | Picklist: VendorStatus<br>Values: Active, Blocked, Inactive<br>Required
StockExchange | Picklist: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
SupplierApprovalStatus | Picklist: SupplierApprovalStatus<br>Values: Approved, NotApproved, UnderReview<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
VendorId<br>Primary key | Number sequence: <br>Unique, Searchable<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
WebsiteURL | Data: Text<br>Maximum length: 255

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Vendor|Parent vendor|OneToMany|Association
Contact|Primary contact|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|PersonName<br>Status<br>ParentVendor<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary<br>PartyType<br>Source<br>IsEmailContactAllowed<br>IsPhoneContactAllowed<br>SupplierApprovalStatus
DefaultList|DefaultList field group|VendorId<br>FullName<br>Status<br>PhonePrimary<br>WebsiteURL
DefaultCard|DefaultCard field group|VendorId<br>FullName<br>Status
DefaultDetails|DefaultDetails field group|VendorId<br>FullName<br>PersonName<br>Status<br>ParentVendor<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary<br>MailingPostalAddress<br>ShippingPostalAddress
DefaultLookup|DefaultLookup field group|VendorId<br>FullName<br>Status
DefaultReport|DefaultReport field group|VendorId<br>FullName<br>PersonName<br>Status<br>ParentVendor<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultIdentification|DefaultIdentification field group|VendorId<br>FullName

## VendorContact (Vendor contact) Entity 
Associates a vendor and a contact. This entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Contact | Lookup: Contact<br>Required
DataSource | Picklist: Source<br>Values: Default<br>Required<br>Description: Source
Description | Data: Text<br>Maximum length: 128
Vendor<br>Primary key | Lookup: Vendor<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Vendor|Vendor|OneToMany|Association
Contact|Contact|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultIdentification|DefaultIdentification field group|Vendor<br>Contact
DefaultCreate|DefaultCreate field group|Vendor<br>Contact<br>DataSource<br>Description
DefaultList|DefaultList field group|Vendor<br>Contact<br>DataSource<br>Description
DefaultCard|DefaultCard field group|Vendor<br>Contact<br>DataSource<br>Description
DefaultDetails|DefaultDetails field group|Vendor<br>Contact<br>DataSource<br>Description
DefaultLookup|DefaultLookup field group|Vendor<br>Contact<br>DataSource<br>Description
DefaultReport|DefaultReport field group|Vendor<br>Contact<br>DataSource<br>Description

## VendorInvoice (Vendor invoice) Entity 
An invoice received from a vendor that documents the liability for a purchase. 

Field | Description
---|---
BillingAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
FreightTerms | Picklist: FreightTerms<br>Values: FOB, NoCharge
Organization | Lookup: Organization
PaymentTerms | Picklist: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
PurchaseOrder | Lookup: PurchaseOrder
ShippingAddress | Data: Address
ShippingMethod | Picklist: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Picklist: InvoiceStatus<br>Values: Cancelled, Created, Hold, Paid<br>Required<br>Description: Invoice status
TotalAmount | Data: Currency<br>Decimal places: 6
TotalChargeAmount | Data: Currency<br>Decimal places: 6
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6
Vendor | Lookup: Vendor<br>Required
VendorContact | Lookup: Contact
VendorInvoiceDate | Data: DateTime<br>Required, Searchable<br>Description: Invoice date
VendorInvoiceId<br>Primary key | Number sequence: <br>Unique, Searchable
WorkerBuyer | Lookup: Worker<br>Description: Purchase person

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Vendor|Vendor|OneToMany|Association
Worker|Purchase person|OneToMany|Association
Contact|Vendor contact|OneToMany|Association
PurchaseOrder|Purchase order|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|VendorInvoiceDate<br>Description<br>Vendor<br>VendorContact<br>Status<br>BillingAddress
DefaultList|DefaultList field group|VendorInvoiceId<br>VendorInvoiceDate<br>Description<br>Vendor<br>Status<br>TotalAmount
DefaultCard|DefaultCard field group|VendorInvoiceId<br>VendorInvoiceDate<br>Description<br>Vendor<br>Status<br>TotalAmount
DefaultDetails|DefaultDetails field group|VendorInvoiceId<br>VendorInvoiceDate<br>Description<br>Vendor<br>VendorContact<br>Status<br>TotalAmount<br>FreightTerms<br>PaymentTerms<br>WorkerBuyer<br>ShippingMethod<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount<br>BillingAddress
DefaultLookup|DefaultLookup field group|VendorInvoiceId<br>VendorInvoiceDate<br>Vendor
DefaultReport|DefaultReport field group|VendorInvoiceDate<br>VendorInvoiceId<br>Description<br>Vendor<br>VendorContact<br>Status<br>TotalAmount<br>FreightTerms<br>PaymentTerms<br>WorkerBuyer<br>ShippingMethod<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount<br>BillingAddress
DefaultIdentification|DefaultIdentification field group|VendorInvoiceId

## VendorInvoiceCharge (Vendor invoice charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the whole invoice. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: InvoiceChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
VendorInvoice<br>Primary key | Lookup: VendorInvoice<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
VendorInvoice|Vendor invoice|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|VendorInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|VendorInvoice<br>ChargeType<br>Name<br>Amount
DefaultCard|DefaultCard field group|VendorInvoice<br>ChargeType<br>Name<br>Amount
DefaultDetails|DefaultDetails field group|VendorInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|VendorInvoice<br>ChargeType<br>Name<br>Amount
DefaultReport|DefaultReport field group|VendorInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|DefaultIdentification field group|VendorInvoice<br>Name

## VendorInvoiceLine (Vendor invoice line) Entity 
A component of a vendor invoice that contains a portion of the invoiced amount including information such as product, quantity, and price. 

Field | Description
---|---
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
LineAmount | Data: Currency<br>Required, Decimal places: 6
Name | Data: Text<br>Required, Maximum length: 60
Product | Lookup: Product
ProductName | Data: Text<br>Required, Maximum length: 60
PurchaseOrderLine | Lookup: PurchaseOrderLine
Quantity | Data: Quantity<br>Required
Sequence | Data: Integer<br>Required
Status | Picklist: OrderLineStatus<br>Values: Active, Confirmed, Invoice, PackingSlip, Quote<br>Required<br>Description: Invoice line status
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6
UnitPrice | Data: Currency<br>Required, Decimal places: 6
VendorInvoice<br>Primary key | Lookup: VendorInvoice<br>Required
VendorProductName | Data: Text<br>Maximum length: 60

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Product|Product|OneToMany|Association
VendorInvoice|Vendor invoice|OneToMany|Composition
PurchaseOrderLine|Purchase order line|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|VendorInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity<br>Sequence<br>ProductName<br>UnitPrice
DefaultList|DefaultList field group|VendorInvoice<br>Product<br>Name<br>Status<br>Quantity<br>LineAmount
DefaultCard|DefaultCard field group|VendorInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultDetails|DefaultDetails field group|VendorInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|DefaultLookup field group|VendorInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultReport|DefaultReport field group|VendorInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultIdentification|DefaultIdentification field group|VendorInvoice<br>Product

## VendorInvoiceLineCharge (Vendor Invoice Line Charge) Entity 
An indirect charge in addition to product pricing and taxes, such as freight or insurance, that applies to the invoice line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total line charges
BusinessUnit | Lookup: BusinessUnit
ChargeType | Picklist: InvoiceLineChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
VendorInvoiceLine<br>Primary key | Lookup: VendorInvoiceLine<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
VendorInvoiceLine|Vendor invoice line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|DefaultList field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Amount
DefaultCard|DefaultCard field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Amount
DefaultDetails|DefaultDetails field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|DefaultLookup field group|VendorInvoiceLine<br>ChargeType<br>Amount
DefaultReport|DefaultReport field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|DefaultIdentification field group|VendorInvoiceLine<br>Name

## VendorInvoiceLineTax (Vendor invoice line tax) Entity 
Tax charged on a vendor invoice line. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
TaxType | Picklist: InvoiceLineTaxType<br>Values: Others, SalesTax, VAT<br>Required
VendorInvoiceLine<br>Primary key | Lookup: VendorInvoiceLine<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
VendorInvoiceLine|Vendor invoice line|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>RateCode<br>TaxType<br>Amount<br>VendorInvoiceLine
DefaultList|DefaultList field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|Name<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|VendorInvoiceLine<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultLookup|DefaultLookup field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|DefaultReport field group|VendorInvoiceLine<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultIdentification|DefaultIdentification field group|VendorInvoiceLine<br>Name

## VendorInvoiceTax (Vendor invoice tax) Entity 
Tax charged on a vendor invoice as a whole. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
TaxType | Picklist: InvoiceTaxType<br>Values: Others, SalesTax, VAT<br>Required
VendorInvoice<br>Primary key | Lookup: VendorInvoice<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
VendorInvoice|Vendor invoice|OneToMany|Composition
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|VendorInvoice<br>RateCode<br>TaxType<br>Name<br>Amount<br>Description
DefaultList|DefaultList field group|VendorInvoice<br>RateCode<br>TaxType<br>Amount
DefaultCard|DefaultCard field group|VendorInvoice<br>TaxType<br>Amount
DefaultDetails|DefaultDetails field group|VendorInvoice<br>RateCode<br>TaxType<br>Name<br>Amount<br>Description
DefaultLookup|DefaultLookup field group|VendorInvoice<br>RateCode<br>Amount
DefaultReport|DefaultReport field group|VendorInvoice<br>RateCode<br>TaxType<br>Name<br>Amount
DefaultIdentification|DefaultIdentification field group|VendorInvoice<br>RateCode

