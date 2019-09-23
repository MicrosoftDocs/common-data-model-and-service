---
title: ProjectParameter - Common Data Model | Microsoft Docs
description: List of settings that determine the behavior of the project-based service solution.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Project Parameter

List of settings that determine the behavior of the project-based service solution.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectParameter.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectParameter  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[projectParameterId](#projectParameterId)|Shows the entity instances.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[stateCode](#stateCode)|Status of the Project Parameter|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[stateCode_display](#stateCode_display)||<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[statusCode](#statusCode)|Reason for the status of the Project Parameter|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[statusCode_display](#statusCode_display)||<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[description](#description)|Type the name of the project parameters.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[allowSkillUpdateByResource](#allowSkillUpdateByResource)|Allow resources to update their skills via the Project Finder Mobile app.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[defaultOrganizationalUnit](#defaultOrganizationalUnit)|Select the default organizational unit that will be used for new resources.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[defaultWorkTemplate](#defaultWorkTemplate)|Select the default work template for new projects.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[invoiceFrequency](#invoiceFrequency)|Select the default frequency for generating invoices.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[projectManagerRole](#projectManagerRole)|Shows the default role to be used when a project manager is added to the project team.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[projectResourceRequirementsVisibleToRe](#projectResourceRequirementsVisibleToRe)|Select whether project resource requirements are visible to resources.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[resourceAllocationMode](#resourceAllocationMode)|Select the default method for allocating resources to projects.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[resourceAllocationMode_display](#resourceAllocationMode_display)||<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|
|[teamMemberRole](#teamMemberRole)|Shows the default role to be used when a team member is added to the project team.|<a href="ProjectParameter.md" target="_blank">projectServiceAutomation/ProjectParameter</a>|

### <a href=#projectParameterId name="projectParameterId">projectParameterId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Parameter</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_projectparameterid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Project Parameter  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Project Parameter</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Project Parameter  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Project Parameter</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#description name="description">description</a>

Type the name of the project parameters.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the name of the project parameters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#allowSkillUpdateByResource name="allowSkillUpdateByResource">allowSkillUpdateByResource</a>

Allow resources to update their skills via the Project Finder Mobile app.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow skill update by resource (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Allow resources to update their skills via the Project Finder Mobile app.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_allowskillupdatebyresource</td></tr></table>

### <a href=#defaultOrganizationalUnit name="defaultOrganizationalUnit">defaultOrganizationalUnit</a>

Select the default organizational unit that will be used for new resources.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Organizational Unit</td></tr><tr><td>description</td><td>Select the default organizational unit that will be used for new resources.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultorganizationalunit</td></tr></table>

### <a href=#defaultWorkTemplate name="defaultWorkTemplate">defaultWorkTemplate</a>

Select the default work template for new projects.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>defaultWorkTemplate</td></tr><tr><td>description</td><td>Select the default work template for new projects.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultworktemplate</td></tr></table>

### <a href=#invoiceFrequency name="invoiceFrequency">invoiceFrequency</a>

Select the default frequency for generating invoices.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Frequency</td></tr><tr><td>description</td><td>Select the default frequency for generating invoices.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicefrequency</td></tr></table>

### <a href=#projectManagerRole name="projectManagerRole">projectManagerRole</a>

Shows the default role to be used when a project manager is added to the project team.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Manager Role</td></tr><tr><td>description</td><td>Shows the default role to be used when a project manager is added to the project team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectmanagerrole</td></tr></table>

### <a href=#projectResourceRequirementsVisibleToRe name="projectResourceRequirementsVisibleToRe">projectResourceRequirementsVisibleToRe</a>

Select whether project resource requirements are visible to resources.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource requirements visible to resources (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Select whether project resource requirements are visible to resources.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectresourcerequirementsvisibletore</td></tr></table>

### <a href=#resourceAllocationMode name="resourceAllocationMode">resourceAllocationMode</a>

Select the default method for allocating resources to projects.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource allocation mode</td></tr><tr><td>description</td><td>Select the default method for allocating resources to projects.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceallocationmode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Centralized</td><td>1</td></tr><tr><td>en</td><td>Hybrid</td><td>2</td></tr></table></td></tr></table>

### <a href=#resourceAllocationMode_display name="resourceAllocationMode_display">resourceAllocationMode_display</a>

First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#teamMemberRole name="teamMemberRole">teamMemberRole</a>

Shows the default role to be used when a team member is added to the project team.  
First included in: projectServiceAutomation/ProjectParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team Member Role</td></tr><tr><td>description</td><td>Shows the default role to be used when a team member is added to the project team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_teammemberrole</td></tr></table>
