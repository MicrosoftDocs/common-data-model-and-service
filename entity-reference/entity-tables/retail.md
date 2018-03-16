---
title: "Retail reference | Microsoft Docs"
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

# Retail reference 

[!INCLUDE [](../../includes/new-version-cdm.md)]

## RetailChannel (Retail channel) Entity 
This entity is used to define the variety of channels that retailers use to drive a customer's shopping experience and the transactions that they have with each customer. examples of retail channels include retail stores, online stores, call centers, or mobile app stores. 

Field | Description
---|---
CurrencyCode | Picklist: CurrencyCode<br>Values: AED, AFN, ALL, AMD, ANG, AOA, ARS, AUD, AWG, AZN, BAM, BBD, BDT, BGN, BHD, BIF, BMD, BND, BOB, BOV, BRL, BSD, BTN, BWP, BYN, BYR, BZD, CAD, CDF, CHE, CHF, CHW, CLF, CLP, CNY, COP, COU, CRC, CUC, CUP, CVE, CZK, DJF, DKK, DOP, DZD, EGP, ERN, ETB, EUR, FJD, FKP, GBP, GEL, GHS, GIP, GMD, GNF, GTQ, GYD, HKD, HNL, HRK, HTG, HUF, IDR, ILS, INR, IQD, IRR, ISK, JMD, JOD, JPY, KES, KGS, KHR, KMF, KPW, KRW, KWD, KYD, KZT, LAK, LBP, LKR, LRD, LSL, LYD, MAD, MDL, MGA, MKD, MMK, MNT, MOP, MRO, MUR, MVR, MWK, MXN, MXV, MYR, MZN, NAD, NGN, NIO, NOK, NPR, NZD, OMR, PAB, PEN, PGK, PHP, PKR, PLN, PYG, QAR, RON, RSD, RUB, RWF, SAR, SBD, SCR, SDG, SEK, SGD, SHP, SLL, SOS, SRD, SSP, STD, SVC, SYP, SZL, THB, TJS, TMT, TND, TOP, TRY, TTD, TWD, TZS, UAH, UGX, USD, USN, UYI, UYU, UZS, VEF, VND, VUV, WST, XAF, XAG, XAU, XBA, XBB, XBC, XBD, XCD, XDR, XOF, XPD, XPF, XPT, XSU, XTS, XUA, XXX, YER, ZAR, ZMW, ZWL
Name | Data: Text<br>Maximum length: 128
Organization | Lookup: Organization
RetailChannelId<br>Primary key | Number sequence: <br>Unique, Searchable
TimeZone | Picklist: Timezone<br>Values: GMT_CASABLANCA, GMT_CASABLANCA_MONTROVIA_REYKJAVIK, GMT_COORDINATEDUNIVERSALTIME, GMT_DUBLIN_EDINBURGH_LISBON_LONDON, GMT_PLUS0300KALININGRAD_MINSK, GMTMINUS0100AZORES, GMTMINUS0100CAPEVERDIS, GMTMINUS0200MIDATLANTIC, GMTMINUS0300_SALVADOR, GMTMINUS0300BRASILIA, GMTMINUS0300BUENOSAIRES, GMTMINUS0300BUENOSAIRES_GEORGETOWN, GMTMINUS0300GREENLAND, GMTMINUS0300MONTEVIDEO, GMTMINUS0330NEWFOUNDLAND, GMTMINUS0400ASUNCION, GMTMINUS0400ATLANTICTIME, GMTMINUS0400LAPAZ, GMTMINUS0400MANAUS, GMTMINUS0400SANTIAGO, GMTMINUS0430CARACAS, GMTMINUS0500BOGOTA_LIMA_QUITO_RIOBRANCO, GMTMINUS0500EASTERNTIME, GMTMINUS0500INDIANA, GMTMINUS0600CENTRALAMERICA, GMTMINUS0600CENTRALTIME, GMTMINUS0600GUADALAJARA_MEXICOCITY, GMTMINUS0600SASKATCHEWAN, GMTMINUS0700ARIZONA, GMTMINUS0700CHIHUAHUA_LAPAZ_MAZATLAN, GMTMINUS0700MOUNTAINTIME, GMTMINUS0800PACIFICTIME, GMTMINUS0800TIJUANA_BAJACALIFORNIA, GMTMINUS0900ALASKA, GMTMINUS1000HAWAII, GMTMINUS1100COORDINATEDUNIVERSALTIME, GMTMINUS1100MIDWAYISLAND_SAMOA, GMTMINUS1200INTERNATIONALDATELINEWEST, GMTPLUS0100_AMSTERDAM_BERLIN_BERN_ROME, GMTPLUS0100BELGRADE_BRATISLAVA_BUDAPEST, GMTPLUS0100BRUSSELS_COPENHAGEN_MADRID, GMTPLUS0100SARAJEVO_SKOPJE_WARSAW_ZAGREB, GMTPLUS0100TRIPOLI, GMTPLUS0100WESTCENTRALAFRICA, GMTPLUS0200_DAMASCUS, GMTPLUS0200AMMAN, GMTPLUS0200ATHENS_BUCHAREST_ISTANBUL, GMTPLUS0200BEIRUT, GMTPLUS0200CAIRO, GMTPLUS0200HARARE_PRETORIA, GMTPLUS0200HELSINKI_KYIV_RIGA_VILNIUS, GMTPLUS0200ISTANBUL, GMTPLUS0200JERUSALEM, GMTPLUS0200MINSK, GMTPLUS0200WINDHOEK, GMTPLUS0300BAGHDAD, GMTPLUS0300KUWAIT_RIYADH, GMTPLUS0300MOSCOW_STPETERSBURG_VOLGOGRAD, GMTPLUS0300NAIROBI, GMTPLUS0300TBILISI, GMTPLUS0330TEHRAN, GMTPLUS0400ABUDHABI_MUSCAT, GMTPLUS0400BAKU, GMTPLUS0400CAUCASUSSTANDARDTIME, GMTPLUS0400IZHEVSK_SAMARA, GMTPLUS0400PORTLOUIS, GMTPLUS0400YEREVAN, GMTPLUS0430KABUL, GMTPLUS0500EKATERINBURG, GMTPLUS0500ISLAMABAD_KARACHI, GMTPLUS0500ISLAMABAD_KARACHI_TASHKENT, GMTPLUS0530CHENNAI_KOLKATA_MUMBAI, GMTPLUS0530SRIJAYAWARDENEPURA, GMTPLUS0545KATHMANDU, GMTPLUS0600ALMATY_NOVOSIBIRSK, GMTPLUS0600ASTANA_DHAKA, GMTPLUS0600DHAKA, GMTPLUS0600MAGADAN, GMTPLUS0630_YANGON, GMTPLUS0700_BANGKOK_HANOI_JAKARTA, GMTPLUS0700KRASNOYARSK, GMTPLUS0800_ULAANBAATAR, GMTPLUS0800BEIJING_CHONGQING_HONGKONG, GMTPLUS0800IRKUTSK_ULAANBATAAR, GMTPLUS0800KUALALUMPUR_SINGAPORE, GMTPLUS0800PERTH, GMTPLUS0800TAIPEI, GMTPLUS0900OSAKA_SAPPORO_TOKYO, GMTPLUS0900SEOUL, GMTPLUS0900YAKUTSK, GMTPLUS0930ADELAIDE, GMTPLUS0930DARWIN, GMTPLUS1000BRISBANE, GMTPLUS1000CANBERRA_MELBOURNE_SYDNEY, GMTPLUS1000GUAM_PORTMORESBY, GMTPLUS1000HOBART, GMTPLUS1000VLADIVOSTOK, GMTPLUS1100CHOKURDAKH, GMTPLUS1100MAGADAN_SOLOMONIS, GMTPLUS1200ANADYR_PETRO_KAMCHATSKY, GMTPLUS1200AUCKLAND_WELLINGTON, GMTPLUS1200COORDINATEDUNIVERSALTIME, GMTPLUS1200FIJI_KAMCHATKA_MARSHALLIS, GMTPLUS1300NUKU_ALOFA
Type | Picklist: RetailChannelType<br>Values: CallCenter, OnlineStore, RetailStore<br>Required<br>Description: Channel type

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|RetailChannelId<br>Name<br>Type<br>Organization
DefaultCreate|DefaultCreate field group|RetailChannelId<br>Name<br>Type<br>Organization<br>CurrencyCode
DefaultDetails|DefaultDetails field group|RetailChannelId<br>Name<br>Type<br>Organization<br>CurrencyCode<br>TimeZone
DefaultIdentification|DefaultIdentification field group|RetailChannelId
DefaultList|DefaultList field group|RetailChannelId<br>Name<br>Type
DefaultLookup|DefaultLookup field group|RetailChannelId<br>Name
DefaultReport|DefaultReport field group|RetailChannelId<br>Name<br>Type<br>Organization<br>CurrencyCode<br>TimeZone

