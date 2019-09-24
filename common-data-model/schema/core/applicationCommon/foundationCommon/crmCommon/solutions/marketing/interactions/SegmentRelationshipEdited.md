---
title: SegmentRelationshipEdited - Common Data Model | Microsoft Docs
description: This describes the SegmentRelationshipEdited entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Segment relationship edited

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/SegmentRelationshipEdited.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/interactions/SegmentRelationshipEdited  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[contactId](#contactId)|Contact|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[accountId](#accountId)|Account|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[sessionId](#sessionId)|Session ID|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[visitorId](#visitorId)|Visitor ID|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[sendingId](#sendingId)|Sending ID|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[countryIsoCode](#countryIsoCode)|Country ISO code|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[state](#state)|State|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[city](#city)|City|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[postalCode](#postalCode)|Postal code|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[browserId](#browserId)|Browser ID|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[browserVersion](#browserVersion)|Browser version|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[operatingSystemId](#operatingSystemId)|Operating system ID|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[operatingSystemVersion](#operatingSystemVersion)|Operating system version|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[segmentId](#segmentId)|Segment ID|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[relationshipOperatorAction](#relationshipOperatorAction)|Relationship operator action|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[result](#result)|Result|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[searchPhrase](#searchPhrase)|Search phrase|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[searchEngineName](#searchEngineName)|Search engine name|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[visitDuration](#visitDuration)|Visit duration|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[visitorReturningStatus](#visitorReturningStatus)|Visitor returning status|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[timestamp](#timestamp)|Timestamp|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[visitorAnonymousStatus](#visitorAnonymousStatus)|Visitor anonymous status|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|
|[leadId](#leadId)|Lead ID|<a href="SegmentRelationshipEdited.md" target="_blank">interactions/SegmentRelationshipEdited</a>|

### <a href=#interactionId name="interactionId">interactionId</a>

Unique identifier of the interaction.  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction Id</td></tr><tr><td>description</td><td>Unique identifier of the interaction.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>interactionId</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Contact  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ContactId</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Account  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>AccountId</td></tr></table>

### <a href=#sessionId name="sessionId">sessionId</a>

Session ID  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session ID</td></tr><tr><td>description</td><td>Session ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorId name="visitorId">visitorId</a>

Visitor ID  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor ID</td></tr><tr><td>description</td><td>Visitor ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sendingId name="sendingId">sendingId</a>

Sending ID  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sending ID</td></tr><tr><td>description</td><td>Sending ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#countryIsoCode name="countryIsoCode">countryIsoCode</a>

Country ISO code  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country ISO code</td></tr><tr><td>description</td><td>Country ISO code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#state name="state">state</a>

State  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>State</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#city name="city">city</a>

City  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal code  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal code</td></tr><tr><td>description</td><td>Postal code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserId name="browserId">browserId</a>

Browser ID  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser ID</td></tr><tr><td>description</td><td>Browser ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserVersion name="browserVersion">browserVersion</a>

Browser version  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser version</td></tr><tr><td>description</td><td>Browser version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemId name="operatingSystemId">operatingSystemId</a>

Operating system ID  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system ID</td></tr><tr><td>description</td><td>Operating system ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemVersion name="operatingSystemVersion">operatingSystemVersion</a>

Operating system version  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system version</td></tr><tr><td>description</td><td>Operating system version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#segmentId name="segmentId">segmentId</a>

Segment ID  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment ID</td></tr><tr><td>description</td><td>Segment ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#relationshipOperatorAction name="relationshipOperatorAction">relationshipOperatorAction</a>

Relationship operator action  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Relationship operator action</td></tr><tr><td>description</td><td>Relationship operator action</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#result name="result">result</a>

Result  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Result</td></tr><tr><td>description</td><td>Result</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchPhrase name="searchPhrase">searchPhrase</a>

Search phrase  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search phrase</td></tr><tr><td>description</td><td>Search phrase</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchEngineName name="searchEngineName">searchEngineName</a>

Search engine name  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search engine name</td></tr><tr><td>description</td><td>Search engine name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitDuration name="visitDuration">visitDuration</a>

Visit duration  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visit duration</td></tr><tr><td>description</td><td>Visit duration</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorReturningStatus name="visitorReturningStatus">visitorReturningStatus</a>

Visitor returning status  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor returning status</td></tr><tr><td>description</td><td>Visitor returning status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#timestamp name="timestamp">timestamp</a>

Timestamp  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timestamp</td></tr><tr><td>description</td><td>Timestamp</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorAnonymousStatus name="visitorAnonymousStatus">visitorAnonymousStatus</a>

Visitor anonymous status  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor anonymous status</td></tr><tr><td>description</td><td>Visitor anonymous status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

Lead ID  
First included in: interactions/SegmentRelationshipEdited (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead ID</td></tr><tr><td>description</td><td>Lead ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>
