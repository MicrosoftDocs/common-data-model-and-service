---
title: PropertyOptionSetItem - Common Data Model | Microsoft Docs
description: Item with a name and value in a property option set type.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Property Option Set Item

Item with a name and value in a property option set type.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/PropertyOptionSetItem.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/PropertyOptionSetItem  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[dynamicPropertyOptionSetValueId](#dynamicPropertyOptionSetValueId)|Shows the unique identifier of the property option set item.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[dynamicPropertyOptionName](#dynamicPropertyOptionName)|Type the name of the property option set item.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[dynamicPropertyOptionValue](#dynamicPropertyOptionValue)|Shows the value of the property option set item.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[dynamicPropertyOptionDescription](#dynamicPropertyOptionDescription)|Type additional information about the property option set item.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[dynamicPropertyId](#dynamicPropertyId)|Shows the property that uses this option set item.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[dynamicPropertyOptionSetValueSequenceNumber](#dynamicPropertyOptionSetValueSequenceNumber)|Internal Use Only|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the record.|<a href="PropertyOptionSetItem.md" target="_blank">foundationCommon/PropertyOptionSetItem</a>|

### <a href=#dynamicPropertyOptionSetValueId name="dynamicPropertyOptionSetValueId">dynamicPropertyOptionSetValueId</a>

Shows the unique identifier of the property option set item.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property Option Set ID</td></tr><tr><td>description</td><td>Shows the unique identifier of the property option set item.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>dynamicpropertyoptionsetvalueid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#dynamicPropertyOptionName name="dynamicPropertyOptionName">dynamicPropertyOptionName</a>

Type the name of the property option set item.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the property option set item.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>dynamicpropertyoptionname</td></tr></table>

### <a href=#dynamicPropertyOptionValue name="dynamicPropertyOptionValue">dynamicPropertyOptionValue</a>

Shows the value of the property option set item.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value</td></tr><tr><td>description</td><td>Shows the value of the property option set item.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>dynamicpropertyoptionvalue</td></tr></table>

### <a href=#dynamicPropertyOptionDescription name="dynamicPropertyOptionDescription">dynamicPropertyOptionDescription</a>

Type additional information about the property option set item.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information about the property option set item.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>dynamicpropertyoptiondescription</td></tr></table>

### <a href=#dynamicPropertyId name="dynamicPropertyId">dynamicPropertyId</a>

Shows the property that uses this option set item.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property ID</td></tr><tr><td>description</td><td>Shows the property that uses this option set item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>dynamicpropertyid</td></tr></table>

### <a href=#dynamicPropertyOptionSetValueSequenceNumber name="dynamicPropertyOptionSetValueSequenceNumber">dynamicPropertyOptionSetValueSequenceNumber</a>

Internal Use Only  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internal Use Only</td></tr><tr><td>description</td><td>Internal Use Only</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>dynamicpropertyoptionsetvaluesequencenumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the record.  
First included in: foundationCommon/PropertyOptionSetItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
