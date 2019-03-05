---
title: EmailSubscriptionSubmit - Common Data Model | Microsoft Docs
description: This describes the EmailSubscriptionSubmit entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Email subscription submitted

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailSubscriptionSubmit.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/interactions/EmailSubscriptionSubmit  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[contactId](#contactId)|Contact|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[accountId](#accountId)|Account|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[messageId](#messageId)|Message|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[customerJourneyId](#customerJourneyId)|Customer journey|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[organizationId](#organizationId)|Organization ID|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[sendingId](#sendingId)|Sending ID|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[customerJourneyIterationId](#customerJourneyIterationId)|Customer journey iteration ID|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[usageType](#usageType)|Usage type|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[interactionType](#interactionType)|Interaction type|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[timestamp](#timestamp)|Timestamp|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[countryIsoCode](#countryIsoCode)|Country ISO code|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[state](#state)|State|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[city](#city)|City|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[postalCode](#postalCode)|Postal code|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[browserId](#browserId)|Browser ID|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[browserVersion](#browserVersion)|Browser version|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[operatingSystemId](#operatingSystemId)|Operating system ID|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[operatingSystemVersion](#operatingSystemVersion)|Operating system version|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[deviceType](#deviceType)|Device type|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[deviceBrand](#deviceBrand)|Device brand|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|
|[deviceModel](#deviceModel)|Device model|<a href="EmailSubscriptionSubmit.md" target="_blank">interactions/EmailSubscriptionSubmit</a>|

### <a href=#interactionId name="interactionId">interactionId</a>

Unique identifier of the interaction.  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction Id</td></tr><tr><td>description</td><td>Unique identifier of the interaction.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>interactionId</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Contact  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ContactId</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Account  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>AccountId</td></tr></table>

### <a href=#messageId name="messageId">messageId</a>

Message  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Message</td></tr><tr><td>description</td><td>Message</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>MessageId</td></tr></table>

### <a href=#customerJourneyId name="customerJourneyId">customerJourneyId</a>

Customer journey  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey</td></tr><tr><td>description</td><td>Customer journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>CustomerJourneyId</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Organization ID  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization ID</td></tr><tr><td>description</td><td>Organization ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#sendingId name="sendingId">sendingId</a>

Sending ID  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sending ID</td></tr><tr><td>description</td><td>Sending ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#customerJourneyIterationId name="customerJourneyIterationId">customerJourneyIterationId</a>

Customer journey iteration ID  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey iteration ID</td></tr><tr><td>description</td><td>Customer journey iteration ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#usageType name="usageType">usageType</a>

Usage type  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Usage type</td></tr><tr><td>description</td><td>Usage type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#interactionType name="interactionType">interactionType</a>

Interaction type  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction type</td></tr><tr><td>description</td><td>Interaction type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#timestamp name="timestamp">timestamp</a>

Timestamp  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timestamp</td></tr><tr><td>description</td><td>Timestamp</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#countryIsoCode name="countryIsoCode">countryIsoCode</a>

Country ISO code  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country ISO code</td></tr><tr><td>description</td><td>Country ISO code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#state name="state">state</a>

State  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>State</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#city name="city">city</a>

City  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal code  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal code</td></tr><tr><td>description</td><td>Postal code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserId name="browserId">browserId</a>

Browser ID  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser ID</td></tr><tr><td>description</td><td>Browser ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#browserVersion name="browserVersion">browserVersion</a>

Browser version  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Browser version</td></tr><tr><td>description</td><td>Browser version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemId name="operatingSystemId">operatingSystemId</a>

Operating system ID  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system ID</td></tr><tr><td>description</td><td>Operating system ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#operatingSystemVersion name="operatingSystemVersion">operatingSystemVersion</a>

Operating system version  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operating system version</td></tr><tr><td>description</td><td>Operating system version</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#deviceType name="deviceType">deviceType</a>

Device type  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device type</td></tr><tr><td>description</td><td>Device type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#deviceBrand name="deviceBrand">deviceBrand</a>

Device brand  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device brand</td></tr><tr><td>description</td><td>Device brand</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#deviceModel name="deviceModel">deviceModel</a>

Device model  
First included in: interactions/EmailSubscriptionSubmit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device model</td></tr><tr><td>description</td><td>Device model</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>
