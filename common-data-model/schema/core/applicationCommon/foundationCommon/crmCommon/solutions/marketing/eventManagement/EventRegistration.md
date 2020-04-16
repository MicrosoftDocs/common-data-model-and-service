---
title: EventRegistration - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# Event Registration

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/EventRegistration.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsCreationModificationDatesAndIds</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsOwnershipInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsTimeZoneInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsVersionTracking</td></tr><tr><td>/core/applicationCommon/foundationCommon<br>/crmCommon/solutions/marketing/eventManagement<br>/EventRegistration.cdm.json/EventRegistration<br>/hasAttributes/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EventRegistration/(resolvedAttributes)/eventRegistrationId](#eventRegistrationId)</td><td>attribute</td><td></td></tr></table>

**means.entityState**  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EventRegistration/(resolvedAttributes)/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Event Registration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_EventRegistration"</td><td>string</td><td></td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[ownerId](#ownerId)|Owner Id|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[eventRegistrationId](#eventRegistrationId)|Unique identifier for entity instances|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[stateCode](#stateCode)|Status of the Event Registration|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[stateCode_display](#stateCode_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[statusCode](#statusCode)|Reason for the status of the Event Registration|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[statusCode_display](#statusCode_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[name](#name)|The name of the custom entity.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[area](#area)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[area_display](#area_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[companySize](#companySize)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[companySize_display](#companySize_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[contactId](#contactId)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[eventId](#eventId)|Unique identifier for Event associated with Event Registration.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[industry](#industry)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[industry_display](#industry_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[isCanceled](#isCanceled)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[memo](#memo)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[primaryRole](#primaryRole)|Primary Role of the event attendee.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[primaryRole_display](#primaryRole_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[publishingState](#publishingState)|The publishing state of the event registration.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[publishingState_display](#publishingState_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[registeredBy](#registeredBy)|A lookup to the contact who created this event registration|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[registrationNotificationSeen](#registrationNotificationSeen)|Whether the registration creation notification has been seen or not|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[registrationStatus](#registrationStatus)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[syncedWithProvider](#syncedWithProvider)|A flag that indicates that the registration was synced with provider|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[syncedWithProvider_display](#syncedWithProvider_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[timesCheckedIn](#timesCheckedIn)|Hidden field. Number of Event Check-ins related to this ER.
Used as partial aggregation for Check-in count of Event.
Increasing and decreasing done by corresponding workflows.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[webinarRegistrationID](#webinarRegistrationID)|Webinar ID of the Event Registration.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[yearsInIndustry](#yearsInIndustry)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[yearsInIndustry_display](#yearsInIndustry_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**means.measurement.date.creation**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**means.measurement.date.modify**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOnBehalfBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdonbehalfby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOnBehalfBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedonbehalfby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**means.measurement.date.creation**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr><tr><td><a href="../../../../../Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../../Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"ownerid"</td><td>string</td><td></td></tr></table>

**is.CDS.owner**  
contains a User or Team ID  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerIdType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.entityName**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of owner, either User or Team.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.name**  
Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.  

**is.readOnly**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owneridtype"</td><td>string</td><td></td></tr></table>

**is.CDS.owner**  
contains a User or Team ID  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningBusinessUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Business Unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../BusinessUnit.md" target="_blank">/core/applicationCommon/BusinessUnit.cdm.json/BusinessUnit</a></td><td><a href="../../../../../BusinessUnit.md#businessUnitId" target="_blank">businessUnitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owningbusinessunit"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning User</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>en</td><td>Unique identifier of the user that owns the activity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owninguser"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningTeam attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Team</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../../Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owningteam"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"timezoneruleversionnumber"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"utcconversiontimezonecode"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>3</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the versionNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**means.measurement.version**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"versionnumber"</td><td>string</td><td></td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#eventRegistrationId name="eventRegistrationId">eventRegistrationId</a>

Unique identifier for entity instances  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Registration</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>sourceName</td><td>msevtmgt_eventregistrationid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the eventRegistrationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EventRegistration/(resolvedAttributes)/eventRegistrationId](#eventRegistrationId)</td><td>attribute</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Event Registration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_eventregistrationid"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"1"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Event Registration  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Event Registration</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**means.entityState**  
the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EventRegistration/(resolvedAttributes)/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the Event Registration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statecode"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"24"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"stateCode"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Event Registration  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Event Registration</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.correlatedWith**  
the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>"stateCode"</td><td>attributeName</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for the status of the Event Registration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statuscode"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"26"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"statusCode"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration ID</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.identity.name**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"required"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Registration ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the custom entity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_name"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"33"</td><td>integer</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#area name="area">area</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Area</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_area</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Administration</td><td>100000000</td></tr><tr><td>en</td><td>Customer Service</td><td>100000001</td></tr><tr><td>en</td><td>Executive/Management</td><td>100000002</td></tr><tr><td>en</td><td>Logistics</td><td>100000003</td></tr><tr><td>en</td><td>Finance</td><td>100000004</td></tr><tr><td>en</td><td>HR</td><td>100000005</td></tr><tr><td>en</td><td>IT</td><td>100000006</td></tr><tr><td>en</td><td>Legal</td><td>100000007</td></tr><tr><td>en</td><td>Marketing</td><td>100000008</td></tr><tr><td>en</td><td>Sales</td><td>100000009</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the area attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Administration</td><td>100000000</td></tr><tr><td>en</td><td>Customer Service</td><td>100000001</td></tr><tr><td>en</td><td>Executive/Management</td><td>100000002</td></tr><tr><td>en</td><td>Logistics</td><td>100000003</td></tr><tr><td>en</td><td>Finance</td><td>100000004</td></tr><tr><td>en</td><td>HR</td><td>100000005</td></tr><tr><td>en</td><td>IT</td><td>100000006</td></tr><tr><td>en</td><td>Legal</td><td>100000007</td></tr><tr><td>en</td><td>Marketing</td><td>100000008</td></tr><tr><td>en</td><td>Sales</td><td>100000009</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Area</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_area"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"34"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#area_display name="area_display">area_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the area_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"area"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#companySize name="companySize">companySize</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Size</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_companysize</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>50 or less</td><td>100000000</td></tr><tr><td>en</td><td>51 to 100</td><td>100000001</td></tr><tr><td>en</td><td>101 to 250</td><td>100000002</td></tr><tr><td>en</td><td>251 to 500</td><td>100000003</td></tr><tr><td>en</td><td>501 to 1000</td><td>100000004</td></tr><tr><td>en</td><td>1001 to 2500</td><td>100000005</td></tr><tr><td>en</td><td>2501 to 5000</td><td>100000006</td></tr><tr><td>en</td><td>5001 to 10000</td><td>100000007</td></tr><tr><td>en</td><td>10001 or more</td><td>100000008</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the companySize attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>50 or less</td><td>100000000</td></tr><tr><td>en</td><td>51 to 100</td><td>100000001</td></tr><tr><td>en</td><td>101 to 250</td><td>100000002</td></tr><tr><td>en</td><td>251 to 500</td><td>100000003</td></tr><tr><td>en</td><td>501 to 1000</td><td>100000004</td></tr><tr><td>en</td><td>1001 to 2500</td><td>100000005</td></tr><tr><td>en</td><td>2501 to 5000</td><td>100000006</td></tr><tr><td>en</td><td>5001 to 10000</td><td>100000007</td></tr><tr><td>en</td><td>10001 or more</td><td>100000008</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company Size</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_companysize"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"36"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#companySize_display name="companySize_display">companySize_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the companySize_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"companySize"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#contactId name="contactId">contactId</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_contactid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contactId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"required"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contact</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Contact.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Contact.cdm.json/Contact</a></td><td><a href="../Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_contactid"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"38"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#eventId name="eventId">eventId</a>

Unique identifier for Event associated with Event Registration.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Unique identifier for Event associated with Event Registration.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the eventId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"required"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Event</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for Event associated with Event Registration.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Event.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/Event.cdm.json/Event</a></td><td><a href="Event.md#eventId" target="_blank">eventId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_eventid"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"39"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#industry name="industry">industry</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Industry</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_industry</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Architecture and Engineering</td><td>100000000</td></tr><tr><td>en</td><td>Financial Services</td><td>100000001</td></tr><tr><td>en</td><td>Manufacturing</td><td>100000002</td></tr><tr><td>en</td><td>Media, Entertainment</td><td>100000003</td></tr><tr><td>en</td><td>Professional Services</td><td>100000004</td></tr><tr><td>en</td><td>Public Sector</td><td>100000005</td></tr><tr><td>en</td><td>Retail</td><td>100000006</td></tr><tr><td>en</td><td>Wholesale and Distribution</td><td>100000007</td></tr><tr><td>en</td><td>Other</td><td>100000008</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the industry attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Architecture and Engineering</td><td>100000000</td></tr><tr><td>en</td><td>Financial Services</td><td>100000001</td></tr><tr><td>en</td><td>Manufacturing</td><td>100000002</td></tr><tr><td>en</td><td>Media, Entertainment</td><td>100000003</td></tr><tr><td>en</td><td>Professional Services</td><td>100000004</td></tr><tr><td>en</td><td>Public Sector</td><td>100000005</td></tr><tr><td>en</td><td>Retail</td><td>100000006</td></tr><tr><td>en</td><td>Wholesale and Distribution</td><td>100000007</td></tr><tr><td>en</td><td>Other</td><td>100000008</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Industry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_industry"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"40"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#industry_display name="industry_display">industry_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the industry_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"industry"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#isCanceled name="isCanceled">isCanceled</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Canceled</td></tr><tr><td>dataFormat</td><td>15</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_iscanceled</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isCanceled attribute are listed below.</summary>

**is.dataFormat.boolean**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is Canceled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_iscanceled"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"42"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.boolean**  
</details>

### <a href=#memo name="memo">memo</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Memo</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_memo</td></tr></table>

#### Traits

<details>
<summary>List of traits for the memo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Memo</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_memo"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"44"</td><td>integer</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#primaryRole name="primaryRole">primaryRole</a>

Primary Role of the event attendee.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Role</td></tr><tr><td>description</td><td>Primary Role of the event attendee.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_primaryrole</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Attendee</td><td>100000000</td></tr><tr><td>en</td><td>Journalist</td><td>100000001</td></tr><tr><td>en</td><td>Other</td><td>100000002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the primaryRole attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Attendee</td><td>100000000</td></tr><tr><td>en</td><td>Journalist</td><td>100000001</td></tr><tr><td>en</td><td>Other</td><td>100000002</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"recommended"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary Role</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary Role of the event attendee.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_primaryrole"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"45"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#primaryRole_display name="primaryRole_display">primaryRole_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the primaryRole_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"primaryRole"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#publishingState name="publishingState">publishingState</a>

The publishing state of the event registration.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publishing State</td></tr><tr><td>description</td><td>The publishing state of the event registration.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_publishingstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pending</td><td>100000000</td></tr><tr><td>en</td><td>Published</td><td>100000001</td></tr><tr><td>en</td><td>ParentWebinarFailed</td><td>100000002</td></tr><tr><td>en</td><td>FailedToPublish</td><td>100000003</td></tr><tr><td>en</td><td>WebinarProviderError</td><td>100000004</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the publishingState attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pending</td><td>100000000</td></tr><tr><td>en</td><td>Published</td><td>100000001</td></tr><tr><td>en</td><td>ParentWebinarFailed</td><td>100000002</td></tr><tr><td>en</td><td>FailedToPublish</td><td>100000003</td></tr><tr><td>en</td><td>WebinarProviderError</td><td>100000004</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Publishing State</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The publishing state of the event registration.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_publishingstate"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"47"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#publishingState_display name="publishingState_display">publishingState_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the publishingState_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"publishingState"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#registeredBy name="registeredBy">registeredBy</a>

A lookup to the contact who created this event registration  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registered By</td></tr><tr><td>description</td><td>A lookup to the contact who created this event registration</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registeredby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the registeredBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Registered By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A lookup to the contact who created this event registration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_registeredby"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"49"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#registrationNotificationSeen name="registrationNotificationSeen">registrationNotificationSeen</a>

Whether the registration creation notification has been seen or not  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Notification Seen</td></tr><tr><td>description</td><td>Whether the registration creation notification has been seen or not</td></tr><tr><td>dataFormat</td><td>15</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationnotificationseen</td></tr></table>

#### Traits

<details>
<summary>List of traits for the registrationNotificationSeen attribute are listed below.</summary>

**is.dataFormat.boolean**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Registration Notification Seen</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Whether the registration creation notification has been seen or not</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_registrationnotificationseen"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"50"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.boolean**  
</details>

### <a href=#registrationStatus name="registrationStatus">registrationStatus</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Status</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationstatus</td></tr></table>

#### Traits

<details>
<summary>List of traits for the registrationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Registration Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_registrationstatus"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"52"</td><td>integer</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#syncedWithProvider name="syncedWithProvider">syncedWithProvider</a>

A flag that indicates that the registration was synced with provider  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Synced with Provider</td></tr><tr><td>description</td><td>A flag that indicates that the registration was synced with provider</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_syncedwithprovider</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>100000001</td></tr><tr><td>en</td><td>Yes</td><td>100000002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the syncedWithProvider attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>100000001</td></tr><tr><td>en</td><td>Yes</td><td>100000002</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Synced with Provider</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A flag that indicates that the registration was synced with provider</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_syncedwithprovider"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"53"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#syncedWithProvider_display name="syncedWithProvider_display">syncedWithProvider_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the syncedWithProvider_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"syncedWithProvider"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#timesCheckedIn name="timesCheckedIn">timesCheckedIn</a>

Hidden field. Number of Event Check-ins related to this ER.
Used as partial aggregation for Check-in count of Event.
Increasing and decreasing done by corresponding workflows.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Times Checked-in</td></tr><tr><td>description</td><td>Hidden field. Number of Event Check-ins related to this ER.
Used as partial aggregation for Check-in count of Event.
Increasing and decreasing done by corresponding workflows.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_timescheckedin</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timesCheckedIn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Times Checked-in</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Hidden field. Number of Event Check-ins related to this ER.
Used as partial aggregation for Check-in count of Event.
Increasing and decreasing done by corresponding workflows.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_timescheckedin"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"55"</td><td>integer</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#webinarRegistrationID name="webinarRegistrationID">webinarRegistrationID</a>

Webinar ID of the Event Registration.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Registration ID</td></tr><tr><td>description</td><td>Webinar ID of the Event Registration.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarregistrationid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the webinarRegistrationID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Webinar Registration ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Webinar ID of the Event Registration.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_webinarregistrationid"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"56"</td><td>integer</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#yearsInIndustry name="yearsInIndustry">yearsInIndustry</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Years in Industry</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_yearsinindustry</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Under 1 year</td><td>100000000</td></tr><tr><td>en</td><td>1 to 5 year</td><td>100000001</td></tr><tr><td>en</td><td>5 to 10 years</td><td>100000002</td></tr><tr><td>en</td><td>Over 10 years</td><td>100000003</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the yearsInIndustry attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Under 1 year</td><td>100000000</td></tr><tr><td>en</td><td>1 to 5 year</td><td>100000001</td></tr><tr><td>en</td><td>5 to 10 years</td><td>100000002</td></tr><tr><td>en</td><td>Over 10 years</td><td>100000003</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Years in Industry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msevtmgt_yearsinindustry"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"57"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#yearsInIndustry_display name="yearsInIndustry_display">yearsInIndustry_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the yearsInIndustry_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"yearsInIndustry"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
