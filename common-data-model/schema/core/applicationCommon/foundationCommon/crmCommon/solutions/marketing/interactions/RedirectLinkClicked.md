---
title: RedirectLinkClicked - Common Data Model | Microsoft Docs
description: This describes the RedirectLinkClicked entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Redirect link clicked

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/RedirectLinkClicked.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/interactions/RedirectLinkClicked  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[contactId](#contactId)|Contact|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[accountId](#accountId)|Account|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[messageId](#messageId)|Message|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[customerJourneyId](#customerJourneyId)|Customer journey|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[linkId](#linkId)|Link ID|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[link](#link)|Link|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[originalUrl](#originalUrl)|Original URL|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[referrerUri](#referrerUri)|Referrer URL|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[customerJourneyIterationId](#customerJourneyIterationId)|Customer journey iteration ID|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[sendingId](#sendingId)|Sending ID|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[interactionType](#interactionType)|Interaction type|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[organizationId](#organizationId)|Organization ID|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[timestamp](#timestamp)|Timestamp|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[visitorId](#visitorId)|Visitor ID|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[sessionId](#sessionId)|Session ID|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[countryIsoCode](#countryIsoCode)|Country ISO code|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[state](#state)|State|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[city](#city)|City|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[postalCode](#postalCode)|Postal code|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[browserId](#browserId)|Browser ID|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[browserVersion](#browserVersion)|Browser version|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[operatingSystemId](#operatingSystemId)|Operating system ID|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[operatingSystemVersion](#operatingSystemVersion)|Operating system version|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[searchPhrase](#searchPhrase)|Search phrase|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[searchEngineName](#searchEngineName)|Search engine name|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[visitDuration](#visitDuration)|Visit duration|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[visitorReturningStatus](#visitorReturningStatus)|Visitor returning status|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[visitorAnonymousStatus](#visitorAnonymousStatus)|Visitor anonymous status|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|
|[leadId](#leadId)|Lead ID|<a href="RedirectLinkClicked.md" target="_blank">interactions/RedirectLinkClicked</a>|

### <a href=#interactionId name="interactionId">interactionId</a>

Unique identifier of the interaction.  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction Id</td></tr><tr><td>description</td><td>Unique identifier of the interaction.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>interactionId</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Contact  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ContactId</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Account  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>AccountId</td></tr></table>

### <a href=#messageId name="messageId">messageId</a>

Message  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Message</td></tr><tr><td>description</td><td>Message</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>MessageId</td></tr></table>

### <a href=#customerJourneyId name="customerJourneyId">customerJourneyId</a>

Customer journey  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey</td></tr><tr><td>description</td><td>Customer journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>CustomerJourneyId</td></tr></table>

### <a href=#linkId name="linkId">linkId</a>

Link ID  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Link ID</td></tr><tr><td>description</td><td>Link ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#link name="link">link</a>

Link  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Link</td></tr><tr><td>description</td><td>Link</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#originalUrl name="originalUrl">originalUrl</a>

Original URL  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original URL</td></tr><tr><td>description</td><td>Original URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#referrerUri name="referrerUri">referrerUri</a>

Referrer URL  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referrer URL</td></tr><tr><td>description</td><td>Referrer URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#customerJourneyIterationId name="customerJourneyIterationId">customerJourneyIterationId</a>

Customer journey iteration ID  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey iteration ID</td></tr><tr><td>description</td><td>Customer journey iteration ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sendingId name="sendingId">sendingId</a>

Sending ID  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sending ID</td></tr><tr><td>description</td><td>Sending ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#interactionType name="interactionType">interactionType</a>

Interaction type  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction type</td></tr><tr><td>description</td><td>Interaction type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Organization ID  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization ID</td></tr><tr><td>description</td><td>Organization ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#timestamp name="timestamp">timestamp</a>

Timestamp  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timestamp</td></tr><tr><td>description</td><td>Timestamp</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorId name="visitorId">visitorId</a>

Visitor ID  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor ID</td></tr><tr><td>description</td><td>Visitor ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sessionId name="sessionId">sessionId</a>

Session ID  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session ID</td></tr><tr><td>description</td><td>Session ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#countryIsoCode name="countryIsoCode">countryIsoCode</a>

Country ISO code  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country ISO code</td></tr><tr><td>description</td><td>Country ISO code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#state name="state">state</a>

State  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>State</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#city name="city">city</a>

City  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal code  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal code</td></tr><tr><td>description</td><td>Postal code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserId name="browserId">browserId</a>

Browser ID  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser ID</td></tr><tr><td>description</td><td>Browser ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserVersion name="browserVersion">browserVersion</a>

Browser version  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser version</td></tr><tr><td>description</td><td>Browser version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemId name="operatingSystemId">operatingSystemId</a>

Operating system ID  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system ID</td></tr><tr><td>description</td><td>Operating system ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemVersion name="operatingSystemVersion">operatingSystemVersion</a>

Operating system version  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system version</td></tr><tr><td>description</td><td>Operating system version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchPhrase name="searchPhrase">searchPhrase</a>

Search phrase  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search phrase</td></tr><tr><td>description</td><td>Search phrase</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchEngineName name="searchEngineName">searchEngineName</a>

Search engine name  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search engine name</td></tr><tr><td>description</td><td>Search engine name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitDuration name="visitDuration">visitDuration</a>

Visit duration  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visit duration</td></tr><tr><td>description</td><td>Visit duration</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorReturningStatus name="visitorReturningStatus">visitorReturningStatus</a>

Visitor returning status  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor returning status</td></tr><tr><td>description</td><td>Visitor returning status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorAnonymousStatus name="visitorAnonymousStatus">visitorAnonymousStatus</a>

Visitor anonymous status  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor anonymous status</td></tr><tr><td>description</td><td>Visitor anonymous status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

Lead ID  
First included in: interactions/RedirectLinkClicked (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead ID</td></tr><tr><td>description</td><td>Lead ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>
