---
title: CompetitorSalesLiterature - Common Data Model | Microsoft Docs
description: This describes the CompetitorSalesLiterature entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# CompetitorSalesLiterature

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/sales/CompetitorSalesLiterature.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/sales/CompetitorSalesLiterature  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[competitorSalesLiteratureId](#competitorSalesLiteratureId)|Unique identifier of the sales literature for the competitor product.|<a href="CompetitorSalesLiterature.md" target="_blank">sales/CompetitorSalesLiterature</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CompetitorSalesLiterature.md" target="_blank">sales/CompetitorSalesLiterature</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="CompetitorSalesLiterature.md" target="_blank">sales/CompetitorSalesLiterature</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CompetitorSalesLiterature.md" target="_blank">sales/CompetitorSalesLiterature</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CompetitorSalesLiterature.md" target="_blank">sales/CompetitorSalesLiterature</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CompetitorSalesLiterature.md" target="_blank">sales/CompetitorSalesLiterature</a>|
|[name](#name)|name|<a href="CompetitorSalesLiterature.md" target="_blank">sales/CompetitorSalesLiterature</a>|
|[competitorId](#competitorId)||<a href="CompetitorSalesLiterature.md" target="_blank">sales/CompetitorSalesLiterature</a>|
|[salesLiteratureId](#salesLiteratureId)||<a href="CompetitorSalesLiterature.md" target="_blank">sales/CompetitorSalesLiterature</a>|

### <a href=#competitorSalesLiteratureId name="competitorSalesLiteratureId">competitorSalesLiteratureId</a>

Unique identifier of the sales literature for the competitor product.  
First included in: sales/CompetitorSalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the sales literature for the competitor product.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>competitorsalesliteratureid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: sales/CompetitorSalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: sales/CompetitorSalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: sales/CompetitorSalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: sales/CompetitorSalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: sales/CompetitorSalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

name  
First included in: sales/CompetitorSalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>name</td></tr><tr><td>description</td><td>name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#competitorId name="competitorId">competitorId</a>

First included in: sales/CompetitorSalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>competitorid</td></tr></table>

### <a href=#salesLiteratureId name="salesLiteratureId">salesLiteratureId</a>

First included in: sales/CompetitorSalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>salesliteratureid</td></tr></table>
