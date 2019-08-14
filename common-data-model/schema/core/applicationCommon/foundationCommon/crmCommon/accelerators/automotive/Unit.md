---
title: Unit - Common Data Model | Microsoft Docs
description: Unit of measure.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Unit

Unit of measure.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/Unit.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/foundationCommon/Unit](../../../Unit.md "/core/applicationCommon/foundationCommon/Unit.cdm.json/Unit")  
- /foundationCommon/crmCommon/accelerators/automotive/Unit  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[uoMId](#uoMId)|Unique identifier of the unit.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[createdOn](#createdOn)|Date and time when the unit was created.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[modifiedOn](#modifiedOn)|Date and time when the unit was last modified.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the uom.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the uom.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[name](#name)|Type a descriptive title or name for the unit of measure.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[baseUoM](#baseUoM)|Choose the base or primary unit on which the unit is based.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[isScheduleBaseUoM](#isScheduleBaseUoM)|Tells whether the unit is the base unit for the associated unit group.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the unit of measure.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[quantity](#quantity)|Unit quantity for the product.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[uoMScheduleId](#uoMScheduleId)|Choose the ID of the unit group that the unit is associated with.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[createdByExternalParty](#createdByExternalParty)|Shows the external party who created the record.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[modifiedByExternalParty](#modifiedByExternalParty)|Shows the external party who modified the record.|<a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>|
|[unitId](#unitId)|Unique identifier for entity instances|<a href="Unit.md" target="_blank">automotive/Unit</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Unit.md" target="_blank">automotive/Unit</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Unit.md" target="_blank">automotive/Unit</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Unit.md" target="_blank">automotive/Unit</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Unit.md" target="_blank">automotive/Unit</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="Unit.md" target="_blank">automotive/Unit</a>|
|[stateCode](#stateCode)|Status of the Unit|<a href="Unit.md" target="_blank">automotive/Unit</a>|
|[stateCode_display](#stateCode_display)||<a href="Unit.md" target="_blank">automotive/Unit</a>|
|[statusCode](#statusCode)|Reason for the status of the Unit|<a href="Unit.md" target="_blank">automotive/Unit</a>|
|[statusCode_display](#statusCode_display)||<a href="Unit.md" target="_blank">automotive/Unit</a>|

### <a href=#uoMId name="uoMId">uoMId</a>

Unique identifier of the unit.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Unique identifier of the unit.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>uomid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the unit was created.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the unit was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the unit was last modified.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the unit was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the uom.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the uom.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the uom.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the uom.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Type a descriptive title or name for the unit of measure.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a descriptive title or name for the unit of measure.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#baseUoM name="baseUoM">baseUoM</a>

Choose the base or primary unit on which the unit is based.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base Unit</td></tr><tr><td>description</td><td>Choose the base or primary unit on which the unit is based.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseuom</td></tr></table>

### <a href=#isScheduleBaseUoM name="isScheduleBaseUoM">isScheduleBaseUoM</a>

Tells whether the unit is the base unit for the associated unit group.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Schedule Base Unit</td></tr><tr><td>description</td><td>Tells whether the unit is the base unit for the associated unit group.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isschedulebaseuom</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the unit of measure.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization </td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the unit of measure.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Unit quantity for the product.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Unit quantity for the product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>10000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantity</td></tr></table>

### <a href=#uoMScheduleId name="uoMScheduleId">uoMScheduleId</a>

Choose the ID of the unit group that the unit is associated with.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Schedule</td></tr><tr><td>description</td><td>Choose the ID of the unit group that the unit is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>uomscheduleid</td></tr></table>

### <a href=#createdByExternalParty name="createdByExternalParty">createdByExternalParty</a>

Shows the external party who created the record.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdbyexternalparty</td></tr></table>

### <a href=#modifiedByExternalParty name="modifiedByExternalParty">modifiedByExternalParty</a>

Shows the external party who modified the record.  
First included in: <a href="../../../Unit.md" target="_blank">foundationCommon/Unit</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedbyexternalparty</td></tr></table>

### <a href=#unitId name="unitId">unitId</a>

Unique identifier for entity instances  
First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_unitid</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Unit  
First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Unit</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Unit  
First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Unit</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/Unit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
