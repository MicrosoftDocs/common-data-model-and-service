---
title: ProjectTaskStatusUser - Common Data Model | Microsoft Docs
description: User status for project tasks (Deprecated in v3.0).
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Project Task Status User

User status for project tasks (Deprecated in v3.0).  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectTaskStatusUser.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectTaskStatusUser  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[projectTaskStatusUserId](#projectTaskStatusUserId)|Unique identifier for entity instances|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[stateCode](#stateCode)|Status of the Project Task Status User|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[stateCode_display](#stateCode_display)||<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[statusCode](#statusCode)|Reason for the status of the Project Task Status User|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[statusCode_display](#statusCode_display)||<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[name](#name)|Type the name of the custom entity.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[bookableResource](#bookableResource)||<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[description](#description)|Shows the description of the task.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[expectedCompletionDate](#expectedCompletionDate)|Shows the expected completion date of the task entered by the assigned resource.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[expectedHoursToComplete](#expectedHoursToComplete)|Shows the expected hours to complete the task entered by the assigned resource.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[isCompleted](#isCompleted)|Shows if the task is completed.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[percentComplete](#percentComplete)|Shows the reported percentage complete for the project task.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[projectTaskId](#projectTaskId)|Unique identifier for Project Task associated with Project Task Status User.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[projectTaskStatusIndicator](#projectTaskStatusIndicator)|Indicates the status of the project task reported by the user resource.|<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|
|[projectTaskStatusIndicator_display](#projectTaskStatusIndicator_display)||<a href="ProjectTaskStatusUser.md" target="_blank">projectServiceAutomation/ProjectTaskStatusUser</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#projectTaskStatusUserId name="projectTaskStatusUserId">projectTaskStatusUserId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Task Status User</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_projecttaskstatususerid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Project Task Status User  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Project Task Status User</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Project Task Status User  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Project Task Status User</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#description name="description">description</a>

Shows the description of the task.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Shows the description of the task.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#expectedCompletionDate name="expectedCompletionDate">expectedCompletionDate</a>

Shows the expected completion date of the task entered by the assigned resource.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Completion Date</td></tr><tr><td>description</td><td>Shows the expected completion date of the task entered by the assigned resource.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_expectedcompletiondate</td></tr></table>

### <a href=#expectedHoursToComplete name="expectedHoursToComplete">expectedHoursToComplete</a>

Shows the expected hours to complete the task entered by the assigned resource.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Hours To Complete</td></tr><tr><td>description</td><td>Shows the expected hours to complete the task entered by the assigned resource.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_expectedhourstocomplete</td></tr></table>

### <a href=#isCompleted name="isCompleted">isCompleted</a>

Shows if the task is completed.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Completed</td></tr><tr><td>description</td><td>Shows if the task is completed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_iscompleted</td></tr></table>

### <a href=#percentComplete name="percentComplete">percentComplete</a>

Shows the reported percentage complete for the project task.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percent Complete</td></tr><tr><td>description</td><td>Shows the reported percentage complete for the project task.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_percentcomplete</td></tr></table>

### <a href=#projectTaskId name="projectTaskId">projectTaskId</a>

Unique identifier for Project Task associated with Project Task Status User.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Task</td></tr><tr><td>description</td><td>Unique identifier for Project Task associated with Project Task Status User.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projecttaskid</td></tr></table>

### <a href=#projectTaskStatusIndicator name="projectTaskStatusIndicator">projectTaskStatusIndicator</a>

Indicates the status of the project task reported by the user resource.  
First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Task Status Indicator</td></tr><tr><td>description</td><td>Indicates the status of the project task reported by the user resource.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projecttaskstatusindicator</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Green</td><td>192350000</td></tr><tr><td>en</td><td>Yellow</td><td>192350001</td></tr><tr><td>en</td><td>Red</td><td>192350002</td></tr><tr><td>en</td><td>None</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#projectTaskStatusIndicator_display name="projectTaskStatusIndicator_display">projectTaskStatusIndicator_display</a>

First included in: projectServiceAutomation/ProjectTaskStatusUser (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
