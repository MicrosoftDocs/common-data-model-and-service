---
title: "Foundation reference | Microsoft Docs"
description: "The foundation entities are used to drive other entities in the Common Data Model."
author: "robinarh"
manager: "robinarh"
ms.date: "05/08/2017"
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
A division or unit within an organization with a defined business function. 

Field | Description
---|---
BusinessUnitId<br>Primary key | Number sequence: <br>Unique, Searchable
CostCenter | Lookup: CostCenter
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email<br>Searchable
FullName | Data: Text<br>Searchable, Maximum length: 128
IsDefaultForOrganization | Data: Boolean<br>Required
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Organization | Lookup: Organization
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
ParentBusinessUnit | Lookup: BusinessUnit<br>Description: Parent business unit ID
PartyType | Picklist: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
Source | Picklist: Source<br>Values: Default<br>Required
Status | Picklist: BusinessUnitStatus<br>Values: Active, Inactive<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
CostCenter|Cost center|OneToMany|Association
Organization|Organization|OneToMany|Association
BusinessUnit|Parent business unit ID|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|OrganizationName<br>Description<br>ParentBusinessUnit<br>CostCenter<br>MailingPostalAddress<br>PhonePrimary<br>WebsiteURL<br>EmailPrimary<br>PartyType<br>Source<br>IsEmailContactAllowed<br>IsPhoneContactAllowed<br>Status<br>IsDefaultForOrganization
DefaultList|DefaultList field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit
DefaultCard|DefaultCard field group|FullName<br>OrganizationName<br>ParentBusinessUnit
DefaultDetails|DefaultDetails field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit<br>CostCenter<br>MailingPostalAddress<br>PhonePrimary<br>WebsiteURL<br>EmailPrimary
DefaultLookup|DefaultLookup field group|BusinessUnitId<br>FullName<br>OrganizationName
DefaultReport|DefaultReport field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit<br>CostCenter<br>MailingPostalAddress<br>PhonePrimary<br>WebsiteURL<br>EmailPrimary
DefaultIdentification|DefaultIdentification field group|BusinessUnitId<br>FullName

## BusinessUnitContact (Business unit contact) Entity 
Associates a business unit and a contact. This entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
BusinessUnit<br>Primary key | Lookup: BusinessUnit<br>Required
Contact | Lookup: Contact<br>Required
DataSource | Picklist: Source<br>Values: Default<br>Required<br>Description: Source
Description | Data: Text<br>Maximum length: 128

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
BusinessUnit|Business unit|OneToMany|Association
Contact|Contact|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|BusinessUnit<br>Contact<br>DataSource<br>Description
DefaultList|DefaultList field group|BusinessUnit<br>Contact<br>DataSource<br>Description
DefaultCard|DefaultCard field group|BusinessUnit<br>Contact<br>DataSource<br>Description
DefaultDetails|DefaultDetails field group|BusinessUnit<br>Contact<br>DataSource<br>Description
DefaultLookup|DefaultLookup field group|BusinessUnit<br>Contact<br>DataSource<br>Description
DefaultReport|DefaultReport field group|BusinessUnit<br>Contact<br>DataSource<br>Description
DefaultIdentification|DefaultIdentification field group|BusinessUnit<br>Contact

## CostCenter (Cost center) Entity 
A department within an organization that does not directly add profits to an organization but costs the organization money to operate. 

Field | Description
---|---
CostCenterId<br>Primary key | Number sequence: <br>Unique, Searchable
Description | Data: Text<br>Maximum length: 128
Name | Data: Text<br>Required, Maximum length: 128
Organization | Lookup: Organization<br>Required
ParentCostCenter | Lookup: CostCenter

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Organization|Organization|OneToMany|Association
CostCenter|Parent cost center|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>ParentCostCenter<br>Organization<br>Description
DefaultList|DefaultList field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization
DefaultCard|DefaultCard field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization
DefaultDetails|DefaultDetails field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization<br>Description
DefaultLookup|DefaultLookup field group|CostCenterId<br>Name<br>ParentCostCenter
DefaultReport|DefaultReport field group|Description<br>CostCenterId<br>Name<br>ParentCostCenter<br>Organization
DefaultIdentification|DefaultIdentification field group|CostCenterId<br>Name

## Department (Department) Entity 
Department 

Field | Description
---|---
DepartmentId<br>Primary key | Number sequence: <br>Unique, Searchable
Description | Data: Text<br>Maximum length: 2048
Name | Data: Text<br>Required, Maximum length: 2048
Organization | Lookup: Organization
ParentDepartment | Lookup: Department

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Department|Parent department|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|DepartmentId<br>Name<br>Organization<br>ParentDepartment
DefaultCreate|DefaultCreate field group|DepartmentId<br>Name<br>Organization<br>ParentDepartment<br>Description
DefaultDetails|DefaultDetails field group|DepartmentId<br>Name<br>Organization<br>ParentDepartment<br>Description
DefaultIdentification|DefaultIdentification field group|DepartmentId<br>Name
DefaultList|DefaultList field group|DepartmentId<br>Name<br>Organization<br>ParentDepartment
DefaultLookup|DefaultLookup field group|DepartmentId<br>Name
DefaultReport|DefaultReport field group|DepartmentId<br>Name<br>Organization<br>ParentDepartment<br>Description

