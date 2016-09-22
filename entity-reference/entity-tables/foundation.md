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

# Foundation
## AddressCountryRegion (Country Region) Entity
Country Region

Field | Description
---|---
CountryId<br>Primary key | Data: Text<br>Required, Unique, Maximum length: 10
DefaultTimeZone | Enumeration: TimezoneValues: GMT_CASABLANCA, GMT_CASABLANCA_MONTROVIA_REYKJAVIK, GMT_COORDINATEDUNIVERSALTIME, GMT_DUBLIN_EDINBURGH_LISBON_LONDON, GMT_PLUS0300KALININGRAD_MINSK, GMTMINUS0100AZORES, GMTMINUS0100CAPEVERDIS, GMTMINUS0200MIDATLANTIC, GMTMINUS0300_SALVADOR, GMTMINUS0300BRASILIA, GMTMINUS0300BUENOSAIRES, GMTMINUS0300BUENOSAIRES_GEORGETOWN, GMTMINUS0300GREENLAND, GMTMINUS0300MONTEVIDEO, GMTMINUS0330NEWFOUNDLAND, GMTMINUS0400ASUNCION, GMTMINUS0400ATLANTICTIME, GMTMINUS0400LAPAZ, GMTMINUS0400MANAUS, GMTMINUS0400SANTIAGO, GMTMINUS0430CARACAS, GMTMINUS0500BOGOTA_LIMA_QUITO_RIOBRANCO, GMTMINUS0500EASTERNTIME, GMTMINUS0500INDIANA, GMTMINUS0600CENTRALAMERICA, GMTMINUS0600CENTRALTIME, GMTMINUS0600GUADALAJARA_MEXICOCITY, GMTMINUS0600SASKATCHEWAN, GMTMINUS0700ARIZONA, GMTMINUS0700CHIHUAHUA_LAPAZ_MAZATLAN, GMTMINUS0700MOUNTAINTIME, GMTMINUS0800PACIFICTIME, GMTMINUS0800TIJUANA_BAJACALIFORNIA, GMTMINUS0900ALASKA, GMTMINUS1000HAWAII, GMTMINUS1100COORDINATEDUNIVERSALTIME, GMTMINUS1100MIDWAYISLAND_SAMOA, GMTMINUS1200INTERNATIONALDATELINEWEST, GMTPLUS0100_AMSTERDAM_BERLIN_BERN_ROME, GMTPLUS0100BELGRADE_BRATISLAVA_BUDAPEST, GMTPLUS0100BRUSSELS_COPENHAGEN_MADRID, GMTPLUS0100SARAJEVO_SKOPJE_WARSAW_ZAGREB, GMTPLUS0100TRIPOLI, GMTPLUS0100WESTCENTRALAFRICA, GMTPLUS0200_DAMASCUS, GMTPLUS0200AMMAN, GMTPLUS0200ATHENS_BUCHAREST_ISTANBUL, GMTPLUS0200BEIRUT, GMTPLUS0200CAIRO, GMTPLUS0200HARARE_PRETORIA, GMTPLUS0200HELSINKI_KYIV_RIGA_VILNIUS, GMTPLUS0200ISTANBUL, GMTPLUS0200JERUSALEM, GMTPLUS0200MINSK, GMTPLUS0200WINDHOEK, GMTPLUS0300BAGHDAD, GMTPLUS0300KUWAIT_RIYADH, GMTPLUS0300MOSCOW_STPETERSBURG_VOLGOGRAD, GMTPLUS0300NAIROBI, GMTPLUS0300TBILISI, GMTPLUS0330TEHRAN, GMTPLUS0400ABUDHABI_MUSCAT, GMTPLUS0400BAKU, GMTPLUS0400CAUCASUSSTANDARDTIME, GMTPLUS0400IZHEVSK_SAMARA, GMTPLUS0400PORTLOUIS, GMTPLUS0400YEREVAN, GMTPLUS0430KABUL, GMTPLUS0500EKATERINBURG, GMTPLUS0500ISLAMABAD_KARACHI, GMTPLUS0500ISLAMABAD_KARACHI_TASHKENT, GMTPLUS0530CHENNAI_KOLKATA_MUMBAI, GMTPLUS0530SRIJAYAWARDENEPURA, GMTPLUS0545KATHMANDU, GMTPLUS0600ALMATY_NOVOSIBIRSK, GMTPLUS0600ASTANA_DHAKA, GMTPLUS0600DHAKA, GMTPLUS0600MAGADAN, GMTPLUS0630_YANGON, GMTPLUS0700_BANGKOK_HANOI_JAKARTA, GMTPLUS0700KRASNOYARSK, GMTPLUS0800_ULAANBAATAR, GMTPLUS0800BEIJING_CHONGQING_HONGKONG, GMTPLUS0800IRKUTSK_ULAANBATAAR, GMTPLUS0800KUALALUMPUR_SINGAPORE, GMTPLUS0800PERTH, GMTPLUS0800TAIPEI, GMTPLUS0900OSAKA_SAPPORO_TOKYO, GMTPLUS0900SEOUL, GMTPLUS0900YAKUTSK, GMTPLUS0930ADELAIDE, GMTPLUS0930DARWIN, GMTPLUS1000BRISBANE, GMTPLUS1000CANBERRA_MELBOURNE_SYDNEY, GMTPLUS1000GUAM_PORTMORESBY, GMTPLUS1000HOBART, GMTPLUS1000VLADIVOSTOK, GMTPLUS1100CHOKURDAKH, GMTPLUS1100MAGADAN_SOLOMONIS, GMTPLUS1200ANADYR_PETRO_KAMCHATSKY, GMTPLUS1200AUCKLAND_WELLINGTON, GMTPLUS1200COORDINATEDUNIVERSALTIME, GMTPLUS1200FIJI_KAMCHATKA_MARSHALLIS, GMTPLUS1300NUKU_ALOFA
Name | Data: Text<br>Maximum length: 60
ShortName | Data: Text<br>Maximum length: 2
## AddressPostalCodeList (Postal Codes) Entity
A zip code or postal code.

