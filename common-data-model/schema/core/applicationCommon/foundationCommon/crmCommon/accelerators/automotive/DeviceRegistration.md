---
title: DeviceRegistration - Common Data Model | Microsoft Docs
description: Record of registrations of a specific vehicle or device to specific customers over time.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Device Registration

Record of registrations of a specific vehicle or device to specific customers over time.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/DeviceRegistration.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/DeviceRegistration  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[comments](#comments)|Notes or remarks about the vehicle or device registration.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[deviceId](#deviceId)|Vehicle or device that is registered.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[deviceLicensePlateId](#deviceLicensePlateId)|License plate number for the vehicle or device that is registered.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[deviceRegistrationId](#deviceRegistrationId)|Unique identifier for entity instances|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[name](#name)|Name of the vehicle or device registration.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[role](#role)|Role of the person on the registration (owner, custodian or operator). |<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[role_display](#role_display)||<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[validFrom](#validFrom)|First date at which the registration is valid.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[validTo](#validTo)|Last date at which the registration is valid.|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[stateCode](#stateCode)|Status of the Device Registration|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[stateCode_display](#stateCode_display)||<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[statusCode](#statusCode)|Reason for the status of the Device Registration|<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|
|[statusCode_display](#statusCode_display)||<a href="DeviceRegistration.md" target="_blank">automotive/DeviceRegistration</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#comments name="comments">comments</a>

Notes or remarks about the vehicle or device registration.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comments</td></tr><tr><td>description</td><td>Notes or remarks about the vehicle or device registration.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_comments</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#deviceId name="deviceId">deviceId</a>

Vehicle or device that is registered.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>Vehicle or device that is registered.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceid</td></tr></table>

### <a href=#deviceLicensePlateId name="deviceLicensePlateId">deviceLicensePlateId</a>

License plate number for the vehicle or device that is registered.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device License Plate</td></tr><tr><td>description</td><td>License plate number for the vehicle or device that is registered.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicelicenseplateid</td></tr></table>

### <a href=#deviceRegistrationId name="deviceRegistrationId">deviceRegistrationId</a>

Unique identifier for entity instances  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Registration</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceregistrationid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the vehicle or device registration.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the vehicle or device registration.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#role name="role">role</a>

Role of the person on the registration (owner, custodian or operator).   
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Role of the person on the registration (owner, custodian or operator). </td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_role</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#role_display name="role_display">role_display</a>

First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#validFrom name="validFrom">validFrom</a>

First date at which the registration is valid.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Valid From</td></tr><tr><td>description</td><td>First date at which the registration is valid.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_validfrom</td></tr></table>

### <a href=#validTo name="validTo">validTo</a>

Last date at which the registration is valid.  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Valid To</td></tr><tr><td>description</td><td>Last date at which the registration is valid.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_validto</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Device Registration  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Device Registration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Device Registration  
First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Device Registration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/DeviceRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
