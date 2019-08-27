---
title: WebPage - Common Data Model | Microsoft Docs
description: Webpage
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Web Page

Webpage  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPage.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/portals/WebPage  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[ownerId](#ownerId)|Owner Id|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[webpageId](#webpageId)|Unique identifier for entity instances|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[stateCode](#stateCode)|Status of the Web Page|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[stateCode_display](#stateCode_display)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[statusCode](#statusCode)|Reason for the status of the Web Page|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[statusCode_display](#statusCode_display)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[name](#name)|Shows the name of the custom entity.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[authorId](#authorId)|Unique identifier for Contact associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[category](#category)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[category_display](#category_display)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[copy](#copy)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[adxCreatedByIPAddress](#adxCreatedByIPAddress)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[adxCreatedByUsername](#adxCreatedByUsername)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[displayDate](#displayDate)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[displayOrder](#displayOrder)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[hiddenFromSitemap](#hiddenFromSitemap)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[adxModifiedByIPAddress](#adxModifiedByIPAddress)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[adxModifiedByUsername](#adxModifiedByUsername)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[pageTemplateId](#pageTemplateId)|Unique identifier for Page Template associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[parentPageId](#parentPageId)|Unique identifier for Web Page associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[partialURL](#partialURL)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[subjectId](#subjectId)|Unique identifier for Subject associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[summary](#summary)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[title](#title)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[websiteId](#websiteId)|Unique identifier for Website associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[allowOrigin](#allowOrigin)|Defines CORS header Access-Control-Allow-Origin for cross origin requests.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[customCSS](#customCSS)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[customJavaScript](#customJavaScript)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[editorialComments](#editorialComments)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[enabletracking](#enabletracking)|Select whether to enable logging of users' downloads of this webpage.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[excludeFromSearch](#excludeFromSearch)|Shows whether the webpage is excluded from the portal search.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[expirationDate](#expirationDate)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[image](#image)|Unique identifier for Web File associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[imageURL](#imageURL)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[isRoot](#isRoot)|Defines whether this is the "root" record of this translated group of Web Pages.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[masterWebPageId](#masterWebPageId)|Unique identifier for Web Page associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[metaDescription](#metaDescription)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[navigation](#navigation)|Unique identifier for Web Link Set associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[publishingStateId](#publishingStateId)|Unique identifier for Publishing State associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[releaseDate](#releaseDate)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[rootWebpageId](#rootWebpageId)|Lookup to root WebPage.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[sharedPageConfiguration](#sharedPageConfiguration)|Determines if the content page uses the root page configuration|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[webpageLanguageId](#webpageLanguageId)|Language of this web page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[entityForm](#entityForm)|Unique identifier for Entity Form associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[entityList](#entityList)|Unique identifier for Entity List associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[webForm](#webForm)|Unique identifier for Web Form associated with Web Page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[commentPolicy](#commentPolicy)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[commentPolicy_display](#commentPolicy_display)||<a href="WebPage.md" target="_blank">portals/WebPage</a>|
|[enableRatings](#enableRatings)|Setting this value to 'Yes' will allow users to rate the web page.|<a href="WebPage.md" target="_blank">portals/WebPage</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#webpageId name="webpageId">webpageId</a>

Unique identifier for entity instances  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Web Page</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>adx_webpageid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Web Page  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Web Page</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Web Page  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Web Page</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Shows the name of the custom entity.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Shows the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_name</td></tr></table>

### <a href=#authorId name="authorId">authorId</a>

Unique identifier for Contact associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Author</td></tr><tr><td>description</td><td>Unique identifier for Contact associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_authorid</td></tr></table>

### <a href=#category name="category">category</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_category</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>News</td><td>1</td></tr></table></td></tr></table>

### <a href=#category_display name="category_display">category_display</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#copy name="copy">copy</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Copy</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>65536</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_copy</td></tr></table>

### <a href=#adxCreatedByIPAddress name="adxCreatedByIPAddress">adxCreatedByIPAddress</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By IP Address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_createdbyipaddress</td></tr></table>

### <a href=#adxCreatedByUsername name="adxCreatedByUsername">adxCreatedByUsername</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By Username</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_createdbyusername</td></tr></table>

### <a href=#displayDate name="displayDate">displayDate</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_displaydate</td></tr></table>

### <a href=#displayOrder name="displayOrder">displayOrder</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display Order</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_displayorder</td></tr></table>

### <a href=#hiddenFromSitemap name="hiddenFromSitemap">hiddenFromSitemap</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hidden From Sitemap</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_hiddenfromsitemap</td></tr></table>

### <a href=#adxModifiedByIPAddress name="adxModifiedByIPAddress">adxModifiedByIPAddress</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By IP Address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_modifiedbyipaddress</td></tr></table>

### <a href=#adxModifiedByUsername name="adxModifiedByUsername">adxModifiedByUsername</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By Username</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_modifiedbyusername</td></tr></table>

### <a href=#pageTemplateId name="pageTemplateId">pageTemplateId</a>

Unique identifier for Page Template associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Page Template</td></tr><tr><td>description</td><td>Unique identifier for Page Template associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_pagetemplateid</td></tr></table>

### <a href=#parentPageId name="parentPageId">parentPageId</a>

Unique identifier for Web Page associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Page</td></tr><tr><td>description</td><td>Unique identifier for Web Page associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_parentpageid</td></tr></table>

### <a href=#partialURL name="partialURL">partialURL</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partial URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_partialurl</td></tr></table>

### <a href=#subjectId name="subjectId">subjectId</a>

Unique identifier for Subject associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Unique identifier for Subject associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_subjectid</td></tr></table>

### <a href=#summary name="summary">summary</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Summary</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_summary</td></tr></table>

### <a href=#title name="title">title</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>512</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_title</td></tr></table>

### <a href=#websiteId name="websiteId">websiteId</a>

Unique identifier for Website associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Unique identifier for Website associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_websiteid</td></tr></table>

### <a href=#allowOrigin name="allowOrigin">allowOrigin</a>

Defines CORS header Access-Control-Allow-Origin for cross origin requests.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Origin</td></tr><tr><td>description</td><td>Defines CORS header Access-Control-Allow-Origin for cross origin requests.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_alloworigin</td></tr></table>

### <a href=#customCSS name="customCSS">customCSS</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom CSS</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_customcss</td></tr></table>

### <a href=#customJavaScript name="customJavaScript">customJavaScript</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom JavaScript</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_customjavascript</td></tr></table>

### <a href=#editorialComments name="editorialComments">editorialComments</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Editorial Comments</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_editorialcomments</td></tr></table>

### <a href=#enabletracking name="enabletracking">enabletracking</a>

Select whether to enable logging of users' downloads of this webpage.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Tracking (deprecated)</td></tr><tr><td>description</td><td>Select whether to enable logging of users' downloads of this webpage.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_enabletracking</td></tr></table>

### <a href=#excludeFromSearch name="excludeFromSearch">excludeFromSearch</a>

Shows whether the webpage is excluded from the portal search.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exclude From Search</td></tr><tr><td>description</td><td>Shows whether the webpage is excluded from the portal search.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_excludefromsearch</td></tr></table>

### <a href=#expirationDate name="expirationDate">expirationDate</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiration Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_expirationdate</td></tr></table>

### <a href=#image name="image">image</a>

Unique identifier for Web File associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Image</td></tr><tr><td>description</td><td>Unique identifier for Web File associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_image</td></tr></table>

### <a href=#imageURL name="imageURL">imageURL</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Image URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_imageurl</td></tr></table>

### <a href=#isRoot name="isRoot">isRoot</a>

Defines whether this is the "root" record of this translated group of Web Pages.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Root</td></tr><tr><td>description</td><td>Defines whether this is the "root" record of this translated group of Web Pages.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_isroot</td></tr></table>

### <a href=#masterWebPageId name="masterWebPageId">masterWebPageId</a>

Unique identifier for Web Page associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Master Web Page</td></tr><tr><td>description</td><td>Unique identifier for Web Page associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_masterwebpageid</td></tr></table>

### <a href=#metaDescription name="metaDescription">metaDescription</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_meta_description</td></tr></table>

### <a href=#navigation name="navigation">navigation</a>

Unique identifier for Web Link Set associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Navigation</td></tr><tr><td>description</td><td>Unique identifier for Web Link Set associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_navigation</td></tr></table>

### <a href=#publishingStateId name="publishingStateId">publishingStateId</a>

Unique identifier for Publishing State associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publishing State</td></tr><tr><td>description</td><td>Unique identifier for Publishing State associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_publishingstateid</td></tr></table>

### <a href=#releaseDate name="releaseDate">releaseDate</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Release Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_releasedate</td></tr></table>

### <a href=#rootWebpageId name="rootWebpageId">rootWebpageId</a>

Lookup to root WebPage.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Root Webpage</td></tr><tr><td>description</td><td>Lookup to root WebPage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_rootwebpageid</td></tr></table>

### <a href=#sharedPageConfiguration name="sharedPageConfiguration">sharedPageConfiguration</a>

Determines if the content page uses the root page configuration  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shared Page Configuration</td></tr><tr><td>description</td><td>Determines if the content page uses the root page configuration</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_sharedpageconfiguration</td></tr></table>

### <a href=#webpageLanguageId name="webpageLanguageId">webpageLanguageId</a>

Language of this web page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webpage Language</td></tr><tr><td>description</td><td>Language of this web page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_webpagelanguageid</td></tr></table>

### <a href=#entityForm name="entityForm">entityForm</a>

Unique identifier for Entity Form associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Form</td></tr><tr><td>description</td><td>Unique identifier for Entity Form associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_entityform</td></tr></table>

### <a href=#entityList name="entityList">entityList</a>

Unique identifier for Entity List associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity List</td></tr><tr><td>description</td><td>Unique identifier for Entity List associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_entitylist</td></tr></table>

### <a href=#webForm name="webForm">webForm</a>

Unique identifier for Web Form associated with Web Page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Web Form</td></tr><tr><td>description</td><td>Unique identifier for Web Form associated with Web Page.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_webform</td></tr></table>

### <a href=#commentPolicy name="commentPolicy">commentPolicy</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment Policy</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_feedbackpolicy</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Inherit</td><td>756150000</td></tr><tr><td>en</td><td>None</td><td>756150001</td></tr><tr><td>en</td><td>Open</td><td>756150002</td></tr><tr><td>en</td><td>Open to Authenticated Users</td><td>756150003</td></tr><tr><td>en</td><td>Moderated</td><td>756150004</td></tr><tr><td>en</td><td>Closed</td><td>756150005</td></tr></table></td></tr></table>

### <a href=#commentPolicy_display name="commentPolicy_display">commentPolicy_display</a>

First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#enableRatings name="enableRatings">enableRatings</a>

Setting this value to 'Yes' will allow users to rate the web page.  
First included in: portals/WebPage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Ratings</td></tr><tr><td>description</td><td>Setting this value to 'Yes' will allow users to rate the web page.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_enablerating</td></tr></table>
