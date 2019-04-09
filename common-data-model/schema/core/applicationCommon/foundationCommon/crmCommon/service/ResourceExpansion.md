---
title: ResourceExpansion - Common Data Model | Microsoft Docs
description: Resource Expansions.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Resource Expansion

Resource Expansions.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/ResourceExpansion.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/ResourceExpansion  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[resourceGroupExpansionId](#resourceGroupExpansionId)|Unique identifier of the resource expansion record.|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[name](#name)|name|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[itemId](#itemId)|Item that is part of expansion of resource identified by object ID. One object ID can have many item IDs.|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[methodCode](#methodCode)|Code for retrieval method.|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[methodCode_display](#methodCode_display)||<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was last modified.|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|
|[objectId](#objectId)|Object being expanded.|<a href="ResourceExpansion.md" target="_blank">service/ResourceExpansion</a>|

### <a href=#resourceGroupExpansionId name="resourceGroupExpansionId">resourceGroupExpansionId</a>

Unique identifier of the resource expansion record.  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Expansion</td></tr><tr><td>description</td><td>Unique identifier of the resource expansion record.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>resourcegroupexpansionid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

name  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>name</td></tr><tr><td>description</td><td>name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#itemId name="itemId">itemId</a>

Item that is part of expansion of resource identified by object ID. One object ID can have many item IDs.  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item</td></tr><tr><td>description</td><td>Item that is part of expansion of resource identified by object ID. One object ID can have many item IDs.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>itemid</td></tr></table>

### <a href=#methodCode name="methodCode">methodCode</a>

Code for retrieval method.  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Method</td></tr><tr><td>description</td><td>Code for retrieval method.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>methodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Participating Resources</td><td>1</td></tr><tr><td>en</td><td>Schedulable Resources</td><td>2</td></tr><tr><td>en</td><td>Supported Services</td><td>3</td></tr><tr><td>en</td><td>Resources</td><td>4</td></tr><tr><td>en</td><td>All Resources</td><td>5</td></tr><tr><td>en</td><td>Subgroups</td><td>6</td></tr><tr><td>en</td><td>Parent Groups</td><td>7</td></tr><tr><td>en</td><td>All Subgroups</td><td>8</td></tr></table></td></tr></table>

### <a href=#methodCode_display name="methodCode_display">methodCode_display</a>

First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was last modified.  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#objectId name="objectId">objectId</a>

Object being expanded.  
First included in: service/ResourceExpansion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Object</td></tr><tr><td>description</td><td>Object being expanded.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>objectid</td></tr></table>
