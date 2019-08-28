---
title: PropertyInstance - Common Data Model | Microsoft Docs
description: Instance of a property with its value.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Property Instance

Instance of a property with its value.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/PropertyInstance.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/PropertyInstance  
- [/foundationCommon/crmCommon/sales/PropertyInstance](crmCommon/sales/PropertyInstance.md "/core/applicationCommon/foundationCommon/crmCommon/sales/PropertyInstance.cdm.json/PropertyInstance")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[ownerId](#ownerId)|Owner Id|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[dynamicPropertyInstanceIdType](#dynamicPropertyInstanceIdType)|The name of the entity linked by dynamicPropertyInstanceId|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[dynamicPropertyInstanceid](#dynamicPropertyInstanceid)|Shows the unique identifier of the property instance.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[name](#name)|name|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[valueInteger](#valueInteger)|Shows the integer value of the property.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[valueDecimal](#valueDecimal)|Shows the decimal value of the property.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[valueDouble](#valueDouble)|Shows the double value of the property.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[valueString](#valueString)|Shows the string value of the property.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[dynamicPropertyId](#dynamicPropertyId)|Shows the property that this record is associated with.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[isValid](#isValid)|Shows whether the property value is valid.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the record.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="PropertyInstance.md" target="_blank">foundationCommon/PropertyInstance</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#dynamicPropertyInstanceIdType name="dynamicPropertyInstanceIdType">dynamicPropertyInstanceIdType</a>

The name of the entity linked by dynamicPropertyInstanceId  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>dynamicPropertyInstanceId Type</td></tr><tr><td>description</td><td>The name of the entity linked by dynamicPropertyInstanceId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>dynamicpropertyinstanceidtype</td></tr></table>

### <a href=#dynamicPropertyInstanceid name="dynamicPropertyInstanceid">dynamicPropertyInstanceid</a>

Shows the unique identifier of the property instance.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property Instance ID</td></tr><tr><td>description</td><td>Shows the unique identifier of the property instance.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>dynamicpropertyinstanceid</td></tr></table>

### <a href=#name name="name">name</a>

name  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>name</td></tr><tr><td>description</td><td>name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#valueInteger name="valueInteger">valueInteger</a>

Shows the integer value of the property.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Integer Value</td></tr><tr><td>description</td><td>Shows the integer value of the property.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>valueinteger</td></tr></table>

### <a href=#valueDecimal name="valueDecimal">valueDecimal</a>

Shows the decimal value of the property.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decimal Value</td></tr><tr><td>description</td><td>Shows the decimal value of the property.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>valuedecimal</td></tr></table>

### <a href=#valueDouble name="valueDouble">valueDouble</a>

Shows the double value of the property.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Double Value</td></tr><tr><td>description</td><td>Shows the double value of the property.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>valuedouble</td></tr></table>

### <a href=#valueString name="valueString">valueString</a>

Shows the string value of the property.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>String Value</td></tr><tr><td>description</td><td>Shows the string value of the property.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>valuestring</td></tr></table>

### <a href=#dynamicPropertyId name="dynamicPropertyId">dynamicPropertyId</a>

Shows the property that this record is associated with.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property ID</td></tr><tr><td>description</td><td>Shows the property that this record is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>dynamicpropertyid</td></tr></table>

### <a href=#isValid name="isValid">isValid</a>

Shows whether the property value is valid.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Valid</td></tr><tr><td>description</td><td>Shows whether the property value is valid.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>validationstatus</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the record.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: foundationCommon/PropertyInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>
