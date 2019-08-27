---
title: ActualDataExport - Common Data Model | Microsoft Docs
description: Data export entity for the actual entity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Actual Data Export (Deprecated)

Data export entity for the actual entity.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ActualDataExport.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ActualDataExport  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[dataExportId](#dataExportId)|Shows the entity instances.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[stateCode](#stateCode)|Status of the Actual Data Export|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[stateCode_display](#stateCode_display)||<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[statusCode](#statusCode)|Reason for the status of the Actual Data Export|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[statusCode_display](#statusCode_display)||<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[name](#name)|Type the name of the record.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[dataToken](#dataToken)|The data token that is returned on a successful export. The data token is used to retrieve only the newly added records.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[entityName](#entityName)|Name of the entity exported|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[exportedRecordCount](#exportedRecordCount)|The number of records that have been currently exported|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[exportStatus](#exportStatus)|Status of the export|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[exportStatus_display](#exportStatus_display)||<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[linkedEntityData](#linkedEntityData)|Contains data representing the linked entities|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|
|[pagingData](#pagingData)|Paging data associated to an incomplete export.|<a href="ActualDataExport.md" target="_blank">projectServiceAutomation/ActualDataExport</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#dataExportId name="dataExportId">dataExportId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Data Export</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_dataexportid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Actual Data Export  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Actual Data Export</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Actual Data Export  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Actual Data Export</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the record.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#dataToken name="dataToken">dataToken</a>

The data token that is returned on a successful export. The data token is used to retrieve only the newly added records.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data Token</td></tr><tr><td>description</td><td>The data token that is returned on a successful export. The data token is used to retrieve only the newly added records.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_datatoken</td></tr></table>

### <a href=#entityName name="entityName">entityName</a>

Name of the entity exported  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Name</td></tr><tr><td>description</td><td>Name of the entity exported</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_entityname</td></tr></table>

### <a href=#exportedRecordCount name="exportedRecordCount">exportedRecordCount</a>

The number of records that have been currently exported  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exported Record Count</td></tr><tr><td>description</td><td>The number of records that have been currently exported</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_exportedrecordcount</td></tr></table>

### <a href=#exportStatus name="exportStatus">exportStatus</a>

Status of the export  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Export Status</td></tr><tr><td>description</td><td>Status of the export</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_exportstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Submitted.</td><td>192350000</td></tr><tr><td>en</td><td>Exporting.</td><td>192350001</td></tr><tr><td>en</td><td>Completed. All records extracted.</td><td>192350002</td></tr><tr><td>en</td><td>Exported with more records to extract.</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#exportStatus_display name="exportStatus_display">exportStatus_display</a>

First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#linkedEntityData name="linkedEntityData">linkedEntityData</a>

Contains data representing the linked entities  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Linked Entity Data</td></tr><tr><td>description</td><td>Contains data representing the linked entities</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_linkedentitydata</td></tr></table>

### <a href=#pagingData name="pagingData">pagingData</a>

Paging data associated to an incomplete export.  
First included in: projectServiceAutomation/ActualDataExport (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paging Data</td></tr><tr><td>description</td><td>Paging data associated to an incomplete export.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pagingdata</td></tr></table>
