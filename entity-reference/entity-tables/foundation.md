---
title: "Foundation reference"
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
ms.assetid: "c06c0de3-404b-4b44-9d58-6f63760f2a24"
---

# Foundation
## AddressCountryRegion (@Foundation.CountryRegion) Entity 
@Foundation.CountryRegion 

Field | Description
---|---
CountryId<br>Primary key | Data: Text<br>Required, Unique, Maximum length: 10<br>Description: Country/region
DefaultTimeZone | Enumeration: Timezone<br>Values: GMT_CASABLANCA, GMT_CASABLANCA_MONTROVIA_REYKJAVIK, GMT_COORDINATEDUNIVERSALTIME, GMT_DUBLIN_EDINBURGH_LISBON_LONDON, GMT_PLUS0300KALININGRAD_MINSK, GMTMINUS0100AZORES, GMTMINUS0100CAPEVERDIS, GMTMINUS0200MIDATLANTIC, GMTMINUS0300_SALVADOR, GMTMINUS0300BRASILIA, GMTMINUS0300BUENOSAIRES, GMTMINUS0300BUENOSAIRES_GEORGETOWN, GMTMINUS0300GREENLAND, GMTMINUS0300MONTEVIDEO, GMTMINUS0330NEWFOUNDLAND, GMTMINUS0400ASUNCION, GMTMINUS0400ATLANTICTIME, GMTMINUS0400LAPAZ, GMTMINUS0400MANAUS, GMTMINUS0400SANTIAGO, GMTMINUS0430CARACAS, GMTMINUS0500BOGOTA_LIMA_QUITO_RIOBRANCO, GMTMINUS0500EASTERNTIME, GMTMINUS0500INDIANA, GMTMINUS0600CENTRALAMERICA, GMTMINUS0600CENTRALTIME, GMTMINUS0600GUADALAJARA_MEXICOCITY, GMTMINUS0600SASKATCHEWAN, GMTMINUS0700ARIZONA, GMTMINUS0700CHIHUAHUA_LAPAZ_MAZATLAN, GMTMINUS0700MOUNTAINTIME, GMTMINUS0800PACIFICTIME, GMTMINUS0800TIJUANA_BAJACALIFORNIA, GMTMINUS0900ALASKA, GMTMINUS1000HAWAII, GMTMINUS1100COORDINATEDUNIVERSALTIME, GMTMINUS1100MIDWAYISLAND_SAMOA, GMTMINUS1200INTERNATIONALDATELINEWEST, GMTPLUS0100_AMSTERDAM_BERLIN_BERN_ROME, GMTPLUS0100BELGRADE_BRATISLAVA_BUDAPEST, GMTPLUS0100BRUSSELS_COPENHAGEN_MADRID, GMTPLUS0100SARAJEVO_SKOPJE_WARSAW_ZAGREB, GMTPLUS0100TRIPOLI, GMTPLUS0100WESTCENTRALAFRICA, GMTPLUS0200_DAMASCUS, GMTPLUS0200AMMAN, GMTPLUS0200ATHENS_BUCHAREST_ISTANBUL, GMTPLUS0200BEIRUT, GMTPLUS0200CAIRO, GMTPLUS0200HARARE_PRETORIA, GMTPLUS0200HELSINKI_KYIV_RIGA_VILNIUS, GMTPLUS0200ISTANBUL, GMTPLUS0200JERUSALEM, GMTPLUS0200MINSK, GMTPLUS0200WINDHOEK, GMTPLUS0300BAGHDAD, GMTPLUS0300KUWAIT_RIYADH, GMTPLUS0300MOSCOW_STPETERSBURG_VOLGOGRAD, GMTPLUS0300NAIROBI, GMTPLUS0300TBILISI, GMTPLUS0330TEHRAN, GMTPLUS0400ABUDHABI_MUSCAT, GMTPLUS0400BAKU, GMTPLUS0400CAUCASUSSTANDARDTIME, GMTPLUS0400IZHEVSK_SAMARA, GMTPLUS0400PORTLOUIS, GMTPLUS0400YEREVAN, GMTPLUS0430KABUL, GMTPLUS0500EKATERINBURG, GMTPLUS0500ISLAMABAD_KARACHI, GMTPLUS0500ISLAMABAD_KARACHI_TASHKENT, GMTPLUS0530CHENNAI_KOLKATA_MUMBAI, GMTPLUS0530SRIJAYAWARDENEPURA, GMTPLUS0545KATHMANDU, GMTPLUS0600ALMATY_NOVOSIBIRSK, GMTPLUS0600ASTANA_DHAKA, GMTPLUS0600DHAKA, GMTPLUS0600MAGADAN, GMTPLUS0630_YANGON, GMTPLUS0700_BANGKOK_HANOI_JAKARTA, GMTPLUS0700KRASNOYARSK, GMTPLUS0800_ULAANBAATAR, GMTPLUS0800BEIJING_CHONGQING_HONGKONG, GMTPLUS0800IRKUTSK_ULAANBATAAR, GMTPLUS0800KUALALUMPUR_SINGAPORE, GMTPLUS0800PERTH, GMTPLUS0800TAIPEI, GMTPLUS0900OSAKA_SAPPORO_TOKYO, GMTPLUS0900SEOUL, GMTPLUS0900YAKUTSK, GMTPLUS0930ADELAIDE, GMTPLUS0930DARWIN, GMTPLUS1000BRISBANE, GMTPLUS1000CANBERRA_MELBOURNE_SYDNEY, GMTPLUS1000GUAM_PORTMORESBY, GMTPLUS1000HOBART, GMTPLUS1000VLADIVOSTOK, GMTPLUS1100CHOKURDAKH, GMTPLUS1100MAGADAN_SOLOMONIS, GMTPLUS1200ANADYR_PETRO_KAMCHATSKY, GMTPLUS1200AUCKLAND_WELLINGTON, GMTPLUS1200COORDINATEDUNIVERSALTIME, GMTPLUS1200FIJI_KAMCHATKA_MARSHALLIS, GMTPLUS1300NUKU_ALOFA
Name | Data: Text<br>Maximum length: 60
ShortName | Data: Text<br>Maximum length: 2

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|
DefaultList|Auto generated DefaultList field group|
DefaultCard|Auto generated DefaultCard field group|
DefaultDetails|Auto generated DefaultDetails field group|
DefaultLookup|Auto generated DefaultLookup field group|
DefaultReport|Auto generated DefaultReport field group|
DefaultIdentification|Auto generated DefaultIdentification field group|
## AddressPostalCode (@Foundation.PostalCodes) Entity 
@Foundation.PostalCodes 

