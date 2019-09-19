---
title: Service - Common Data Model | Microsoft Docs
description: Activity that represents work done to satisfy a customer's need.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Service

Activity that represents work done to satisfy a customer's need.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/Service.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/Service  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[serviceId](#serviceId)|Unique identifier of the associated service.|<a href="Service.md" target="_blank">service/Service</a>|
|[createdOn](#createdOn)|Date and time when the service was created.|<a href="Service.md" target="_blank">service/Service</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the service.|<a href="Service.md" target="_blank">service/Service</a>|
|[modifiedOn](#modifiedOn)|Date and time when the service was last modified.|<a href="Service.md" target="_blank">service/Service</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the service.|<a href="Service.md" target="_blank">service/Service</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the service.|<a href="Service.md" target="_blank">service/Service</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the service.|<a href="Service.md" target="_blank">service/Service</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="Service.md" target="_blank">service/Service</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Service.md" target="_blank">service/Service</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="Service.md" target="_blank">service/Service</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Service.md" target="_blank">service/Service</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Service.md" target="_blank">service/Service</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Service.md" target="_blank">service/Service</a>|
|[name](#name)|Name of the service.|<a href="Service.md" target="_blank">service/Service</a>|
|[anchorOffset](#anchorOffset)|Used in conjunction with granularity to describes when services can be performed in relation to midnight on a given day.|<a href="Service.md" target="_blank">service/Service</a>|
|[calendarId](#calendarId)|Unique identifier of the calendar.|<a href="Service.md" target="_blank">service/Service</a>|
|[description](#description)|Description of activity that represents work done to satisfy a customer's need.|<a href="Service.md" target="_blank">service/Service</a>|
|[duration](#duration)|Duration of the service.|<a href="Service.md" target="_blank">service/Service</a>|
|[granularity](#granularity)|Describes how often the service is performed.|<a href="Service.md" target="_blank">service/Service</a>|
|[initialStatusCode](#initialStatusCode)|Initial status reason for the service activity.|<a href="Service.md" target="_blank">service/Service</a>|
|[initialStatusCode_display](#initialStatusCode_display)||<a href="Service.md" target="_blank">service/Service</a>|
|[isSchedulable](#isSchedulable)|Information about whether the service can be scheduled.|<a href="Service.md" target="_blank">service/Service</a>|
|[isVisible](#isVisible)|Information about whether the service is visible to users.|<a href="Service.md" target="_blank">service/Service</a>|
|[resourceSpecId](#resourceSpecId)|Unique identifier of the resource specification with which the service is associated.|<a href="Service.md" target="_blank">service/Service</a>|
|[showResources](#showResources)|For internal use only.|<a href="Service.md" target="_blank">service/Service</a>|
|[strategyId](#strategyId)|Value that is taken from PluginTypeId in the Plugin Type record for the scheduling strategy. This is the ID of the scheduling strategy plug-in associated with the service.|<a href="Service.md" target="_blank">service/Service</a>|

### <a href=#serviceId name="serviceId">serviceId</a>

Unique identifier of the associated service.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service</td></tr><tr><td>description</td><td>Unique identifier of the associated service.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>serviceid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the service was created.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the service was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the service.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the service was last modified.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the service was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the service.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the service.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the service.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the service.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the service.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#anchorOffset name="anchorOffset">anchorOffset</a>

Used in conjunction with granularity to describes when services can be performed in relation to midnight on a given day.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anchor Offset</td></tr><tr><td>description</td><td>Used in conjunction with granularity to describes when services can be performed in relation to midnight on a given day.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1440</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>anchoroffset</td></tr></table>

### <a href=#calendarId name="calendarId">calendarId</a>

Unique identifier of the calendar.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calendar</td></tr><tr><td>description</td><td>Unique identifier of the calendar.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>calendarid</td></tr></table>

### <a href=#description name="description">description</a>

Description of activity that represents work done to satisfy a customer's need.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of activity that represents work done to satisfy a customer's need.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#duration name="duration">duration</a>

Duration of the service.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Duration of the service.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>duration</td></tr></table>

### <a href=#granularity name="granularity">granularity</a>

Describes how often the service is performed.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Granularity</td></tr><tr><td>description</td><td>Describes how often the service is performed.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>granularity</td></tr></table>

### <a href=#initialStatusCode name="initialStatusCode">initialStatusCode</a>

Initial status reason for the service activity.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initial Status Reason</td></tr><tr><td>description</td><td>Initial status reason for the service activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>initialstatuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Requested</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Tentative</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Pending</td><td>3</td><td>0</td></tr><tr><td>en</td><td>Reserved</td><td>4</td><td>0</td></tr><tr><td>en</td><td>In Progress</td><td>6</td><td>0</td></tr><tr><td>en</td><td>Arrived</td><td>7</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>8</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>9</td><td>2</td></tr><tr><td>en</td><td>No Show</td><td>10</td><td>2</td></tr></table></td></tr></table>

### <a href=#initialStatusCode_display name="initialStatusCode_display">initialStatusCode_display</a>

First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isSchedulable name="isSchedulable">isSchedulable</a>

Information about whether the service can be scheduled.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Information about whether the service can be scheduled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isschedulable</td></tr></table>

### <a href=#isVisible name="isVisible">isVisible</a>

Information about whether the service is visible to users.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Visible</td></tr><tr><td>description</td><td>Information about whether the service is visible to users.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isvisible</td></tr></table>

### <a href=#resourceSpecId name="resourceSpecId">resourceSpecId</a>

Unique identifier of the resource specification with which the service is associated.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required Resources</td></tr><tr><td>description</td><td>Unique identifier of the resource specification with which the service is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>resourcespecid</td></tr></table>

### <a href=#showResources name="showResources">showResources</a>

For internal use only.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Show Resources</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>showresources</td></tr></table>

### <a href=#strategyId name="strategyId">strategyId</a>

Value that is taken from PluginTypeId in the Plugin Type record for the scheduling strategy. This is the ID of the scheduling strategy plug-in associated with the service.  
First included in: service/Service (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Strategy</td></tr><tr><td>description</td><td>Value that is taken from PluginTypeId in the Plugin Type record for the scheduling strategy. This is the ID of the scheduling strategy plug-in associated with the service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>strategyid</td></tr></table>
