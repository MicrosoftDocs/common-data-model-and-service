---
title: "Purchasing reference"
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
ms.assetid: "b332c83a-cd81-41c0-8ca5-4cd8da77cccf"
---

# Purchasing
## PurchaseOrder (@Purchase.PurchaseOrder) Entity 
A first offer for a commercial engagement that the company issues to a supplier. The PurchaseOrder entity indicates the types, quantities, prices, and delivery timelines for products and services. 

Field | Description
---|---
BillingAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
FreightTerms | Enumeration: FreightTerms<br>Values: FOB, NoCharge
OrderDate | Data: DateTime<br>Required
PaymentTerms | Enumeration: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
PurchaseOrderId<br>Primary key | Number sequence: <br>Unique<br>Description: Order id
ShippingAddress | Data: Address
ShippingMethod | Enumeration: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Enumeration: PurchaseOrderStatus<br>Values: Blocked, Closed, Confirmed, Invoiced, Open, Received, Suspended<br>Required<br>Description: Order status
TotalAmount | Data: Currency<br>Decimal places: 6
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total charges
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total taxes
Vendor | Lookup: Vendor<br>Required
VendorContact | Lookup: Contact
VendorInvoice | Data: Text<br>Maximum length: 128
WorkerBuyer | Lookup: Worker

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>Description<br>WorkerBuyer<br>VendorContact<br>FreightTerms<br>ShippingMethod<br>ShippingAddress<br>VendorInvoice<br>BillingAddress
DefaultList|Auto generated DefaultList field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>Status<br>WorkerBuyer<br>TotalAmount
DefaultCard|Auto generated DefaultCard field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>WorkerBuyer
DefaultDetails|Auto generated DefaultDetails field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>Description<br>Status<br>WorkerBuyer<br>VendorContact<br>TotalAmount<br>FreightTerms<br>ShippingMethod<br>ShippingAddress<br>VendorInvoice<br>BillingAddress<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultLookup|Auto generated DefaultLookup field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>Description
DefaultReport|Auto generated DefaultReport field group|PurchaseOrderId<br>Vendor<br>OrderDate<br>Description<br>WorkerBuyer<br>VendorContact<br>TotalAmount<br>FreightTerms<br>ShippingMethod<br>VendorInvoice
DefaultIdentification|Auto generated DefaultIdentification field group|PurchaseOrderId<br>Description
## PurchaseOrderCharge (@Purchase.PurchaseOrderCharges) Entity 
A purchase order charge. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total charges
ChargeType | Enumeration: ChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
PurchaseOrder<br>Primary key | Lookup: PurchaseOrder<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|PurchaseOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|Auto generated DefaultList field group|PurchaseOrder<br>ChargeType<br>Name<br>Amount
DefaultCard|Auto generated DefaultCard field group|PurchaseOrder<br>ChargeType<br>Name<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|PurchaseOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|Auto generated DefaultLookup field group|PurchaseOrder<br>ChargeType<br>Name<br>Amount
DefaultReport|Auto generated DefaultReport field group|PurchaseOrder<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|PurchaseOrder<br>ChargeType
## PurchaseOrderLine (@Purchase.PurchaseOrderLines) Entity 
A purchase order line item. 

