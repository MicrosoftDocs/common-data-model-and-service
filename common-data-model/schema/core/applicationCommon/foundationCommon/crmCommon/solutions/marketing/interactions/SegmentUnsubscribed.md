---
title: SegmentUnsubscribed - Common Data Model | Microsoft Docs
description: This describes the SegmentUnsubscribed entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Segment unsubscribed

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/SegmentUnsubscribed.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/interactions/SegmentUnsubscribed  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[contactId](#contactId)|Contact|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[accountId](#accountId)|Account|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[customerJourneyId](#customerJourneyId)|Customer journey|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[messageId](#messageId)|Message|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[sessionId](#sessionId)|Session ID|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[visitorId](#visitorId)|Visitor ID|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[customerJourneyIterationId](#customerJourneyIterationId)|Customer journey iteration ID|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[sendingId](#sendingId)|Sending ID|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[emailDomain](#emailDomain)|Email domain|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[emailAddressUsed](#emailAddressUsed)|Email address used|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[countryIsoCode](#countryIsoCode)|Country ISO code|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[state](#state)|State|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[city](#city)|City|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[postalCode](#postalCode)|Postal code|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[browserId](#browserId)|Browser ID|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[browserVersion](#browserVersion)|Browser version|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[operatingSystemId](#operatingSystemId)|Operating system ID|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[operatingSystemVersion](#operatingSystemVersion)|Operating system version|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[segmentId](#segmentId)|Segment ID|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[formSubmissionId](#formSubmissionId)|Form submission ID|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[searchPhrase](#searchPhrase)|Search phrase|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[searchEngineName](#searchEngineName)|Search engine name|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[visitDuration](#visitDuration)|Visit duration|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[visitorReturningStatus](#visitorReturningStatus)|Visitor returning status|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[timestamp](#timestamp)|Timestamp|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[visitorAnonymousStatus](#visitorAnonymousStatus)|Visitor anonymous status|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|
|[leadId](#leadId)|Lead ID|<a href="SegmentUnsubscribed.md" target="_blank">interactions/SegmentUnsubscribed</a>|

### <a href=#interactionId name="interactionId">interactionId</a>

Unique identifier of the interaction.  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction Id</td></tr><tr><td>description</td><td>Unique identifier of the interaction.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>interactionId</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Contact  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ContactId</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Account  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>AccountId</td></tr></table>

### <a href=#customerJourneyId name="customerJourneyId">customerJourneyId</a>

Customer journey  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey</td></tr><tr><td>description</td><td>Customer journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>CustomerJourneyId</td></tr></table>

### <a href=#messageId name="messageId">messageId</a>

Message  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Message</td></tr><tr><td>description</td><td>Message</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>MessageId</td></tr></table>

### <a href=#sessionId name="sessionId">sessionId</a>

Session ID  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session ID</td></tr><tr><td>description</td><td>Session ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorId name="visitorId">visitorId</a>

Visitor ID  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor ID</td></tr><tr><td>description</td><td>Visitor ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#customerJourneyIterationId name="customerJourneyIterationId">customerJourneyIterationId</a>

Customer journey iteration ID  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey iteration ID</td></tr><tr><td>description</td><td>Customer journey iteration ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sendingId name="sendingId">sendingId</a>

Sending ID  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sending ID</td></tr><tr><td>description</td><td>Sending ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#emailDomain name="emailDomain">emailDomain</a>

Email domain  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email domain</td></tr><tr><td>description</td><td>Email domain</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#emailAddressUsed name="emailAddressUsed">emailAddressUsed</a>

Email address used  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email address used</td></tr><tr><td>description</td><td>Email address used</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#countryIsoCode name="countryIsoCode">countryIsoCode</a>

Country ISO code  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country ISO code</td></tr><tr><td>description</td><td>Country ISO code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#state name="state">state</a>

State  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>State</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#city name="city">city</a>

City  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal code  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal code</td></tr><tr><td>description</td><td>Postal code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserId name="browserId">browserId</a>

Browser ID  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser ID</td></tr><tr><td>description</td><td>Browser ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserVersion name="browserVersion">browserVersion</a>

Browser version  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser version</td></tr><tr><td>description</td><td>Browser version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemId name="operatingSystemId">operatingSystemId</a>

Operating system ID  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system ID</td></tr><tr><td>description</td><td>Operating system ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemVersion name="operatingSystemVersion">operatingSystemVersion</a>

Operating system version  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system version</td></tr><tr><td>description</td><td>Operating system version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#segmentId name="segmentId">segmentId</a>

Segment ID  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment ID</td></tr><tr><td>description</td><td>Segment ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#formSubmissionId name="formSubmissionId">formSubmissionId</a>

Form submission ID  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form submission ID</td></tr><tr><td>description</td><td>Form submission ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchPhrase name="searchPhrase">searchPhrase</a>

Search phrase  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search phrase</td></tr><tr><td>description</td><td>Search phrase</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchEngineName name="searchEngineName">searchEngineName</a>

Search engine name  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search engine name</td></tr><tr><td>description</td><td>Search engine name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitDuration name="visitDuration">visitDuration</a>

Visit duration  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visit duration</td></tr><tr><td>description</td><td>Visit duration</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorReturningStatus name="visitorReturningStatus">visitorReturningStatus</a>

Visitor returning status  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor returning status</td></tr><tr><td>description</td><td>Visitor returning status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#timestamp name="timestamp">timestamp</a>

Timestamp  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timestamp</td></tr><tr><td>description</td><td>Timestamp</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorAnonymousStatus name="visitorAnonymousStatus">visitorAnonymousStatus</a>

Visitor anonymous status  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor anonymous status</td></tr><tr><td>description</td><td>Visitor anonymous status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

Lead ID  
First included in: interactions/SegmentUnsubscribed (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead ID</td></tr><tr><td>description</td><td>Lead ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>
