---
title: FormVisited in Customer Insights Journeys - Common Data Model | Microsoft Docs
description: undefined
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 3/26/2024
ms.author: anbichse
---

# FormVisited in Customer Insights Journeys

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/CustomerInsightsJourneys/formvisited.cdm.json" target="_blank">GitHub</a>.  

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
|[BrowserId](#BrowserId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[BrowserVersion](#BrowserVersion)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[City](#City)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[CountryIsoCode](#CountryIsoCode)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[FormId](#FormId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[LeadId](#LeadId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[OperatingSystemId](#OperatingSystemId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[OperatingSystemVersion](#OperatingSystemVersion)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[PageId](#PageId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[PageUrl](#PageUrl)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[PostalCode](#PostalCode)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[ReferrerUri](#ReferrerUri)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[SearchEngineName](#SearchEngineName)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[SearchPhrase](#SearchPhrase)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[SessionId](#SessionId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[State](#State)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[VisitDuration](#VisitDuration)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[VisitorAnonymousStatus](#VisitorAnonymousStatus)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[VisitorId](#VisitorId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[VisitorReturningStatus](#VisitorReturningStatus)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[WebsiteId](#WebsiteId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[SourceEntityName](#SourceEntityName)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[SourceEntityId](#SourceEntityId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[IsUnresolvedProfile](#IsUnresolvedProfile)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[JourneyRunId](#JourneyRunId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[JourneyActionId](#JourneyActionId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[JourneyVersion](#JourneyVersion)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[MessageTemplateVersion](#MessageTemplateVersion)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[EmailAddressUsed](#EmailAddressUsed)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[EmailDomain](#EmailDomain)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[MessageId](#MessageId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[SendingId](#SendingId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[UsageType](#UsageType)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[CustomerJourneyIterationId](#CustomerJourneyIterationId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[ProfileId](#ProfileId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[ProfileType](#ProfileType)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[AccountId](#AccountId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[ActivityId](#ActivityId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[ContactId](#ContactId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[CustomerJourneyId](#CustomerJourneyId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[BusinessUnitId](#BusinessUnitId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[IdempotencyId](#IdempotencyId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[InternalMarketingInteractionId](#InternalMarketingInteractionId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[OrganizationId](#OrganizationId)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[Timestamp](#Timestamp)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[Version](#Version)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[SourceSystem](#SourceSystem)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|
|[InteractionType](#InteractionType)||<a href="formvisited.md" target="_blank">CustomerInsightsJourneys/formvisited</a>|

### <a href=#BrowserId name="BrowserId">BrowserId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrowserId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#BrowserVersion name="BrowserVersion">BrowserVersion</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrowserVersion attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#City name="City">City</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the City attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#CountryIsoCode name="CountryIsoCode">CountryIsoCode</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryIsoCode attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#FormId name="FormId">FormId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#LeadId name="LeadId">LeadId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeadId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#OperatingSystemId name="OperatingSystemId">OperatingSystemId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingSystemId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#OperatingSystemVersion name="OperatingSystemVersion">OperatingSystemVersion</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingSystemVersion attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#PageId name="PageId">PageId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PageId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#PageUrl name="PageUrl">PageUrl</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PageUrl attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#PostalCode name="PostalCode">PostalCode</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostalCode attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ReferrerUri name="ReferrerUri">ReferrerUri</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferrerUri attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SearchEngineName name="SearchEngineName">SearchEngineName</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchEngineName attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SearchPhrase name="SearchPhrase">SearchPhrase</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchPhrase attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#State name="State">State</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#VisitDuration name="VisitDuration">VisitDuration</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisitDuration attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#VisitorAnonymousStatus name="VisitorAnonymousStatus">VisitorAnonymousStatus</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisitorAnonymousStatus attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#VisitorId name="VisitorId">VisitorId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisitorId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#VisitorReturningStatus name="VisitorReturningStatus">VisitorReturningStatus</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisitorReturningStatus attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#WebsiteId name="WebsiteId">WebsiteId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WebsiteId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SourceEntityName name="SourceEntityName">SourceEntityName</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceEntityName attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SourceEntityId name="SourceEntityId">SourceEntityId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#IsUnresolvedProfile name="IsUnresolvedProfile">IsUnresolvedProfile</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>boolean</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUnresolvedProfile attribute are listed below.</summary>

**is.dataFormat.boolean**  
  **is.dataFormat.boolean**  
  </details>

### <a href=#JourneyRunId name="JourneyRunId">JourneyRunId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JourneyRunId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#JourneyActionId name="JourneyActionId">JourneyActionId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JourneyActionId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#JourneyVersion name="JourneyVersion">JourneyVersion</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JourneyVersion attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#MessageTemplateVersion name="MessageTemplateVersion">MessageTemplateVersion</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageTemplateVersion attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#EmailAddressUsed name="EmailAddressUsed">EmailAddressUsed</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailAddressUsed attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#EmailDomain name="EmailDomain">EmailDomain</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailDomain attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#MessageId name="MessageId">MessageId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#SendingId name="SendingId">SendingId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SendingId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#UsageType name="UsageType">UsageType</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsageType attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#CustomerJourneyIterationId name="CustomerJourneyIterationId">CustomerJourneyIterationId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerJourneyIterationId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ProfileId name="ProfileId">ProfileId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ProfileType name="ProfileType">ProfileType</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileType attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#AccountId name="AccountId">AccountId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ActivityId name="ActivityId">ActivityId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ContactId name="ContactId">ContactId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#CustomerJourneyId name="CustomerJourneyId">CustomerJourneyId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerJourneyId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **means.identity.entityId**  
  **is.linkedEntity.identifier**  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../solutions/marketing/CustomerJourney.md" target="_blank">solutions/marketing/CustomerJourney.cdm.json/CustomerJourney</a></td><td><a href="../../solutions/marketing/CustomerJourney.md#customerJourneyId" target="_blank">customerJourneyId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#BusinessUnitId name="BusinessUnitId">BusinessUnitId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **means.identity.entityId**  
  **is.linkedEntity.identifier**  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../businessunit.md" target="_blank">BusinessUnit.cdm.json/BusinessUnit</a></td><td><a href="../../../businessunit.md#businessUnitId" target="_blank">businessUnitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#IdempotencyId name="IdempotencyId">IdempotencyId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdempotencyId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#InternalMarketingInteractionId name="InternalMarketingInteractionId">InternalMarketingInteractionId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalMarketingInteractionId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#OrganizationId name="OrganizationId">OrganizationId</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#Timestamp name="Timestamp">Timestamp</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>dateTime</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timestamp attribute are listed below.</summary>

**is.dataFormat.date**  
  **means.measurement.date**  
  **is.dataFormat.time**  
  **means.measurement.time**  
  **is.dataFormat.time**  
  **is.dataFormat.date**  
  </details>

### <a href=#Version name="Version">Version</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

**is.dataFormat.integer**  
  **is.dataFormat.signed**  
  indicates the capability to represent values less than zero.  

**is.dataFormat.numeric**  
  **is.dataFormat.integer**  
  </details>

### <a href=#SourceSystem name="SourceSystem">SourceSystem</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceSystem attribute are listed below.</summary>

**is.dataFormat.integer**  
  **is.dataFormat.signed**  
  indicates the capability to represent values less than zero.  

**is.dataFormat.numeric**  
  **is.dataFormat.integer**  
  </details>

### <a href=#InteractionType name="InteractionType">InteractionType</a>

First included in: CustomerInsightsJourneys/formvisited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InteractionType attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>
