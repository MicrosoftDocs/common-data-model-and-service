---
title: LinkedInAccount - Common Data Model | Microsoft Docs
description: The LinkedIn account where forms are created and published.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# LinkedIn Account

The LinkedIn account where forms are created and published.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInAccount.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/LinkedInLeads/LinkedInAccount  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[ownerId](#ownerId)|Owner Id|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[linkedInAccountID](#linkedInAccountID)|Unique identifier for entity instances|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[stateCode](#stateCode)|Status of the LinkedIn Account|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[stateCode_display](#stateCode_display)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[statusCode](#statusCode)|Reason for the status of the LinkedIn Account|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[statusCode_display](#statusCode_display)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[name](#name)|Account name|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[campaignSyncStatus](#campaignSyncStatus)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[campaignSyncStatus_display](#campaignSyncStatus_display)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[defaultLeadOwner](#defaultLeadOwner)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[syncEnabled](#syncEnabled)|Do you want to sync LinkedIn data related to this account?|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[lastCampaignSyncDate](#lastCampaignSyncDate)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[lastFormSyncDate](#lastFormSyncDate)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[linkedInAccountTextID](#linkedInAccountTextID)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[statusDetails](#statusDetails)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[formSyncStatus](#formSyncStatus)|Status of last sync of LinkedIn forms and submissions|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[formSyncStatus_display](#formSyncStatus_display)||<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[lastSync](#lastSync)|Date and time of last sync of LinkedIn form submissions|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[lastsynctimestamprollupDate](#lastsynctimestamprollupDate)|Last Updated time of rollup field Last sync.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|
|[lastsynctimestamprollupState](#lastsynctimestamprollupState)|State of rollup field Last sync.|<a href="LinkedInAccount.md" target="_blank">LinkedInLeads/LinkedInAccount</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#linkedInAccountID name="linkedInAccountID">linkedInAccountID</a>

Unique identifier for entity instances  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Account</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinaccountid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the LinkedIn Account  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the LinkedIn Account</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the LinkedIn Account  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the LinkedIn Account</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Account name  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Account name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#campaignSyncStatus name="campaignSyncStatus">campaignSyncStatus</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign sync status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_campaignsyncstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pending Synchronization</td><td>192350000</td></tr><tr><td>en</td><td>Active</td><td>192350001</td></tr><tr><td>en</td><td>No Active Campaigns Available</td><td>192350002</td></tr><tr><td>en</td><td>Forbidden</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#campaignSyncStatus_display name="campaignSyncStatus_display">campaignSyncStatus_display</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#defaultLeadOwner name="defaultLeadOwner">defaultLeadOwner</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Lead Owner</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_defaultleadowner</td></tr></table>

### <a href=#syncEnabled name="syncEnabled">syncEnabled</a>

Do you want to sync LinkedIn data related to this account?  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sync enabled</td></tr><tr><td>description</td><td>Do you want to sync LinkedIn data related to this account?</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_enabledforsync</td></tr></table>

### <a href=#lastCampaignSyncDate name="lastCampaignSyncDate">lastCampaignSyncDate</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Campaign Sync Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_lastcampaignsyncdate</td></tr></table>

### <a href=#lastFormSyncDate name="lastFormSyncDate">lastFormSyncDate</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Form Sync Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_lastsyncdate</td></tr></table>

### <a href=#linkedInAccountTextID name="linkedInAccountTextID">linkedInAccountTextID</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Account Text ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinaccounttextid</td></tr></table>

### <a href=#statusDetails name="statusDetails">statusDetails</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Details</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_statusdetails</td></tr></table>

### <a href=#formSyncStatus name="formSyncStatus">formSyncStatus</a>

Status of last sync of LinkedIn forms and submissions  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form sync status</td></tr><tr><td>description</td><td>Status of last sync of LinkedIn forms and submissions</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_syncstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Syncing</td><td>192350002</td></tr><tr><td>en</td><td>Pending Synchronization</td><td>192350000</td></tr><tr><td>en</td><td>Active</td><td>192350001</td></tr><tr><td>en</td><td>No Forms Available</td><td>192350003</td></tr><tr><td>en</td><td>Forbidden</td><td>192350004</td></tr></table></td></tr></table>

### <a href=#formSyncStatus_display name="formSyncStatus_display">formSyncStatus_display</a>

First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#lastSync name="lastSync">lastSync</a>

Date and time of last sync of LinkedIn form submissions  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last sync</td></tr><tr><td>description</td><td>Date and time of last sync of LinkedIn form submissions</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_lastsynctimestamprollup</td></tr></table>

### <a href=#lastsynctimestamprollupDate name="lastsynctimestamprollupDate">lastsynctimestamprollupDate</a>

Last Updated time of rollup field Last sync.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last sync (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Last sync.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_lastsynctimestamprollup_date</td></tr></table>

### <a href=#lastsynctimestamprollupState name="lastsynctimestamprollupState">lastsynctimestamprollupState</a>

State of rollup field Last sync.  
First included in: LinkedInLeads/LinkedInAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last sync (State)</td></tr><tr><td>description</td><td>State of rollup field Last sync.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_lastsynctimestamprollup_state</td></tr></table>