Field | Description
---|---
City | Data: Text<br>Required, Maximum length: 60
Country<br>Primary key | Lookup: AddressCountryRegion<br>Required
Description | Data: Text<br>Maximum length: 60
PostalCode | Data: Text<br>Required, Maximum length: 10<br>Description: Zipcode
State | Lookup: AddressStateProvince<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|
DefaultList|Auto generated DefaultList field group|
DefaultCard|Auto generated DefaultCard field group|
DefaultDetails|Auto generated DefaultDetails field group|
DefaultLookup|Auto generated DefaultLookup field group|
DefaultReport|Auto generated DefaultReport field group|
DefaultIdentification|Auto generated DefaultIdentification field group|
## AddressPostalCodeList (@Foundation.PostalCodes) Entity 
A zip code or postal code. 

Field | Description
---|---
PostalCode<br>Primary key | Data: Text<br>Required, Maximum length: 10<br>Description: Zipcode

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|
DefaultList|Auto generated DefaultList field group|
DefaultCard|Auto generated DefaultCard field group|
DefaultDetails|Auto generated DefaultDetails field group|
DefaultLookup|Auto generated DefaultLookup field group|
DefaultReport|Auto generated DefaultReport field group|
DefaultIdentification|Auto generated DefaultIdentification field group|
## AddressStateProvince (@Foundation.States) Entity 
@Foundation.States 

