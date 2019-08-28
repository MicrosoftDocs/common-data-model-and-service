---
title: Device - Common Data Model | Microsoft Docs
description: This describes the Device entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Device

Physical piece of equipment of considerable value such as a vehicle or a device such as an excavator, that can be tracked through its entire life cycle of trade, ownership and service and may be related to one or more customers over time.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/Device.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/Device  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Device.md" target="_blank">automotive/Device</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Device.md" target="_blank">automotive/Device</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Device.md" target="_blank">automotive/Device</a>|
|[entityImage](#entityImage)||<a href="Device.md" target="_blank">automotive/Device</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[businessOperationId](#businessOperationId)|Department/team at business operation responsible for vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[chassisNumber](#chassisNumber)|Unique number for the vehicle's engine; last 6 digits of the VIN.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[condition](#condition)|Current condition of the vehicle or device (excellent, good, fair, poor or unknown).|<a href="Device.md" target="_blank">automotive/Device</a>|
|[condition_display](#condition_display)||<a href="Device.md" target="_blank">automotive/Device</a>|
|[description](#description)|Description of the vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceBrandId](#deviceBrandId)|Brand of the vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceClassId](#deviceClassId)|Class of the vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceGenerationId](#deviceGenerationId)|Generation of the vehicle or device's model.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceId](#deviceId)|Unique identifier for entity instances|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceModelCodeId](#deviceModelCodeId)|Configuration of the vehicle or device model.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceModelId](#deviceModelId)|Model of the vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceNumber](#deviceNumber)|Unique number of the vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceStateId](#deviceStateId)|Status of the vehicle or device, which may represent a given combination of inventory, ownership and trade status.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceStyleId](#deviceStyleId)|Body style of the vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceTypeId](#deviceTypeId)|Type of this vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[deviceVariantId](#deviceVariantId)|Specific configuration for this vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[listPrice](#listPrice)|Sale price of vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[listPriceBase](#listPriceBase)|Value of the List Price in base currency.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[listPriceComments](#listPriceComments)|Comments regarding the listed price for this vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[name](#name)|Name of the vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[registrationNumber](#registrationNumber)|Registration number for this vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[specificationId](#specificationId)|Specification tied to this vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[URL](#URL)|Webpage for vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[vendorsStockNumber](#vendorsStockNumber)|Stock number for vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[VIN](#VIN)|Unique code used to identify an vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[year](#year)|Manufacture year of the vehicle or device.|<a href="Device.md" target="_blank">automotive/Device</a>|
|[stateCode](#stateCode)|Status of the Device|<a href="Device.md" target="_blank">automotive/Device</a>|
|[stateCode_display](#stateCode_display)||<a href="Device.md" target="_blank">automotive/Device</a>|
|[statusCode](#statusCode)|Reason for the status of the Device|<a href="Device.md" target="_blank">automotive/Device</a>|
|[statusCode_display](#statusCode_display)||<a href="Device.md" target="_blank">automotive/Device</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Device.md" target="_blank">automotive/Device</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#entityImage name="entityImage">entityImage</a>

First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Image</td></tr><tr><td>dataFormat</td><td>Binary</td></tr><tr><td>maximumLength</td><td>9437328</td></tr><tr><td>sourceName</td><td>entityimage</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#businessOperationId name="businessOperationId">businessOperationId</a>

Department/team at business operation responsible for vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Operation</td></tr><tr><td>description</td><td>Department/team at business operation responsible for vehicle or device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_businessoperationid</td></tr></table>

### <a href=#chassisNumber name="chassisNumber">chassisNumber</a>

Unique number for the vehicle's engine; last 6 digits of the VIN.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Chassis Number</td></tr><tr><td>description</td><td>Unique number for the vehicle's engine; last 6 digits of the VIN.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_chassisnumber</td></tr></table>

### <a href=#condition name="condition">condition</a>

Current condition of the vehicle or device (excellent, good, fair, poor or unknown).  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Condition</td></tr><tr><td>description</td><td>Current condition of the vehicle or device (excellent, good, fair, poor or unknown).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_condition</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#condition_display name="condition_display">condition_display</a>

First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Description of the vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_description</td></tr></table>

### <a href=#deviceBrandId name="deviceBrandId">deviceBrandId</a>

Brand of the vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Brand</td></tr><tr><td>description</td><td>Brand of the vehicle or device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicebrandid</td></tr></table>

### <a href=#deviceClassId name="deviceClassId">deviceClassId</a>

Class of the vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Class</td></tr><tr><td>description</td><td>Class of the vehicle or device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceclassid</td></tr></table>

### <a href=#deviceGenerationId name="deviceGenerationId">deviceGenerationId</a>

Generation of the vehicle or device's model.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Generation</td></tr><tr><td>description</td><td>Generation of the vehicle or device's model.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicegenerationid</td></tr></table>

### <a href=#deviceId name="deviceId">deviceId</a>

Unique identifier for entity instances  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceid</td></tr></table>

### <a href=#deviceModelCodeId name="deviceModelCodeId">deviceModelCodeId</a>

Configuration of the vehicle or device model.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Model Code</td></tr><tr><td>description</td><td>Configuration of the vehicle or device model.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicemodelcodeid</td></tr></table>

### <a href=#deviceModelId name="deviceModelId">deviceModelId</a>

Model of the vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Model</td></tr><tr><td>description</td><td>Model of the vehicle or device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicemodelid</td></tr></table>

### <a href=#deviceNumber name="deviceNumber">deviceNumber</a>

Unique number of the vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Number</td></tr><tr><td>description</td><td>Unique number of the vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_devicenumber</td></tr></table>

### <a href=#deviceStateId name="deviceStateId">deviceStateId</a>

Status of the vehicle or device, which may represent a given combination of inventory, ownership and trade status.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device State</td></tr><tr><td>description</td><td>Status of the vehicle or device, which may represent a given combination of inventory, ownership and trade status.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicestateid</td></tr></table>

### <a href=#deviceStyleId name="deviceStyleId">deviceStyleId</a>

Body style of the vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Style</td></tr><tr><td>description</td><td>Body style of the vehicle or device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicestyleid</td></tr></table>

### <a href=#deviceTypeId name="deviceTypeId">deviceTypeId</a>

Type of this vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Type</td></tr><tr><td>description</td><td>Type of this vehicle or device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicetypeid</td></tr></table>

### <a href=#deviceVariantId name="deviceVariantId">deviceVariantId</a>

Specific configuration for this vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Variant</td></tr><tr><td>description</td><td>Specific configuration for this vehicle or device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicevariantid</td></tr></table>

### <a href=#listPrice name="listPrice">listPrice</a>

Sale price of vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>List Price</td></tr><tr><td>description</td><td>Sale price of vehicle or device.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_listprice</td></tr></table>

### <a href=#listPriceBase name="listPriceBase">listPriceBase</a>

Value of the List Price in base currency.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>List Price (Base)</td></tr><tr><td>description</td><td>Value of the List Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_listprice_base</td></tr></table>

### <a href=#listPriceComments name="listPriceComments">listPriceComments</a>

Comments regarding the listed price for this vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>List Price Comments</td></tr><tr><td>description</td><td>Comments regarding the listed price for this vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_listpricecomments</td></tr></table>

### <a href=#name name="name">name</a>

Name of the vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#registrationNumber name="registrationNumber">registrationNumber</a>

Registration number for this vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Number</td></tr><tr><td>description</td><td>Registration number for this vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_registrationnumber</td></tr></table>

### <a href=#specificationId name="specificationId">specificationId</a>

Specification tied to this vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Specification</td></tr><tr><td>description</td><td>Specification tied to this vehicle or device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_specificationid</td></tr></table>

### <a href=#URL name="URL">URL</a>

Webpage for vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>URL</td></tr><tr><td>description</td><td>Webpage for vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_url</td></tr></table>

### <a href=#vendorsStockNumber name="vendorsStockNumber">vendorsStockNumber</a>

Stock number for vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendors Stock Number</td></tr><tr><td>description</td><td>Stock number for vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_vendorsstocknumber</td></tr></table>

### <a href=#VIN name="VIN">VIN</a>

Unique code used to identify an vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>VIN</td></tr><tr><td>description</td><td>Unique code used to identify an vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_vin</td></tr></table>

### <a href=#year name="year">year</a>

Manufacture year of the vehicle or device.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Year</td></tr><tr><td>description</td><td>Manufacture year of the vehicle or device.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msauto_year</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Device  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Device</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Device  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Device</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: automotive/Device (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
