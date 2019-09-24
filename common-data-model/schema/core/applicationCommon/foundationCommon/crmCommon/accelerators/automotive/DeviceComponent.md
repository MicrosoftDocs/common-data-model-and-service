---
title: DeviceComponent - Common Data Model | Microsoft Docs
description: Physical or logical part of a vehicle or device.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Device Component

Physical or logical part of a vehicle or device.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/DeviceComponent.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/DeviceComponent  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[entityImage](#entityImage)||<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[behavior](#behavior)|Describes if the component is fixed, movable or replaceable.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[behavior_display](#behavior_display)||<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[componentDeviceId](#componentDeviceId)|Reference to a separate sub-device that the component may represent.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[configurationOptionId](#configurationOptionId)|Specific option for the component on the device.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[description](#description)|Description of the device component.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[deviceComponentId](#deviceComponentId)|Unique identifier for entity instances|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[deviceId](#deviceId)|Parent vehicle or device that contains the component.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[deviceMeterId](#deviceMeterId)|Reference to a meter that the component may represent.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[deviceSensorId](#deviceSensorId)|Reference to a sensor that the component may represent.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[itemName](#itemName)|Name of the component.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[name](#name)|The name of the custom entity.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[parentComponentId](#parentComponentId)|Larger component for which the component is a part.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[quantity](#quantity)|Number of component needed.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[serialNumber](#serialNumber)|Unique number for component.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[specificationAccessoryId](#specificationAccessoryId)|Accessory for which the component is a part.|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[type](#type)|Type of component (standard, option, accessory, device, meter, sensor or custom).|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[type_display](#type_display)||<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[stateCode](#stateCode)|Status of the Device Component|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[stateCode_display](#stateCode_display)||<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[statusCode](#statusCode)|Reason for the status of the Device Component|<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|
|[statusCode_display](#statusCode_display)||<a href="DeviceComponent.md" target="_blank">automotive/DeviceComponent</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#entityImage name="entityImage">entityImage</a>

First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Image</td></tr><tr><td>dataFormat</td><td>Binary</td></tr><tr><td>maximumLength</td><td>9437328</td></tr><tr><td>sourceName</td><td>entityimage</td></tr></table>

### <a href=#behavior name="behavior">behavior</a>

Describes if the component is fixed, movable or replaceable.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Behavior</td></tr><tr><td>description</td><td>Describes if the component is fixed, movable or replaceable.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_behavior</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#behavior_display name="behavior_display">behavior_display</a>

First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#componentDeviceId name="componentDeviceId">componentDeviceId</a>

Reference to a separate sub-device that the component may represent.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Component Device</td></tr><tr><td>description</td><td>Reference to a separate sub-device that the component may represent.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_componentdeviceid</td></tr></table>

### <a href=#configurationOptionId name="configurationOptionId">configurationOptionId</a>

Specific option for the component on the device.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Configuration Option</td></tr><tr><td>description</td><td>Specific option for the component on the device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_configurationoptionid</td></tr></table>

### <a href=#description name="description">description</a>

Description of the device component.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the device component.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_description</td></tr></table>

### <a href=#deviceComponentId name="deviceComponentId">deviceComponentId</a>

Unique identifier for entity instances  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Component</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicecomponentid</td></tr></table>

### <a href=#deviceId name="deviceId">deviceId</a>

Parent vehicle or device that contains the component.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>Parent vehicle or device that contains the component.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceid</td></tr></table>

### <a href=#deviceMeterId name="deviceMeterId">deviceMeterId</a>

Reference to a meter that the component may represent.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Meter</td></tr><tr><td>description</td><td>Reference to a meter that the component may represent.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicemeterid</td></tr></table>

### <a href=#deviceSensorId name="deviceSensorId">deviceSensorId</a>

Reference to a sensor that the component may represent.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Sensor</td></tr><tr><td>description</td><td>Reference to a sensor that the component may represent.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicesensorid</td></tr></table>

### <a href=#itemName name="itemName">itemName</a>

Name of the component.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item Name</td></tr><tr><td>description</td><td>Name of the component.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_itemname</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#parentComponentId name="parentComponentId">parentComponentId</a>

Larger component for which the component is a part.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Component</td></tr><tr><td>description</td><td>Larger component for which the component is a part.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_parentcomponentid</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Number of component needed.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Number of component needed.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msauto_quantity</td></tr></table>

### <a href=#serialNumber name="serialNumber">serialNumber</a>

Unique number for component.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Serial Number</td></tr><tr><td>description</td><td>Unique number for component.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_serialnumber</td></tr></table>

### <a href=#specificationAccessoryId name="specificationAccessoryId">specificationAccessoryId</a>

Accessory for which the component is a part.  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Specification Accessory</td></tr><tr><td>description</td><td>Accessory for which the component is a part.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_specificationaccessoryid</td></tr></table>

### <a href=#type name="type">type</a>

Type of component (standard, option, accessory, device, meter, sensor or custom).  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Type of component (standard, option, accessory, device, meter, sensor or custom).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Device Component  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Device Component</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Device Component  
First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Device Component</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/DeviceComponent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
