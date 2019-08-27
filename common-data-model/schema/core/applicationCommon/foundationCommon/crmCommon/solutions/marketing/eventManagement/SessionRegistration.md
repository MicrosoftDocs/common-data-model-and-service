---
title: SessionRegistration - Common Data Model | Microsoft Docs
description: This describes the SessionRegistration entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Session Registration

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/SessionRegistration.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/SessionRegistration  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[ownerId](#ownerId)|Owner Id|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[sessionRegistrationId](#sessionRegistrationId)|Unique identifier for entity instances|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[stateCode](#stateCode)|Status of the Session Registration|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[stateCode_display](#stateCode_display)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[statusCode](#statusCode)|Reason for the status of the Session Registration|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[statusCode_display](#statusCode_display)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[name](#name)|The name of the custom entity.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[contactId](#contactId)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[event](#event)|Active Events records|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[isCanceled](#isCanceled)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[publishingState](#publishingState)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[publishingState_display](#publishingState_display)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[registrationId](#registrationId)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[registrationNotificationSeen](#registrationNotificationSeen)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[registrationStatus](#registrationStatus)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[sessionId](#sessionId)|Unique identifier for Session associated with Session Registration.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[syncedWithProvider](#syncedWithProvider)|A flag that indicates that the registration was synced with provider|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[syncedWithProvider_display](#syncedWithProvider_display)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[timesCheckedIn](#timesCheckedIn)||<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|
|[webinarRegistrationID](#webinarRegistrationID)|Webinar ID of the Session Registration.|<a href="SessionRegistration.md" target="_blank">eventManagement/SessionRegistration</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#sessionRegistrationId name="sessionRegistrationId">sessionRegistrationId</a>

Unique identifier for entity instances  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Registration</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionregistrationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Session Registration  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Session Registration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Session Registration  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Session Registration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration ID</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_contactid</td></tr></table>

### <a href=#event name="event">event</a>

Active Events records  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Active Events records</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_event</td></tr></table>

### <a href=#isCanceled name="isCanceled">isCanceled</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Canceled</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_iscanceled</td></tr></table>

### <a href=#publishingState name="publishingState">publishingState</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publishing State</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_publishingstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pending</td><td>100000000</td></tr><tr><td>en</td><td>Published</td><td>100000001</td></tr><tr><td>en</td><td>ParentWebinarFailed</td><td>100000002</td></tr><tr><td>en</td><td>FailedToPublish</td><td>100000003</td></tr><tr><td>en</td><td>WebinarProviderError</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#publishingState_display name="publishingState_display">publishingState_display</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#registrationId name="registrationId">registrationId</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Registration ID</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationid</td></tr></table>

### <a href=#registrationNotificationSeen name="registrationNotificationSeen">registrationNotificationSeen</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Notification Seen</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationnotificationseen</td></tr></table>

### <a href=#registrationStatus name="registrationStatus">registrationStatus</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationstatus</td></tr></table>

### <a href=#sessionId name="sessionId">sessionId</a>

Unique identifier for Session associated with Session Registration.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session</td></tr><tr><td>description</td><td>Unique identifier for Session associated with Session Registration.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionid</td></tr></table>

### <a href=#syncedWithProvider name="syncedWithProvider">syncedWithProvider</a>

A flag that indicates that the registration was synced with provider  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Synced with Provider</td></tr><tr><td>description</td><td>A flag that indicates that the registration was synced with provider</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_syncedwithprovider</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>100000001</td></tr><tr><td>en</td><td>Yes</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#syncedWithProvider_display name="syncedWithProvider_display">syncedWithProvider_display</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#timesCheckedIn name="timesCheckedIn">timesCheckedIn</a>

First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Times Checked-in</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_timescheckedin</td></tr></table>

### <a href=#webinarRegistrationID name="webinarRegistrationID">webinarRegistrationID</a>

Webinar ID of the Session Registration.  
First included in: eventManagement/SessionRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Registration ID</td></tr><tr><td>description</td><td>Webinar ID of the Session Registration.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarregistrationid</td></tr></table>
