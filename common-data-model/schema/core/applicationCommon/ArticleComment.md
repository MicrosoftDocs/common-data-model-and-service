---
title: ArticleComment - Common Data Model | Microsoft Docs
description: Comment on a knowledge base article.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Article Comment

Comment on a knowledge base article.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/ArticleComment.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /ArticleComment  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[kbArticleCommentId](#kbArticleCommentId)|Unique identifier of the knowledge base article comment.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[kbArticleId](#kbArticleId)|Unique identifier of the knowledge base article to which the comment applies.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[title](#title)|Title of the knowledge base article comment.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[commentText](#commentText)|Comment text for the knowledge base article.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[createdOn](#createdOn)|Date and time when the knowledge base article comment was created.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the knowledge base article comment.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[modifiedOn](#modifiedOn)|Date and time when the knowledge base article comment was last modified.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the knowledge base article comment.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[versionNumber](#versionNumber)||<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[organizationId](#organizationId)|Unique identifier of the organization with which the article comment is associated.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the kbarticlecomment.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the kbarticlecomment.|<a href="ArticleComment.md" target="_blank">applicationCommon/ArticleComment</a>|

### <a href=#kbArticleCommentId name="kbArticleCommentId">kbArticleCommentId</a>

Unique identifier of the knowledge base article comment.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Article Comment</td></tr><tr><td>description</td><td>Unique identifier of the knowledge base article comment.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>kbarticlecommentid</td></tr></table>

### <a href=#kbArticleId name="kbArticleId">kbArticleId</a>

Unique identifier of the knowledge base article to which the comment applies.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KB Article</td></tr><tr><td>description</td><td>Unique identifier of the knowledge base article to which the comment applies.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>kbarticleid</td></tr></table>

### <a href=#title name="title">title</a>

Title of the knowledge base article comment.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Title of the knowledge base article comment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#commentText name="commentText">commentText</a>

Comment text for the knowledge base article.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment Text</td></tr><tr><td>description</td><td>Comment text for the knowledge base article.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>commenttext</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the knowledge base article comment was created.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the knowledge base article comment was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the knowledge base article comment.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the knowledge base article comment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the knowledge base article comment was last modified.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the knowledge base article comment was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the knowledge base article comment.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the knowledge base article comment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization with which the article comment is associated.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization </td></tr><tr><td>description</td><td>Unique identifier of the organization with which the article comment is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the kbarticlecomment.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the kbarticlecomment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the kbarticlecomment.  
First included in: applicationCommon/ArticleComment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the kbarticlecomment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>
