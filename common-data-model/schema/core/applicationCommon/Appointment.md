---
title: Appointment - Common Data Model | Microsoft Docs
description: Commitment representing a time interval with start/end times and duration.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Appointment

Commitment representing a time interval with start/end times and duration.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Appointment.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Appointment  
- [/foundationCommon/crmCommon/Appointment](foundationCommon/crmCommon/Appointment.md "/core/applicationCommon/foundationCommon/crmCommon/Appointment.cdm.json/Appointment")  
- [/foundationCommon/crmCommon/solutions/marketing/Appointment](foundationCommon/crmCommon/solutions/marketing/Appointment.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Appointment.cdm.json/Appointment")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[activityTypeCode](#activityTypeCode)|Type of activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[activityId](#activityId)|Unique identifier of the activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[isBilled](#isBilled)|Information regarding whether the fax activity was billed as part of resolving a case.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[isRegularActivity](#isRegularActivity)|Information regarding whether the activity is a regular activity type or event type.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Information regarding whether the activity was created from a workflow rule.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[priorityCode](#priorityCode)|Priority of the activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[priorityCode_display](#priorityCode_display)||<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[regardingObjectTypeCode](#regardingObjectTypeCode)|The name of the entity linked by regardingObjectId|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[scheduledEnd](#scheduledEnd)|Scheduled end time of the activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[scheduledStart](#scheduledStart)|Scheduled start time of the activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[subject](#subject)|Subject associated with the activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Scheduled duration of the activity, specified in minutes.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[actualDurationMinutes](#actualDurationMinutes)|Actual duration of the activity in minutes.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[actualEnd](#actualEnd)|Actual end time of the activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[actualStart](#actualStart)|Actual start time of the activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[category](#category)|Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[subcategory](#subcategory)|Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[activityAdditionalParams](#activityAdditionalParams)|Additional information provided by the external application as JSON. For internal use only.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[instanceTypeCode](#instanceTypeCode)|Type of instance of a recurring series.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[instanceTypeCode_display](#instanceTypeCode_display)||<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[isMapiPrivate](#isMapiPrivate)|For internal use only.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[organizer](#organizer)|The user who is in charge of coordinating or leading the activity.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[requiredAttendees](#requiredAttendees)|Enter the account, contact, lead, user, or other equipment resources that are required to attend the appointment.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[optionalAttendees](#optionalAttendees)|Enter the account, contact, lead, user, or other equipment resources that are not needed at the appointment, but can optionally attend.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[isAllDayEvent](#isAllDayEvent)|Select whether the appointment is an all-day event to make sure that the required resources are scheduled for the full day.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[description](#description)|Type additional information to describe the purpose of the appointment.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[globalObjectId](#globalObjectId)|Shows the ID of the appointment in Microsoft Office Outlook. The ID is used to synchronize the appointment between Microsoft Dynamics 365 and the correct Exchange account.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[statusCode](#statusCode)|Select the appointment's status.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[statusCode_display](#statusCode_display)||<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[outlookOwnerApptId](#outlookOwnerApptId)|Unique identifier of the Microsoft Office Outlook appointment owner that correlates to the PR_OWNER_APPT_ID MAPI property.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[location](#location)|Type the location where the appointment will take place, such as a conference room or customer office.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[stateCode](#stateCode)|Shows whether the appointment is open, completed, or canceled. Completed and canceled appointments are read-only and can't be edited.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[stateCode_display](#stateCode_display)||<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[modifiedFieldsMask](#modifiedFieldsMask)|For internal use only. |<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[seriesId](#seriesId)|Shows the ID of the recurring series of an instance.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[originalStartDate](#originalStartDate)|The original start date of the appointment.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[processId](#processId)|Shows the ID of the process.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[stageId](#stageId)|Shows the ID of the stage.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[attachmentErrors](#attachmentErrors)|Select the error code to identify issues with the outlook item recipients or attachments, such as blocked attachments.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[attachmentErrors_display](#attachmentErrors_display)||<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[attachmentCount](#attachmentCount)|Shows the number of attachments on the appointment.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the appointment record.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this appointment. This field is for internal use only.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[isUnsafe](#isUnsafe)|For internal use only.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|
|[isDraft](#isDraft)|Information regarding whether the appointment is a draft.|<a href="Appointment.md" target="_blank">applicationCommon/Appointment</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Type of activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fax</td></tr><tr><td>en</td><td>Phone Call</td></tr><tr><td>en</td><td>Email</td></tr><tr><td>en</td><td>Letter</td></tr><tr><td>en</td><td>Appointment</td></tr><tr><td>en</td><td>Task</td></tr><tr><td>en</td><td>Recurring Appointment</td></tr><tr><td>en</td><td>Quick Campaign</td></tr><tr><td>en</td><td>Campaign Activity</td></tr><tr><td>en</td><td>Campaign Response</td></tr><tr><td>en</td><td>Case Resolution</td></tr><tr><td>en</td><td>Service Activity</td></tr><tr><td>en</td><td>Opportunity Close</td></tr><tr><td>en</td><td>Order Close</td></tr><tr><td>en</td><td>Quote Close</td></tr><tr><td>en</td><td>Alert Subscription</td></tr><tr><td>en</td><td>Invite Redemption</td></tr><tr><td>en</td><td>Portal Comment</td></tr></table></td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Information regarding whether the fax activity was billed as part of resolving a case.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Information regarding whether the activity is a regular activity type or event type.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Information regarding whether the activity was created from a workflow rule.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Priority of the activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectTypeCode name="regardingObjectTypeCode">regardingObjectTypeCode</a>

The name of the entity linked by regardingObjectId  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Type</td></tr><tr><td>description</td><td>The name of the entity linked by regardingObjectId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjecttypecode</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Scheduled end time of the activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Scheduled start time of the activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Scheduled duration of the activity, specified in minutes.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Scheduled duration of the activity, specified in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr></table>

### <a href=#actualDurationMinutes name="actualDurationMinutes">actualDurationMinutes</a>

Actual duration of the activity in minutes.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Actual duration of the activity in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Actual end time of the activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Actual end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Actual start time of the activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Actual start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#category name="category">category</a>

Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>category</td></tr></table>

### <a href=#subcategory name="subcategory">subcategory</a>

Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sub-Category</td></tr><tr><td>description</td><td>Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subcategory</td></tr></table>

### <a href=#activityAdditionalParams name="activityAdditionalParams">activityAdditionalParams</a>

Additional information provided by the external application as JSON. For internal use only.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr></table>

### <a href=#instanceTypeCode name="instanceTypeCode">instanceTypeCode</a>

Type of instance of a recurring series.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurring Instance Type</td></tr><tr><td>description</td><td>Type of instance of a recurring series.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>instancetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Recurring</td><td>0</td></tr><tr><td>en</td><td>Recurring Master</td><td>1</td></tr><tr><td>en</td><td>Recurring Instance</td><td>2</td></tr><tr><td>en</td><td>Recurring Exception</td><td>3</td></tr><tr><td>en</td><td>Recurring Future Exception</td><td>4</td></tr></table></td></tr></table>

### <a href=#instanceTypeCode_display name="instanceTypeCode_display">instanceTypeCode_display</a>

First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isMapiPrivate name="isMapiPrivate">isMapiPrivate</a>

For internal use only.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Private</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ismapiprivate</td></tr></table>

### <a href=#organizer name="organizer">organizer</a>

The user who is in charge of coordinating or leading the activity.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizer</td></tr><tr><td>description</td><td>The user who is in charge of coordinating or leading the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizer</td></tr></table>

### <a href=#requiredAttendees name="requiredAttendees">requiredAttendees</a>

Enter the account, contact, lead, user, or other equipment resources that are required to attend the appointment.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required Attendees</td></tr><tr><td>description</td><td>Enter the account, contact, lead, user, or other equipment resources that are required to attend the appointment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>requiredattendees</td></tr></table>

### <a href=#optionalAttendees name="optionalAttendees">optionalAttendees</a>

Enter the account, contact, lead, user, or other equipment resources that are not needed at the appointment, but can optionally attend.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Optional Attendees</td></tr><tr><td>description</td><td>Enter the account, contact, lead, user, or other equipment resources that are not needed at the appointment, but can optionally attend.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>optionalattendees</td></tr></table>

### <a href=#isAllDayEvent name="isAllDayEvent">isAllDayEvent</a>

Select whether the appointment is an all-day event to make sure that the required resources are scheduled for the full day.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>All Day Event</td></tr><tr><td>description</td><td>Select whether the appointment is an all-day event to make sure that the required resources are scheduled for the full day.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isalldayevent</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the purpose of the appointment.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the purpose of the appointment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#globalObjectId name="globalObjectId">globalObjectId</a>

Shows the ID of the appointment in Microsoft Office Outlook. The ID is used to synchronize the appointment between Microsoft Dynamics 365 and the correct Exchange account.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outlook Appointment</td></tr><tr><td>description</td><td>Shows the ID of the appointment in Microsoft Office Outlook. The ID is used to synchronize the appointment between Microsoft Dynamics 365 and the correct Exchange account.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>globalobjectid</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the appointment's status.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the appointment's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Free</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Tentative</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>4</td><td>2</td></tr><tr><td>en</td><td>Busy</td><td>5</td><td>3</td></tr><tr><td>en</td><td>Out of Office</td><td>6</td><td>3</td></tr><tr><td>en</td><td>Free</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Tentative</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>4</td><td>2</td></tr><tr><td>en</td><td>Busy</td><td>5</td><td>3</td></tr><tr><td>en</td><td>Out of Office</td><td>6</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#outlookOwnerApptId name="outlookOwnerApptId">outlookOwnerApptId</a>

Unique identifier of the Microsoft Office Outlook appointment owner that correlates to the PR_OWNER_APPT_ID MAPI property.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outlook Appointment Owner</td></tr><tr><td>description</td><td>Unique identifier of the Microsoft Office Outlook appointment owner that correlates to the PR_OWNER_APPT_ID MAPI property.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>outlookownerapptid</td></tr></table>

### <a href=#location name="location">location</a>

Type the location where the appointment will take place, such as a conference room or customer office.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>description</td><td>Type the location where the appointment will take place, such as a conference room or customer office.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>location</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the appointment is open, completed, or canceled. Completed and canceled appointments are read-only and can't be edited.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the appointment is open, completed, or canceled. Completed and canceled appointments are read-only and can't be edited.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr><tr><td>en</td><td>Scheduled</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#modifiedFieldsMask name="modifiedFieldsMask">modifiedFieldsMask</a>

For internal use only.   
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified Fields Mask</td></tr><tr><td>description</td><td>For internal use only. </td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedfieldsmask</td></tr></table>

### <a href=#seriesId name="seriesId">seriesId</a>

Shows the ID of the recurring series of an instance.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Series Id</td></tr><tr><td>description</td><td>Shows the ID of the recurring series of an instance.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>seriesid</td></tr></table>

### <a href=#originalStartDate name="originalStartDate">originalStartDate</a>

The original start date of the appointment.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original Start Date</td></tr><tr><td>description</td><td>The original start date of the appointment.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>originalstartdate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the ID of the process.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the ID of the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the ID of the stage.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the ID of the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#attachmentErrors name="attachmentErrors">attachmentErrors</a>

Select the error code to identify issues with the outlook item recipients or attachments, such as blocked attachments.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>AttachmentErrors</td></tr><tr><td>description</td><td>Select the error code to identify issues with the outlook item recipients or attachments, such as blocked attachments.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>attachmenterrors</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>The appointment was saved as a Microsoft Dynamics 365 appointment record, but not all the attachments could be saved with it. An attachment cannot be saved if it is blocked or if its file type is invalid.</td><td>1</td></tr></table></td></tr></table>

### <a href=#attachmentErrors_display name="attachmentErrors_display">attachmentErrors_display</a>

First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#attachmentCount name="attachmentCount">attachmentCount</a>

Shows the number of attachments on the appointment.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attachment Count</td></tr><tr><td>description</td><td>Shows the number of attachments on the appointment.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>attachmentcount</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the appointment record.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the appointment record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this appointment. This field is for internal use only.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this appointment. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#isUnsafe name="isUnsafe">isUnsafe</a>

For internal use only.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IsUnsafe</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isunsafe</td></tr></table>

### <a href=#isDraft name="isDraft">isDraft</a>

Information regarding whether the appointment is a draft.  
First included in: applicationCommon/Appointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IsDraft</td></tr><tr><td>description</td><td>Information regarding whether the appointment is a draft.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isdraft</td></tr></table>