## RetailChannelWorker (Channel worker) Entity 
Retail stores are staffed and operated by personnel who may have different roles, such as store manager, store cashier, store inventory clerk, or support staff. based on the size and type of the retail store, each employee could potentially work across multiple shifts and stores. this entity is used to define the personnel who work at each store. 

Field | Description
---|---
RetailChannel<br>Primary key | Lookup: RetailChannel<br>Required
Status | Picklist: RetailChannelWorkerStatus<br>Values: Active, Inactive<br>Required
Worker | Lookup: Worker<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Worker|Worker|OneToMany|Association
RetailChannel|Retail channel|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|RetailChannel<br>Worker<br>Status
DefaultCreate|DefaultCreate field group|RetailChannel<br>Worker<br>Status
DefaultDetails|DefaultDetails field group|RetailChannel<br>Worker<br>Status
DefaultIdentification|DefaultIdentification field group|RetailChannel<br>Worker
DefaultList|DefaultList field group|RetailChannel<br>Worker<br>Status
DefaultLookup|DefaultLookup field group|RetailChannel<br>Worker<br>Status
DefaultReport|DefaultReport field group|RetailChannel<br>Worker<br>Status

## ScheduleEvent (Schedule event) Entity 
This entity holds information around the different schedule events like shifts & absences for workers in different channels. 

