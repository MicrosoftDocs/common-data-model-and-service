---
title: Indicator - Common Data Model | Microsoft Docs
description: This describes the Indicator entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Indicator

An Indicator describes what will be measured to track evidence of a Result. Indicators can be qualitative or quantitative and may or may not be aggregable.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Indicator.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Indicator  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[indicatorId](#indicatorId)|Unique identifier for entity instances|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[stateCode](#stateCode)|Status of the Indicator|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[stateCode_display](#stateCode_display)||<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[statusCode](#statusCode)|Reason for the status of the Indicator|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[statusCode_display](#statusCode_display)||<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[name](#name)|The name of the custom entity.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[aggregationStatus](#aggregationStatus)|Indicates whether the data in the result set are suitable for aggregation|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[ascending](#ascending)|An IATI boolean describing the behaviour of the indicator. It is “true” if the indicator improves from small to large (e.g. clinics built); false if it improves from large to small (e.g. cases of a di|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[baselineValue](#baselineValue)|An IATI string definining the Baseline value for the value being reported.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[description](#description)|Description|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[endDate](#endDate)|End date of the Indicator.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[measure](#measure)|An IATI code defining the unit of measure in which the value is reported.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[measure_display](#measure_display)||<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[resultId](#resultId)|Result|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[startDate](#startDate)|Start Date of the Indicator|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|
|[indicatorMeasureId](#indicatorMeasureId)|The unit of measure in which the value is reported.|<a href="Indicator.md" target="_blank">nonProfit/Indicator</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#indicatorId name="indicatorId">indicatorId</a>

Unique identifier for entity instances  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indicator</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_indicatorid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Indicator  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Indicator</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Indicator  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Indicator</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#aggregationStatus name="aggregationStatus">aggregationStatus</a>

Indicates whether the data in the result set are suitable for aggregation  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aggregation Status</td></tr><tr><td>description</td><td>Indicates whether the data in the result set are suitable for aggregation</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_aggregationstatus</td></tr></table>

### <a href=#ascending name="ascending">ascending</a>

An IATI boolean describing the behaviour of the indicator. It is “true” if the indicator improves from small to large (e.g. clinics built); false if it improves from large to small (e.g. cases of a di  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ascending</td></tr><tr><td>description</td><td>An IATI boolean describing the behaviour of the indicator. It is “true” if the indicator improves from small to large (e.g. clinics built); false if it improves from large to small (e.g. cases of a di</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_ascending</td></tr></table>

### <a href=#baselineValue name="baselineValue">baselineValue</a>

An IATI string definining the Baseline value for the value being reported.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Baseline Value</td></tr><tr><td>description</td><td>An IATI string definining the Baseline value for the value being reported.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_baselinevalue</td></tr></table>

### <a href=#description name="description">description</a>

Description  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_description</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

End date of the Indicator.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>End date of the Indicator.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_enddate</td></tr></table>

### <a href=#measure name="measure">measure</a>

An IATI code defining the unit of measure in which the value is reported.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measure</td></tr><tr><td>description</td><td>An IATI code defining the unit of measure in which the value is reported.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_measure</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unit</td><td>844060000</td></tr><tr><td>en</td><td>Percentage</td><td>844060001</td></tr><tr><td>en</td><td>Nominal</td><td>844060002</td></tr><tr><td>en</td><td>Ordinal</td><td>844060003</td></tr><tr><td>en</td><td>Qualitative</td><td>844060004</td></tr></table></td></tr></table>

### <a href=#measure_display name="measure_display">measure_display</a>

First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#resultId name="resultId">resultId</a>

Result  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Result</td></tr><tr><td>description</td><td>Result</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_resultid</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

Start Date of the Indicator  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Start Date of the Indicator</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_startdate</td></tr></table>

### <a href=#indicatorMeasureId name="indicatorMeasureId">indicatorMeasureId</a>

The unit of measure in which the value is reported.  
First included in: nonProfit/Indicator (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indicator Measure</td></tr><tr><td>description</td><td>The unit of measure in which the value is reported.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_indicatormeasureid</td></tr></table>
