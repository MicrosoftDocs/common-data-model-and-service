---
title: WebTemplate - Common Data Model | Microsoft Docs
description: This describes the WebTemplate entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Web Template

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebTemplate.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/portals/WebTemplate  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[webTemplateId](#webTemplateId)|Shows the entity instance.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[createdOn](#createdOn)|Shows the date and time when the record was created.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was modified.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[organizationId](#organizationId)|Shows the organization.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[stateCode](#stateCode)|Status of the Web Template|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[stateCode_display](#stateCode_display)||<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[statusCode](#statusCode)|Select the web template's status.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[statusCode_display](#statusCode_display)||<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[importSequenceNumber](#importSequenceNumber)|Shows the sequence number of the import that created this record.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Shows the date and time that the record was migrated.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Shows the time zone code that was in use when the record was created.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[name](#name)|Type the name of the custom entity.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[MIMEType](#MIMEType)|Shows the MIME type of the web template content.|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[source](#source)||<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|
|[websiteId](#websiteId)|Unique identifier for Website associated with Web Template|<a href="WebTemplate.md" target="_blank">portals/WebTemplate</a>|

### <a href=#webTemplateId name="webTemplateId">webTemplateId</a>

Shows the entity instance.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Web Template</td></tr><tr><td>description</td><td>Shows the entity instance.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>adx_webtemplateid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the record was created.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was modified.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Shows the organization.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shows the organization.</td></tr><tr><td>description</td><td>Shows the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Web Template  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Web Template</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the web template's status.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the web template's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Shows the sequence number of the import that created this record.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Shows the sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Shows the date and time that the record was migrated.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Shows the date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Shows the time zone code that was in use when the record was created.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Shows the time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_name</td></tr></table>

### <a href=#MIMEType name="MIMEType">MIMEType</a>

Shows the MIME type of the web template content.  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>MIME Type</td></tr><tr><td>description</td><td>Shows the MIME type of the web template content.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_mimetype</td></tr></table>

### <a href=#source name="source">source</a>

First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_source</td></tr></table>

### <a href=#websiteId name="websiteId">websiteId</a>

Unique identifier for Website associated with Web Template  
First included in: portals/WebTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Unique identifier for Website associated with Web Template</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_websiteid</td></tr></table>
