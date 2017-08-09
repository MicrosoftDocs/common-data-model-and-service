---
title: "Productivity reference | Microsoft Docs"
description: "The productivity entities let you track events and messages."
author: "robinarh"
manager: "robinarh"
ms.date: "05/08/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "8ed2fc48-8ee7-4279-823d-7690bf944add"
ms.reviewer: robinr
ms.author: robinr
---

# Productivity reference 
## Event (Event) Entity 
An event (appointment, meeting) within a users mailbox or related to data within the common data service. this entity is connect to the microsoft graph to retrieve mail box events. 

Field | Description
---|---
Attendees | Data: Text<br>Maximum length: 2048
Body_Content | Data: Memo<br>Description: Body content
Body_ContentType | Picklist: BodyContentType<br>Values: HTML, Text<br>Description: Body content type
BodyPreview | Data: Text<br>Maximum length: 2048
Categories | Data: Text<br>Maximum length: 2048
ChangeKey | Data: Text<br>Maximum length: 2048
End | Data: DateTime
HasAttachments | Data: Boolean
ICalUId | Data: Text<br>Maximum length: 2048<br>Description: Unique calendar ID
Id<br>Primary key | Data: Text<br>Required, Unique, Searchable, Maximum length: 2048<br>Description: Event ID
Importance | Picklist: EventImportance<br>Values: High, Low, Normal
IsAllDay | Data: Boolean<br>Description: All day
IsCancelled | Data: Boolean<br>Description: Cancelled
IsOrganizer | Data: Boolean<br>Description: Organizer
IsReminderOn | Data: Boolean<br>Description: Reminder
Location_Address | Data: Address<br>Description: Location address
Location_DisplayName | Data: Text<br>Maximum length: 2048<br>Description: Location display name
Location_EmailAddress | Data: Text<br>Maximum length: 2048<br>Description: Location email address
OnlineMeetingURL | Data: Text<br>Maximum length: 2048
Organizer | Data: Text<br>Maximum length: 2048
OriginalEndTimeZone | Picklist: Timezone<br>Values: GMT_CASABLANCA, GMT_CASABLANCA_MONTROVIA_REYKJAVIK, GMT_COORDINATEDUNIVERSALTIME, GMT_DUBLIN_EDINBURGH_LISBON_LONDON, GMT_PLUS0300KALININGRAD_MINSK, GMTMINUS0100AZORES, GMTMINUS0100CAPEVERDIS, GMTMINUS0200MIDATLANTIC, GMTMINUS0300_SALVADOR, GMTMINUS0300BRASILIA, GMTMINUS0300BUENOSAIRES, GMTMINUS0300BUENOSAIRES_GEORGETOWN, GMTMINUS0300GREENLAND, GMTMINUS0300MONTEVIDEO, GMTMINUS0330NEWFOUNDLAND, GMTMINUS0400ASUNCION, GMTMINUS0400ATLANTICTIME, GMTMINUS0400LAPAZ, GMTMINUS0400MANAUS, GMTMINUS0400SANTIAGO, GMTMINUS0430CARACAS, GMTMINUS0500BOGOTA_LIMA_QUITO_RIOBRANCO, GMTMINUS0500EASTERNTIME, GMTMINUS0500INDIANA, GMTMINUS0600CENTRALAMERICA, GMTMINUS0600CENTRALTIME, GMTMINUS0600GUADALAJARA_MEXICOCITY, GMTMINUS0600SASKATCHEWAN, GMTMINUS0700ARIZONA, GMTMINUS0700CHIHUAHUA_LAPAZ_MAZATLAN, GMTMINUS0700MOUNTAINTIME, GMTMINUS0800PACIFICTIME, GMTMINUS0800TIJUANA_BAJACALIFORNIA, GMTMINUS0900ALASKA, GMTMINUS1000HAWAII, GMTMINUS1100COORDINATEDUNIVERSALTIME, GMTMINUS1100MIDWAYISLAND_SAMOA, GMTMINUS1200INTERNATIONALDATELINEWEST, GMTPLUS0100_AMSTERDAM_BERLIN_BERN_ROME, GMTPLUS0100BELGRADE_BRATISLAVA_BUDAPEST, GMTPLUS0100BRUSSELS_COPENHAGEN_MADRID, GMTPLUS0100SARAJEVO_SKOPJE_WARSAW_ZAGREB, GMTPLUS0100TRIPOLI, GMTPLUS0100WESTCENTRALAFRICA, GMTPLUS0200_DAMASCUS, GMTPLUS0200AMMAN, GMTPLUS0200ATHENS_BUCHAREST_ISTANBUL, GMTPLUS0200BEIRUT, GMTPLUS0200CAIRO, GMTPLUS0200HARARE_PRETORIA, GMTPLUS0200HELSINKI_KYIV_RIGA_VILNIUS, GMTPLUS0200ISTANBUL, GMTPLUS0200JERUSALEM, GMTPLUS0200MINSK, GMTPLUS0200WINDHOEK, GMTPLUS0300BAGHDAD, GMTPLUS0300KUWAIT_RIYADH, GMTPLUS0300MOSCOW_STPETERSBURG_VOLGOGRAD, GMTPLUS0300NAIROBI, GMTPLUS0300TBILISI, GMTPLUS0330TEHRAN, GMTPLUS0400ABUDHABI_MUSCAT, GMTPLUS0400BAKU, GMTPLUS0400CAUCASUSSTANDARDTIME, GMTPLUS0400IZHEVSK_SAMARA, GMTPLUS0400PORTLOUIS, GMTPLUS0400YEREVAN, GMTPLUS0430KABUL, GMTPLUS0500EKATERINBURG, GMTPLUS0500ISLAMABAD_KARACHI, GMTPLUS0500ISLAMABAD_KARACHI_TASHKENT, GMTPLUS0530CHENNAI_KOLKATA_MUMBAI, GMTPLUS0530SRIJAYAWARDENEPURA, GMTPLUS0545KATHMANDU, GMTPLUS0600ALMATY_NOVOSIBIRSK, GMTPLUS0600ASTANA_DHAKA, GMTPLUS0600DHAKA, GMTPLUS0600MAGADAN, GMTPLUS0630_YANGON, GMTPLUS0700_BANGKOK_HANOI_JAKARTA, GMTPLUS0700KRASNOYARSK, GMTPLUS0800_ULAANBAATAR, GMTPLUS0800BEIJING_CHONGQING_HONGKONG, GMTPLUS0800IRKUTSK_ULAANBATAAR, GMTPLUS0800KUALALUMPUR_SINGAPORE, GMTPLUS0800PERTH, GMTPLUS0800TAIPEI, GMTPLUS0900OSAKA_SAPPORO_TOKYO, GMTPLUS0900SEOUL, GMTPLUS0900YAKUTSK, GMTPLUS0930ADELAIDE, GMTPLUS0930DARWIN, GMTPLUS1000BRISBANE, GMTPLUS1000CANBERRA_MELBOURNE_SYDNEY, GMTPLUS1000GUAM_PORTMORESBY, GMTPLUS1000HOBART, GMTPLUS1000VLADIVOSTOK, GMTPLUS1100CHOKURDAKH, GMTPLUS1100MAGADAN_SOLOMONIS, GMTPLUS1200ANADYR_PETRO_KAMCHATSKY, GMTPLUS1200AUCKLAND_WELLINGTON, GMTPLUS1200COORDINATEDUNIVERSALTIME, GMTPLUS1200FIJI_KAMCHATKA_MARSHALLIS, GMTPLUS1300NUKU_ALOFA
OriginalStart | Data: DateTime<br>Searchable
OriginalStartTimeZone | Picklist: Timezone<br>Values: GMT_CASABLANCA, GMT_CASABLANCA_MONTROVIA_REYKJAVIK, GMT_COORDINATEDUNIVERSALTIME, GMT_DUBLIN_EDINBURGH_LISBON_LONDON, GMT_PLUS0300KALININGRAD_MINSK, GMTMINUS0100AZORES, GMTMINUS0100CAPEVERDIS, GMTMINUS0200MIDATLANTIC, GMTMINUS0300_SALVADOR, GMTMINUS0300BRASILIA, GMTMINUS0300BUENOSAIRES, GMTMINUS0300BUENOSAIRES_GEORGETOWN, GMTMINUS0300GREENLAND, GMTMINUS0300MONTEVIDEO, GMTMINUS0330NEWFOUNDLAND, GMTMINUS0400ASUNCION, GMTMINUS0400ATLANTICTIME, GMTMINUS0400LAPAZ, GMTMINUS0400MANAUS, GMTMINUS0400SANTIAGO, GMTMINUS0430CARACAS, GMTMINUS0500BOGOTA_LIMA_QUITO_RIOBRANCO, GMTMINUS0500EASTERNTIME, GMTMINUS0500INDIANA, GMTMINUS0600CENTRALAMERICA, GMTMINUS0600CENTRALTIME, GMTMINUS0600GUADALAJARA_MEXICOCITY, GMTMINUS0600SASKATCHEWAN, GMTMINUS0700ARIZONA, GMTMINUS0700CHIHUAHUA_LAPAZ_MAZATLAN, GMTMINUS0700MOUNTAINTIME, GMTMINUS0800PACIFICTIME, GMTMINUS0800TIJUANA_BAJACALIFORNIA, GMTMINUS0900ALASKA, GMTMINUS1000HAWAII, GMTMINUS1100COORDINATEDUNIVERSALTIME, GMTMINUS1100MIDWAYISLAND_SAMOA, GMTMINUS1200INTERNATIONALDATELINEWEST, GMTPLUS0100_AMSTERDAM_BERLIN_BERN_ROME, GMTPLUS0100BELGRADE_BRATISLAVA_BUDAPEST, GMTPLUS0100BRUSSELS_COPENHAGEN_MADRID, GMTPLUS0100SARAJEVO_SKOPJE_WARSAW_ZAGREB, GMTPLUS0100TRIPOLI, GMTPLUS0100WESTCENTRALAFRICA, GMTPLUS0200_DAMASCUS, GMTPLUS0200AMMAN, GMTPLUS0200ATHENS_BUCHAREST_ISTANBUL, GMTPLUS0200BEIRUT, GMTPLUS0200CAIRO, GMTPLUS0200HARARE_PRETORIA, GMTPLUS0200HELSINKI_KYIV_RIGA_VILNIUS, GMTPLUS0200ISTANBUL, GMTPLUS0200JERUSALEM, GMTPLUS0200MINSK, GMTPLUS0200WINDHOEK, GMTPLUS0300BAGHDAD, GMTPLUS0300KUWAIT_RIYADH, GMTPLUS0300MOSCOW_STPETERSBURG_VOLGOGRAD, GMTPLUS0300NAIROBI, GMTPLUS0300TBILISI, GMTPLUS0330TEHRAN, GMTPLUS0400ABUDHABI_MUSCAT, GMTPLUS0400BAKU, GMTPLUS0400CAUCASUSSTANDARDTIME, GMTPLUS0400IZHEVSK_SAMARA, GMTPLUS0400PORTLOUIS, GMTPLUS0400YEREVAN, GMTPLUS0430KABUL, GMTPLUS0500EKATERINBURG, GMTPLUS0500ISLAMABAD_KARACHI, GMTPLUS0500ISLAMABAD_KARACHI_TASHKENT, GMTPLUS0530CHENNAI_KOLKATA_MUMBAI, GMTPLUS0530SRIJAYAWARDENEPURA, GMTPLUS0545KATHMANDU, GMTPLUS0600ALMATY_NOVOSIBIRSK, GMTPLUS0600ASTANA_DHAKA, GMTPLUS0600DHAKA, GMTPLUS0600MAGADAN, GMTPLUS0630_YANGON, GMTPLUS0700_BANGKOK_HANOI_JAKARTA, GMTPLUS0700KRASNOYARSK, GMTPLUS0800_ULAANBAATAR, GMTPLUS0800BEIJING_CHONGQING_HONGKONG, GMTPLUS0800IRKUTSK_ULAANBATAAR, GMTPLUS0800KUALALUMPUR_SINGAPORE, GMTPLUS0800PERTH, GMTPLUS0800TAIPEI, GMTPLUS0900OSAKA_SAPPORO_TOKYO, GMTPLUS0900SEOUL, GMTPLUS0900YAKUTSK, GMTPLUS0930ADELAIDE, GMTPLUS0930DARWIN, GMTPLUS1000BRISBANE, GMTPLUS1000CANBERRA_MELBOURNE_SYDNEY, GMTPLUS1000GUAM_PORTMORESBY, GMTPLUS1000HOBART, GMTPLUS1000VLADIVOSTOK, GMTPLUS1100CHOKURDAKH, GMTPLUS1100MAGADAN_SOLOMONIS, GMTPLUS1200ANADYR_PETRO_KAMCHATSKY, GMTPLUS1200AUCKLAND_WELLINGTON, GMTPLUS1200COORDINATEDUNIVERSALTIME, GMTPLUS1200FIJI_KAMCHATKA_MARSHALLIS, GMTPLUS1300NUKU_ALOFA
ReminderMinutesBeforeStart | Data: Integer
ResponseRequested | Data: Boolean
ResponseStatus_Response | Picklist: EventResponse<br>Values: Accepted, Declined, None, NotResponded, Organizer, TentativelyAccepted<br>Description: Response
ResponseStatus_Time | Data: DateTime<br>Description: Response time
Sensitivity | Picklist: EventSensitivity<br>Values: Confidential, Normal, Personal, Private
ShowAs | Picklist: EventTimeStatus<br>Values: Busy, Free, OutofOffice, Tentative, Unknown, Workingelsewhere
SourceCreatedDateTime | Data: DateTime<br>Searchable
SourceLastModifiedDateTime | Data: DateTime
Start | Data: DateTime
Subject | Data: Text<br>Maximum length: 2048
Type | Picklist: EventType<br>Values: Exception, Occurrence, SeriesMaster, SingleInstance
WebLink | Data: Text<br>Maximum length: 255

