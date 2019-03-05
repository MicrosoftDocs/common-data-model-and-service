---
title: ResourceSpecification - Common Data Model | Microsoft Docs
description: This describes the ResourceSpecification entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Resource Specification

Selection rule that allows the scheduling engine to select a number of resources from a pool of resources. The rules can be associated with a service.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/ResourceSpecification.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/ResourceSpecification  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[resourceSpecId](#resourceSpecId)|Unique identifier of the resource specification.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[createdOn](#createdOn)|Date and time when the resource specification was created.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the resource specification.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[modifiedOn](#modifiedOn)|Date and time when the resource specification was last modified.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the resource specification.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the resourcespec.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the resourcespec.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[businessUnitId](#businessUnitId)|Unique identifier of the business unit with which the resource specification is associated.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[name](#name)|Name of the resource specification.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[constraints](#constraints)|Additional constraints, specified as expressions, which are used to filter a set of valid resources.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[description](#description)|Selection rule that allows the scheduling engine to select a number of resources from a pool of resources. The rules can be associated with a service.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[effortRequired](#effortRequired)|Number that specifies the minimal effort required from resources.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[groupObjectId](#groupObjectId)|Unique identifier of the scheduling group with which the resource specification is associated.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[objectiveExpression](#objectiveExpression)|Search strategy to use for the resource specification.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[objectTypeCode](#objectTypeCode)|Type of entity with which the resource specification is associated.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[organizationId](#organizationId)|Unique identifier of the organization with which the resource specification is associated.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[requiredCount](#requiredCount)|Required number of resources that must be available. Use -1 to indicate all resources.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|
|[sameSite](#sameSite)|Value that specifies that all valid and available resources must be in the same site.|<a href="ResourceSpecification.md" target="_blank">service/ResourceSpecification</a>|

### <a href=#resourceSpecId name="resourceSpecId">resourceSpecId</a>

Unique identifier of the resource specification.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Spec</td></tr><tr><td>description</td><td>Unique identifier of the resource specification.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>resourcespecid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the resource specification was created.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the resource specification was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the resource specification.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the resource specification.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the resource specification was last modified.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the resource specification was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the resource specification.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the resource specification.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the resourcespec.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the resourcespec.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the resourcespec.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the resourcespec.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#businessUnitId name="businessUnitId">businessUnitId</a>

Unique identifier of the business unit with which the resource specification is associated.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit with which the resource specification is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>businessunitid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the resource specification.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the resource specification.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#constraints name="constraints">constraints</a>

Additional constraints, specified as expressions, which are used to filter a set of valid resources.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Constraints</td></tr><tr><td>description</td><td>Additional constraints, specified as expressions, which are used to filter a set of valid resources.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>constraints</td></tr></table>

### <a href=#description name="description">description</a>

Selection rule that allows the scheduling engine to select a number of resources from a pool of resources. The rules can be associated with a service.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Selection rule that allows the scheduling engine to select a number of resources from a pool of resources. The rules can be associated with a service.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#effortRequired name="effortRequired">effortRequired</a>

Number that specifies the minimal effort required from resources.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effort Required</td></tr><tr><td>description</td><td>Number that specifies the minimal effort required from resources.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>effortrequired</td></tr></table>

### <a href=#groupObjectId name="groupObjectId">groupObjectId</a>

Unique identifier of the scheduling group with which the resource specification is associated.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group Object</td></tr><tr><td>description</td><td>Unique identifier of the scheduling group with which the resource specification is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>groupobjectid</td></tr></table>

### <a href=#objectiveExpression name="objectiveExpression">objectiveExpression</a>

Search strategy to use for the resource specification.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Objective Expression</td></tr><tr><td>description</td><td>Search strategy to use for the resource specification.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>sourceName</td><td>objectiveexpression</td></tr></table>

### <a href=#objectTypeCode name="objectTypeCode">objectTypeCode</a>

Type of entity with which the resource specification is associated.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Object Type </td></tr><tr><td>description</td><td>Type of entity with which the resource specification is associated.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>sourceName</td><td>objecttypecode</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization with which the resource specification is associated.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization with which the resource specification is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#requiredCount name="requiredCount">requiredCount</a>

Required number of resources that must be available. Use -1 to indicate all resources.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required Count</td></tr><tr><td>description</td><td>Required number of resources that must be available. Use -1 to indicate all resources.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>sourceName</td><td>requiredcount</td></tr></table>

### <a href=#sameSite name="sameSite">sameSite</a>

Value that specifies that all valid and available resources must be in the same site.  
First included in: service/ResourceSpecification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Same Site</td></tr><tr><td>description</td><td>Value that specifies that all valid and available resources must be in the same site.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>samesite</td></tr></table>
