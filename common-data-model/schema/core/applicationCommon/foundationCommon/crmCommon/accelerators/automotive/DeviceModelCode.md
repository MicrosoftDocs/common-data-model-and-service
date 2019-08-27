---
title: DeviceModelCode - Common Data Model | Microsoft Docs
description: This describes the DeviceModelCode entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Device Model Code

Specific configuration of a device, such as a vehicle of specific generation, body style, engine option and transmission.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/DeviceModelCode.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/DeviceModelCode  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[entityImage](#entityImage)||<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[code](#code)|Unique code for this device model.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[description](#description)|Description of the model code.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[deviceBrandId](#deviceBrandId)|Brand of the model code.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[deviceClassId](#deviceClassId)|Class of the model code.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[deviceGenerationId](#deviceGenerationId)|Generation of the model code.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[deviceModelCodeId](#deviceModelCodeId)|Unique identifier for entity instances|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[deviceModelId](#deviceModelId)|Model of the model code.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[deviceStyleId](#deviceStyleId)|Body style of the model code.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[deviceTypeId](#deviceTypeId)|Type of device for this model.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[name](#name)|Name of the model code.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[specificationId](#specificationId)|Specification of this model code.|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[stateCode](#stateCode)|Status of the Device Model Code|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[stateCode_display](#stateCode_display)||<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[statusCode](#statusCode)|Reason for the status of the Device Model Code|<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|
|[statusCode_display](#statusCode_display)||<a href="DeviceModelCode.md" target="_blank">automotive/DeviceModelCode</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#entityImage name="entityImage">entityImage</a>

First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Image</td></tr><tr><td>dataFormat</td><td>Binary</td></tr><tr><td>maximumLength</td><td>9437328</td></tr><tr><td>sourceName</td><td>entityimage</td></tr></table>

### <a href=#code name="code">code</a>

Unique code for this device model.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>Unique code for this device model.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_code</td></tr></table>

### <a href=#description name="description">description</a>

Description of the model code.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the model code.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_description</td></tr></table>

### <a href=#deviceBrandId name="deviceBrandId">deviceBrandId</a>

Brand of the model code.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Brand</td></tr><tr><td>description</td><td>Brand of the model code.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicebrandid</td></tr></table>

### <a href=#deviceClassId name="deviceClassId">deviceClassId</a>

Class of the model code.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Class</td></tr><tr><td>description</td><td>Class of the model code.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceclassid</td></tr></table>

### <a href=#deviceGenerationId name="deviceGenerationId">deviceGenerationId</a>

Generation of the model code.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Generation</td></tr><tr><td>description</td><td>Generation of the model code.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicegenerationid</td></tr></table>

### <a href=#deviceModelCodeId name="deviceModelCodeId">deviceModelCodeId</a>

Unique identifier for entity instances  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Model Code</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicemodelcodeid</td></tr></table>

### <a href=#deviceModelId name="deviceModelId">deviceModelId</a>

Model of the model code.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Model</td></tr><tr><td>description</td><td>Model of the model code.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicemodelid</td></tr></table>

### <a href=#deviceStyleId name="deviceStyleId">deviceStyleId</a>

Body style of the model code.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Style</td></tr><tr><td>description</td><td>Body style of the model code.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicestyleid</td></tr></table>

### <a href=#deviceTypeId name="deviceTypeId">deviceTypeId</a>

Type of device for this model.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Type</td></tr><tr><td>description</td><td>Type of device for this model.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicetypeid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the model code.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the model code.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#specificationId name="specificationId">specificationId</a>

Specification of this model code.  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Specification</td></tr><tr><td>description</td><td>Specification of this model code.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_specificationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Device Model Code  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Device Model Code</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Device Model Code  
First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Device Model Code</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/DeviceModelCode (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