Field | Description
---|---
DeliveryPostalAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
ExpectedShipDate | Data: DateTime
LineAmount | Data: Currency<br>Required, Decimal places: 6
MostRecentActualReceiptDate | Data: DateTime<br>Description: Most recent actual ship date
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Product
ProductName | Data: Text<br>Required, Maximum length: 60
ProductUnitOfMeasure_UOM | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard<br>Description: Product unit of measure
PromisedShipDate | Data: DateTime
PurchaseOrder<br>Primary key | Lookup: PurchaseOrder<br>Required
Quantity | Data: Quantity<br>Required
Sequence | Data: Integer<br>Required
Status | Enumeration: PurchaseOrderLineStatus<br>Values: Blocked, Closed, Confirmed, Invoiced, Open, Received, Suspended<br>Required<br>Description: Order line status
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total charges
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total taxes
UnitPrice | Data: Currency<br>Required, Decimal places: 6
VendorProductName | Data: Text<br>Maximum length: 60
VendorProductUnitOfMeasure_UOM | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard<br>Description: Vendor product unit of measure

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|PurchaseOrder<br>Sequence<br>Product<br>Description<br>Quantity<br>Status<br>UnitPrice<br>LineAmount
DefaultList|Auto generated DefaultList field group|PurchaseOrder<br>Product<br>ProductName<br>Status<br>Quantity<br>LineAmount
DefaultCard|Auto generated DefaultCard field group|PurchaseOrder<br>Product<br>ProductName<br>Status<br>Quantity
DefaultDetails|Auto generated DefaultDetails field group|PurchaseOrder<br>Sequence<br>Product<br>ProductName<br>Description<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>PromisedShipDate<br>MostRecentActualReceiptDate<br>DeliveryPostalAddress<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|Auto generated DefaultLookup field group|PurchaseOrder<br>ProductName<br>Status<br>Quantity
DefaultReport|Auto generated DefaultReport field group|PurchaseOrder<br>Product<br>ProductName<br>Status<br>Quantity<br>UnitPrice<br>LineAmount<br>PromisedShipDate<br>MostRecentActualReceiptDate
DefaultIdentification|Auto generated DefaultIdentification field group|PurchaseOrder<br>Sequence<br>ProductName
## PurchaseOrderLineCharge (@Purchase.PurchaseOrderLineCharge) Entity 
A purchase order line item charge. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total line charges
ChargeType | Enumeration: LineChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
PurchaseOrderLine<br>Primary key | Lookup: PurchaseOrderLine<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|Auto generated DefaultList field group|PurchaseOrderLine<br>Name<br>Amount
DefaultCard|Auto generated DefaultCard field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|Auto generated DefaultLookup field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Amount
DefaultReport|Auto generated DefaultReport field group|PurchaseOrderLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|PurchaseOrderLine<br>ChargeType
## PurchaseOrderLineReceipt (@Purchase.PurchaseOrderLineReceipt) Entity 
A purchase order line item receipt. 

