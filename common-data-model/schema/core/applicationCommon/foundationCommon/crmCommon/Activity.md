---
title: Activity - Common Data Model | Microsoft Docs
description: This describes the Activity entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Activity

Task performed, or to be performed, by a user. An activity is any action for which an entry can be made on a calendar.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/Activity.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/Activity](../../Activity.md "/core/applicationCommon/Activity.cdm.json/Activity")  
- /foundationCommon/crmCommon/Activity  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[activityTypeCode](#activityTypeCode)|Type of activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[activityId](#activityId)|Unique identifier of the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[isBilled](#isBilled)|Information regarding whether the fax activity was billed as part of resolving a case.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[isRegularActivity](#isRegularActivity)|Information regarding whether the activity is a regular activity type or event type.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Information regarding whether the activity was created from a workflow rule.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[priorityCode](#priorityCode)|Priority of the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[priorityCode_display](#priorityCode_display)||<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[regardingObjectTypeCode](#regardingObjectTypeCode)|The name of the entity linked by regardingObjectId|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[scheduledEnd](#scheduledEnd)|Scheduled end time of the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[scheduledStart](#scheduledStart)|Scheduled start time of the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[subject](#subject)|Subject associated with the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Scheduled duration of the activity, specified in minutes.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[actualDurationMinutes](#actualDurationMinutes)|Actual duration of the activity in minutes.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[actualEnd](#actualEnd)|Actual end time of the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[actualStart](#actualStart)|Actual start time of the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[activityAdditionalParams](#activityAdditionalParams)|Additional information provided by the external application as JSON. For internal use only.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[instanceTypeCode](#instanceTypeCode)|Type of instance of a recurring series.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[instanceTypeCode_display](#instanceTypeCode_display)||<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[isMapiPrivate](#isMapiPrivate)|For internal use only.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[seriesId](#seriesId)|Uniqueidentifier specifying the id of recurring series of an instance.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[sentOn](#sentOn)|Date and time when the activity was sent.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[senderMailboxId](#senderMailboxId)|Unique identifier of the mailbox associated with the sender of the email message.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[deliveryPriorityCode](#deliveryPriorityCode)|Priority of delivery of the activity to the email server.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[deliveryPriorityCode_display](#deliveryPriorityCode_display)||<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[community](#community)|Shows how contact about the activity originated, such as from Twitter or Facebook. This field is read-only.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[community_display](#community_display)||<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[leftVoiceMail](#leftVoiceMail)|Left the voice mail|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[deliveryLastAttemptedOn](#deliveryLastAttemptedOn)|Date and time when the delivery of the activity was last attempted.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[exchangeItemId](#exchangeItemId)|The message id of activity which is returned from Exchange Server.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[exchangeWebLink](#exchangeWebLink)|Shows the web link of Activity of type email.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[postponeActivityProcessingUntil](#postponeActivityProcessingUntil)|For internal use only.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[description](#description)|Description of the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[stateCode](#stateCode)|Status of the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[stateCode_display](#stateCode_display)||<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[statusCode](#statusCode)|Reason for the status of the activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[statusCode_display](#statusCode_display)||<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the activitypointer.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the activitypointer with respect to the base currency.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[allActivityParties](#allActivityParties)|All activity parties associated with this activity.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[processId](#processId)|Unique identifier of the Process.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[stageId](#stageId)|Unique identifier of the Stage.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the case record.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this case. This field is for internal use only.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>|
|[serviceId](#serviceId)|Unique identifier of an associated service.|<a href="Activity.md" target="_blank">crmCommon/Activity</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Type of activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fax</td></tr><tr><td>en</td><td>Phone Call</td></tr><tr><td>en</td><td>Email</td></tr><tr><td>en</td><td>Letter</td></tr><tr><td>en</td><td>Appointment</td></tr><tr><td>en</td><td>Task</td></tr><tr><td>en</td><td>Recurring Appointment</td></tr><tr><td>en</td><td>Quick Campaign</td></tr><tr><td>en</td><td>Campaign Activity</td></tr><tr><td>en</td><td>Campaign Response</td></tr><tr><td>en</td><td>Case Resolution</td></tr><tr><td>en</td><td>Service Activity</td></tr><tr><td>en</td><td>Opportunity Close</td></tr><tr><td>en</td><td>Order Close</td></tr><tr><td>en</td><td>Quote Close</td></tr><tr><td>en</td><td>Alert Subscription</td></tr><tr><td>en</td><td>Invite Redemption</td></tr><tr><td>en</td><td>Portal Comment</td></tr></table></td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Information regarding whether the fax activity was billed as part of resolving a case.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Information regarding whether the activity is a regular activity type or event type.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Information regarding whether the activity was created from a workflow rule.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Priority of the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectTypeCode name="regardingObjectTypeCode">regardingObjectTypeCode</a>

The name of the entity linked by regardingObjectId  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Type</td></tr><tr><td>description</td><td>The name of the entity linked by regardingObjectId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjecttypecode</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Scheduled end time of the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Scheduled start time of the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Scheduled duration of the activity, specified in minutes.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Scheduled duration of the activity, specified in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr></table>

### <a href=#actualDurationMinutes name="actualDurationMinutes">actualDurationMinutes</a>

Actual duration of the activity in minutes.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Actual duration of the activity in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Actual end time of the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Actual end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Actual start time of the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Actual start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#activityAdditionalParams name="activityAdditionalParams">activityAdditionalParams</a>

Additional information provided by the external application as JSON. For internal use only.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr></table>

### <a href=#instanceTypeCode name="instanceTypeCode">instanceTypeCode</a>

Type of instance of a recurring series.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurring Instance Type</td></tr><tr><td>description</td><td>Type of instance of a recurring series.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>instancetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Recurring</td><td>0</td></tr><tr><td>en</td><td>Recurring Master</td><td>1</td></tr><tr><td>en</td><td>Recurring Instance</td><td>2</td></tr><tr><td>en</td><td>Recurring Exception</td><td>3</td></tr><tr><td>en</td><td>Recurring Future Exception</td><td>4</td></tr></table></td></tr></table>

### <a href=#instanceTypeCode_display name="instanceTypeCode_display">instanceTypeCode_display</a>

First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isMapiPrivate name="isMapiPrivate">isMapiPrivate</a>

For internal use only.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Private</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ismapiprivate</td></tr></table>

### <a href=#seriesId name="seriesId">seriesId</a>

Uniqueidentifier specifying the id of recurring series of an instance.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Series Id</td></tr><tr><td>description</td><td>Uniqueidentifier specifying the id of recurring series of an instance.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>seriesid</td></tr></table>

### <a href=#sentOn name="sentOn">sentOn</a>

Date and time when the activity was sent.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Sent</td></tr><tr><td>description</td><td>Date and time when the activity was sent.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>senton</td></tr></table>

### <a href=#senderMailboxId name="senderMailboxId">senderMailboxId</a>

Unique identifier of the mailbox associated with the sender of the email message.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sender's Mailbox</td></tr><tr><td>description</td><td>Unique identifier of the mailbox associated with the sender of the email message.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendermailboxid</td></tr></table>

### <a href=#deliveryPriorityCode name="deliveryPriorityCode">deliveryPriorityCode</a>

Priority of delivery of the activity to the email server.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Priority</td></tr><tr><td>description</td><td>Priority of delivery of the activity to the email server.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryprioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#deliveryPriorityCode_display name="deliveryPriorityCode_display">deliveryPriorityCode_display</a>

First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#community name="community">community</a>

Shows how contact about the activity originated, such as from Twitter or Facebook. This field is read-only.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Channel</td></tr><tr><td>description</td><td>Shows how contact about the activity originated, such as from Twitter or Facebook. This field is read-only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>community</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Facebook</td><td>1</td></tr><tr><td>en</td><td>Twitter</td><td>2</td></tr><tr><td>en</td><td>Other</td><td>0</td></tr></table></td></tr></table>

### <a href=#community_display name="community_display">community_display</a>

First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#leftVoiceMail name="leftVoiceMail">leftVoiceMail</a>

Left the voice mail  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Left Voice Mail</td></tr><tr><td>description</td><td>Left the voice mail</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>leftvoicemail</td></tr></table>

### <a href=#deliveryLastAttemptedOn name="deliveryLastAttemptedOn">deliveryLastAttemptedOn</a>

Date and time when the delivery of the activity was last attempted.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Delivery Last Attempted</td></tr><tr><td>description</td><td>Date and time when the delivery of the activity was last attempted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliverylastattemptedon</td></tr></table>

### <a href=#exchangeItemId name="exchangeItemId">exchangeItemId</a>

The message id of activity which is returned from Exchange Server.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Item ID</td></tr><tr><td>description</td><td>The message id of activity which is returned from Exchange Server.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeitemid</td></tr></table>

### <a href=#exchangeWebLink name="exchangeWebLink">exchangeWebLink</a>

Shows the web link of Activity of type email.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange WebLink</td></tr><tr><td>description</td><td>Shows the web link of Activity of type email.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeweblink</td></tr></table>

### <a href=#postponeActivityProcessingUntil name="postponeActivityProcessingUntil">postponeActivityProcessingUntil</a>

For internal use only.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delay activity processing until</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postponeactivityprocessinguntil</td></tr></table>

### <a href=#description name="description">description</a>

Description of the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Status</td></tr><tr><td>description</td><td>Status of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr><tr><td>en</td><td>Scheduled</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Open</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>3</td><td>2</td></tr><tr><td>en</td><td>Scheduled</td><td>4</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the activitypointer.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the activitypointer.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the activitypointer with respect to the base currency.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the activitypointer with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#allActivityParties name="allActivityParties">allActivityParties</a>

All activity parties associated with this activity.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>All Activity Parties</td></tr><tr><td>description</td><td>All activity parties associated with this activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>allparties</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#processId name="processId">processId</a>

Unique identifier of the Process.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Unique identifier of the Process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Unique identifier of the Stage.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Unique identifier of the Stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the case record.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the case record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this case. This field is for internal use only.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: <a href="../../Activity.md" target="_blank">applicationCommon/Activity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#serviceId name="serviceId">serviceId</a>

Unique identifier of an associated service.  
First included in: crmCommon/Activity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service</td></tr><tr><td>description</td><td>Unique identifier of an associated service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceid</td></tr></table>
