---
title: KnowledgeArticle - Common Data Model | Microsoft Docs
description: Organizational knowledge for internal and external use.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Knowledge Article

Organizational knowledge for internal and external use.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/KnowledgeArticle.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /KnowledgeArticle  
- [/foundationCommon/KnowledgeArticle](foundationCommon/KnowledgeArticle.md "/core/applicationCommon/foundationCommon/KnowledgeArticle.cdm.json/KnowledgeArticle")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[ownerId](#ownerId)|Owner Id|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[knowledgearticleId](#knowledgearticleId)|Unique identifier for entity instances|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[stateCode](#stateCode)|Shows whether the article is a draft or is published, archived, or discarded. Draft articles aren't available externally and can be edited. Published articles are available externally, based on applicable permissions, but can't be edited. All metadata changes are reflected in the published version. Archived and discarded articles aren't available externally and can't be edited.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[stateCode_display](#stateCode_display)||<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[statusCode](#statusCode)|Select the article's status.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[statusCode_display](#statusCode_display)||<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the KnowledgeArticle with respect to the base currency.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Exchange rate for the currency associated with the KnowledgeArticle with respect to the base currency.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[title](#title)|Type a title for the article.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[content](#content)|Shows the body of the article stored in HTML format.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[keyWords](#keyWords)|Type keywords to be used for searches in knowledge base articles. Separate keywords by using commas.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[publishOn](#publishOn)|Date and time when the record was published.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[expirationDate](#expirationDate)|Enter an expiration date for the article. Leave this field blank for no expiration date.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[parentArticleContentId](#parentArticleContentId)|Contains the id of the parent article content associated with the entity.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[knowledgeArticleViews](#knowledgeArticleViews)|Shows the total number of article views.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[description](#description)|A short overview of the article, primarily used in search results and for search engine optimization.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[majorVersionNumber](#majorVersionNumber)|Shows the major version number of this article's content.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[minorVersionNumber](#minorVersionNumber)|Shows the minor version number of this article's content.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[languageLocaleId](#languageLocaleId)|Select the language that the article's content is in.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[scheduledStatusId](#scheduledStatusId)|Contains the id of the scheduled status of the entity.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[expirationStatusId](#expirationStatusId)|Contains the id of the expiration status of the entity.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[publishStatusId](#publishStatusId)|Publish Status of the Article.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[isPrimary](#isPrimary)|Select whether the article is the primary article.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[readyForReview](#readyForReview)|Ready For Review|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[review](#review)|Review|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[review_display](#review_display)||<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[updateContent](#updateContent)|Update Content|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[expiredReviewOptions](#expiredReviewOptions)|Expired Review Options|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[expiredReviewOptions_display](#expiredReviewOptions_display)||<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[subjectId](#subjectId)|Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[primaryAuthorId](#primaryAuthorId)|Contains the id of the primary author associated with the article.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[isRootArticle](#isRootArticle)|Select whether the article is the root article.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[previousArticleContentId](#previousArticleContentId)|Shows the version that the current article was restored from.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[articlePublicNumber](#articlePublicNumber)|Shows the automatically generated ID exposed to customers, partners, and other external users to reference and look up articles.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[isLatestVersion](#isLatestVersion)|Shows which version of the knowledge article is the latest version.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[rootArticleId](#rootArticleId)|Contains the id of the root article.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[knowledgeArticleViewsDate](#knowledgeArticleViewsDate)|The date time for Knowledge Article View.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[knowledgeArticleViewsState](#knowledgeArticleViewsState)|State of Knowledge Article View.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[rating](#rating)|Information which specifies how helpful the related record was.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[ratingDate](#ratingDate)|The date time for Rating.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[ratingState](#ratingState)|State of Rating|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[ratingSum](#ratingSum)|Total sum of Rating|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[ratingCount](#ratingCount)|Rating Count|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[isInternal](#isInternal)|Shows whether this article is only visible internally.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[setCategoryAssociations](#setCategoryAssociations)|Shows whether category associations have been set|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|
|[expirationStateId](#expirationStateId)|Contains the id of the expiration state of the entity.|<a href="KnowledgeArticle.md" target="_blank">applicationCommon/KnowledgeArticle</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#knowledgearticleId name="knowledgearticleId">knowledgearticleId</a>

Unique identifier for entity instances  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Article</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>knowledgearticleid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the article is a draft or is published, archived, or discarded. Draft articles aren't available externally and can be edited. Published articles are available externally, based on applicable permissions, but can't be edited. All metadata changes are reflected in the published version. Archived and discarded articles aren't available externally and can't be edited.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the article is a draft or is published, archived, or discarded. Draft articles aren't available externally and can be edited. Published articles are available externally, based on applicable permissions, but can't be edited. All metadata changes are reflected in the published version. Archived and discarded articles aren't available externally and can't be edited.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>0</td></tr><tr><td>en</td><td>Approved</td><td>1</td></tr><tr><td>en</td><td>Scheduled</td><td>2</td></tr><tr><td>en</td><td>Published</td><td>3</td></tr><tr><td>en</td><td>Expired</td><td>4</td></tr><tr><td>en</td><td>Archived</td><td>5</td></tr><tr><td>en</td><td>Discarded</td><td>6</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the article's status.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the article's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Proposed</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Draft</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Needs review</td><td>3</td><td>0</td></tr><tr><td>en</td><td>In review</td><td>4</td><td>0</td></tr><tr><td>en</td><td>Approved</td><td>5</td><td>1</td></tr><tr><td>en</td><td>Scheduled</td><td>6</td><td>2</td></tr><tr><td>en</td><td>Published</td><td>7</td><td>3</td></tr><tr><td>en</td><td>Needs review</td><td>8</td><td>3</td></tr><tr><td>en</td><td>Updating</td><td>9</td><td>3</td></tr><tr><td>en</td><td>Expired</td><td>10</td><td>4</td></tr><tr><td>en</td><td>Rejected</td><td>11</td><td>4</td></tr><tr><td>en</td><td>Archived</td><td>12</td><td>5</td></tr><tr><td>en</td><td>Discarded</td><td>13</td><td>6</td></tr><tr><td>en</td><td>Rejected</td><td>14</td><td>6</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the KnowledgeArticle with respect to the base currency.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExchangeRate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the KnowledgeArticle with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Exchange rate for the currency associated with the KnowledgeArticle with respect to the base currency.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the KnowledgeArticle with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#title name="title">title</a>

Type a title for the article.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Type a title for the article.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#content name="content">content</a>

Shows the body of the article stored in HTML format.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Content</td></tr><tr><td>description</td><td>Shows the body of the article stored in HTML format.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>content</td></tr></table>

### <a href=#keyWords name="keyWords">keyWords</a>

Type keywords to be used for searches in knowledge base articles. Separate keywords by using commas.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Keywords</td></tr><tr><td>description</td><td>Type keywords to be used for searches in knowledge base articles. Separate keywords by using commas.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>keywords</td></tr></table>

### <a href=#publishOn name="publishOn">publishOn</a>

Date and time when the record was published.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publish On</td></tr><tr><td>description</td><td>Date and time when the record was published.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>publishon</td></tr></table>

### <a href=#expirationDate name="expirationDate">expirationDate</a>

Enter an expiration date for the article. Leave this field blank for no expiration date.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiration Date</td></tr><tr><td>description</td><td>Enter an expiration date for the article. Leave this field blank for no expiration date.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expirationdate</td></tr></table>

### <a href=#parentArticleContentId name="parentArticleContentId">parentArticleContentId</a>

Contains the id of the parent article content associated with the entity.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Article Content Id</td></tr><tr><td>description</td><td>Contains the id of the parent article content associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentarticlecontentid</td></tr></table>

### <a href=#knowledgeArticleViews name="knowledgeArticleViews">knowledgeArticleViews</a>

Shows the total number of article views.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Article Views</td></tr><tr><td>description</td><td>Shows the total number of article views.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>knowledgearticleviews</td></tr></table>

### <a href=#description name="description">description</a>

A short overview of the article, primarily used in search results and for search engine optimization.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>A short overview of the article, primarily used in search results and for search engine optimization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>155</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#majorVersionNumber name="majorVersionNumber">majorVersionNumber</a>

Shows the major version number of this article's content.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Major Version Number</td></tr><tr><td>description</td><td>Shows the major version number of this article's content.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>majorversionnumber</td></tr></table>

### <a href=#minorVersionNumber name="minorVersionNumber">minorVersionNumber</a>

Shows the minor version number of this article's content.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minor Version Number</td></tr><tr><td>description</td><td>Shows the minor version number of this article's content.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>minorversionnumber</td></tr></table>

### <a href=#languageLocaleId name="languageLocaleId">languageLocaleId</a>

Select the language that the article's content is in.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>Select the language that the article's content is in.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>languagelocaleid</td></tr></table>

### <a href=#scheduledStatusId name="scheduledStatusId">scheduledStatusId</a>

Contains the id of the scheduled status of the entity.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Status</td></tr><tr><td>description</td><td>Contains the id of the scheduled status of the entity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstatusid</td></tr></table>

### <a href=#expirationStatusId name="expirationStatusId">expirationStatusId</a>

Contains the id of the expiration status of the entity.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expired Status</td></tr><tr><td>description</td><td>Contains the id of the expiration status of the entity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expirationstatusid</td></tr></table>

### <a href=#publishStatusId name="publishStatusId">publishStatusId</a>

Publish Status of the Article.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Published Status</td></tr><tr><td>description</td><td>Publish Status of the Article.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>publishstatusid</td></tr></table>

### <a href=#isPrimary name="isPrimary">isPrimary</a>

Select whether the article is the primary article.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Article</td></tr><tr><td>description</td><td>Select whether the article is the primary article.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isprimary</td></tr></table>

### <a href=#readyForReview name="readyForReview">readyForReview</a>

Ready For Review  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ready For Review</td></tr><tr><td>description</td><td>Ready For Review</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>readyforreview</td></tr></table>

### <a href=#review name="review">review</a>

Review  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Review</td></tr><tr><td>description</td><td>Review</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>review</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Approved</td><td>0</td></tr><tr><td>en</td><td>Rejected</td><td>1</td></tr></table></td></tr></table>

### <a href=#review_display name="review_display">review_display</a>

First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#updateContent name="updateContent">updateContent</a>

Update Content  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update Content</td></tr><tr><td>description</td><td>Update Content</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>updatecontent</td></tr></table>

### <a href=#expiredReviewOptions name="expiredReviewOptions">expiredReviewOptions</a>

Expired Review Options  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expired Review Options</td></tr><tr><td>description</td><td>Expired Review Options</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expiredreviewoptions</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Needs Updating</td><td>0</td></tr><tr><td>en</td><td>Republish</td><td>1</td></tr><tr><td>en</td><td>Archive</td><td>2</td></tr></table></td></tr></table>

### <a href=#expiredReviewOptions_display name="expiredReviewOptions_display">expiredReviewOptions_display</a>

First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectId name="subjectId">subjectId</a>

Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subjectid</td></tr></table>

### <a href=#primaryAuthorId name="primaryAuthorId">primaryAuthorId</a>

Contains the id of the primary author associated with the article.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Author Id</td></tr><tr><td>description</td><td>Contains the id of the primary author associated with the article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primaryauthorid</td></tr></table>

### <a href=#isRootArticle name="isRootArticle">isRootArticle</a>

Select whether the article is the root article.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Root Article</td></tr><tr><td>description</td><td>Select whether the article is the root article.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isrootarticle</td></tr></table>

### <a href=#previousArticleContentId name="previousArticleContentId">previousArticleContentId</a>

Shows the version that the current article was restored from.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Previous Article Content ID</td></tr><tr><td>description</td><td>Shows the version that the current article was restored from.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>previousarticlecontentid</td></tr></table>

### <a href=#articlePublicNumber name="articlePublicNumber">articlePublicNumber</a>

Shows the automatically generated ID exposed to customers, partners, and other external users to reference and look up articles.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Article Public Number</td></tr><tr><td>description</td><td>Shows the automatically generated ID exposed to customers, partners, and other external users to reference and look up articles.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>sourceName</td><td>articlepublicnumber</td></tr></table>

### <a href=#isLatestVersion name="isLatestVersion">isLatestVersion</a>

Shows which version of the knowledge article is the latest version.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Latest Version</td></tr><tr><td>description</td><td>Shows which version of the knowledge article is the latest version.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>islatestversion</td></tr></table>

### <a href=#rootArticleId name="rootArticleId">rootArticleId</a>

Contains the id of the root article.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Root Article Id</td></tr><tr><td>description</td><td>Contains the id of the root article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rootarticleid</td></tr></table>

### <a href=#knowledgeArticleViewsDate name="knowledgeArticleViewsDate">knowledgeArticleViewsDate</a>

The date time for Knowledge Article View.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Article View(Last Updated Time)</td></tr><tr><td>description</td><td>The date time for Knowledge Article View.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>knowledgearticleviews_date</td></tr></table>

### <a href=#knowledgeArticleViewsState name="knowledgeArticleViewsState">knowledgeArticleViewsState</a>

State of Knowledge Article View.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Article View(State)</td></tr><tr><td>description</td><td>State of Knowledge Article View.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>knowledgearticleviews_state</td></tr></table>

### <a href=#rating name="rating">rating</a>

Information which specifies how helpful the related record was.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating</td></tr><tr><td>description</td><td>Information which specifies how helpful the related record was.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rating</td></tr></table>

### <a href=#ratingDate name="ratingDate">ratingDate</a>

The date time for Rating.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating(Last Updated Time)</td></tr><tr><td>description</td><td>The date time for Rating.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rating_date</td></tr></table>

### <a href=#ratingState name="ratingState">ratingState</a>

State of Rating  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating(State)</td></tr><tr><td>description</td><td>State of Rating</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rating_state</td></tr></table>

### <a href=#ratingSum name="ratingSum">ratingSum</a>

Total sum of Rating  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating(sum)</td></tr><tr><td>description</td><td>Total sum of Rating</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rating_sum</td></tr></table>

### <a href=#ratingCount name="ratingCount">ratingCount</a>

Rating Count  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating(Count)</td></tr><tr><td>description</td><td>Rating Count</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rating_count</td></tr></table>

### <a href=#isInternal name="isInternal">isInternal</a>

Shows whether this article is only visible internally.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internal</td></tr><tr><td>description</td><td>Shows whether this article is only visible internally.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isinternal</td></tr></table>

### <a href=#setCategoryAssociations name="setCategoryAssociations">setCategoryAssociations</a>

Shows whether category associations have been set  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Set Category Associations</td></tr><tr><td>description</td><td>Shows whether category associations have been set</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>setcategoryassociations</td></tr></table>

### <a href=#expirationStateId name="expirationStateId">expirationStateId</a>

Contains the id of the expiration state of the entity.  
First included in: applicationCommon/KnowledgeArticle (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiration State Id</td></tr><tr><td>description</td><td>Contains the id of the expiration state of the entity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expirationstateid</td></tr></table>
