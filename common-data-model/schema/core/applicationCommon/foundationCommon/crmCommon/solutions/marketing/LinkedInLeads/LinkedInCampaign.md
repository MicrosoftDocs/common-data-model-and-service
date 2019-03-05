---
title: LinkedInCampaign - Common Data Model | Microsoft Docs
description: Campaign used to capture submissions from prospects.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# LinkedIn Campaign

Campaign used to capture submissions from prospects.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInCampaign.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInCampaign  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[ownerId](#ownerId)|Owner Id|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[linkedInCampaignID](#linkedInCampaignID)|Unique identifier for entity instances|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[stateCode](#stateCode)|Status of the LinkedIn Campaign|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[stateCode_display](#stateCode_display)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[statusCode](#statusCode)|Reason for the status of the LinkedIn Campaign|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[statusCode_display](#statusCode_display)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[name](#name)|The name of the campaign.|<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[campaignType](#campaignType)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[campaignType_display](#campaignType_display)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[endDate](#endDate)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[linkedInAccount](#linkedInAccount)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[linkedInID](#linkedInID)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[linkedInStatus](#linkedInStatus)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[linkedInStatus_display](#linkedInStatus_display)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|
|[startDate](#startDate)||<a href="LinkedInCampaign.md" target="_blank">LinkedInLeads/LinkedInCampaign</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#linkedInCampaignID name="linkedInCampaignID">linkedInCampaignID</a>

Unique identifier for entity instances  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Campaign</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedincampaignid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the LinkedIn Campaign  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the LinkedIn Campaign</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the LinkedIn Campaign  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the LinkedIn Campaign</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the campaign.  
First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the campaign.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#campaignType name="campaignType">campaignType</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_campaigntype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>LinkedIn Dynamic Ad</td><td>192350003</td></tr><tr><td>en</td><td>LinkedIn Sponsored InMail</td><td>192350002</td></tr><tr><td>en</td><td>LinkedIn Sponsored Content</td><td>192350001</td></tr><tr><td>en</td><td>Text Advertisement</td><td>192350000</td></tr></table></td></tr></table>

### <a href=#campaignType_display name="campaignType_display">campaignType_display</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Proposed End Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_enddate</td></tr></table>

### <a href=#linkedInAccount name="linkedInAccount">linkedInAccount</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinaccount</td></tr></table>

### <a href=#linkedInID name="linkedInID">linkedInID</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinid</td></tr></table>

### <a href=#linkedInStatus name="linkedInStatus">linkedInStatus</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>192350000</td></tr><tr><td>en</td><td>Paused</td><td>192350001</td></tr><tr><td>en</td><td>Archived</td><td>192350002</td></tr><tr><td>en</td><td>Completed</td><td>192350003</td></tr><tr><td>en</td><td>Canceled</td><td>192350004</td></tr><tr><td>en</td><td>Draft</td><td>192350005</td></tr></table></td></tr></table>

### <a href=#linkedInStatus_display name="linkedInStatus_display">linkedInStatus_display</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

First included in: LinkedInLeads/LinkedInCampaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Proposed Start Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_startdate</td></tr></table>
