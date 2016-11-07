---
title: "Foundation reference | Common Data Model"
description: "The foundation entities are used to drive other entities in the Common Data Model."
author: "robinarh"
manager: "robinarh"
ms.date: "11/03/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "c06c0de3-404b-4b44-9d58-6f63760f2a24"
---

# Foundation reference 
## BusinessUnit (Business unit) Entity 
Entity representing a division or unit within an organization with defined business function 

Field | Description
---|---
BusinessUnitId<br>Primary key | Number sequence: <br>Unique, Searchable
CostCenter | Lookup: CostCenter<br>Required
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FullName | Data: Text<br>Searchable, Maximum length: 128
IsDefaultForOrganization | Data: Boolean<br>Required
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
MailingPostalAddress | Data: Address<br>Description: Mailing postal address line 1
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Organization | Lookup: Organization<br>Required
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address<br>Description: Other postal address line 1
ParentBusinessUnit | Lookup: BusinessUnit
PartyType | Data: Picklist<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address<br>Description: Shipping postal address line 1
Source | Data: Picklist<br>Required
Status | Data: Picklist<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|OrganizationName<br>Description<br>ParentBusinessUnit<br>CostCenter<br>MailingPostalAddress<br>PhonePrimary<br>WebsiteURL<br>EmailPrimary
DefaultList|DefaultList field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit
DefaultCard|DefaultCard field group|FullName<br>OrganizationName<br>ParentBusinessUnit
DefaultDetails|DefaultDetails field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit<br>CostCenter<br>MailingPostalAddress<br>PhonePrimary<br>WebsiteURL<br>EmailPrimary
DefaultLookup|DefaultLookup field group|BusinessUnitId<br>FullName<br>OrganizationName
DefaultReport|DefaultReport field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit<br>CostCenter<br>MailingPostalAddress<br>PhonePrimary<br>WebsiteURL<br>EmailPrimary
DefaultIdentification|DefaultIdentification field group|BusinessUnitId<br>FullName
## CostCenter (Cost center) Entity 
A department within an organization that does not directly add profits to an organization but costs the organization money to operate. 

Field | Description
---|---
CostCenterId<br>Primary key | Number sequence: <br>Unique, Searchable
Description | Data: Text<br>Maximum length: 128
Name | Data: Text<br>Required, Maximum length: 128
Organization | Lookup: Organization<br>Required
ParentCostCenter | Lookup: CostCenter

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>ParentCostCenter<br>Organization<br>Description
DefaultList|DefaultList field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization
DefaultCard|DefaultCard field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization
DefaultDetails|DefaultDetails field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization<br>Description
DefaultLookup|DefaultLookup field group|CostCenterId<br>Name<br>ParentCostCenter
DefaultReport|DefaultReport field group|Description<br>CostCenterId<br>Name<br>ParentCostCenter<br>Organization
DefaultIdentification|DefaultIdentification field group|CostCenterId<br>Name
## Product (Product) Entity 
Product 

Field | Description
---|---
DefaultBuyingUnitOfMeasure | Data: Picklist
DefaultSellingQuantity | Data: Quantity
DefaultStockingUnitOfMeasure | Data: Picklist
Description | Data: Text<br>Maximum length: 255
Name | Data: Text<br>Required, Searchable, Maximum length: 60
ProductCategory | Lookup: ProductCategory<br>Required
ProductId<br>Primary key | Number sequence: <br>Unique, Searchable
ProductType | Data: Picklist<br>Required
SellingUnitPrice | Data: Currency<br>Decimal places: 6
StandardCostAmount | Data: Currency<br>Decimal places: 6
Status | Data: Picklist<br>Required

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>ProductType<br>ProductCategory<br>Status<br>Description<br>StandardCostAmount<br>SellingUnitPrice
DefaultList|DefaultList field group|ProductId<br>Name<br>ProductType<br>ProductCategory<br>Status
DefaultCard|DefaultCard field group|ProductId<br>Name<br>ProductType<br>Status
DefaultDetails|DefaultDetails field group|ProductId<br>Name<br>ProductType<br>ProductCategory<br>Status<br>Description<br>StandardCostAmount<br>SellingUnitPrice<br>DefaultBuyingUnitOfMeasure<br>DefaultSellingQuantity<br>DefaultStockingUnitOfMeasure
DefaultLookup|DefaultLookup field group|ProductId<br>Name<br>ProductType<br>Status
DefaultReport|DefaultReport field group|ProductId<br>Name<br>ProductType<br>ProductCategory<br>Status<br>StandardCostAmount<br>SellingUnitPrice<br>DefaultBuyingUnitOfMeasure<br>DefaultSellingQuantity<br>DefaultStockingUnitOfMeasure
DefaultIdentification|DefaultIdentification field group|ProductId<br>Name
## ProductCategory (Product category) Entity 
A classification of a product. 

Field | Description
---|---
CategoryId<br>Primary key | Number sequence: <br>Unique, Searchable
Description | Data: MultilineText
Name | Data: Text<br>Required, Maximum length: 60<br>Description: Category name

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>Description
DefaultList|DefaultList field group|CategoryId<br>Name
DefaultCard|DefaultCard field group|CategoryId<br>Name
DefaultDetails|DefaultDetails field group|CategoryId<br>Name<br>Description
DefaultLookup|DefaultLookup field group|CategoryId<br>Name<br>Description
DefaultReport|DefaultReport field group|CategoryId<br>Name<br>Description
DefaultIdentification|DefaultIdentification field group|CategoryId<br>Name
## UnitOfMeasureConversion (Unit of measure conversion) Entity 
Unit of measure conversion 

Field | Description
---|---
FromToConversionRate | Data: Number<br>Required
FromUnitOfMeasure<br>Primary key | Data: Picklist<br>Required
ToFromConversionRate | Data: Number<br>Required
ToUnitOfMeasure | Data: Picklist<br>Required

###Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|FromUnitOfMeasure<br>ToUnitOfMeasure<br>FromToConversionRate<br>ToFromConversionRate
DefaultList|DefaultList field group|FromUnitOfMeasure<br>ToUnitOfMeasure
DefaultCard|DefaultCard field group|FromUnitOfMeasure<br>ToUnitOfMeasure
DefaultDetails|DefaultDetails field group|FromUnitOfMeasure<br>ToUnitOfMeasure<br>FromToConversionRate<br>ToFromConversionRate
DefaultLookup|DefaultLookup field group|FromUnitOfMeasure<br>ToUnitOfMeasure
DefaultReport|DefaultReport field group|FromUnitOfMeasure<br>ToUnitOfMeasure<br>FromToConversionRate<br>ToFromConversionRate
DefaultIdentification|DefaultIdentification field group|FromUnitOfMeasure<br>ToUnitOfMeasure
