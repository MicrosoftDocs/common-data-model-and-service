---
title: DeviceLicensePlate - Common Data Model | Microsoft Docs
description: Record of license plates assigned to a given vehicle or device over time.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Device License Plate

Record of license plates assigned to a given vehicle or device over time.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/DeviceLicensePlate.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/DeviceLicensePlate  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[comments](#comments)|Notes or remarks about the license plate.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[deviceId](#deviceId)|Vehicle for which the license plate is registered.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[deviceLicensePlateId](#deviceLicensePlateId)|Unique identifier for entity instances|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[issuedBy](#issuedBy)|Issuer of the license plate.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[registrationNumber](#registrationNumber)|Name of the vehicle license plate.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[validFrom](#validFrom)|First day for which the license plate is valid.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[validTo](#validTo)|Last day for which the license plate is valid.|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[stateCode](#stateCode)|Status of the Device License Plate|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[stateCode_display](#stateCode_display)||<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[statusCode](#statusCode)|Reason for the status of the Device License Plate|<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|
|[statusCode_display](#statusCode_display)||<a href="DeviceLicensePlate.md" target="_blank">automotive/DeviceLicensePlate</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#comments name="comments">comments</a>

Notes or remarks about the license plate.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comments</td></tr><tr><td>description</td><td>Notes or remarks about the license plate.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_comments</td></tr></table>

### <a href=#deviceId name="deviceId">deviceId</a>

Vehicle for which the license plate is registered.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>Vehicle for which the license plate is registered.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceid</td></tr></table>

### <a href=#deviceLicensePlateId name="deviceLicensePlateId">deviceLicensePlateId</a>

Unique identifier for entity instances  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device License Plate</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicelicenseplateid</td></tr></table>

### <a href=#issuedBy name="issuedBy">issuedBy</a>

Issuer of the license plate.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Issued By</td></tr><tr><td>description</td><td>Issuer of the license plate.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_issuedby</td></tr></table>

### <a href=#registrationNumber name="registrationNumber">registrationNumber</a>

Name of the vehicle license plate.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Number</td></tr><tr><td>description</td><td>Name of the vehicle license plate.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_registrationnumber</td></tr></table>

### <a href=#validFrom name="validFrom">validFrom</a>

First day for which the license plate is valid.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Valid From</td></tr><tr><td>description</td><td>First day for which the license plate is valid.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_validfrom</td></tr></table>

### <a href=#validTo name="validTo">validTo</a>

Last day for which the license plate is valid.  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Valid To</td></tr><tr><td>description</td><td>Last day for which the license plate is valid.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_validto</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Device License Plate  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Device License Plate</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Device License Plate  
First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Device License Plate</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/DeviceLicensePlate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
