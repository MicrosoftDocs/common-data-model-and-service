---
title: UnitGroup - Common Data Model | Microsoft Docs
description: Grouping of units.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Unit Group

Grouping of units.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/UnitGroup.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/UnitGroup  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[uoMScheduleId](#uoMScheduleId)|Unique identifier for the unit group.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[createdOn](#createdOn)|Date and time when the unit group was created.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the unit group.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[modifiedOn](#modifiedOn)|Date and time when the unit group was last modified.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the unit group.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the uomschedule.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the uomschedule.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[name](#name)|Name of the unit group.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[baseUoMName](#baseUoMName)|Name of the base unit.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[description](#description)|Description of the unit group.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[stateCode](#stateCode)|Status of the Unit Group.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[stateCode_display](#stateCode_display)||<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[statusCode](#statusCode)|Reason for the status of the Unit Group.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[statusCode_display](#statusCode_display)||<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[createdByExternalParty](#createdByExternalParty)|Shows the external party who created the record.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|
|[modifiedByExternalParty](#modifiedByExternalParty)|Shows the external party who modified the record.|<a href="UnitGroup.md" target="_blank">foundationCommon/UnitGroup</a>|

### <a href=#uoMScheduleId name="uoMScheduleId">uoMScheduleId</a>

Unique identifier for the unit group.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Group</td></tr><tr><td>description</td><td>Unique identifier for the unit group.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>uomscheduleid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the unit group was created.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the unit group was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the unit group.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the unit group.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the unit group was last modified.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the unit group was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the unit group.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the unit group.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the uomschedule.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the uomschedule.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the uomschedule.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the uomschedule.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the unit group.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the unit group.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#baseUoMName name="baseUoMName">baseUoMName</a>

Name of the base unit.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base Unit name</td></tr><tr><td>description</td><td>Name of the base unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseuomname</td></tr></table>

### <a href=#description name="description">description</a>

Description of the unit group.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the unit group.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Unit Group.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Unit Group.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Unit Group.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Unit Group.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#createdByExternalParty name="createdByExternalParty">createdByExternalParty</a>

Shows the external party who created the record.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdbyexternalparty</td></tr></table>

### <a href=#modifiedByExternalParty name="modifiedByExternalParty">modifiedByExternalParty</a>

Shows the external party who modified the record.  
First included in: foundationCommon/UnitGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedbyexternalparty</td></tr></table>
