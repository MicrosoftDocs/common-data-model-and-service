---
title: TimeEntry - Common Data Model | Microsoft Docs
description: Entity used  for time entry.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Time Entry

Entity used  for time entry.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/TimeEntry.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/TimeEntry  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[ownerId](#ownerId)|Owner Id|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[timeEntryId](#timeEntryId)|The unique identifier for a time entry.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[stateCode](#stateCode)|Status of the Time Entry|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[stateCode_display](#stateCode_display)||<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[statusCode](#statusCode)|Reason for the status of the Time Entry|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[statusCode_display](#statusCode_display)||<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[internalComments](#internalComments)|Type the description of the time entry.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[bookableResource](#bookableResource)|Shows the bookable resource.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[date](#date)|Enter the time entry date.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[duration](#duration)|Shows the time spent.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[entryStatus](#entryStatus)|Select the entry status.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[entryStatus_display](#entryStatus_display)||<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[externalDescription](#externalDescription)|Type the external description of the time entry.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[manager](#manager)|Select the manager of the time entry user. This field is used for approval.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[project](#project)|Select the project that the time entry is related to.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[projectTask](#projectTask)|Select the project task that the time entry is related to.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[relatedItemId](#relatedItemId)|The identifier of the related item.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[relatedItemType](#relatedItemType)|The related item type|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[relatedItemType_display](#relatedItemType_display)||<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[resourceCategory](#resourceCategory)|Select the role that the user has in the project that the time entry is for.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[resourceOrganizationalUnitId](#resourceOrganizationalUnitId)|Select the organizational unit at the time the entry was registered of the resource who performed the work.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[targetEntryStatus](#targetEntryStatus)||<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[targetEntryStatus_display](#targetEntryStatus_display)||<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[transactionCategory](#transactionCategory)|Shows the transaction category.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[type](#type)|Select the time entry type.|<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|
|[type_display](#type_display)||<a href="TimeEntry.md" target="_blank">projectServiceAutomation/TimeEntry</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#timeEntryId name="timeEntryId">timeEntryId</a>

The unique identifier for a time entry.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Entry</td></tr><tr><td>description</td><td>The unique identifier for a time entry.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_timeentryid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Time Entry  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Time Entry</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Time Entry  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Time Entry</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#internalComments name="internalComments">internalComments</a>

Type the description of the time entry.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the description of the time entry.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Shows the bookable resource.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the bookable resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#date name="date">date</a>

Enter the time entry date.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date</td></tr><tr><td>description</td><td>Enter the time entry date.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_date</td></tr></table>

### <a href=#duration name="duration">duration</a>

Shows the time spent.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Shows the time spent.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_duration</td></tr></table>

### <a href=#entryStatus name="entryStatus">entryStatus</a>

Select the entry status.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entry Status</td></tr><tr><td>description</td><td>Select the entry status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_entrystatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>192350000</td></tr><tr><td>en</td><td>Returned</td><td>192350001</td></tr><tr><td>en</td><td>Approved</td><td>192350002</td></tr><tr><td>en</td><td>Submitted</td><td>192350003</td></tr><tr><td>en</td><td>Recall Requested</td><td>192350004</td></tr></table></td></tr></table>

### <a href=#entryStatus_display name="entryStatus_display">entryStatus_display</a>

First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#externalDescription name="externalDescription">externalDescription</a>

Type the external description of the time entry.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Comments</td></tr><tr><td>description</td><td>Type the external description of the time entry.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_externaldescription</td></tr></table>

### <a href=#manager name="manager">manager</a>

Select the manager of the time entry user. This field is used for approval.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manager</td></tr><tr><td>description</td><td>Select the manager of the time entry user. This field is used for approval.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_manager</td></tr></table>

### <a href=#project name="project">project</a>

Select the project that the time entry is related to.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Select the project that the time entry is related to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#projectTask name="projectTask">projectTask</a>

Select the project task that the time entry is related to.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Task</td></tr><tr><td>description</td><td>Select the project task that the time entry is related to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projecttask</td></tr></table>

### <a href=#relatedItemId name="relatedItemId">relatedItemId</a>

The identifier of the related item.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related item identifier</td></tr><tr><td>description</td><td>The identifier of the related item.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_relateditemid</td></tr></table>

### <a href=#relatedItemType name="relatedItemType">relatedItemType</a>

The related item type  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related item type</td></tr><tr><td>description</td><td>The related item type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_relateditemtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>192350000</td></tr><tr><td>en</td><td>Resource Booking</td><td>192350001</td></tr><tr><td>en</td><td>Resource Assignment</td><td>192350002</td></tr><tr><td>en</td><td>Exchange Appointments</td><td>192350100</td></tr></table></td></tr></table>

### <a href=#relatedItemType_display name="relatedItemType_display">relatedItemType_display</a>

First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Select the role that the user has in the project that the time entry is for.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Select the role that the user has in the project that the time entry is for.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#resourceOrganizationalUnitId name="resourceOrganizationalUnitId">resourceOrganizationalUnitId</a>

Select the organizational unit at the time the entry was registered of the resource who performed the work.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resourcing Unit</td></tr><tr><td>description</td><td>Select the organizational unit at the time the entry was registered of the resource who performed the work.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceorganizationalunitid</td></tr></table>

### <a href=#targetEntryStatus name="targetEntryStatus">targetEntryStatus</a>

First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target Entry Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_targetentrystatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>192350000</td></tr><tr><td>en</td><td>Returned</td><td>192350001</td></tr><tr><td>en</td><td>Approved</td><td>192350002</td></tr><tr><td>en</td><td>Submitted</td><td>192350003</td></tr><tr><td>en</td><td>Recall Requested</td><td>192350004</td></tr></table></td></tr></table>

### <a href=#targetEntryStatus_display name="targetEntryStatus_display">targetEntryStatus_display</a>

First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Shows the transaction category.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>description</td><td>Shows the transaction category.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#type name="type">type</a>

Select the time entry type.  
First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Select the time entry type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Work</td><td>192350000</td></tr><tr><td>en</td><td>Absence</td><td>192350001</td></tr><tr><td>en</td><td>Vacation</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: projectServiceAutomation/TimeEntry (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