Field | Description
---|---
Country<br>Primary key | Lookup: AddressCountryRegion<br>Required
DefaultTimeZone | Enumeration: Timezone<br>Values: GMT_CASABLANCA, GMT_CASABLANCA_MONTROVIA_REYKJAVIK, GMT_COORDINATEDUNIVERSALTIME, GMT_DUBLIN_EDINBURGH_LISBON_LONDON, GMT_PLUS0300KALININGRAD_MINSK, GMTMINUS0100AZORES, GMTMINUS0100CAPEVERDIS, GMTMINUS0200MIDATLANTIC, GMTMINUS0300_SALVADOR, GMTMINUS0300BRASILIA, GMTMINUS0300BUENOSAIRES, GMTMINUS0300BUENOSAIRES_GEORGETOWN, GMTMINUS0300GREENLAND, GMTMINUS0300MONTEVIDEO, GMTMINUS0330NEWFOUNDLAND, GMTMINUS0400ASUNCION, GMTMINUS0400ATLANTICTIME, GMTMINUS0400LAPAZ, GMTMINUS0400MANAUS, GMTMINUS0400SANTIAGO, GMTMINUS0430CARACAS, GMTMINUS0500BOGOTA_LIMA_QUITO_RIOBRANCO, GMTMINUS0500EASTERNTIME, GMTMINUS0500INDIANA, GMTMINUS0600CENTRALAMERICA, GMTMINUS0600CENTRALTIME, GMTMINUS0600GUADALAJARA_MEXICOCITY, GMTMINUS0600SASKATCHEWAN, GMTMINUS0700ARIZONA, GMTMINUS0700CHIHUAHUA_LAPAZ_MAZATLAN, GMTMINUS0700MOUNTAINTIME, GMTMINUS0800PACIFICTIME, GMTMINUS0800TIJUANA_BAJACALIFORNIA, GMTMINUS0900ALASKA, GMTMINUS1000HAWAII, GMTMINUS1100COORDINATEDUNIVERSALTIME, GMTMINUS1100MIDWAYISLAND_SAMOA, GMTMINUS1200INTERNATIONALDATELINEWEST, GMTPLUS0100_AMSTERDAM_BERLIN_BERN_ROME, GMTPLUS0100BELGRADE_BRATISLAVA_BUDAPEST, GMTPLUS0100BRUSSELS_COPENHAGEN_MADRID, GMTPLUS0100SARAJEVO_SKOPJE_WARSAW_ZAGREB, GMTPLUS0100TRIPOLI, GMTPLUS0100WESTCENTRALAFRICA, GMTPLUS0200_DAMASCUS, GMTPLUS0200AMMAN, GMTPLUS0200ATHENS_BUCHAREST_ISTANBUL, GMTPLUS0200BEIRUT, GMTPLUS0200CAIRO, GMTPLUS0200HARARE_PRETORIA, GMTPLUS0200HELSINKI_KYIV_RIGA_VILNIUS, GMTPLUS0200ISTANBUL, GMTPLUS0200JERUSALEM, GMTPLUS0200MINSK, GMTPLUS0200WINDHOEK, GMTPLUS0300BAGHDAD, GMTPLUS0300KUWAIT_RIYADH, GMTPLUS0300MOSCOW_STPETERSBURG_VOLGOGRAD, GMTPLUS0300NAIROBI, GMTPLUS0300TBILISI, GMTPLUS0330TEHRAN, GMTPLUS0400ABUDHABI_MUSCAT, GMTPLUS0400BAKU, GMTPLUS0400CAUCASUSSTANDARDTIME, GMTPLUS0400IZHEVSK_SAMARA, GMTPLUS0400PORTLOUIS, GMTPLUS0400YEREVAN, GMTPLUS0430KABUL, GMTPLUS0500EKATERINBURG, GMTPLUS0500ISLAMABAD_KARACHI, GMTPLUS0500ISLAMABAD_KARACHI_TASHKENT, GMTPLUS0530CHENNAI_KOLKATA_MUMBAI, GMTPLUS0530SRIJAYAWARDENEPURA, GMTPLUS0545KATHMANDU, GMTPLUS0600ALMATY_NOVOSIBIRSK, GMTPLUS0600ASTANA_DHAKA, GMTPLUS0600DHAKA, GMTPLUS0600MAGADAN, GMTPLUS0630_YANGON, GMTPLUS0700_BANGKOK_HANOI_JAKARTA, GMTPLUS0700KRASNOYARSK, GMTPLUS0800_ULAANBAATAR, GMTPLUS0800BEIJING_CHONGQING_HONGKONG, GMTPLUS0800IRKUTSK_ULAANBATAAR, GMTPLUS0800KUALALUMPUR_SINGAPORE, GMTPLUS0800PERTH, GMTPLUS0800TAIPEI, GMTPLUS0900OSAKA_SAPPORO_TOKYO, GMTPLUS0900SEOUL, GMTPLUS0900YAKUTSK, GMTPLUS0930ADELAIDE, GMTPLUS0930DARWIN, GMTPLUS1000BRISBANE, GMTPLUS1000CANBERRA_MELBOURNE_SYDNEY, GMTPLUS1000GUAM_PORTMORESBY, GMTPLUS1000HOBART, GMTPLUS1000VLADIVOSTOK, GMTPLUS1100CHOKURDAKH, GMTPLUS1100MAGADAN_SOLOMONIS, GMTPLUS1200ANADYR_PETRO_KAMCHATSKY, GMTPLUS1200AUCKLAND_WELLINGTON, GMTPLUS1200COORDINATEDUNIVERSALTIME, GMTPLUS1200FIJI_KAMCHATKA_MARSHALLIS, GMTPLUS1300NUKU_ALOFA<br>Description: Time zone
Name | Data: Text<br>Maximum length: 60
ProvinceId | Data: Text<br>Required, Maximum length: 10<br>Description: State

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|
DefaultList|Auto generated DefaultList field group|
DefaultCard|Auto generated DefaultCard field group|
DefaultDetails|Auto generated DefaultDetails field group|
DefaultLookup|Auto generated DefaultLookup field group|
DefaultReport|Auto generated DefaultReport field group|
DefaultIdentification|Auto generated DefaultIdentification field group|
## AddressStateProvinceList (@Foundation.StateList) Entity 
A state or province. 

