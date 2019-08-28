---
title: PropertyAssociation - Common Data Model | Microsoft Docs
description: Association of a property definition with another entity in the system.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Property Association

Association of a property definition with another entity in the system.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/PropertyAssociation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/PropertyAssociation  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[dynamicPropertyAssociationId](#dynamicPropertyAssociationId)|Shows the unique identifier of the property association.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[name](#name)|name|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[regardingObjectId](#regardingObjectId)|Shows the object that the property is associated with.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[dynamicPropertyId](#dynamicPropertyId)|Shows the property that uses this option set item.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[associationStatus](#associationStatus)|Shows the status of the property association.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[associationStatus_display](#associationStatus_display)||<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[inheritanceState](#inheritanceState)|Shows the inheritance state in relationship to the parent property.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[inheritanceState_display](#inheritanceState_display)||<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the record.|<a href="PropertyAssociation.md" target="_blank">foundationCommon/PropertyAssociation</a>|

### <a href=#dynamicPropertyAssociationId name="dynamicPropertyAssociationId">dynamicPropertyAssociationId</a>

Shows the unique identifier of the property association.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property Association ID</td></tr><tr><td>description</td><td>Shows the unique identifier of the property association.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>dynamicpropertyassociationid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

name  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>name</td></tr><tr><td>description</td><td>name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Shows the object that the property is associated with.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Shows the object that the property is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#dynamicPropertyId name="dynamicPropertyId">dynamicPropertyId</a>

Shows the property that uses this option set item.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property ID</td></tr><tr><td>description</td><td>Shows the property that uses this option set item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>dynamicpropertyid</td></tr></table>

### <a href=#associationStatus name="associationStatus">associationStatus</a>

Shows the status of the property association.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Association Status.</td></tr><tr><td>description</td><td>Shows the status of the property association.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>associationstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Deleted</td><td>1</td></tr><tr><td>en</td><td>Draft</td><td>2</td></tr><tr><td>en</td><td>Draft Added</td><td>3</td></tr><tr><td>en</td><td>Draft Deleted</td><td>4</td></tr></table></td></tr></table>

### <a href=#associationStatus_display name="associationStatus_display">associationStatus_display</a>

First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#inheritanceState name="inheritanceState">inheritanceState</a>

Shows the inheritance state in relationship to the parent property.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inheritance State.</td></tr><tr><td>description</td><td>Shows the inheritance state in relationship to the parent property.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inheritancestate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Inherited</td><td>0</td></tr><tr><td>en</td><td>Overridden</td><td>1</td></tr><tr><td>en</td><td>Owned</td><td>2</td></tr></table></td></tr></table>

### <a href=#inheritanceState_display name="inheritanceState_display">inheritanceState_display</a>

First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the record.  
First included in: foundationCommon/PropertyAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
