---
title: EntitlementContact - Common Data Model | Microsoft Docs
description: This describes the EntitlementContact entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Entitlement Contact

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/EntitlementContact.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/EntitlementContact  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[entitlementContactId](#entitlementContactId)|Unique identifier of the contacts for the entitlements.|<a href="EntitlementContact.md" target="_blank">service/EntitlementContact</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="EntitlementContact.md" target="_blank">service/EntitlementContact</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="EntitlementContact.md" target="_blank">service/EntitlementContact</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="EntitlementContact.md" target="_blank">service/EntitlementContact</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="EntitlementContact.md" target="_blank">service/EntitlementContact</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="EntitlementContact.md" target="_blank">service/EntitlementContact</a>|
|[name](#name)|name|<a href="EntitlementContact.md" target="_blank">service/EntitlementContact</a>|
|[contactId](#contactId)||<a href="EntitlementContact.md" target="_blank">service/EntitlementContact</a>|
|[entitlementId](#entitlementId)||<a href="EntitlementContact.md" target="_blank">service/EntitlementContact</a>|

### <a href=#entitlementContactId name="entitlementContactId">entitlementContactId</a>

Unique identifier of the contacts for the entitlements.  
First included in: service/EntitlementContact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the contacts for the entitlements.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>entitlementcontactid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/EntitlementContact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: service/EntitlementContact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/EntitlementContact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/EntitlementContact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/EntitlementContact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

name  
First included in: service/EntitlementContact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>name</td></tr><tr><td>description</td><td>name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

First included in: service/EntitlementContact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>contactid</td></tr></table>

### <a href=#entitlementId name="entitlementId">entitlementId</a>

First included in: service/EntitlementContact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>entitlementid</td></tr></table>
