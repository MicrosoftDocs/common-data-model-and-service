---
title: "Project reference | Microsoft Docs"
description: ""
author: "robinarh"
manager: "robinarh"
ms.date: "11/07/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: ""
---

# Project reference 

[!INCLUDE [](../../includes/new-version.md)]

## Project (Project) Entity 
Project 

Field | Description
---|---
Account | Lookup: Account
ActualCost | Data: Currency<br>Decimal places: 6
ActualEffortHours | Data: BigInteger
ActualEndDate | Data: DateTime
ActualStartDate | Data: DateTime
Address | Data: Address
BusinessUnit | Lookup: BusinessUnit
CompletionEffortHours | Data: Number
CurrencyCode | Picklist: CurrencyCode<br>Values: AED, AFN, ALL, AMD, ANG, AOA, ARS, AUD, AWG, AZN, BAM, BBD, BDT, BGN, BHD, BIF, BMD, BND, BOB, BOV, BRL, BSD, BTN, BWP, BYN, BYR, BZD, CAD, CDF, CHE, CHF, CHW, CLF, CLP, CNY, COP, COU, CRC, CUC, CUP, CVE, CZK, DJF, DKK, DOP, DZD, EGP, ERN, ETB, EUR, FJD, FKP, GBP, GEL, GHS, GIP, GMD, GNF, GTQ, GYD, HKD, HNL, HRK, HTG, HUF, IDR, ILS, INR, IQD, IRR, ISK, JMD, JOD, JPY, KES, KGS, KHR, KMF, KPW, KRW, KWD, KYD, KZT, LAK, LBP, LKR, LRD, LSL, LYD, MAD, MDL, MGA, MKD, MMK, MNT, MOP, MRO, MUR, MVR, MWK, MXN, MXV, MYR, MZN, NAD, NGN, NIO, NOK, NPR, NZD, OMR, PAB, PEN, PGK, PHP, PKR, PLN, PYG, QAR, RON, RSD, RUB, RWF, SAR, SBD, SCR, SDG, SEK, SGD, SHP, SLL, SOS, SRD, SSP, STD, SVC, SYP, SZL, THB, TJS, TMT, TND, TOP, TRY, TTD, TWD, TZS, UAH, UGX, USD, USN, UYI, UYU, UZS, VEF, VND, VUV, WST, XAF, XAG, XAU, XBA, XBB, XBC, XBD, XCD, XDR, XOF, XPD, XPF, XPT, XSU, XTS, XUA, XXX, YER, ZAR, ZMW, ZWL
Description | Data: Text<br>Maximum length: 2048
Manager | Lookup: Worker
Name | Data: Text<br>Required, Maximum length: 2048
Organization | Lookup: Organization
ParentProject | Lookup: Project
PlannedCost | Data: Currency<br>Decimal places: 6
PlannedEffortHours | Data: BigInteger
PlannedEndDate | Data: DateTime
PlannedStartDate | Data: DateTime
ProjectContract | Lookup: ProjectContract
ProjectId<br>Primary key | Number sequence: <br>Unique, Searchable
RemainingEffortHours | Data: Number
Source | Picklist: Source<br>Values: Attract, CustomerEngagement, Default, Finance, Gauge, Greenhouse, iCIMS, LinkedIn, Onboarding, Operations, Talent
Status | Picklist: ProjectStatus<br>Values: Active, Created, Estimated, Finished, Inactive, Scheduled<br>Required
Type | Picklist: ProjectType<br>Values: CostProject, FixedPrice, Internal, Investment, NotSpecified, TimeAndMaterials, TimeProject<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Project|Parent project|OneToMany|Association
ProjectContract|Project contract|OneToMany|Association
Account|Account|OneToMany|Association
Worker|Manager|OneToMany|Association
Organization|Organization|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|ProjectId<br>Name
DefaultCreate|DefaultCreate field group|ProjectId<br>Name<br>Manager<br>Account<br>PlannedStartDate<br>Description
DefaultDetails|DefaultDetails field group|ProjectId<br>Name<br>Manager<br>Account<br>PlannedStartDate<br>Description
DefaultIdentification|DefaultIdentification field group|ProjectId<br>Name
DefaultList|DefaultList field group|ProjectId<br>Name<br>Manager<br>Account<br>PlannedStartDate
DefaultLookup|DefaultLookup field group|ProjectId<br>Name
DefaultReport|DefaultReport field group|ProjectId<br>Name<br>Manager<br>Account<br>PlannedStartDate<br>Description

