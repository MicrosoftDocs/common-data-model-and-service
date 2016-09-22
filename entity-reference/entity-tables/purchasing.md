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

# Purchase
## PurchaseOrder (Purchase Order) Entity
A first offer for a commercial engagement that the company issues to a supplier. The PurchaseOrder entity indicates the types, quantities, prices, and delivery timelines for products and services.

Field | Description
---|---
BillingAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
DiscountAmountCurrency | Lookup: Currency
DiscountPercent | Data: Number
FreightTerms | Enumeration: FreightTermsValues: FOB, NoCharge
OrderDate | Data: DateTime<br>Required
PaymentTerms | Enumeration: PaymentTermsValues: Net30, Net45, Net60, TwoPercent10Net30
PurchaseOrderId<br>Primary key | Number sequence: <br>Unique<br>Description: Order number
PurchasePerson | Lookup: Employee
ShippingAddress | Data: Address
ShippingMethod | Enumeration: ShippingMethodValues: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Enumeration: PurchaseOrderStatusValues: Blocked, Closed, Confirmed, Invoiced, Open, Received, Suspended<br>Description: Order Status
Supplier | Lookup: Supplier<br>Required
SupplierContact | Lookup: Supplier
SupplierInvoice | Data: Text<br>Maximum length: 128
TotalAmount | Data: Currency<br>Decimal places: 6
TotalAmountCurrency | Lookup: Currency
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Charges
TotalChargeAmountCurrency | Lookup: Currency
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalDiscountAmountCurrency | Lookup: Currency
TotalDiscountPercent | Data: Number
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Taxes
TotalTaxAmountCurrency | Lookup: Currency
## PurchaseOrderCharge (Purchase Order Charges) Entity
A purchase order charge.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Charges
AmountCurrency | Lookup: Currency
ChargeId<br>Primary key | Number sequence: <br>Unique<br>Description: Purchase Order Charge Id
ChargeType | Enumeration: ChargeTypeValues: Freight, Insurance, Others
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge Name
PurchaseOrder | Lookup: PurchaseOrder<br>Required
## PurchaseOrderLine (Purchase Order Lines) Entity
A purchase order line item.

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
MostRecentActualReceiptDate | Data: DateTime<br>Description: Most Recent Actual Ship Date
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Products
ProductName | Data: Text<br>Maximum length: 60
ProductUnitOfMeasure | Lookup: Units
PromisedShipDate | Data: DateTime
PurchaseOrder | Lookup: PurchaseOrder<br>Required
PurchaseOrderLineId<br>Primary key | Number sequence: <br>Unique<br>Description: Purchase Order Line Number
Quantity | Data: Number
Sequence | Data: Integer
Status | Enumeration: PurchaseOrderLineStatusValues: Blocked, Closed, Confirmed, Invoiced, Open, Received, Suspended<br>Description: Order Line Status
SupplierProductName | Data: Text<br>Maximum length: 60
SupplierProductUnitOfMeasure | Lookup: Units
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Charge
TotalChargesCurrency | Lookup: Currency
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Tax
TotalTaxesCurrency | Lookup: Currency
UnitPrice | Data: Currency<br>Decimal places: 6
UnitPriceCurrency | Lookup: Currency
## PurchaseOrderLineCharge (Purchase Order Line Charge) Entity
A purchase order line item charge.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Line Charges
AmountCurrency | Lookup: Currency
ChargeType | Enumeration: LineChargeTypeValues: Freight, Insurance, Others
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge Name
PurchaseOrderLine | Lookup: PurchaseOrderLine<br>Required
PurchaseOrderLineChargeId<br>Primary key | Number sequence: <br>Unique
## PurchaseOrderLineReceipt (Purchase Order Line Receipt) Entity
A purchase order line item receipt.