Field | Description
---|---
ProvinceId<br>Primary key | Data: Text<br>Required, Maximum length: 10<br>Description: State

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|
DefaultList|Auto generated DefaultList field group|
DefaultCard|Auto generated DefaultCard field group|
DefaultDetails|Auto generated DefaultDetails field group|
DefaultLookup|Auto generated DefaultLookup field group|
DefaultReport|Auto generated DefaultReport field group|
DefaultIdentification|Auto generated DefaultIdentification field group|
## BusinessUnit (@Foundation.BusinessUnit) Entity 
A division or unit within an organization with a defined business function. 

Field | Description
---|---
BusinessUnitId<br>Primary key | Number sequence: <br>Unique<br>Description: Business unit number
CostCenter | Lookup: CostCenter<br>Required
Description | Data: Text<br>Maximum length: 128
EmailAlternate | Data: Email
EmailPrimary | Data: Email
FullName | Data: Text<br>Maximum length: 128
IsDefaultForOrganization | Data: Boolean<br>Required
IsEmailContactAllowed | Data: Boolean<br>Required
IsPhoneContactAllowed | Data: Boolean<br>Required
MailingPostalAddress | Data: Address
OfficeGraphIdentifier | Data: Text<br>Maximum length: 200
Organization | Lookup: Organization<br>Required
OrganizationName | Data: Text<br>Maximum length: 128
OtherPostalAddress | Data: Address
ParentBusinessUnit | Lookup: BusinessUnit
PartyType | Enumeration: PartyType<br>Values: Group, Organization, Person<br>Required
Phone01 | Data: Phone
Phone02 | Data: Phone
Phone03 | Data: Phone
PhonePrimary | Data: Phone
SatoriId | Data: Text<br>Maximum length: 128
ShippingPostalAddress | Data: Address
Source | Enumeration: Source<br>Values: Default<br>Required
Status | Enumeration: BusinessUnitStatus<br>Values: Active, Inactive<br>Required
TaxIdentificationIssuer | Data: Text<br>Maximum length: 128
TaxIdentificationNumber | Data: Text<br>Maximum length: 128
WebsiteURL | Data: Text<br>Maximum length: 255

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit<br>CostCenter<br>MailingPostalAddress<br>PhonePrimary<br>WebsiteURL<br>EmailPrimary
DefaultList|Auto generated DefaultList field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit
DefaultCard|Auto generated DefaultCard field group|FullName<br>OrganizationName<br>ParentBusinessUnit
DefaultDetails|Auto generated DefaultDetails field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit<br>CostCenter<br>MailingPostalAddress<br>PhonePrimary<br>WebsiteURL<br>EmailPrimary
DefaultLookup|Auto generated DefaultLookup field group|BusinessUnitId<br>FullName<br>OrganizationName
DefaultReport|Auto generated DefaultReport field group|BusinessUnitId<br>FullName<br>OrganizationName<br>Description<br>ParentBusinessUnit<br>CostCenter<br>MailingPostalAddress<br>PhonePrimary<br>WebsiteURL<br>EmailPrimary
DefaultIdentification|Auto generated DefaultIdentification field group|BusinessUnitId<br>FullName
## CostCenter (@Foundation.CostCenter) Entity 
A department within an organization that does not directly add profits to an organization but costs the organization money to operate. 

