---
title: AggregateKPIMeasurement - Common Data Model | Microsoft Docs
description: Measured value for a given aggregate KPI in a given context.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Aggregate KPI Measurement

Measured value for a given aggregate KPI in a given context.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/AggregateKPIMeasurement.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/AggregateKPIMeasurement  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[ownerId](#ownerId)|Owner Id|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[aggregateId](#aggregateId)|Unique identifier for entity instances|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[aggregateKPIContextId](#aggregateKPIContextId)|Parent aggregate KPI context for the aggregate record.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[count](#count)|Total number of items in the aggregate.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[max](#max)|The largest amount for any one item in the aggregate.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[mean](#mean)|The average value of the items in the aggregate.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[measuredById](#measuredById)|The person who measured the aggregate.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[measuredOn](#measuredOn)|The date upon which the aggregate was measured.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[min](#min)|The lowest value in the aggregate.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[name](#name)|Name of the aggregate KPI measurement.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[stdDev](#stdDev)|The standard deviation of the values in the aggregate.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[targetValue](#targetValue)|The desired goal value of the aggregate.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[unitId](#unitId)|The unit of measure used for this aggregate.|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[value](#value)|The meaning of the aggregate value (time, value or value per specified unit).|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[value_display](#value_display)||<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[stateCode](#stateCode)|Status of the Aggregate KPI Measurement|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[stateCode_display](#stateCode_display)||<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[statusCode](#statusCode)|Reason for the status of the Aggregate KPI Measurement|<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|
|[statusCode_display](#statusCode_display)||<a href="AggregateKPIMeasurement.md" target="_blank">automotive/AggregateKPIMeasurement</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#aggregateId name="aggregateId">aggregateId</a>

Unique identifier for entity instances  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aggregate KPI Measurement</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_aggregateid</td></tr></table>

### <a href=#aggregateKPIContextId name="aggregateKPIContextId">aggregateKPIContextId</a>

Parent aggregate KPI context for the aggregate record.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aggregate KPI Context</td></tr><tr><td>description</td><td>Parent aggregate KPI context for the aggregate record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_aggregatekpicontextid</td></tr></table>

### <a href=#count name="count">count</a>

Total number of items in the aggregate.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Count</td></tr><tr><td>description</td><td>Total number of items in the aggregate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msauto_count</td></tr></table>

### <a href=#max name="max">max</a>

The largest amount for any one item in the aggregate.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max</td></tr><tr><td>description</td><td>The largest amount for any one item in the aggregate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msauto_max</td></tr></table>

### <a href=#mean name="mean">mean</a>

The average value of the items in the aggregate.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mean</td></tr><tr><td>description</td><td>The average value of the items in the aggregate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msauto_mean</td></tr></table>

### <a href=#measuredById name="measuredById">measuredById</a>

The person who measured the aggregate.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measured By</td></tr><tr><td>description</td><td>The person who measured the aggregate.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_measuredby</td></tr></table>

### <a href=#measuredOn name="measuredOn">measuredOn</a>

The date upon which the aggregate was measured.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measured On</td></tr><tr><td>description</td><td>The date upon which the aggregate was measured.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_measuredon</td></tr></table>

### <a href=#min name="min">min</a>

The lowest value in the aggregate.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Min</td></tr><tr><td>description</td><td>The lowest value in the aggregate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msauto_min</td></tr></table>

### <a href=#name name="name">name</a>

Name of the aggregate KPI measurement.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the aggregate KPI measurement.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#stdDev name="stdDev">stdDev</a>

The standard deviation of the values in the aggregate.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>StdDev</td></tr><tr><td>description</td><td>The standard deviation of the values in the aggregate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msauto_stddev</td></tr></table>

### <a href=#targetValue name="targetValue">targetValue</a>

The desired goal value of the aggregate.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target Value</td></tr><tr><td>description</td><td>The desired goal value of the aggregate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msauto_targetvalue</td></tr></table>

### <a href=#unitId name="unitId">unitId</a>

The unit of measure used for this aggregate.  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>The unit of measure used for this aggregate.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_unitid</td></tr></table>

### <a href=#value name="value">value</a>

The meaning of the aggregate value (time, value or value per specified unit).  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Type</td></tr><tr><td>description</td><td>The meaning of the aggregate value (time, value or value per specified unit).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_value</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#value_display name="value_display">value_display</a>

First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Aggregate KPI Measurement  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Aggregate KPI Measurement</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Aggregate KPI Measurement  
First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Aggregate KPI Measurement</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/AggregateKPIMeasurement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
