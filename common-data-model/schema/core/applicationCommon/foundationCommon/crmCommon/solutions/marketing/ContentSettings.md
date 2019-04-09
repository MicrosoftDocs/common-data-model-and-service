---
title: ContentSettings - Common Data Model | Microsoft Docs
description: This describes the ContentSettings entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Content Settings

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/ContentSettings.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/ContentSettings  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[contentSettingsId](#contentSettingsId)|Unique ID for entity instances.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[stateCode](#stateCode)|Status of the Content Settings|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[stateCode_display](#stateCode_display)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[statusCode](#statusCode)|Content settings status reason|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[statusCode_display](#statusCode_display)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[name](#name)|The name of the custom entity.|<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[addressLine2](#addressLine2)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[addressMain](#addressMain)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[default](#default)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[facebookUrl](#facebookUrl)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[forwardToAFriend](#forwardToAFriend)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[linkedInUrl](#linkedInUrl)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[subscriptionCenter](#subscriptionCenter)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[twitterUrl](#twitterUrl)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[googlePlusUrl](#googlePlusUrl)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|
|[youtubeUrl](#youtubeUrl)||<a href="ContentSettings.md" target="_blank">marketing/ContentSettings</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#contentSettingsId name="contentSettingsId">contentSettingsId</a>

Unique ID for entity instances.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Content settings</td></tr><tr><td>description</td><td>Unique ID for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_contentsettingsid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Content Settings  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Content Settings</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Content settings status reason  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status reason</td></tr><tr><td>description</td><td>Content settings status reason</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>192350000</td><td>0</td></tr><tr><td>en</td><td>Live</td><td>192350001</td><td>0</td></tr><tr><td>en</td><td>Stopped</td><td>192350002</td><td>0</td></tr><tr><td>en</td><td>Live, Editable</td><td>192350003</td><td>0</td></tr><tr><td>en</td><td>Expired</td><td>192350004</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#addressLine2 name="addressLine2">addressLine2</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 2</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_addressline2</td></tr></table>

### <a href=#addressMain name="addressMain">addressMain</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address main</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_addressmain</td></tr></table>

### <a href=#default name="default">default</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_default</td></tr></table>

### <a href=#facebookUrl name="facebookUrl">facebookUrl</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facebook URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_facebookurl</td></tr></table>

### <a href=#forwardToAFriend name="forwardToAFriend">forwardToAFriend</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Forward to a friend</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_forwardtoafriend</td></tr></table>

### <a href=#linkedInUrl name="linkedInUrl">linkedInUrl</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_linkedinurl</td></tr></table>

### <a href=#subscriptionCenter name="subscriptionCenter">subscriptionCenter</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subscription center</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2098</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_subscriptioncenter</td></tr></table>

### <a href=#twitterUrl name="twitterUrl">twitterUrl</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Twitter URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_twitterurl</td></tr></table>

### <a href=#googlePlusUrl name="googlePlusUrl">googlePlusUrl</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Google Plus URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_googleplusurl</td></tr></table>

### <a href=#youtubeUrl name="youtubeUrl">youtubeUrl</a>

First included in: marketing/ContentSettings (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>YouTube URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_youtubeurl</td></tr></table>
