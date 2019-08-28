---
title: Recommendation - Common Data Model | Microsoft Docs
description: This is the mechanism through which Foundations provide recommendations back to a grant applicant.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Recommendation

This is the mechanism through which Foundations provide recommendations back to a grant applicant.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Recommendation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Recommendation  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[recommendationId](#recommendationId)|Unique identifier for entity instances|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[stateCode](#stateCode)|Status of the Recommendation|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[stateCode_display](#stateCode_display)||<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[statusCode](#statusCode)|Reason for the status of the Recommendation|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[statusCode_display](#statusCode_display)||<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[name](#name)||<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[communicationChannel](#communicationChannel)|The media used to communicate the Recommendation|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[communicationChannel_display](#communicationChannel_display)||<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[date](#date)|Date the Recommendation was made.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[dateSubmitted](#dateSubmitted)|Date Recommendation was submitted.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[description](#description)|Description of the Recommendation.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[recommendationLeadId](#recommendationLeadId)|Lead|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[recommenderAccountId](#recommenderAccountId)|On Behalf of Account|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[recommenderContactId](#recommenderContactId)|Recommended by Contact|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[requestId](#requestId)|Request|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[status](#status)|Status of the Recommendation.|<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|
|[status_display](#status_display)||<a href="Recommendation.md" target="_blank">nonProfit/Recommendation</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#recommendationId name="recommendationId">recommendationId</a>

Unique identifier for entity instances  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recommendation</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_recommendationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Recommendation  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Recommendation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Recommendation  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Recommendation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#communicationChannel name="communicationChannel">communicationChannel</a>

The media used to communicate the Recommendation  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Communication Channel</td></tr><tr><td>description</td><td>The media used to communicate the Recommendation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_communicationchannel</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>CommChannel</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#communicationChannel_display name="communicationChannel_display">communicationChannel_display</a>

First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#date name="date">date</a>

Date the Recommendation was made.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date</td></tr><tr><td>description</td><td>Date the Recommendation was made.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_date</td></tr></table>

### <a href=#dateSubmitted name="dateSubmitted">dateSubmitted</a>

Date Recommendation was submitted.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Submitted</td></tr><tr><td>description</td><td>Date Recommendation was submitted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datesubmitted</td></tr></table>

### <a href=#description name="description">description</a>

Description of the Recommendation.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the Recommendation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>32000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_description</td></tr></table>

### <a href=#recommendationLeadId name="recommendationLeadId">recommendationLeadId</a>

Lead  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead</td></tr><tr><td>description</td><td>Lead</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recommendation_leadid</td></tr></table>

### <a href=#recommenderAccountId name="recommenderAccountId">recommenderAccountId</a>

On Behalf of Account  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Behalf of Account</td></tr><tr><td>description</td><td>On Behalf of Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recommenderaccountid</td></tr></table>

### <a href=#recommenderContactId name="recommenderContactId">recommenderContactId</a>

Recommended by Contact  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recommended by Contact</td></tr><tr><td>description</td><td>Recommended by Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recommendercontactid</td></tr></table>

### <a href=#requestId name="requestId">requestId</a>

Request  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request</td></tr><tr><td>description</td><td>Request</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_requestid</td></tr></table>

### <a href=#status name="status">status</a>

Status of the Recommendation.  
First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Recommendation.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Ready to Review</td><td>100000000</td></tr><tr><td>en</td><td>Review in Progress</td><td>100000001</td></tr><tr><td>en</td><td>Review Submitted</td><td>100000002</td></tr><tr><td>en</td><td>Deadline Passed</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: nonProfit/Recommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
