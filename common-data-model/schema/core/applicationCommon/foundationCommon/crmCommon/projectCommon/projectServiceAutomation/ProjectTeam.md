---
title: ProjectTeam - Common Data Model | Microsoft Docs
description: Entity used to model relationship between resources and project teams.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Project Team Member

Entity used to model relationship between resources and project teams.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectTeam.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectTeam  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[projectTeamId](#projectTeamId)|Unique identifier for entity instances|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[stateCode](#stateCode)|Shows the status of the project team.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[stateCode_display](#stateCode_display)||<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[statusCode](#statusCode)|Reason for the status of the Project Team|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[statusCode_display](#statusCode_display)||<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[positionName](#positionName)|Type the name of the custom entity.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[allocationMethod](#allocationMethod)|Shows the allocation method used to book resources on the project (full capacity, percentage, and so on).|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[allocationMethod_display](#allocationMethod_display)||<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[assignedHours](#assignedHours)|Type the total assigned hours for project team member.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[billingType](#billingType)|Select whether the team member is billable|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[billingType_display](#billingType_display)||<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[bookableResourceId](#bookableResourceId)|Shows the resource.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[calendarId](#calendarId)|Shows the calendar used for staffing this project team.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[description](#description)|Type the system description.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[from](#from)|Enter the resource team membership start date.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[hardBookedHours](#hardBookedHours)|Hard Booked Hours|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[hours](#hours)|Duplicate for resource requirement|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[hoursRequested](#hoursRequested)|Shows the number of hours required of this team member on the project.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[membershipStatus](#membershipStatus)|Shows the membership status of this project team member.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[membershipStatus_display](#membershipStatus_display)||<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[MSProjectClientId](#MSProjectClientId)|The id of the project team member in MS Project Client.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[number](#number)|Shows the number of resources requested.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[resourcingUnit](#resourcingUnit)|The organizational unit of the resource performing the work.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[percentage](#percentage)|Duplicate for resource requirement|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[project](#project)|Select the project that this team members are part of.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[projectApprover](#projectApprover)|Select whether the team member can approve time and expenses.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[requiredHours](#requiredHours)|Required hours of team member from team member requirement|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[resourceCategory](#resourceCategory)|Select the role this team member is playing in this team.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[resourceRequirementId](#resourceRequirementId)|Unique identifier for Resource Requirement associated with Project Team Member.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[roleDescription](#roleDescription)|Enter a description of the role for this team member.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[softBookedHours](#softBookedHours)|Soft Booked Hours|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[to](#to)|Enter the end date of the resource membership in a team.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[workTemplate](#workTemplate)|Template to use for generic resource's schedule. Will be ignored if its a user or facility resource|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[applicantCount](#applicantCount)|Shows the number of applicants for this project team.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[applicantCountDate](#applicantCountDate)|Last Updated time of rollup field Applicant count.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[applicantCountState](#applicantCountState)|State of rollup field Applicant count.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|
|[applicantsAvailable](#applicantsAvailable)|Shows if there are applicants available for this project team.|<a href="ProjectTeam.md" target="_blank">projectServiceAutomation/ProjectTeam</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#projectTeamId name="projectTeamId">projectTeamId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Team</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_projectteamid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows the status of the project team.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows the status of the project team.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Project Team  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Project Team</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#positionName name="positionName">positionName</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Position Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#allocationMethod name="allocationMethod">allocationMethod</a>

Shows the allocation method used to book resources on the project (full capacity, percentage, and so on).  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allocation method</td></tr><tr><td>description</td><td>Shows the allocation method used to book resources on the project (full capacity, percentage, and so on).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_allocationmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>192350000</td></tr><tr><td>en</td><td>Full Capacity</td><td>192350001</td></tr><tr><td>en</td><td>Percentage Capacity</td><td>192350004</td></tr><tr><td>en</td><td>By Hours - Distribute evenly</td><td>192350003</td></tr><tr><td>en</td><td>By Hours - Front load</td><td>192350005</td></tr></table></td></tr></table>

### <a href=#allocationMethod_display name="allocationMethod_display">allocationMethod_display</a>

First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#assignedHours name="assignedHours">assignedHours</a>

Type the total assigned hours for project team member.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assigned Hours</td></tr><tr><td>description</td><td>Type the total assigned hours for project team member.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_assignedhours</td></tr></table>

### <a href=#billingType name="billingType">billingType</a>

Select whether the team member is billable  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Type</td></tr><tr><td>description</td><td>Select whether the team member is billable</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingType_display name="billingType_display">billingType_display</a>

First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookableResourceId name="bookableResourceId">bookableResourceId</a>

Shows the resource.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresourceid</td></tr></table>

### <a href=#calendarId name="calendarId">calendarId</a>

Shows the calendar used for staffing this project team.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calendar Id</td></tr><tr><td>description</td><td>Shows the calendar used for staffing this project team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_calendarid</td></tr></table>

### <a href=#description name="description">description</a>

Type the system description.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the system description.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#from name="from">from</a>

Enter the resource team membership start date.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Enter the resource team membership start date.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_from</td></tr></table>

### <a href=#hardBookedHours name="hardBookedHours">hardBookedHours</a>

Hard Booked Hours  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hard Booked Hours</td></tr><tr><td>description</td><td>Hard Booked Hours</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_hardbookedhours</td></tr></table>

### <a href=#hours name="hours">hours</a>

Duplicate for resource requirement  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hours</td></tr><tr><td>description</td><td>Duplicate for resource requirement</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_hours</td></tr></table>

### <a href=#hoursRequested name="hoursRequested">hoursRequested</a>

Shows the number of hours required of this team member on the project.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required Hours (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Shows the number of hours required of this team member on the project.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_hoursrequested</td></tr></table>

### <a href=#membershipStatus name="membershipStatus">membershipStatus</a>

Shows the membership status of this project team member.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Membership Status (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Shows the membership status of this project team member.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_membershipstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Requested</td><td>1</td></tr><tr><td>en</td><td>Assigned</td><td>2</td></tr><tr><td>en</td><td>Declined</td><td>3</td></tr></table></td></tr></table>

### <a href=#membershipStatus_display name="membershipStatus_display">membershipStatus_display</a>

First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#MSProjectClientId name="MSProjectClientId">MSProjectClientId</a>

The id of the project team member in MS Project Client.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>MS Project Client Id</td></tr><tr><td>description</td><td>The id of the project team member in MS Project Client.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_msprojectclientid</td></tr></table>

### <a href=#number name="number">number</a>

Shows the number of resources requested.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number</td></tr><tr><td>description</td><td>Shows the number of resources requested.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_number</td></tr></table>

### <a href=#resourcingUnit name="resourcingUnit">resourcingUnit</a>

The organizational unit of the resource performing the work.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resourcing Unit</td></tr><tr><td>description</td><td>The organizational unit of the resource performing the work.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_organizationalunit</td></tr></table>

### <a href=#percentage name="percentage">percentage</a>

Duplicate for resource requirement  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage</td></tr><tr><td>description</td><td>Duplicate for resource requirement</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_percentage</td></tr></table>

### <a href=#project name="project">project</a>

Select the project that this team members are part of.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>project</td></tr><tr><td>description</td><td>Select the project that this team members are part of.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#projectApprover name="projectApprover">projectApprover</a>

Select whether the team member can approve time and expenses.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Approver</td></tr><tr><td>description</td><td>Select whether the team member can approve time and expenses.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectapprover</td></tr></table>

### <a href=#requiredHours name="requiredHours">requiredHours</a>

Required hours of team member from team member requirement  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required Hours</td></tr><tr><td>description</td><td>Required hours of team member from team member requirement</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requiredhours</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Select the role this team member is playing in this team.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Select the role this team member is playing in this team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#resourceRequirementId name="resourceRequirementId">resourceRequirementId</a>

Unique identifier for Resource Requirement associated with Project Team Member.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Requirement</td></tr><tr><td>description</td><td>Unique identifier for Resource Requirement associated with Project Team Member.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcerequirementid</td></tr></table>

### <a href=#roleDescription name="roleDescription">roleDescription</a>

Enter a description of the role for this team member.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Position Description</td></tr><tr><td>description</td><td>Enter a description of the role for this team member.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_roledescription</td></tr></table>

### <a href=#softBookedHours name="softBookedHours">softBookedHours</a>

Soft Booked Hours  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Soft Booked Hours</td></tr><tr><td>description</td><td>Soft Booked Hours</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_softbookedhours</td></tr></table>

### <a href=#to name="to">to</a>

Enter the end date of the resource membership in a team.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To</td></tr><tr><td>description</td><td>Enter the end date of the resource membership in a team.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_to</td></tr></table>

### <a href=#workTemplate name="workTemplate">workTemplate</a>

Template to use for generic resource's schedule. Will be ignored if its a user or facility resource  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work Template</td></tr><tr><td>description</td><td>Template to use for generic resource's schedule. Will be ignored if its a user or facility resource</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_worktemplate</td></tr></table>

### <a href=#applicantCount name="applicantCount">applicantCount</a>

Shows the number of applicants for this project team.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applicant count</td></tr><tr><td>description</td><td>Shows the number of applicants for this project team.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_applicantcount</td></tr></table>

### <a href=#applicantCountDate name="applicantCountDate">applicantCountDate</a>

Last Updated time of rollup field Applicant count.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applicant count (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Applicant count.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_applicantcount_date</td></tr></table>

### <a href=#applicantCountState name="applicantCountState">applicantCountState</a>

State of rollup field Applicant count.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applicant count (State)</td></tr><tr><td>description</td><td>State of rollup field Applicant count.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_applicantcount_state</td></tr></table>

### <a href=#applicantsAvailable name="applicantsAvailable">applicantsAvailable</a>

Shows if there are applicants available for this project team.  
First included in: projectServiceAutomation/ProjectTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applicants available (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Shows if there are applicants available for this project team.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_applicantsavailable</td></tr></table>