Field | Description
---|---
EndDateTime | Data: DateTime<br>Required
EventId<br>Primary key | Number sequence: <br>Unique, Searchable
LeaveType | Lookup: LeaveType
Note | Data: Text<br>Maximum length: 1024
RetailChannel | Lookup: RetailChannel<br>Required
StartDateTime | Data: DateTime<br>Required
Status | Picklist: ScheduleEventStatus<br>Values: Deleted, Draft, Published, Requested<br>Required
Type | Picklist: ScheduleEventType<br>Values: Absence, Work<br>Required
Worker | Lookup: Worker<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
RetailChannel|Retail channel|OneToMany|Association
LeaveType|Leave type|OneToMany|Association
Worker|Worker|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|EventId<br>Type<br>Worker<br>StartDateTime<br>EndDateTime
DefaultCreate|DefaultCreate field group|EventId<br>Type<br>Worker<br>StartDateTime<br>EndDateTime<br>Status<br>LeaveType<br>RetailChannel
DefaultDetails|DefaultDetails field group|EventId<br>Type<br>Worker<br>StartDateTime<br>EndDateTime<br>Status<br>LeaveType<br>Note
DefaultIdentification|DefaultIdentification field group|EventId
DefaultList|DefaultList field group|EventId<br>Type<br>Worker<br>StartDateTime<br>EndDateTime
DefaultLookup|DefaultLookup field group|Worker<br>Type<br>StartDateTime<br>EndDateTime
DefaultReport|DefaultReport field group|EventId<br>Type<br>Status<br>StartDateTime<br>EndDateTime<br>Worker<br>LeaveType<br>RetailChannel

## ScheduleEventPublishedRange (Published schedule range) Entity 
This entity holds information around the published time range of a schedule for the different retail channels. 

