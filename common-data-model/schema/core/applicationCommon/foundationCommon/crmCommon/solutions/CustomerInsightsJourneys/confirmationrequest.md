---
title: ConfirmationRequest in CustomerInsightsJourneys - Common Data Model | Microsoft Docs
description: undefined
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/4/2024
ms.author: cdmditeam
---

# ConfirmationRequest in CustomerInsightsJourneys

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/CustomerInsightsJourneys/confirmationrequest.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BrowserId](#BrowserId)|Browser ID|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[BrowserVersion](#BrowserVersion)|Browser version|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[ChannelMessageId](#ChannelMessageId)|Channel message ID|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[ChannelType](#ChannelType)|Channel type|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[City](#City)|City|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[ConfirmationRequestId](#ConfirmationRequestId)|Confirmation request ID|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[CountryIsoCode](#CountryIsoCode)|Country ISO code|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[OperatingSystemId](#OperatingSystemId)|Operating system ID|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[OperatingSystemVersion](#OperatingSystemVersion)|Operating system version|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[PostalCode](#PostalCode)|Postal code|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[RequestObjectId](#RequestObjectId)|Request object ID|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[RequestObjectName](#RequestObjectName)|Request object name|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[RequestObjectValue](#RequestObjectValue)|Request object value|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[RequestType](#RequestType)|Request type|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[SessionId](#SessionId)|Session ID|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[State](#State)|State|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[VisitorId](#VisitorId)|Visitor ID|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[VisitDuration](#VisitDuration)|Visit duration|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[VisitorReturningStatus](#VisitorReturningStatus)|Visitor returning status|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[VisitorAnonymousStatus](#VisitorAnonymousStatus)|Visitor anonymous status|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[SearchPhrase](#SearchPhrase)|Search phrase|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[SearchEngineName](#SearchEngineName)|Search engine name|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[IsSmartScheduled](#IsSmartScheduled)||<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[SchedulerId](#SchedulerId)||<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[EmailAddressUsed](#EmailAddressUsed)|The profile's email address\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[EmailDomain](#EmailDomain)|Email domain|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[MessageId](#MessageId)|Message ID|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[SendingId](#SendingId)|Indicates the journey iteration ID\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[UsageType](#UsageType)|Usage type|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[CustomerJourneyIterationId](#CustomerJourneyIterationId)|Customer journey iteration ID|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[ProfileId](#ProfileId)|Unique identifier of the profile\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[ProfileType](#ProfileType)|The profile type \(Contact, Lead or CI Profile\)|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[AccountId](#AccountId)|Unique identifier of the Account\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[ActivityId](#ActivityId)|Unique identifier of the Activity\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[ContactId](#ContactId)|Unique identifier of the Contact\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[LeadId](#LeadId)|Unique identifier of the Lead\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[CustomerJourneyId](#CustomerJourneyId)| Unique identifier of the Customer journey|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[BusinessUnitId](#BusinessUnitId)|Unique identifier of the Business unit\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[IdempotencyId](#IdempotencyId)|Idempotency ID defines uniqueness of an analytics event\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[InternalMarketingInteractionId](#InternalMarketingInteractionId)|Internal marketing interaction Id\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[OrganizationId](#OrganizationId)|Organization Id\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[Timestamp](#Timestamp)|Indicates the exact date and time when the interaction was emitted\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[Version](#Version)|Interaction version\. Used for updating the interaction\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[SourceSystem](#SourceSystem)| Refers to the source system that generated the interaction\. Outbound marketing \(OBM\) is represented by value 1\. Any other value than 1 represents Real\x2dtime journeys \(RTJ\)\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|
|[InteractionType](#InteractionType)|Type of the interaction\.|<a href="confirmationrequest.md" target="_blank">CustomerInsightsJourneys/confirmationrequest</a>|

### <a href=#BrowserId name="BrowserId">BrowserId</a>

Browser ID  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Browser ID</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrowserId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Browser ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#BrowserVersion name="BrowserVersion">BrowserVersion</a>

Browser version  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Browser version</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrowserVersion attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Browser version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ChannelMessageId name="ChannelMessageId">ChannelMessageId</a>

Channel message ID  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Channel message ID</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelMessageId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Channel message ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ChannelType name="ChannelType">ChannelType</a>

Channel type  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Channel type</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelType attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Channel type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#City name="City">City</a>

City  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>City</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the City attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>City</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ConfirmationRequestId name="ConfirmationRequestId">ConfirmationRequestId</a>

Confirmation request ID  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Confirmation request ID</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmationRequestId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confirmation request ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#CountryIsoCode name="CountryIsoCode">CountryIsoCode</a>

Country ISO code  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Country ISO code</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryIsoCode attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Country ISO code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#OperatingSystemId name="OperatingSystemId">OperatingSystemId</a>

Operating system ID  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Operating system ID</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingSystemId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operating system ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#OperatingSystemVersion name="OperatingSystemVersion">OperatingSystemVersion</a>

Operating system version  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Operating system version</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingSystemVersion attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operating system version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#PostalCode name="PostalCode">PostalCode</a>

Postal code  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Postal code</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostalCode attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Postal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#RequestObjectId name="RequestObjectId">RequestObjectId</a>

Request object ID  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Request object ID</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestObjectId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request object ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#RequestObjectName name="RequestObjectName">RequestObjectName</a>

Request object name  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Request object name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestObjectName attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request object name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#RequestObjectValue name="RequestObjectValue">RequestObjectValue</a>

Request object value  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Request object value</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestObjectValue attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request object value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#RequestType name="RequestType">RequestType</a>

Request type  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Request type</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestType attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SessionId name="SessionId">SessionId</a>

Session ID  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Session ID</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Session ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#State name="State">State</a>

State  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>State</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>State</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#VisitorId name="VisitorId">VisitorId</a>

Visitor ID  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Visitor ID</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisitorId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Visitor ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#VisitDuration name="VisitDuration">VisitDuration</a>

Visit duration  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Visit duration</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisitDuration attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Visit duration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#VisitorReturningStatus name="VisitorReturningStatus">VisitorReturningStatus</a>

Visitor returning status  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Visitor returning status</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisitorReturningStatus attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Visitor returning status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#VisitorAnonymousStatus name="VisitorAnonymousStatus">VisitorAnonymousStatus</a>

Visitor anonymous status  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Visitor anonymous status</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisitorAnonymousStatus attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Visitor anonymous status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SearchPhrase name="SearchPhrase">SearchPhrase</a>

Search phrase  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Search phrase</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchPhrase attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Search phrase</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SearchEngineName name="SearchEngineName">SearchEngineName</a>

Search engine name  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Search engine name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchEngineName attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Search engine name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#IsSmartScheduled name="IsSmartScheduled">IsSmartScheduled</a>

First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>boolean</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSmartScheduled attribute are listed below.</summary>

\*\*is\.dataFormat\.boolean\*\*  
  \*\*is\.dataFormat\.boolean\*\*  
  </details>

### <a href=#SchedulerId name="SchedulerId">SchedulerId</a>

First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedulerId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#EmailAddressUsed name="EmailAddressUsed">EmailAddressUsed</a>

The profile's email address\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>The profile's email address.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailAddressUsed attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The profile's email address.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#EmailDomain name="EmailDomain">EmailDomain</a>

Email domain  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Email domain</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailDomain attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email domain</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#MessageId name="MessageId">MessageId</a>

Message ID  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Message ID</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Message ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SendingId name="SendingId">SendingId</a>

Indicates the journey iteration ID\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Indicates the journey iteration ID.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SendingId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates the journey iteration ID.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#UsageType name="UsageType">UsageType</a>

Usage type  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Usage type</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsageType attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Usage type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#CustomerJourneyIterationId name="CustomerJourneyIterationId">CustomerJourneyIterationId</a>

Customer journey iteration ID  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Customer journey iteration ID</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerJourneyIterationId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*means\.identity\.entityId\*\*  
  \*\*is\.linkedEntity\.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Marketing/MarketingSolution/CustomerJourneyIteration.md" target="_blank">/Marketing/MarketingSolution/CustomerJourneyIteration.cdm.json</a></td><td><a href="../Marketing/MarketingSolution/CustomerJourneyIteration.md#customerJourneyIterationId" target="_blank">customerJourneyIterationId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer journey iteration ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ProfileId name="ProfileId">ProfileId</a>

Unique identifier of the profile\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the profile.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the profile.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ProfileType name="ProfileType">ProfileType</a>

The profile type \(Contact, Lead or CI Profile\)  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>The profile type (Contact, Lead or CI Profile)</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileType attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The profile type (Contact, Lead or CI Profile)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#AccountId name="AccountId">AccountId</a>

Unique identifier of the Account\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Account.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*means\.identity\.entityId\*\*  
  \*\*is\.linkedEntity\.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/Account.md" target="_blank">/core/applicationCommon/Account.cdm.json/Account</a></td><td><a href="../core/applicationCommon/Account.md#accountId" target="_blank">accountId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Account.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ActivityId name="ActivityId">ActivityId</a>

Unique identifier of the Activity\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Activity.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*means\.identity\.entityId\*\*  
  \*\*is\.linkedEntity\.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/Activity.md" target="_blank">/core/applicationCommon/Activity.cdm.json/Activity</a></td><td><a href="../core/applicationCommon/Activity.md#activityId" target="_blank">activityId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Activity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ContactId name="ContactId">ContactId</a>

Unique identifier of the Contact\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Contact.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.linkedEntity\.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/Contact.md" target="_blank">/core/applicationCommon/Contact.cdm.json/Contact</a></td><td><a href="../core/applicationCommon/Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Contact.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#LeadId name="LeadId">LeadId</a>

Unique identifier of the Lead\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Lead.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeadId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*means\.identity\.entityId\*\*  
  \*\*is\.linkedEntity\.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/foundationCommon/crmCommon/Lead.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/Lead.cdm.json/Lead</a></td><td><a href="../core/applicationCommon/foundationCommon/crmCommon/Lead.md#leadId" target="_blank">leadId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Lead.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#CustomerJourneyId name="CustomerJourneyId">CustomerJourneyId</a>

 Unique identifier of the Customer journey  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td> Unique identifier of the Customer journey</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerJourneyId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td> Unique identifier of the Customer journey</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#BusinessUnitId name="BusinessUnitId">BusinessUnitId</a>

Unique identifier of the Business unit\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Business unit.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessUnitId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*means\.identity\.entityId\*\*  
  \*\*is\.linkedEntity\.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/BusinessUnit.md" target="_blank">/core/applicationCommon/BusinessUnit.cdm.json/BusinessUnit</a></td><td><a href="../core/applicationCommon/BusinessUnit.md#businessUnitId" target="_blank">businessUnitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Business unit.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#IdempotencyId name="IdempotencyId">IdempotencyId</a>

Idempotency ID defines uniqueness of an analytics event\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Idempotency ID defines uniqueness of an analytics event.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdempotencyId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Idempotency ID defines uniqueness of an analytics event.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#InternalMarketingInteractionId name="InternalMarketingInteractionId">InternalMarketingInteractionId</a>

Internal marketing interaction Id\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Internal marketing interaction Id.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalMarketingInteractionId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Internal marketing interaction Id.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#OrganizationId name="OrganizationId">OrganizationId</a>

Organization Id\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Organization Id.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization Id.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#Timestamp name="Timestamp">Timestamp</a>

Indicates the exact date and time when the interaction was emitted\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Indicates the exact date and time when the interaction was emitted.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timestamp attribute are listed below.</summary>

\*\*is\.dataFormat\.date\*\*  
  \*\*means\.measurement\.date\*\*  
  \*\*is\.dataFormat\.time\*\*  
  \*\*means\.measurement\.time\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates the exact date and time when the interaction was emitted.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.time\*\*  
  \*\*is\.dataFormat\.date\*\*  
  </details>

### <a href=#Version name="Version">Version</a>

Interaction version\. Used for updating the interaction\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Interaction version. Used for updating the interaction.</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interaction version. Used for updating the interaction.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#SourceSystem name="SourceSystem">SourceSystem</a>

 Refers to the source system that generated the interaction\. Outbound marketing \(OBM\) is represented by value 1\. Any other value than 1 represents Real\x2dtime journeys \(RTJ\)\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td> Refers to the source system that generated the interaction. Outbound marketing (OBM) is represented by value 1. Any other value than 1 represents Real-time journeys (RTJ).</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceSystem attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td> Refers to the source system that generated the interaction. Outbound marketing (OBM) is represented by value 1. Any other value than 1 represents Real-time journeys (RTJ).</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#InteractionType name="InteractionType">InteractionType</a>

Type of the interaction\.  
First included in: CustomerInsightsJourneys/confirmationrequest \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Type of the interaction.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InteractionType attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of the interaction.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>
