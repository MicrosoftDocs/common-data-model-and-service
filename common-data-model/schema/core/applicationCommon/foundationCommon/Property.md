---
title: Property - Common Data Model | Microsoft Docs
description: Information about a product property.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Property

Information about a product property.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/Property.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/Property  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[dynamicPropertyId](#dynamicPropertyId)|Shows the unique identifier of the property.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[name](#name)|Type the name of the property.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[description](#description)|Type a description for the property.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[dataType](#dataType)|Select the data type of the property.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[dataType_display](#dataType_display)||<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[defaultValueInteger](#defaultValueInteger)|Shows the default value of the property for a whole number data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[defaultValueString](#defaultValueString)|Shows the default value of the property for a string data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[defaultValueDecimal](#defaultValueDecimal)|Shows the default value of the property for a decimal data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[baseDynamicPropertyId](#baseDynamicPropertyId)|Shows the property in the product family that this property is being inherited from.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[overwrittenDynamicPropertyId](#overwrittenDynamicPropertyId)|Shows the related overwritten property.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[rootDynamicPropertyId](#rootDynamicPropertyId)|Shows the root property that this property is derived from.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[minValueDecimal](#minValueDecimal)|Shows the minimum allowed value of the property for a decimal data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[maxValueDecimal](#maxValueDecimal)|Shows the maximum allowed value of the property for a decimal data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[precision](#precision)|Shows the allowed precision of the property for a whole number data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[stateCode](#stateCode)|Shows the state of the property.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[stateCode_display](#stateCode_display)||<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[statusCode](#statusCode)|Shows whether the property is active or inactive.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[statusCode_display](#statusCode_display)||<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[regardingObjectId](#regardingObjectId)|Choose the product that the property is associated with.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[defaultValueDouble](#defaultValueDouble)|Shows the default value of the property for a double data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[minValueDouble](#minValueDouble)|Shows the minimum allowed value of the property for a double data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[maxValueDouble](#maxValueDouble)|Shows the maximum allowed value of the property for a double data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[minValueInteger](#minValueInteger)|Shows the minimum allowed value of the property for a whole number data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[maxValueInteger](#maxValueInteger)|Shows the maximum allowed value of the property for a whole number data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[isReadOnly](#isReadOnly)|Defines whether the attribute is read-only or if it can be edited.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[isHidden](#isHidden)|Defines whether the attribute is hidden or shown.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[isRequired](#isRequired)|Defines whether the attribute is mandatory.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[maxLengthString](#maxLengthString)|Shows the maximum allowed length of the property for a string data type.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|
|[defaultValueOptionSet](#defaultValueOptionSet)|Shows the default value of the property.|<a href="Property.md" target="_blank">foundationCommon/Property</a>|

### <a href=#dynamicPropertyId name="dynamicPropertyId">dynamicPropertyId</a>

Shows the unique identifier of the property.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property ID</td></tr><tr><td>description</td><td>Shows the unique identifier of the property.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>dynamicpropertyid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the property.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the property.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#description name="description">description</a>

Type a description for the property.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type a description for the property.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#dataType name="dataType">dataType</a>

Select the data type of the property.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data Type</td></tr><tr><td>description</td><td>Select the data type of the property.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>datatype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Option Set</td><td>0</td></tr><tr><td>en</td><td>Decimal</td><td>1</td></tr><tr><td>en</td><td>Floating Point Number</td><td>2</td></tr><tr><td>en</td><td>Single Line Of Text</td><td>3</td></tr><tr><td>en</td><td>Whole Number</td><td>4</td></tr></table></td></tr></table>

### <a href=#dataType_display name="dataType_display">dataType_display</a>

First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#defaultValueInteger name="defaultValueInteger">defaultValueInteger</a>

Shows the default value of the property for a whole number data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Whole Number Value</td></tr><tr><td>description</td><td>Shows the default value of the property for a whole number data type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultvalueinteger</td></tr></table>

### <a href=#defaultValueString name="defaultValueString">defaultValueString</a>

Shows the default value of the property for a string data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default String Value</td></tr><tr><td>description</td><td>Shows the default value of the property for a string data type.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultvaluestring</td></tr></table>

### <a href=#defaultValueDecimal name="defaultValueDecimal">defaultValueDecimal</a>

Shows the default value of the property for a decimal data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Decimal Value</td></tr><tr><td>description</td><td>Shows the default value of the property for a decimal data type.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultvaluedecimal</td></tr></table>

### <a href=#baseDynamicPropertyId name="baseDynamicPropertyId">baseDynamicPropertyId</a>

Shows the property in the product family that this property is being inherited from.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base Property</td></tr><tr><td>description</td><td>Shows the property in the product family that this property is being inherited from.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>basedynamicpropertyid</td></tr></table>

### <a href=#overwrittenDynamicPropertyId name="overwrittenDynamicPropertyId">overwrittenDynamicPropertyId</a>

Shows the related overwritten property.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overwritten Property</td></tr><tr><td>description</td><td>Shows the related overwritten property.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overwrittendynamicpropertyid</td></tr></table>

### <a href=#rootDynamicPropertyId name="rootDynamicPropertyId">rootDynamicPropertyId</a>

Shows the root property that this property is derived from.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Root Property</td></tr><tr><td>description</td><td>Shows the root property that this property is derived from.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rootdynamicpropertyid</td></tr></table>

### <a href=#minValueDecimal name="minValueDecimal">minValueDecimal</a>

Shows the minimum allowed value of the property for a decimal data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum Decimal Value</td></tr><tr><td>description</td><td>Shows the minimum allowed value of the property for a decimal data type.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>minvaluedecimal</td></tr></table>

### <a href=#maxValueDecimal name="maxValueDecimal">maxValueDecimal</a>

Shows the maximum allowed value of the property for a decimal data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum Decimal Value</td></tr><tr><td>description</td><td>Shows the maximum allowed value of the property for a decimal data type.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maxvaluedecimal</td></tr></table>

### <a href=#precision name="precision">precision</a>

Shows the allowed precision of the property for a whole number data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Precision</td></tr><tr><td>description</td><td>Shows the allowed precision of the property for a whole number data type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>5</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>precision</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows the state of the property.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows the state of the property.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Draft</td><td>1</td></tr><tr><td>en</td><td>Retired</td><td>2</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Shows whether the property is active or inactive.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Shows whether the property is active or inactive.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Draft</td><td>0</td><td>1</td></tr><tr><td>en</td><td>Retired</td><td>2</td><td>2</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Choose the product that the property is associated with.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Choose the product that the property is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#defaultValueDouble name="defaultValueDouble">defaultValueDouble</a>

Shows the default value of the property for a double data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Double Value</td></tr><tr><td>description</td><td>Shows the default value of the property for a double data type.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultvaluedouble</td></tr></table>

### <a href=#minValueDouble name="minValueDouble">minValueDouble</a>

Shows the minimum allowed value of the property for a double data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum Double Value</td></tr><tr><td>description</td><td>Shows the minimum allowed value of the property for a double data type.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>minvaluedouble</td></tr></table>

### <a href=#maxValueDouble name="maxValueDouble">maxValueDouble</a>

Shows the maximum allowed value of the property for a double data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum Double Value</td></tr><tr><td>description</td><td>Shows the maximum allowed value of the property for a double data type.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maxvaluedouble</td></tr></table>

### <a href=#minValueInteger name="minValueInteger">minValueInteger</a>

Shows the minimum allowed value of the property for a whole number data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum Whole Number Value</td></tr><tr><td>description</td><td>Shows the minimum allowed value of the property for a whole number data type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>minvalueinteger</td></tr></table>

### <a href=#maxValueInteger name="maxValueInteger">maxValueInteger</a>

Shows the maximum allowed value of the property for a whole number data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum Whole Number Value</td></tr><tr><td>description</td><td>Shows the maximum allowed value of the property for a whole number data type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maxvalueinteger</td></tr></table>

### <a href=#isReadOnly name="isReadOnly">isReadOnly</a>

Defines whether the attribute is read-only or if it can be edited.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Read-Only</td></tr><tr><td>description</td><td>Defines whether the attribute is read-only or if it can be edited.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isreadonly</td></tr></table>

### <a href=#isHidden name="isHidden">isHidden</a>

Defines whether the attribute is hidden or shown.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hidden</td></tr><tr><td>description</td><td>Defines whether the attribute is hidden or shown.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ishidden</td></tr></table>

### <a href=#isRequired name="isRequired">isRequired</a>

Defines whether the attribute is mandatory.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required</td></tr><tr><td>description</td><td>Defines whether the attribute is mandatory.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isrequired</td></tr></table>

### <a href=#maxLengthString name="maxLengthString">maxLengthString</a>

Shows the maximum allowed length of the property for a string data type.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum String Length</td></tr><tr><td>description</td><td>Shows the maximum allowed length of the property for a string data type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1024</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maxlengthstring</td></tr></table>

### <a href=#defaultValueOptionSet name="defaultValueOptionSet">defaultValueOptionSet</a>

Shows the default value of the property.  
First included in: foundationCommon/Property (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default OptionSet Value</td></tr><tr><td>description</td><td>Shows the default value of the property.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultvalueoptionset</td></tr></table>
