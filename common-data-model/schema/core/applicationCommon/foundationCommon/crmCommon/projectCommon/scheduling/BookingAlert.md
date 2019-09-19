---
title: BookingAlert - Common Data Model | Microsoft Docs
description: Alerts that notify schedule board users of booking issues or information.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Booking Alert

Alerts that notify schedule board users of booking issues or information.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/BookingAlert.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/scheduling/BookingAlert  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[ownerId](#ownerId)|Owner Id|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[actualEnd](#actualEnd)|Shows the actual end time of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[activityId](#activityId)|Unique identifier of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[isBilled](#isBilled)|Information regarding whether the activity was billed as part of resolving a case.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[description](#description)|Type a description of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[activityTypeCode](#activityTypeCode)|Type of activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[activityTypeCode_display](#activityTypeCode_display)||<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[stateCode](#stateCode)|Status of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[stateCode_display](#stateCode_display)||<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[scheduledEnd](#scheduledEnd)|Enter the scheduled end time of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Enter the scheduled duration of the activity, in minutes.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[actualDurationMinutes](#actualDurationMinutes)|Shows the actual duration of the activity in minutes.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[statusCode](#statusCode)|Reason for the status of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[statusCode_display](#statusCode_display)||<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[actualStart](#actualStart)|Shows the actual start time of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[priorityCode](#priorityCode)|Priority of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[priorityCode_display](#priorityCode_display)||<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[regardingObjectIdType](#regardingObjectIdType)||<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[subject](#subject)|Enter the subject associated with the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Information regarding whether the activity was created from a workflow rule.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[scheduledStart](#scheduledStart)|Enter the scheduled start time of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[instanceTypeCode](#instanceTypeCode)|Type of instance of a recurring series.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[instanceTypeCode_display](#instanceTypeCode_display)||<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[seriesId](#seriesId)|Shows the ID of the recurring series of an instance.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[isRegularActivity](#isRegularActivity)|Shows whether the activity is a regular activity type or event type.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the activitypointer.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the activitypointer with respect to the base currency.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[leftVoiceMail](#leftVoiceMail)|Shows whether a voice mail was left.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[community](#community)|For internal use only.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[community_display](#community_display)||<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[isMapiPrivate](#isMapiPrivate)|For internal use only.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[exchangeWebLink](#exchangeWebLink)|Shows the web link of Activity of type email.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[exchangeItemId](#exchangeItemId)|The message id of activity which is returned from Exchange Server.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[deliveryPriorityCode](#deliveryPriorityCode)|Enter the priority of delivery of the activity to the email server.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[deliveryPriorityCode_display](#deliveryPriorityCode_display)||<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[sentOn](#sentOn)|Enter the date and time when the activity was sent.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[deliveryLastAttemptedOn](#deliveryLastAttemptedOn)|Enter the date and time when the delivery of the activity was last attempted.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[senderMailboxId](#senderMailboxId)|Unique identifier of the mailbox associated with the sender of the email message.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[postponeActivityProcessingUntil](#postponeActivityProcessingUntil)|For internal use only.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[processId](#processId)|Shows the process.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[stageId](#stageId)|Shows the stage.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[activityAdditionalParams](#activityAdditionalParams)|Shows additional information provided by the external application as JSON. For internal use only.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the case record.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[SLAInvokedId](#SLAInvokedId)|Shows the last service level agreement (SLA) that was applied to this case. This field is for internal use only.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[serviceId](#serviceId)|Unique identifier of an associated service.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[from](#from)|Shows the person who the activity is from.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[to](#to)|Shows the person who is the receiver of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[CC](#CC)|Enter the carbon-copy (cc) recipients of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[BCC](#BCC)|Enter the blind carbon-copy (bcc) recipients of the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[requiredAttendees](#requiredAttendees)|Shows the list of assignees to be notified by alert.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[optionalAttendees](#optionalAttendees)|Shows the list of optional attendees for the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[organizer](#organizer)|Shows the person who organized the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[resources](#resources)|Shows the users or facility/equipment that are required for the activity.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[customers](#customers)|Enter the customer that the activity is associated with.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|
|[partners](#partners)|Shows the outsource vendor that the activity is associated with.|<a href="BookingAlert.md" target="_blank">scheduling/BookingAlert</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Shows the actual end time of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Shows the actual end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Information regarding whether the activity was billed as part of resolving a case.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#description name="description">description</a>

Type a description of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type a description of the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Type of activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#activityTypeCode_display name="activityTypeCode_display">activityTypeCode_display</a>

First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Status</td></tr><tr><td>description</td><td>Status of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr><tr><td>en</td><td>Scheduled</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Enter the scheduled end time of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Enter the scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Enter the scheduled duration of the activity, in minutes.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Duration</td></tr><tr><td>description</td><td>Enter the scheduled duration of the activity, in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr></table>

### <a href=#actualDurationMinutes name="actualDurationMinutes">actualDurationMinutes</a>

Shows the actual duration of the activity in minutes.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Shows the actual duration of the activity in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Open</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>3</td><td>2</td></tr><tr><td>en</td><td>Scheduled</td><td>4</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Shows the actual start time of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Shows the actual start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Priority of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectIdType name="regardingObjectIdType">regardingObjectIdType</a>

First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#subject name="subject">subject</a>

Enter the subject associated with the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Enter the subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Information regarding whether the activity was created from a workflow rule.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Enter the scheduled start time of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Enter the scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#instanceTypeCode name="instanceTypeCode">instanceTypeCode</a>

Type of instance of a recurring series.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurring Instance Type</td></tr><tr><td>description</td><td>Type of instance of a recurring series.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>instancetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Recurring</td><td>0</td></tr><tr><td>en</td><td>Recurring Master</td><td>1</td></tr><tr><td>en</td><td>Recurring Instance</td><td>2</td></tr><tr><td>en</td><td>Recurring Exception</td><td>3</td></tr><tr><td>en</td><td>Recurring Future Exception</td><td>4</td></tr></table></td></tr></table>

### <a href=#instanceTypeCode_display name="instanceTypeCode_display">instanceTypeCode_display</a>

First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#seriesId name="seriesId">seriesId</a>

Shows the ID of the recurring series of an instance.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Series Id</td></tr><tr><td>description</td><td>Shows the ID of the recurring series of an instance.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>seriesid</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Shows whether the activity is a regular activity type or event type.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Shows whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the activitypointer.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the activitypointer.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the activitypointer with respect to the base currency.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the activitypointer with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#leftVoiceMail name="leftVoiceMail">leftVoiceMail</a>

Shows whether a voice mail was left.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Left Voice Mail</td></tr><tr><td>description</td><td>Shows whether a voice mail was left.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>leftvoicemail</td></tr></table>

### <a href=#community name="community">community</a>

For internal use only.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Channel</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>community</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#community_display name="community_display">community_display</a>

First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#isMapiPrivate name="isMapiPrivate">isMapiPrivate</a>

For internal use only.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Private</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ismapiprivate</td></tr></table>

### <a href=#exchangeWebLink name="exchangeWebLink">exchangeWebLink</a>

Shows the web link of Activity of type email.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange WebLink</td></tr><tr><td>description</td><td>Shows the web link of Activity of type email.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeweblink</td></tr></table>

### <a href=#exchangeItemId name="exchangeItemId">exchangeItemId</a>

The message id of activity which is returned from Exchange Server.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Item ID</td></tr><tr><td>description</td><td>The message id of activity which is returned from Exchange Server.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeitemid</td></tr></table>

### <a href=#deliveryPriorityCode name="deliveryPriorityCode">deliveryPriorityCode</a>

Enter the priority of delivery of the activity to the email server.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Priority</td></tr><tr><td>description</td><td>Enter the priority of delivery of the activity to the email server.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryprioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#deliveryPriorityCode_display name="deliveryPriorityCode_display">deliveryPriorityCode_display</a>

First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#sentOn name="sentOn">sentOn</a>

Enter the date and time when the activity was sent.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Sent</td></tr><tr><td>description</td><td>Enter the date and time when the activity was sent.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>senton</td></tr></table>

### <a href=#deliveryLastAttemptedOn name="deliveryLastAttemptedOn">deliveryLastAttemptedOn</a>

Enter the date and time when the delivery of the activity was last attempted.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Delivery Last Attempted</td></tr><tr><td>description</td><td>Enter the date and time when the delivery of the activity was last attempted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliverylastattemptedon</td></tr></table>

### <a href=#senderMailboxId name="senderMailboxId">senderMailboxId</a>

Unique identifier of the mailbox associated with the sender of the email message.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sender's Mailbox</td></tr><tr><td>description</td><td>Unique identifier of the mailbox associated with the sender of the email message.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendermailboxid</td></tr></table>

### <a href=#postponeActivityProcessingUntil name="postponeActivityProcessingUntil">postponeActivityProcessingUntil</a>

For internal use only.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delay activity processing until</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postponeactivityprocessinguntil</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the process.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the stage.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#activityAdditionalParams name="activityAdditionalParams">activityAdditionalParams</a>

Shows additional information provided by the external application as JSON. For internal use only.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Shows additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the case record.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the case record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Shows the last service level agreement (SLA) that was applied to this case. This field is for internal use only.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Shows the last service level agreement (SLA) that was applied to this case. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#serviceId name="serviceId">serviceId</a>

Unique identifier of an associated service.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service</td></tr><tr><td>description</td><td>Unique identifier of an associated service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceid</td></tr></table>

### <a href=#from name="from">from</a>

Shows the person who the activity is from.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Shows the person who the activity is from.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>from</td></tr></table>

### <a href=#to name="to">to</a>

Shows the person who is the receiver of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To</td></tr><tr><td>description</td><td>Shows the person who is the receiver of the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>to</td></tr></table>

### <a href=#CC name="CC">CC</a>

Enter the carbon-copy (cc) recipients of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CC</td></tr><tr><td>description</td><td>Enter the carbon-copy (cc) recipients of the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cc</td></tr></table>

### <a href=#BCC name="BCC">BCC</a>

Enter the blind carbon-copy (bcc) recipients of the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>BCC</td></tr><tr><td>description</td><td>Enter the blind carbon-copy (bcc) recipients of the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>bcc</td></tr></table>

### <a href=#requiredAttendees name="requiredAttendees">requiredAttendees</a>

Shows the list of assignees to be notified by alert.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assignees</td></tr><tr><td>description</td><td>Shows the list of assignees to be notified by alert.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>requiredattendees</td></tr></table>

### <a href=#optionalAttendees name="optionalAttendees">optionalAttendees</a>

Shows the list of optional attendees for the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Optional Attendees</td></tr><tr><td>description</td><td>Shows the list of optional attendees for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>optionalattendees</td></tr></table>

### <a href=#organizer name="organizer">organizer</a>

Shows the person who organized the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizer</td></tr><tr><td>description</td><td>Shows the person who organized the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizer</td></tr></table>

### <a href=#resources name="resources">resources</a>

Shows the users or facility/equipment that are required for the activity.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resources</td></tr><tr><td>description</td><td>Shows the users or facility/equipment that are required for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resources</td></tr></table>

### <a href=#customers name="customers">customers</a>

Enter the customer that the activity is associated with.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customers</td></tr><tr><td>description</td><td>Enter the customer that the activity is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customers</td></tr></table>

### <a href=#partners name="partners">partners</a>

Shows the outsource vendor that the activity is associated with.  
First included in: scheduling/BookingAlert (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outsource Vendors</td></tr><tr><td>description</td><td>Shows the outsource vendor that the activity is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partners</td></tr></table>
