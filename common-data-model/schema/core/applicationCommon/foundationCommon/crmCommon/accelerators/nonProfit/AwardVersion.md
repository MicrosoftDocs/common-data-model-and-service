---
title: AwardVersion - Common Data Model | Microsoft Docs
description: An Award Version represents a point in time snapshot of the attributes of an Award.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Award Version

An Award Version represents a point in time snapshot of the attributes of an Award.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/AwardVersion.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/AwardVersion  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[ownerId](#ownerId)|Owner Id|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[awardVersionId](#awardVersionId)|Unique identifier for entity instances|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[stateCode](#stateCode)|Status of the Award Version|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[stateCode_display](#stateCode_display)||<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[statusCode](#statusCode)|Reason for the status of the Award Version|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[statusCode_display](#statusCode_display)||<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[name](#name)|The name of the custom entity.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[awardDate](#awardDate)|Date award was made.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[awardEndDate](#awardEndDate)|Date Award related Activities end.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[awardId](#awardId)|Award|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[awardStartDate](#awardStartDate)|Date Award related Activities begin. Award may be won in June but related activities do not begin until July.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[description](#description)||<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[enrollmentStartDate](#enrollmentStartDate)|Manually populated field on a Award record indicating when an Awardee may enroll in Award Activity.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[performanceMeasuresSummary](#performanceMeasuresSummary)|Brief overview of performance measures as set by Awarder in contract agreement|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[primaryContactId](#primaryContactId)|Brief overview of performance measures as set by Awarder in contract agreement|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[reportingSchedule](#reportingSchedule)|Manually populated,indicates the frequency that Award reports are scheduled to be disbursed as agreed in donor contract. These can include financial statements, narrative assessments, Impact reports,|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[status](#status)|Status of the Report.|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[status_display](#status_display)||<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|
|[submittedById](#submittedById)|Submitted By|<a href="AwardVersion.md" target="_blank">nonProfit/AwardVersion</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#awardVersionId name="awardVersionId">awardVersionId</a>

Unique identifier for entity instances  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Award Version</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_awardversionid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Award Version  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Award Version</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Award Version  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Award Version</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#awardDate name="awardDate">awardDate</a>

Date award was made.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Award Date</td></tr><tr><td>description</td><td>Date award was made.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_awarddate</td></tr></table>

### <a href=#awardEndDate name="awardEndDate">awardEndDate</a>

Date Award related Activities end.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Award End Date</td></tr><tr><td>description</td><td>Date Award related Activities end.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_awardenddate</td></tr></table>

### <a href=#awardId name="awardId">awardId</a>

Award  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Award</td></tr><tr><td>description</td><td>Award</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_awardid</td></tr></table>

### <a href=#awardStartDate name="awardStartDate">awardStartDate</a>

Date Award related Activities begin. Award may be won in June but related activities do not begin until July.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Award Start Date</td></tr><tr><td>description</td><td>Date Award related Activities begin. Award may be won in June but related activities do not begin until July.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_awardstartdate</td></tr></table>

### <a href=#description name="description">description</a>

First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2048</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_description</td></tr></table>

### <a href=#enrollmentStartDate name="enrollmentStartDate">enrollmentStartDate</a>

Manually populated field on a Award record indicating when an Awardee may enroll in Award Activity.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enrollment Start Date</td></tr><tr><td>description</td><td>Manually populated field on a Award record indicating when an Awardee may enroll in Award Activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_enrollmentstartdate</td></tr></table>

### <a href=#performanceMeasuresSummary name="performanceMeasuresSummary">performanceMeasuresSummary</a>

Brief overview of performance measures as set by Awarder in contract agreement  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performance Measures Smmary</td></tr><tr><td>description</td><td>Brief overview of performance measures as set by Awarder in contract agreement</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2048</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_performancemeasuressummary</td></tr></table>

### <a href=#primaryContactId name="primaryContactId">primaryContactId</a>

Brief overview of performance measures as set by Awarder in contract agreement  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Contact</td></tr><tr><td>description</td><td>Brief overview of performance measures as set by Awarder in contract agreement</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_primarycontactid</td></tr></table>

### <a href=#reportingSchedule name="reportingSchedule">reportingSchedule</a>

Manually populated,indicates the frequency that Award reports are scheduled to be disbursed as agreed in donor contract. These can include financial statements, narrative assessments, Impact reports,  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reporting Schedule</td></tr><tr><td>description</td><td>Manually populated,indicates the frequency that Award reports are scheduled to be disbursed as agreed in donor contract. These can include financial statements, narrative assessments, Impact reports,</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2048</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_reportingschedule</td></tr></table>

### <a href=#status name="status">status</a>

Status of the Report.  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Report.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>844060000</td></tr><tr><td>en</td><td>Submitted</td><td>844060001</td></tr><tr><td>en</td><td>Under Review</td><td>844060002</td></tr><tr><td>en</td><td>Approved</td><td>844060003</td></tr><tr><td>en</td><td>Rejected</td><td>844060004</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#submittedById name="submittedById">submittedById</a>

Submitted By  
First included in: nonProfit/AwardVersion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted By</td></tr><tr><td>description</td><td>Submitted By</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_submittedbyid</td></tr></table>
