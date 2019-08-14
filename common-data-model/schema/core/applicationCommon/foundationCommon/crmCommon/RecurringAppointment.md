---
title: RecurringAppointment - Common Data Model | Microsoft Docs
description: The Master appointment of a recurring appointment series.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Recurring Appointment

The Master appointment of a recurring appointment series.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/RecurringAppointment.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/RecurringAppointment](../../RecurringAppointment.md "/core/applicationCommon/RecurringAppointment.cdm.json/RecurringAppointment")  
- /foundationCommon/crmCommon/RecurringAppointment  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[activityTypeCode](#activityTypeCode)|Type of activity.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[activityId](#activityId)|Unique identifier of the activity.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isBilled](#isBilled)|Information regarding whether the fax activity was billed as part of resolving a case.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isRegularActivity](#isRegularActivity)|Information regarding whether the activity is a regular activity type or event type.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Information regarding whether the activity was created from a workflow rule.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[priorityCode](#priorityCode)|Priority of the activity.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[priorityCode_display](#priorityCode_display)||<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[regardingObjectTypeCode](#regardingObjectTypeCode)|The name of the entity linked by regardingObjectId|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[scheduledEnd](#scheduledEnd)|Scheduled end time of the activity.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[scheduledStart](#scheduledStart)|Scheduled start time of the activity.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[subject](#subject)|Subject associated with the activity.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[category](#category)|Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[subcategory](#subcategory)|Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[instanceTypeCode](#instanceTypeCode)|Type of instance of a recurring series.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[instanceTypeCode_display](#instanceTypeCode_display)||<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isMapiPrivate](#isMapiPrivate)|For internal use only.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[organizer](#organizer)|The user who is in charge of coordinating or leading the activity.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[requiredAttendees](#requiredAttendees)|Enter the account, contact, lead, user, or other equipment resources that are required to attend the appointment.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[optionalAttendees](#optionalAttendees)|Enter the account, contact, lead, user, or other equipment resources that are not needed at the appointment, but can optionally attend.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isWeekDayPattern](#isWeekDayPattern)|Indicates whether the weekly recurrence pattern is a daily weekday pattern. Valid for weekly recurrence pattern only.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[ruleId](#ruleId)|Unique identifier of the recurrence rule that is associated with the recurring appointment series.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isNthYearly](#isNthYearly)|Indicates whether the recurring appointment series should occur after every N years. Valid for yearly recurrence pattern only.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[stateCode](#stateCode)|Shows whether the recurring appointment is open, scheduled, completed, or canceled. Completed and canceled appointments are read-only and can't be edited.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[stateCode_display](#stateCode_display)||<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[groupId](#groupId)|Unique identifier of the recurring appointment series for which the recurrence information was updated. |<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[lastExpandedInstanceDate](#lastExpandedInstanceDate)|Date of last expanded instance of a recurring appointment series.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[effectiveEndDate](#effectiveEndDate)|Actual end date of the recurring appointment series based on the specified end date and recurrence pattern.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[patternStartDate](#patternStartDate)|Start date of the recurrence range.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isRegenerate](#isRegenerate)|For internal use only.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[firstDayOfWeek](#firstDayOfWeek)|First day of week for the recurrence pattern.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[outlookOwnerApptId](#outlookOwnerApptId)|Unique identifier of the Microsoft Office Outlook recurring appointment series owner that correlates to the PR_OWNER_APPT_ID MAPI property.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[recurrencePatternType](#recurrencePatternType)|Select the pattern type for the recurring appointment to indicate whether the appointment occurs daily, weekly, monthly, or yearly.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[recurrencePatternType_display](#recurrencePatternType_display)||<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[nextExpansionInstanceDate](#nextExpansionInstanceDate)|Date of the next expanded instance of a recurring appointment series.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[expansionStateCode](#expansionStateCode)|State code to indicate whether the recurring appointment series is expanded fully or partially.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[expansionStateCode_display](#expansionStateCode_display)||<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[patternEndDate](#patternEndDate)|End date of the recurrence range.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[globalObjectId](#globalObjectId)|Unique Outlook identifier to correlate recurring appointment series across Exchange mailboxes.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[effectiveStartDate](#effectiveStartDate)|Actual start date of the recurring appointment series based on the specified start date and recurrence pattern.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[dayOfMonth](#dayOfMonth)|The day of the month on which the recurring appointment occurs.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[statusCode](#statusCode)|Select the recurring appointment's status.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[statusCode_display](#statusCode_display)||<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[startTime](#startTime)|Start time of the recurring appointment series.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[occurrences](#occurrences)|Number of appointment occurrences in a recurring appointment series.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isAllDayEvent](#isAllDayEvent)|Select whether the recurring appointment is an all-day event to make sure that the required resources are scheduled for the full day.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[seriesStatus](#seriesStatus)|Indicates whether the recurring appointment series is active or inactive.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isNthMonthly](#isNthMonthly)|Indicates whether the recurring appointment series should occur after every N months. Valid for monthly recurrence pattern only.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[endTime](#endTime)|End time of the associated activity.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[daysOfWeekMask](#daysOfWeekMask)|Bitmask that represents the days of the week on which the recurring appointment occurs.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[description](#description)|Type additional information to describe the recurring appointment, such as key talking points or objectives.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[instance](#instance)|Specifies the recurring appointment series to occur on every Nth day of a month. Valid for monthly and yearly recurrence patterns only.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[instance_display](#instance_display)||<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[deletedExceptionsList](#deletedExceptionsList)|List of deleted instances of the recurring appointment series.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[interval](#interval)|Number of units of a given recurrence type between occurrences.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[duration](#duration)|Duration of the recurring appointment series in minutes.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[monthOfYear](#monthOfYear)|Indicates the month of the year for the recurrence pattern.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[monthOfYear_display](#monthOfYear_display)||<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[location](#location)|Type the location where the recurring appointment will take place, such as a conference room or customer office.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[patternEndType](#patternEndType)|Select the type of end date for the recurring appointment, such as no end date or the number of occurrences.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[patternEndType_display](#patternEndType_display)||<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[processId](#processId)|Shows the ID of the process.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[stageId](#stageId)|Shows the ID of the stage.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[isUnsafe](#isUnsafe)|For internal use only.|<a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>|
|[serviceId](#serviceId)|Unique identifier for an associated service.|<a href="RecurringAppointment.md" target="_blank">crmCommon/RecurringAppointment</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Type of activity.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fax</td></tr><tr><td>en</td><td>Phone Call</td></tr><tr><td>en</td><td>Email</td></tr><tr><td>en</td><td>Letter</td></tr><tr><td>en</td><td>Appointment</td></tr><tr><td>en</td><td>Task</td></tr><tr><td>en</td><td>Recurring Appointment</td></tr><tr><td>en</td><td>Quick Campaign</td></tr><tr><td>en</td><td>Campaign Activity</td></tr><tr><td>en</td><td>Campaign Response</td></tr><tr><td>en</td><td>Case Resolution</td></tr><tr><td>en</td><td>Service Activity</td></tr><tr><td>en</td><td>Opportunity Close</td></tr><tr><td>en</td><td>Order Close</td></tr><tr><td>en</td><td>Quote Close</td></tr><tr><td>en</td><td>Alert Subscription</td></tr><tr><td>en</td><td>Invite Redemption</td></tr><tr><td>en</td><td>Portal Comment</td></tr></table></td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Information regarding whether the fax activity was billed as part of resolving a case.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Information regarding whether the activity is a regular activity type or event type.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Information regarding whether the activity was created from a workflow rule.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Priority of the activity.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectTypeCode name="regardingObjectTypeCode">regardingObjectTypeCode</a>

The name of the entity linked by regardingObjectId  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Type</td></tr><tr><td>description</td><td>The name of the entity linked by regardingObjectId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjecttypecode</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Scheduled end time of the activity.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Scheduled start time of the activity.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the activity.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#category name="category">category</a>

Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>category</td></tr></table>

### <a href=#subcategory name="subcategory">subcategory</a>

Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sub-Category</td></tr><tr><td>description</td><td>Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subcategory</td></tr></table>

### <a href=#instanceTypeCode name="instanceTypeCode">instanceTypeCode</a>

Type of instance of a recurring series.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurring Instance Type</td></tr><tr><td>description</td><td>Type of instance of a recurring series.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>instancetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Recurring</td><td>0</td></tr><tr><td>en</td><td>Recurring Master</td><td>1</td></tr><tr><td>en</td><td>Recurring Instance</td><td>2</td></tr><tr><td>en</td><td>Recurring Exception</td><td>3</td></tr><tr><td>en</td><td>Recurring Future Exception</td><td>4</td></tr></table></td></tr></table>

### <a href=#instanceTypeCode_display name="instanceTypeCode_display">instanceTypeCode_display</a>

First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isMapiPrivate name="isMapiPrivate">isMapiPrivate</a>

For internal use only.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Private</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ismapiprivate</td></tr></table>

### <a href=#organizer name="organizer">organizer</a>

The user who is in charge of coordinating or leading the activity.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizer</td></tr><tr><td>description</td><td>The user who is in charge of coordinating or leading the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizer</td></tr></table>

### <a href=#requiredAttendees name="requiredAttendees">requiredAttendees</a>

Enter the account, contact, lead, user, or other equipment resources that are required to attend the appointment.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required Attendees</td></tr><tr><td>description</td><td>Enter the account, contact, lead, user, or other equipment resources that are required to attend the appointment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>requiredattendees</td></tr></table>

### <a href=#optionalAttendees name="optionalAttendees">optionalAttendees</a>

Enter the account, contact, lead, user, or other equipment resources that are not needed at the appointment, but can optionally attend.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Optional Attendees</td></tr><tr><td>description</td><td>Enter the account, contact, lead, user, or other equipment resources that are not needed at the appointment, but can optionally attend.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>optionalattendees</td></tr></table>

### <a href=#isWeekDayPattern name="isWeekDayPattern">isWeekDayPattern</a>

Indicates whether the weekly recurrence pattern is a daily weekday pattern. Valid for weekly recurrence pattern only.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Every Weekday</td></tr><tr><td>description</td><td>Indicates whether the weekly recurrence pattern is a daily weekday pattern. Valid for weekly recurrence pattern only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isweekdaypattern</td></tr></table>

### <a href=#ruleId name="ruleId">ruleId</a>

Unique identifier of the recurrence rule that is associated with the recurring appointment series.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence Rule</td></tr><tr><td>description</td><td>Unique identifier of the recurrence rule that is associated with the recurring appointment series.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ruleid</td></tr></table>

### <a href=#isNthYearly name="isNthYearly">isNthYearly</a>

Indicates whether the recurring appointment series should occur after every N years. Valid for yearly recurrence pattern only.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nth Yearly</td></tr><tr><td>description</td><td>Indicates whether the recurring appointment series should occur after every N years. Valid for yearly recurrence pattern only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isnthyearly</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the recurring appointment is open, scheduled, completed, or canceled. Completed and canceled appointments are read-only and can't be edited.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the recurring appointment is open, scheduled, completed, or canceled. Completed and canceled appointments are read-only and can't be edited.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr><tr><td>en</td><td>Scheduled</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#groupId name="groupId">groupId</a>

Unique identifier of the recurring appointment series for which the recurrence information was updated.   
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group Id</td></tr><tr><td>description</td><td>Unique identifier of the recurring appointment series for which the recurrence information was updated. </td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>groupid</td></tr></table>

### <a href=#lastExpandedInstanceDate name="lastExpandedInstanceDate">lastExpandedInstanceDate</a>

Date of last expanded instance of a recurring appointment series.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Expanded Instance Date</td></tr><tr><td>description</td><td>Date of last expanded instance of a recurring appointment series.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastexpandedinstancedate</td></tr></table>

### <a href=#effectiveEndDate name="effectiveEndDate">effectiveEndDate</a>

Actual end date of the recurring appointment series based on the specified end date and recurrence pattern.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective End Date</td></tr><tr><td>description</td><td>Actual end date of the recurring appointment series based on the specified end date and recurrence pattern.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>effectiveenddate</td></tr></table>

### <a href=#patternStartDate name="patternStartDate">patternStartDate</a>

Start date of the recurrence range.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence Range Start</td></tr><tr><td>description</td><td>Start date of the recurrence range.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>patternstartdate</td></tr></table>

### <a href=#isRegenerate name="isRegenerate">isRegenerate</a>

For internal use only.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regenerate</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregenerate</td></tr></table>

### <a href=#firstDayOfWeek name="firstDayOfWeek">firstDayOfWeek</a>

First day of week for the recurrence pattern.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Day Of Week</td></tr><tr><td>description</td><td>First day of week for the recurrence pattern.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>6</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>firstdayofweek</td></tr></table>

### <a href=#outlookOwnerApptId name="outlookOwnerApptId">outlookOwnerApptId</a>

Unique identifier of the Microsoft Office Outlook recurring appointment series owner that correlates to the PR_OWNER_APPT_ID MAPI property.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outlook Recurring Appointment Master Owner</td></tr><tr><td>description</td><td>Unique identifier of the Microsoft Office Outlook recurring appointment series owner that correlates to the PR_OWNER_APPT_ID MAPI property.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>outlookownerapptid</td></tr></table>

### <a href=#recurrencePatternType name="recurrencePatternType">recurrencePatternType</a>

Select the pattern type for the recurring appointment to indicate whether the appointment occurs daily, weekly, monthly, or yearly.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence Frequency</td></tr><tr><td>description</td><td>Select the pattern type for the recurring appointment to indicate whether the appointment occurs daily, weekly, monthly, or yearly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>recurrencepatterntype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Daily</td><td>0</td></tr><tr><td>en</td><td>Weekly</td><td>1</td></tr><tr><td>en</td><td>Monthly</td><td>2</td></tr><tr><td>en</td><td>Yearly</td><td>3</td></tr></table></td></tr></table>

### <a href=#recurrencePatternType_display name="recurrencePatternType_display">recurrencePatternType_display</a>

First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#nextExpansionInstanceDate name="nextExpansionInstanceDate">nextExpansionInstanceDate</a>

Date of the next expanded instance of a recurring appointment series.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Expanded Instance Date</td></tr><tr><td>description</td><td>Date of the next expanded instance of a recurring appointment series.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>nextexpansioninstancedate</td></tr></table>

### <a href=#expansionStateCode name="expansionStateCode">expansionStateCode</a>

State code to indicate whether the recurring appointment series is expanded fully or partially.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expansion State Code</td></tr><tr><td>description</td><td>State code to indicate whether the recurring appointment series is expanded fully or partially.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expansionstatecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unexpanded</td><td>0</td></tr><tr><td>en</td><td>Partial</td><td>1</td></tr><tr><td>en</td><td>Full</td><td>2</td></tr></table></td></tr></table>

### <a href=#expansionStateCode_display name="expansionStateCode_display">expansionStateCode_display</a>

First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#patternEndDate name="patternEndDate">patternEndDate</a>

End date of the recurrence range.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence Range End</td></tr><tr><td>description</td><td>End date of the recurrence range.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>patternenddate</td></tr></table>

### <a href=#globalObjectId name="globalObjectId">globalObjectId</a>

Unique Outlook identifier to correlate recurring appointment series across Exchange mailboxes.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outlook Recurring Appointment Master</td></tr><tr><td>description</td><td>Unique Outlook identifier to correlate recurring appointment series across Exchange mailboxes.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>globalobjectid</td></tr></table>

### <a href=#effectiveStartDate name="effectiveStartDate">effectiveStartDate</a>

Actual start date of the recurring appointment series based on the specified start date and recurrence pattern.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Start Date</td></tr><tr><td>description</td><td>Actual start date of the recurring appointment series based on the specified start date and recurrence pattern.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>effectivestartdate</td></tr></table>

### <a href=#dayOfMonth name="dayOfMonth">dayOfMonth</a>

The day of the month on which the recurring appointment occurs.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Day Of Month</td></tr><tr><td>description</td><td>The day of the month on which the recurring appointment occurs.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>31</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>dayofmonth</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the recurring appointment's status.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the recurring appointment's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Free</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Tentative</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>4</td><td>2</td></tr><tr><td>en</td><td>Busy</td><td>5</td><td>3</td></tr><tr><td>en</td><td>Out of Office</td><td>6</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#startTime name="startTime">startTime</a>

Start time of the recurring appointment series.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pattern Start Time</td></tr><tr><td>description</td><td>Start time of the recurring appointment series.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>starttime</td></tr></table>

### <a href=#occurrences name="occurrences">occurrences</a>

Number of appointment occurrences in a recurring appointment series.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Occurrences</td></tr><tr><td>description</td><td>Number of appointment occurrences in a recurring appointment series.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>999</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>occurrences</td></tr></table>

### <a href=#isAllDayEvent name="isAllDayEvent">isAllDayEvent</a>

Select whether the recurring appointment is an all-day event to make sure that the required resources are scheduled for the full day.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>All Day Event</td></tr><tr><td>description</td><td>Select whether the recurring appointment is an all-day event to make sure that the required resources are scheduled for the full day.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isalldayevent</td></tr></table>

### <a href=#seriesStatus name="seriesStatus">seriesStatus</a>

Indicates whether the recurring appointment series is active or inactive.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Series Status</td></tr><tr><td>description</td><td>Indicates whether the recurring appointment series is active or inactive.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>seriesstatus</td></tr></table>

### <a href=#isNthMonthly name="isNthMonthly">isNthMonthly</a>

Indicates whether the recurring appointment series should occur after every N months. Valid for monthly recurrence pattern only.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nth Monthly</td></tr><tr><td>description</td><td>Indicates whether the recurring appointment series should occur after every N months. Valid for monthly recurrence pattern only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isnthmonthly</td></tr></table>

### <a href=#endTime name="endTime">endTime</a>

End time of the associated activity.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pattern End Time</td></tr><tr><td>description</td><td>End time of the associated activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>endtime</td></tr></table>

### <a href=#daysOfWeekMask name="daysOfWeekMask">daysOfWeekMask</a>

Bitmask that represents the days of the week on which the recurring appointment occurs.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days Of Week Mask</td></tr><tr><td>description</td><td>Bitmask that represents the days of the week on which the recurring appointment occurs.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>127</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>daysofweekmask</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the recurring appointment, such as key talking points or objectives.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the recurring appointment, such as key talking points or objectives.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#instance name="instance">instance</a>

Specifies the recurring appointment series to occur on every Nth day of a month. Valid for monthly and yearly recurrence patterns only.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Instance</td></tr><tr><td>description</td><td>Specifies the recurring appointment series to occur on every Nth day of a month. Valid for monthly and yearly recurrence patterns only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>instance</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>First</td><td>1</td></tr><tr><td>en</td><td>Second</td><td>2</td></tr><tr><td>en</td><td>Third</td><td>3</td></tr><tr><td>en</td><td>Fourth</td><td>4</td></tr><tr><td>en</td><td>Last</td><td>5</td></tr></table></td></tr></table>

### <a href=#instance_display name="instance_display">instance_display</a>

First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#deletedExceptionsList name="deletedExceptionsList">deletedExceptionsList</a>

List of deleted instances of the recurring appointment series.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deleted Appointments</td></tr><tr><td>description</td><td>List of deleted instances of the recurring appointment series.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deletedexceptionslist</td></tr></table>

### <a href=#interval name="interval">interval</a>

Number of units of a given recurrence type between occurrences.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interval</td></tr><tr><td>description</td><td>Number of units of a given recurrence type between occurrences.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>interval</td></tr></table>

### <a href=#duration name="duration">duration</a>

Duration of the recurring appointment series in minutes.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Duration of the recurring appointment series in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>duration</td></tr></table>

### <a href=#monthOfYear name="monthOfYear">monthOfYear</a>

Indicates the month of the year for the recurrence pattern.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Month Of Year</td></tr><tr><td>description</td><td>Indicates the month of the year for the recurrence pattern.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>monthofyear</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Invalid Month Of Year</td><td>0</td></tr><tr><td>en</td><td>January</td><td>1</td></tr><tr><td>en</td><td>February</td><td>2</td></tr><tr><td>en</td><td>March</td><td>3</td></tr><tr><td>en</td><td>April</td><td>4</td></tr><tr><td>en</td><td>May</td><td>5</td></tr><tr><td>en</td><td>June</td><td>6</td></tr><tr><td>en</td><td>July</td><td>7</td></tr><tr><td>en</td><td>August</td><td>8</td></tr><tr><td>en</td><td>September</td><td>9</td></tr><tr><td>en</td><td>October</td><td>10</td></tr><tr><td>en</td><td>November</td><td>11</td></tr><tr><td>en</td><td>December</td><td>12</td></tr></table></td></tr></table>

### <a href=#monthOfYear_display name="monthOfYear_display">monthOfYear_display</a>

First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#location name="location">location</a>

Type the location where the recurring appointment will take place, such as a conference room or customer office.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>description</td><td>Type the location where the recurring appointment will take place, such as a conference room or customer office.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>location</td></tr></table>

### <a href=#patternEndType name="patternEndType">patternEndType</a>

Select the type of end date for the recurring appointment, such as no end date or the number of occurrences.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pattern End Type</td></tr><tr><td>description</td><td>Select the type of end date for the recurring appointment, such as no end date or the number of occurrences.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>patternendtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No End Date</td><td>1</td></tr><tr><td>en</td><td>Occurrences</td><td>2</td></tr><tr><td>en</td><td>Pattern End Date</td><td>3</td></tr></table></td></tr></table>

### <a href=#patternEndType_display name="patternEndType_display">patternEndType_display</a>

First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the ID of the process.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the ID of the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the ID of the stage.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the ID of the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#isUnsafe name="isUnsafe">isUnsafe</a>

For internal use only.  
First included in: <a href="../../RecurringAppointment.md" target="_blank">applicationCommon/RecurringAppointment</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IsUnsafe</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isunsafe</td></tr></table>

### <a href=#serviceId name="serviceId">serviceId</a>

Unique identifier for an associated service.  
First included in: crmCommon/RecurringAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service</td></tr><tr><td>description</td><td>Unique identifier for an associated service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceid</td></tr></table>
