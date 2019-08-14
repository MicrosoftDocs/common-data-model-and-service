---
title: EmploymentHistory - Common Data Model | Microsoft Docs
description: This describes the EmploymentHistory entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Employment History

Employment History represents historical and/or current information about where a contact works, volunteers or serves in some capacity at an organization.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/EmploymentHistory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/EmploymentHistory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[ownerId](#ownerId)|Owner Id|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[employmentHistoryId](#employmentHistoryId)|Unique identifier for entity instances|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[stateCode](#stateCode)|Status of the Employment History|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[stateCode_display](#stateCode_display)||<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[statusCode](#statusCode)|Reason for the status of the Employment History|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[statusCode_display](#statusCode_display)||<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[name](#name)||<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[contactId](#contactId)||<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[currentEmployment](#currentEmployment)|Is this record a presumed current position?|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[employerId](#employerId)|Employer|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[employerName](#employerName)|Employer Name|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[employmentEndDate](#employmentEndDate)|End Date of work.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[employmentStartDate](#employmentStartDate)|Start Date of work.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[industry](#industry)|Type of Industry that the employee has worked for.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[industry_display](#industry_display)||<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[occupation](#occupation)|Occupation of the employee.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[occupation_display](#occupation_display)||<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|
|[title](#title)|Title of the Job or position of the employee.|<a href="EmploymentHistory.md" target="_blank">nonProfit/EmploymentHistory</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#employmentHistoryId name="employmentHistoryId">employmentHistoryId</a>

Unique identifier for entity instances  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employment History</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_employmenthistoryid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Employment History  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Employment History</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Employment History  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Employment History</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_contactid</td></tr></table>

### <a href=#currentEmployment name="currentEmployment">currentEmployment</a>

Is this record a presumed current position?  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Employment</td></tr><tr><td>description</td><td>Is this record a presumed current position?</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_currentemployment</td></tr></table>

### <a href=#employerId name="employerId">employerId</a>

Employer  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employer</td></tr><tr><td>description</td><td>Employer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_employerid</td></tr></table>

### <a href=#employerName name="employerName">employerName</a>

Employer Name  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employer Name</td></tr><tr><td>description</td><td>Employer Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_employername</td></tr></table>

### <a href=#employmentEndDate name="employmentEndDate">employmentEndDate</a>

End Date of work.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employment End Date</td></tr><tr><td>description</td><td>End Date of work.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_employmentenddate</td></tr></table>

### <a href=#employmentStartDate name="employmentStartDate">employmentStartDate</a>

Start Date of work.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employment Start Date</td></tr><tr><td>description</td><td>Start Date of work.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_employmentstartdate</td></tr></table>

### <a href=#industry name="industry">industry</a>

Type of Industry that the employee has worked for.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Industry</td></tr><tr><td>description</td><td>Type of Industry that the employee has worked for.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_industry</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Finance</td><td>100000000</td></tr><tr><td>en</td><td>Retail</td><td>100000001</td></tr><tr><td>en</td><td>Aumotive</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#industry_display name="industry_display">industry_display</a>

First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#occupation name="occupation">occupation</a>

Occupation of the employee.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Occupation</td></tr><tr><td>description</td><td>Occupation of the employee.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_occupation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Sales</td><td>100000000</td></tr><tr><td>en</td><td>Marketing</td><td>100000001</td></tr><tr><td>en</td><td>Manager</td><td>100000002</td></tr><tr><td>en</td><td>Executive</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#occupation_display name="occupation_display">occupation_display</a>

First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#title name="title">title</a>

Title of the Job or position of the employee.  
First included in: nonProfit/EmploymentHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Title of the Job or position of the employee.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_title</td></tr></table>
