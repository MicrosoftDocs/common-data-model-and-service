---
title: RatingValue - Common Data Model | Microsoft Docs
description: A unique value associated with a rating model that allows providing a user friendly rating value.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Rating Value

A unique value associated with a rating model that allows providing a user friendly rating value.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/RatingValue.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/foundationCommon/RatingValue](../../RatingValue.md "/core/applicationCommon/foundationCommon/RatingValue.cdm.json/RatingValue")  
- /foundationCommon/crmCommon/projectCommon/RatingValue  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="RatingValue.md" target="_blank">projectCommon/RatingValue</a>|
|[ownerId](#ownerId)|Owner Id|<a href="RatingValue.md" target="_blank">projectCommon/RatingValue</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[ratingValueId](#ratingValueId)|Unique identifier of the rating value.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[name](#name)|Type a name that represents a rating value such as familiar, good, proficient etc.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[ratingModel](#ratingModel)|Select the model that this rating value is associated with.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[stateCode](#stateCode)|Status of the Rating Value|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[stateCode_display](#stateCode_display)||<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[statusCode](#statusCode)|Reason for the status of the Rating Value|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[statusCode_display](#statusCode_display)||<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[value](#value)|Type a rating value which is unique to the rating model it is associated with and lies within the range specified on the model.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the ratingvalue with respect to the base currency.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Exchange rate for the currency associated with the RatingValue with respect to the base currency.|<a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>|
|[isDefault](#isDefault)||<a href="RatingValue.md" target="_blank">projectCommon/RatingValue</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectCommon/RatingValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectCommon/RatingValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#ratingValueId name="ratingValueId">ratingValueId</a>

Unique identifier of the rating value.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating Value</td></tr><tr><td>description</td><td>Unique identifier of the rating value.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ratingvalueid</td></tr></table>

### <a href=#name name="name">name</a>

Type a name that represents a rating value such as familiar, good, proficient etc.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a name that represents a rating value such as familiar, good, proficient etc.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#ratingModel name="ratingModel">ratingModel</a>

Select the model that this rating value is associated with.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating Model</td></tr><tr><td>description</td><td>Select the model that this rating value is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ratingmodel</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Rating Value  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Rating Value</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Rating Value  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Rating Value</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#value name="value">value</a>

Type a rating value which is unique to the rating model it is associated with and lies within the range specified on the model.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value</td></tr><tr><td>description</td><td>Type a rating value which is unique to the rating model it is associated with and lies within the range specified on the model.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>200</td></tr><tr><td>minimumValue</td><td>-200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>value</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the ratingvalue with respect to the base currency.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExchangeRate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the ratingvalue with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Exchange rate for the currency associated with the RatingValue with respect to the base currency.  
First included in: <a href="../../RatingValue.md" target="_blank">foundationCommon/RatingValue</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the RatingValue with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#isDefault name="isDefault">isDefault</a>

First included in: projectCommon/RatingValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Default</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_isdefault</td></tr></table>
