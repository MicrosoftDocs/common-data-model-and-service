---
title: ActivityParty - Common Data Model | Microsoft Docs
description: Person or group associated with an activity. An activity can have multiple activity parties.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Activity Party

Person or group associated with an activity. An activity can have multiple activity parties.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/ActivityParty.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/ActivityParty](../../../ActivityParty.md "/core/applicationCommon/ActivityParty.cdm.json/ActivityParty")  
- /foundationCommon/crmCommon/service/ActivityParty  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[activityId](#activityId)|Unique identifier of the activity associated with the activity party. (A "party" is any person who is associated with an activity.)|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[activityPartyId](#activityPartyId)|Unique identifier of the activity party.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[partyObjectTypeCode](#partyObjectTypeCode)|The name of the entity linked by partyId|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[partyId](#partyId)|Unique identifier of the party associated with the activity.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[participationTypeMask](#participationTypeMask)|Role of the person in the activity, such as sender, to, cc, bcc, required, optional, organizer, regarding, or owner.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[participationTypeMask_display](#participationTypeMask_display)||<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[addressUsed](#addressUsed)|Email address to which an email is delivered, and which is associated with the target entity.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[doNotFax](#doNotFax)|Information about whether to allow sending faxes to the activity party.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[scheduledStart](#scheduledStart)|Scheduled start time of the activity.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[scheduledEnd](#scheduledEnd)|Scheduled end time of the activity.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[effort](#effort)|Amount of effort used by the resource in a service appointment activity.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[doNotEMail](#doNotEMail)|Information about whether to allow sending email to the activity party.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[exchangeEntryId](#exchangeEntryId)|For internal use only.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[versionNumber](#versionNumber)||<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[doNotPostalMail](#doNotPostalMail)|Information about whether to allow sending postal mail to the lead.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[doNotPhone](#doNotPhone)|Information about whether to allow phone calls to the lead.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[instanceTypeCode](#instanceTypeCode)|Type of instance of a recurring series.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[instanceTypeCode_display](#instanceTypeCode_display)||<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[isPartyDeleted](#isPartyDeleted)|Information about whether the underlying entity record is deleted.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[addressUsedEmailColumnNumber](#addressUsedEmailColumnNumber)|Email address column number from associated party.|<a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>|
|[resourceSpecId](#resourceSpecId)|Unique identifier of the resource specification for the activity party.|<a href="ActivityParty.md" target="_blank">service/ActivityParty</a>|

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity associated with the activity party. (A "party" is any person who is associated with an activity.)  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity associated with the activity party. (A "party" is any person who is associated with an activity.)</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#activityPartyId name="activityPartyId">activityPartyId</a>

Unique identifier of the activity party.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Party</td></tr><tr><td>description</td><td>Unique identifier of the activity party.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activitypartyid</td></tr></table>

### <a href=#partyObjectTypeCode name="partyObjectTypeCode">partyObjectTypeCode</a>

The name of the entity linked by partyId  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>partyId Type</td></tr><tr><td>description</td><td>The name of the entity linked by partyId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>partyobjecttypecode</td></tr></table>

### <a href=#partyId name="partyId">partyId</a>

Unique identifier of the party associated with the activity.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Party</td></tr><tr><td>description</td><td>Unique identifier of the party associated with the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partyid</td></tr></table>

### <a href=#participationTypeMask name="participationTypeMask">participationTypeMask</a>

Role of the person in the activity, such as sender, to, cc, bcc, required, optional, organizer, regarding, or owner.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participation Type</td></tr><tr><td>description</td><td>Role of the person in the activity, such as sender, to, cc, bcc, required, optional, organizer, regarding, or owner.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>participationtypemask</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Sender</td><td>1</td></tr><tr><td>en</td><td>To Recipient</td><td>2</td></tr><tr><td>en</td><td>CC Recipient</td><td>3</td></tr><tr><td>en</td><td>BCC Recipient</td><td>4</td></tr><tr><td>en</td><td>Required attendee</td><td>5</td></tr><tr><td>en</td><td>Optional attendee</td><td>6</td></tr><tr><td>en</td><td>Organizer</td><td>7</td></tr><tr><td>en</td><td>Regarding</td><td>8</td></tr><tr><td>en</td><td>Owner</td><td>9</td></tr><tr><td>en</td><td>Resource</td><td>10</td></tr><tr><td>en</td><td>Customer</td><td>11</td></tr></table></td></tr></table>

### <a href=#participationTypeMask_display name="participationTypeMask_display">participationTypeMask_display</a>

First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#addressUsed name="addressUsed">addressUsed</a>

Email address to which an email is delivered, and which is associated with the target entity.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address </td></tr><tr><td>description</td><td>Email address to which an email is delivered, and which is associated with the target entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addressused</td></tr></table>

### <a href=#doNotFax name="doNotFax">doNotFax</a>

Information about whether to allow sending faxes to the activity party.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Faxes</td></tr><tr><td>description</td><td>Information about whether to allow sending faxes to the activity party.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotfax</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Scheduled start time of the activity.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Start</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Scheduled end time of the activity.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled End</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#effort name="effort">effort</a>

Amount of effort used by the resource in a service appointment activity.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effort</td></tr><tr><td>description</td><td>Amount of effort used by the resource in a service appointment activity.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>effort</td></tr></table>

### <a href=#doNotEMail name="doNotEMail">doNotEMail</a>

Information about whether to allow sending email to the activity party.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Emails</td></tr><tr><td>description</td><td>Information about whether to allow sending email to the activity party.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotemail</td></tr></table>

### <a href=#exchangeEntryId name="exchangeEntryId">exchangeEntryId</a>

For internal use only.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Entry</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeentryid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#doNotPostalMail name="doNotPostalMail">doNotPostalMail</a>

Information about whether to allow sending postal mail to the lead.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Postal Mails</td></tr><tr><td>description</td><td>Information about whether to allow sending postal mail to the lead.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotpostalmail</td></tr></table>

### <a href=#doNotPhone name="doNotPhone">doNotPhone</a>

Information about whether to allow phone calls to the lead.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Phone Calls</td></tr><tr><td>description</td><td>Information about whether to allow phone calls to the lead.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotphone</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#instanceTypeCode name="instanceTypeCode">instanceTypeCode</a>

Type of instance of a recurring series.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment Type</td></tr><tr><td>description</td><td>Type of instance of a recurring series.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>instancetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Recurring</td><td>0</td></tr><tr><td>en</td><td>Recurring Master</td><td>1</td></tr><tr><td>en</td><td>Recurring Instance</td><td>2</td></tr><tr><td>en</td><td>Recurring Exception</td><td>3</td></tr><tr><td>en</td><td>Recurring Future Exception</td><td>4</td></tr></table></td></tr></table>

### <a href=#instanceTypeCode_display name="instanceTypeCode_display">instanceTypeCode_display</a>

First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isPartyDeleted name="isPartyDeleted">isPartyDeleted</a>

Information about whether the underlying entity record is deleted.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Party Deleted</td></tr><tr><td>description</td><td>Information about whether the underlying entity record is deleted.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ispartydeleted</td></tr></table>

### <a href=#addressUsedEmailColumnNumber name="addressUsedEmailColumnNumber">addressUsedEmailColumnNumber</a>

Email address column number from associated party.  
First included in: <a href="../../../ActivityParty.md" target="_blank">applicationCommon/ActivityParty</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email column number of party</td></tr><tr><td>description</td><td>Email address column number from associated party.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addressusedemailcolumnnumber</td></tr></table>

### <a href=#resourceSpecId name="resourceSpecId">resourceSpecId</a>

Unique identifier of the resource specification for the activity party.  
First included in: service/ActivityParty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Specification</td></tr><tr><td>description</td><td>Unique identifier of the resource specification for the activity party.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resourcespecid</td></tr></table>
