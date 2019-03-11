---
title: Article - Common Data Model | Microsoft Docs
description: Structured content that is part of the knowledge base.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Article

Structured content that is part of the knowledge base.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Article.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/Article](../../../../Article.md "/core/applicationCommon/Article.cdm.json/Article")  
- /foundationCommon/crmCommon/solutions/portals/Article  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[kbArticleId](#kbArticleId)|Shows the ID of the article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[kbArticleTemplateId](#kbArticleTemplateId)|Choose the template that you want to use as a base for creating the new article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[subjectId](#subjectId)|Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[articleXml](#articleXml)|Shows the article content and formatting, stored as XML.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[title](#title)|Type a subject or descriptive name for the article to assist with article searches.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[number](#number)|Knowledge base article number.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[content](#content)|Description of the content of the knowledge base article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[description](#description)|Type additional information that describes the knowledge base article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[comments](#comments)|Comments regarding the knowledge base article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[createdOn](#createdOn)|Date and time when the knowledge base article was created.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the knowledge base article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the knowledge base article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[modifiedOn](#modifiedOn)|Date and time when the knowledge base article was last modified.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[stateCode](#stateCode)|Shows whether the knowledge base article is in draft, unapproved, or published status. Published articles are read-only and can't be edited unless they are unpublished.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[stateCode_display](#stateCode_display)||<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[statusCode](#statusCode)|Select the article's status.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[statusCode_display](#statusCode_display)||<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[versionNumber](#versionNumber)|Title of the knowledge base article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[keyWords](#keyWords)|Keywords to be used for searches in knowledge base articles.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the article.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the kbarticle.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[languageCode](#languageCode)|Select which language the article must be available in. This list is based on the list of language packs that are installed in your Microsoft Dynamics 365 environment.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[entityImageId](#entityImageId)|For internal use only.|<a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>|
|[publishToWeb](#publishToWeb)|If set to Yes, the article will be visible and searchable on portals connected to this organization.|<a href="Article.md" target="_blank">portals/Article</a>|
|[averageRating](#averageRating)|The average rating of this article.|<a href="Article.md" target="_blank">portals/Article</a>|
|[averageRatingWholeNumber](#averageRatingWholeNumber)|The average rating of this article, rounded to a whole number (positive integer).|<a href="Article.md" target="_blank">portals/Article</a>|
|[downvotes](#downvotes)|The number of negative vote ratings applied to this article.|<a href="Article.md" target="_blank">portals/Article</a>|
|[ratingCount](#ratingCount)||<a href="Article.md" target="_blank">portals/Article</a>|
|[ratingSum](#ratingSum)|The sum of the values of all ratings applied to this article.|<a href="Article.md" target="_blank">portals/Article</a>|
|[upvotes](#upvotes)|The number of positive vote ratings applied to this article.|<a href="Article.md" target="_blank">portals/Article</a>|

### <a href=#kbArticleId name="kbArticleId">kbArticleId</a>

Shows the ID of the article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Article</td></tr><tr><td>description</td><td>Shows the ID of the article.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>kbarticleid</td></tr></table>

### <a href=#kbArticleTemplateId name="kbArticleTemplateId">kbArticleTemplateId</a>

Choose the template that you want to use as a base for creating the new article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base Template</td></tr><tr><td>description</td><td>Choose the template that you want to use as a base for creating the new article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>kbarticletemplateid</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#subjectId name="subjectId">subjectId</a>

Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>subjectid</td></tr></table>

### <a href=#articleXml name="articleXml">articleXml</a>

Shows the article content and formatting, stored as XML.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Article XML</td></tr><tr><td>description</td><td>Shows the article content and formatting, stored as XML.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>articlexml</td></tr></table>

### <a href=#title name="title">title</a>

Type a subject or descriptive name for the article to assist with article searches.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Type a subject or descriptive name for the article to assist with article searches.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#number name="number">number</a>

Knowledge base article number.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number</td></tr><tr><td>description</td><td>Knowledge base article number.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>number</td></tr></table>

### <a href=#content name="content">content</a>

Description of the content of the knowledge base article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Content</td></tr><tr><td>description</td><td>Description of the content of the knowledge base article.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>content</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information that describes the knowledge base article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information that describes the knowledge base article.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#comments name="comments">comments</a>

Comments regarding the knowledge base article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comments</td></tr><tr><td>description</td><td>Comments regarding the knowledge base article.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>comments</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the knowledge base article was created.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the knowledge base article was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the knowledge base article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the knowledge base article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the knowledge base article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the knowledge base article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the knowledge base article was last modified.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the knowledge base article was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the knowledge base article is in draft, unapproved, or published status. Published articles are read-only and can't be edited unless they are unpublished.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status </td></tr><tr><td>description</td><td>Shows whether the knowledge base article is in draft, unapproved, or published status. Published articles are read-only and can't be edited unless they are unpublished.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>1</td></tr><tr><td>en</td><td>Unapproved</td><td>2</td></tr><tr><td>en</td><td>Published</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the article's status.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the article's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Unapproved</td><td>2</td><td>2</td></tr><tr><td>en</td><td>Published</td><td>3</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Title of the knowledge base article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Title of the knowledge base article.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#keyWords name="keyWords">keyWords</a>

Keywords to be used for searches in knowledge base articles.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Key Words</td></tr><tr><td>description</td><td>Keywords to be used for searches in knowledge base articles.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>keywords</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the article.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the kbarticle.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the kbarticle.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#languageCode name="languageCode">languageCode</a>

Select which language the article must be available in. This list is based on the list of language packs that are installed in your Microsoft Dynamics 365 environment.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>Select which language the article must be available in. This list is based on the list of language packs that are installed in your Microsoft Dynamics 365 environment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>languagecode</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

For internal use only.  
First included in: <a href="../../../../Article.md" target="_blank">applicationCommon/Article</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#publishToWeb name="publishToWeb">publishToWeb</a>

If set to Yes, the article will be visible and searchable on portals connected to this organization.  
First included in: portals/Article (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publish to Web</td></tr><tr><td>description</td><td>If set to Yes, the article will be visible and searchable on portals connected to this organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msa_publishtoweb</td></tr></table>

### <a href=#averageRating name="averageRating">averageRating</a>

The average rating of this article.  
First included in: portals/Article (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Average Rating</td></tr><tr><td>description</td><td>The average rating of this article.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_averagerating</td></tr></table>

### <a href=#averageRatingWholeNumber name="averageRatingWholeNumber">averageRatingWholeNumber</a>

The average rating of this article, rounded to a whole number (positive integer).  
First included in: portals/Article (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Average Rating (Whole Number)</td></tr><tr><td>description</td><td>The average rating of this article, rounded to a whole number (positive integer).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_averagerating_int</td></tr></table>

### <a href=#downvotes name="downvotes">downvotes</a>

The number of negative vote ratings applied to this article.  
First included in: portals/Article (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Downvotes</td></tr><tr><td>description</td><td>The number of negative vote ratings applied to this article.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_downvotes</td></tr></table>

### <a href=#ratingCount name="ratingCount">ratingCount</a>

First included in: portals/Article (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating Count</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_ratingcount</td></tr></table>

### <a href=#ratingSum name="ratingSum">ratingSum</a>

The sum of the values of all ratings applied to this article.  
First included in: portals/Article (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating Sum</td></tr><tr><td>description</td><td>The sum of the values of all ratings applied to this article.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_ratingsum</td></tr></table>

### <a href=#upvotes name="upvotes">upvotes</a>

The number of positive vote ratings applied to this article.  
First included in: portals/Article (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Upvotes</td></tr><tr><td>description</td><td>The number of positive vote ratings applied to this article.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_upvotes</td></tr></table>