Field | Description
---|---
ActualReceiptDate | Data: Date<br>Required
Description | Data: Text<br>Maximum length: 60
PurchaseOrderLine<br>Primary key | Lookup: PurchaseOrderLine<br>Required
Quantity | Data: Number<br>Required
Sequence | Data: Integer<br>Required
Status | Enumeration: ShipmentStatus<br>Values: Delivered, Open<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|PurchaseOrderLine<br>Description<br>Quantity<br>Status<br>ActualReceiptDate<br>Sequence
DefaultList|Auto generated DefaultList field group|Description<br>Quantity<br>Status<br>ActualReceiptDate
DefaultCard|Auto generated DefaultCard field group|PurchaseOrderLine<br>Quantity<br>Status<br>ActualReceiptDate
DefaultDetails|Auto generated DefaultDetails field group|PurchaseOrderLine<br>Description<br>Quantity<br>Status<br>ActualReceiptDate<br>Sequence
DefaultLookup|Auto generated DefaultLookup field group|PurchaseOrderLine<br>Description<br>Quantity<br>Status<br>ActualReceiptDate
DefaultReport|Auto generated DefaultReport field group|PurchaseOrderLine<br>Description<br>Quantity<br>Status<br>ActualReceiptDate<br>Sequence
DefaultIdentification|Auto generated DefaultIdentification field group|PurchaseOrderLine<br>Description
## PurchaseOrderLineTax (@Purchase.PurchaseOrderLineTax) Entity 
The purchase order line item tax. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total line taxes
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
PurchaseOrderLine<br>Primary key | Lookup: PurchaseOrderLine<br>Required
RateCode | Data: Text<br>Maximum length: 60
TaxType | Enumeration: LineTaxType<br>Values: Others, SalesTax, VAT<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>PurchaseOrderLine
DefaultList|Auto generated DefaultList field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|Auto generated DefaultCard field group|Name<br>TaxType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>PurchaseOrderLine
DefaultLookup|Auto generated DefaultLookup field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|Auto generated DefaultReport field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>PurchaseOrderLine
DefaultIdentification|Auto generated DefaultIdentification field group|PurchaseOrderLine<br>Name
## PurchaseOrderTax (@Purchase.PurchaseOrderTax) Entity 
The tax on a purchase order. 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total taxes
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
PurchaseOrder<br>Primary key | Lookup: PurchaseOrder<br>Required
RateCode | Data: Text<br>Maximum length: 60
TaxType | Enumeration: TaxType<br>Values: Others, SalesTax, VAT<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultList|Auto generated DefaultList field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|Auto generated DefaultCard field group|PurchaseOrder<br>Name<br>TaxType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultLookup|Auto generated DefaultLookup field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|Auto generated DefaultReport field group|PurchaseOrder<br>Name<br>RateCode<br>TaxType<br>Amount<br>Description
DefaultIdentification|Auto generated DefaultIdentification field group|PurchaseOrder<br>Name
## Vendor (@Foundation.Vendor) Entity 
@Purchase.VendorHelp 

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
IndustryCode | Enumeration: IndustryCode<br>Values: Accounting, Agriculture, BroadcastingPrintingPublishing, Brokers, BuildingSupplyRetail, BusinessServices, Consulting, ConsumerServices, DesignCreativeManagement, DistributorsDispatchersProcessors, DoctorOfficesClinics, DurableManufacturing, EatingDrinkingPlaces, EntertainmentRetail, EquipmentRentalLeasing, Financial, FoodTobaccoProcessing, InboundCapitalIntensiveProcessing, InboundRepairServices, Insurance, LegalServices, NonDurableMerchandiseRetail, OutboundConsumerService, Petrochemicals, ServiceRetail, SIGAffiliations, SocialServices, SpecialOutboundTradeContractors, SpecialtyRealty, Transportation, UtilityCreationDistribution, VehicleRetail, Wholesale
IsDisabledOwned | Data: Boolean<br>Description: Disabled owned
IsEmailContactAllowed | Data: Boolean<br>Required
IsMinorityOwned | Data: Boolean<br>Description: Minority owned
IsNativeAmOwned | Data: Boolean<br>Description: Native American owned
IsPhoneContactAllowed | Data: Boolean<br>Required
IsWomanOwned | Data: Boolean<br>Description: Woman owned
LinkedinIdentity | Data: Text<br>Maximum length: 128
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
ParentVendor | Lookup: Vendor
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
Status | Enumeration: VendorStatus<br>Values: Active, Blocked, Inactive<br>Required
StockExchange | Enumeration: StockExchange<br>Values: BMESpanishExchanges, Euronext, FrankfurtStockExchange, HongKongStockExchange, ItalianStockExchange, KoreaExchange, LondonStockExchange, NASDAQ, NYSE, OMXNordicExchanges, ShanghaiStockExchange, ShenzhenStockExchange, SWXSwissExchange, TokyoStockExchange, TorontoStockExchange
StockTicker | Data: Text<br>Maximum length: 128
SupplierApprovalStatus | Enumeration: SupplierApprovalStatus<br>Values: Approved, NotApproved, UnderReview<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
TwitterIdentity | Data: Text<br>Maximum length: 128
VendorId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an Id number or code for the account to quickly search and identify the account in system views.
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|VendorId<br>FullName<br>PersonName<br>Status<br>ParentVendor<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultList|Auto generated DefaultList field group|VendorId<br>FullName<br>Status<br>PhonePrimary<br>WebsiteURL
DefaultCard|Auto generated DefaultCard field group|VendorId<br>FullName<br>Status
DefaultDetails|Auto generated DefaultDetails field group|VendorId<br>FullName<br>PersonName<br>Status<br>ParentVendor<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultLookup|Auto generated DefaultLookup field group|VendorId<br>FullName<br>Status
DefaultReport|Auto generated DefaultReport field group|VendorId<br>FullName<br>PersonName<br>Status<br>ParentVendor<br>Description<br>EmailPrimary<br>WebsiteURL<br>PhonePrimary
DefaultIdentification|Auto generated DefaultIdentification field group|VendorId<br>FullName
## VendorInvoice (@Purchase.VendorInvoice) Entity 
@Purchase.VendorInvoiceHelp 

