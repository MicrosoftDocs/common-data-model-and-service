---
title: SchedulingGroup - Common Data Model | Microsoft Docs
description: Resource group or team whose members can be scheduled for a service.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Scheduling Group

Resource group or team whose members can be scheduled for a service.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/SchedulingGroup.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/SchedulingGroup  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[resourceGroupId](#resourceGroupId)|Unique identifier of the scheduling group.|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[businessUnitId](#businessUnitId)|Business Unit Id|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[name](#name)|Name of the scheduling group.|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[groupTypeCode](#groupTypeCode)|Scheduling group type code.|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[groupTypeCode_display](#groupTypeCode_display)||<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[objectTypeCode](#objectTypeCode)|Type of entity with which the scheduling group is associated.|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the scheduling group.|<a href="SchedulingGroup.md" target="_blank">service/SchedulingGroup</a>|

### <a href=#resourceGroupId name="resourceGroupId">resourceGroupId</a>

Unique identifier of the scheduling group.  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduling Group</td></tr><tr><td>description</td><td>Unique identifier of the scheduling group.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>resourcegroupid</td></tr></table>

### <a href=#businessUnitId name="businessUnitId">businessUnitId</a>

Business Unit Id  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Unit Id</td></tr><tr><td>description</td><td>Business Unit Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>businessunitid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the scheduling group.  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the scheduling group.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#groupTypeCode name="groupTypeCode">groupTypeCode</a>

Scheduling group type code.  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group Type Code</td></tr><tr><td>description</td><td>Scheduling group type code.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>grouptypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Static</td><td>0</td></tr><tr><td>en</td><td>Dynamic</td><td>1</td></tr><tr><td>en</td><td>Hidden</td><td>2</td></tr></table></td></tr></table>

### <a href=#groupTypeCode_display name="groupTypeCode_display">groupTypeCode_display</a>

First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#objectTypeCode name="objectTypeCode">objectTypeCode</a>

Type of entity with which the scheduling group is associated.  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity</td></tr><tr><td>description</td><td>Type of entity with which the scheduling group is associated.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>objecttypecode</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the scheduling group.  
First included in: service/SchedulingGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the scheduling group.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>