Field | Description
---|---
EndDateTime | Data: DateTime<br>Required
RangeId<br>Primary key | Number sequence: <br>Unique, Searchable
RetailChannel | Lookup: RetailChannel<br>Required
StartDateTime | Data: DateTime<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
RetailChannel|Retail channel|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|RangeId<br>RetailChannel<br>StartDateTime<br>EndDateTime
DefaultCreate|DefaultCreate field group|RangeId<br>RetailChannel<br>StartDateTime<br>EndDateTime
DefaultDetails|DefaultDetails field group|RangeId<br>RetailChannel<br>StartDateTime<br>EndDateTime
DefaultIdentification|DefaultIdentification field group|RangeId
DefaultList|DefaultList field group|RangeId<br>RetailChannel<br>StartDateTime<br>EndDateTime
DefaultLookup|DefaultLookup field group|StartDateTime<br>EndDateTime
DefaultReport|DefaultReport field group|RangeId<br>RetailChannel<br>StartDateTime<br>EndDateTime

## ScheduleEventRequest (Schedule request) Entity 
This entity holds information around the different request events like shift swap, offer shift, absence request for retail workers. 

Field | Description
---|---
FromEvent | Lookup: ScheduleEvent<br>Required<br>Description: Scheduleevent
FromWorker | Lookup: Worker<br>Required<br>Description: Worker
RequestId<br>Primary key | Number sequence: <br>Unique, Searchable
RetailChannel | Lookup: RetailChannel<br>Required
Status | Picklist: ScheduleEventRequestStatus<br>Values: Approved, Canceled, DeclinedByManager, DeclinedByWorker, PendingManagerApproval, PendingWorkerApproval<br>Required
ToEvent | Lookup: ScheduleEvent<br>Description: Scheduleevent
ToWorker | Lookup: Worker<br>Description: Worker
Type | Picklist: ScheduleEventRequestType<br>Values: OfferWork, RequestAbsence, SwapWork<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
RetailChannel|Retail channel|OneToMany|Association
ScheduleEvent|Scheduleevent|OneToMany|Association
ScheduleEvent|Scheduleevent|OneToMany|Association
Worker|Worker|OneToMany|Association
Worker|Worker|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|RequestId<br>Type<br>Status<br>FromWorker<br>RetailChannel
DefaultCreate|DefaultCreate field group|RequestId<br>Type<br>Status<br>FromWorker<br>ToWorker<br>FromEvent<br>ToEvent<br>RetailChannel
DefaultDetails|DefaultDetails field group|RequestId<br>Type<br>Status<br>FromWorker<br>ToWorker<br>FromEvent<br>ToEvent<br>RetailChannel
DefaultIdentification|DefaultIdentification field group|RequestId
DefaultList|DefaultList field group|RequestId<br>Type<br>Status<br>FromWorker
DefaultLookup|DefaultLookup field group|RequestId<br>Type<br>Status
DefaultReport|DefaultReport field group|RequestId<br>Type<br>Status<br>FromWorker<br>ToWorker<br>FromEvent<br>ToEvent<br>RetailChannel

## ScheduleEventRequestAction (Schedule request action) Entity 
This entity holds information around actions like create, cancel, decline or approve that are taken for the different request events. 

Field | Description
---|---
ActionId<br>Primary key | Number sequence: <br>Unique, Searchable
EventRequest | Lookup: ScheduleEventRequest<br>Required
Note | Data: Text<br>Maximum length: 1024
Type | Picklist: ScheduleEventRequestActionType<br>Values: Approve, Cancel, Create, Decline<br>Required
Worker | Lookup: Worker<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Worker|Worker|OneToMany|Association
ScheduleEventRequest|Event request|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|ActionId<br>Type<br>EventRequest<br>Worker
DefaultCreate|DefaultCreate field group|ActionId<br>Type<br>EventRequest<br>Worker<br>Note
DefaultDetails|DefaultDetails field group|ActionId<br>Type<br>EventRequest<br>Worker<br>Note
DefaultIdentification|DefaultIdentification field group|ActionId
DefaultList|DefaultList field group|ActionId<br>Type<br>EventRequest<br>Worker
DefaultLookup|DefaultLookup field group|ActionId<br>Type<br>EventRequest
DefaultReport|DefaultReport field group|ActionId<br>Type<br>EventRequest<br>Worker

