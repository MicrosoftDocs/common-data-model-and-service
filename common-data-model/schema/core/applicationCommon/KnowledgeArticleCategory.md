---
title: KnowledgeArticleCategory - Common Data Model | Microsoft Docs
description: Category for a Knowledge Article.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Knowledge Article Category

Category for a Knowledge Article.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/KnowledgeArticleCategory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /KnowledgeArticleCategory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[knowledgeArticleId](#knowledgeArticleId)||<a href="KnowledgeArticleCategory.md" target="_blank">applicationCommon/KnowledgeArticleCategory</a>|
|[categoryId](#categoryId)||<a href="KnowledgeArticleCategory.md" target="_blank">applicationCommon/KnowledgeArticleCategory</a>|
|[knowledgeArticleCategoryId](#knowledgeArticleCategoryId)|Unique identifier of the Category for the knowledge article.|<a href="KnowledgeArticleCategory.md" target="_blank">applicationCommon/KnowledgeArticleCategory</a>|
|[versionNumber](#versionNumber)||<a href="KnowledgeArticleCategory.md" target="_blank">applicationCommon/KnowledgeArticleCategory</a>|

### <a href=#knowledgeArticleId name="knowledgeArticleId">knowledgeArticleId</a>

First included in: applicationCommon/KnowledgeArticleCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>knowledgearticleid</td></tr></table>

### <a href=#categoryId name="categoryId">categoryId</a>

First included in: applicationCommon/KnowledgeArticleCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>categoryid</td></tr></table>

### <a href=#knowledgeArticleCategoryId name="knowledgeArticleCategoryId">knowledgeArticleCategoryId</a>

Unique identifier of the Category for the knowledge article.  
First included in: applicationCommon/KnowledgeArticleCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the Category for the knowledge article.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>knowledgearticlecategoryid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

First included in: applicationCommon/KnowledgeArticleCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>