### Relationships

This entity has no relationships.

### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Start<br>End<br>Subject<br>Location_DisplayName
DefaultCreate|DefaultCreate field group|Id<br>Start<br>End<br>Subject<br>Importance<br>Location_DisplayName<br>Body_Content
DefaultDetails|DefaultDetails field group|Start<br>End<br>Subject<br>ShowAs<br>Importance<br>BodyPreview<br>Location_DisplayName
DefaultIdentification|DefaultIdentification field group|Id<br>Subject
DefaultList|DefaultList field group|Start<br>End<br>Subject<br>Location_DisplayName
DefaultLookup|DefaultLookup field group|Start<br>Subject
DefaultReport|DefaultReport field group|Start<br>End<br>Subject<br>Location_DisplayName

## Message (Message) Entity 
A message (email) within a users mailbox or related to data within the Common Data Service. This entity is connect to the Microsoft Graph to retrieve mail box messages. 

Field | Description
---|---
BccRecipients | Data: Text<br>Maximum length: 2048
Body_Content | Data: Memo<br>Description: Body content
Body_ContentType | Picklist: BodyContentType<br>Values: HTML, Text<br>Description: Body content type
BodyPreview | Data: Text<br>Maximum length: 2048
Categories | Data: Text<br>Maximum length: 2048
CCRecipients | Data: Text<br>Maximum length: 2048
ChangeKey | Data: Text<br>Maximum length: 2048
ConversationId | Data: Text<br>Maximum length: 2048
From | Data: Text<br>Maximum length: 2048
HasAttachments | Data: Boolean
Id<br>Primary key | Data: Text<br>Required, Unique, Searchable, Maximum length: 2048<br>Description: Message ID
Importance | Picklist: MessageImportance<br>Values: High, Low, Normal
InferenceClassification | Picklist: MessageInferenceClassification<br>Values: Focused, Other
InternetMessageId | Data: Text<br>Maximum length: 2048
IsDeliveryReceiptRequested | Data: Boolean<br>Description: Delivery receipt requested
IsDraft | Data: Boolean<br>Description: Draft
IsRead | Data: Boolean<br>Description: Read
IsReadReceiptRequested | Data: Boolean<br>Description: Read receipt requested
ParentFolderId | Data: Text<br>Maximum length: 2048
ReceivedDateTime | Data: DateTime
ReplyTo | Data: Text<br>Maximum length: 2048
Sender | Data: Text<br>Maximum length: 2048
SentDateTime | Data: DateTime<br>Searchable
SourceCreatedDateTime | Data: DateTime<br>Searchable
SourceLastModifiedDateTime | Data: DateTime
Subject | Data: Text<br>Searchable, Maximum length: 2048
ToRecipients | Data: Text<br>Maximum length: 2048<br>Description: To receipients
UniqueBody_Content | Data: Memo<br>Description: Unique body content
UniqueBody_ContentType | Picklist: BodyContentType<br>Values: HTML, Text<br>Description: Unique body content type
WebLink | Data: Text<br>Maximum length: 255

### Relationships

This entity has no relationships.

### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|From<br>ToRecipients<br>Subject<br>SentDateTime
DefaultCreate|DefaultCreate field group|Id<br>From<br>ToRecipients<br>CCRecipients<br>Subject<br>SentDateTime<br>Importance<br>Body_Content
DefaultDetails|DefaultDetails field group|From<br>ToRecipients<br>CCRecipients<br>Subject<br>SentDateTime<br>Importance<br>BodyPreview
DefaultIdentification|DefaultIdentification field group|Id<br>Subject
DefaultList|DefaultList field group|From<br>ToRecipients<br>Subject<br>SentDateTime
DefaultLookup|DefaultLookup field group|Subject<br>SentDateTime
DefaultReport|DefaultReport field group|From<br>ToRecipients<br>Subject<br>SentDateTime

