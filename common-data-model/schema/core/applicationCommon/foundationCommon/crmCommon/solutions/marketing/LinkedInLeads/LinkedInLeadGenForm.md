---
title: LinkedInLeadGenForm - Common Data Model | Microsoft Docs
description: Form shown to prospects on LinkedIn
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# LinkedIn Lead Gen Form

Form shown to prospects on LinkedIn  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInLeadGenForm.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInLeadGenForm  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[ownerId](#ownerId)|Owner Id|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[linkedinformId](#linkedinformId)|Unique identifier for entity instances|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[stateCode](#stateCode)|Status of the LinkedIn Form|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[stateCode_display](#stateCode_display)||<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[statusCode](#statusCode)|Reason for the status of the LinkedIn Form|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[statusCode_display](#statusCode_display)||<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[name](#name)|LinkedIn form name|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[description](#description)|Description of the LinkedIn form|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[headline](#headline)|Headline displayed to leads on LinkedIn|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[landingpageURL](#landingpageURL)|Landing page URL used on the LinkedIn form|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[lastSyncDate](#lastSyncDate)||<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[linkedInID](#linkedInID)|Unique identifier of the LinkedIn form|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[linkedInParentAccount](#linkedInParentAccount)|LinkedIn account record to which this form belongs to|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[localeCountry](#localeCountry)|Locale country information for the LinkedIn form|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[localeLanguage](#localeLanguage)|Locale language information for the LinkedIn form|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[privacyPolicyURL](#privacyPolicyURL)|Privacy policy URL displayed on the LinkedIn form|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[syncStatus](#syncStatus)||<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[syncStatus_display](#syncStatus_display)||<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[thankyoumessage](#thankyoumessage)|Thank you message to leads who submit a form on LinkedIn|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[totalSubmissions](#totalSubmissions)|Total number of submissions received on this form|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[totalsubmissionsDate](#totalsubmissionsDate)|Last Updated time of rollup field Total submissions.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|
|[totalsubmissionsState](#totalsubmissionsState)|State of rollup field Total submissions.|<a href="LinkedInLeadGenForm.md" target="_blank">LinkedInLeads/LinkedInLeadGenForm</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#linkedinformId name="linkedinformId">linkedinformId</a>

Unique identifier for entity instances  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Lead Gen Form</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinformid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the LinkedIn Form  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the LinkedIn Form</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the LinkedIn Form  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the LinkedIn Form</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

LinkedIn form name  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>LinkedIn form name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#description name="description">description</a>

Description of the LinkedIn form  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the LinkedIn form</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_description</td></tr></table>

### <a href=#headline name="headline">headline</a>

Headline displayed to leads on LinkedIn  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn form headline</td></tr><tr><td>description</td><td>Headline displayed to leads on LinkedIn</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_headline</td></tr></table>

### <a href=#landingpageURL name="landingpageURL">landingpageURL</a>

Landing page URL used on the LinkedIn form  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Landing page URL</td></tr><tr><td>description</td><td>Landing page URL used on the LinkedIn form</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_landingpageurl</td></tr></table>

### <a href=#lastSyncDate name="lastSyncDate">lastSyncDate</a>

First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Sync Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_lastsyncdate</td></tr></table>

### <a href=#linkedInID name="linkedInID">linkedInID</a>

Unique identifier of the LinkedIn form  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn ID</td></tr><tr><td>description</td><td>Unique identifier of the LinkedIn form</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinid</td></tr></table>

### <a href=#linkedInParentAccount name="linkedInParentAccount">linkedInParentAccount</a>

LinkedIn account record to which this form belongs to  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Account</td></tr><tr><td>description</td><td>LinkedIn account record to which this form belongs to</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinparentaccount</td></tr></table>

### <a href=#localeCountry name="localeCountry">localeCountry</a>

Locale country information for the LinkedIn form  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Locale country</td></tr><tr><td>description</td><td>Locale country information for the LinkedIn form</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_localecountry</td></tr></table>

### <a href=#localeLanguage name="localeLanguage">localeLanguage</a>

Locale language information for the LinkedIn form  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Locale language</td></tr><tr><td>description</td><td>Locale language information for the LinkedIn form</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_localelanguage</td></tr></table>

### <a href=#privacyPolicyURL name="privacyPolicyURL">privacyPolicyURL</a>

Privacy policy URL displayed on the LinkedIn form  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Privacy policy URL</td></tr><tr><td>description</td><td>Privacy policy URL displayed on the LinkedIn form</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_privacypolicyurl</td></tr></table>

### <a href=#syncStatus name="syncStatus">syncStatus</a>

First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sync status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_syncstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pending Synchronization</td><td>192350000</td></tr><tr><td>en</td><td>Active</td><td>192350001</td></tr><tr><td>en</td><td>No Form Submissions</td><td>192350002</td></tr><tr><td>en</td><td>Forbidden</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#syncStatus_display name="syncStatus_display">syncStatus_display</a>

First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#thankyoumessage name="thankyoumessage">thankyoumessage</a>

Thank you message to leads who submit a form on LinkedIn  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Thank you message</td></tr><tr><td>description</td><td>Thank you message to leads who submit a form on LinkedIn</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_thankyoumessage</td></tr></table>

### <a href=#totalSubmissions name="totalSubmissions">totalSubmissions</a>

Total number of submissions received on this form  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total submissions</td></tr><tr><td>description</td><td>Total number of submissions received on this form</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_totalsubmissions</td></tr></table>

### <a href=#totalsubmissionsDate name="totalsubmissionsDate">totalsubmissionsDate</a>

Last Updated time of rollup field Total submissions.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total submissions (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Total submissions.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_totalsubmissions_date</td></tr></table>

### <a href=#totalsubmissionsState name="totalsubmissionsState">totalsubmissionsState</a>

State of rollup field Total submissions.  
First included in: LinkedInLeads/LinkedInLeadGenForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total submissions (State)</td></tr><tr><td>description</td><td>State of rollup field Total submissions.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_totalsubmissions_state</td></tr></table>
