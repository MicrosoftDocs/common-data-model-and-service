---
title: ContactRegisteredToEvent - Common Data Model | Microsoft Docs
description: This describes the ContactRegisteredToEvent entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Event registration

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/ContactRegisteredToEvent.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/interactions/ContactRegisteredToEvent  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|<a href="ContactRegisteredToEvent.md" target="_blank">interactions/ContactRegisteredToEvent</a>|
|[eventId](#eventId)|Event|<a href="ContactRegisteredToEvent.md" target="_blank">interactions/ContactRegisteredToEvent</a>|
|[contactId](#contactId)|Contact|<a href="ContactRegisteredToEvent.md" target="_blank">interactions/ContactRegisteredToEvent</a>|
|[accountId](#accountId)|Account|<a href="ContactRegisteredToEvent.md" target="_blank">interactions/ContactRegisteredToEvent</a>|
|[customerJourneyId](#customerJourneyId)|Customer journey|<a href="ContactRegisteredToEvent.md" target="_blank">interactions/ContactRegisteredToEvent</a>|
|[organizationId](#organizationId)|Organization ID|<a href="ContactRegisteredToEvent.md" target="_blank">interactions/ContactRegisteredToEvent</a>|
|[eventRegistrationId](#eventRegistrationId)|eventregistrationid|<a href="ContactRegisteredToEvent.md" target="_blank">interactions/ContactRegisteredToEvent</a>|
|[interactionType](#interactionType)|Interaction type|<a href="ContactRegisteredToEvent.md" target="_blank">interactions/ContactRegisteredToEvent</a>|
|[timestamp](#timestamp)|Timestamp|<a href="ContactRegisteredToEvent.md" target="_blank">interactions/ContactRegisteredToEvent</a>|

### <a href=#interactionId name="interactionId">interactionId</a>

Unique identifier of the interaction.  
First included in: interactions/ContactRegisteredToEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction Id</td></tr><tr><td>description</td><td>Unique identifier of the interaction.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>interactionId</td></tr></table>

### <a href=#eventId name="eventId">eventId</a>

Event  
First included in: interactions/ContactRegisteredToEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Event</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>EventId</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Contact  
First included in: interactions/ContactRegisteredToEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ContactId</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Account  
First included in: interactions/ContactRegisteredToEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>AccountId</td></tr></table>

### <a href=#customerJourneyId name="customerJourneyId">customerJourneyId</a>

Customer journey  
First included in: interactions/ContactRegisteredToEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey</td></tr><tr><td>description</td><td>Customer journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>CustomerJourneyId</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Organization ID  
First included in: interactions/ContactRegisteredToEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization ID</td></tr><tr><td>description</td><td>Organization ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#eventRegistrationId name="eventRegistrationId">eventRegistrationId</a>

eventregistrationid  
First included in: interactions/ContactRegisteredToEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>eventregistrationid</td></tr><tr><td>description</td><td>eventregistrationid</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#interactionType name="interactionType">interactionType</a>

Interaction type  
First included in: interactions/ContactRegisteredToEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interaction type</td></tr><tr><td>description</td><td>Interaction type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#timestamp name="timestamp">timestamp</a>

Timestamp  
First included in: interactions/ContactRegisteredToEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timestamp</td></tr><tr><td>description</td><td>Timestamp</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>
