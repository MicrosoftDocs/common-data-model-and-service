---
title: LinkedInFormQuestion - Common Data Model | Microsoft Docs
description: This describes the LinkedInFormQuestion entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# LinkedIn Form Question

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInFormQuestion.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInFormQuestion  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[ownerId](#ownerId)|Owner Id|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[linkedInFormQuestionId](#linkedInFormQuestionId)|Unique identifier for entity instances|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[stateCode](#stateCode)|Status of the LinkedIn Form Question|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[stateCode_display](#stateCode_display)||<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[statusCode](#statusCode)|Reason for the status of the LinkedIn Form Question|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[statusCode_display](#statusCode_display)||<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[name](#name)|Enter the LinkedIn form question name|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[displayName](#displayName)|Display name on the LinkedIn form|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[isCustomQuestion](#isCustomQuestion)||<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[linkedinForm](#linkedinForm)|LinkedIn form where this question appears|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[linkedInID](#linkedInID)|Unique identifier of the form question on LinkedIn|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[linkedInPredefinedField](#linkedInPredefinedField)||<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[responseEditable](#responseEditable)|Can a LinkedIn user edit this response, or is it pre-filled based on their profile?|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|
|[responseType](#responseType)|Response format used for this question|<a href="LinkedInFormQuestion.md" target="_blank">LinkedInLeads/LinkedInFormQuestion</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#linkedInFormQuestionId name="linkedInFormQuestionId">linkedInFormQuestionId</a>

Unique identifier for entity instances  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Form Question</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinformquestionid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the LinkedIn Form Question  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the LinkedIn Form Question</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the LinkedIn Form Question  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the LinkedIn Form Question</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Enter the LinkedIn form question name  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Enter the LinkedIn form question name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#displayName name="displayName">displayName</a>

Display name on the LinkedIn form  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display name</td></tr><tr><td>description</td><td>Display name on the LinkedIn form</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_displayname</td></tr></table>

### <a href=#isCustomQuestion name="isCustomQuestion">isCustomQuestion</a>

First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Custom Question</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_iscustomquestion</td></tr></table>

### <a href=#linkedinForm name="linkedinForm">linkedinForm</a>

LinkedIn form where this question appears  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn form</td></tr><tr><td>description</td><td>LinkedIn form where this question appears</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinform</td></tr></table>

### <a href=#linkedInID name="linkedInID">linkedInID</a>

Unique identifier of the form question on LinkedIn  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn ID</td></tr><tr><td>description</td><td>Unique identifier of the form question on LinkedIn</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinid</td></tr></table>

### <a href=#linkedInPredefinedField name="linkedInPredefinedField">linkedInPredefinedField</a>

First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Predefined Field</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinpredefinedfield</td></tr></table>

### <a href=#responseEditable name="responseEditable">responseEditable</a>

Can a LinkedIn user edit this response, or is it pre-filled based on their profile?  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Response editable</td></tr><tr><td>description</td><td>Can a LinkedIn user edit this response, or is it pre-filled based on their profile?</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_responseeditable</td></tr></table>

### <a href=#responseType name="responseType">responseType</a>

Response format used for this question  
First included in: LinkedInLeads/LinkedInFormQuestion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Response type</td></tr><tr><td>description</td><td>Response format used for this question</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_responsetype</td></tr></table>
