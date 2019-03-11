---
title: GoalMetric - Common Data Model | Microsoft Docs
description: Type of measurement for a goal, such as money amount or count.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Goal Metric

Type of measurement for a goal, such as money amount or count.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/GoalMetric.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /GoalMetric  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[metricId](#metricId)|Unique identifier of the goal metric.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[organizationId](#organizationId)|Unique identifier of the organization.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[stateCode](#stateCode)|Status of the goal metric.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[stateCode_display](#stateCode_display)||<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[statusCode](#statusCode)|Reason for the status of the goal metric.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[statusCode_display](#statusCode_display)||<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[versionNumber](#versionNumber)|Version number of the goal metric.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[name](#name)|Name of the goal metric.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[amountDataType](#amountDataType)|Data type of the amount.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[amountDataType_display](#amountDataType_display)||<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[isAmount](#isAmount)|Information that indicates whether the metric type is Count or Amount.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[isStretchTracked](#isStretchTracked)|Indicates whether the goal metric tracks stretch targets.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|
|[description](#description)|Description of the goal metric.|<a href="GoalMetric.md" target="_blank">applicationCommon/GoalMetric</a>|

### <a href=#metricId name="metricId">metricId</a>

Unique identifier of the goal metric.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal Metric</td></tr><tr><td>description</td><td>Unique identifier of the goal metric.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>metricid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier of the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the goal metric.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the goal metric.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the goal metric.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the goal metric.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Open</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Closed</td><td>1</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the goal metric.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the goal metric.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the goal metric.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the goal metric.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#amountDataType name="amountDataType">amountDataType</a>

Data type of the amount.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Data Type</td></tr><tr><td>description</td><td>Data type of the amount.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>amountdatatype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Money</td><td>0</td></tr><tr><td>en</td><td>Decimal</td><td>1</td></tr><tr><td>en</td><td>Integer</td><td>2</td></tr></table></td></tr></table>

### <a href=#amountDataType_display name="amountDataType_display">amountDataType_display</a>

First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isAmount name="isAmount">isAmount</a>

Information that indicates whether the metric type is Count or Amount.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Metric Type</td></tr><tr><td>description</td><td>Information that indicates whether the metric type is Count or Amount.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isamount</td></tr></table>

### <a href=#isStretchTracked name="isStretchTracked">isStretchTracked</a>

Indicates whether the goal metric tracks stretch targets.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Track Stretch Target</td></tr><tr><td>description</td><td>Indicates whether the goal metric tracks stretch targets.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isstretchtracked</td></tr></table>

### <a href=#description name="description">description</a>

Description of the goal metric.  
First included in: applicationCommon/GoalMetric (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the goal metric.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>
