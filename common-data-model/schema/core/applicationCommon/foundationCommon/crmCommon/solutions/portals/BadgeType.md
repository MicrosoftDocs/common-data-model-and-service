---
title: BadgeType - Common Data Model | Microsoft Docs
description: This describes the BadgeType entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Badge Type

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/BadgeType.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/portals/BadgeType  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[badgeTypeId](#badgeTypeId)|Shows the entity instances.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[createdOn](#createdOn)|Shows the date and time when the record was created. The date and time are displayed in the time zone selected in the solution options. |<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was updated. The date and time are displayed in the time zone selected in the solution options. |<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[modifiedBy](#modifiedBy)|Shows who updated the record.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who updated the record on behalf of another user.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[organizationId](#organizationId)|Shows the organization.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[stateCode](#stateCode)|Status of the Badge Type|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[stateCode_display](#stateCode_display)||<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[statusCode](#statusCode)|Shows the reason for the status of the badge type.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[statusCode_display](#statusCode_display)||<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[importSequenceNumber](#importSequenceNumber)|Shows the sequence number of the import that created this record.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Shows the date and time when the record was migrated. The date and time are displayed in the time zone selected in the solution options. |<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Shows the time zone code that was in use when the record was created.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[name](#name)|Shows the name of the custom entity.|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[backgroundColor](#backgroundColor)|Enter a hex value or RGB or RGBA

ex: #FFFFFF
rgb(255,255,255)
rgba(255,255,255,0.5)|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[description](#description)||<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[displayText](#displayText)|Actual shown label for the badge|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|
|[iconName](#iconName)|Add font awesome name such as fa-user|<a href="BadgeType.md" target="_blank">portals/BadgeType</a>|

### <a href=#badgeTypeId name="badgeTypeId">badgeTypeId</a>

Shows the entity instances.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Badge Type</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>adx_badgetypeid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the record was created. The date and time are displayed in the time zone selected in the solution options.   
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was created. The date and time are displayed in the time zone selected in the solution options. </td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was updated. The date and time are displayed in the time zone selected in the solution options.   
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was updated. The date and time are displayed in the time zone selected in the solution options. </td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who updated the record.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who updated the record on behalf of another user.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Shows the organization.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Shows the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Badge Type  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Badge Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Shows the reason for the status of the badge type.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Shows the reason for the status of the badge type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Shows the sequence number of the import that created this record.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Shows the sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Shows the date and time when the record was migrated. The date and time are displayed in the time zone selected in the solution options.   
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was migrated. The date and time are displayed in the time zone selected in the solution options. </td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Shows the time zone code that was in use when the record was created.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Shows the time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Shows the name of the custom entity.  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Shows the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_name</td></tr></table>

### <a href=#backgroundColor name="backgroundColor">backgroundColor</a>

Enter a hex value or RGB or RGBA

ex: #FFFFFF
rgb(255,255,255)
rgba(255,255,255,0.5)  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Background Color</td></tr><tr><td>description</td><td>Enter a hex value or RGB or RGBA

ex: #FFFFFF
rgb(255,255,255)
rgba(255,255,255,0.5)</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>25</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_backgroundcolor</td></tr></table>

### <a href=#description name="description">description</a>

First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_description</td></tr></table>

### <a href=#displayText name="displayText">displayText</a>

Actual shown label for the badge  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display Text</td></tr><tr><td>description</td><td>Actual shown label for the badge</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>30</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_displaytext</td></tr></table>

### <a href=#iconName name="iconName">iconName</a>

Add font awesome name such as fa-user  
First included in: portals/BadgeType (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Icon Name</td></tr><tr><td>description</td><td>Add font awesome name such as fa-user</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>30</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_iconname</td></tr></table>
