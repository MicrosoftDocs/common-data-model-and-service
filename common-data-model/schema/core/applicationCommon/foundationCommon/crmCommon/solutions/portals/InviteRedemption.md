---
title: InviteRedemption - Common Data Model | Microsoft Docs
description: Holds information about the redemption of an invite.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Invite Redemption

Holds information about the redemption of an invite.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/InviteRedemption.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/portals/InviteRedemption  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[ownerId](#ownerId)|Owner Id|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[actualEnd](#actualEnd)|Enter the actual end time of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[activityId](#activityId)|Shows the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[isBilled](#isBilled)|Shows whether the activity was billed as part of resolving a case.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[description](#description)|Description of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[activityTypeCode](#activityTypeCode)|Shows the type of activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[activityTypeCode_display](#activityTypeCode_display)||<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[stateCode](#stateCode)|Status of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[stateCode_display](#stateCode_display)||<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[scheduledEnd](#scheduledEnd)|Enter the scheduled end time of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Enter the scheduled duration of the activity, in minutes.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[actualDurationMinutes](#actualDurationMinutes)|Enter the actual duration of the activity in minutes.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[statusCode](#statusCode)|Select the activity's status.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[statusCode_display](#statusCode_display)||<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[actualStart](#actualStart)|Enter the actual start time of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[priorityCode](#priorityCode)|Shows the priority of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[priorityCode_display](#priorityCode_display)||<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[subject](#subject)|Subject associated with the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Shows whether the activity was created from a workflow rule.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[scheduledStart](#scheduledStart)|Enter the scheduled end time of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[instanceTypeCode](#instanceTypeCode)|Shows the type of instance of a recurring series.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[instanceTypeCode_display](#instanceTypeCode_display)||<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[seriesId](#seriesId)|Shows the ID of the recurring series of an instance.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[isRegularActivity](#isRegularActivity)|Shows whether the activity is a regular activity type or event type.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the activitypointer.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the activitypointer with respect to the base currency.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[leftVoiceMail](#leftVoiceMail)|Select if the voice mail was left.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[community](#community)|Shows how contact about the social activity originated, such as from Twitter or Facebook. This field is read-only.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[community_display](#community_display)||<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[isMapiPrivate](#isMapiPrivate)|For internal use only.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[exchangeWebLink](#exchangeWebLink)|Shows the web link of Activity of type email.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[exchangeItemId](#exchangeItemId)|The message id of activity which is returned from Exchange Server.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[deliveryPriorityCode](#deliveryPriorityCode)|Shows the priority of delivery of the activity to the email server.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[deliveryPriorityCode_display](#deliveryPriorityCode_display)||<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[sentOn](#sentOn)|Shows the date and time when the activity was sent.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[deliveryLastAttemptedOn](#deliveryLastAttemptedOn)|Shows the date and time when the delivery of the activity was last attempted.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[senderMailboxId](#senderMailboxId)|Unique identifier of the mailbox associated with the sender of the email message.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[postponeActivityProcessingUntil](#postponeActivityProcessingUntil)|For internal use only.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[processId](#processId)|Shows the process.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[stageId](#stageId)|Shows the stage.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[activityAdditionalParams](#activityAdditionalParams)|Additional information provided by the external application as JSON. For internal use only.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the case record.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this case. This field is for internal use only.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[serviceId](#serviceId)|Unique identifier of an associated service.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[from](#from)|Enter the person who the activity is from.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[to](#to)|Enter the person who is the receiver of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[CC](#CC)|Enter the carbon copy (cc) recipients of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[BCC](#BCC)|Enter the blind carbon copy (bcc) recipients of the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[requiredAttendees](#requiredAttendees)|List of required attendees for the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[optionalAttendees](#optionalAttendees)|List of optional attendees for the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[organizer](#organizer)|Enter the person who organized the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[resources](#resources)|Enter the users or facility/equipment that are required for the activity.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[customers](#customers)|Customer with which the activity is associated.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[partners](#partners)|Shows the outsource vendor who the activity is associated with.|<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|
|[ipAddress](#ipAddress)||<a href="InviteRedemption.md" target="_blank">portals/InviteRedemption</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Enter the actual end time of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Enter the actual end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Shows the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Shows the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Shows whether the activity was billed as part of resolving a case.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Shows whether the activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#description name="description">description</a>

Description of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Shows the type of activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Shows the type of activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#activityTypeCode_display name="activityTypeCode_display">activityTypeCode_display</a>

First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Status</td></tr><tr><td>description</td><td>Status of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr><tr><td>en</td><td>Scheduled</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Enter the scheduled end time of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Enter the scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Enter the scheduled duration of the activity, in minutes.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Enter the scheduled duration of the activity, in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr></table>

### <a href=#actualDurationMinutes name="actualDurationMinutes">actualDurationMinutes</a>

Enter the actual duration of the activity in minutes.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Enter the actual duration of the activity in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the activity's status.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the activity's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Open</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>3</td><td>2</td></tr><tr><td>en</td><td>Scheduled</td><td>4</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Enter the actual start time of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Enter the actual start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Shows the priority of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Shows the priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Shows whether the activity was created from a workflow rule.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Shows whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Enter the scheduled end time of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Enter the scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#instanceTypeCode name="instanceTypeCode">instanceTypeCode</a>

Shows the type of instance of a recurring series.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurring Instance Type</td></tr><tr><td>description</td><td>Shows the type of instance of a recurring series.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>instancetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Recurring</td><td>0</td></tr><tr><td>en</td><td>Recurring Master</td><td>1</td></tr><tr><td>en</td><td>Recurring Instance</td><td>2</td></tr><tr><td>en</td><td>Recurring Exception</td><td>3</td></tr><tr><td>en</td><td>Recurring Future Exception</td><td>4</td></tr></table></td></tr></table>

### <a href=#instanceTypeCode_display name="instanceTypeCode_display">instanceTypeCode_display</a>

First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#seriesId name="seriesId">seriesId</a>

Shows the ID of the recurring series of an instance.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Series ID</td></tr><tr><td>description</td><td>Shows the ID of the recurring series of an instance.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>seriesid</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Shows whether the activity is a regular activity type or event type.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Shows whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the activitypointer.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the activitypointer.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the activitypointer with respect to the base currency.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the activitypointer with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#leftVoiceMail name="leftVoiceMail">leftVoiceMail</a>

Select if the voice mail was left.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Left Voice Mail</td></tr><tr><td>description</td><td>Select if the voice mail was left.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>leftvoicemail</td></tr></table>

### <a href=#community name="community">community</a>

Shows how contact about the social activity originated, such as from Twitter or Facebook. This field is read-only.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Channel</td></tr><tr><td>description</td><td>Shows how contact about the social activity originated, such as from Twitter or Facebook. This field is read-only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>community</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#community_display name="community_display">community_display</a>

First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#isMapiPrivate name="isMapiPrivate">isMapiPrivate</a>

For internal use only.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Private</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ismapiprivate</td></tr></table>

### <a href=#exchangeWebLink name="exchangeWebLink">exchangeWebLink</a>

Shows the web link of Activity of type email.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange WebLink</td></tr><tr><td>description</td><td>Shows the web link of Activity of type email.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeweblink</td></tr></table>

### <a href=#exchangeItemId name="exchangeItemId">exchangeItemId</a>

The message id of activity which is returned from Exchange Server.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Item ID</td></tr><tr><td>description</td><td>The message id of activity which is returned from Exchange Server.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeitemid</td></tr></table>

### <a href=#deliveryPriorityCode name="deliveryPriorityCode">deliveryPriorityCode</a>

Shows the priority of delivery of the activity to the email server.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Priority</td></tr><tr><td>description</td><td>Shows the priority of delivery of the activity to the email server.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryprioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#deliveryPriorityCode_display name="deliveryPriorityCode_display">deliveryPriorityCode_display</a>

First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#sentOn name="sentOn">sentOn</a>

Shows the date and time when the activity was sent.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Sent</td></tr><tr><td>description</td><td>Shows the date and time when the activity was sent.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>senton</td></tr></table>

### <a href=#deliveryLastAttemptedOn name="deliveryLastAttemptedOn">deliveryLastAttemptedOn</a>

Shows the date and time when the delivery of the activity was last attempted.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Delivery Last Attempted</td></tr><tr><td>description</td><td>Shows the date and time when the delivery of the activity was last attempted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliverylastattemptedon</td></tr></table>

### <a href=#senderMailboxId name="senderMailboxId">senderMailboxId</a>

Unique identifier of the mailbox associated with the sender of the email message.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sender's Mailbox</td></tr><tr><td>description</td><td>Unique identifier of the mailbox associated with the sender of the email message.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendermailboxid</td></tr></table>

### <a href=#postponeActivityProcessingUntil name="postponeActivityProcessingUntil">postponeActivityProcessingUntil</a>

For internal use only.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delay activity processing until</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postponeactivityprocessinguntil</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the process.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the stage.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#activityAdditionalParams name="activityAdditionalParams">activityAdditionalParams</a>

Additional information provided by the external application as JSON. For internal use only.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the case record.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the case record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this case. This field is for internal use only.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#serviceId name="serviceId">serviceId</a>

Unique identifier of an associated service.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service</td></tr><tr><td>description</td><td>Unique identifier of an associated service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceid</td></tr></table>

### <a href=#from name="from">from</a>

Enter the person who the activity is from.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Enter the person who the activity is from.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>from</td></tr></table>

### <a href=#to name="to">to</a>

Enter the person who is the receiver of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To</td></tr><tr><td>description</td><td>Enter the person who is the receiver of the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>to</td></tr></table>

### <a href=#CC name="CC">CC</a>

Enter the carbon copy (cc) recipients of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CC</td></tr><tr><td>description</td><td>Enter the carbon copy (cc) recipients of the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cc</td></tr></table>

### <a href=#BCC name="BCC">BCC</a>

Enter the blind carbon copy (bcc) recipients of the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>BCC</td></tr><tr><td>description</td><td>Enter the blind carbon copy (bcc) recipients of the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>bcc</td></tr></table>

### <a href=#requiredAttendees name="requiredAttendees">requiredAttendees</a>

List of required attendees for the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required Attendees</td></tr><tr><td>description</td><td>List of required attendees for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>requiredattendees</td></tr></table>

### <a href=#optionalAttendees name="optionalAttendees">optionalAttendees</a>

List of optional attendees for the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Optional Attendees</td></tr><tr><td>description</td><td>List of optional attendees for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>optionalattendees</td></tr></table>

### <a href=#organizer name="organizer">organizer</a>

Enter the person who organized the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizer</td></tr><tr><td>description</td><td>Enter the person who organized the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizer</td></tr></table>

### <a href=#resources name="resources">resources</a>

Enter the users or facility/equipment that are required for the activity.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resources</td></tr><tr><td>description</td><td>Enter the users or facility/equipment that are required for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resources</td></tr></table>

### <a href=#customers name="customers">customers</a>

Customer with which the activity is associated.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customers</td></tr><tr><td>description</td><td>Customer with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customers</td></tr></table>

### <a href=#partners name="partners">partners</a>

Shows the outsource vendor who the activity is associated with.  
First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outsource Vendors</td></tr><tr><td>description</td><td>Shows the outsource vendor who the activity is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partners</td></tr></table>

### <a href=#ipAddress name="ipAddress">ipAddress</a>

First included in: portals/InviteRedemption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IP Address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_ipaddress</td></tr></table>