## ProjectContract (Project contract) Entity 
Project contract 

Field | Description
---|---
Account | Lookup: Account
AccountManager | Lookup: Worker
BillingAddress | Data: Address
BusinessUnit | Lookup: BusinessUnit
CurrencyCode | Picklist: CurrencyCode<br>Values: AED, AFN, ALL, AMD, ANG, AOA, ARS, AUD, AWG, AZN, BAM, BBD, BDT, BGN, BHD, BIF, BMD, BND, BOB, BOV, BRL, BSD, BTN, BWP, BYN, BYR, BZD, CAD, CDF, CHE, CHF, CHW, CLF, CLP, CNY, COP, COU, CRC, CUC, CUP, CVE, CZK, DJF, DKK, DOP, DZD, EGP, ERN, ETB, EUR, FJD, FKP, GBP, GEL, GHS, GIP, GMD, GNF, GTQ, GYD, HKD, HNL, HRK, HTG, HUF, IDR, ILS, INR, IQD, IRR, ISK, JMD, JOD, JPY, KES, KGS, KHR, KMF, KPW, KRW, KWD, KYD, KZT, LAK, LBP, LKR, LRD, LSL, LYD, MAD, MDL, MGA, MKD, MMK, MNT, MOP, MRO, MUR, MVR, MWK, MXN, MXV, MYR, MZN, NAD, NGN, NIO, NOK, NPR, NZD, OMR, PAB, PEN, PGK, PHP, PKR, PLN, PYG, QAR, RON, RSD, RUB, RWF, SAR, SBD, SCR, SDG, SEK, SGD, SHP, SLL, SOS, SRD, SSP, STD, SVC, SYP, SZL, THB, TJS, TMT, TND, TOP, TRY, TTD, TWD, TZS, UAH, UGX, USD, USN, UYI, UYU, UZS, VEF, VND, VUV, WST, XAF, XAG, XAU, XBA, XBB, XBC, XBD, XCD, XDR, XOF, XPD, XPF, XPT, XSU, XTS, XUA, XXX, YER, ZAR, ZMW, ZWL
Description | Data: Text<br>Maximum length: 2048
EffectiveDate | Data: DateTime
EstimatedCompletionDate | Data: DateTime
FixedExchangeRate | Data: Number
IsExternal | Data: Boolean<br>Required
Name | Data: Text<br>Required, Maximum length: 2048
Opportunity | Lookup: Opportunity
OrderType | Picklist: ProjectOrderType<br>Values: ItemBased, WorkBased
Organization | Lookup: Organization
PaymentTerms | Picklist: PaymentTerms<br>Values: Net30, Net45, Net60, TwoPercent10Net30
ProjectContractId<br>Primary key | Number sequence: <br>Unique, Searchable
Quotation | Lookup: Quotation
Reference | Data: Text<br>Maximum length: 2048
RequestedCompletionDate | Data: DateTime
Source | Picklist: Source<br>Values: Attract, CustomerEngagement, Default, Finance, Gauge, Greenhouse, iCIMS, LinkedIn, Onboarding, Operations, Talent
Status | Picklist: ProjectContractStatus<br>Values: Active, Inactive<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Quotation|Quotation|OneToMany|Association
Opportunity|Opportunity|OneToMany|Association
Worker|Account manager|OneToMany|Association
Account|Account|OneToMany|Association
Organization|Organization|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|ProjectContractId<br>Name<br>Account
DefaultCreate|DefaultCreate field group|ProjectContractId<br>Name<br>Account<br>Status<br>AccountManager<br>Description
DefaultDetails|DefaultDetails field group|ProjectContractId<br>Name<br>Account<br>Status<br>AccountManager<br>Description
DefaultIdentification|DefaultIdentification field group|ProjectContractId<br>Name
DefaultList|DefaultList field group|ProjectContractId<br>Name<br>Account<br>Status<br>AccountManager
DefaultLookup|DefaultLookup field group|ProjectContractId<br>Name
DefaultReport|DefaultReport field group|ProjectContractId<br>Name<br>Account<br>Status<br>AccountManager<br>Description

