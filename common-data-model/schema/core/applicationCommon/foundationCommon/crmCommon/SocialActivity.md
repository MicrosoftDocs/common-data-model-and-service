---
title: SocialActivity - Common Data Model | Microsoft Docs
description: For internal use only.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Social Activity

For internal use only.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/SocialActivity.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/SocialActivity](../../SocialActivity.md "/core/applicationCommon/SocialActivity.cdm.json/SocialActivity")  
- /foundationCommon/crmCommon/SocialActivity  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[activityTypeCode](#activityTypeCode)|Type of activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[activityId](#activityId)|Unique identifier of the activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[isBilled](#isBilled)|Information regarding whether the fax activity was billed as part of resolving a case.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[isRegularActivity](#isRegularActivity)|Information regarding whether the activity is a regular activity type or event type.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Information regarding whether the activity was created from a workflow rule.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[priorityCode](#priorityCode)|Priority of the activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[priorityCode_display](#priorityCode_display)||<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[regardingObjectTypeCode](#regardingObjectTypeCode)|The name of the entity linked by regardingObjectId|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[scheduledEnd](#scheduledEnd)|Scheduled end time of the activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[scheduledStart](#scheduledStart)|Scheduled start time of the activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[subject](#subject)|Subject associated with the activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Scheduled duration of the activity, specified in minutes.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[actualDurationMinutes](#actualDurationMinutes)|Actual duration of the activity in minutes.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[actualEnd](#actualEnd)|Actual end time of the activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[actualStart](#actualStart)|Actual start time of the activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[activityAdditionalParams](#activityAdditionalParams)|Additional information provided by the external application as JSON. For internal use only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[to](#to)|Enter the account, contact, lead, or user recipients of the phone call.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[from](#from)|Enter the account, contact, lead, or user who made the phone call.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[resources](#resources)|Users or facility/equipment that are required for the activity.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[community](#community)|Shows how contact about the activity originated, such as from Twitter or Facebook. This field is read-only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[community_display](#community_display)||<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[directionCode](#directionCode)|Select the direction of the activity as incoming or outbound.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[description](#description)|Shows information about the social post content. This field is read-only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[processId](#processId)|Unique identifier of the Process.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[stageId](#stageId)|Unique identifier of the Stage.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[stateCode](#stateCode)|Shows whether the social activity completed. This field is read-only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[stateCode_display](#stateCode_display)||<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[statusCode](#statusCode)|Shows whether the social activity is completed, failed, or processing. This field is read-only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[statusCode_display](#statusCode_display)||<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[sentimentValue](#sentimentValue)|Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postedOn](#postedOn)|For internal use only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postURL](#postURL)|Shows the URL of the post.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[inResponseTo](#inResponseTo)|Unique identifier for the responses to a post. For internal use only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postMessageType](#postMessageType)|Shows if the social post originated as a private or public message.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postMessageType_display](#postMessageType_display)||<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postId](#postId)|Unique identifier of the post. For internal use only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[threadId](#threadId)|Unique identifier of the social conversation. For internal use only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this Social Activity. This field is for internal use only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postFromProfileId](#postFromProfileId)|Shows the author of the post on the corresponding social channel.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postToProfileId](#postToProfileId)|Shows the recipients of the social post.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postAuthorAccountType](#postAuthorAccountType)|The type of post author account, either Account or Contact.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postAuthorAccount](#postAuthorAccount)|Shows the parent account of the author of the post.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postAuthorType](#postAuthorType)|The type of post author, either Account or Contact.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[postAuthor](#postAuthor)|Shows the contact or account that authored the post.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[socialAdditionalParams](#socialAdditionalParams)|For internal use only.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the Social Activity record.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>|
|[serviceId](#serviceId)|Unique identifier for the associated service.|<a href="SocialActivity.md" target="_blank">crmCommon/SocialActivity</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Type of activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fax</td></tr><tr><td>en</td><td>Phone Call</td></tr><tr><td>en</td><td>Email</td></tr><tr><td>en</td><td>Letter</td></tr><tr><td>en</td><td>Appointment</td></tr><tr><td>en</td><td>Task</td></tr><tr><td>en</td><td>Recurring Appointment</td></tr><tr><td>en</td><td>Quick Campaign</td></tr><tr><td>en</td><td>Campaign Activity</td></tr><tr><td>en</td><td>Campaign Response</td></tr><tr><td>en</td><td>Case Resolution</td></tr><tr><td>en</td><td>Service Activity</td></tr><tr><td>en</td><td>Opportunity Close</td></tr><tr><td>en</td><td>Order Close</td></tr><tr><td>en</td><td>Quote Close</td></tr><tr><td>en</td><td>Alert Subscription</td></tr><tr><td>en</td><td>Invite Redemption</td></tr><tr><td>en</td><td>Portal Comment</td></tr></table></td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Information regarding whether the fax activity was billed as part of resolving a case.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Information regarding whether the activity is a regular activity type or event type.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Information regarding whether the activity was created from a workflow rule.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Priority of the activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectTypeCode name="regardingObjectTypeCode">regardingObjectTypeCode</a>

The name of the entity linked by regardingObjectId  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Type</td></tr><tr><td>description</td><td>The name of the entity linked by regardingObjectId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjecttypecode</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Scheduled end time of the activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Scheduled start time of the activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Scheduled duration of the activity, specified in minutes.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Scheduled duration of the activity, specified in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr></table>

### <a href=#actualDurationMinutes name="actualDurationMinutes">actualDurationMinutes</a>

Actual duration of the activity in minutes.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Actual duration of the activity in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Actual end time of the activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Actual end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Actual start time of the activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Actual start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#activityAdditionalParams name="activityAdditionalParams">activityAdditionalParams</a>

Additional information provided by the external application as JSON. For internal use only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr></table>

### <a href=#to name="to">to</a>

Enter the account, contact, lead, or user recipients of the phone call.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Call To</td></tr><tr><td>description</td><td>Enter the account, contact, lead, or user recipients of the phone call.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>to</td></tr></table>

### <a href=#from name="from">from</a>

Enter the account, contact, lead, or user who made the phone call.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Enter the account, contact, lead, or user who made the phone call.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>from</td></tr></table>

### <a href=#resources name="resources">resources</a>

Users or facility/equipment that are required for the activity.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resources</td></tr><tr><td>description</td><td>Users or facility/equipment that are required for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resources</td></tr></table>

### <a href=#community name="community">community</a>

Shows how contact about the activity originated, such as from Twitter or Facebook. This field is read-only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Channel</td></tr><tr><td>description</td><td>Shows how contact about the activity originated, such as from Twitter or Facebook. This field is read-only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>community</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Facebook</td><td>1</td></tr><tr><td>en</td><td>Twitter</td><td>2</td></tr><tr><td>en</td><td>Other</td><td>0</td></tr></table></td></tr></table>

### <a href=#community_display name="community_display">community_display</a>

First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#directionCode name="directionCode">directionCode</a>

Select the direction of the activity as incoming or outbound.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Direction</td></tr><tr><td>description</td><td>Select the direction of the activity as incoming or outbound.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>directioncode</td></tr></table>

### <a href=#description name="description">description</a>

Shows information about the social post content. This field is read-only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Description</td></tr><tr><td>description</td><td>Shows information about the social post content. This field is read-only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#processId name="processId">processId</a>

Unique identifier of the Process.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Unique identifier of the Process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Unique identifier of the Stage.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Unique identifier of the Stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the social activity completed. This field is read-only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the social activity completed. This field is read-only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Shows whether the social activity is completed, failed, or processing. This field is read-only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Shows whether the social activity is completed, failed, or processing. This field is read-only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Completed</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Failed</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Processing</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Open</td><td>4</td><td>0</td></tr><tr><td>en</td><td>Canceled</td><td>5</td><td>2</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#sentimentValue name="sentimentValue">sentimentValue</a>

Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sentiment Value</td></tr><tr><td>description</td><td>Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sentimentvalue</td></tr></table>

### <a href=#postedOn name="postedOn">postedOn</a>

For internal use only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postedon</td></tr></table>

### <a href=#postURL name="postURL">postURL</a>

Shows the URL of the post.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post URL</td></tr><tr><td>description</td><td>Shows the URL of the post.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>posturl</td></tr></table>

### <a href=#inResponseTo name="inResponseTo">inResponseTo</a>

Unique identifier for the responses to a post. For internal use only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In Response To</td></tr><tr><td>description</td><td>Unique identifier for the responses to a post. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inresponseto</td></tr></table>

### <a href=#postMessageType name="postMessageType">postMessageType</a>

Shows if the social post originated as a private or public message.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Received As</td></tr><tr><td>description</td><td>Shows if the social post originated as a private or public message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postmessagetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Public Message</td><td>0</td></tr><tr><td>en</td><td>Private Message</td><td>1</td></tr></table></td></tr></table>

### <a href=#postMessageType_display name="postMessageType_display">postMessageType_display</a>

First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#postId name="postId">postId</a>

Unique identifier of the post. For internal use only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post ID</td></tr><tr><td>description</td><td>Unique identifier of the post. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postid</td></tr></table>

### <a href=#threadId name="threadId">threadId</a>

Unique identifier of the social conversation. For internal use only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Thread ID</td></tr><tr><td>description</td><td>Unique identifier of the social conversation. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>threadid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this Social Activity. This field is for internal use only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this Social Activity. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#postFromProfileId name="postFromProfileId">postFromProfileId</a>

Shows the author of the post on the corresponding social channel.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posted By</td></tr><tr><td>description</td><td>Shows the author of the post on the corresponding social channel.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postfromprofileid</td></tr></table>

### <a href=#postToProfileId name="postToProfileId">postToProfileId</a>

Shows the recipients of the social post.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posted To</td></tr><tr><td>description</td><td>Shows the recipients of the social post.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>posttoprofileid</td></tr></table>

### <a href=#postAuthorAccountType name="postAuthorAccountType">postAuthorAccountType</a>

The type of post author account, either Account or Contact.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Author Account Type</td></tr><tr><td>description</td><td>The type of post author account, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>postauthoraccounttype</td></tr></table>

### <a href=#postAuthorAccount name="postAuthorAccount">postAuthorAccount</a>

Shows the parent account of the author of the post.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Author Account</td></tr><tr><td>description</td><td>Shows the parent account of the author of the post.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postauthoraccount</td></tr></table>

### <a href=#postAuthorType name="postAuthorType">postAuthorType</a>

The type of post author, either Account or Contact.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Author Type</td></tr><tr><td>description</td><td>The type of post author, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>postauthortype</td></tr></table>

### <a href=#postAuthor name="postAuthor">postAuthor</a>

Shows the contact or account that authored the post.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Author</td></tr><tr><td>description</td><td>Shows the contact or account that authored the post.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postauthor</td></tr></table>

### <a href=#socialAdditionalParams name="socialAdditionalParams">socialAdditionalParams</a>

For internal use only.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Additional Parameters</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>socialadditionalparams</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the Social Activity record.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the Social Activity record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: <a href="../../SocialActivity.md" target="_blank">applicationCommon/SocialActivity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#serviceId name="serviceId">serviceId</a>

Unique identifier for the associated service.  
First included in: crmCommon/SocialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service</td></tr><tr><td>description</td><td>Unique identifier for the associated service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceid</td></tr></table>
