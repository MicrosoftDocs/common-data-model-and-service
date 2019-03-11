---
title: FacilityEquipment - Common Data Model | Microsoft Docs
description: Resource that can be scheduled.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Facility/Equipment

Resource that can be scheduled.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/FacilityEquipment.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/FacilityEquipment  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[equipmentId](#equipmentId)|Unique identifier of the facility/equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the facility/equipment entry.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the facility/equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[businessUnitId](#businessUnitId)|Business Unit Id|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[name](#name)|Name of the facility/equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[calendarId](#calendarId)|Fiscal calendar associated with the facility/equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[description](#description)|Description of the facility/equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[displayInServiceViews](#displayInServiceViews)|For internal use only.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[emailAddress](#emailAddress)|Email address of person to contact about the use of the facility/equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[isDisabled](#isDisabled)|Whether the facility/equipment is disabled or operational.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[organizationId](#organizationId)|Unique identifier of the parent business unit.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[siteId](#siteId)|Site where the facility/equipment is located.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[skills](#skills)|Skills needed to operate the facility/equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[timeZoneCode](#timeZoneCode)|Local time zone where the facility/equipment is located.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the equipment with respect to the base currency.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the equipment.|<a href="FacilityEquipment.md" target="_blank">service/FacilityEquipment</a>|

### <a href=#equipmentId name="equipmentId">equipmentId</a>

Unique identifier of the facility/equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facility/Equipment</td></tr><tr><td>description</td><td>Unique identifier of the facility/equipment.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>equipmentid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the facility/equipment entry.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the facility/equipment entry.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the facility/equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the facility/equipment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the equipment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the equipment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#businessUnitId name="businessUnitId">businessUnitId</a>

Business Unit Id  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Unit Id</td></tr><tr><td>description</td><td>Business Unit Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>businessunitid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the facility/equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the facility/equipment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#calendarId name="calendarId">calendarId</a>

Fiscal calendar associated with the facility/equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calendar</td></tr><tr><td>description</td><td>Fiscal calendar associated with the facility/equipment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>calendarid</td></tr></table>

### <a href=#description name="description">description</a>

Description of the facility/equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the facility/equipment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#displayInServiceViews name="displayInServiceViews">displayInServiceViews</a>

For internal use only.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display in Service Views</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>displayinserviceviews</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

Email address of person to contact about the use of the facility/equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Email</td></tr><tr><td>description</td><td>Email address of person to contact about the use of the facility/equipment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#isDisabled name="isDisabled">isDisabled</a>

Whether the facility/equipment is disabled or operational.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Disabled</td></tr><tr><td>description</td><td>Whether the facility/equipment is disabled or operational.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdisabled</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the parent business unit.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the parent business unit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#siteId name="siteId">siteId</a>

Site where the facility/equipment is located.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Site</td></tr><tr><td>description</td><td>Site where the facility/equipment is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>siteid</td></tr></table>

### <a href=#skills name="skills">skills</a>

Skills needed to operate the facility/equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Skills</td></tr><tr><td>description</td><td>Skills needed to operate the facility/equipment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>skills</td></tr></table>

### <a href=#timeZoneCode name="timeZoneCode">timeZoneCode</a>

Local time zone where the facility/equipment is located.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone</td></tr><tr><td>description</td><td>Local time zone where the facility/equipment is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>sourceName</td><td>timezonecode</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the equipment with respect to the base currency.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the equipment with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the equipment.  
First included in: service/FacilityEquipment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the equipment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
