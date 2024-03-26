---
title: EmailContainsBlacklistedLinks in CustomerInsightsJourneys - Common Data Model | Microsoft Docs
description: undefined
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 3/26/2024
ms.author: cdmditeam
---

# EmailContainsBlacklistedLinks in CustomerInsightsJourneys

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/CustomerInsightsJourneys/emailcontainsblacklistedlinks.cdm.json" target="_blank">GitHub</a>.  

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
|[BlacklistedLink](#BlacklistedLink)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[MessageId](#MessageId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[SendingId](#SendingId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[UsageType](#UsageType)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[CustomerJourneyIterationId](#CustomerJourneyIterationId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[ProfileId](#ProfileId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[ProfileType](#ProfileType)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[AccountId](#AccountId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[ActivityId](#ActivityId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[ContactId](#ContactId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[LeadId](#LeadId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[CustomerJourneyId](#CustomerJourneyId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[BusinessUnitId](#BusinessUnitId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[IdempotencyId](#IdempotencyId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[InternalMarketingInteractionId](#InternalMarketingInteractionId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[OrganizationId](#OrganizationId)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[Timestamp](#Timestamp)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[Version](#Version)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[SourceSystem](#SourceSystem)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|
|[InteractionType](#InteractionType)||<a href="emailcontainsblacklistedlinks.md" target="_blank">CustomerInsightsJourneys/emailcontainsblacklistedlinks</a>|

### <a href=#BlacklistedLink name="BlacklistedLink">BlacklistedLink</a>

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlacklistedLink attribute are listed below.</summary>

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

### <a href=#LeadId name="LeadId">LeadId</a>

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

### <a href=#CustomerJourneyId name="CustomerJourneyId">CustomerJourneyId</a>

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../BusinessUnit.md" target="_blank">BusinessUnit.cdm.json/BusinessUnit</a></td><td><a href="../../BusinessUnit.md#businessUnitId" target="_blank">businessUnitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#IdempotencyId name="IdempotencyId">IdempotencyId</a>

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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

First included in: CustomerInsightsJourneys/emailcontainsblacklistedlinks \(this entity\)  

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