## ProjectContractLine (Project contract line) Entity 
Project contract line 

Field | Description
---|---
BillingMethod | Picklist: ProjectBillingMethod<br>Values: FixedPrice, TimeAndMaterials
BillingStartDate | Data: DateTime
BillingType | Picklist: ProjectBillingType<br>Values: Chargeable, Compliementary, NonChargeable, NotAvailable, NotSpecified
BudgetAmount | Data: Currency<br>Decimal places: 6
BusinessUnit | Lookup: BusinessUnit
Description | Data: Text<br>Maximum length: 2048
FixedExchangeRate | Data: Number
InvoiceFrequency | Picklist: ProjectInvoiceFrequency<br>Values: Biweekly, Monthly, Weekly
IsExpenseIncluded | Data: Boolean
IsFeeIncluded | Data: Boolean
IsMaterialIncluded | Data: Boolean
IsTimeIncluded | Data: Boolean
LineAmount | Data: Currency<br>Decimal places: 6
OrderLineType | Picklist: ProjectOrderLineType<br>Values: FieldServiceLine, ProjectServiceLine
Product | Lookup: Product
Project | Lookup: Project
ProjectContract<br>Primary key | Lookup: ProjectContract<br>Required
Quantity | Data: Number
QuotationLine | Lookup: QuotationLine
Sequence | Data: Integer<br>Required
Source | Picklist: Source<br>Values: Attract, CustomerEngagement, Default, Finance, Gauge, Greenhouse, iCIMS, LinkedIn, Onboarding, Operations, Talent
Status | Picklist: ProjectContractLineStatus<br>Values: Active, Cancelled, Invoiced<br>Required
TotalCostAmount | Data: Currency<br>Decimal places: 6
TotalTaxAmount | Data: Currency<br>Decimal places: 6
Type | Picklist: ProjectTransactionType<br>Values: Additional, Commission, Expense, Fee, Material, Milestone, Tax, Time<br>Required
UnitCost | Data: Currency<br>Decimal places: 6
UnitPrice | Data: Currency<br>Decimal places: 6
Vendor | Lookup: Vendor

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Vendor|Vendor|OneToMany|Association
Product|Product|OneToMany|Association
QuotationLine|Quotation line|OneToMany|Association
Project|Project|OneToMany|Association
ProjectContract|Project contract|OneToMany|Association
BusinessUnit|Business unit|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|ProjectContract<br>Sequence<br>Type
DefaultCreate|DefaultCreate field group|ProjectContract<br>Sequence<br>Description<br>Type<br>LineAmount
DefaultDetails|DefaultDetails field group|ProjectContract<br>Sequence<br>Description<br>Type<br>LineAmount
DefaultIdentification|DefaultIdentification field group|ProjectContract<br>Sequence
DefaultList|DefaultList field group|ProjectContract<br>Sequence<br>Type<br>LineAmount
DefaultLookup|DefaultLookup field group|ProjectContract<br>Sequence<br>Type
DefaultReport|DefaultReport field group|ProjectContract<br>Sequence<br>Description<br>Type<br>LineAmount

