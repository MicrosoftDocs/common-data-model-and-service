---
title: WebFile - Common Data Model | Microsoft Docs
description: Storage of files used in the web Portals.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Web File

Storage of files used in the web Portals.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebFile.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/portals/WebFile  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[ownerId](#ownerId)|Owner Id|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[webFileId](#webFileId)|Unique identifier for entity instances|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[stateCode](#stateCode)|Status of the Web File|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[stateCode_display](#stateCode_display)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[statusCode](#statusCode)|Reason for the status of the Web File|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[statusCode_display](#statusCode_display)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[name](#name)|Shows the name of the custom entity.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[adxCreatedByIPAddress](#adxCreatedByIPAddress)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[adxCreatedByUsername](#adxCreatedByUsername)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[displayDate](#displayDate)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[displayOrder](#displayOrder)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[hiddenFromSitemap](#hiddenFromSitemap)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[adxModifiedByIPAddress](#adxModifiedByIPAddress)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[adxModifiedByUsername](#adxModifiedByUsername)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[parentPageId](#parentPageId)|Unique identifier for Web Page associated with Web File.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[partialURL](#partialURL)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[subjectId](#subjectId)|Unique identifier for Subject associated with Web File.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[summary](#summary)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[websiteId](#websiteId)|Unique identifier for Website associated with Web File.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[allowOrigin](#allowOrigin)|Defines CORS header Access-Control-Allow-Origin for cross origin requests.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[cloudBlobAddress](#cloudBlobAddress)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[contentDisposition](#contentDisposition)|Shows the value to be applied to the HTTP Response Headers Content-Disposition.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[contentDisposition_display](#contentDisposition_display)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[enableTracking](#enableTracking)|Select whether to enable logging of users' downloads of this web file.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[excludeFromSearch](#excludeFromSearch)|Shows whether the web file is excluded from the portal search.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[expirationDate](#expirationDate)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[masterWebFileId](#masterWebFileId)|Unique identifier for Web File associated with Web File.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[publishingStateId](#publishingStateId)|Unique identifier for Publishing State associated with Web File.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[releaseDate](#releaseDate)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[title](#title)||<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[blogPostId](#blogPostId)|Unique identifier for Blog Post associated with Web File.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|
|[ideaId](#ideaId)|Shows the Idea associated with the Web File.|<a href="WebFile.md" target="_blank">portals/WebFile</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#webFileId name="webFileId">webFileId</a>

Unique identifier for entity instances  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Web File</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>adx_webfileid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Web File  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Web File</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Web File  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Web File</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Shows the name of the custom entity.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Shows the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_name</td></tr></table>

### <a href=#adxCreatedByIPAddress name="adxCreatedByIPAddress">adxCreatedByIPAddress</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By IP Address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_createdbyipaddress</td></tr></table>

### <a href=#adxCreatedByUsername name="adxCreatedByUsername">adxCreatedByUsername</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By Username</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_createdbyusername</td></tr></table>

### <a href=#displayDate name="displayDate">displayDate</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_displaydate</td></tr></table>

### <a href=#displayOrder name="displayOrder">displayOrder</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display Order</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_displayorder</td></tr></table>

### <a href=#hiddenFromSitemap name="hiddenFromSitemap">hiddenFromSitemap</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hidden From Sitemap</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_hiddenfromsitemap</td></tr></table>

### <a href=#adxModifiedByIPAddress name="adxModifiedByIPAddress">adxModifiedByIPAddress</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By IP Address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_modifiedbyipaddress</td></tr></table>

### <a href=#adxModifiedByUsername name="adxModifiedByUsername">adxModifiedByUsername</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By Username</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_modifiedbyusername</td></tr></table>

### <a href=#parentPageId name="parentPageId">parentPageId</a>

Unique identifier for Web Page associated with Web File.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Page</td></tr><tr><td>description</td><td>Unique identifier for Web Page associated with Web File.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_parentpageid</td></tr></table>

### <a href=#partialURL name="partialURL">partialURL</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partial URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_partialurl</td></tr></table>

### <a href=#subjectId name="subjectId">subjectId</a>

Unique identifier for Subject associated with Web File.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Unique identifier for Subject associated with Web File.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_subjectid</td></tr></table>

### <a href=#summary name="summary">summary</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Summary</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4096</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_summary</td></tr></table>

### <a href=#websiteId name="websiteId">websiteId</a>

Unique identifier for Website associated with Web File.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Unique identifier for Website associated with Web File.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_websiteid</td></tr></table>

### <a href=#allowOrigin name="allowOrigin">allowOrigin</a>

Defines CORS header Access-Control-Allow-Origin for cross origin requests.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Origin</td></tr><tr><td>description</td><td>Defines CORS header Access-Control-Allow-Origin for cross origin requests.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_alloworigin</td></tr></table>

### <a href=#cloudBlobAddress name="cloudBlobAddress">cloudBlobAddress</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cloud Blob Address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_cloudblobaddress</td></tr></table>

### <a href=#contentDisposition name="contentDisposition">contentDisposition</a>

Shows the value to be applied to the HTTP Response Headers Content-Disposition.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Content-Disposition</td></tr><tr><td>description</td><td>Shows the value to be applied to the HTTP Response Headers Content-Disposition.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_contentdisposition</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>inline</td><td>756150000</td></tr><tr><td>en</td><td>attachment</td><td>756150001</td></tr></table></td></tr></table>

### <a href=#contentDisposition_display name="contentDisposition_display">contentDisposition_display</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#enableTracking name="enableTracking">enableTracking</a>

Select whether to enable logging of users' downloads of this web file.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Tracking (deprecated)</td></tr><tr><td>description</td><td>Select whether to enable logging of users' downloads of this web file.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_enabletracking</td></tr></table>

### <a href=#excludeFromSearch name="excludeFromSearch">excludeFromSearch</a>

Shows whether the web file is excluded from the portal search.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exclude From Search</td></tr><tr><td>description</td><td>Shows whether the web file is excluded from the portal search.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_excludefromsearch</td></tr></table>

### <a href=#expirationDate name="expirationDate">expirationDate</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiration Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_expirationdate</td></tr></table>

### <a href=#masterWebFileId name="masterWebFileId">masterWebFileId</a>

Unique identifier for Web File associated with Web File.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Master Web File</td></tr><tr><td>description</td><td>Unique identifier for Web File associated with Web File.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_masterwebfileid</td></tr></table>

### <a href=#publishingStateId name="publishingStateId">publishingStateId</a>

Unique identifier for Publishing State associated with Web File.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publishing State</td></tr><tr><td>description</td><td>Unique identifier for Publishing State associated with Web File.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_publishingstateid</td></tr></table>

### <a href=#releaseDate name="releaseDate">releaseDate</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Release Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_releasedate</td></tr></table>

### <a href=#title name="title">title</a>

First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>512</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_title</td></tr></table>

### <a href=#blogPostId name="blogPostId">blogPostId</a>

Unique identifier for Blog Post associated with Web File.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Blog Post</td></tr><tr><td>description</td><td>Unique identifier for Blog Post associated with Web File.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_blogpostid</td></tr></table>

### <a href=#ideaId name="ideaId">ideaId</a>

Shows the Idea associated with the Web File.  
First included in: portals/WebFile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Idea</td></tr><tr><td>description</td><td>Shows the Idea associated with the Web File.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_ideaid</td></tr></table>
