---
title: Review - Common Data Model | Microsoft Docs
description: This describes the Review entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Review

The assessment of a Request made by an internal staff member (or team) or an external third party individual or entity (i.e. Consultant) and all of the relevant information that needs to be tracked.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Review.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Review  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[reviewId](#reviewId)|Unique identifier for entity instances|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[stateCode](#stateCode)|Status of the Review|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[stateCode_display](#stateCode_display)||<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[statusCode](#statusCode)|Reason for the status of the Review|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[statusCode_display](#statusCode_display)||<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[name](#name)||<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[awardId](#awardId)|Award|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[awardVersionId](#awardVersionId)|Award Version|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[dateSubmitted](#dateSubmitted)|Date Review was submitted.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[description](#description)|Description of the Review.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[dueDate](#dueDate)|Date the review is due.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[requestId](#requestId)|Request|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[reviewDocketId](#reviewDocketId)|Docket|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[reviewLeadId](#reviewLeadId)|Lead|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[reviewReportId](#reviewReportId)|Report|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[reviewDate](#reviewDate)|Date the review was conducted.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[reviewerId](#reviewerId)|Reviewer|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[reviewerType](#reviewerType)|Indicates the type of Reviewer.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[reviewerType_display](#reviewerType_display)||<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[status](#status)|Status of the Review.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[status_display](#status_display)||<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[type](#type)|The type of Review.|<a href="Review.md" target="_blank">nonProfit/Review</a>|
|[type_display](#type_display)||<a href="Review.md" target="_blank">nonProfit/Review</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#reviewId name="reviewId">reviewId</a>

Unique identifier for entity instances  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Review</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_reviewid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Review  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Review</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Review  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Review</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#awardId name="awardId">awardId</a>

Award  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Award</td></tr><tr><td>description</td><td>Award</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_awardid</td></tr></table>

### <a href=#awardVersionId name="awardVersionId">awardVersionId</a>

Award Version  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Award Version</td></tr><tr><td>description</td><td>Award Version</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_awardversionid</td></tr></table>

### <a href=#dateSubmitted name="dateSubmitted">dateSubmitted</a>

Date Review was submitted.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Submitted</td></tr><tr><td>description</td><td>Date Review was submitted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datesubmitted</td></tr></table>

### <a href=#description name="description">description</a>

Description of the Review.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the Review.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_description</td></tr></table>

### <a href=#dueDate name="dueDate">dueDate</a>

Date the review is due.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Date the review is due.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_duedate</td></tr></table>

### <a href=#requestId name="requestId">requestId</a>

Request  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request</td></tr><tr><td>description</td><td>Request</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_requestid</td></tr></table>

### <a href=#reviewDocketId name="reviewDocketId">reviewDocketId</a>

Docket  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Docket</td></tr><tr><td>description</td><td>Docket</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_review_docketid</td></tr></table>

### <a href=#reviewLeadId name="reviewLeadId">reviewLeadId</a>

Lead  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead</td></tr><tr><td>description</td><td>Lead</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_review_leadid</td></tr></table>

### <a href=#reviewReportId name="reviewReportId">reviewReportId</a>

Report  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Report</td></tr><tr><td>description</td><td>Report</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_review_reportid</td></tr></table>

### <a href=#reviewDate name="reviewDate">reviewDate</a>

Date the review was conducted.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Review Date</td></tr><tr><td>description</td><td>Date the review was conducted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_reviewdate</td></tr></table>

### <a href=#reviewerId name="reviewerId">reviewerId</a>

Reviewer  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reviewer</td></tr><tr><td>description</td><td>Reviewer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_reviewerid</td></tr></table>

### <a href=#reviewerType name="reviewerType">reviewerType</a>

Indicates the type of Reviewer.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reviewer Type</td></tr><tr><td>description</td><td>Indicates the type of Reviewer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_reviewertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Type A</td><td>100000000</td></tr><tr><td>en</td><td>Type B</td><td>100000001</td></tr></table></td></tr></table>

### <a href=#reviewerType_display name="reviewerType_display">reviewerType_display</a>

First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#status name="status">status</a>

Status of the Review.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Review.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Ready to Review</td><td>100000000</td></tr><tr><td>en</td><td>Review in Progress</td><td>100000001</td></tr><tr><td>en</td><td>Review Submitted</td><td>100000002</td></tr><tr><td>en</td><td>Deadline Passed</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#type name="type">type</a>

The type of Review.  
First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>The type of Review.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Type A</td><td>100000000</td></tr><tr><td>en</td><td>Type B</td><td>100000001</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: nonProfit/Review (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