Field | Description
---|---
PostalCode<br>Primary key | Data: Text<br>Required, Maximum length: 10
## AddressStateProvinceList (State List) Entity
A state or province.

Field | Description
---|---
ProvinceId<br>Primary key | Data: Text<br>Required, Maximum length: 10
## BusinessUnit (BusinessUnit) Entity
A division or unit within an organization with a defined business function.

Field | Description
---|---
BusinessPhone | Data: Phone
BusinessUnitId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
CellPhone | Data: Phone
Company | Lookup: Company<br>Required
CostCenter | Lookup: CostCenter
Description | Data: Text<br>Maximum length: 128
Email | Data: Email
Facebook | Data: Text<br>Maximum length: 128
FullName | Data: Text<br>Required, Maximum length: 128
Linkedin | Data: Text<br>Maximum length: 128
ParentBusinessUnit | Lookup: BusinessUnit
PartyRole | Enumeration: PartyRoleValues: Alumnus, Company, Constituent, Contractor, Customer, Donor, Employee, Fan, Member, NonProfit, Supplier, Tenant, Vendor, Volunteer
PostalAddress | Data: Address
Thumbnail | Data: Image
Twitter | Data: Text<br>Maximum length: 128
Website | Data: WebsiteUrl
## CostCenter (Cost Center) Entity
A department within an organization that does not directly add profits to an organization but costs the organization money to operate.

Field | Description
---|---
Company | Lookup: Company
CostCenterId<br>Primary key | Number sequence: <br>Unique<br>Description: Type an ID number or code for the account to quickly search and identify the account in system views.
Description | Data: Text<br>Maximum length: 128
Name | Data: Text<br>Required, Maximum length: 128<br>Description: Type the company or business name.
ParentCostCenter | Lookup: CostCenter
## Currency (Currency) Entity
A currency that can be used for foreign exchange.

Field | Description
---|---
CurrencyCode<br>Primary key | Data: Text<br>Required, Unique, Maximum length: 3
Description | Data: Text<br>Maximum length: 60
Symbol | Data: Text<br>Maximum length: 5
## ProductCategory (Product Category) Entity
A product category.

Field | Description
---|---
CategoryId<br>Primary key | Number sequence: <br>Unique
Description | Data: MultilineText
Name | Data: Text<br>Required, Maximum length: 60<br>Description: Category Name
## Products (Product) Entity
A product with description and price.

Field | Description
---|---
DefaultBuyingUnitOfMeasure | Lookup: Units
DefaultSellingQuantity | Data: Number
DefaultSellingUnitOfMeasure | Lookup: Units
DefaultStockingUnitOfMeasure | Lookup: Units
Description | Data: Text<br>Maximum length: 255
ProductCategory | Lookup: ProductCategory
ProductImage | Data: Image
ProductName | Data: Text<br>Required, Maximum length: 60
ProductNumber<br>Primary key | Number sequence: <br>Unique<br>Description: Product ID
ProductType | Enumeration: ProductTypeValues: Item, Service
SellingUnitPrice | Data: Currency<br>Decimal places: 6
SellingUnitPriceCurrency | Lookup: Currency
StandardCostAmount | Data: Number
Status | Enumeration: ProductStatusValues: Active, InActive
## UnitConversion (Unit of Measure Conversions) Entity
The formula and reciprocal formula for converting one unit of measure to another.

Field | Description
---|---
Factor | Data: Number<br>Required
FromUnit | Lookup: Units<br>Required
Markup | Data: Number<br>Required
Rounding | Enumeration: ConversionRoundingValues: Down, Nearest, Up
ToUnit | Lookup: Units<br>Required
UnitConversionId<br>Primary key | Number sequence: <br>Unique
## Units (Unit of Measure) Entity
A division of quantity accepted as a standard of measurement or exchange.

Field | Description
---|---
Description | Data: Text<br>Maximum length: 60
Symbol | Data: Text<br>Maximum length: 10
UnitId<br>Primary key | Data: Text<br>Required, Unique, Maximum length: 5
