---
title: ArticleTemplate - Common Data Model | Microsoft Docs
description: Template for a knowledge base article that contains the standard attributes of an article.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Article Template

Template for a knowledge base article that contains the standard attributes of an article.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/ArticleTemplate.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /ArticleTemplate  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[kbArticleTemplateId](#kbArticleTemplateId)|Unique identifier of the knowledge base article template.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[structureXml](#structureXml)|XML structure of the knowledge base article.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the template.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[formatXml](#formatXml)|XML format of the knowledge base article template.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[title](#title)|Title of the knowledge base article template.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[versionNumber](#versionNumber)||<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[description](#description)|Description of the knowledge base article template.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[isActive](#isActive)|Information about whether the knowledge base article is active.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the knowledge base article template.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the knowledge base article template.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[createdOn](#createdOn)|Date and time when the knowledge base article template was created.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[modifiedOn](#modifiedOn)|Date and time when the knowledge base article template was last modified.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[languageCode](#languageCode)|Language of the Article Template|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[kbArticleTemplateIdUnique](#kbArticleTemplateIdUnique)|For internal use only.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[componentState](#componentState)|For internal use only.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[componentState_display](#componentState_display)||<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[solutionId](#solutionId)|Unique identifier of the associated solution.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[overwriteTime](#overwriteTime)|For internal use only.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the kbarticletemplate.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the kbarticletemplate.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[isManaged](#isManaged)||<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[isCustomizable](#isCustomizable)|Information that specifies whether this component can be customized.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|
|[introducedVersion](#introducedVersion)|Version in which the form is introduced.|<a href="ArticleTemplate.md" target="_blank">applicationCommon/ArticleTemplate</a>|

### <a href=#kbArticleTemplateId name="kbArticleTemplateId">kbArticleTemplateId</a>

Unique identifier of the knowledge base article template.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Article Template</td></tr><tr><td>description</td><td>Unique identifier of the knowledge base article template.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>kbarticletemplateid</td></tr></table>

### <a href=#structureXml name="structureXml">structureXml</a>

XML structure of the knowledge base article.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Structure XML</td></tr><tr><td>description</td><td>XML structure of the knowledge base article.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>structurexml</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the template.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the template.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#formatXml name="formatXml">formatXml</a>

XML format of the knowledge base article template.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Format XML</td></tr><tr><td>description</td><td>XML format of the knowledge base article template.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>formatxml</td></tr></table>

### <a href=#title name="title">title</a>

Title of the knowledge base article template.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Title of the knowledge base article template.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#description name="description">description</a>

Description of the knowledge base article template.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the knowledge base article template.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#isActive name="isActive">isActive</a>

Information about whether the knowledge base article is active.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Information about whether the knowledge base article is active.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isactive</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the knowledge base article template.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the knowledge base article template.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the knowledge base article template.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the knowledge base article template.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the knowledge base article template was created.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the knowledge base article template was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the knowledge base article template was last modified.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the knowledge base article template was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#languageCode name="languageCode">languageCode</a>

Language of the Article Template  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>Language of the Article Template</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>languagecode</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#kbArticleTemplateIdUnique name="kbArticleTemplateIdUnique">kbArticleTemplateIdUnique</a>

For internal use only.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>kbarticletemplateidunique</td></tr></table>

### <a href=#componentState name="componentState">componentState</a>

For internal use only.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Component State</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>componentstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Published</td><td>0</td></tr><tr><td>en</td><td>Unpublished</td><td>1</td></tr><tr><td>en</td><td>Deleted</td><td>2</td></tr><tr><td>en</td><td>Deleted Unpublished</td><td>3</td></tr></table></td></tr></table>

### <a href=#componentState_display name="componentState_display">componentState_display</a>

First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#solutionId name="solutionId">solutionId</a>

Unique identifier of the associated solution.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Solution</td></tr><tr><td>description</td><td>Unique identifier of the associated solution.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>solutionid</td></tr></table>

### <a href=#overwriteTime name="overwriteTime">overwriteTime</a>

For internal use only.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Overwrite Time</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>overwritetime</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the kbarticletemplate.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the kbarticletemplate.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the kbarticletemplate.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the kbarticletemplate.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#isManaged name="isManaged">isManaged</a>

First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ismanaged</td></tr></table>

### <a href=#isCustomizable name="isCustomizable">isCustomizable</a>

Information that specifies whether this component can be customized.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customizable</td></tr><tr><td>description</td><td>Information that specifies whether this component can be customized.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>iscustomizable</td></tr></table>

### <a href=#introducedVersion name="introducedVersion">introducedVersion</a>

Version in which the form is introduced.  
First included in: applicationCommon/ArticleTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Introduced Version</td></tr><tr><td>description</td><td>Version in which the form is introduced.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>48</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>introducedversion</td></tr></table>
