---
title: LinkedInLeadGenFormSubmission - Common Data Model | Microsoft Docs
description: Submissions from prospects on LinkedIn
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# LinkedIn Lead Gen Form Submission

Submissions from prospects on LinkedIn  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInLeadGenFormSubmission.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInLeadGenFormSubmission  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[ownerId](#ownerId)|Owner Id|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[linkedInFormSubmissionId](#linkedInFormSubmissionId)|Unique identifier of the LinkedIn form submission|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[stateCode](#stateCode)|Status of the LinkedIn Form Submission|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[stateCode_display](#stateCode_display)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[statusCode](#statusCode)|Reason for the status of the LinkedIn Form Submission|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[statusCode_display](#statusCode_display)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[name](#name)|The name of the custom entity.|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[lead](#lead)|Dynamics 365 lead associated with this submission|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[linkedInAccountID](#linkedInAccountID)|LinkedIn account this submission came from|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[linkedInCampaign](#linkedInCampaign)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[linkedInCampaignID](#linkedInCampaignID)|Unique identifier of the LinkedIn campaign this submission is for|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[linkedInCreativeID](#linkedInCreativeID)|Unique identifier of the LinkedIn creative campaign this submission is for|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[linkedinformId](#linkedinformId)|LinkedIn form this submission came from|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[linkedInLeadGenFormSubmissionTextId](#linkedInLeadGenFormSubmissionTextId)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[linkedInUserProfileID](#linkedInUserProfileID)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[matchingStatus](#matchingStatus)|Status of matching and lead association with Dynamics 365|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[matchingStatus_display](#matchingStatus_display)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[processingState](#processingState)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[processingState_display](#processingState_display)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[submissionDate](#submissionDate)|Date and time submission was captured|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[type](#type)|Submission type|<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[linkedInFormName](#linkedInFormName)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|
|[customerJourney](#customerJourney)||<a href="LinkedInLeadGenFormSubmission.md" target="_blank">LinkedInLeads/LinkedInLeadGenFormSubmission</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#linkedInFormSubmissionId name="linkedInFormSubmissionId">linkedInFormSubmissionId</a>

Unique identifier of the LinkedIn form submission  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn ID</td></tr><tr><td>description</td><td>Unique identifier of the LinkedIn form submission</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinformsubmissionid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the LinkedIn Form Submission  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the LinkedIn Form Submission</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the LinkedIn Form Submission  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the LinkedIn Form Submission</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#lead name="lead">lead</a>

Dynamics 365 lead associated with this submission  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead</td></tr><tr><td>description</td><td>Dynamics 365 lead associated with this submission</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_lead</td></tr></table>

### <a href=#linkedInAccountID name="linkedInAccountID">linkedInAccountID</a>

LinkedIn account this submission came from  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn account</td></tr><tr><td>description</td><td>LinkedIn account this submission came from</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinaccountid</td></tr></table>

### <a href=#linkedInCampaign name="linkedInCampaign">linkedInCampaign</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Campaign</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedincampaign</td></tr></table>

### <a href=#linkedInCampaignID name="linkedInCampaignID">linkedInCampaignID</a>

Unique identifier of the LinkedIn campaign this submission is for  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn campaign ID</td></tr><tr><td>description</td><td>Unique identifier of the LinkedIn campaign this submission is for</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedincampaignid</td></tr></table>

### <a href=#linkedInCreativeID name="linkedInCreativeID">linkedInCreativeID</a>

Unique identifier of the LinkedIn creative campaign this submission is for  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Creative ID</td></tr><tr><td>description</td><td>Unique identifier of the LinkedIn creative campaign this submission is for</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedincreativeid</td></tr></table>

### <a href=#linkedinformId name="linkedinformId">linkedinformId</a>

LinkedIn form this submission came from  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Lead Gen Form</td></tr><tr><td>description</td><td>LinkedIn form this submission came from</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinformid</td></tr></table>

### <a href=#linkedInLeadGenFormSubmissionTextId name="linkedInLeadGenFormSubmissionTextId">linkedInLeadGenFormSubmissionTextId</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Lead Gen Form Submission Text Id</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinformsubmission_textid</td></tr></table>

### <a href=#linkedInUserProfileID name="linkedInUserProfileID">linkedInUserProfileID</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn User Profile</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinuserprofileid</td></tr></table>

### <a href=#matchingStatus name="matchingStatus">matchingStatus</a>

Status of matching and lead association with Dynamics 365  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Matching status</td></tr><tr><td>description</td><td>Status of matching and lead association with Dynamics 365</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_matchingstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pending lead matching</td><td>192350000</td></tr><tr><td>en</td><td>New lead created</td><td>192350001</td></tr><tr><td>en</td><td>Updated existing lead</td><td>192350002</td></tr><tr><td>en</td><td>Match failed</td><td>192350003</td></tr><tr><td>en</td><td>Lead creation failed</td><td>192350004</td></tr><tr><td>en</td><td>Lead update failed</td><td>192350005</td></tr><tr><td>en</td><td>Lead matched but not updated</td><td>192350006</td></tr></table></td></tr></table>

### <a href=#matchingStatus_display name="matchingStatus_display">matchingStatus_display</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#processingState name="processingState">processingState</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Processing State</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_processingstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unprocessed</td><td>192350000</td></tr><tr><td>en</td><td>Processing Succeeded</td><td>192350001</td></tr><tr><td>en</td><td>Processing Failed</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#processingState_display name="processingState_display">processingState_display</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#submissionDate name="submissionDate">submissionDate</a>

Date and time submission was captured  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submission date</td></tr><tr><td>description</td><td>Date and time submission was captured</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_submissiondate</td></tr></table>

### <a href=#type name="type">type</a>

Submission type  
First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Submission type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_type</td></tr></table>

### <a href=#linkedInFormName name="linkedInFormName">linkedInFormName</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source Form</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinformname</td></tr></table>

### <a href=#customerJourney name="customerJourney">customerJourney</a>

First included in: LinkedInLeads/LinkedInLeadGenFormSubmission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncr2_customerjourney</td></tr></table>
