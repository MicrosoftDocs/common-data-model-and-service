---
title: Resource - Common Data Model | Microsoft Docs
description: User or facility/equipment that can be scheduled for a service.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Resource

User or facility/equipment that can be scheduled for a service.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/Resource.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/Resource  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[resourceId](#resourceId)|Unique identifier of the resource.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[businessUnitId](#businessUnitId)|Business Unit Id|<a href="Resource.md" target="_blank">service/Resource</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Resource.md" target="_blank">service/Resource</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[name](#name)|Name of the resource.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[calendarId](#calendarId)|Unique identifier of the calendar for the resource.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[displayInServiceViews](#displayInServiceViews)|For internal use only.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[isDisabled](#isDisabled)|Information about whether the resource is enabled.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[objectTypeCode](#objectTypeCode)|Type of entity with which the resource is associated.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[organizationId](#organizationId)|Unique identifier of the organization with which the resource is associated.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[siteId](#siteId)|Unique identifier of the site at which the resource is located.|<a href="Resource.md" target="_blank">service/Resource</a>|
|[entityImageId](#entityImageId)||<a href="Resource.md" target="_blank">service/Resource</a>|

### <a href=#resourceId name="resourceId">resourceId</a>

Unique identifier of the resource.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource</td></tr><tr><td>description</td><td>Unique identifier of the resource.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>resourceid</td></tr></table>

### <a href=#businessUnitId name="businessUnitId">businessUnitId</a>

Business Unit Id  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Unit Id</td></tr><tr><td>description</td><td>Business Unit Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>businessunitid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the resource.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the resource.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#calendarId name="calendarId">calendarId</a>

Unique identifier of the calendar for the resource.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calendar</td></tr><tr><td>description</td><td>Unique identifier of the calendar for the resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>calendarid</td></tr></table>

### <a href=#displayInServiceViews name="displayInServiceViews">displayInServiceViews</a>

For internal use only.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display in Service Views</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>displayinserviceviews</td></tr></table>

### <a href=#isDisabled name="isDisabled">isDisabled</a>

Information about whether the resource is enabled.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Disabled</td></tr><tr><td>description</td><td>Information about whether the resource is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdisabled</td></tr></table>

### <a href=#objectTypeCode name="objectTypeCode">objectTypeCode</a>

Type of entity with which the resource is associated.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Object Type </td></tr><tr><td>description</td><td>Type of entity with which the resource is associated.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>objecttypecode</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization with which the resource is associated.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization with which the resource is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#siteId name="siteId">siteId</a>

Unique identifier of the site at which the resource is located.  
First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Site</td></tr><tr><td>description</td><td>Unique identifier of the site at which the resource is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>siteid</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: service/Resource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>