## Product (Product) Entity 
An item that is available for sale. 

Field | Description
---|---
DefaultBuyingUnitOfMeasure | Picklist: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard
DefaultSellingQuantity | Data: Quantity
DefaultStockingUnitOfMeasure | Picklist: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard
Description | Data: Text<br>Maximum length: 255
IsStocked | Data: Boolean
Name | Data: Text<br>Required, Searchable, Maximum length: 60
Organization | Lookup: Organization
ProductCategory | Lookup: ProductCategory
ProductId<br>Primary key | Number sequence: <br>Unique, Searchable
ProductType | Picklist: ProductType<br>Values: Item, Service<br>Required
SellingUnitPrice | Data: Currency<br>Decimal places: 6
StandardCostAmount | Data: Currency<br>Decimal places: 6
Status | Picklist: ProductStatus<br>Values: Active, Inactive<br>Required
UnitOfMeasureScale | Data: Integer

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
ProductCategory|Product category|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

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
A categorization of a product. 

Field | Description
---|---
CategoryId<br>Primary key | Number sequence: <br>Unique, Searchable
Description | Data: MultilineText
Name | Data: Text<br>Required, Maximum length: 60<br>Description: Category name
Organization | Lookup: Organization
ParentProductCategory | Lookup: ProductCategory

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
ProductCategory|Parent product category|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Name<br>Description
DefaultList|DefaultList field group|CategoryId<br>Name
DefaultCard|DefaultCard field group|CategoryId<br>Name
DefaultDetails|DefaultDetails field group|CategoryId<br>Name<br>Description
DefaultLookup|DefaultLookup field group|CategoryId<br>Name<br>Description
DefaultReport|DefaultReport field group|CategoryId<br>Name<br>Description
DefaultIdentification|DefaultIdentification field group|CategoryId<br>Name

## ProductCategoryAssignment (Product category assignment) Entity 
Associates a product and a product category. This entity creates a many-to-many relationship between the two entities. 

Field | Description
---|---
Product<br>Primary key | Lookup: Product<br>Required
ProductCategory | Lookup: ProductCategory<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Product|Product|OneToMany|Association
ProductCategory|Product category|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|Product<br>ProductCategory
DefaultList|DefaultList field group|Product<br>ProductCategory
DefaultCard|DefaultCard field group|Product<br>ProductCategory
DefaultDetails|DefaultDetails field group|Product<br>ProductCategory
DefaultLookup|DefaultLookup field group|Product<br>ProductCategory
DefaultReport|DefaultReport field group|Product<br>ProductCategory
DefaultIdentification|DefaultIdentification field group|Product<br>ProductCategory

## UnitOfMeasureConversion (Unit of measure conversion) Entity 
The linear conversion rate of one unit of measure to another. 

Field | Description
---|---
FromToConversionRate | Data: Number<br>Required
FromUnitOfMeasure<br>Primary key | Picklist: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard<br>Required
ToFromConversionRate | Data: Number<br>Required
ToUnitOfMeasure | Picklist: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard<br>Required

### Relationships

This entity has no relationships.

### Field groups

Field group | Description | Fields
---|---|---
DefaultCreate|DefaultCreate field group|FromUnitOfMeasure<br>ToUnitOfMeasure<br>FromToConversionRate<br>ToFromConversionRate
DefaultList|DefaultList field group|FromUnitOfMeasure<br>ToUnitOfMeasure
DefaultCard|DefaultCard field group|FromUnitOfMeasure<br>ToUnitOfMeasure
DefaultDetails|DefaultDetails field group|FromUnitOfMeasure<br>ToUnitOfMeasure<br>FromToConversionRate<br>ToFromConversionRate
DefaultLookup|DefaultLookup field group|FromUnitOfMeasure<br>ToUnitOfMeasure
DefaultReport|DefaultReport field group|FromUnitOfMeasure<br>ToUnitOfMeasure<br>FromToConversionRate<br>ToFromConversionRate
DefaultIdentification|DefaultIdentification field group|FromUnitOfMeasure<br>ToUnitOfMeasure

## UserOrGroup (User or group) Entity 
User or group 

Field | Description
---|---
DisplayName | Data: Text<br>Required, Maximum length: 255
Email | Data: Text<br>Maximum length: 255
GivenName | Data: Text<br>Maximum length: 255
GraphIdentifier<br>Primary key | Data: Text<br>Required, Unique, Searchable, Maximum length: 36
IsSecurityEnabled | Data: Boolean<br>Required
Surname | Data: Text<br>Maximum length: 255
Type | Picklist: UserOrGroupType<br>Values: Group, ServicePrincipal, User<br>Required

### Relationships

This entity has no relationships.

### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|DisplayName<br>Email
DefaultCreate|DefaultCreate field group|DisplayName<br>Type<br>GivenName<br>Surname<br>Email
DefaultDetails|DefaultDetails field group|DisplayName<br>Type<br>GivenName<br>Surname<br>Email
DefaultIdentification|DefaultIdentification field group|GraphIdentifier
DefaultList|DefaultList field group|DisplayName<br>Type<br>Email
DefaultLookup|DefaultLookup field group|DisplayName<br>Email
DefaultReport|DefaultReport field group|