Field | Description
---|---
ActualReceiptDate | Data: Date
Description | Data: Text<br>Maximum length: 60
PurchaseOrderLine | Lookup: PurchaseOrderLine<br>Required
PurchaseOrderLineReceiptId<br>Primary key | Number sequence: <br>Unique
Quantity | Data: Number
Sequence | Data: Integer
Status | Enumeration: ShipmentStatusValues: Delivered, Open
## PurchaseOrderLineTax (Purchase Order Line Tax) Entity
The purchase order line item tax.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Line Taxes
AmountCurrency | Lookup: Currency<br>Required
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax Name
PurchaseOrderLine | Lookup: PurchaseOrderLine<br>Required
PurchaseOrderLineTaxId<br>Primary key | Number sequence: <br>Unique
RateCode | Data: Text<br>Maximum length: 60
TaxType | Enumeration: LineTaxTypeValues: Others, SalesTax, VAT
## PurchaseOrderTax (Purchase Order Tax) Entity
The tax on a purchase order.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Taxes
AmountCurrency | Lookup: Currency
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax Name
PurchaseOrder | Lookup: PurchaseOrder<br>Required
PurchaseOrderTaxId<br>Primary key | Number sequence: <br>Unique
RateCode | Data: Text<br>Maximum length: 60
TaxType | Enumeration: TaxTypeValues: Others, SalesTax, VAT
## Supplier (Supplier) Entity
An organization that supplies something.

Field | Description
---|---
BusinessPhone | Data: Phone
CellPhone | Data: Phone
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FirstName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
FullName | Data: Text<br>Maximum length: 128
HomePhone | Data: Phone
IsApprovedSupplier | Data: Boolean<br>Description: Approved supplier
IsDisabledOwned | Data: Boolean<br>Description: Disabled owned
IsMinorityOwned | Data: Boolean<br>Description: Minority owned
IsNativeAmOwned | Data: Boolean<br>Description: Native American owned
IsPreferredSupplier | Data: Boolean<br>Description: Preferred supplier
IsWomanOwned | Data: Boolean<br>Description: Woman owned
LastName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
Linkedin | Data: Text<br>Maximum length: 128
MiddleName | Data: Text<br>Maximum length: 128<br>Description: Type the company or business name.
ParentSupplier | Lookup: Supplier
PartyRole | Enumeration: PartyRoleValues: Alumnus, Company, Constituent, Contractor, Customer, Donor, Employee, Fan, Member, NonProfit, Supplier, Tenant, Vendor, Volunteer
PartyType | Enumeration: PartyTypeValues: Group, Organization, Person
PostalAddress | Data: Address
SatoriID | Data: Text<br>Maximum length: 128
StockExchange | Data: Text<br>Maximum length: 128
SupplierId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Thumbnail | Data: Image
Ticker | Data: Text<br>Maximum length: 128
Twitter | Data: Text<br>Maximum length: 128
Website | Data: WebsiteUrl
## SupplierInvoice (Supplier Invoice) Entity
An invoice that is received from a supplier.

