---
title: smmKnowledgeArticleEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Knowledge articles

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/smmKnowledgeArticleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Knowledge articles</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ArticleDocument](#ArticleDocument)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|
|[ArticleItemId](#ArticleItemId)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|
|[ArticleName](#ArticleName)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|
|[ArticleURL](#ArticleURL)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|
|[ArticleMemo](#ArticleMemo)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|
|[ParentArticleItemId](#ParentArticleItemId)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|
|[ArticleSubject](#ArticleSubject)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|
|[ArticleDocumentType](#ArticleDocumentType)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|
|[BackingTable_smmEncyclopediaItemsRelationshipId](#BackingTable_smmEncyclopediaItemsRelationshipId)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="smmKnowledgeArticleEntity.md" target="_blank">SalesAndMarketing/smmKnowledgeArticleEntity</a>|

### <a href=#ArticleDocument name="ArticleDocument">ArticleDocument</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArticleDocument attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArticleItemId name="ArticleItemId">ArticleItemId</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArticleItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArticleName name="ArticleName">ArticleName</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArticleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArticleURL name="ArticleURL">ArticleURL</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArticleURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArticleMemo name="ArticleMemo">ArticleMemo</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArticleMemo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentArticleItemId name="ParentArticleItemId">ParentArticleItemId</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentArticleItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArticleSubject name="ArticleSubject">ArticleSubject</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArticleSubject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArticleDocumentType name="ArticleDocumentType">ArticleDocumentType</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArticleDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_smmEncyclopediaItemsRelationshipId name="BackingTable_smmEncyclopediaItemsRelationshipId">BackingTable_smmEncyclopediaItemsRelationshipId</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_smmEncyclopediaItemsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/smmEncyclopediaItems.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/smmEncyclopediaItems.cdm.json/smmEncyclopediaItems</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/smmEncyclopediaItems.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/smmKnowledgeArticleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
