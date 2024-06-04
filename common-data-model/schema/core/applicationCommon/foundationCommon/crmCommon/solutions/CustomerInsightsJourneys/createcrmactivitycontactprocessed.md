---
title: CreateCrmActivityContactProcessed in CustomerInsightsJourneys - Common Data Model | Microsoft Docs
description: undefined
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/4/2024
ms.author: cdmditeam
---

# CreateCrmActivityContactProcessed in CustomerInsightsJourneys

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/CustomerInsightsJourneys/createcrmactivitycontactprocessed.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or restates parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WorkflowId](#WorkflowId)|Workflow ID|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[CustomerJourneyIterationId](#CustomerJourneyIterationId)|Customer journey iteration ID|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[ProfileId](#ProfileId)|Unique identifier of the profile.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[ProfileType](#ProfileType)|The profile type \(Contact, Lead or CI Profile\)|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[AccountId](#AccountId)|Unique identifier of the Account.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[ActivityId](#ActivityId)|Unique identifier of the Activity.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[ContactId](#ContactId)|Unique identifier of the Contact.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[LeadId](#LeadId)|Unique identifier of the Lead.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[CustomerJourneyId](#CustomerJourneyId)| Unique identifier of the Customer journey|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[BusinessUnitId](#BusinessUnitId)|Unique identifier of the Business unit.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[IdempotencyId](#IdempotencyId)|Idempotency ID defines uniqueness of an analytics event.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[InternalMarketingInteractionId](#InternalMarketingInteractionId)|Internal marketing interaction Id.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[OrganizationId](#OrganizationId)|Organization Id.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[Timestamp](#Timestamp)|Indicates the exact date and time when the interaction was emitted.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[Version](#Version)|Interaction version. Used for updating the interaction.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[SourceSystem](#SourceSystem)| Refers to the source system that generated the interaction. Outbound marketing \(OBM\) is represented by value 1. Any other value than 1 represents Real\x2dtime journeys \(RTJ\).|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|
|[InteractionType](#InteractionType)|Type of the interaction.|<a href="createcrmactivitycontactprocessed.md" target="_blank">CustomerInsightsJourneys/createcrmactivitycontactprocessed</a>|

### <a href=#WorkflowId name="WorkflowId">WorkflowId</a>

Workflow ID  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Workflow ID</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workflow ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#CustomerJourneyIterationId name="CustomerJourneyIterationId">CustomerJourneyIterationId</a>

Customer journey iteration ID  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Customer journey iteration ID</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerJourneyIterationId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.linkedEntity.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Marketing/MarketingSolution/CustomerJourneyIteration.md" target="_blank">/Marketing/MarketingSolution/CustomerJourneyIteration.cdm.json</a></td><td><a href="../Marketing/MarketingSolution/CustomerJourneyIteration.md#customerJourneyIterationId" target="_blank">customerJourneyIterationId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer journey iteration ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ProfileId name="ProfileId">ProfileId</a>

Unique identifier of the profile.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the profile.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the profile.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ProfileType name="ProfileType">ProfileType</a>

The profile type \(Contact, Lead or CI Profile\)  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>The profile type (Contact, Lead or CI Profile)</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileType attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The profile type (Contact, Lead or CI Profile)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#AccountId name="AccountId">AccountId</a>

Unique identifier of the Account.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Account.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.linkedEntity.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/Account.md" target="_blank">/core/applicationCommon/Account.cdm.json/Account</a></td><td><a href="../core/applicationCommon/Account.md#accountId" target="_blank">accountId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Account.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ActivityId name="ActivityId">ActivityId</a>

Unique identifier of the Activity.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Activity.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.linkedEntity.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/Activity.md" target="_blank">/core/applicationCommon/Activity.cdm.json/Activity</a></td><td><a href="../core/applicationCommon/Activity.md#activityId" target="_blank">activityId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Activity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ContactId name="ContactId">ContactId</a>

Unique identifier of the Contact.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Contact.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.linkedEntity.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/Contact.md" target="_blank">/core/applicationCommon/Contact.cdm.json/Contact</a></td><td><a href="../core/applicationCommon/Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Contact.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#LeadId name="LeadId">LeadId</a>

Unique identifier of the Lead.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Lead.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeadId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.linkedEntity.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/foundationCommon/crmCommon/Lead.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/Lead.cdm.json/Lead</a></td><td><a href="../core/applicationCommon/foundationCommon/crmCommon/Lead.md#leadId" target="_blank">leadId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Lead.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#CustomerJourneyId name="CustomerJourneyId">CustomerJourneyId</a>

 Unique identifier of the Customer journey  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td> Unique identifier of the Customer journey</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerJourneyId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td> Unique identifier of the Customer journey</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#BusinessUnitId name="BusinessUnitId">BusinessUnitId</a>

Unique identifier of the Business unit.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Business unit.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessUnitId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.linkedEntity.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../core/applicationCommon/BusinessUnit.md" target="_blank">/core/applicationCommon/BusinessUnit.cdm.json/BusinessUnit</a></td><td><a href="../core/applicationCommon/BusinessUnit.md#businessUnitId" target="_blank">businessUnitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the Business unit.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#IdempotencyId name="IdempotencyId">IdempotencyId</a>

Idempotency ID defines uniqueness of an analytics event.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Idempotency ID defines uniqueness of an analytics event.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdempotencyId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Idempotency ID defines uniqueness of an analytics event.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#InternalMarketingInteractionId name="InternalMarketingInteractionId">InternalMarketingInteractionId</a>

Internal marketing interaction Id.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Internal marketing interaction Id.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalMarketingInteractionId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Internal marketing interaction Id.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#OrganizationId name="OrganizationId">OrganizationId</a>

Organization Id.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Organization Id.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization Id.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#Timestamp name="Timestamp">Timestamp</a>

Indicates the exact date and time when the interaction was emitted.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Indicates the exact date and time when the interaction was emitted.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timestamp attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates the exact date and time when the interaction was emitted.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#Version name="Version">Version</a>

Interaction version. Used for updating the interaction.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Interaction version. Used for updating the interaction.</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interaction version. Used for updating the interaction.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#SourceSystem name="SourceSystem">SourceSystem</a>

 Refers to the source system that generated the interaction. Outbound marketing \(OBM\) is represented by value 1. Any other value than 1 represents Real\x2dtime journeys \(RTJ\).  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td> Refers to the source system that generated the interaction. Outbound marketing (OBM) is represented by value 1. Any other value than 1 represents Real-time journeys (RTJ).</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceSystem attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td> Refers to the source system that generated the interaction. Outbound marketing (OBM) is represented by value 1. Any other value than 1 represents Real-time journeys (RTJ).</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#InteractionType name="InteractionType">InteractionType</a>

Type of the interaction.  
First included in: CustomerInsightsJourneys/createcrmactivitycontactprocessed \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Type of the interaction.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InteractionType attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of the interaction.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>
