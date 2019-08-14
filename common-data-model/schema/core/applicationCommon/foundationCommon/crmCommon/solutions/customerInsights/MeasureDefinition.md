---
title: MeasureDefinition - Common Data Model | Microsoft Docs
description: This describes the MeasureDefinition entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Measure Definition

Definition of KPIs partitioned by zero or more dimensions (eg. Monthly Active Users, Total Spend By Customer, Average Customer Acquisition Cost)  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/customerInsights/MeasureDefinition.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/customerInsights/MeasureDefinition  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[ownerId](#ownerId)|Owner Id|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[lastEvaluationDate](#lastEvaluationDate)|Latest date when a measure is evaluated/refreshed.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[measureDefinitionId](#measureDefinitionId)|Unique identifier for entity instances|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[measureName](#measureName)|Required name field. Name of the measure.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[measureQuery](#measureQuery)|Measure definition including entities, variables, definition, calculations, dimensions etc.|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[measureSubType](#measureSubType)|Subtype of the measure.
|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[measureSubType_display](#measureSubType_display)||<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[measureType](#measureType)|Type of the measure.
|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[measureType_display](#measureType_display)||<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[stateCode](#stateCode)|Status of the Measure Definition|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[stateCode_display](#stateCode_display)||<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[statusCode](#statusCode)|Reason for the status of the Measure Definition|<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|
|[statusCode_display](#statusCode_display)||<a href="MeasureDefinition.md" target="_blank">customerInsights/MeasureDefinition</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#lastEvaluationDate name="lastEvaluationDate">lastEvaluationDate</a>

Latest date when a measure is evaluated/refreshed.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Evaluation Date</td></tr><tr><td>description</td><td>Latest date when a measure is evaluated/refreshed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msdynci_LastEvaluationDate</td></tr></table>

### <a href=#measureDefinitionId name="measureDefinitionId">measureDefinitionId</a>

Unique identifier for entity instances  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measure Definition</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdynci_MeasureDefinitionId</td></tr></table>

### <a href=#measureName name="measureName">measureName</a>

Required name field. Name of the measure.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measure Name</td></tr><tr><td>description</td><td>Required name field. Name of the measure.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_MeasureName</td></tr></table>

### <a href=#measureQuery name="measureQuery">measureQuery</a>

Measure definition including entities, variables, definition, calculations, dimensions etc.  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measure Query</td></tr><tr><td>description</td><td>Measure definition including entities, variables, definition, calculations, dimensions etc.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_MeasureQuery</td></tr></table>

### <a href=#measureSubType name="measureSubType">measureSubType</a>

Subtype of the measure.
  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measure SubType</td></tr><tr><td>description</td><td>Subtype of the measure.
</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msdynci_MeasureSubType</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#measureSubType_display name="measureSubType_display">measureSubType_display</a>

First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#measureType name="measureType">measureType</a>

Type of the measure.
  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measure Type</td></tr><tr><td>description</td><td>Type of the measure.
</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msdynci_MeasureType</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#measureType_display name="measureType_display">measureType_display</a>

First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Measure Definition  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Measure Definition</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>stateCode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Measure Definition  
First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Measure Definition</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statusCode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: customerInsights/MeasureDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
