---
title: CampaignActivityItem - Common Data Model | Microsoft Docs
description: Work item of a campaign activity, such as a list or sales literature.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Campaign Activity Item

Work item of a campaign activity, such as a list or sales literature.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/CampaignActivityItem.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/CampaignActivityItem  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[campaignActivityItemId](#campaignActivityItemId)|Unique identifier of the campaign activity item.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[name](#name)|name|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[campaignActivityIdType](#campaignActivityIdType)|The name of the entity linked by campaignActivityId|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[campaignActivityId](#campaignActivityId)|Unique identifier of the campaign activity for the item.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[itemId](#itemId)|Unique identifier of the item.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[itemObjectTypeCode](#itemObjectTypeCode)|Identification of the type of the campaign activity item.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[itemObjectTypeCode_display](#itemObjectTypeCode_display)||<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier of the business unit that owns the campaign activity item.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the campaign activity item.|<a href="CampaignActivityItem.md" target="_blank">crmCommon/CampaignActivityItem</a>|

### <a href=#campaignActivityItemId name="campaignActivityItemId">campaignActivityItemId</a>

Unique identifier of the campaign activity item.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the campaign activity item.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>campaignactivityitemid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

name  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>name</td></tr><tr><td>description</td><td>name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#campaignActivityIdType name="campaignActivityIdType">campaignActivityIdType</a>

The name of the entity linked by campaignActivityId  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>campaignActivityId Type</td></tr><tr><td>description</td><td>The name of the entity linked by campaignActivityId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>campaignactivityidtype</td></tr></table>

### <a href=#campaignActivityId name="campaignActivityId">campaignActivityId</a>

Unique identifier of the campaign activity for the item.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the campaign activity for the item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>campaignactivityid</td></tr></table>

### <a href=#itemId name="itemId">itemId</a>

Unique identifier of the item.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>itemid</td></tr></table>

### <a href=#itemObjectTypeCode name="itemObjectTypeCode">itemObjectTypeCode</a>

Identification of the type of the campaign activity item.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Identification of the type of the campaign activity item.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>itemobjecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#itemObjectTypeCode_display name="itemObjectTypeCode_display">itemObjectTypeCode_display</a>

First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier of the business unit that owns the campaign activity item.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the campaign activity item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the campaign activity item.  
First included in: crmCommon/CampaignActivityItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the user that owns the campaign activity item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>
