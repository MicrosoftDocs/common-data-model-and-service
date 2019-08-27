---
title: MarketingForm - Common Data Model | Microsoft Docs
description: This describes the MarketingForm entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Marketing Form

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/MarketingForm.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/MarketingForm  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[ownerId](#ownerId)|Owner Id|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[marketingFormId](#marketingFormId)|Unique ID for entity instances|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[stateCode](#stateCode)|Status of the marketing form|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[stateCode_display](#stateCode_display)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[statusCode](#statusCode)|Reason for the status of the marketing form|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[statusCode_display](#statusCode_display)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[name](#name)|The name of the custom entity.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[allowPrefill](#allowPrefill)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[contactMatchingStrategy](#contactMatchingStrategy)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[updateContactsLeads](#updateContactsLeads)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[updateContactsLeads_display](#updateContactsLeads_display)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[marketingFormTemplate](#marketingFormTemplate)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[formControlMapping](#formControlMapping)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[formDefinition](#formDefinition)|JSON definition of the fields related to the Marketing form entity.|<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[insightsPlaceholder](#insightsPlaceholder)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[leadMatchingStrategy](#leadMatchingStrategy)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[validForPageType](#validForPageType)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[validForPageType_display](#validForPageType_display)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[purpose](#purpose)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[purpose_display](#purpose_display)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[visualStyle](#visualStyle)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|
|[visualStyle_display](#visualStyle_display)||<a href="MarketingForm.md" target="_blank">marketing/MarketingForm</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#marketingFormId name="marketingFormId">marketingFormId</a>

Unique ID for entity instances  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing form</td></tr><tr><td>description</td><td>Unique ID for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_marketingformid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the marketing form  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the marketing form</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the marketing form  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status reason</td></tr><tr><td>description</td><td>Reason for the status of the marketing form</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#allowPrefill name="allowPrefill">allowPrefill</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prefill fields</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_allowprefill</td></tr></table>

### <a href=#contactMatchingStrategy name="contactMatchingStrategy">contactMatchingStrategy</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact matching strategy</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_contactmatchingstrategy</td></tr></table>

### <a href=#updateContactsLeads name="updateContactsLeads">updateContactsLeads</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update contacts/leads</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_entityupdatebehavioronsubmit</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Contacts and leads</td><td>0</td></tr><tr><td>en</td><td>Only contacts</td><td>1</td></tr><tr><td>en</td><td>Only leads</td><td>2</td></tr></table></td></tr></table>

### <a href=#updateContactsLeads_display name="updateContactsLeads_display">updateContactsLeads_display</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#marketingFormTemplate name="marketingFormTemplate">marketingFormTemplate</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing form template</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_marketingformtemplate</td></tr></table>

### <a href=#formControlMapping name="formControlMapping">formControlMapping</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form control mapping</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_formcontrolmapping</td></tr></table>

### <a href=#formDefinition name="formDefinition">formDefinition</a>

JSON definition of the fields related to the Marketing form entity.  
First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form definition</td></tr><tr><td>description</td><td>JSON definition of the fields related to the Marketing form entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_formdefinition</td></tr></table>

### <a href=#insightsPlaceholder name="insightsPlaceholder">insightsPlaceholder</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insights</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_insights_placeholder</td></tr></table>

### <a href=#leadMatchingStrategy name="leadMatchingStrategy">leadMatchingStrategy</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead matching strategy</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_leadmatchingstrategy</td></tr></table>

### <a href=#validForPageType name="validForPageType">validForPageType</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_validforpagetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Landing Page</td><td>0</td></tr><tr><td>en</td><td>Subscription center</td><td>1</td></tr><tr><td>en</td><td>Forward to a friend</td><td>2</td></tr></table></td></tr></table>

### <a href=#validForPageType_display name="validForPageType_display">validForPageType_display</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#purpose name="purpose">purpose</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purpose</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_purpose</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Contact capture</td><td>0</td></tr><tr><td>en</td><td>Newsletter subscription</td><td>1</td></tr><tr><td>en</td><td>Lead generation</td><td>2</td></tr><tr><td>en</td><td>Collateral download</td><td>3</td></tr><tr><td>en</td><td>Event registration</td><td>4</td></tr><tr><td>en</td><td>Event feedback</td><td>5</td></tr><tr><td>en</td><td>Structural</td><td>6</td></tr></table></td></tr></table>

### <a href=#purpose_display name="purpose_display">purpose_display</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#visualStyle name="visualStyle">visualStyle</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visual style</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_visualstyle</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>1-column</td><td>0</td></tr><tr><td>en</td><td>2-column</td><td>1</td></tr><tr><td>en</td><td>Mixed</td><td>2</td></tr></table></td></tr></table>

### <a href=#visualStyle_display name="visualStyle_display">visualStyle_display</a>

First included in: marketing/MarketingForm (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
