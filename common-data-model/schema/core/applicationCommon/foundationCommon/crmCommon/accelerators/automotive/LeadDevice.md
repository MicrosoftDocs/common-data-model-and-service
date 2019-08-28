---
title: LeadDevice - Common Data Model | Microsoft Docs
description: Vehicle or device that is the subject of a lead, which may involve one or more vehicles or devices.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Lead Device

Vehicle or device that is the subject of a lead, which may involve one or more vehicles or devices.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/LeadDevice.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/LeadDevice  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[ownerId](#ownerId)|Owner Id|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[entityImage](#entityImage)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[comments](#comments)|Notes/remarks regarding this vehicle or device.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceBrandId](#deviceBrandId)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceClassId](#deviceClassId)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceGenerationId](#deviceGenerationId)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceId](#deviceId)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceModelCodeId](#deviceModelCodeId)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceModelId](#deviceModelId)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceStyleId](#deviceStyleId)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceTypeId](#deviceTypeId)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceVariantId](#deviceVariantId)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[deviceYear](#deviceYear)|The year of manufacture of the vehicle or device.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[leadDeviceId](#leadDeviceId)|Unique identifier for entity instances|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[leadId](#leadId)|The parent lead that this vehicle or device is associated with.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[name](#name)|Name of the vehicle or device in this lead.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[price](#price)|The sales price attributed to this vehicle or device.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[priceBase](#priceBase)|Value of the price in base currency.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[priceComments](#priceComments)|Notes/remarks regarding the sales price for this vehicle or device.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[priceTypeId](#priceTypeId)|The type of pricing associated with the sales price of this vehicle or device.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[state](#state)|Type of the device in this vehicle or device (new or used).|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[state_display](#state_display)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[URL](#URL)|URL for the source lead.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[stateCode](#stateCode)|Status of the Lead Device|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[stateCode_display](#stateCode_display)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[statusCode](#statusCode)|Reason for the status of the Lead Device|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[statusCode_display](#statusCode_display)||<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="LeadDevice.md" target="_blank">automotive/LeadDevice</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#entityImage name="entityImage">entityImage</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Image</td></tr><tr><td>dataFormat</td><td>Binary</td></tr><tr><td>maximumLength</td><td>9437328</td></tr><tr><td>sourceName</td><td>entityimage</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#comments name="comments">comments</a>

Notes/remarks regarding this vehicle or device.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comments</td></tr><tr><td>description</td><td>Notes/remarks regarding this vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_comments</td></tr></table>

### <a href=#deviceBrandId name="deviceBrandId">deviceBrandId</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Brand</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicebrandid</td></tr></table>

### <a href=#deviceClassId name="deviceClassId">deviceClassId</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Class</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceclassid</td></tr></table>

### <a href=#deviceGenerationId name="deviceGenerationId">deviceGenerationId</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Generation</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicegenerationid</td></tr></table>

### <a href=#deviceId name="deviceId">deviceId</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceid</td></tr></table>

### <a href=#deviceModelCodeId name="deviceModelCodeId">deviceModelCodeId</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Model Code</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicemodelcodeid</td></tr></table>

### <a href=#deviceModelId name="deviceModelId">deviceModelId</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Model</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicemodelid</td></tr></table>

### <a href=#deviceStyleId name="deviceStyleId">deviceStyleId</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Style</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicestyleid</td></tr></table>

### <a href=#deviceTypeId name="deviceTypeId">deviceTypeId</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Type</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicetypeid</td></tr></table>

### <a href=#deviceVariantId name="deviceVariantId">deviceVariantId</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Variant</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicevariantid</td></tr></table>

### <a href=#deviceYear name="deviceYear">deviceYear</a>

The year of manufacture of the vehicle or device.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Year</td></tr><tr><td>description</td><td>The year of manufacture of the vehicle or device.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msauto_deviceyear</td></tr></table>

### <a href=#leadDeviceId name="leadDeviceId">leadDeviceId</a>

Unique identifier for entity instances  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead Device</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_leaddeviceid</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

The parent lead that this vehicle or device is associated with.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead</td></tr><tr><td>description</td><td>The parent lead that this vehicle or device is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_leadid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the vehicle or device in this lead.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the vehicle or device in this lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#price name="price">price</a>

The sales price attributed to this vehicle or device.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price</td></tr><tr><td>description</td><td>The sales price attributed to this vehicle or device.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the price in base currency.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price (Base)</td></tr><tr><td>description</td><td>Value of the price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_price_base</td></tr></table>

### <a href=#priceComments name="priceComments">priceComments</a>

Notes/remarks regarding the sales price for this vehicle or device.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Comments</td></tr><tr><td>description</td><td>Notes/remarks regarding the sales price for this vehicle or device.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_pricecomments</td></tr></table>

### <a href=#priceTypeId name="priceTypeId">priceTypeId</a>

The type of pricing associated with the sales price of this vehicle or device.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Type</td></tr><tr><td>description</td><td>The type of pricing associated with the sales price of this vehicle or device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_pricetypeid</td></tr></table>

### <a href=#state name="state">state</a>

Type of the device in this vehicle or device (new or used).  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>Type of the device in this vehicle or device (new or used).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_state</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#state_display name="state_display">state_display</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#URL name="URL">URL</a>

URL for the source lead.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>URL</td></tr><tr><td>description</td><td>URL for the source lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>sourceName</td><td>msauto_url</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Lead Device  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Lead Device</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Lead Device  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Lead Device</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: automotive/LeadDevice (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