Field | Description
---|---
BillingAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
FreightTerms | Enumeration: FreightTerms<br>Values: FOB, NoCharge
PaymentTerms | Enumeration: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
PurchaseOrder | Lookup: PurchaseOrder<br>Required
ShippingAddress | Data: Address
ShippingMethod | Enumeration: ShippingMethod<br>Values: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Enumeration: InvoiceStatus<br>Values: Cancelled, Created, Hold, Paid<br>Required<br>Description: Invoice status
TotalAmount | Data: Currency<br>Decimal places: 6
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total charges
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total taxes
Vendor | Lookup: Vendor<br>Required
VendorContact | Lookup: Contact
VendorInvoiceDate | Data: DateTime<br>Required<br>Description: Invoice date
VendorInvoiceId<br>Primary key | Number sequence: <br>Unique
WorkerBuyer | Lookup: Worker

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|VendorInvoiceDate<br>VendorInvoiceId<br>Description<br>Vendor<br>VendorContact<br>Status<br>BillingAddress
DefaultList|Auto generated DefaultList field group|VendorInvoiceDate<br>VendorInvoiceId<br>Description<br>Vendor<br>Status<br>TotalAmount
DefaultCard|Auto generated DefaultCard field group|VendorInvoiceDate<br>VendorInvoiceId<br>Description<br>Vendor<br>Status<br>TotalAmount
DefaultDetails|Auto generated DefaultDetails field group|VendorInvoiceDate<br>VendorInvoiceId<br>Description<br>Vendor<br>VendorContact<br>Status<br>BillingAddress<br>TotalAmount<br>FreightTerms<br>PaymentTerms<br>WorkerBuyer<br>ShippingMethod<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultLookup|Auto generated DefaultLookup field group|VendorInvoiceDate<br>VendorInvoiceId<br>Vendor
DefaultReport|Auto generated DefaultReport field group|VendorInvoiceDate<br>VendorInvoiceId<br>Description<br>Vendor<br>VendorContact<br>Status<br>BillingAddress<br>TotalAmount<br>FreightTerms<br>PaymentTerms<br>WorkerBuyer<br>ShippingMethod<br>TotalChargeAmount<br>TotalDiscountAmount<br>TotalTaxAmount
DefaultIdentification|Auto generated DefaultIdentification field group|VendorInvoiceId
## VendorInvoiceCharge (@Purchase.VendorInvoiceCharges) Entity 
@Purchase.VendorInvoiceChargeHelp 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total charges
ChargeType | Enumeration: InvoiceChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
VendorInvoice<br>Primary key | Lookup: VendorInvoice<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|VendorInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|Auto generated DefaultList field group|VendorInvoice<br>ChargeType<br>Name<br>Amount
DefaultCard|Auto generated DefaultCard field group|VendorInvoice<br>ChargeType<br>Name<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|VendorInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|Auto generated DefaultLookup field group|VendorInvoice<br>ChargeType<br>Name<br>Amount
DefaultReport|Auto generated DefaultReport field group|VendorInvoice<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|VendorInvoice<br>Name
## VendorInvoiceLine (@Purchase.VendorInvoiceLines) Entity 
@Purchase.VendorInvoiceLineHelp 

