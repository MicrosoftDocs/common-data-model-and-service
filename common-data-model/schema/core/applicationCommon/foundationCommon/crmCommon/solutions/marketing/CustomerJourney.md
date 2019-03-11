---
title: CustomerJourney - Common Data Model | Microsoft Docs
description: This describes the CustomerJourney entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Customer Journey

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/CustomerJourney.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/CustomerJourney  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[customerJourneyId](#customerJourneyId)|Unique ID for entity instances.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[stateCode](#stateCode)|Status of the customer journey|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[stateCode_display](#stateCode_display)||<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[statusCode](#statusCode)|Reason for the status of the customer journey.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[statusCode_display](#statusCode_display)||<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[name](#name)|The name of the customer journey.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[contentSettingsId](#contentSettingsId)|Content settings that apply to this customer journey.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[customerJourneyDesignerState](#customerJourneyDesignerState)|The state of customer journey.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[customerJourneyTemplate](#customerJourneyTemplate)|The template used to create the initial layout of the customer journey.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[customerJourneyTimeZone](#customerJourneyTimeZone)|Effective time zone for this customer journey|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[description](#description)|Enter additional information to describe this customer journey.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[endDateTime](#endDateTime)|The end date of customer journey|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[insightsPlaceholder](#insightsPlaceholder)||<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[isRecurring](#isRecurring)|Tells whether the customer journey is recurring or not.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[publishedBy](#publishedBy)|Unique ID of the user who published the customer journey|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[purpose](#purpose)||<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[recurrenceCount](#recurrenceCount)|The number of iterations.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[recurrenceIntervalDays](#recurrenceIntervalDays)|The duration of the iteration (in days)|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[startDateTime](#startDateTime)|The start date of the customer journey.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[suppressionSegmentId](#suppressionSegmentId)|A segment that defines a list of contacts that are excluded from this customer journey.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[type](#type)||<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[type_display](#type_display)||<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[validationResults](#validationResults)||<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[workflowDefinition](#workflowDefinition)|The customer journey design definition.|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|
|[linkedInCampaign](#linkedInCampaign)|Link to LinkedIn Campaign|<a href="CustomerJourney.md" target="_blank">marketing/CustomerJourney</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#customerJourneyId name="customerJourneyId">customerJourneyId</a>

Unique ID for entity instances.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey</td></tr><tr><td>description</td><td>Unique ID for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_customerjourneyid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the customer journey  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the customer journey</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the customer journey.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status reason</td></tr><tr><td>description</td><td>Reason for the status of the customer journey.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>192350000</td><td>0</td></tr><tr><td>en</td><td>Live</td><td>192350001</td><td>0</td></tr><tr><td>en</td><td>Stopped</td><td>192350002</td><td>0</td></tr><tr><td>en</td><td>Live, Editable</td><td>192350003</td><td>0</td></tr><tr><td>en</td><td>Error</td><td>192350005</td><td>0</td></tr><tr><td>en</td><td>Going live</td><td>192350006</td><td>0</td></tr><tr><td>en</td><td>Stopping</td><td>192350007</td><td>0</td></tr><tr><td>en</td><td>Expired</td><td>192350004</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the customer journey.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the customer journey.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#contentSettingsId name="contentSettingsId">contentSettingsId</a>

Content settings that apply to this customer journey.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Content settings</td></tr><tr><td>description</td><td>Content settings that apply to this customer journey.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_contentsettingsid</td></tr></table>

### <a href=#customerJourneyDesignerState name="customerJourneyDesignerState">customerJourneyDesignerState</a>

The state of customer journey.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey designer state</td></tr><tr><td>description</td><td>The state of customer journey.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_customerjourneydesignerstate</td></tr></table>

### <a href=#customerJourneyTemplate name="customerJourneyTemplate">customerJourneyTemplate</a>

The template used to create the initial layout of the customer journey.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer journey template</td></tr><tr><td>description</td><td>The template used to create the initial layout of the customer journey.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_customerjourneytemplate</td></tr></table>

### <a href=#customerJourneyTimeZone name="customerJourneyTimeZone">customerJourneyTimeZone</a>

Effective time zone for this customer journey  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time zone</td></tr><tr><td>description</td><td>Effective time zone for this customer journey</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_customerjourneytimezone</td></tr></table>

### <a href=#description name="description">description</a>

Enter additional information to describe this customer journey.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Enter additional information to describe this customer journey.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_description</td></tr></table>

### <a href=#endDateTime name="endDateTime">endDateTime</a>

The end date of customer journey  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End date and time</td></tr><tr><td>description</td><td>The end date of customer journey</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_enddatetime</td></tr></table>

### <a href=#insightsPlaceholder name="insightsPlaceholder">insightsPlaceholder</a>

First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insights</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_insights_placeholder</td></tr></table>

### <a href=#isRecurring name="isRecurring">isRecurring</a>

Tells whether the customer journey is recurring or not.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is recurring</td></tr><tr><td>description</td><td>Tells whether the customer journey is recurring or not.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_isrecurring</td></tr></table>

### <a href=#publishedBy name="publishedBy">publishedBy</a>

Unique ID of the user who published the customer journey  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Published by</td></tr><tr><td>description</td><td>Unique ID of the user who published the customer journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_publishedby</td></tr></table>

### <a href=#purpose name="purpose">purpose</a>

First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purpose</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_purpose</td></tr></table>

### <a href=#recurrenceCount name="recurrenceCount">recurrenceCount</a>

The number of iterations.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence count</td></tr><tr><td>description</td><td>The number of iterations.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_recurrencecount</td></tr></table>

### <a href=#recurrenceIntervalDays name="recurrenceIntervalDays">recurrenceIntervalDays</a>

The duration of the iteration (in days)  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence interval (days)</td></tr><tr><td>description</td><td>The duration of the iteration (in days)</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_recurrenceintervaldays</td></tr></table>

### <a href=#startDateTime name="startDateTime">startDateTime</a>

The start date of the customer journey.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start date and time</td></tr><tr><td>description</td><td>The start date of the customer journey.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_startdatetime</td></tr></table>

### <a href=#suppressionSegmentId name="suppressionSegmentId">suppressionSegmentId</a>

A segment that defines a list of contacts that are excluded from this customer journey.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suppression segment</td></tr><tr><td>description</td><td>A segment that defines a list of contacts that are excluded from this customer journey.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_suppressionsegmentid</td></tr></table>

### <a href=#type name="type">type</a>

First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Automated</td><td>192350000</td></tr><tr><td>en</td><td>LinkedIn</td><td>192350001</td></tr><tr><td>en</td><td>LinkedIn</td><td>192350001</td></tr><tr><td>en</td><td>Automated</td><td>192350000</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#validationResults name="validationResults">validationResults</a>

First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Error check results</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_validationresults</td></tr></table>

### <a href=#workflowDefinition name="workflowDefinition">workflowDefinition</a>

The customer journey design definition.  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Workflow definition</td></tr><tr><td>description</td><td>The customer journey design definition.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_workflowdefinition</td></tr></table>

### <a href=#linkedInCampaign name="linkedInCampaign">linkedInCampaign</a>

Link to LinkedIn Campaign  
First included in: marketing/CustomerJourney (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Campaign</td></tr><tr><td>description</td><td>Link to LinkedIn Campaign</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncr2_linkedincampaign</td></tr></table>