Field | Description
---|---
BillingAddress | Data: Address
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
DiscountAmountCurrency | Lookup: Currency
DiscountPercent | Data: Number
FreightTerms | Enumeration: FreightTermsValues: FOB, NoCharge
OrderDate | Data: DateTime<br>Required, Unique<br>Description: Invoice Date
PaymentTerms | Enumeration: PaymentTermsValues: Net30, Net45, Net60, TwoPercent10Net30
PurchaseOrder | Lookup: PurchaseOrder<br>Required, Unique
PurchasePerson | Lookup: Employee
ShippingAddress | Data: Address
ShippingMethod | Enumeration: ShippingMethodValues: AirBorne, DHL, Fedex, PostalMail, UPS
Status | Enumeration: InvoiceStatusValues: Cancelled, Created, Hold, Paid<br>Description: Invoice Status
Supplier | Lookup: Supplier<br>Required
SupplierContact | Lookup: Supplier
SupplierInvoiceId<br>Primary key | Number sequence: <br>Unique
TotalAmount | Data: Currency<br>Decimal places: 6
TotalAmountCurrency | Lookup: Currency
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Charges
TotalChargeAmountCurrency | Lookup: Currency
TotalDiscountAmount | Data: Currency<br>Decimal places: 6
TotalDiscountAmountCurrency | Lookup: Currency
TotalDiscountPercent | Data: Number
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Taxes
TotalTaxAmountCurrency | Lookup: Currency
## SupplierInvoiceCharge (Supplier Invoice Charges) Entity
A charge that is part of a supplier invoice.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Charges
AmountCurrency | Lookup: Currency
ChargeType | Enumeration: InvoiceChargeTypeValues: Freight, Insurance, Others
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge Name
SupplierInvoice | Lookup: SupplierInvoice<br>Required
SupplierInvoiceChargeId<br>Primary key | Number sequence: <br>Unique
## SupplierInvoiceLine (Supplier Invoice Lines) Entity
A line item on a supplier invoice.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 255
DiscountAmount | Data: Currency<br>Decimal places: 6
DiscountAmountCurrency | Lookup: Currency
DiscountPercent | Data: Number
LineAmount | Data: Currency<br>Decimal places: 6
LineAmountCurrency | Lookup: Currency
Name | Data: Text<br>Maximum length: 60
Product | Lookup: Products
ProductName | Data: Text<br>Maximum length: 60
ProductUnitOfMeasure | Lookup: Units
Quantity | Data: Number
Sequence | Data: Integer
Status | Enumeration: OrderLineStatusValues: Active, Confirmed, Invoice, PackingSlip, Quote<br>Description: Invoice Line Status
SupplierInvoiceLine | Lookup: SupplierInvoice<br>Required
SupplierInvoiceLineId<br>Primary key | Number sequence: <br>Unique<br>Description: Supplier Invoice Line Number
SupplierProductName | Data: Text<br>Maximum length: 60
SupplierProductUnitOfMeasure | Lookup: Units
TotalChargeAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Charge
TotalChargesCurrency | Lookup: Currency
TotalTaxAmount | Data: Currency<br>Decimal places: 6<br>Description: Total Tax
TotalTaxesCurrency | Lookup: Currency
UnitPrice | Data: Currency<br>Decimal places: 6
UnitPriceCurrency | Lookup: Currency
## SupplierInvoiceLineCharge (Supplier Invoice Line Charge) Entity
A supplier invoice line item charge.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Line Charges
AmountCurrency | Lookup: Currency
ChargeType | Enumeration: InvoiceLineChargeTypeValues: Freight, Insurance, Others
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Charge Name
SupplierInvoiceLine | Lookup: SupplierInvoiceLine<br>Required
SupplierInvoiceLineChargeId<br>Primary key | Number sequence: <br>Unique
## SupplierInvoiceLineTax (Supplier Invoice Line Tax) Entity
The supplier invoice line item tax.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Invoice Line Taxes
AmountCurrency | Lookup: Currency
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax Name
RateCode | Data: Text<br>Maximum length: 60
SupplierInvoiceLine | Lookup: SupplierInvoiceLine<br>Required
SupplierInvoiceLineTaxId<br>Primary key | Number sequence: <br>Unique<br>Description: Sales Invoice Line Tax Id
TaxType | Enumeration: InvoiceLineTaxTypeValues: Others, SalesTax, VAT
## SupplierInvoiceTax (Supplier Invoice Tax) Entity
The tax on a supplier invoice.

Field | Description
---|---
Amount | Data: Currency<br>Required, Decimal places: 6<br>Description: Total Taxes
AmountCurrency | Lookup: Currency
Description | Data: Text<br>Maximum length: 60
Name | Data: Text<br>Maximum length: 60<br>Description: Tax Name
RateCode | Data: Text<br>Maximum length: 60
SupplierInvoice | Lookup: SupplierInvoice<br>Required
SupplierInvoiceTaxId<br>Primary key | Number sequence: <br>Unique
TaxType | Enumeration: InvoiceTaxTypeValues: Others, SalesTax, VAT