Field | Description
---|---
CostCenterId<br>Primary key | Number sequence: <br>Unique<br>Description: Cost center number
Description | Data: Text<br>Maximum length: 128
Name | Data: Text<br>Required, Maximum length: 128
Organization | Lookup: Organization<br>Required
ParentCostCenter | Lookup: CostCenter

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization<br>Description
DefaultList|Auto generated DefaultList field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization
DefaultCard|Auto generated DefaultCard field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization
DefaultDetails|Auto generated DefaultDetails field group|CostCenterId<br>Name<br>ParentCostCenter<br>Organization<br>Description
DefaultLookup|Auto generated DefaultLookup field group|CostCenterId<br>Name<br>ParentCostCenter
DefaultReport|Auto generated DefaultReport field group|Description<br>CostCenterId<br>Name<br>ParentCostCenter<br>Organization
DefaultIdentification|Auto generated DefaultIdentification field group|CostCenterId<br>Name
## Product (@Foundation.Product) Entity 
@Foundation.Product 

Field | Description
---|---
DefaultBuyingUnitOfMeasure | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard
DefaultSellingQuantity | Data: Quantity
DefaultSellingUnitOfMeasure | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard
DefaultStockingUnitOfMeasure | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard
Description | Data: Text<br>Maximum length: 255
Name | Data: Text<br>Required, Maximum length: 60
ProductCategory | Lookup: ProductCategory<br>Required
ProductId<br>Primary key | Number sequence: <br>Unique
ProductType | Enumeration: ProductType<br>Values: Item, Service<br>Required
SellingUnitPrice | Data: Currency<br>Decimal places: 6
SellingUnitPriceCurrency | Enumeration: CurrencyCode<br>Values: AED, AFN, ALL, AMD, ANG, AOA, ARS, AUD, AWG, AZN, BAM, BBD, BDT, BGN, BHD, BIF, BMD, BND, BOB, BOV, BRL, BSD, BTN, BWP, BYN, BYR, BZD, CAD, CDF, CHE, CHF, CHW, CLF, CLP, CNY, COP, COU, CRC, CUC, CUP, CVE, CZK, DJF, DKK, DOP, DZD, EGP, ERN, ETB, EUR, FJD, FKP, GBP, GEL, GHS, GIP, GMD, GNF, GTQ, GYD, HKD, HNL, HRK, HTG, HUF, IDR, ILS, INR, IQD, IRR, ISK, JMD, JOD, JPY, KES, KGS, KHR, KMF, KPW, KRW, KWD, KYD, KZT, LAK, LBP, LKR, LRD, LSL, LYD, MAD, MDL, MGA, MKD, MMK, MNT, MOP, MRO, MUR, MVR, MWK, MXN, MXV, MYR, MZN, NAD, NGN, NIO, NOK, NPR, NZD, OMR, PAB, PEN, PGK, PHP, PKR, PLN, PYG, QAR, RON, RSD, RUB, RWF, SAR, SBD, SCR, SDG, SEK, SGD, SHP, SLL, SOS, SRD, SSP, STD, SVC, SYP, SZL, THB, TJS, TMT, TND, TOP, TRY, TTD, TWD, TZS, UAH, UGX, USD, USN, UYI, UYU, UZS, VEF, VND, VUV, WST, XAF, XAG, XAU, XBA, XBB, XBC, XBD, XCD, XDR, XOF, XPD, XPF, XPT, XSU, XTS, XUA, XXX, YER, ZAR, ZMW, ZWL<br>Required<br>Description: Selling unit price currency code
StandardCostAmount | Data: Currency<br>Decimal places: 6
StandardCostAmountCurrency | Enumeration: CurrencyCode<br>Values: AED, AFN, ALL, AMD, ANG, AOA, ARS, AUD, AWG, AZN, BAM, BBD, BDT, BGN, BHD, BIF, BMD, BND, BOB, BOV, BRL, BSD, BTN, BWP, BYN, BYR, BZD, CAD, CDF, CHE, CHF, CHW, CLF, CLP, CNY, COP, COU, CRC, CUC, CUP, CVE, CZK, DJF, DKK, DOP, DZD, EGP, ERN, ETB, EUR, FJD, FKP, GBP, GEL, GHS, GIP, GMD, GNF, GTQ, GYD, HKD, HNL, HRK, HTG, HUF, IDR, ILS, INR, IQD, IRR, ISK, JMD, JOD, JPY, KES, KGS, KHR, KMF, KPW, KRW, KWD, KYD, KZT, LAK, LBP, LKR, LRD, LSL, LYD, MAD, MDL, MGA, MKD, MMK, MNT, MOP, MRO, MUR, MVR, MWK, MXN, MXV, MYR, MZN, NAD, NGN, NIO, NOK, NPR, NZD, OMR, PAB, PEN, PGK, PHP, PKR, PLN, PYG, QAR, RON, RSD, RUB, RWF, SAR, SBD, SCR, SDG, SEK, SGD, SHP, SLL, SOS, SRD, SSP, STD, SVC, SYP, SZL, THB, TJS, TMT, TND, TOP, TRY, TTD, TWD, TZS, UAH, UGX, USD, USN, UYI, UYU, UZS, VEF, VND, VUV, WST, XAF, XAG, XAU, XBA, XBB, XBC, XBD, XCD, XDR, XOF, XPD, XPF, XPT, XSU, XTS, XUA, XXX, YER, ZAR, ZMW, ZWL
Status | Enumeration: ProductStatus<br>Values: Active, Inactive<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|ProductId<br>Name<br>ProductType<br>ProductCategory<br>Status<br>Description<br>StandardCostAmount<br>SellingUnitPrice<br>SellingUnitPriceCurrency
DefaultList|Auto generated DefaultList field group|ProductId<br>Name<br>ProductType<br>ProductCategory<br>Status
DefaultCard|Auto generated DefaultCard field group|ProductId<br>Name<br>ProductType<br>Status
DefaultDetails|Auto generated DefaultDetails field group|ProductId<br>Name<br>ProductType<br>ProductCategory<br>Status<br>Description<br>StandardCostAmount<br>SellingUnitPrice<br>SellingUnitPriceCurrency<br>DefaultBuyingUnitOfMeasure<br>DefaultSellingQuantity<br>DefaultSellingUnitOfMeasure<br>DefaultStockingUnitOfMeasure
DefaultLookup|Auto generated DefaultLookup field group|ProductId<br>Name<br>ProductType<br>Status
DefaultReport|Auto generated DefaultReport field group|ProductId<br>Name<br>ProductType<br>ProductCategory<br>Status<br>StandardCostAmount<br>SellingUnitPrice<br>SellingUnitPriceCurrency<br>DefaultBuyingUnitOfMeasure<br>DefaultSellingQuantity<br>DefaultSellingUnitOfMeasure<br>DefaultStockingUnitOfMeasure
DefaultIdentification|Auto generated DefaultIdentification field group|ProductId<br>Name
## ProductCategory (@Foundation.ProductCategory) Entity 
A product category. 

