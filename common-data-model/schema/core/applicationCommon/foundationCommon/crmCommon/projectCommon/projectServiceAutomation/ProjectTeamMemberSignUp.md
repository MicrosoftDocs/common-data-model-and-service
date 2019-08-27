---
title: ProjectTeamMemberSignUp - Common Data Model | Microsoft Docs
description: Entity used to capture all resources that have applied for open position on projects.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Project Team Member Sign-Up (Deprecated in v3.0)

Entity used to capture all resources that have applied for open position on projects.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectTeamMemberSignUp.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectTeamMemberSignUp  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[projectTeamMemberSignUpId](#projectTeamMemberSignUpId)|Unique identifier for entity instances|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[stateCode](#stateCode)|Status of the Project Team Member Sign-Up|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[stateCode_display](#stateCode_display)||<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[statusCode](#statusCode)|Reason for the status of the Project Team Member Sign-Up|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[statusCode_display](#statusCode_display)||<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[defaultDescription](#defaultDescription)|Type a description of the entity.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[bookableResource](#bookableResource)|Shows the name of the resource signing up for this project team.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[membershipStatus](#membershipStatus)|Select the membership status.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[membershipStatus_display](#membershipStatus_display)||<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|
|[teamMembership](#teamMembership)|Shows the team membership for the person signing up for this project team.|<a href="ProjectTeamMemberSignUp.md" target="_blank">projectServiceAutomation/ProjectTeamMemberSignUp</a>|

### <a href=#projectTeamMemberSignUpId name="projectTeamMemberSignUpId">projectTeamMemberSignUpId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Team Member Sign-Up</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_projectteammembersignupid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applied Date</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Project Team Member Sign-Up  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Project Team Member Sign-Up</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Project Team Member Sign-Up  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Project Team Member Sign-Up</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#defaultDescription name="defaultDescription">defaultDescription</a>

Type a description of the entity.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Description</td></tr><tr><td>description</td><td>Type a description of the entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Shows the name of the resource signing up for this project team.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the name of the resource signing up for this project team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#membershipStatus name="membershipStatus">membershipStatus</a>

Select the membership status.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Membership Status</td></tr><tr><td>description</td><td>Select the membership status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_membershipstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Requested</td><td>1</td></tr><tr><td>en</td><td>Assigned</td><td>2</td></tr><tr><td>en</td><td>Declined</td><td>3</td></tr></table></td></tr></table>

### <a href=#membershipStatus_display name="membershipStatus_display">membershipStatus_display</a>

First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#teamMembership name="teamMembership">teamMembership</a>

Shows the team membership for the person signing up for this project team.  
First included in: projectServiceAutomation/ProjectTeamMemberSignUp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team Membership</td></tr><tr><td>description</td><td>Shows the team membership for the person signing up for this project team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_teammembership</td></tr></table>
