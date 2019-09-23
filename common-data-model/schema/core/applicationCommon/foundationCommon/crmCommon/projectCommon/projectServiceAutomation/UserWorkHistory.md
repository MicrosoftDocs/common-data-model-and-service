---
title: UserWorkHistory - Common Data Model | Microsoft Docs
description: Entity used to look up resources based on demonstrated skills.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# User Work History

Entity used to look up resources based on demonstrated skills.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/UserWorkHistory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/UserWorkHistory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[ownerId](#ownerId)|Owner Id|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[userWorkHistoryId](#userWorkHistoryId)|Unique identifier for entity instances|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[stateCode](#stateCode)|Status of the User Work History|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[stateCode_display](#stateCode_display)||<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[statusCode](#statusCode)|Reason for the status of the User Work History|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[statusCode_display](#statusCode_display)||<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[name](#name)|Type the name of the custom entity.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[bookableResource](#bookableResource)|Shows the name of the resource.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[budgetPerformance](#budgetPerformance)|Shows the planned versus actual cost for past projects.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[onTimePerformance](#onTimePerformance)|Shows the estimated versus. actual time spent on past projects.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[onTimeProjectCount](#onTimeProjectCount)|Shows the number of completed projects that are on time.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[projectCount](#projectCount)|Shows the number of completed projects.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[recordType](#recordType)|Type of the record: User (0), Min (1), Max (2)|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|
|[skillExperience](#skillExperience)|Enter the JSON object containing the skill experience.|<a href="UserWorkHistory.md" target="_blank">projectServiceAutomation/UserWorkHistory</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#userWorkHistoryId name="userWorkHistoryId">userWorkHistoryId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User Work History</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_userworkhistoryid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the User Work History  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the User Work History</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the User Work History  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the User Work History</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Shows the name of the resource.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable resource</td></tr><tr><td>description</td><td>Shows the name of the resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#budgetPerformance name="budgetPerformance">budgetPerformance</a>

Shows the planned versus actual cost for past projects.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Performance</td></tr><tr><td>description</td><td>Shows the planned versus actual cost for past projects.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_budgetperformance</td></tr></table>

### <a href=#onTimePerformance name="onTimePerformance">onTimePerformance</a>

Shows the estimated versus. actual time spent on past projects.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Time Performance</td></tr><tr><td>description</td><td>Shows the estimated versus. actual time spent on past projects.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_ontimeperformance</td></tr></table>

### <a href=#onTimeProjectCount name="onTimeProjectCount">onTimeProjectCount</a>

Shows the number of completed projects that are on time.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Time Project Count</td></tr><tr><td>description</td><td>Shows the number of completed projects that are on time.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_ontimeprojectcount</td></tr></table>

### <a href=#projectCount name="projectCount">projectCount</a>

Shows the number of completed projects.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Count</td></tr><tr><td>description</td><td>Shows the number of completed projects.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectcount</td></tr></table>

### <a href=#recordType name="recordType">recordType</a>

Type of the record: User (0), Min (1), Max (2)  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Type</td></tr><tr><td>description</td><td>Type of the record: User (0), Min (1), Max (2)</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>3</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_recordtype</td></tr></table>

### <a href=#skillExperience name="skillExperience">skillExperience</a>

Enter the JSON object containing the skill experience.  
First included in: projectServiceAutomation/UserWorkHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Skill Experience</td></tr><tr><td>description</td><td>Enter the JSON object containing the skill experience.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_skillexperience</td></tr></table>