Field | Description
---|---
CategoryId<br>Primary key | Number sequence: <br>Unique
Description | Data: MultilineText
Name | Data: Text<br>Required, Maximum length: 60<br>Description: Category name

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|CategoryId<br>Name<br>Description
DefaultList|Auto generated DefaultList field group|CategoryId<br>Name
DefaultCard|Auto generated DefaultCard field group|CategoryId<br>Name
DefaultDetails|Auto generated DefaultDetails field group|CategoryId<br>Name<br>Description
DefaultLookup|Auto generated DefaultLookup field group|CategoryId<br>Name<br>Description
DefaultReport|Auto generated DefaultReport field group|CategoryId<br>Name<br>Description
DefaultIdentification|Auto generated DefaultIdentification field group|CategoryId<br>Name
## UnitOfMeasureConversion (@Foundation.UnitOfMeasureConversion) Entity 
@Foundation.UnitOfMeasureConversion 

Field | Description
---|---
FromToConversionRate | Data: Number<br>Required
FromUnitOfMeasure<br>Primary key | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard<br>Required
ToFromConversionRate | Data: Number<br>Required
ToUnitOfMeasure | Enumeration: UnitOfMeasure<br>Values: Bag, Box, Bucket, Centilitre, Centimeter, CubicCentimeter, CubicFeet, CubicInch, CubicMeter, CubicMillimeter, CubicYard, Day, Deciliter, DegreesBrix, Dozen, Each, Feet, FluidOunce, Gallon, GigaByte, Gram, HalfCubicInch, HalfInch, HalfPint, HalfPound, HalfSquareInch, Hour, Inch, Keg, Kilogram, Kilometer, KilowattHour, Litre, Meter, Mgpx, Mile, Milligram, Millilitre, Millimeter, Minute, Month, Ohm, OneEighthCubicInch, OneEighthInch, OneEighthSquareInch, Option, Ounce, Pair, Pallet, PascalSecond, Percentage, pHValue, Piece, Pint, Pound, Quart, QuarterCubicInch, QuarterInch, QuarterPound, QuarterSquareInch, Second, SetOfEquipment, SquareCentimeter, SquareFeet, SquareInch, SquareMeter, SquareMile, SquareMillimeter, SquareYard, Ton, Tray, Yard<br>Required

Field group | Description | Fields
---|---|---
DefaultCreate|Auto generated DefaultCreate field group|FromUnitOfMeasure<br>ToUnitOfMeasure<br>FromToConversionRate<br>ToFromConversionRate
DefaultList|Auto generated DefaultList field group|FromUnitOfMeasure<br>ToUnitOfMeasure
DefaultCard|Auto generated DefaultCard field group|FromUnitOfMeasure<br>ToUnitOfMeasure
DefaultDetails|Auto generated DefaultDetails field group|FromUnitOfMeasure<br>ToUnitOfMeasure<br>FromToConversionRate<br>ToFromConversionRate
DefaultLookup|Auto generated DefaultLookup field group|FromUnitOfMeasure<br>ToUnitOfMeasure
DefaultReport|Auto generated DefaultReport field group|FromUnitOfMeasure<br>ToUnitOfMeasure<br>FromToConversionRate<br>ToFromConversionRate
DefaultIdentification|Auto generated DefaultIdentification field group|FromUnitOfMeasure<br>ToUnitOfMeasure
