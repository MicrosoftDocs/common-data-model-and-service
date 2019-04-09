---
title: Territory - Common Data Model | Microsoft Docs
description: Territory represents sales regions.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Territory

Territory represents sales regions.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Territory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Territory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[territoryId](#territoryId)|Unique identifier of the territory.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the territory.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the territory.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the territory.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the territory.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[name](#name)|Name of the territory.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[description](#description)|Description of the territory.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[managerId](#managerId)|Unique identifier of the manager of the territory.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[entityImageId](#entityImageId)||<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the territory with respect to the base currency.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the territory.|<a href="Territory.md" target="_blank">applicationCommon/Territory</a>|

### <a href=#territoryId name="territoryId">territoryId</a>

Unique identifier of the territory.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Territory</td></tr><tr><td>description</td><td>Unique identifier of the territory.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>territoryid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the territory.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the territory.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the territory.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the territory.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the territory.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the territory.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the territory.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the territory.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the territory.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Territory Name</td></tr><tr><td>description</td><td>Name of the territory.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#description name="description">description</a>

Description of the territory.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the territory.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#managerId name="managerId">managerId</a>

Unique identifier of the manager of the territory.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manager</td></tr><tr><td>description</td><td>Unique identifier of the manager of the territory.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>managerid</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the territory with respect to the base currency.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the territory with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the territory.  
First included in: applicationCommon/Territory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the territory.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
