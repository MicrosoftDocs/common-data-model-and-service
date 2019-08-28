---
title: FormSubmitted - Common Data Model | Microsoft Docs
description: This describes the FormSubmitted entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Form submitted

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[formId](#formId)|Form|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[pageId](#pageId)|Marketing page|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[messageId](#messageId)|Message|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[contactId](#contactId)|Contact|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[accountId](#accountId)|Account|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[customerJourneyId](#customerJourneyId)|Customer journey|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[formName](#formName)|Form name|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[formSubmissionId](#formSubmissionId)|Form submission ID|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[customerJourneyIterationId](#customerJourneyIterationId)|Customer journey iteration ID|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[result](#result)|Result|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[visitorId](#visitorId)|Visitor ID|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[sessionId](#sessionId)|Session ID|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[contactMatchingResult](#contactMatchingResult)|Contact matching result|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[leadMatchingResult](#leadMatchingResult)|Lead matching result|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[countryIsoCode](#countryIsoCode)|Country ISO code|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[state](#state)|State|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[city](#city)|City|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[postalCode](#postalCode)|Postal code|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[browserId](#browserId)|Browser ID|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[browserVersion](#browserVersion)|Browser version|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[operatingSystemId](#operatingSystemId)|Operating system ID|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[operatingSystemVersion](#operatingSystemVersion)|Operating system version|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[referrerUri](#referrerUri)|Referrer URL|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[sendingId](#sendingId)|Sending ID|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[searchPhrase](#searchPhrase)|Search phrase|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[searchEngineName](#searchEngineName)|Search engine name|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[visitDuration](#visitDuration)|Visit duration|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[visitorReturningStatus](#visitorReturningStatus)|Visitor returning status|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[contactFailureMessage](#contactFailureMessage)|Contact failure message|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[leadFailureMessage](#leadFailureMessage)|Lead failure message|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[timestamp](#timestamp)|Timestamp|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[visitorAnonymousStatus](#visitorAnonymousStatus)|Visitor anonymous status|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|
|[leadId](#leadId)|Lead ID|<a href="FormSubmitted.md" target="_blank">interactions/FormSubmitted</a>|

### <a href=#interactionId name="interactionId">interactionId</a>

Unique identifier of the interaction.  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction Id</td></tr><tr><td>description</td><td>Unique identifier of the interaction.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>interactionId</td></tr></table>

### <a href=#formId name="formId">formId</a>

Form  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form</td></tr><tr><td>description</td><td>Form</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>FormId</td></tr></table>

### <a href=#pageId name="pageId">pageId</a>

Marketing page  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing page</td></tr><tr><td>description</td><td>Marketing page</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>PageId</td></tr></table>

### <a href=#messageId name="messageId">messageId</a>

Message  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Message</td></tr><tr><td>description</td><td>Message</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>MessageId</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Contact  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ContactId</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Account  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>AccountId</td></tr></table>

### <a href=#customerJourneyId name="customerJourneyId">customerJourneyId</a>

Customer journey  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey</td></tr><tr><td>description</td><td>Customer journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>CustomerJourneyId</td></tr></table>

### <a href=#formName name="formName">formName</a>

Form name  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form name</td></tr><tr><td>description</td><td>Form name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#formSubmissionId name="formSubmissionId">formSubmissionId</a>

Form submission ID  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form submission ID</td></tr><tr><td>description</td><td>Form submission ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#customerJourneyIterationId name="customerJourneyIterationId">customerJourneyIterationId</a>

Customer journey iteration ID  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey iteration ID</td></tr><tr><td>description</td><td>Customer journey iteration ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#result name="result">result</a>

Result  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Result</td></tr><tr><td>description</td><td>Result</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorId name="visitorId">visitorId</a>

Visitor ID  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor ID</td></tr><tr><td>description</td><td>Visitor ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sessionId name="sessionId">sessionId</a>

Session ID  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session ID</td></tr><tr><td>description</td><td>Session ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#contactMatchingResult name="contactMatchingResult">contactMatchingResult</a>

Contact matching result  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact matching result</td></tr><tr><td>description</td><td>Contact matching result</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#leadMatchingResult name="leadMatchingResult">leadMatchingResult</a>

Lead matching result  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead matching result</td></tr><tr><td>description</td><td>Lead matching result</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#countryIsoCode name="countryIsoCode">countryIsoCode</a>

Country ISO code  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country ISO code</td></tr><tr><td>description</td><td>Country ISO code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#state name="state">state</a>

State  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>State</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#city name="city">city</a>

City  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal code  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal code</td></tr><tr><td>description</td><td>Postal code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserId name="browserId">browserId</a>

Browser ID  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser ID</td></tr><tr><td>description</td><td>Browser ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserVersion name="browserVersion">browserVersion</a>

Browser version  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser version</td></tr><tr><td>description</td><td>Browser version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemId name="operatingSystemId">operatingSystemId</a>

Operating system ID  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system ID</td></tr><tr><td>description</td><td>Operating system ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemVersion name="operatingSystemVersion">operatingSystemVersion</a>

Operating system version  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system version</td></tr><tr><td>description</td><td>Operating system version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#referrerUri name="referrerUri">referrerUri</a>

Referrer URL  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referrer URL</td></tr><tr><td>description</td><td>Referrer URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sendingId name="sendingId">sendingId</a>

Sending ID  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sending ID</td></tr><tr><td>description</td><td>Sending ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchPhrase name="searchPhrase">searchPhrase</a>

Search phrase  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search phrase</td></tr><tr><td>description</td><td>Search phrase</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#searchEngineName name="searchEngineName">searchEngineName</a>

Search engine name  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Search engine name</td></tr><tr><td>description</td><td>Search engine name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitDuration name="visitDuration">visitDuration</a>

Visit duration  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visit duration</td></tr><tr><td>description</td><td>Visit duration</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorReturningStatus name="visitorReturningStatus">visitorReturningStatus</a>

Visitor returning status  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor returning status</td></tr><tr><td>description</td><td>Visitor returning status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#contactFailureMessage name="contactFailureMessage">contactFailureMessage</a>

Contact failure message  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact failure message</td></tr><tr><td>description</td><td>Contact failure message</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#leadFailureMessage name="leadFailureMessage">leadFailureMessage</a>

Lead failure message  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead failure message</td></tr><tr><td>description</td><td>Lead failure message</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#timestamp name="timestamp">timestamp</a>

Timestamp  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timestamp</td></tr><tr><td>description</td><td>Timestamp</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#visitorAnonymousStatus name="visitorAnonymousStatus">visitorAnonymousStatus</a>

Visitor anonymous status  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visitor anonymous status</td></tr><tr><td>description</td><td>Visitor anonymous status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

Lead ID  
First included in: interactions/FormSubmitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead ID</td></tr><tr><td>description</td><td>Lead ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>