Field | Description
---|---
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Required, Decimal places: 6
LineAmount | Data: Currency<br>Required, Decimal places: 6
Name | Data: Text<br>Required, Maximum length: 60
Product | Lookup: Product
ProductName | Data: Text<br>Required, Maximum length: 60
ProductUnitOfMeasure_UOM | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard<br>Description: Product unit of measure
PurchaseOrder_PurchaseOrderId | Number sequence: <br>Unique<br>Description: Order id
PurchaseOrderLine_Sequence | Data: Integer<br>Required<br>Description: Sequence
Quantity | Data: Quantity<br>Required
Sequence | Data: Integer<br>Required
Status | Enumeration: OrderLineStatus<br>Values: Active, Confirmed, Invoice, PackingSlip, Quote<br>Required<br>Description: Invoice line status
TotalChargeAmount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total charges
TotalTaxAmount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total taxes
UnitPrice | Data: Currency<br>Required, Decimal places: 6
VendorInvoice<br>Primary key | Lookup: VendorInvoice<br>Required
VendorProduct | Lookup: Product
VendorProductName | Data: Text<br>Maximum length: 60

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|VendorInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity
DefaultList|Auto generated DefaultList field group|VendorInvoice<br>Product<br>Name<br>Status<br>Quantity<br>LineAmount
DefaultCard|Auto generated DefaultCard field group|VendorInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultDetails|Auto generated DefaultDetails field group|VendorInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultLookup|Auto generated DefaultLookup field group|VendorInvoice<br>Product<br>Status<br>Quantity<br>LineAmount
DefaultReport|Auto generated DefaultReport field group|VendorInvoice<br>Product<br>Name<br>Description<br>Status<br>Quantity<br>LineAmount<br>DiscountAmount<br>TotalChargeAmount<br>TotalTaxAmount
DefaultIdentification|Auto generated DefaultIdentification field group|VendorInvoice<br>Product
## VendorInvoiceLineCharge (@Purchase.VendorInvoiceLineCharge) Entity 
@Purchase.VendorInvoiceLineChargeHelp 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total line charges
ChargeType | Enumeration: InvoiceLineChargeType<br>Values: Freight, Insurance, Others<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge name
VendorInvoiceLine<br>Primary key | Lookup: VendorInvoiceLine<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultList|Auto generated DefaultList field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Amount
DefaultCard|Auto generated DefaultCard field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultLookup|Auto generated DefaultLookup field group|VendorInvoiceLine<br>ChargeType<br>Amount
DefaultReport|Auto generated DefaultReport field group|VendorInvoiceLine<br>ChargeType<br>Name<br>Description<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|VendorInvoiceLine<br>Name
## VendorInvoiceLineTax (@Purchase.VendorInvoiceLineTax) Entity 
@Purchase.VendorInvoiceLineTaxHelp 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total invoice line taxes
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
TaxType | Enumeration: InvoiceLineTaxType<br>Values: Others, SalesTax, VAT<br>Required
VendorInvoiceLine<br>Primary key | Lookup: VendorInvoiceLine<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultList|Auto generated DefaultList field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultCard|Auto generated DefaultCard field group|Name<br>TaxType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>VendorInvoiceLine
DefaultLookup|Auto generated DefaultLookup field group|Name<br>RateCode<br>TaxType<br>Amount
DefaultReport|Auto generated DefaultReport field group|Name<br>RateCode<br>TaxType<br>Amount<br>Description<br>VendorInvoiceLine
DefaultIdentification|Auto generated DefaultIdentification field group|VendorInvoiceLine<br>Name
## VendorInvoiceTax (@Purchase.VendorInvoiceTax) Entity 
@Purchase.VendorInvoiceTaxHelp 

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total taxes
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax name
RateCode | Data: Text<br>Maximum length: 60
TaxType | Enumeration: InvoiceTaxType<br>Values: Others, SalesTax, VAT<br>Required
VendorInvoice<br>Primary key | Lookup: VendorInvoice<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|VendorInvoice<br>RateCode<br>TaxType<br>Name<br>Amount<br>Description
DefaultList|Auto generated DefaultList field group|VendorInvoice<br>RateCode<br>TaxType<br>Amount
DefaultCard|Auto generated DefaultCard field group|VendorInvoice<br>TaxType<br>Amount
DefaultDetails|Auto generated DefaultDetails field group|VendorInvoice<br>RateCode<br>TaxType<br>Name<br>Amount<br>Description
DefaultLookup|Auto generated DefaultLookup field group|VendorInvoice<br>RateCode<br>Amount
DefaultReport|Auto generated DefaultReport field group|VendorInvoice<br>RateCode<br>TaxType<br>Name<br>Amount
DefaultIdentification|Auto generated DefaultIdentification field group|VendorInvoice<br>RateCode
