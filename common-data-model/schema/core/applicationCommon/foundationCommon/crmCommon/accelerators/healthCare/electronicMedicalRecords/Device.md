---
title: Device - Common Data Model | Microsoft Docs
description: This describes the Device entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Device

An instance or a type of a manufactured item that's used in the provision of healthcare without being substantially changed through that activity.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Device.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Device  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[deviceId](#deviceId)|Unique identifier for entity instances|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[stateCode](#stateCode)|Status of the Device|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[stateCode_display](#stateCode_display)||<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[statusCode](#statusCode)|Reason for the status of the Device|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[statusCode_display](#statusCode_display)||<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[name](#name)|The name of the custom entity.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[carrierAIDC](#carrierAIDC)|The full UDI carrier of the Automatic Identification and Data Capture (AIDC) technology representation of the bar code string as printed on the packaging of the device - E.g a bar code or RFID.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[deviceNumber](#deviceNumber)|Unique instance identifiers assigned to a device by manufacturers other organizations or owners.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[deviceStatus](#deviceStatus)|Status of the Device availability.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[deviceStatus_display](#deviceStatus_display)||<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[expirationDate](#expirationDate)|The date and time beyond which this device is no longer valid or should not be used (if applicable).|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[location](#location)|The place where the device can be found.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[lotNumber](#lotNumber)|Lot number assigned by the manufacturer.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[manufacturer](#manufacturer)|A name of the manufacturer.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[manufacturerDate](#manufacturerDate)|The date and time when the device was manufactured.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[model](#model)|The "model" is an identifier assigned by the manufacturer to identify the product by its type. This number is shared by the all devices sold as the same type.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[owner](#owner)|An organization that is responsible for the provision and ongoing maintenance of the device.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[patient](#patient)|Demographics and other administrative information about an individual or animal receiving care or other health-related services.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[type](#type)|Code or identifier to identify a kind of device.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[UDI](#UDI)|Unique device identifier (UDI) assigned to device label or package.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[UDICarrierHRF](#UDICarrierHRF)|Unique device identifier (UDI) assigned to device label or package.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[UDIEntryType](#UDIEntryType)|A coded entry to indicate how the data was entered.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[UDIEntryType_display](#UDIEntryType_display)||<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[UDIIssuer](#UDIIssuer)|Organization that is charged with issuing UDIs for devices|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[udiJurisdiction](#udiJurisdiction)|The identity of the authoritative source for UDI generation within a jurisdiction. All UDIs are globally unique within a single namespace with the appropriate repository uri as the system.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[URL](#URL)|A network address on which the device may be contacted directly.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|
|[version](#version)|The version of the device, if the device has multiple releases under the same model, or if the device is software or carries firmware.|<a href="Device.md" target="_blank">electronicMedicalRecords/Device</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#deviceId name="deviceId">deviceId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_deviceid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Device  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Device</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Device  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Device</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#carrierAIDC name="carrierAIDC">carrierAIDC</a>

The full UDI carrier of the Automatic Identification and Data Capture (AIDC) technology representation of the bar code string as printed on the packaging of the device - E.g a bar code or RFID.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UDI Carrier AIDC</td></tr><tr><td>description</td><td>The full UDI carrier of the Automatic Identification and Data Capture (AIDC) technology representation of the bar code string as printed on the packaging of the device - E.g a bar code or RFID.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_carrieraidc</td></tr></table>

### <a href=#deviceNumber name="deviceNumber">deviceNumber</a>

Unique instance identifiers assigned to a device by manufacturers other organizations or owners.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Number</td></tr><tr><td>description</td><td>Unique instance identifiers assigned to a device by manufacturers other organizations or owners.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_devicenumber</td></tr></table>

### <a href=#deviceStatus name="deviceStatus">deviceStatus</a>

Status of the Device availability.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Status</td></tr><tr><td>description</td><td>Status of the Device availability.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_devicestatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>935000000</td></tr><tr><td>en</td><td>InActive</td><td>935000001</td></tr><tr><td>en</td><td>Entered-In-Error</td><td>935000002</td></tr><tr><td>en</td><td>Unknown</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#deviceStatus_display name="deviceStatus_display">deviceStatus_display</a>

First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#expirationDate name="expirationDate">expirationDate</a>

The date and time beyond which this device is no longer valid or should not be used (if applicable).  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiration Date</td></tr><tr><td>description</td><td>The date and time beyond which this device is no longer valid or should not be used (if applicable).</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_expirationdate</td></tr></table>

### <a href=#location name="location">location</a>

The place where the device can be found.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>description</td><td>The place where the device can be found.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_location</td></tr></table>

### <a href=#lotNumber name="lotNumber">lotNumber</a>

Lot number assigned by the manufacturer.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lot Number</td></tr><tr><td>description</td><td>Lot number assigned by the manufacturer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_lotnumber</td></tr></table>

### <a href=#manufacturer name="manufacturer">manufacturer</a>

A name of the manufacturer.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manufacturer</td></tr><tr><td>description</td><td>A name of the manufacturer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_manufacturer</td></tr></table>

### <a href=#manufacturerDate name="manufacturerDate">manufacturerDate</a>

The date and time when the device was manufactured.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manufacturer Date</td></tr><tr><td>description</td><td>The date and time when the device was manufactured.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_manufacturerdate</td></tr></table>

### <a href=#model name="model">model</a>

The "model" is an identifier assigned by the manufacturer to identify the product by its type. This number is shared by the all devices sold as the same type.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Model</td></tr><tr><td>description</td><td>The "model" is an identifier assigned by the manufacturer to identify the product by its type. This number is shared by the all devices sold as the same type.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_model</td></tr></table>

### <a href=#owner name="owner">owner</a>

An organization that is responsible for the provision and ongoing maintenance of the device.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>An organization that is responsible for the provision and ongoing maintenance of the device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_owner</td></tr></table>

### <a href=#patient name="patient">patient</a>

Demographics and other administrative information about an individual or animal receiving care or other health-related services.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>Demographics and other administrative information about an individual or animal receiving care or other health-related services.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_patient</td></tr></table>

### <a href=#type name="type">type</a>

Code or identifier to identify a kind of device.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Code or identifier to identify a kind of device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_type</td></tr></table>

### <a href=#UDI name="UDI">UDI</a>

Unique device identifier (UDI) assigned to device label or package.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UDI</td></tr><tr><td>description</td><td>Unique device identifier (UDI) assigned to device label or package.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_udi</td></tr></table>

### <a href=#UDICarrierHRF name="UDICarrierHRF">UDICarrierHRF</a>

Unique device identifier (UDI) assigned to device label or package.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UDI Carrier HRF</td></tr><tr><td>description</td><td>Unique device identifier (UDI) assigned to device label or package.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_udicarrierhrf</td></tr></table>

### <a href=#UDIEntryType name="UDIEntryType">UDIEntryType</a>

A coded entry to indicate how the data was entered.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UDI Entry Type</td></tr><tr><td>description</td><td>A coded entry to indicate how the data was entered.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_udientrytype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Barcode</td><td>935000000</td></tr><tr><td>en</td><td>RFID</td><td>935000001</td></tr><tr><td>en</td><td>Manual</td><td>935000002</td></tr><tr><td>en</td><td>Card</td><td>935000003</td></tr><tr><td>en</td><td>Self Reported</td><td>935000004</td></tr><tr><td>en</td><td>Known</td><td>935000005</td></tr></table></td></tr></table>

### <a href=#UDIEntryType_display name="UDIEntryType_display">UDIEntryType_display</a>

First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#UDIIssuer name="UDIIssuer">UDIIssuer</a>

Organization that is charged with issuing UDIs for devices  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UDI Issuer</td></tr><tr><td>description</td><td>Organization that is charged with issuing UDIs for devices</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_udiissuer</td></tr></table>

### <a href=#udiJurisdiction name="udiJurisdiction">udiJurisdiction</a>

The identity of the authoritative source for UDI generation within a jurisdiction. All UDIs are globally unique within a single namespace with the appropriate repository uri as the system.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Jurisdiction</td></tr><tr><td>description</td><td>The identity of the authoritative source for UDI generation within a jurisdiction. All UDIs are globally unique within a single namespace with the appropriate repository uri as the system.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_udijurisdiction</td></tr></table>

### <a href=#URL name="URL">URL</a>

A network address on which the device may be contacted directly.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>URL</td></tr><tr><td>description</td><td>A network address on which the device may be contacted directly.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_url</td></tr></table>

### <a href=#version name="version">version</a>

The version of the device, if the device has multiple releases under the same model, or if the device is software or carries firmware.  
First included in: electronicMedicalRecords/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version</td></tr><tr><td>description</td><td>The version of the device, if the device has multiple releases under the same model, or if the device is software or carries firmware.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_version</td></tr></table>
